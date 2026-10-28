---
name: reviewer-eye
slug: reviewer-eye
displayName: Reviewer Eye
version: "2.1.2"
summary: Reviewer-mindset self-audit for academic documents - 50 checkpoints on structure, method-evidence alignment, design feasibility, journal-versus-design priority, direction review, and AI-sounding jargon cleanup
description: |
  Use when writing, reviewing, revising, or self-auditing academic papers, research proposals,
  journal submissions, study designs, or any deliverable that will be judged by a critical human
  reviewer. Triggers include paper, submission, peer review, journal, core journal, outline,
  proposal, self-audit, self-review, desk reject, topic selection, sample, title, journal
  requirements, formatting, SSCI, SCI, ESCI, impact factor, quartile, target journal,
  change of title, change of journal, word limit, length requirement, multiple revision rounds,
  direction review, AI-sounding wording, jargon cleanup.
  Enforces reviewer-mindset self-audit: structure follows reading order, promises match content,
  methods match data, claims match evidence, samples really exist in the research setting, the
  title's every content word has a research question carrying it, research design is protected
  before journal requirements, numbers verified by addition, decisions preserved through
  rewrites, direction re-examined against sunk cost, and jargon scrubbed everywhere.
license: MIT
tags:
  - academic-writing
  - peer-review
  - self-audit
  - journal-submission
  - research-design
  - reviewer-mindset
agent_created: true
homepage: https://github.com/jamesting-eng/reviewer-eye
---

# reviewer-eye — Auditing Your Own Draft with a Reviewer's Eyes

## One-liner

Read your own manuscript with the eyes of the harshest reviewer — turn the reasons
every real audit was challenged into permanent checklist items, so the "correct"
drifts closer to the "publishable".

## Why this exists

Anything an AI produces at first pass falls short of a human's taste and logic. Between
"correct" and "good enough to submit" lies an entire spectrum of deductions (not just
fabrication and misconduct). Every item below came from a reason a real human actually
challenged during a real audit — not from armchair theorising.

## When to trigger

- Before delivering an academic document (paper / outline / grant proposal / cover letter / research plan).
- After rewriting a version, reordering sections, or expanding a candidate pool (**list the decision trace before rewriting — see H44**).
- After the title or positioning changes (a full-document consistency sweep; **after a title change, re-derive the contributions — see G41**).
- After a decision changes (make the framing follow the new state).
- After the target journal is fixed (**read the scope eligibility sentence first, then formatting — see E35**; reverse-calibration of formatting is E33).
- **When journal requirements conflict with the research design (protect the design, change the journal — see I47; this is the easiest fatal error)**.
- After a change of language or indexing system (Chinese journal ↔ SSCI/ESCI, see E36).
- **After three or more revision rounds on the same document (direction review against sunk cost — see J49)**.
- **When merging multiple documents (re-check merged content against the current design — see J50)**.
- After each revision round: tick every item; ship only when all are green.

---

## A. Structure and reading order (reader first)

1. **Document structure = the reader's reading order, not the order in which you wrote it** (title before the story, overview before everything).
2. **Sweep every cross-reference**: after any reordering, every "see §X" must be updated.
3. **Citing a deleted file = dead link**: when rewriting, any content referenced from the old version must be carried into the new one.
4. **Revision record = minimal version history**: process detail belongs in the internal log — a document for others and an internal log are two audiences, two styles.
5. **Verify before asserting**: before saying "it's all in the document", open the file and confirm. Never assert from memory.
6. **Title promise must match content positioning; a problem-driven study opens with the problem**: a "from A to B" title reads as a panorama. If the content is a problem-driven study, the title must carry the problem and the body must open with it (not a chronicle). When the title changes, update overview, body and version history together. **Deliverables that propose titles must offer a candidate set (≥3, each with positioning and rationale) — a single title marked "provisional" is not a candidate set, it is unfinished work.**
7. **Calibrate wording against academic conventions**: authorship belongs to individuals (an institution is an affiliation, not an author) — "institution as first author" is not a valid formulation. Likewise, every convention-bound statement (authorship, citation, acknowledgement, funding note) is checked item by item against convention, never replaced with everyday business language.
8. **Typesetting self-check after incremental updates**: section numbering runs wild across repeated edits (duplicate numbers, skipped numbers, out-of-order, two numbering schemes coexisting) — **after every update, grep all section headings and verify the sequence is continuous with no duplicates**; fold same-topic updates into the existing subsection instead of opening a parallel number. **The root cause of recurring typesetting failures is editing only the changed region instead of the whole document — the countermeasure is a full read or a structural grep after each round.**

