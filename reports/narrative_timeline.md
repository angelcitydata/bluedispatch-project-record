# Narrative Timeline (Project Delivery, Feedback, and Key Topics)

This narrative is built from:

- `analysis/transcript_index.md` (meeting-by-meeting month coverage and notes)
- `evidence/` files (timestamped quotes + “Significance” that explain why the quote matters)

## May 2025: Scope + timeline pressure (speed-to-market framing)

May began with explicit attempts to set expectations around feasibility and timelines, plus early “MVP/phasing” thinking.

On **May 5, 2025**, the client team sought a feasibility-based timeline and emphasized deadlines:

> `SCOPE-001` — “We want to set a timeline around this, what you guys think is feasible, and start working into that timeline… [to] hit our deadlines.”  
> (Source: `source/transcripts/2025-05/GMT20250505-180246_Recording_otter_ai.txt`)

Also on **May 5**, the development side pushed MVP/phasing rather than tackling everything at once:

> `SCOPE-002` — “We want our… minimal viable product… [and] break it into a couple pieces…”  
> (Source: `source/transcripts/2025-05/GMT20250505-180246_Recording_otter_ai.txt`)

As the client iterated on the scope shape, “being cognizant of time” and pivoting frequently was called out as part of how the engagement was being run:

> `SCOPE-007` — “We make a lot of changes, and we pivot, pivot. But we… want… requirements outlined…”  
> (Source: `source/transcripts/2025-05/GMT20250505-180246_Recording_otter_ai.txt`)

By **May 20**, leadership pressure around being “quick and fast” anchored the timeline stakes:

> `SCOPE-005` — “We want things quick and fast… [the] six month mark… [is] the sticking point.”  
> (Source: `source/transcripts/2025-05/GMT20250520-200331_Recording_otter_ai.txt`)

On **May 27**, the team discussed trading a quicker “scope with broader numbers” path versus a full proposal that would require discovery meetings:

> `SCOPE-006` — full proposal would “probably take at least a discovery meeting or two… It takes a little while…”  
> (Source: `source/transcripts/2025-05/GMT20250527-200227_Recording_otter_ai.txt`)

And the client pushed for a rapid decision by Friday (and cost focus):

> `SCOPE-008` — “I’m hoping by Friday’s meeting at the latest… she wants more narrow focus as to what we’re going to expect cost wise…”  
> (Source: `source/transcripts/2025-05/GMT20250527-200227_Recording_otter_ai.txt`)

The engagement never fully followed a formal “proposal + discovery + estimate” path. In an early **Jan 13, 2026** email summary of the native app project history, the team explicitly states:

> `SCOPE-004` — “we did not prepare a proposal or estimate exactly for the native app project… [and] we did not go through a proper discovery, proposal or project preparation.”  
> (Source: `source/emails/brian_overby_2026_01_13.txt`)

### May–July 2025: “burn rate” as the working basis for officer native app resourcing + estimate

In May, the team discusses “burn rate” in the context of resourcing so they can keep development moving once discovery is complete (within the same meeting where the agenda includes “officer app scheduler issues”):

On **May 16, 2025** (Speaker 2, `7:39`), they say they want to “kick up that burn rate” after discovery and explain that adding a third person would let them offer “about the same burn rate as before” (or “even a little bit more”):

> “once we start, once we finish discovery, and get on to starting the client app. You know, we want to kick up that burn rate a little bit, and this will allow us to do that, having a, having a third person helping us out, instead of just the two of us, we'll be able to offer you, offer you the probably about the same burn rate as before, or maybe even a little bit more. And otherwise we wouldn't be able to, because we've, you know, the boss is complaining that we're pushing deadlines for other clients, so this will allow us to to do that to keep a good burn rate for you guys moving Yeah.”  
> (Source: `source/transcripts/2025-05/GMT20250516-200438_Recording_otter_ai.txt`)

On **July 22, 2025**, the team ties burn rate and “hours per week” to projected estimate math and fixed-bid expectations for the **native app** (and explicitly calls out separating “native app” invoice work from other work):

