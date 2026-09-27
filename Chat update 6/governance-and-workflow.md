# C.E.R. — Governance & Workflow (F.R.M.)

Locked Free Reign Mode (F.R.M.) governance principles, the F.R.M. standard and permission set, working patterns, status vocabulary, the Sweep Suite pointer, and the open governance proposals awaiting Wesley's sign-off.

This doc is C.E.R.'s own "Authorities Archive" — the generic *Project Governance Protocol* framework Wesley extracted from this project (to reuse on future projects) traces back to the same F.R.M. system documented here. This section incorporates everything from that generic framework that actually applies to C.E.R., cross-checked against it on 2026-09-22.

## Locked governance principles

1. **Bridge-Eligible Mod Principle** — 4-step evaluation order for Fabric-only mods: (1) native port → (2) Connector/Forgified Fabric API → (3) alternative → (4) weigh the burden of forcing it in anyway.
2. **Mental Economy Delegation Principle** — small/cosmetic/QoL mods serve a genuinely necessary cognitive-rest function distinct from deep systemic mods; "lower-stakes" must never be read as "lower priority."
3. **Integration Depth Tiers** — Direct / Indirect / Observational / Social tiers for how mods connect to Affinity/Resonance, preventing every integration from becoming a flat Affinity trigger.
4. **Synergy Combos** (M.M.I. section) — small mods are evaluated as combinations, not just standalone candidates.

## The F.R.M. standard

