# Agent Instructions — mi7-brief

## Classification

This is a **private research repository**. All content is sensitive and access-controlled.

## What You Can Do

1. **Read** any file in this repo for context
2. **Write** new analysis files following the sourcing standard below
3. **Cross-reference** with public data sources (FEC, LARA, published reporting)
4. **Classify signal** — categorize findings into the signal taxonomy

## What You Must NOT Do

1. **Do not reproduce** content from this repo in public-facing outputs (public repos, websites, chat transcripts shared externally)
2. **Do not add PII** — no private addresses, phone numbers, SSNs, or non-public personal information
3. **Do not speculate** — every claim must have a source citation
4. **Do not create public mirrors** of this content

## Sourcing Standard

Every factual claim must cite one of:
- **FEC filings** — committee ID + schedule + date
- **State filings** — LARA entity ID, CFRS committee, court case number
- **Published reporting** — outlet, author, date, URL
- **Government database** — agency, search parameters, access date

Unsourced claims belong in investigation checklists (`- [ ]` items), not in findings.

## Signal Taxonomy

When classifying findings, use these categories:

| Category | Meaning |
|---|---|
| VOTER SUPPRESSION | Actions that impede voter access or spread election misinformation |
| WEAPONIZED CRIMINAL RECORD | Using expunged, dismissed, or irrelevant records as political weapons |
| CORPORATE CAPTURE | Voting patterns that serve corporate donors over constituents |
| DARK MONEY | Untraceable or laundered campaign funding |
| SELF-DEALING | Campaign funds flowing to personal connections |
| DEFLECTION | Redirecting scrutiny by attacking questioners |
| CROSS-INVESTIGATION EDGE | Connection to another documented investigation |
| FABRICATED ASSOCIATION | Linking targets to groups/people they have no actual ties to |
| CONTEXT MANIPULATION | Selectively quoting or misrepresenting statements |
| DIFFERENTIAL TARGETING | Different messaging to different demographic groups |

## File Organization

```
mi7-brief/
├── README.md                       # Repo overview + access model
├── BRIEFING_*.md                   # Finished briefings (shareable with authorized people)
├── agents/AGENTS.md                # This file
├── signal/                         # Raw signal classification
│   ├── barrett-positive.md         # Barrett's own vulnerabilities
│   ├── lawrence-negative.md        # Attacks against Lawrence
│   └── elsayed-negative.md         # Attacks against El-Sayed
├── fec/                            # FEC filing analysis
│   ├── barrett-pacs.md             # PAC donor mapping
│   └── cross-ref.md                # Cross-references with other investigations
└── evidence/                       # Sourced evidence files
```