## B. Completeness and promise-keeping

9. **Fill the candidate pool / ammunition store**: give the decision-maker options err-on-the-side-of-complete — writing only what they happened to name is laziness; good candidates they did not name must be surfaced too.
10. **"Anchor" resources must be mined to the list level, not the name level**: when citing a ranking or framework, extract the list, the entries, the actual numbers into the document (a name is only a citation, never the content).
11. **Highlighting saves the reader effort**: while filling the pool, add a first-pass impression mark (★) and state explicitly "initial impression only, the decision rests with the decision-maker".
12. **Deliver what you promise + structure the leads**: textual promises ("already listed / already pre-checked / see appendix") must match the tables and body — a promise exceeding the content is an ambiguous claim. Literature and case leads must be **presented structurally (table) with a per-row "value to this paper"** — flattened into prose is a loss of information density (this has been caught before).
13. **When rewriting a version, recover the old one section by section**: check every prior key judgement, criterion, conclusion and candidate list one by one — important content must not evaporate during iteration (sampling criteria, journal ladder, candidate brands, method-literature depth — every one of these has been lost this way).
14. **Persisted = the full mirror of thought**: on first delivery, every dimension, option and lineage analysed in your head must be written into the document — "I thought about it" ≠ "I wrote it". Analysis completed in the head but not persisted does not exist for the reader (evidence: a five-category journal lineage was worked out in full yet only one category reached the file, and the decision-maker caught it).
15. **Run retrievable searches proactively**: literature and evidence searches that can be completed online are executed immediately — do not wait for the decision-maker to "have time". **The completion criterion for a search task is that the resulting list is persisted into the deliverable** — "left for later" is not completion. **Make the dependency split explicit**: the deliverable must separate "deliverable now" from "pending dependency" (listed separately, with proportions), leaving no room for "can't this be written yet?".

## C. Method and evidence ("right, but not good enough" + construct boundary + method-literature mirror)

16. **Method–data mismatch**: analytical complexity exceeding what the data structure can support is a deduction (e.g. a two-variable contingency table analysed with multivariate correspondence analysis). Complexity must be earned by data complexity.
17. **Method–question mismatch**: every method step must be able to state which research question it serves; anything that cannot is deleted.
18. **Over-claiming**: the evidential strength behind each sentence must keep up — exploratory work must never write "this shows the population"; analytical inference and statistical inference are declared separately.
19. **Insufficient reliability / quality**: measurement quality is reported item by item; anything below threshold is re-coded or dropped. Manual coding has a scale ceiling — beyond it quality collapses.
20. **Missing literature dialogue**: the discussion must answer each interlocutor one by one; describing only your own work = reject.
21. **Limitation avoidance**: weaknesses go into the body verbatim — they may only be added, never hidden.
22. **Construct boundary: overlapping words are not overlapping constructs** — an included case must match the **core construct** of the research question, not merely "touch" it. "It is a cultural phenomenon" ≠ "it is the cultural adaptation this paper studies" (discursive contestation inside one cultural context and cross-cultural adaptation are two different things). The test: is the case inside the context delimited by the operational definition? However many similar cases exist, a construct mismatch is excluded — forcing it in blurs the research boundary, and the reviewer's first question is "what exactly is your core construct?".
23. **Construct avoidance across a multi-output matrix**: when one body of material is split into several papers, the core constructs and key terms of each must avoid each other (e.g. paper A uses "cultural adaptation", paper B uses "marketing localisation") — construct collision invites a duplicate-publication suspicion and also exposes the linkage between the papers.
24. **Method literature = a mirror of the method stack, plus a pre-delivery alignment check**: however many method stacks the document uses, the method-literature section must carry one reference per stack — the depth of method literature mirrors methodological completeness; a missing book is a missing piece of methodological legitimacy. **Before delivery, run the alignment check: list the method stacks, list the method references, align them one to one, fill every gap** (the same issue being flagged twice means the item exists as a principle but was not executed — it must be rewritten as a check action, not an aspiration).

