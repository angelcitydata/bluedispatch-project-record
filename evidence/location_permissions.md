# Area of Concern: Location Services / Permission Education

## LOCATION-001

Date: June 25, 2025  
Meeting: Native app proof-of-concept (permissions + GPS)  
Source File: [GMT20250625-200429_Recording_otter_ai.txt](../source/transcripts/2025-06/GMT20250625-200429_Recording_otter_ai.txt)  
Speaker: Jake Johnson  
Timestamp: 6:15

Quote

> "and I will say, always allow. And when I go back, location access has been enabled right."

Significance

Direct, timestamped instance of “Always Allow” being presented as the setting needed to enable location access.

## LOCATION-002

Date: June 25, 2025  
Meeting: Native app proof-of-concept (permissions + GPS)  
Source File: [GMT20250625-200429_Recording_otter_ai.txt](../source/transcripts/2025-06/GMT20250625-200429_Recording_otter_ai.txt)  
Speaker: Jake Johnson  
Timestamp: 6:15

Quote

> "I think part of our onboarding, we really need them to enable location, even though we're only tracking them while they're clocked in, which I'll show you here in a second. We do need that option toggled on, otherwise the app is not going to function as you would expect it to."

Significance

Explains that onboarding must educate users to enable location permissions and ties that requirement to expected app functionality.

## LOCATION-003

Date: June 25, 2025  
Meeting: Native app proof-of-concept (permissions + GPS)  
Source File: [GMT20250625-200429_Recording_otter_ai.txt](../source/transcripts/2025-06/GMT20250625-200429_Recording_otter_ai.txt)  
Speaker: Jake Johnson  
Timestamp: 7:24

Quote

> "It's going to show allow location access, so we can give them a message of this is where we can say we only track you when you're clocked into a job, or whatever we want to say, and then we let them allow location."

Significance

Documents planned user-facing permission education language (“we only track you when you're clocked into a job”) during the system prompt.

## LOCATION-004

Date: June 25, 2025  
Meeting: Native app proof-of-concept (permissions + GPS)  
Source File: [GMT20250625-200429_Recording_otter_ai.txt](../source/transcripts/2025-06/GMT20250625-200429_Recording_otter_ai.txt)  
Speaker: Jake Johnson  
Timestamp: 7:24

Quote

> "this is a system level UI that pops up. I can say Allow while using, and then always allow. And then, boom, that now is enabled."

Significance

Clarifies the permission choice is controlled by iOS system UI (not the app), and explicitly names “Allow while using” vs “always allow.”

## LOCATION-005

Date: June 25, 2025  
Meeting: Native app proof-of-concept (geofencing + privacy discussion)  
Source File: [GMT20250625-200429_Recording_otter_ai.txt](../source/transcripts/2025-06/GMT20250625-200429_Recording_otter_ai.txt)  
Speaker: Jake Johnson  
Timestamp: 30:23

Quote

> "You know what I mean by we're not we don't track you unless you're clocked in, is we don't do anything with your location data. When you're not clocked in, it's only when you're clocked in. The app itself does have permission at an iOS settings level to it has access to their location at all times. So that's it."

Significance

Distinguishes between iOS-level permission (“access to their location at all times”) and what the app records/uses (“only when they're clocked in”).

## LOCATION-006

Date: Dec 9, 2025  
Meeting: Native app behavior / background tracking  
Source File: [GMT20251209-200151_Recording_otter_ai.txt](../source/transcripts/2025-12/GMT20251209-200151_Recording_otter_ai.txt)  
Speaker: Brian Overby  
Timestamp: 17:09

Quote

> "it's the phone actually turning on the tracking for the app and telling the app where you happen to be. The app actually isn't requesting and doesn't send it back to our servers. ... it's just kind of something that seems to be happening when you when you have background GPS turned on, which is kind of the highest level of, you know, Location Services, permissions you can have."

Significance

Explains that the blue “tracking” indicator is driven by iOS background GPS behavior, with the app not sending that location back to servers, and ties it to the highest Location Services permission level.
