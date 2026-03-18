# Blue Dispatch Project Record

A **project record and evidence index** for the Blue Dispatch native app engagement (ACD ↔ LES). Source materials (transcripts, emails, documents) plus **timestamped, verbatim quotes**—every entry links to a specific source so statements can be verified.

---

# Quick guide: How to use this repo

**Pick your goal and go.**

| I want to…                                                       | Go here                                                                                                         |
| ---------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| **Get the big picture in one page**                              | [Executive summary](reports/executive_summary.md)                                                               |
| **See all evidence in one place (with links)**                   | [Evidence Index](evidence/evidence_index.md) — one list, every entry, by topic                                  |
| **Get a timeline of events**                                     | [Narrative timeline](reports/narrative_timeline.md)                                                             |
| **Look up scope or “what was agreed”**                           | [Scope & phasing](evidence/scope_and_phasing.md) — e.g. no formal discovery, speed-to-market                    |
| **Look up what we told the client (test plan, approvals, etc.)** | [Communication & project management](evidence/communication_and_project_management.md)                          |
| **Look up technical limitations we communicated**                | [Rehydration / force-close](evidence/rehydration.md) · [Location permissions](evidence/location_permissions.md) |
| **Look up positive client feedback**                             | [Client sentiment](evidence/client_sentiment.md)                                                                |
| **Check the original source (transcript, email, doc)**           | Each evidence entry lists its **Source File**; open that path under `source/` to verify.                        |

**One-line rule:** [Quote Index](evidence/evidence_index.md) has everything listed by category—click through to the full entry or the report you need.

---

## Reference (detail when you need it)

### Project context

**What:** Blue Dispatch officer native app (iOS/Android)—scheduling, clock in/out, location, job management. **Who:** Dev team (ACD: Brian Overby, Jake Johnson, Steve); client (LES: Joe Morales, Amanda Markham, Bonnie Lucas, Ashley). **When:** Start June 2025; go-live **Jan 16, 2026**. No formal proposal or full discovery—client prioritized **speed-to-market** ([scope evidence](evidence/scope_and_phasing.md#scope-004)).

### Repo structure

| Path                                                         | What’s in it                                                                                                                            |
| ------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------- |
| [**evidence/evidence_index.md**](evidence/evidence_index.md) | Master list of all evidence — **start here** to navigate                                                                                |
| **evidence/**                                                | One file per topic (scope, communication, rehydration, location, sentiment); each entry has quote + significance + source               |
| **source/**                                                  | Raw [transcripts](source/transcripts/), [emails](source/emails/), [documents](source/documents/) (e.g. test plan, meeting participants) |
| **reports/**                                                 | [Executive summary](reports/executive_summary.md), [findings](reports/findings.md), [narrative timeline](reports/narrative_timeline.md) |
| **analysis/**                                                | Working materials (playbooks, timelines, topic lists)                                                                                   |

### Quote categories (in the Index)

1. **Rehydration** — Force-close behavior, “rehydrate” not by go-live, reset workflow.
2. **Location** — How permissions and background location were explained.
3. **Scope** — Timeline/feasibility, MVP/phasing, no formal discovery (speed-to-market).
4. **Sentiment** — Client praise and positive feedback (verbatim).
5. **Communication** — Test plan, TestFlight, run-through/approvals, go-live confirmation.

Quotes are **fact-based and traceable**; interpretation and narrative live in [reports/](reports/).