## D. Ethics and compliance (red lines, no second chance)

25. Zero tolerance for fabrication and misconduct; simultaneous submission, or publishing the same study in two languages without disclosure, is disqualifying.
26. **Order of intellectual property**: file patents and software copyright first, publish second — publication destroys patent novelty.
27. **Commercially sensitive and internal reconciliation content never enters an outbound document**; people are referred to by pseudonyms and the real names are substituted by the human (the substitution itself is a content review). **Grep repeatedly for buried or deleted content on later updates** — deleting once is not the same as being permanently clean.
28. Data and material compliance: public data only, platform terms respected, factual claims anchored to public reporting.
29. **For output that must stay confidential, choose a channel outside the decision-maker's circle = physical-grade secrecy**: the journal you submit to, the platform you publish on, the venue where you disclose — these are themselves confidentiality tools. Inside the decision-maker's home circle (their field, their socially reachable channels) nothing is confidential by default.

## E. Prepare to the highest target standard

30. For any "one fish, many dishes" route (the same research programme producing multiple languages or formats), prepare materials to the **highest standard in the target sequence** (ethics statement, data availability statement, pre-registration) — "the current target doesn't require it" is not a reason to skip.
31. When a large sample or a high-end method is expected, give the legitimate path: method upgrades are driven by data upgrades, and a relay design (manual precision coding → training set → large-scale computational analysis) beats piling complexity onto the current paper.
32. **Check journal facts up front**: the moment a target journal is chosen, verify online its **review model (single/double anonymised), fees, turnaround, formatting rules (abstract/keywords/word count/AIGC statement), annual topic guidance, and whether your institution recognises it** — all public facts. Not checking at selection time and discovering them at submission time means a rewrite or wasted work. Pre-write two strategies for anonymisation (single-blind: reveal names per policy; double-blind: anonymise the body, add acknowledgements after acceptance).
33. **🔴 Reverse-calibrate against the target journal (formatting and style only)**: once the target journal is fixed, **the first action is to reverse-calibrate the outline against the official requirements** — word count (is the cap inclusive of tables?), abstract type (descriptive or structured, and its length), keyword count (and language pairing), figure/table limits, note and citation style, section preferences. Every one must be aligned in the outline; the prescribed essay starts at the outline stage — **write it right from step one, not fix it at the end**. When sources disagree (official page vs third-party claims), confirm with the editorial office before submitting. **Boundary: this item calibrates formatting and style only, not research design — if the scope eligibility sentence conflicts with your core design, go to I47 (change the journal, not the design). Never use this item as permission to reshape the design for a journal.**
34. **Journals under the same publisher share a submission system — verify one, presume the same policy for its siblings, then confirm each journal's own page** (evidence: several Chinese academic journals under one publisher share a submission system whose generative-AI prohibition is word-for-word identical — after finding it in one, presume the siblings match and confirm journal by journal rather than inferring the whole family from a single impression).
35. **🔴 The scope eligibility sentence outranks all formatting**: the first step when choosing a journal is not checking the word limit but **reading the eligibility sentence in Aims & Scope** — formatting non-compliance is a revision, scope non-compliance is a desk reject, regardless of quality. Evidence: a journal's scope explicitly requires comparisons of two or more countries or regions; a design comparing only channels or generations is out, no matter how well written. **Action**: copy the eligibility sentence verbatim into the plan and test the design against it line by line. **If it cannot be met, the first remedy is to change the journal, not the design** — adding an analytical dimension is allowed only if that dimension already had theoretical necessity in your study; otherwise go to I47.
36. **Never blur indexing tiers, and the test is not "does it have an impact factor"**: SCI/SCIE, SSCI, A&HCI and ESCI are different tiers; **since the 2023 JCR release, ESCI journals also carry impact factors and quartiles** — "ESCI has no impact factor" is outdated knowledge that a great deal of Chinese-language guidance still repeats. The real test is not metric strength but **whether your institution or funding body recognises it**: a rule saying "must be indexed in SCI/SSCI" excludes ESCI; a rule saying "must be in the Web of Science Core Collection" or "must be in CAS quartile X or above" may include it. **Action**: use one consistent indexing vocabulary outbound; the fastest way to confirm is to ask "has anyone here used this kind of paper for a grant or promotion in the last three years?".
37. **When several target journals run in parallel, take the intersection and flag the single unavoidable conflict**: compare item by item and take the intersection (the stricter word count, the shorter abstract, the smaller keyword count, the stricter review model). **The one item that usually cannot be reconciled is the reference style** — keep two style files, switch once when the journal is fixed, and never mix them mid-writing. **Action**: build a three-column table of "item × journal A × journal B × execution standard" with hard numbers in the last column.

