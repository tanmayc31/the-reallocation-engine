## 2026-10-29 — search-layer setup (personal data layer)

- **Built:** `search/resume.json`, `search/profile.yml`, `search/gaps.md`. All untracked per `DATA_CONTRACT.md` §Zero-Conditions; submitted privately via Canvas together with the full version of this log entry. `search/private-notes.md` added to `.gitignore`; `git check-ignore -v` confirms it is blocked.
- **Attestation (details in the private copy):** three import errors corrected: skills listed as shipped that were only learned; coursework-only skills listed beside production skills; a team project described as solo ownership.
- **Corrected profile.yml fields:** the agent's company-size exclusion was wrong (my real exclusion is a different constraint). The eligibility gate is marked `uncertain` until confirmed with my advisor, per the assignment's verification checklist.
- **Top gap:** LLM evaluation. **Killed row:** a gap the agent inferred from resume bullets alone, contradicted by direct work experience the resume does not state.

### Conflicts between the assignment and the repo
1. The assignment says submit `search/` in the fork; `DATA_CONTRACT.md` forbids committing real resume or immigration data, and forbids weakening `.gitignore` to allow it. Real files stay untracked and go to Canvas.
2. The assignment says write to `logs/RUN_LOG.md`; that file forbids student edits. This entry uses `logs/runs/`.

### Process note (self-report)
A first push of this entry included employer names, an application ID, and an eligibility status. A read-only audit flagged it; the branch was re-cut and force-pushed before review, per `DATA_CONTRACT.md`. No PR was opened.

- **Human gate:** tanmayc31, 2026-10-29.
