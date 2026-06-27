# QA Maturity Assessment

A structured, interactive self-assessment that scores a team's QA maturity across five dimensions — grounded in ISTQB Foundation Level (CTFL 4.0) principles and the AI testing specialist syllabuses.

**[Take the assessment →](https://nataliiastetsyk.github.io/qa-maturity-assessment.html)**

---

## What it measures

Maturity isn't a tool choice. The assessment looks past the framework debate at the fundamentals that actually determine quality:

| # | Dimension | Focus |
|---|-----------|-------|
| 01 | **Test Strategy & Risk** | What you test, and why — decided by risk and business impact |
| 02 | **Test Design & Coverage** | How rigorously you derive tests and measure coverage |
| 03 | **Automation & Continuous Testing** | How much of the safety net runs in CI/CD |
| 04 | **Whole-Team Quality** | Whether quality is shared or siloed |
| 05 | **AI in Quality** | How deliberately the team uses, and tests, AI |

## How it works

- 15 statements, three per dimension
- Each rated 1 (ad hoc or absent) to 4 (consistent and by design)
- Total score 15–60, mapped to a maturity band: **Initial → Managed → Defined → Optimizing**
- Per-dimension breakdown with a tailored next step for each
- Takes about three minutes — no signup, nothing stored

## Methodology

The framework draws on ISTQB Foundation Level (CTFL 4.0) principles — shift-left testing, risk-based prioritization, and quality as a whole-team responsibility — together with the **Certified Tester AI Testing (CT-AI)** and **Testing with Generative AI (CT-GenAI)** specialist syllabuses. The AI dimension reflects both directions the field now certifies: using AI to support testing (with human oversight) and testing AI-based systems for bias, non-determinism, and model drift.

*An independent guide. Not affiliated with or endorsed by ISTQB.*

## Tech

Single-file HTML — no build step, no dependencies, no tracking. Open it locally or host it anywhere static files are served.

```bash
# run locally
open qa-maturity-assessment.html
```

## License

MIT — free to use, adapt, and share.