## F. Design feasibility ("cannot be done" kills more papers than "not correct")

38. **🔴 Every candidate sample must be verified as actually existing in the research setting**: each entry in the candidate pool must be checked against the context the study delimits (region, platform, period, language) — **a brand or institution list on paper is not an available sampling frame**. Evidence: a candidate whose main market lay outside the study region was kept in the pool; the hard condition "every sample must cover every context" then emptied one cell, and that cell was the core comparison — the whole design collapsed. **Action**: before freezing the pool, verify one by one "is it genuinely active in this region/platform?"; set **Go/No-Go tiers** (meets the bar → proceed / partially meets → switch to an unbalanced design / fails → trigger a substitute context); keep the pool larger than needed (spread 8 to choose 3).
39. **🔴 Every content word of the title must have a research question carrying it**: every concept and verb in the title (especially "evolution", "mechanism", "difference", "pathway") must map to a research question, otherwise it is an empty promise and the reviewer's first question is "where is your evidence for X". Evidence: the title promised "strategic evolution" while none of the four research questions addressed evolution. **Action**: break the title into content words and annotate each with "which RQ carries it, which test supports it"; pre-plan "if the test fails, how does the second half of the title degrade" — never force the claim when the results do not support it.
40. **🔴 Every number table must be summed and checked against external bounds**: word-count allocations, sample sizes, cell counts, section budgets — **the line items must sum to the stated total**, and the total must fall inside the target journal's or the design's bounds. Evidence: line items summed to 7,800 while the total read 7,900, and it fell below the target journal's floor. **Action**: before delivering any number table, sum it and check the bounds; changing any line item means recomputing the total.

## G. Re-derivation after a change (title / journal / measurement)

41. **🔴 After a title or journal change, the research focus and the contributions must be re-derived, never re-skinned**: a new title or a new target journal usually invalidates the old contribution claims wholesale. There is one test — **can each claim survive the reviewer's "so what?"**. Three categories never count as contributions: ① "I built a framework/scale" = craft; ② "nobody has done this" = gap-filling, the weakest form; ③ "this is common sense" = no contribution. **Action**: after a title change, first write one falsifiable core proposition, then let the three contributions land on the conceptual, explanatory and mechanistic levels respectively.
42. **A change in variable type must be propagated through the whole chain**: when the measurement level of the outcome changes (categorical → continuous, or the reverse), four things must change together — one omission makes the document self-contradictory: ① the reliability index (κ suits categorical judgement only; continuous or ordinal ratings need α or ICC); ② the statistical model (multinomial logistic ↔ linear mixed); ③ the sample-size argument (chi-square expected frequencies ↔ precision of cell means); ④ the coding-manual decision rules ("assign exactly one type" ↔ "score dimensions independently").
43. **Pre-plan remedies for too few clustering units**: when the level-2 unit count in a multilevel model is below the usual recommendation (roughly ≥20), the analysis can still proceed, but three things must be reported together and written into the limitations — cluster-robust standard errors, a level-2 fixed-effects sensitivity check, and effect size plus attenuation magnitude as the primary criteria (never p-values alone).

