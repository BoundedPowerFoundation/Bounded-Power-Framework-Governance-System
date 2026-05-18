# Bounded-Frameworks Migration & Cleanup Checklist

Working document. Mark items with `[x]` as completed. Order is suggested, not required.

Source: review of `Bounded-Power-Framework-main`, the new-domain zips, the cross-AI registration attempts (0020 Perplexity, 0021 Gemini), and harvest pass on the five external assessments in `05-Reference/`.

---

## Phase 0 — Decisions

- [x] **Repo name:** `Bounded-Frameworks`
- [x] **Root-README description / framing phrase:** "The Civilizational Stack" (already in use within the LT framework; promoted to umbrella-description duty)
- [x] **Foundation rename:** "Bounded Power Foundation" → "Bounded Power Project" throughout
- [x] **Placeholders:** include `DATA/`, `ECON/`, `TECH/` as visible folders with READMEs explicitly labeled "placeholder — framework not yet drafted"
- [x] **Domain reasoning docs:** `Reasoning-GOV.md` and `Reasoning-LT.md` stay in `BPF/00-Reading/`
- [x] **`zz-Absurdity/`:** stays at root in new repo; gets a README claiming it as project workspace
- [x] **Education:** out — separate project
- [x] **Assessments strategy:** harvest still-relevant items into checklist (this pass); move existing assessments to `zz-Absurdity/Past-Assessments/` at migration; commission fresh assessments after v1 launch

### Resolved as not-actually-broken

- [x] **"Sixth Estate" in `zz-Absurdity` transcripts:** confirmed by maintainer as abandoned earlier description. No action.

---

## Phase 1 — Foundation → Project rename pass (do first)

Touches the most files; doing it first means other fixes land on renamed versions.

- [ ] **Create new ProtonMail address** before any docs reference it.
- [ ] **Apply rename across all files** — "Bounded Power Foundation" → "Bounded Power Project"; "the Foundation" → "the Project" (case-by-case); `BoundedPowerFoundation@proton.me` → new address.
- [ ] **Tighten Charter §4 (Operator)** — once "Project" is the operator's accurate name, the paragraph simplifies. Fewer hedges, more direct.
- [ ] **Update SCBP-REG-0001's `mechanism_name`** to "Bounded Power Project — Public Registry and Framework." `mechanism_id: SCBP-REG-0001` unchanged.
- [ ] **Refresh AI Registration Bundle's embedded copies** (form and SCBP-09).

---

## Phase 2 — Mechanical structural fixes

Pure text edits, no judgment calls. Apply to the renamed versions.

### High severity — framework contradicts itself