- Timestamp: `46:02–46:34` (Unknown Speaker) — Quote:  
  > “to work. So if you want, can you give like a projected estimate? We understand that things are coming to play, but just leaving it open ended could be a million dollars. Oh, no, no, yeah, and I don't see that at all, like I had discussed with Joe and such before, we were looking at pushing a burn rate of somewhere between 120 and 140 in the hours per week as we hit top end. Now, we have not hit that. I don't believe we have hit 120 a week yet, but we've come pretty close, although that is including the native app and the other stuff that we're still doing, see that's what, that's what I want separated. Yeah.”
  > (Source: `source/transcripts/2025-07/GMT20250722-200252_Recording_otter_ai.txt`)

- Timestamp: `47:16–47:30` (Unknown Speaker) — Quote:  
  > “for a general number, like I was saying, even if we hit that 120 hours burn rate per week from now through the expected deadline in October, the numbers looking somewhere around, around 275 275,000”
  > (Source: `source/transcripts/2025-07/GMT20250722-200252_Recording_otter_ai.txt`)

Finally, in the Jan 13 recap email, Brian explicitly describes how “burn rate” was the closest available basis for a loosely quoted estimate (because a formal proposal/estimate was not prepared):

> “The best that was offered and discussed several times was the burn rate we hoped to meet originally. Project starting June 16th 2025 and an original hopeful go live of October 17th 2025. This is 18 weeks at the hopeful burn rate of 120-160 hours per week. This makes a loosely quoted estimate as follows:  
> Low end: 18 weeks X 120 Hours per = 2,160  hours at $225 per hour = $486,000  
> High end: 18 weeks X 160 hours per = 2,880 hours at $225 per hour = $648,000  
> Making the loosely estimated range $486,000 - $648,000.”  
> (Source: `source/emails/brian_overby_2026_01_13.txt`)

## June 2025: Native app direction + location services requirements (Always Allow education)

The June transcripts shift toward native app discovery and the practical iOS permissions needed for GPS-driven functionality.

The **first explicit “Always Allow” location-permission framing** appears on **June 25, 2025**:

> `LOCATION-001` — “always allow… location access has been enabled right.”  
> (Source: `source/transcripts/2025-06/GMT20250625-200429_Recording_otter_ai.txt`)

That same session ties onboarding messaging to app functionality: location must be enabled even though tracking is intended to be conditional in the product experience:

> `LOCATION-002` — “we really need them to enable location… even though we’re only tracking them while they’re clocked in… otherwise the app is not going to function…”  
> (Source: `source/transcripts/2025-06/GMT20250625-200429_Recording_otter_ai.txt`)

They also planned user-facing permission language that communicates the “only track… when clocked” idea:

> `LOCATION-003` — “we can give them a message… we only track you when you’re clocked into a job…”  
> (Source: `source/transcripts/2025-06/GMT20250625-200429_Recording_otter_ai.txt`)

And they clarified how the iOS system UI presents permission options:

> `LOCATION-004` — “Allow while using, and then always allow. And then… that now is enabled.”  
> (Source: `source/transcripts/2025-06/GMT20250625-200429_Recording_otter_ai.txt`)

## July 2025: Reliability work + AWS planning and operational continuity

Transcript notes for July emphasize ongoing operational/reliability challenges and AWS setup coordination:

- **July 1, 2025**: admin/job states, server instability, and reporting emails.
- **July 8, 2025**: AWS setup coordination and security/access troubleshooting (as summarized in `analysis/transcript_index.md`).
- **July 15, 2025**: SSL/cert outage postmortem and migration timeline planning.

These points set the stage for continuing “infrastructure + production readiness” work as the native app matures.

## August–September 2025: TestFlight, app handshake/login workflows, and continued AWS cutover

In the late Aug / Sep transcripts, the focus shifts toward:

- getting the right testing access in place (TestFlight),
- refining app login/handshake workflows,
- continuing AWS migration and app-specific issues.

For **TestFlight specifically**, the delivery team’s hands-on move to get the client testing access in place is captured on **Sep 15, 2025**:

> `COMMUNICATION-006` — pushing up to “test flight sometime after this meeting… you’ll have to re download the new version…”  
> (Source: `source/transcripts/2025-09/GMT20250915-160220_Recording_otter_ai.txt`)

## October 2025: Force-close behavior surfaces as a session-recovery constraint (rehydration groundwork)

