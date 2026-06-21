# Style Guide v1.0

> Last revised: 2026-06-20 | Coordinator: Kal'tsit

## 0. General Principles

### 0.1 Writing Style

**The entire book is written in plain modern prose.** No classical Chinese, no archaic headings. Narrative should be clean, precise, and readable. Arguments should be evidence-based, insightful, and free of empty talk.

### 0.2 Truthfulness Principle

Every factual claim must be **traceable**:

- **Links must be accessible**: All cited URLs must be live at the time of writing. Dead links must be marked "(link no longer available)."
- **Web snapshots archived**: Important cited web pages must have snapshots saved under the `sources/` directory.
- **Cross-verification**: Key data must come from at least two independent sources. Single-source information must be marked "(unverified)."
- **Write with evidence, leave blank without.** Do not write what is uncertain. Everything written must be traceable.
- **Protect sources**: Use pseudonyms or code names to protect interviewees who do not wish to be identified. Mark as "anonymized."

### 0.3 People First

The core subject of this project is **people** — not models, not companies, not technology.

Priority order:
1. **Workers** (annotators, content moderators, data labelers, displaced professionals) — highest priority
2. **Impact events** (layoffs, industry collapses, specific cases of technological displacement) — high priority
3. **Institutions and policies** (labor law, AI regulation, union action) — medium priority
4. **Analysis and commentary** (academic research, industry reports, ethical discussions) — supplementary

## 1. Investigations

Investigations are the core of this book. Organized by topic, each piece stands independently.

### 1.1 Format

```
# [Topic Name]

> A one-paragraph summary of the key facts and significance

## I. Background
## II. Key Facts
## III. What the People Involved Say
## IV. Impact and Aftermath
## Commentary

---
Footnotes
```

### 1.2 Sources

Every key fact must cite its source:

- News reports (Time, NYT, Reuters, The Verge, etc.)
- Investigation reports (academic papers, NGO reports, government audits)
- Testimony from interviewees (label with pseudonym or "anonymous interviewee")
- Official company statements

Footnote format:
```
[^1]: Time, "OpenAI Used Kenyan Workers...", 2023-01-18. https://time.com/...
```

### 1.3 Source Protection

- Use pseudonyms or code names: e.g., "Annotator A," "Former Scale AI employee"
- Do not reveal specific work locations (unless already publicly reported)
- When citing anonymous sources from public reporting, note "as reported by [outlet]"

## 2. Impact

Documenting industries and professions disrupted by AI.

### 2.1 Format

```
# [Industry/Profession Name]

> A one-paragraph summary of the extent and timeline of disruption

## I. Before Impact: What This Profession Used to Look Like
## II. The Impact: What AI Did
## III. The Numbers: Layoffs / Income Decline / Industry Scale Changes
## IV. Cases: Specific People and Stories
## V. Response: Who Adapted, Who Left
## Commentary
```

## 3. Transitions

Documenting responses — adaptation, career change, resistance.

## 4. Essays

Independent analytical articles. 150–300 lines. Each must include a "Commentary" section.

## 5. Data

Quick-reference tables. Organized in tabular form, no narrative.

## 6. sources/ Archiving

```
sources/
├── investigations/
│   ├── kenya-labelers/
│   │   ├── time-2023-01-18.html
│   │   └── index.json
│   └── ...
├── impact/
│   └── ...
└── ...
```

## 7. Cross-References

- Investigations citing Impact cases: `See [Impact · (Industry Name)]`
- Impact citing Investigations: `See [Investigation · (Topic Name)]`
- Essays citing Investigations/Impact: `See [Investigation · (Topic Name)]`