## H. Rewriting and expression (don't lose the decisions, don't lose the reader)

44. **🔴 Before rewriting a long document, list the decision trace**: enumerate the blocks in the previous version that are **decisions rather than derivations** and confirm each one is kept or replaced — typical entries: roadmap and milestones, the path to outcomes, linkage with your own assets or product, compliance and conflict-of-interest statements, agreed conventions. **Methods can be re-derived; decisions cannot be rebuilt.** Evidence: a rewrite silently dropped the entire "paper → grant → follow-on papers" roadmap and the "mutual value between the paper and our own product + disclosure rules" block, and the decision-maker flagged both as must-restore.
45. **Self-coined terminology is banned, and jargon must be scrubbed**: never invent two-step terms of the "first X / then Y" kind that make the reader stop and guess the difference — replace them with action sentences. Evidence: "pre-coding / post-coding" drew the challenge "this is unreadable, can you write like a human?" — rewritten as "step one: record what you see / step two: assign scores", it became immediately readable.
    **The same scrub applies to insider jargon verbs**: leverage, empower, align, close the loop, feed back, land, unlock, granularity, mindset, playbook, lever, underlying logic, sediment, potential energy, breakthrough, combo, single chessboard, top-level design — and "ecosystem" used as a universal suffix. These are sometimes legitimate in a paper body (disciplinary terms), but **in a plan written for a collaborator they make it read as machine-written**. Evidence: a collaborator said outright that one adaptation-flavoured term "is not a phrase humans use in normal conversation, it looks very AI"; subsequently some twenty instances of adaptation / displacement / loop-closing / feeding back / landing / unlocking / iteration / hard-coding were removed in one pass.
    **The test is not "where is it written" but "would a peer in this field actually say it"** — do not grant jargon a "legitimate inside a paper" exemption; in a paper body it looks just as fake. Three categories:
    - ① **Established disciplinary terms** (reliability, validity, scale, attribution, mediation effect, platform logic, content adaptation): peers really say these; usable in both papers and plans.
    - ② **Internet / management jargon** (leverage, empower, align, close the loop, feed back, unlock, granularity, mindset, playbook, lever, underlying logic, sediment, potential energy, breakthrough, combo, single chessboard, top-level design; plus "ecosystem" as a universal suffix such as "content ecosystem", "platform ecosystem"): **never use these anywhere**.
    - ③ **Pseudo-academic words** (adaptation-as-jargon, displacement, downgrade, land as a verb, hold up, hard-code): unless the field has a real definition, replace with action sentences — adapt → adjust or localise; displacement → change; land → become; hold up → withstand scrutiny; hard-code → decide in advance; close the loop → cycle; feed back → support; unlock → work across.
    **The test: can you read this sentence aloud without wincing?**
46. **For research involving your own tool or product, three compliance actions**: ① the method section carries a functional description only (1–2 sentences), with no product positioning, selling points, pricing, competitor comparison or marketing vocabulary; ② the cover letter does not sell it; ③ **if any author is affiliated with the developer, a conflict-of-interest statement must be written proactively** — hiding it is far riskier than disclosing it; contributions are declared under CRediT as they stand.

## I. Journal versus design: which comes first

