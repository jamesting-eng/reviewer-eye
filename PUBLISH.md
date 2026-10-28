# Release Log — reviewer-eye

Dual-release iron rule: **GitHub = English, SkillHub = Chinese, same version number
on both ends.** Reference style for both ends: SemVer, decided before editing.

Version levels: PATCH = correctness/wording fixes; MINOR = new capability with old usage
intact; MAJOR = existing users must change a step.

## v2.1.2 — 2026-10-28 (first public release)

- **GitHub**: `jamesting-eng/workbuddy-skills`
- **SkillHub**: published as `reviewer-eye` v2.1.2
- **Content**: 50 checkpoints across ten sections (A–J).
- **Iron rule check**: GitHub tree 100% English, SkillHub tree 100% Chinese, no scripts.
- **Parity**: both trees carry the same 50 items at the same indices; checked by
  `package.py` before packaging.
- **Privacy scan**: clean. Removed before release: three real journal names, one
  submission-system domain, one verbatim internal quotation.

### What v2.1.2 adds over the internal v2.0.0

- **I. Journal versus design** (I47–I48): protect the research design, change the
  journal. Scope eligibility outranks formatting; length requirements must be classified
  as minimum / maximum / approximate.
- **J. Direction review** (J49–J50): after three revision rounds, re-derive the direction;
  when merging documents, recompute instead of copying.
- **F38–F40**: samples must really exist in the research setting; every content word of
  the title needs a research question; every number table must be summed and bounded.
- **H45 expanded**: the jargon scrub is no longer limited to self-coined terms — it covers
  insider jargon verbs, with the test being "would a peer actually say it", not "where is
  it written".

## Unreleased

- Nothing pending.