Rehydration (session recovery) becomes a concrete topic when they discuss what happens when the app is force quit.

The **first rehydration/force-quit constraint captured in evidence** is **Oct 22, 2025**:

> `REHYDRATION-015` — “The only thing you can’t do is force quit the app… that kills the app from memory.”  
> (Source: `source/transcripts/2025-10/GMT20251022-200300_Recording_otter_ai.txt`)

Transcript notes also show rehydration continuing to be discussed around **Oct 29** (“rehydration after force-close…” in `analysis/transcript_index.md`).

## November 2025: Recovery Q&A clarifies what can and cannot resume after force close

By **Nov 4, 2025**, force-close behavior is treated as a known failure mode with a clear operational workaround requirement:

> `REHYDRATION-010` — “If you force close it… it’s done… [then] you guys are going to have to clock them out from file maker.”  
> (Source: `source/transcripts/2025-11/GMT20251104-200328_Recording_otter_ai.txt`)

They also distinguish force closing from normal backgrounding/multitasking:

> `REHYDRATION-012` — “force closing… ‘that week, we’ll mess things up’… switching to another app and having it in the background… shouldn’t affect anything.”  
> (Source: `source/transcripts/2025-11/GMT20251104-200328_Recording_otter_ai.txt`)

## December 2025: Hard constraints + test plans; “rehydrate a job” defined as a post-go-live goal

December includes both (a) continued technical clarifications around location behavior and (b) a structured push toward testing and launch.

On **Dec 9, 2025**, the “background GPS indicator” behavior is explained in a location-permissions context:

> `LOCATION-006` — “phone… turning on the tracking… app actually isn’t requesting and doesn’t send it back to our servers…”  
> (Source: `source/transcripts/2025-12/GMT20251209-200151_Recording_otter_ai.txt`)

On **Dec 15–16, 2025**, communication focuses on approvals and launch process:

> `COMMUNICATION-005` — questions about launch process (Apple vs Android, how the process works) + thanks  
> (Source: `source/emails/bonnie_lucas_2025_12_2025.txt`)

> `COMMUNICATION-004` — approval for soft opening + “those approvals are TOUGH!”  
> (Source: `source/emails/joe_morales_2025_12_16.txt`)

Client sentiment in this window is explicitly framed as appreciation (not dissatisfaction):

> `SENTIMENT-009` — “We also appreciate the updates… those approvals are TOUGH!”  
> (Source: `source/emails/joe_morales_2025_12_16.txt`)

### Rehydration during testing: what’s likely pre-go-live vs post-go-live

On **Dec 18, 2025**, rehydration behavior is treated as unlikely to fully land before initial go-live (for the “clocked in + closed app” scenario):

> `REHYDRATION-002` — “This most likely isn’t going to make it to go live…”  
> (Source: `source/transcripts/2025-12/GMT20251218-201707_Recording_otter_ai.txt`)

They also directly capture a non-negotiable constraint about location tracking after closing:

> `REHYDRATION-009` — “It stops tracking their location… and there’s nothing we can do about that.”  
> (Source: `source/transcripts/2025-12/GMT20251218-201707_Recording_otter_ai.txt`)

On **Dec 30, 2025**, the team defines “rehydrate a job” as a session-recovery approach after force quit, and explicitly states it will not be before go-live on Jan 16:

> `REHYDRATION-001` — “you can force quit the app… later try to come back… notice that you’re locked clocked… [it’s]… not going to be in before go live on the 16th.”  
> (Source: `source/transcripts/2025-12/GMT20251230-200427_Recording_otter_ai.txt`)

They also commit to post-go-live follow-up work:

> `REHYDRATION-003` — “working on after go live… one of the updates we want to look into after go live.”  
> (Source: `source/transcripts/2025-12/GMT20251230-200427_Recording_otter_ai.txt`)

### Structured testing and rollout communications

During late Dec, the team moves from verbal updates into formal test planning:

> `COMMUNICATION-007` — writing “a test plan” for the client to run through  
> (Source: `source/transcripts/2025-12/GMT20251223-195858_Recording_otter_ai.txt`)

> `COMMUNICATION-008` — native app test plan completed and ready to send  
> (Source: `source/transcripts/2025-12/GMT20251230-200427_Recording_otter_ai.txt`)