47. **🔴 When a journal requirement conflicts with the core design, change the journal, not the design — the highest-priority item in this skill**: after reading a target journal's scope and formatting rules, run one conflict test — **would complying shift the subject, the object of study, or the research questions?** If yes, change the journal. If no (word count, style, formatting, section preferences), change the manuscript. **A journal is a submission channel, not the legislature of your research direction.**
    - **Action 1 (before reading the journal)**: write down the **non-negotiable list** — the title, the subject of the core proposition, the core construct, the subject and number of the research questions, the nature of the sample. No journal requirement may touch anything on this list.
    - **Action 2 (after reading the journal)**: sort every requirement into "style" (comply) and "design" (change the journal if touched).
    - **Action 3 (before switching)**: verify that the replacement candidate genuinely lacks the same requirement — do not jump from one trap into another.
    - **Evidence**: a journal's scope hard-required comparisons of two or more countries or regions. To satisfy it, a regional comparison dimension was added; the subject of the core proposition shifted from "generational difference" to "platform structure and region", **generational difference was demoted to a residual to be excluded**, the paper's strongest contribution was diluted (from "these two factors have never shared a model" to a more common three-way design), the data collection doubled, and a sample-availability risk was introduced. To squeeze into one journal, the paper became a different paper. The correct remedy: drop the dimension, verify another SSCI journal has no such requirement, and switch journals — the design was unchanged and the off-topic problem disappeared.
    - **Mnemonic**: **the journal can change; the proposition cannot.**
48. **Length requirements must be quoted verbatim and labelled as minimum / maximum / approximate**: the wording differs in kind — "should be **about** A–B" is an approximate range (neither a hard floor nor a ceiling); "should **not normally exceed** C" is a soft ceiling; "minimum of D" is a hard floor. **Recording it loosely as "this journal requires N words" causes misjudgement**, and it is fatal when several journals run in parallel.
    - **Action**: ① quote the original sentence into the plan; ② label its nature; ③ with parallel journals, take the intersection and verify the arithmetic (line items must sum to the total, and the total must fall inside the intersection); ④ check what is counted — inclusive or exclusive of figures, tables, captions, appendices — the same manuscript has different counts under different journals' definitions.

## J. Direction review (against sunk cost)

49. **🔴 After three revision rounds, run a direction review; never defend the status quo just because of what has been invested**: iteration makes details sharper, but **polish cannot substitute for a correct direction**. The more rounds you have done, the easier it is to mistake "we have built a lot" for "the direction is right".
    - **Triggers**: three or more revision rounds on the same document; a request for an adversarial review; or the symptom "it keeps getting more complex but nobody asks why any more".
    - **Action 1**: lay the original direction (title, core proposition, core construct) side by side with the current version, item by item.
    - **Action 2**: for each item ask "**if I started from zero today, would I still design it this way?**".
    - **Action 3**: identify **the one premise in the current version you have never questioned** — that premise is usually the source of the error (typically something added early on to satisfy an external constraint and later treated as an axiom).
    - **Evidence**: several rounds of iteration had made one dimension extremely refined (scales, robustness checks, a two-form test, statistical remedies), but that dimension itself was added to accommodate a journal's scope — the craft was good on a wrong foundation. The decision-maker broke it open with a remark that the direction itself was wrong and only the decoration had improved, and after checking item by item the challenge held in full. **At the time the defence was "this follows the new design" — which was in fact decorating the wrong direction.**
50. **When merging documents, recompute the merged content against the current design — never copy it over**: the point of merging is "review one file", not "move the content". Before merging, ask of each item "**does this still hold under the current design?**" — if yes, merge it; if not, rewrite it and mark why it changed (so the reader knows why it is not the original sentence).
    - **Evidence**: when the research focus and contributions from a separate submission plan were merged into the main plan, two items no longer held — ① "set A and B as two competing explanations" (the current design had changed, so both the number and the meaning were wrong); ② "evolution = continually revising strategy on audience feedback" (the current data contain no audience side, so the feedback link cannot be detected, and copying it over would be over-claiming). Had they been copied verbatim, the contradiction between the two documents would have been visible to any reviewer.

## Output conventions

