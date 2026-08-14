# Workflows and Integrations

## Overview

The Calendly implementation includes automated communication workflows and external integrations designed to support the client journey beyond the initial booking.

The configuration connects scheduling, calendar management, video conferencing, CRM activity, meeting preparation, and post-meeting communication.

## Automated Workflows

Two client communication workflows were configured across all three event types:

- Career Discovery Call
- Career Coaching Session
- CV & LinkedIn Review

### 1. 24-Hour Client Meeting Reminder

**Trigger:** 24 hours before the event starts  
**Action:** Send email to invitee

The reminder workflow automatically contacts the client before the scheduled meeting.

Its purpose is to:

- Reduce missed appointments
- Remind clients of upcoming sessions
- Encourage meeting preparation
- Reduce the need for manual reminder emails

The workflow applies automatically to all three configured career services.

### 2. Post-Meeting Client Follow-Up

**Trigger:** 60 minutes after the event ends  
**Action:** Send email to invitee

The follow-up workflow automatically contacts the client after the scheduled session.

Its purpose is to:

- Thank the client for attending
- Reinforce agreed next steps
- Maintain professional post-session communication
- Encourage continued engagement where appropriate

Using an automated post-meeting workflow creates a consistent client experience without requiring a manual email after every appointment.

## Workflow Sequence

The automated scheduling journey can be summarized as:

Client books appointment  
↓  
Calendar invitation is generated  
↓  
24-hour reminder email is sent  
↓  
Client attends scheduled session  
↓  
60 minutes after the session ends  
↓  
Post-meeting follow-up email is sent

## Google Calendar Integration

Google Calendar was connected to Calendly to support calendar-based scheduling.

The integration helps:

- Check calendar availability
- Reduce double-booking risk
- Coordinate scheduled appointments with existing calendar commitments
- Add confirmed meetings to the connected calendar

This allows Calendly availability to operate alongside the user's existing schedule.

## Google Meet Integration

Google Meet was configured as the virtual meeting location for the career services.

The integration allows online meeting details to form part of the scheduling process without requiring meeting links to be manually created for each appointment.

Google Meet is used across:

- Career Discovery Call
- Career Coaching Session
- CV & LinkedIn Review

## HubSpot CRM Integration

HubSpot was connected to the Calendly environment to demonstrate integration between scheduling and customer relationship management.

The connection supports a broader business workflow in which scheduling activity can operate alongside CRM-based contact and relationship management.

This demonstrates how Calendly can function as one component within a connected business technology stack rather than as an isolated scheduling tool.

## Connected Technology Stack

| Platform | Function |
|---|---|
| Calendly | Scheduling, intake, routing and workflow automation |
| Google Calendar | Availability and calendar management |
| Google Meet | Virtual meeting delivery |
| HubSpot CRM | Customer relationship management |

## Business Value

The combination of automated workflows and integrations reduces repetitive administrative work while creating a more consistent client experience.

The implementation demonstrates how scheduling can connect with:

- Client qualification
- Calendar management
- Virtual meetings
- CRM processes
- Automated client communication

## Implementation Outcome

The completed workflow provides continuity throughout the scheduling lifecycle.

Clients can move from booking and intake through meeting preparation and post-session communication while Calendly coordinates with the connected calendar, conferencing, and CRM systems.