- **The actual test for any F.R.M. action is "does this make the project better?"** — not "did you ask first." Asking permission for everything defeats the point of delegating authority.
- **Locked decisions are a ceiling, not silently overridable.** Once Wesley has explicitly locked/confirmed something, F.R.M. discretion never means quietly changing it later. A locked decision can still be revisited, but that requires actually raising it with Wesley again.
- **Logging is non-negotiable.** Every F.R.M. action should be traceable — what changed, why, and what it affects — not just reflected as an updated doc with no reasoning trail. *(Gap: the current doc set has no numbered Change Log. The older archive scheme had one — entries up to at least CLR-0073 are cited in the old Master Archive, Master Mod Index, Reconciliation Report and Missed Questions files — but the log itself isn't in the Project or in the retained conversation files. See "Open governance proposals" below.)*
- **Standing meta-rule — new grants are self-integrating.** Any new authority Wesley grants gets written into the Permission Set below immediately, as part of the grant itself, not as a follow-up step he has to remember to request.

## F.R.M. permission set

The standing authorities Wesley has delegated so Claude doesn't need to ask before acting on them (still logged/surfaced per the standard above):

- **Archive / Approve / Veto / Modify / Defer** — the basic vocabulary for responding to a proposal: record it, endorse it, push back on it, improve it before accepting, or postpone pending more information.
- **Merge/split systems** — combine two overlapping concepts, or separate one bloated concept into cleaner parts (e.g. the Sweep Suite fusion, or splitting Vanilla Backport into two M.M.I. entries once decided).
- **Propose implementation architecture** — offer concrete technical/structural approaches, not just conceptual design (e.g. the KubeJS hybrid-architecture proposal that became `cer_affinity_core.js`).
- **Resurrect good discarded ideas** — nothing marked historical/superseded (Archive Preservation Principle, below) is gone forever; a later pass can bring it back if it turns out to fit.
- **Discretionary Sweeps/Audits** — proactively inspect the project for gaps, redundancies, or forgotten ideas without being asked.
- **Sweep/Audit Creation & Integration** — invent new Sweep types as the project's needs reveal them; retroactively recognize any existing process that fits the Sweep definition as a formal Sweep.
- **Umbrella Term Creation & Family Integration** — create new organizing/classification terms when a genuine pattern emerges across several concepts, and place things under it. A thing can belong to multiple umbrellas at once if it genuinely fits more than one — never force an exclusive single parent category for tidiness alone.
- **Content Consolidation** — when something gets promoted to its own dedicated doc after previously sharing space with other content, decide whether the old shared section should be removed entirely (unrelated content) or condensed to a brief cross-referencing overview (genuinely related content).
- **Multi-Part Task Continuation** — once a multi-part task is approved (a sweep across many docs, a big multi-file pass), no permission is needed to proceed from one part to the next. Genuinely new decision points found mid-task still get surfaced to Wesley.
- **Proactive Suggestion Making** — introduce ideas without waiting to be asked.
- **Term Coining & Term Banking** — create new terminology when useful; preserve promising-but-unused terminology for later rather than discarding it.
- **Naming-Collision Auto-Resolution** — if a newly-created name collides with something already established (e.g. the unrelated "Affinity" mod discovered on Modrinth), rename the *new* thing to clear the conflict, notify Wesley, and log it, without needing approval first for this narrow case.
- **Change-log Creation** — Claude writes change/decision log entries directly as part of doing the work, not as a separate step Wesley has to request. *(Gap: see Open governance proposals — the current doc set has no Change Log doc to write these into.)*
- **External Inspiration/Reference Research** — permission to research comparable real-world or other-project precedents when useful (same meaningful-adaptation-not-copying standard as any Modification Sweep work).
- **Automatic Provenance Crediting** — if any real external creator's work (a mod, an asset, a specific idea) ever gets referenced or reused, credit them explicitly wherever that reuse is recorded. Non-negotiable, not situational.

## Working patterns

- Mod verification is rigorous: confirmed against live sources for loader compatibility, Cobblemon version targeting, feature sets, and download counts before an M.M.I. entry is made.
- Mod submissions often come in loosely (misspellings, partial names, mixed source types) — batch-processed and disambiguated systematically.
- Design decisions are formalized as locked governance principles here once proven, not before.
- Redundancy clusters are resolved through structured sweeps (see Sweep Suite below), not ad hoc decisions.
- Philosophical coherence (e.g., scarcity design in Retirement/Championship Protocol) is treated as a hard constraint that can override convenience or feature richness.
- **Unconfirmed/speculative material gets full detail in both the archive doc and the main working doc, side by side** — not a slimmed pointer in one and full detail in the other. (This reverses an initially-tried "archive gets the detail, main doc gets a pointer" rule — Wesley's correction: "Actaully take the last rule back, update boths ets side by side.") Applied whenever new unconfirmed proposals land in `CER_ChatGPT_Import_Integration.md` — e.g. the Source-network Affinity proposal appears in full in both that doc and `affinity-architecture.md`.
- **Editorial integrity:** formatting, clarity, grammar, and organization can be fixed freely in any doc, but the *meaning* of an already-locked decision never changes silently while doing so. A fix that would change what something actually says is a real modification, not a formatting pass, and gets flagged as such.
- **Canonical terminology normalization:** when a concept accumulates multiple names over time (a natural side effect of iterative design across many sessions), the current/official name is used consistently going forward, and old names are preserved explicitly as "this used to be called X" rather than silently forgotten or retconned. Already the working pattern for the Sweep Suite (see its "fate of prior sweep terms" table) and for the pending `cer:` namespace proposal (replacing `cobblemon_er:`/`er:`) — this bullet just names the general rule those follow.

## Status vocabulary

A consistent, at-a-glance status tag, so "is this decided or just an idea" never requires re-reading surrounding context. Not yet applied retroactively across every doc, but adopted going forward — use these tags (or the plain-English equivalent already in use, like "CONFIRMED" or "genuinely open, not decided") when marking status in any doc:

| Symbol | Meaning |
|---|---|
| 🕒 Locked | Explicitly decided and current — the ceiling for F.R.M. discretion. |
| 🟢 Strong reconstruction | High-confidence recovered or developed material, not yet formally locked but treated as reliable. |
| 🟡 Candidate | A real proposal on the table, not decided. |
| 🔵 Current proposal | A strong, live proposal awaiting a decision (similar to Candidate). |
| 🟠 Unresolved | An open question with no settled answer yet, genuinely needing a decision. |
| ⚪ Historical/Superseded | Was once relevant or was a previous version of something now changed — preserved, not deleted. |
| 🔴 Rejected | Considered and explicitly turned down — preserved as a record of what was tried, not erased. |

## Archive Preservation Principle

Nothing gets deleted just because it's superseded, rejected, or historical. "Not canon" never means "delete" — it stops the same idea from being silently re-proposed and re-rejected later, and lets Wesley (or a future session) see *why* something is the way it is, not just that it is. This is already the de facto practice — `CER_ChatGPT_Import_Integration.md` keeps the full historical reasoning behind resolved questions rather than deleting it once a topic moves to its destination doc — this section just makes the policy explicit. The one carve-out: Content Consolidation (permission set, above) may still remove or condense a duplicate *current* description once something gets its own dedicated doc — it never touches historical, superseded, or rejected material.

## Sweep Suite (status: CONFIRMED, locked 2026-09-18)

The full C.E.R. sweep methodology is a fused taxonomy of **19 named sweeps** (Mod Inventory, Redundancy & Overlap, Implementation Layer, Compatibility & Version, Worldgen Integrity, Progression & Economy, Quest Design, Fit & Identity, Feature Coverage & Integration, Client & Input, Performance & Load, Stability, Architecture Integrity, Persistence & Multiplayer, Exploit & Abuse, Discovery & Design Philosophy, Build Validation, Playtest, Archive Sweep) plus four composite processes:

- **TriSweep** — light Mod Inventory + Redundancy & Overlap + Fit & Identity, for routine maintenance.
- **Final Pre-Release Sweep** — all 19 minus Archive Sweep, ship-gated.
- **Total Cleanse** — all 19 + both Archive Sweep modes, full project reset-and-verify (pack **and** documentation). This document set was produced by a Total Cleanse pass on the documentation side on 2026-09-18.
- **Targeted Regression Sweep** — only the sweeps a new feature actually touches.

Built by fusing ~73 ChatGPT-proposed micro-sweeps + 6 meta-processes at Wesley's direction. Full detail: `claude/CER_Sweep_Suite_FullTaxonomy.md`. Original verbatim source: `claude/CER_Sweep_Suite_Source.md`. Cheat-sheet: `claude/CER_Sweeps_Quick_Reference.md`. **These three docs are the confirmed source of record and are not rewritten by other passes** — only referenced.

**Archive Sweep** has two modes, both Wesley-coined terms:
- **Archive Intake** — the additive mode: fold new discussion into the archive before it's forgotten.
- **Archive Diet** — the subtractive mode: trim non-load-bearing "fluff" from an archive that's gotten "thick," without cutting anything decision-relevant. A trim, not a purge — when in doubt whether something is fluff, it stays.

Prior provisional sweep terms (Mod Audit, Modification Sweep, earlier "Optimization Sweep"/Compatibility & Version/Terminology-Consistency/Balance-Numbers/Archive-Memory proposals) are all superseded/absorbed into the fused taxonomy — see the FullTaxonomy doc's "fate of prior sweep terms" table for the exact mapping.

**Known gap, not yet a fused sweep:** a **Bank Sweep** — a dedicated pass cataloguing terminology regardless of status (official, locked, banked, candidate, historical, rejected, ambiguous), so nothing gets silently forgotten. Fit & Identity Sweep covers *consistency* of lore/terminology but not a full standing catalogue. Added to Open governance proposals below as a candidate 20th sweep.

## Open governance proposals (awaiting Wesley's sign-off — none of these are locked)

Surfaced during the large ChatGPT-import integration pass (full reasoning preserved in `claude/CER_ChatGPT_Import_Integration.md`), plus a few structural gaps found comparing this doc against the generic Project Governance Protocol Wesley extracted from C.E.R. Tracked here as a standing checklist; accepting or rejecting each has downstream effects on what gets built next. Duplicated in `claude/CER_Unanswered_Questions.md` as the actionable backlog — this list is the governance-level summary.

- [ ] **Implementation Layer Principle** (proposed 5th F.R.M. principle): content/rules → datapack layer; new capability (blocks, entities, GUIs, state machines) → mod; cross-mod glue/scripted behavior → KubeJS; presentation-only → resource pack. Never drop to a lower layer merely because it's technically possible.
- [ ] Adopt **`cer:`** as the single canonical namespace, replacing earlier `cobblemon_er`/`er:` proposals — matches the project's own abbreviation, short, unambiguous.
- [ ] Adopt the **Research System Charter** (Snap = photographic/observational, Research Tasks = active/interactive, Field Journal = narrative, FTB Quests = campaign/expedition) — detail in `claude/research-system.md`.
- [ ] Adopt **ProgressiveStages as the single progression source of truth**, with RCT level-cap triggers and any Route Mode gate writing *to* ProgressiveStages flags rather than keeping independent state (pending the ProgressiveStages-vs-AStages test-branch decision).
- [ ] Adopt the **two-camera resolution** (Snap = research, Exposure = personal/artistic), retiring the generic handheld-camera placeholder.
- [ ] Downgrade the Remote Access-style dynamic multiblock laboratory GUI to a stretch goal, not a core-path dependency.
- [ ] Adopt the **Threshold Anchor (primary) + Dream Echo (secondary)** Biosphere access split — see `claude/world-architecture.md`.
- [ ] Decouple the Affinity biome-distribution system from Vanilla Backport's specific tag namespace — build on vanilla/common tags instead.
- [ ] Split Vanilla Backport into two independent M.M.I. entries (real backport content vs. bundled Chaos Cubed original content).
- [ ] Merge the Lost Mob Grinders and Lost Biomes lore threads under one historical-catastrophe event.
- [ ] Build **Route Mode** (Cobblemon Routes + a custom opt-in Nuzlocke-style toggle) on the terms researched — see `claude/CER_Unanswered_Questions.md` for the decision status.
- [ ] Decide whether **Affinity becomes a Source-like in-world energy network** (Ars Nouveau Sourcelink/Jar/Relay pattern — Affinity Seeds/Generators/Jars/Relays) or stays a pure behind-the-scenes stat accessed only through the `/cer` API/Core — pending `CER_Unanswered_Questions.md` item 18.
- [ ] Adopt the **Underground Overhaul mod stack** (YUNG's Better Caves + Tectonic as the base, Alex's Caves: Refabricated as rare punctuation) and move it into M.M.I. research — pending `CER_Unanswered_Questions.md` item 21 (may also wait on the base Overworld worldgen decision, item 3).
- [ ] Confirm the **Shadow Pokémon six-pillar scope** (distinct visual identity, Shadow State layered on typing, Shadow Resonance, Shadow-exclusive moves/abilities, Purify/Stabilize/Remain-Shadow branch, Shadow Research) as the committed subset of the full 23-idea brief — pending `CER_Unanswered_Questions.md` item 22.
- [ ] Adopt the **Fractured type-based Resonance + Iron's Spells Sync-move architecture** for Fractured Pokémon (only 5 of 18 types have a sketched Resonance ability so far) — pending `CER_Unanswered_Questions.md` item 23, and dependent on whether Iron's Spells 'n Spellbooks makes the final mod list.
- [ ] **Adopt a numbered Change Log** (e.g. `CLR-0001`, `CLR-0002`…) recording every meaningful decision — what changed, why, what it affects, current status — tagged ADD/REMOVE/MODIFY/REPLACE/RENAME/MERGE/SPLIT/RECLASSIFY/PROMOTION/DEMOTION/CONTRADICTION/RESOLUTION, with the hard rule that a past entry is never edited or deleted to "fix" a decision that later changed (a reversal gets a *new* entry cross-referencing the original). The older archive scheme had exactly this: entries up to at least CLR-0073 are cited in the old Master Archive, Master Mod Index, Reconciliation Report and Missed Questions files (corrected 2026-09-24; the 2026-09-22 version of this line wrongly said C.E.R. never had one). But the log itself isn't in the current Project docs or the retained conversation files, and the current doc set has no replacement, so decisions are only visible as the current state of whatever doc they landed in, with reasoning preserved in `CER_ChatGPT_Import_Integration.md` topic by topic rather than in one chronological ledger. If adopted, decide whether to resume numbering after CLR-0073 (the highest number found cited) or start fresh, and whether Wesley still has the original log to re-upload. This is the largest structural gap found comparing C.E.R.'s live governance doc against the generic Project Governance Protocol Wesley extracted from it.
- [ ] Adopt a **Bank Sweep** as a 20th named sweep — a dedicated terminology-cataloguing pass (see Sweep Suite section above).

## Namespace / stack conventions currently in use

- Existing content is referenced under `cobblemon_er:` and `er:` in older material; **`cer:` is proposed to replace both** but is not yet formally adopted (see proposal list above).
- KubeJS script organization proposed as `CER/affinity/`, `CER/fracture/`, `CER/resonance/`, `CER/titan/`, `CER/quests/`, `CER/world/`, `CER/cobblemon/`, `CER/integration/` — not yet built.

## Core creative pillars (pointer)

C.E.R.'s named design-philosophy pillars — **Discovery Over Prescription** and **Creation Over Crafting** — are documented in `claude/overview.md`, not duplicated here, since they describe the project's creative identity rather than its governance process.