## Late December 2025: App is live, launch timeline reinforced, final testing positioned

A consolidated client-side “BD summary” (Dec 29) explicitly states the app is live and “on track” for full go-live on Jan 16:

> `COMMUNICATION-001` — “Current status!! The app is live… We’re on track for full go-live on January 16, 2026.”  
> (Source: `source/emails/amanda_markham_2025_12_29.txt`)

## January 2026: Go-live confirmation, client milestone sentiment, and rollout execution plan

### Early January: go-live date alignment + excitement

On **Jan 6, 2026**, PM communication confirms the go-live date and schedules a celebration:

> `COMMUNICATION-003` — “we are officially 10 days away… Launch Date: January 16, 2026… Zoom celebration meeting”  
> (Source: `source/emails/amanda_markham_2026_01_06.txt`)

In parallel, client sentiment around the launch milestone is captured in the transcript evidence:

> `SENTIMENT-004` — “This is huge milestone… we’re excited little emotional… I love it.”  
> (Source: `source/transcripts/2026-01/GMT20260106-200156_Recording_otter_ai.txt`)

### Jan 16, 2026: launch celebration + rollout strategy (“soft launch” then full blast)

The Jan 16 celebration transcript includes explicit excitement (“awesome,” “Congrats Everybody,” and “high five” energy).

Client congratulations in that day’s email thread:

> `SENTIMENT-003` — “awesome job people!”  
> (Source: `source/emails/bonnie_lucas_brian_overby_2026_01_16.txt`)

And the high-five moment in the Zoom transcript:

> `SENTIMENT-012` — “Can we high five? I’m digitally high fiving all of you.”  
> (Source: `source/transcripts/2026-01/GMT20260116-171759_Recording_otter_ai.txt`)

Rollout execution is also explicitly planned in the meeting:

> `COMMUNICATION-011` — “soft launch version right now… get them through the weekend… full on launch blast… hit everybody Monday.”  
> (Source: `source/transcripts/2026-01/GMT20260116-171759_Recording_otter_ai.txt`)

## Post-go-live (late January): fixes-first approach, but continued collaboration intent

After initial release, the client’s posture shifts into “remediation priorities first,” but also indicates intent to keep moving into the next app phases.

On **Jan 29, 2026**, Bonnie lays out preconditions for moving forward (native app issues resolved first), while still directing next-phase work:

> `SENTIMENT-001` — “Once we get all the current kinks… move forward on the Broker / Client Apps… We will connect all the moving parts soon!”  
> (Source: `source/emails/bonnie_lucas_amanda_markham_brian_overby_2026_01_29.txt`)

Amanda frames that same day as a continuation of a positive relationship and a strong milestone:

> `SENTIMENT-002` — “acknowledge what a strong milestone this has been… Congratulations… Looking forward to continuing this incredible collab!”  
> (Source: `source/emails/bonnie_lucas_amanda_markham_brian_overby_2026_01_29.txt`)

## February 2026: Rehydration delivery validation via TestFlight (app closed / forced close scenarios)

Rehydration becomes something the team is validating in distributed testing.

On **Feb 17, 2026**, transcript notes include a “rehydration demo” and related discussion themes (offline/no-signal handling, location enforcement).

On **Feb 24, 2026**, evidence shows that rehydration behavior is being verified under TestFlight builds, including app closed/reopened behavior:

> `REHYDRATION-004` — “working… no matter if I close the app or whatever… it’s working pretty good”  
> (Source: `source/transcripts/2026-02/GMT20260224-200446_Recording_otter_ai.txt`)

> `REHYDRATION-005` — listening for “close the app… open it up… nothing” failing in the tested flow  
> (Source: `source/transcripts/2026-02/GMT20260224-200446_Recording_otter_ai.txt`)

There’s also client-side attention to ongoing reliability for related “clocking in and out” behavior during rehydration testing:

> `REHYDRATION-006` — “clocking in and out… seems to be going well”  
> (Source: `source/transcripts/2026-02/GMT20260224-200446_Recording_otter_ai.txt`)

## March 2026: Rehydration update pushed (release confirmation)

On **March 2, 2026**, the client confirmation email reflects successful TestFlight validation and requests the update be pushed to production quickly:

