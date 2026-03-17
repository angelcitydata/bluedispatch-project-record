# Blue Dispatch Project Record

This repository is a **project record and evidence index** for the Blue Dispatch native mobile app engagement between the development team (Angel City Data / ACD) and the client (LES). It holds source materials—meeting transcripts, emails, and key documents—and **timestamped, verbatim evidence** organized by area of concern. Every evidence entry is traceable to a specific source file and location so statements can be independently verified.

---

## Executive context

**Project:** Blue Dispatch officer native app (iOS/Android) for scheduling, clock in/out, location tracking, and job management, integrated with the client’s existing FileMaker and web systems.

**Timeline:** Project start June 2025; original target go-live October 2025; actual go-live **January 16, 2026**. The engagement was run without a formal proposal, estimate, or full discovery—the client prioritized **speed-to-market** (documented in scope evidence, including a Jan 2026 email from the dev team to the client).

**Parties:**
- **Client (LES):** Joe Morales (Director of Marketing), Amanda Markham, Bonnie Lucas (President/CEO), Ashley (scheduling/testing), and others.
- **Development (ACD):** Brian Overby, Jake Johnson, Steve, and others.

**Key artifacts in this repo:** Meeting transcripts (May 2025–January 2026), client and dev team emails, the **Officer Native App Test Plan** (created by the dev team and sent to the client for run-through and approval), and the **Evidence Index** linking each finding to a specific source and timestamp.

---

## What this record is for

The record supports:

- **Verification** — Each evidence item points to a source file (transcript, email, or document) and, where applicable, timestamp or location so anyone can confirm the underlying statement.
- **Context** — Areas of concern (e.g., rehydration, location, scope, communication, sentiment) are tagged and summarized so executives can see what was said, when, and why it matters.
- **Audit trail** — Communication around TestFlight access, the test plan, final run-through/approvals (including the Jan 15, 2026 meeting), scope, and technical limitations is captured in one place.

Evidence stays **fact-based and traceable**. Interpretation and narrative conclusions live in `/reports`.

---

## Repository structure

| Path | Contents |
|------|----------|
| **`/source`** | Raw inputs: **transcripts** (by month), **emails**, and **documents** (e.g., test plan, meeting participants CSV). |
| **`/evidence`** | Categorized evidence files. Each entry includes date, source, speaker/author, verbatim quote, and significance. |
| **`/evidence/evidence_index.md`** | Master index of all evidence entries with short descriptions and links into the category files. **Start here** to navigate evidence. |
| **`/analysis`** | Working materials: transcript navigation, mining playbooks, topic lists, timelines. |
| **`/reports`** | High-level summaries, narrative timeline, and executive-facing findings. |
| **`/templates`** | Templates for evidence entries and document evidence. |

---

## Areas of concern (evidence categories)

Evidence is grouped into five categories. The **Evidence Index** lists every entry with a one-line summary and link.

1. **Rehydration / Force-Close / Session Recovery** — What happens when the app is force-closed while clocked in; “rehydrate a job” and that it would not be in by go-live; reset workflow; who must clock out from FileMaker.
2. **Location Services / Permission Education** — How location and background location are explained; “Always Allow” and onboarding; permission vs. when data is actually used.
3. **Project Scope / Development Phasing** — Client ask for feasibility-based timelines; dev proposal of MVP/phasing; FileMaker-to-web as new scope; **no formal discovery/proposal** and speed-to-market (Jan 2026 email).
4. **Client Feedback / Project Sentiment** — Verbatim positive feedback from client (e.g., “You guys are awesome,” “huge milestone,” “Thanks guys!! Great work!”) and when it was said.
5. **Project Communication / Meeting Record** — Written summaries, test plan creation and delivery (Dec 2025–Jan 2026), TestFlight access handover, run-through and final approvals (Jan 15 email chain and meeting participants), go-live confirmation, and other key decisions.

---

## How to use the evidence

- **Browse by topic:** Open [evidence/evidence_index.md](evidence/evidence_index.md). Each section (Rehydration, Location, Scope, Sentiment, Communication) lists entries with a short description and link to the full entry in the corresponding evidence file.
- **Check the source:** Every entry names a source file (e.g. `source/transcripts/2025-12/GMT20251230-200427_Recording_otter_ai.txt`) and, for transcripts, speaker and timestamp. For emails, author and date; for documents, the document path. Use that to verify the quote and context.
- **Evidence format:** Each full entry includes Date, Meeting/Source, Source File, Speaker/Author, Timestamp (if applicable), **Verbatim Quote**, and **Significance** (why it matters for that area of concern).

Conclusions and narrative belong in `/reports`; evidence in `/evidence` remains factual and source-linked.
