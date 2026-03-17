# Area of Concern: Rehydration / Force-Close / Session Recovery

## REHYDRATION-001

Date: Dec 30, 2025  
Meeting: Pre–go-live testing updates  
Source File: `source/transcripts/2025-12/GMT20251230-200427_Recording_otter_ai.txt`  
Speaker: Unknown Speaker  
Timestamp: 1:56

Quote

> "And this will, this could end up happening if they clock into a job and they force quit the app kind of thing before they clock out, and they try to come back in, and they try to clock back into that job, or clock into a different, you know, something else. But it's saying, Hey, you're clocked into something. It thinks you are still"

Significance

Describes a specific failure mode tied to force-quitting: the system still considers the user clocked in, blocking subsequent clock-in attempts.

## REHYDRATION-002

Date: Dec 30, 2025  
Meeting: Pre–go-live testing updates  
Source File: `source/transcripts/2025-12/GMT20251230-200427_Recording_otter_ai.txt`  
Speaker: Unknown Speaker  
Timestamp: 2:26

Quote

> "Basically, that means you can force quit the app and later try to come back and go into it, and it'll notice that you're locked clocked in and take you to that job and allow you to continue it. It's it's very tricky, and it's definitely not going to be in before go live on the 16th, but we're already right now. It's just trying to make sure that that fails as gracefully as we can make it"

Significance

Explicitly defines “rehydrate a job” as a session-recovery approach after force quit, and states it will not be delivered before the Jan 16 go-live.

## REHYDRATION-003

Date: Dec 30, 2025  
Meeting: Pre–go-live testing updates  
Source File: `source/transcripts/2025-12/GMT20251230-200427_Recording_otter_ai.txt`  
Speaker: Unknown Speaker  
Timestamp: 2:56

Quote

> "It's not going to be perfect, because if they do force quit the app, we can't continue to gather location data,"

Significance

States a concrete technical limitation: force quitting stops location collection, limiting what session recovery can do.

## REHYDRATION-004

Date: Dec 18, 2025  
Meeting: Testing feedback / edge cases  
Source File: `source/transcripts/2025-12/GMT20251218-201707_Recording_otter_ai.txt`  
Speaker: Unknown Speaker  
Timestamp: 37:56

Quote

> "that one is really for the I clocked In, but then I accidentally force closed the app"

Significance

Links the “reset button” workflow directly to an “accidentally force closed the app” scenario, i.e., an operational workaround for force-close recovery.

## REHYDRATION-005

Date: Dec 18, 2025  
Meeting: Testing feedback / edge cases  
Source File: `source/transcripts/2025-12/GMT20251218-201707_Recording_otter_ai.txt`  
Speaker: Unknown Speaker  
Timestamp: 38:02

Quote

> "that allows, if they call you with that, that allows les to kind of reset it, and allow them to clock back in."

Significance

Describes the intended recovery behavior: an internal reset enables an officer to clock back in after a force-close-related issue.