- [ ] **Resolve duplicate `SCBP-REG-0016` and integrate pending records.**
  - [ ] Keep `SCBP-REG-0016-CEI-OH.md` as 0016.
  - [ ] Rename `SCBP-REG-0016-UH.md` → `SCBP-REG-0019-UH.md`; update YAML `mechanism_id` to `SCBP-REG-0019`; update the changelog reference at line 733 of the body that mentions the old number.
  - [ ] Regenerate pending records for CCJC (Cuyahoga County Juvenile Center) and CCCPA (Cleveland-Cuyahoga County Port Authority) using Claude + bundle. The Perplexity and Gemini outputs (was-0020 and was-0021 in maintainer's downloads) are not recoverable as-is — preserve them in `zz-Absurdity/Cross-AI-Experiments/` as evidence for the cross-AI compatibility task.
  - [ ] Assign new records the next available IDs after 0019 (likely 0020 and 0021).
- [ ] **Acronym mismatches between filename and YAML `authority_acronym` field** (both files; filenames are correct, only YAML needs updating):
  - [ ] `SCBP-REG-0009-SHCPC-OH.md`: YAML says `CPC` → update to `SHCPC` (Shaker Heights City Planning Commission, matching SH- prefix convention).
  - [ ] `SCBP-REG-0013-CCDCFS-OH.md`: YAML says `DCFS` → update to `CCDCFS` (Cuyahoga County Division of Children and Family Services, matching CC- prefix convention).
- [ ] **SCBP-08 broken Charter cross-references** — §I says "Registry Charter §7" for operational window (Charter §7 is about self-review). §X references "Registry Charter §10" for operator recusal (Charter has only §§1–8; recusal is in §7).
- [ ] **Registration Form line 781 broken Charter cross-reference** — cites "Charter §7" for 7-day publication window. Charter §7 doesn't define any 7-day window.
- [ ] **`04-Registry/README.md` broken file links** — multiple links target `SCBP-REG-0001.md`; actual filename is `SCBP-REG-0001-BPF.md`.
- [ ] **Root README references `99-Archive` (line 78)** — folder is `zz-Absurdity`.
- [ ] **Registration Form version contradiction** — header lists v1–v5; footer reads "v4." Phase 4 v1 reset resolves anyway, noting for completeness.
- [ ] **Add `PUBLIC_SOURCES` to SCBP-09's status taxonomy.** 18 of 19 registry records use this status. It's documented in the Registration Form but missing from SCBP-09 §III's status enumeration (currently only ACTIVE, EXPIRED, RENEWED, WITHDRAWN).

### Medium severity

- [ ] **Duplicate suffix `SHMC-OH`** on REG-0003 (Shaker Heights Municipal Court) and REG-0004 (City of Shaker Heights). Pick a different suffix for the city record.
- [ ] **HOA example uses non-canonical harm category `chronic_asymmetry`** in YAML.
- [ ] **Hash registry artifact list points at `04-Registry/SCBP-REG-0001.md`** — file doesn't exist at that path.

### Low severity — housekeeping

- [ ] **`zz-Absurdity/` filename hygiene** — inconsistent casing, random-string suffixes, one filename contains `&`.

---

## Phase 3 — Intellectual fixes (optional, by your call)

Content decisions, not edits. Most are not load-bearing.

### Worth a real decision

- [ ] **Cross-AI bundle compatibility.** README claims bundle works with "Claude, ChatGPT, Gemini, or similar." Direct experience: Claude works fully; ChatGPT requires attachment workaround (paste too long); Gemini doesn't reliably offer download; Perplexity strips underscores and truncates. Fix: either tighten claim to "known to work with Claude; experimental with others" or document per-AI workarounds in the Citizen Inquiry Guide.
- [ ] **AI-numbering problem — change bundle to use `SCBP-REG-NEXT` placeholder.** Bundle instructs AIs to use `SCBP-REG-NEXT` for both mechanism_id field and filename, with explicit text: "The maintainer will assign the actual number at upload time. Do not invent or assume." Maintainer does single find-and-replace before commit. Sidesteps the AI-can't-check-registry problem entirely. Resolves the parallel-session collision risk.
- [ ] **R56 self-violation** — framework requires hashed canonical artifacts; hash registry is out of date. Add §12 disclosure in SCBP-REG-0001 acknowledging the gap, or carve out "freeze pending" state in R56.
- [ ] **Voice break between README and Reasoning-BPF.**
- [ ] **README "stability" vs Reasoning-BPF "continuity is not a value"** — reconcile or note the distinction.
- [ ] **Project's own three-stop-path claim under SCBP-09 §IV** — three paths that all depend on the same authority's internal cooperation aren't three paths. Acknowledge it's met formally but not substantively, or carve out a small-authority exception.
- [ ] **AI labor as undeclared Type 1/3 dependency** in REG-0001. Same finding as the cross-AI item above, from the dependency angle.

### Framework critique items harvested from existing assessments

- [ ] **Name the load-bearing wagers in the framing layer.** The framework rests on roughly seven wagers (visibility produces consequence, R58 breadth is workable, missing-agent in binding voice is supplied by stakeholders, no-gatekeeping on stakeholder review is preferable, registry-too-small-to-be-captured anchors a framework that addresses large-scale authorities, genre risk is sufficiently mitigated, structural rules are the right level of adjudication). Most are named honestly in scattered places; framing layer would benefit from naming them together as wagers.
- [ ] **R58 breadth: name explicitly as aspirational** if that is the intended reading. Currently reads as binding.
- [ ] **"Automatic" language in R23, R28, R57, R71, R73, R78 hides who acts.** Surfacing is what's automatic; action is by stakeholders. Worth one paragraph somewhere central acknowledging this.
- [ ] **No-gatekeeping stance on stakeholder review is a values position, not a structural inference.** Frame it as such.
- [ ] **Scale-asymmetry leak:** the Foundation/Project solves capture risk by being too small to capture. Rules are calibrated to large-scale authorities. The framework doesn't model what a scaled-up registry would look like.
- [ ] **Form-over-substance choice is a values position** — name it explicitly, including the "circular evaluator" problem (any registry that adjudicated substance would itself become R58-bearing).
- [ ] **Current operating condition: registry functions as third-party reconstruction tool, not authority self-disclosure** — that's what the existing 18 PUBLIC_SOURCES records demonstrate. Worth naming as the actual current operating condition.

### Bundle improvements harvested from existing assessments

- [ ] **Direct AI to read SCBP-REG-0001 first** — Multi-Record assessment names it as "the document I most wish I had read before producing my records."
- [ ] **Direct AI to read `03-Examples/Bad-Faith-Consulting.md` before producing** — sharpens R69 reasoning, capture-risk analysis, and honesty-assertion annotations.
- [ ] **Direct AI to read relevant `03-Examples/` worked record for the domain** before producing — one-line per-domain pointers in the bundle.
- [ ] **Multi-record re-grounding pass** — for sessions producing more than 3 records, prompt the AI to re-read SCBP-04 every 3 records to check reasoning drift.
- [ ] **First-of-type-in-registry prompt** — when producing the first record for a new authority type, explicit prompt to add a top-of-body annotation about how the framework applies to that type.

### YAML schema additions harvested from existing assessments

- [ ] **`threshold_declared_by`** (`authority` / `third_party_reconstruction`) — surfaces whose declaration the §10.7 threshold is. Currently the distinction is buried in prose framing.
- [ ] **`production_continuity`** (`continuous` / `compacted` / `session_resumed`) — discloses whether AI context compaction occurred during record production.
- [ ] **`algorithmic_decision_systems_used`: allow `unknown_or_partial`** alongside `true`/`false`. Binary forces misleading answers for documented-but-not-confirmed cases.
- [ ] **`domain`: allow multiple values with primary/secondary treatment** — many authorities are genuinely multi-domain.
- [ ] **`harm_categories_declared`: add `bodily_harm_indirect`** alongside `bodily_harm`. Surfaces indirect-pathway harms (financial distress → suicide; foreclosure → homelessness → bodily impact) without forcing them into the primary frame.
- [ ] **`threshold_contestability_flag`** (`low` / `medium` / `high`) — distinguishes thresholds backed by clean track record from thresholds set by authorities with documented patterns.

### Form design items

- [ ] **§13 (Submitter) placement** — most commonly skipped section; sits awkwardly at end of body. Move to YAML or to top-of-file alongside frontmatter.
- [ ] **§1.3 (Direct/Indirect/Both) checkbox ambiguity** — two equivalent ways to declare "both" (third box OR first two boxes). Resolve to one canonical form.

### Framing polish

- [ ] **Vestigial "citizen diagnostic" language** in Citizen Inquiry Guide — Form v5 collapsed the two-class model but the guide still uses "citizen-produced structural diagnostic" extensively.
- [ ] **Hash registry mechanism not surfaced in `00-Start-Here.md`** — readers can't find it.

---

## Phase 4 — Migration prep (v1 / date reset)

Last thing before touching folder structure.

- [ ] **Decide and write the multi-domain root README** that orients across BPF, GOV, LT, INFRA, and the placeholders.
- [ ] **v1 / date reset pass across all of BPF:**
  - [ ] All YAML `*_date` fields reset to migration day
  - [ ] All YAML `expiration_date` fields recalculated from new auth date + declared `renewal_interval_years`
  - [ ] All `record_version` fields reset to `v1`
  - [ ] All `v2 update notes:` / `v3 update notes:` / etc. blocks stripped from document bodies
  - [ ] All `Revision 2026-05-16:` and similar inline revision notes stripped from framework docs
  - [ ] AI Registration Bundle's `Snapshot date:` line updated to migration day
  - [ ] Registration Form footer version updated to `v1`
- [ ] **Final commit on draft repo** with a recognizable message.

---

## Phase 5 — Restructure into multi-domain tree

```
Bounded-Frameworks/
├── README.md                          ← multi-domain orientation; introduces "The Civilizational Stack"
├── LICENSE
├── .gitignore
├── BPF/                               ← current repo content
├── GOV/
├── LT/
├── INFRA/
├── DATA/                              ← placeholder
├── ECON/                              ← placeholder
├── TECH/                              ← placeholder
└── zz-Absurdity/                      ← project workspace
```

### Migration sub-tasks

- [ ] **Rename current repo to `Bounded-Power-Framework-draft`** in GitHub settings.
- [ ] **Create new repo `Bounded-Frameworks`** on GitHub. Initialize empty.
- [ ] **Build `BPF/` subfolder** containing current repo content (with all prior phases applied). Current root README becomes `BPF/README.md`.
- [ ] **Merge SCBP zip contents into `BPF/05-Reference/`:**
  - [ ] `!!!-IMPORTANT-Canonical Text Standard.txt` → `BPF/05-Reference/02-Canonical-Text-Standard.md`
  - [ ] `Civilian Red Button.txt` → `BPF/05-Reference/06-Civilian-Red-Button.md`
  - [ ] `AUTHORITY_SURFACE_MAPPING_GUIDE_v0.02.txt` → `BPF/05-Reference/07-Authority-Surface-Mapping-Guide.md`
- [ ] **Move existing assessments to `zz-Absurdity/Past-Assessments/`** — they audit the pre-v1 state and would mislead v1 readers.
- [ ] **Split `BPF/03-Examples/`** into `BPF/03-Examples/honest/` and `BPF/03-Examples/adversarial/` (the Bad-Faith counter-example moves to adversarial/).
- [ ] **Build `GOV/` folder** honoring GOV-MASTER.md's recommended layout (core / operations / safeguards / standards subfolders + `GOV-MASTER.md` + `GOV/README.md`).
- [ ] **Build `LT/` folder** — flat or grouped by phase. Move the 236KB JPEG to `LT/images/`. Add `LT/README.md`.
- [ ] **Build `INFRA/` folder** — three files; README flags early-stage.
- [ ] **Build placeholder folders (`DATA/`, `ECON/`, `TECH/`)** — each gets framework stub and a "placeholder" README.
- [ ] **Move `zz-Absurdity/` to root**, add README claiming it as project workspace.
- [ ] **Write root `README.md`** that orients across all domains and introduces "The Civilizational Stack" as the umbrella framing.
- [ ] **Add `LICENSE`** (Creative Commons for docs is common).
- [ ] **Add `.gitignore`** (minimum: `.DS_Store`, `Thumbs.db`, `*.swp`).
- [ ] **Tag first commit as `v1.0.0`** and push the tag.

---

## Phase 6 — Post-migration sanity

After the new repo is live.

- [ ] **Fix all cross-references inside `BPF/`** that previously pointed at root-level paths.
- [ ] **Cross-link domains** — `BPF/00-Reading/02-Reasoning-GOV.md` links to `../../GOV/`; reciprocal links from each domain back to its BPF reasoning doc.
- [ ] **Update `BPF/README.md`** to acknowledge it's one of N domains.
- [ ] **Update `-draft` repo's README** to point at new canonical URL.
- [ ] **Regenerate the hash registry** once content is stable (weeks after migration).
- [ ] **Commission fresh assessments** of the v1 state.

---

## Future infrastructure (post-v1, when registry grows)

Not for migration; flagged for the next horizon.

- [ ] Per-record one-page summary card (journalists/citizens scanning the registry need this; 60KB Mechanism Records are right for diagnostic work, wrong for first-glance reading).
- [ ] Registry-level analytics (renewal interval distributions, threshold-to-population ratios, capture-risk frequency).
- [ ] Cross-record references in YAML (currently prose-only; hard to navigate at scale).
- [ ] Documented collision-resolution procedure for parallel-session ID conflicts.
- [ ] Worked example of the authority-after-third-party update path — the first time it's exercised will be high-information.
- [ ] Address the "maintenance reality" question — who keeps records synchronized as institutions change.

---

*Working checklist. Edit freely as you go.*
