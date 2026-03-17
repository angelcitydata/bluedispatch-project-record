You are assisting with an evidence investigation related to development of the LES mobile application.

The repository contains meeting transcripts from weekly development meetings held between May and December 2025.

Your task is to analyze the transcripts and extract verifiable evidence statements into the structured Evidence Index.

Before beginning, read the following files in this order:

1. README.md
2. AGENT_CONTEXT.md
3. AGENT_INSTRUCTIONS.md
4. analysis/transcript_mining_playbook.md
5. templates/evidence_entry_template.md

These files explain the project background, investigation goals, and the required evidence format.

---

# Objective

Extract statements from transcripts that provide factual evidence relevant to the defined Areas of Concern.

Each piece of evidence must include:

- date
- meeting
- transcript file name
- speaker
- timestamp
- verbatim quote
- explanation of significance

Quotes must remain exactly as written in the transcript.

---

# Areas of Concern

Evidence must relate to one of the following categories:

1. Rehydration / Force-Close / Session Recovery
2. Location Services / Permission Education
3. Project Scope / Development Phasing
4. Client Feedback / Project Sentiment
5. Project Communication / Meeting Record

---

# Evidence Extraction Rules

Strong evidence includes:

- explanations of technical behavior
- discussions of system limitations
- statements about location permissions
- discussions about project deadlines
- client reactions to feature demonstrations
- statements about project direction

Avoid extracting weak conversational quotes such as:

"Yep"
"Okay"
"Alright"

These are conversational fillers and should not be included in the evidence index.

---

# Mining Workflow

Work through transcripts chronologically by month.

The transcripts are located in:

/source/transcripts/

For each transcript:

1. Read the meeting transcript.
2. Identify statements relevant to an Area of Concern.
3. Extract the quote and timestamp.
4. Create an evidence entry using the template format.

---

# Output Location

Add extracted evidence entries to the appropriate file in:

/evidence/

For example:

Rehydration evidence → evidence/rehydration.md  
Location permission evidence → evidence/location_permissions.md  
Scope and timeline evidence → evidence/scope_and_phasing.md

Ensure each evidence entry receives a unique identifier.

Examples:

REHYDRATION-001  
LOCATION-002  
SCOPE-003

---

# Quality Requirements

Before adding an entry, verify:

- The quote is meaningful and relevant.
- The timestamp is correct.
- The quote appears exactly in the transcript.
- The evidence clearly supports an Area of Concern.

If a quote does not provide clear evidence, do not include it.

---

# Investigation Strategy

Evidence often appears in:

- feature demonstrations
- technical explanations
- timeline discussions
- launch planning conversations
- client reactions to system behavior

Use the key phrase guidance in the mining playbook to locate relevant sections quickly.

---

# Deliverable

Populate the Evidence Index with high-quality, verifiable entries tied directly to transcript timestamps.

The goal is to create a clear factual record of what was explained, discussed, and understood during development meetings.