> `REHYDRATION-008` — “We’re still testing but overall everything looks good… push this update out to tomorrow… let’s shoot for 10am our time”  
> (Source: `source/emails/joe_morales_brian_overby_2026_03_02.txt`)

And later positive client feedback is captured post-launch:

> `SENTIMENT-011` — “You’re the best! Thank you!”  
> (Source: `source/emails/joe_morales_2026_03_12.txt`)

## “First brought up” topic callouts (from evidence + transcript_index)

- **Location services (“Always Allow” education)**: first explicitly evidenced on **June 25, 2025** (`LOCATION-001` + related entries).
- **Rehydration / force-close constraints**: first explicitly evidenced on **Oct 22, 2025** (`REHYDRATION-015`).
- **Session recovery (“rehydrate a job”) delivery timing**: explicitly described as _not_ before Jan 16 go-live on **Dec 30, 2025** (`REHYDRATION-001`), then validated in TestFlight on **Feb 24, 2026** (`REHYDRATION-004` / `REHYDRATION-005`) and released following validation (**Mar 2, 2026** `REHYDRATION-008`).

## Appendix: Meeting-by-meeting transcript notes (from `analysis/transcript_index.md`)

The `Notes` text below is copied directly from `analysis/transcript_index.md` so this appendix does not introduce any new claims beyond the repository’s mined transcript notes.

