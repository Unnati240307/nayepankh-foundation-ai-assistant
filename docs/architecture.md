# Architecture Overview

## System Components

### 1. Autonomous Node

Acts as the primary AI assistant responsible for:

* Understanding user queries
* Searching the Knowledge Base
* Triggering workflows when required
* Managing conversation flow

### 2. Knowledge Base

Stores verified information regarding:

* Foundation overview
* Initiatives
* Impact stories
* Donation information
* Contact details
* Volunteer opportunities

### 3. Volunteer Registration Workflow

Captures volunteer information:

User → Name → Email → Interest Area → Confirmation

### 4. Internship Recommendation Workflow

Captures internship preferences:

User → Interest Domain → Experience Level → Recommendation

## Workflow Triggering

The chatbot detects user intent and routes conversations to the appropriate workflow.

Examples:

* "I want to volunteer" → Volunteer Registration Workflow
* "I need an internship" → Internship Recommendation Workflow

## Data Flow

User Input
↓
Intent Detection
↓
Knowledge Base OR Workflow
↓
Response Generation
↓
User Interaction
