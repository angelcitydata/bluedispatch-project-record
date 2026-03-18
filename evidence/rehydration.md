# Area of Concern: Rehydration / Force-Close / Session Recovery

## REHYDRATION-001

Date: Dec 30, 2025  
Meeting: Pre–go-live testing updates  
Source File: [GMT20251230-200427_Recording_otter_ai.txt](../source/transcripts/2025-12/GMT20251230-200427_Recording_otter_ai.txt)  
Attendees: Brian Overby, Amanda Markham, Ashley Sidor  
Speaker: Brian Overby  
Timestamp: 2:17

Quote

> "We do have ideas for allowing you to what we call rehydrate a job. Basically, that means you can force quit the app and later try to come back and go into it, and it'll notice that you're locked clocked in and take you to that job and allow you to continue it. It's very tricky, and it's definitely not going to be in before go live on the 16th."

Audio: [GMT20251230-200427_REHYDRATION_001.wav](../source/audio/rehydration/GMT20251230-200427_REHYDRATION_001.wav)

Significance

Explicitly defines “rehydrate a job” as a session-recovery approach after force quit, and states it will not be delivered before the Jan 16 go-live.

## REHYDRATION-002

Date: Dec 18, 2025  
Meeting: Testing feedback / edge cases  
Source File: [GMT20251218-201707_Recording_otter_ai.txt](../source/transcripts/2025-12/GMT20251218-201707_Recording_otter_ai.txt)  
Attendees: Brian Overby, Joe Morales, Amanda Markham, Ashley Sidor  
Speaker: Brian Overby  
Timestamp: 6:47

Quote

> "This most likely isn't going to make it to go live before go live, but we are still working on more graceful ways to have the app react when somebody is clocked in and they close the app like they're definitely not supposed to"

Significance

Explicitly indicates that improved session-recovery/rehydration behavior for “clocked in + closed app” is unlikely to be ready for the initial go-live window, reinforcing that force-close handling is a known pre-launch gap.

## REHYDRATION-003

Date: Dec 30, 2025  
Meeting: Testing feedback / edge cases  
Source File: [GMT20251230-200427_Recording_otter_ai.txt](../source/transcripts/2025-12/GMT20251230-200427_Recording_otter_ai.txt)  
Attendees: Brian Overby, Amanda Markham, Ashley Sidor  
Speaker: Brian Overby  
Timestamp: 3:25

Quote

> "So but that's something we'll be working on after go live. That'll be one of the updates we want to look into after go live."

Significance

Directly states that the referenced rehydration/session-recovery improvement work was planned for **after** go-live (as a post-launch update), supporting that full rehydration handling was not part of the Jan 16 delivery scope.

## REHYDRATION-004

Date: Feb 24, 2026  
Meeting: TestFlight validation + rehydration testing  
Source File: [GMT20260224-200446_Recording_otter_ai.txt](../source/transcripts/2026-02/GMT20260224-200446_Recording_otter_ai.txt)  
Speaker: Brian Overby  
Timestamp: 4:20

Quote

> "We have been continuing to test on the test flight version ourselves. I've been doing a bunch of jobs and driving all over Hell's creation and turning it on and off and put it in airplane mode and every other thing I can think of, you know, to trip it up and such. So so far, it's gone very well, at least for me in my testing. So it's, it's working pretty good, no matter if I close the app or whatever."

Significance

Direct, timestamped statement that the rehydration behavior under TestFlight testing is performing as intended—even when the app is closed—supporting that the “rehydration after close/force-close” behavior discussed pre–go-live was implemented and being validated in the distributed TestFlight build.

## REHYDRATION-005

Date: Feb 24, 2026  
Meeting: TestFlight validation + rehydration testing  
Source File: [GMT20260224-200446_Recording_otter_ai.txt](../source/transcripts/2026-02/GMT20260224-200446_Recording_otter_ai.txt)  
Speaker: Speaker 1  
Timestamp: 43:38

Quote

> "So it doesn't sound like, you know, I'm not hearing this rehydration is not working. You know, I close the app, I open it up and I see nothing. And, you know, breaks in what we're testing, as far as that's concerned, which is good news to me."

Significance

Captures that, during TestFlight validation, the team is specifically listening for failures of the rehydration flow (“close the app… open it up”) and is not receiving reports of that breakage—evidence that the delivered TestFlight build includes and is exercising the rehydration behavior the client expected.

## REHYDRATION-006

Date: Feb 24, 2026  
Meeting: TestFlight validation + rehydration testing  
Source File: [GMT20260224-200446_Recording_otter_ai.txt](../source/transcripts/2026-02/GMT20260224-200446_Recording_otter_ai.txt)  
Speaker: Ashley Sidor  
Timestamp: 44:13

Quote

> "But other than that so far, when it comes down to clocking in and out, that seems to be going well,"

Significance

Corroborates `REHYDRATION-005` from the client side during TestFlight testing: beyond a specific reported error, Ashley reports clock in/out behavior “going well,” consistent with rehydration-related stability in the distributed build.

## REHYDRATION-007

Date: Feb 17, 2026  
Meeting: Rehydration progress + TestFlight planning  
Source File: [GMT20260217-200229_Recording_otter_ai.txt](../source/transcripts/2026-02/GMT20260217-200229_Recording_otter_ai.txt)  
Speaker: Unknown Speaker  
Timestamp: 17:29–18:13

Quote

> "we're still thinking the end of the week, right? Jake, … probably by the end of the week, we'll work on being able to get this up to test flight for you guys. … we want to make sure we get it on test flight and and allow them to put it through its paces."

Significance