| Date         | Transcript File | Notes |
| ------------ | ---------------- | ----- |
| May 5 2025   | GMT20250505-180246 | Early project discussions / scope + timeline. |
| May 6 2025   | GMT20250506-200237 | Development planning. |
| May 8 2025   | GMT20250508-200352 | Customer portal scope deep dive: validations, emergency publish, docs, performance. |
| May 13 2025  | GMT20250513-200245 | Fixes triage; GPS quirks; kickoff planning for customer portal work. |
| May 16 2025  | GMT20250516-200438 | Fixes + GPS constraints; debate native app need; meeting process reset. |
| May 19 2025  | GMT20250519-181051 | Customer portal discovery follow-up: rates/late fees, documents, timeline. |
| May 20 2025  | GMT20250520-200331 | Native app timeline pressure (“quick and fast”). |
| May 22 2025  | GMT20250522-200143 | Dev fixes status; correspondence logging; planning dev-to-prod timeline. |
| May 27 2025  | GMT20250527-200227 | Proposal vs discovery discussion. |
| May 30 2025  | GMT20250530-200122 | Native app definition-of-done / estimates. |
| June 3 2025  | GMT20250603-200201 | Jobs marked complete still active; flags/paydate/clock-out mismatch. |
| June 10 2025 | GMT20250610-200254 | Agency release logic; officer past-jobs missing; mileage report quirks. |
| June 13 2025 | GMT20250613-200222 | RFP scope review; permissions/location (geofencing); roles/SSO; AWS scaling. |
| June 17 2025 | GMT20250617-200156 | Clock in/out failures; offline messaging; native app offline-sync plan. |
| June 24 2025 | GMT20250624-200919 | Admin console bug triage (bulk assign), priorities shift, AWS instance/dev-prod planning. |
| June 25 2025 | GMT20250625-200429 | Native app discovery + GPS proof-of-concept; iOS permissions; “move fast” kickoff. |
| July 1 2025  | GMT20250701-200326 | Agency freezes/timeouts; server instability; dashboard on-hold jobs; report emails. |
| July 8 2025  | GMT20250708-200311 | AWS setup coordination; 408/401 agency errors; RFP diagrams/capacity messaging. |
| July 15 2025 | GMT20250715-200138 | SSL/cert outage postmortem; AWS progress; server migration timeline. |
| July 22 2025 | GMT20250722-200252 | Native app UI demo; filters; dark mode; improved dashboards; booking confirmation. |
| July 23 2025 | GMT20250723-173129 | Cert-cache login issues; Apple Maps inaccuracies; agency dev push readiness. |
| Aug 5 2025   | GMT20250805-200537 | FileMaker on AWS ready for testing; security hardening; TestFlight account. |
| Aug 12 2025  | GMT20250812-200151 | Coordinate-based job creation map; address verification; cross-user “my jobs” bug. |
| Aug 19 2025  | GMT20250819-200246 | AWS security containers; testing window; report fixes; mapping UX improvements. |
| Aug 26 2025  | GMT20250826-200248 | Server disk/RAM exhaustion; backup failures; scheduler usability tweaks; deployment risk. |
| Sep 2 2025   | GMT20250902-200151 | AWS security hardening; Node/FileMaker risks; bug triage; test coordination. |
| Sep 9 2025   | GMT20250909-200232 | Native app handshake; AWS capacity concerns; UI flow decisions; launch testing. |
| Sep 11 2025  | GMT20250911-210337 | SMS login workflow; AWS migration; App Store submission planning. |
| Sep 15 2025  | GMT20250915-160220 | AWS cutover readiness; FileMaker map/lat-long workflow; login UI updates. |
| Sep 16 2025  | GMT20250916-200215 | AWS security configuration; native app bugs; geofencing; TestFlight steps. |
| Sep 23 2025  | GMT20250923-200214 | AWS connectivity/SSL fallout; security rollbacks; native app priorities; testing needs. |
| Sep 30 2025  | GMT20250930-200148 | AWS stability; TestFlight crash debugging; improving location/map behavior on-device. |
| Oct 7 2025   | GMT20251007-200142 | AWS migration blocked by connectivity; TestFlight crashes; GPS demo prep. |
| Oct 14 2025  | GMT20251014-200147 | Production AWS breakage (Java/SSL); security coordination; launch dependencies. |
| Oct 22 2025  | GMT20251022-200300 | Force-close discussion. |
| Oct 29 2025  | GMT20251029-200952 | Conference recap; rehydration after force-close; SMS opt-in; AWS testing status. |
| Nov 4 2025   | GMT20251104-200328 | Force-close behavior + recovery constraints. |
| Nov 11 2025  | GMT20251111-200226 | Android parity; UTC/DST handling; notifications; AWS server “nuke/rebuild”. |
| Nov 18 2025  | GMT20251118-200225 | Notes/photos syncing; admin reset controls; privacy constraints; January target. |
| Nov 25 2025  | GMT20251125-200444 | Notifications; background tracking “island”; app icon; release-button regression. |
| Dec 9 2025   | GMT20251209-200151 | Background GPS indicator explanation. |
| Dec 18 2025  | GMT20251218-200427 | GPS trace retention / security responsibilities; pen-test and compliance topics. |
| Dec 18 2025  | GMT20251218-201604 | Google approval; soft-open strategy; FileMaker notifications; production concerns. |
| Dec 18 2025  | GMT20251218-201707 | Notifications deep-links; profile uploads; force-close failure handling improvements. |
| Dec 23 2025  | GMT20251223-195858 | Soft-open live stores; notification release; repointing test plan; clock-out anomalies. |
| Dec 30 2025  | GMT20251230-200427 | Go-live readiness / rehydration described. |
| Jan 6 2026   | GMT20260106-200156 | Go-live date confirmation / launch planning. |
| Jan 13 2026  | GMT20260113-200305 | Go-live week final prep: migrate accounts, prod tests, email/notification changes. |
| Jan 14 2026  | GMT20260114-172139 | Budget governance for next portals; fixed-cost planning; go-live support priority. |
| Jan 16 2026  | GMT20260116-171759 | Go-live celebration; client thanks team; soft-launch weekend + full “hit everybody Monday” rollout plan. |
| Jan 20 2026  | GMT20260120-200358 | Post-launch issues triage: login/clock bugs, emails, permissions, vulnerabilities. |
| Jan 27 2026  | GMT20260127-200414 | Post-launch infra hardening: server cutover, backups strategy, dev/prod planning. |
| Feb 3 2026   | GMT20260203-200426 | AWS migration; rollout/change management; tutorials; deprecating web app. |
| Feb 10 2026  | GMT20260210-200526 | Bugfixes (job timing/UTC); rehydration work; location-permission policy scenarios. |
| Feb 17 2026  | GMT20260217-200229 | Rehydration demo; offline/no-signal handling; location enforcement; dev/prod access issues. |
| Feb 24 2026  | GMT20260224-200446 | TestFlight rehydration validation; dev/prod data leakage; location-services proposal; FileMaker quirks. |
