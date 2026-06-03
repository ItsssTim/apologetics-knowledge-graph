# Red-Team — Adversarial Review of the Apologetics Knowledge Graph

> Written against the project, not for it. The question: if a hostile but fair critic — a religious-studies professor, a skeptic, or a rival apologist — audited this, where would they land a punch? Ranked by severity, each with a proposed fix and whether it's executed now.

## R1 — Selection bias is the project's biggest vulnerability (SEVERE)
**The charge:** This is billed as "the structured argument map of contemporary Christian apologetics." It is not. It is the map of **eight hand-picked conservative, evangelical, broadly ID-friendly apologists** speaking on YouTube. There is no Catholic systematic voice (Barron is a single cameo), no Orthodox voice, no mainline/liberal scholarship except as foils, no progressive/affirming ethics, no analytic philosophers of religion who are theists-but-critics (e.g. nobody like Peter van Inwagen on the problems). The "cross-expert consensus" a reader sees is partly an artifact of choosing experts who already agree.
**Fix:** Reframe the scope claim honestly, and (bigger) add genuine counter-voices so each tree has a real dialectic, not just "objection → apologist wins."
**Executed now:** the honest scope reframe on the index masthead. Counter-voice sourcing is queued (needs new extraction).

## R2 — The sources are popular YouTube talks, not the experts' best work (SEVERE)
**The charge:** Every tree is built from auto-transcribed videos. Even at 100% quote-fidelity, this captures *what an apologist says extemporaneously to a sympathetic crowd*, not the rigorous version in their books and peer-reviewed papers. Craig's published Kalam defence answers Morriston and Malpass in detail; the YouTube version doesn't. So the graph systematically presents the *weakest* form of each argument and then (honestly) flags the holes — which is slightly unfair to the experts and misleads on the state of the actual scholarship.
**Fix:** For the flagship nodes, supplement with the published literature (Craig's *Reasonable Faith*, Meyer's books, Bauckham's *Jesus and the Eyewitnesses*). Label each tree "popular-level" vs "scholarly."
**Executed now:** documented; not fixable without non-transcript sources.

## R3 — "Rich = 3+ experts" conflates popular with important (MODERATE)
**The charge:** The ≥3-expert bar that defined the 81 "rich" trees measures *how often a point is repeated across these eight men*, not its importance or soundness. Frequently-repeated crowd-pleasers (the manuscript-count flex, levels-of-explanation) clear the bar; genuinely hard topics (messianic prophecy, conquest) didn't, purely because they're one expert's specialty. The bar is a popularity metric wearing an importance costume.
**Fix:** The deep-dive pass partly corrected this (built the expert-concentrated topics anyway). Going forward, weight by argumentative centrality, not frequency.
**Executed now:** partially — the 14 deep-dives added the expert-concentrated topics.

## R4 — Single-expert "trees" overstate themselves (MODERATE)
**The charge:** Several trees (cruciform theodicy = Lennox only; the new doctrinal trees = WLC only) are one person's view formatted to look like a synthesised consensus. A "tree" implies convergence; these are monologues.
**Fix:** Already mitigated — these are honestly marked "deep-dive, 1 expert" in their mastheads. But the visual format still implies more than it delivers. v4 should visually distinguish "consensus trees" from "single-voice deep-dives."

## R5 — No skeptic actually checked whether the "best responses" succeed (MODERATE)
**The charge:** Each tree's "objections" section presents the apologist's reply as adequate unless a *building agent* happened to flag a gap. The agents are capable but not domain experts and not adversarial by design. So the graph's implicit verdict ("the response handles the objection") is largely unaudited. The honest gap-flags (Ezekiel 45, NOMA, Hick pluralism, the conquest animals, the Bayesian independence assumption) are real and creditable — but they're the agents' catches, not a systematic adversarial pass.
**Fix:** Run an adversarial "steelman the skeptic" pass per flagship tree — a dedicated agent arguing the objection is NOT answered. Queued.

## R6 — Quote-validation covered 21 of ~97 trees (MODERATE, shrinking)
**The charge:** The proud "100% verbatim-faithful" headline is true only for the 21 headline trees. ~76 trees are unvalidated and still carry ⚠️verify. A reader could over-trust the unvalidated ones.
**Fix:** Validate the remaining trees (same parallel method — cheap). Queued as the clear next batch.

## R7 — The taxonomy is a 1,018-node map over ~250 sources (MODERATE)
**The charge:** The taxonomy advertises 1,018 canonical questions; ~640 have zero coverage. The map dwarfs the territory and implies comprehensiveness the content doesn't have. v4 is specified (the reconciliation memo) but not built.
**Fix:** Execute v4 per `taxonomy/v4_reconciliation_memo.md` — prune/flag unsourced nodes, integrate the 322 proposals, mark the in-house forks.

## R8 — No provenance / un-auditable claims (MINOR)
**The charge:** A tree cites *which transcript* a claim came from, but not the timestamp or a link, so no reader can independently audit a quote in seconds. For a "knowledge graph" that aspires to be citable, traceability is thin.
**Fix:** Add transcript line-refs / YouTube timestamps to canonical quotes. Future enhancement.

## R9 — Genuinely empty branches are presented softly (MINOR)
**The charge:** §19 Christian History, §16 Spiritual Life, and the Catholic/Orthodox deuterocanon are empty or near-empty because the corpus has no material — but the polished UI could let a user assume coverage that isn't there.
**Fix:** The sitemap already lists empty branches explicitly. Keep that prominent; don't let v4 paper over it.

---

## Proposal (ranked execution order for the next work session)
1. **Honesty reframe** of the scope claim (executed now).
2. **Validate the remaining ~76 trees' quotes** (parallel, cheap) → clear ⚠️verify corpus-wide.
3. **Adversarial skeptic pass** on the ~20 flagship trees (R5) → real dialectic, not assumed wins.
4. **Counter-voice extraction** (R1) — add critical/skeptical and cross-tradition sources so trees argue both sides.
5. **Execute taxonomy v4** (R7) per the reconciliation memo.
6. **Supplement flagships with published-work sourcing** (R2); label popular vs scholarly.
7. **Provenance** line-refs (R8).

## Bottom line
The build is honest about its *gaps* (the per-tree flags are genuinely good) but not yet honest about its *scope* — it's an excellent map of conservative-evangelical YouTube apologetics that currently presents as a map of Christian apologetics simpliciter. The single highest-integrity fix is the scope reframe (done); the highest-value substantive fix is adding real counter-voices so the trees stop refereeing their own matches.