Shows the team’s plan to deliver the rehydration work to the client via TestFlight for real-world validation (“put it through its paces”), i.e., the mechanism for client acceptance/testing of the rehydration behavior discussed in December.

## REHYDRATION-008

Date: March 2, 2026  
Meeting: Email (rehydration release confirmation)
Source File: [joe_morales_brian_overby_2026_03_02.txt](../source/emails/joe_morales_brian_overby_2026_03_02.txt)  
Speaker: Joe Morales  
Timestamp: March 2, 2026 at 12:15:43 PM EST

Quote

> "We’re still testing but overall everything looks good. I think we can push this update out to tomorrow, let’s shoot for 10am our time if possible."

Significance

Confirms the client’s post-TestFlight validation outcome: rehydration is “still testing” but “overall everything looks good,” and Joe requests pushing the rehydration update to production the next day—evidence that rehydration behavior was acceptable enough to release.

## REHYDRATION-009

Date: Dec 18, 2025  
Meeting: Testing feedback / edge cases  
Source File: [GMT20251218-201707_Recording_otter_ai.txt](../source/transcripts/2025-12/GMT20251218-201707_Recording_otter_ai.txt)  
Attendees: Brian Overby, Joe Morales, Amanda Markham, Ashley Sidor  
Speaker: Brian Overby  
Timestamp: 7:07

Quote

> "It stops tracking their location and stuff if they close the app, and there's nothing we can do about that."

Significance

Confirms a non-negotiable platform constraint: closing/force-closing the app stops location tracking, and the team cannot prevent or fully recover that behavior in-app—supporting why “rehydration” and related mitigations are best-effort/graceful-failure rather than guaranteed continuity.

## REHYDRATION-010

Date: Nov 4, 2025  
Meeting: Testing feedback / edge cases  
Source File: [GMT20251104-200328_Recording_otter_ai.txt](../source/transcripts/2025-11/GMT20251104-200328_Recording_otter_ai.txt)  
Speaker: Ashley Sidor & Brian Overby  
Timestamp: 29:28

Quote

> "So if you force close it and then open it back up, will it pick up where you left off? No. If you force close it, it doesn't it's done. Yeah, I get you Okay, it's done. And that's when you guys are going to have to clock them out from file maker."

Significance

Clear Q&A stating that force closing ends continuity (“it’s done”) and creates an operational need for a FileMaker-side administrative clock-out to recover.

## REHYDRATION-011

Date: Dec 30, 2025  
Meeting: Pre–go-live testing updates  
Source File: [GMT20251230-200427_Recording_otter_ai.txt](../source/transcripts/2025-12/GMT20251230-200427_Recording_otter_ai.txt)  
Attendees: Brian Overby, Amanda Markham, Ashley Sidor  
Speaker: Brian Overby  
Timestamp: 2:56

Quote

> "It's not going to be perfect, because if they do force quit the app, we can't continue to gather location data,"

Significance

States a concrete technical limitation: force quitting stops location collection, limiting what session recovery can do.

## REHYDRATION-012

Date: Nov 4, 2025  
Meeting: Testing feedback / edge cases  
Source File: [GMT20251104-200328_Recording_otter_ai.txt](../source/transcripts/2025-11/GMT20251104-200328_Recording_otter_ai.txt)  
Speaker: Brian Overby  
Timestamp: 26:02

Quote

> "Correct, as long as she doesn't swipe up. So you know, you show all your apps and then swipe one of the apps up to close it. Brand is called force closing, or force quitting. That week, we'll mess things up, and there's nothing we can really do about that, but, but switching to another app and having it in the background, nope. That shouldn't affect anything."

Significance

Distinguishes normal multitasking (backgrounding) from force closing, and explicitly ties force closing to a failure mode that “will mess things up.”

## REHYDRATION-013

Date: Dec 18, 2025  
Meeting: Testing feedback / edge cases  
Source File: [GMT20251218-201707_Recording_otter_ai.txt](../source/transcripts/2025-12/GMT20251218-201707_Recording_otter_ai.txt)  
Attendees: Brian Overby, Joe Morales, Amanda Markham, Ashley Sidor  
Speaker: Brian Overby  
Timestamp: 38:02

Quote

> "that allows, if they call you with that, that allows les to kind of reset it, and allow them to clock back in."

Significance

Describes the intended recovery behavior: an internal reset enables an officer to clock back in after a force-close-related issue.

## REHYDRATION-014

Date: Dec 18, 2025  
Meeting: Testing feedback / edge cases  
Source File: [GMT20251218-201707_Recording_otter_ai.txt](../source/transcripts/2025-12/GMT20251218-201707_Recording_otter_ai.txt)  
Attendees: Brian Overby, Joe Morales, Amanda Markham, Ashley Sidor  
Speaker: Brian Overby  
Timestamp: 37:56

Quote

> "that one is really for the I clocked In, but then I accidentally force closed the app"

Significance

Links the “reset button” workflow directly to an “accidentally force closed the app” scenario, i.e., an operational workaround for force-close recovery.

## REHYDRATION-015

Date: Oct 22, 2025  
Meeting: Testing / app behavior discussion  
Source File: [GMT20251022-200300_Recording_otter_ai.txt](../source/transcripts/2025-10/GMT20251022-200300_Recording_otter_ai.txt)  
Speaker: Jake Johnson  
Timestamp: 2:08

Quote

> "yeah, it's really cool. The only thing you can't do is force quit the app, because obviously that kills, kills the app from memory."

Significance

Directly states a key constraint tied to session recovery: force quitting terminates the app state, creating a known failure mode for ongoing jobs/tracking.

