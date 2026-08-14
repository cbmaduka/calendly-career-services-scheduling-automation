# Client Intake and Conditional Routing

## Overview

The Calendly implementation was designed to do more than provide appointment links.

Client intake forms and conditional routing were configured to collect relevant information before meetings and guide users toward the service that best matches their needs.

This creates a structured journey from initial inquiry to the appropriate booking destination.

## Career Discovery Call Intake

The Career Discovery Call serves as the initial consultation for prospective clients.

In addition to the standard name and email fields, the booking form collects:

- Current role or career stage
- The primary area in which the prospective client needs support
- How the prospective client discovered the service

These questions provide useful context before the initial consultation and support early client qualification.

## Career Coaching Session Intake

The Career Coaching Session uses a more detailed intake process because it is designed for clients requiring focused one-on-one support.

The booking form collects:

- The client's desired focus for the coaching session
- The outcome that would make the session valuable
- The client's current career priority
- Any materials or information the client would like reviewed before the meeting

Career priority options include:

- Career Transition
- Job Search Strategy
- Interview Preparation
- Professional Branding
- Career Growth
- Other

This allows the coaching session to begin with useful context already available.

## CV & LinkedIn Review Intake

The CV & LinkedIn Review uses service-specific questions to prepare for the review before the meeting begins.

The form collects:

- Whether the client requires CV review, LinkedIn review, or both
- Target roles or industries
- The client's primary concern with the current CV or LinkedIn profile
- LinkedIn profile URL where applicable

This reduces the amount of basic information gathering required during the scheduled session.

# Career Services Routing Form

A dedicated routing form was created to help visitors identify the appropriate service before selecting an appointment.

## Routing Form

**Form Name:** Career Services Consultation Router

The form collects:

- First name
- Last name
- Email address
- Type of career support required
- Current career stage
- Main career goal

## Conditional Routing Logic

The primary routing question is:

**What type of career support are you looking for?**

Based on the visitor's response, Calendly automatically directs the individual to the appropriate event type.

| Client Need | Routing Destination |
|---|---|
| Career guidance / Not sure where to start | Career Discovery Call |
| One-on-one career coaching | Career Coaching Session |
| CV & LinkedIn review | CV & LinkedIn Review |

## Routing Workflow

The implemented client journey follows this structure:

Visitor  
↓  
Career Services Consultation Router  
↓  
Client identifies support requirement  
↓  
Calendly evaluates routing condition  
↓  
Appropriate service is presented  
↓  
Client selects an available date and time  
↓  
Service-specific intake information is collected  
↓  
Meeting is scheduled

## Business Value

Conditional routing reduces the need for manual triage before scheduling.

Instead of requiring a service provider to review every inquiry and manually direct prospective clients, the routing form performs the initial qualification step automatically.

The result is a more organized booking experience in which:

- Prospective clients are directed to an introductory consultation
- Coaching clients can access the appropriate longer session
- CV and LinkedIn clients reach the specialized review service
- Relevant information is collected before the meeting

## Implementation Outcome

Combining custom intake forms with conditional routing transformed the Calendly setup from a collection of appointment links into a structured client intake and scheduling system.

The implementation demonstrates how scheduling technology can support qualification, service selection, and client preparation before a meeting begins.