- **Push back and offer a path**: when the decision-maker asks for something that violates methodological principle, push back with a retrievable empirical benchmark (do not appease), and at the same time give the legitimate way to achieve the wish (e.g. a relay design), so that "correct" does not become a bucket of cold water.
- **Three-step refusal**: when refusing a proposal — ① first acknowledge the part that is academically right (not perfunctorily); ② sharpen the boundary of the reason (which construct, which criterion); ③ convert the valuable part of the proposal into a legitimate destination (a follow-on topic / a backup pool / future material). Refusal ≠ blanket rejection.
- **Framing follows the decision state**: a "dilemma / conflict / versus" framing in the document is downgraded to a neutral "arrangement / two-step" the moment the decision is made, and the adversarial wording is cleaned up alongside — settled matters should not survive in dramatised form.
- **A plan document is also an alignment channel**: a research plan or outline written for a collaborator is not only for writing — it is the channel through which matters are aligned and confirmed. Plant the "to be decided" items explicitly (candidates marked "first author decides", tiers marked "first author weighs"), so the collaborator knows what to sign off on.
- **Self-audit delivery format**: findings graded (fatal / should-fix / minor) + items already fixed + items left to the decision-maker.
- **Two documents, separated**: the document for the decision-maker (clean, in reading order, minimal version history) and the internal reconciliation document (physically separate, file name marked "not for external distribution").

## Inclusion criteria (three hard tests)

1. **Real evidence**: the item was challenged by a human in a real audit.
2. **Non-obvious**: without reading it you would step on it.
3. **Recurrent across projects**: after generalisation it applies to any academic document — "the example looks like this project" is not a reason to reject, generalise it instead.

## Maintenance (living skill)

- After every audit or revision round: generalise the new challenge → append the corresponding item → bump the version.
- When the wording of an item is challenged as imprecise: fix the wording rather than deleting the item (e.g. "showing off method" → "method–data mismatch").
- **Interrupted operations must be verified by reading back**: after an edit or command is cancelled or interrupted, the actual state cannot be assumed — immediately Read the target file to check for partial or leftover changes (interrupted ≠ not executed).
- Log finding and fix records in the working log and feed them back into this skill.
- **Append discipline for logs**: when appending to an append-only log, never anchor on "the end of the previous entry" and replace; after each append, immediately read back and verify the previous entry is intact.
- **Version-bump trigger = structural change**: structural redesign / repositioning / genre reordering = major version; local additions = minor version; multiple changes in one day count as a single jump — **do not wait for the user to point it out; after each delivery ask yourself "is this round a structural change?"**.
- **🔴 Zero tolerance for "said but not done"**: before telling the decision-maker "added / restored / executed", **you must grep or Read the target file to confirm the actual state** — claiming completion ≠ completion. Every historical instance of "said but not done" in this skill came from asserting completion from memory. The countermeasure: bind every promise to a file-level verification action (grep/Read), and report only after it passes. **If the same item is flagged twice with the same class of problem (e.g. method-literature depth twice), the item must be downgraded from "principle" to "check action".**
- **🔴 New items require an inter-item alignment sweep**: after adding items, immediately scan for contradictions or duplicates between the new item and existing ones — **internal contradiction is worse than a missing item, because the skill then issues two opposite instructions**. Focus on items that look similar but have different boundaries (E33 "reverse-calibrate formatting", E35 "scope first", G42 "propagate variable-type changes"); wherever they collide, draw the boundary explicitly. **Evidence**: when "protect the design, change the journal" (I47) was added, E35 still read "if it cannot be met, either change the design or change the journal", which directly opposed the new item, and was rewritten to "the first remedy is to change the journal; adding a dimension is the exception only when it already has theoretical necessity"; E33 gained the boundary clause "calibration covers formatting and style, not research design".
- **🔴 A skill drifts behind its project — sweep on change**: the moment a project's key state changes (title, target journal, language, indexing system, authorship structure), **sweep every item in this skill that is bound to the old state** and confirm each still holds. A stale skill is more dangerous than no skill — it hands out an outdated "pass". Evidence: the title had changed and the target journal had moved from a Chinese core journal to SSCI, while the skill still lived in the Chinese-journal context, and the decision-maker said "the review skill is still stuck in the 4.0 era".
- **Two-copy parity gate**: when the skill ships in two languages, rebuild the numbered list from one authoritative table so that **both copies have the same item count and the same index maps to the same item**; appending to each copy independently always drifts. Run an automated parity check (count + first line per number) before every release.
