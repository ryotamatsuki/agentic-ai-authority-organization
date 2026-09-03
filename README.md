# External Agentic-AI Platforms, Retained Human Recovery Capability, and the Allocation of Authority

Private research repository for the theoretical paper on external agentic-AI platforms, retained human recovery capability, platform pricing, and the allocation of authority inside firms.

## Current manuscript

- Title: *External Agentic-AI Platforms, Retained Human Recovery Capability, and the Allocation of Authority*
- Author: Ryota Matsuki
- Status: working paper / pre-submission
- Current snapshot: 2026-09-03
- Model: two-period authority-allocation model with external agentic AI, recovery-relevant human experience stock, contingency risk, and platform pricing
- Current key result: under a sufficient condition, a uniformly positive human-authority share survives across all admissible AI capability levels

## Repository structure

- `manuscript/` — canonical LaTeX source
- `notes/AI_USE_DISCLOSURE.md` — internal record of generative-AI use and journal-specific disclosure considerations
- `notes/SUBMISSION_STATUS.md` — current journal-target and submission-readiness notes
- `notes/REFEREE_RESPONSE_HISTORY.md` — mapping from prior referee-style concerns to manuscript revisions

## Build

From `manuscript/`:

```bash
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

The repository source is the canonical editable record. Compiled PDF artifacts can be regenerated from the LaTeX source.

## Reproducibility note

This is a theoretical paper and has no empirical dataset. The relevant research assets are the LaTeX manuscript, bibliography, proofs, model definitions, submission notes, and disclosure records.
