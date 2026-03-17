# Agent Instructions

Your task is to analyze meeting transcripts and extract evidence relevant to the Areas of Concern.

Evidence must be:

- factual
- verbatim
- timestamped
- traceable to the transcript source

Do not paraphrase quotes.

---

# Evidence Extraction Process

1. Read the transcript carefully.
2. Identify statements relevant to one of the Areas of Concern.
3. Capture the exact quote.
4. record the timestamp.
5. identify the speaker when possible.
6. write a short explanation of why the quote matters.

---

# Evidence Quality Rules

Strong evidence quotes typically include:

- explanations of technical behavior
- statements about permissions or system limitations
- discussions of project timeline or scope
- client reactions to features
- expressions of sentiment about the project

Avoid weak quotes such as:

"Yep"
"Okay"
"Alright"

These conversational acknowledgments do not provide meaningful evidence.

---

# Evidence Categories

All evidence entries must fall under one of these categories:

REHYDRATION  
LOCATION  
SCOPE  
SENTIMENT  
COMMUNICATION

---

# Evidence ID Format

Each entry receives a unique identifier.

Examples:

REHYDRATION-001  
LOCATION-004  
SCOPE-002

IDs should be sequential within each category.

---

# Important Rules

Evidence files must remain factual.

Do not include analysis, arguments, or speculation.

Interpretation belongs in the `/reports` folder.

---

Evidence may come from transcripts, emails, or documents.

Transcript evidence must include timestamps.

Email and document evidence should include the relevant excerpt and the source file.
