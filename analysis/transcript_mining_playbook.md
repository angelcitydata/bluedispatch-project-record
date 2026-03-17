# Transcript Mining Playbook

This playbook describes how agents should analyze meeting transcripts and extract high-quality evidence.

The goal is to identify statements relevant to the defined Areas of Concern and convert them into structured evidence entries.

---

# Mining Objective

Agents should extract statements that demonstrate:

- technical explanations provided to the client
- client understanding of those explanations
- project timeline decisions
- client reactions to development progress
- communication patterns during the project

All extracted evidence must be traceable to the transcript source.

---

# Areas of Concern

Evidence must relate to one of the following categories.

1. Rehydration / Force-Close / Session Recovery
2. Location Services / Permission Education
3. Project Scope / Development Phasing
4. Client Feedback / Project Sentiment
5. Project Communication / Meeting Record

---

# Transcript Mining Workflow

When reviewing a transcript:

1. Read the transcript sequentially.
2. Identify statements relevant to an Area of Concern.
3. Capture the exact quote.
4. Record the timestamp.
5. Identify the speaker when possible.
6. Create a structured evidence entry.

---

# What Good Evidence Looks Like

Strong evidence typically includes:

Technical explanations

Example:

> "The only thing you can't do is force quit the app because that kills the process."

Education of the client

Example:

> "This is where they choose Always Allow for location."

Timeline decisions

Example:

> "The deadline was based on when you wanted to go live."

Client reactions to functionality

Example:

> "This is exactly what we needed."

Project planning discussion

Example:

> "We are trying to get this live as fast as possible."

---

# Weak Evidence to Avoid

Do NOT extract quotes that are merely conversational fillers.

Examples of weak evidence:

"Yep"

"Okay"

"Alright"

"Sounds good"

"Got it"

These do not provide meaningful insight and should not be included in the Evidence Index.

---

# Where Evidence Usually Appears in Meetings

Important statements tend to appear in specific parts of meetings.

Beginning of meetings

Often includes timeline discussions, status updates, or operational goals.

Feature demonstrations

Often includes client reactions and explanations of system behavior.

Technical explanations

Often includes discussion of platform limitations and architecture.

Launch planning

Often includes statements about deadlines and readiness.

---

# Key Phrases to Watch For

Agents should pay attention to statements containing phrases like:

Technical explanations

- "the app can't"
- "the operating system"
- "iOS requires"
- "background location"

Permissions

- "Always Allow"
- "location access"
- "background GPS"

Timeline

- "deadline"
- "launch"
- "go live"
- "January"

Client sentiment

- "this is great"
- "I like that"
- "that will help"

---

# Evidence Entry Requirements

Every evidence entry must include:

Date  
Meeting  
Source transcript file  
Speaker  
Timestamp  
Quote  
Significance explanation

Quotes must be **verbatim**.

---

# Evidence Quality Check

Before adding evidence to the index, confirm:

- The quote is meaningful
- The quote relates to an Area of Concern
- The quote includes a timestamp
- The quote appears exactly in the transcript

If any of these conditions are not met, the quote should not be added.

---

# Mining Strategy

The most efficient mining strategy is:

1. Scan transcripts for key phrases.
2. Identify relevant sections.
3. Read surrounding context.
4. extract high-quality quotes.

Avoid extracting large blocks of conversation.

Focus on statements that clearly communicate a technical point, decision, or reaction.

---

# Final Goal

The Evidence Index should form a clear, verifiable record showing:

- what was explained during development
- what the client understood
- how project decisions were made
- how the client responded to progress

Every entry should help establish this factual timeline.
