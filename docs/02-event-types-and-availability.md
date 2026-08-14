# Event Types and Availability Configuration

## Overview

The Calendly implementation uses three distinct event types to support different stages of the career services client journey.

Rather than using a single generic appointment type, each service was configured with a specific duration, purpose, and scheduling experience.

## Event Types

### 1. Career Discovery Call

**Duration:** 30 minutes  
**Location:** Google Meet

The Career Discovery Call serves as the initial entry point for prospective clients.

It allows individuals to discuss their career goals, current challenges, and support needs before selecting or proceeding with a more detailed career service.

Key configuration elements include:

- 30-minute meeting duration
- Google Meet conferencing
- Customized discovery intake questions
- Controlled advance booking
- Scheduling notice requirements
- Pre- and post-meeting buffers

---

### 2. Career Coaching Session

**Duration:** 60 minutes  
**Location:** Google Meet

The Career Coaching Session is designed for clients requiring deeper one-on-one support with areas such as:

- Career transitions
- Job search strategy
- Interview preparation
- Professional branding
- Career growth and development

The longer meeting duration allows for more detailed consultation and action planning.

The booking form also collects information about the client's primary focus, desired outcome, current priority, and materials requiring review.

---

### 3. CV & LinkedIn Review

**Duration:** 45 minutes  
**Location:** Google Meet

The CV & LinkedIn Review provides a dedicated appointment type for clients seeking professional profile and application-material feedback.

The intake process identifies:

- Whether the client requires CV review, LinkedIn review, or both
- Target roles or industries
- Current concerns with their professional materials
- LinkedIn profile information where applicable

This ensures that relevant context is collected before the review session.

## Business Availability

A structured weekly availability schedule was configured to control when appointments can be booked.

### Weekly Schedule

| Day | Availability |
|---|---|
| Monday | 09:00–17:00 |
| Tuesday | 09:00–17:00 |
| Wednesday | 09:00–17:00 |
| Thursday | 09:00–17:00 |
| Friday | 09:00–15:00 |
| Saturday | Unavailable |
| Sunday | Unavailable |

**Time Zone:** West Africa Time

## Scheduling Controls

Scheduling controls were used to create a more manageable booking environment.

These included:

- Advance scheduling restrictions
- Minimum booking notice
- Buffer periods between meetings
- Event-specific durations
- Controlled start-time increments
- Automatic invitee time-zone handling

These controls help reduce scheduling conflicts while providing clients with a clear and predictable booking experience.

## Implementation Outcome

The resulting configuration provides a structured scheduling system in which each service has a clear purpose while sharing a consistent availability framework.

This allows Calendly to function as part of the client-service workflow rather than simply as a meeting-link generator.
