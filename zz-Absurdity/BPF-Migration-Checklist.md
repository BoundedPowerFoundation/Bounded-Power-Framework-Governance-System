# Bounded-Frameworks Migration & Cleanup Checklist

Working document. Mark items with `[x]` as completed. Order is suggested, not required.

Source: review of `Bounded-Power-Framework-main` and the new-domain zips, May 2026.

---

## Phase 0 — Decisions

- [x] **Repo name:** `Bounded-Frameworks`
- [x] **Root-README description / framing phrase:** "The Civilizational Stack" (already in use within the LT framework; promoted to umbrella-description duty)
- [x] **Foundation rename:** "Bounded Power Foundation" → "Bounded Power Project" throughout
- [x] **Placeholders:** include `DATA/`, `ECON/`, `TECH/` as visible folders with READMEs explicitly labeled "placeholder — framework not yet drafted"
- [x] **Domain reasoning docs:** `Reasoning-GOV.md` and `Reasoning-LT.md` stay in `BPF/00-Reading/` (BPF's framing of those domains, not the domains themselves)
- [x] **`zz-Absurdity/`:** stays at root in new repo; gets a README claiming it as project workspace
- [x] **Education:** out — separate project, will not be in `Bounded-Frameworks`

### Resolved as not-actually-broken

- [x] **"Sixth Estate" in `zz-Absurdity` transcripts:** confirmed by maintainer as abandoned earlier description. Historical workspace residue, not orphaned vocabulary. No action needed.

---

## Phase 1 — Foundation → Project rename pass (do first)

This touches the most files, so doing it first means every other fix lands on renamed versions rather than needing re-editing.

- [ ] **Create new ProtonMail address** (e.g., `BoundedPowerProject@proton.me`) before any docs reference it.
- [ ] **Apply rename across all files** — every occurrence of:
  - "Bounded Power Foundation" → "Bounded Power Project"
  - "the Foundation" → "the Project" (case-by-case where the context makes "the Project" read naturally)
  - `BoundedPowerFoundation@proton.me` → new address
- [ ] **Tighten Charter §4 (Operator)** — currently leans on "Foundation does not yet exist; maintainers serve the operator function informally" framing. Once "Project" is the operator's accurate name, that paragraph simplifies. Fewer hedges, more direct.
- [ ] **Update SCBP-REG-0001's `mechanism_name`** to "Bounded Power Project — Public Registry and Framework." Keep `mechanism_id: SCBP-REG-0001` unchanged.
- [ ] **Verify the AI Registration Bundle's embedded copies** reflect the rename (the bundle embeds the form and SCBP-09; both will need refreshing).
- [ ] **Update `zz-Absurdity/` references**, if any feel worth touching. Mostly historical, so judgment call — most can stay as-is.

---

## Phase 2 — Mechanical structural fixes

Pure text edits, no judgment calls. Apply to the renamed versions from Phase 1.

### High severity — framework contradicts itself

- [ ] **Duplicate `SCBP-REG-0016`** — both `SCBP-REG-0016-CEI-OH.md` and `SCBP-REG-0016-UH.md` declare `mechanism_id: SCBP-REG-0016`. Bump one of them (e.g., UH becomes 0019).
- [ ] **SCBP-08 broken Charter cross-references** — §I says "per Registry Charter §7" for operational window (Charter §7 is about self-review). §X references "Registry Charter §10" for operator recusal (Charter only has §§1–8; recusal is in §7).
- [ ] **Registration Form line 781 broken Charter cross-reference** — cites "Charter §7" for 7-day publication window. Charter §7 doesn't define any 7-day window. Either move the definition into the Charter or remove the cross-ref.
- [ ] **`04-Registry/README.md` broken file links** — multiple links target `SCBP-REG-0001.md`; actual filename is `SCBP-REG-0001-BPF.md`.
- [ ] **Root README references `99-Archive` (line 78)** — folder is `zz-Absurdity`. Fix the pointer.
- [ ] **Registration Form version contradiction** — header revision history lists v1–v5; footer reads "Registration Form (v4)". Will be resolved by the v1 reset in Phase 4 (everything becomes v1), but worth noting now.

### Medium severity

- [ ] **Duplicate suffix `SHMC-OH`** on REG-0003 (Shaker Heights Municipal Court) and REG-0004 (City of Shaker Heights). Pick a different suffix for the city record.
- [ ] **HOA example uses non-canonical harm category `chronic_asymmetry`** in YAML. Not in R21, not in SCBP-09 §VI. Either add it to §4.7 as an authorized extension or remove from YAML.
- [ ] **Hash registry artifact list points at `04-Registry/SCBP-REG-0001.md`** — file doesn't exist at that path. Fix the artifact list (will be regenerated anyway at freeze).

### Low severity — housekeeping

- [ ] **`zz-Absurdity/` filename hygiene** — inconsistent casing, random-string suffixes, one filename contains `&`. Rename to consistent slugs if keeping.

---

## Phase 3 — Intellectual fixes (optional, by your call)

Content decisions, not edits. Most are not load-bearing. Resolve as time/will allow.

### Worth a real decision

- [ ] **R56 self-violation** — framework requires hashed canonical artifacts; hash registry is openly out of date. Either add a §12 disclosure in SCBP-REG-0001 acknowledging the gap, or carve out a "freeze pending" state in R56 itself.
- [ ] **Voice break between README and Reasoning-BPF** — accessible register shifts to terminal-voice without warning. Either signal the shift in the reading order, or have Reasoning-BPF open with a register note.
- [ ] **README "stability" vs Reasoning-BPF "continuity is not a value"** — reconcile or note the distinction.
- [ ] **Project's own three-stop-path claim under its own SCBP-09 §IV** — once it's the "Project," this becomes easier to address honestly. SCBP-09 §IV says three paths that all depend on the authority's internal cooperation aren't three paths. Acknowledge it's met formally but not substantively, or carve out a small-authority exception.
- [ ] **AI labor as undeclared Type 1/3 dependency** — README's primary path is "paste bundle into AI chat." By the framework's own taxonomy that's a dependency on third-party AI providers. The Project's REG-0001 declares zero Type 1 dependencies. Add a §6 disclosure.

### Framing polish

- [ ] **Vestigial "citizen diagnostic" language** in Citizen Inquiry Guide — Form v5 collapsed the two-class model, but the guide still uses "citizen-produced structural diagnostic" extensively. Decide if intentional or vestigial.

---

## Phase 4 — Migration prep (v1 / date reset)

After Phases 1–2 (and as much of Phase 3 as you want). The last thing before touching folder structure.

- [ ] **Decide and write down the multi-domain README content** that will live at the new repo root — orients across BPF, GOV, LT, INFRA, and the placeholders.
- [ ] **v1 / date reset pass across all of BPF:**
  - [ ] All YAML `*_date` fields reset to migration day (`registered_date`, `snapshot_date`, `last_reviewed_date`, `authorization_date`)
  - [ ] All YAML `expiration_date` fields recalculated from new auth date + declared `renewal_interval_years`
  - [ ] All `record_version` fields reset to `v1`
  - [ ] All `v2 update notes:` / `v3 update notes:` / etc. blocks stripped from document bodies (they describe a history that won't exist in v1)
  - [ ] All `Revision 2026-05-16:` and similar inline revision notes in framework docs (SCBP-08, SCBP-09, Stop-Trigger form) stripped
  - [ ] AI Registration Bundle's `Snapshot date:` line updated to migration day
  - [ ] Registration Form footer version updated to `v1`
- [ ] **Final commit on draft repo** with a recognizable message (e.g., `pre-rename-final`).

---

## Phase 5 — Restructure into multi-domain tree

Proposed tree:

```
Bounded-Frameworks/
├── README.md                          ← multi-domain orientation; introduces "The Civilizational Stack"
├── LICENSE
├── .gitignore
├── BPF/                               ← current repo content
├── GOV/
├── LT/
├── INFRA/
├── DATA/                              ← placeholder (Phase 0: include)
├── ECON/                              ← placeholder (Phase 0: include)
├── TECH/                              ← placeholder (Phase 0: include)
└── zz-Absurdity/                      ← project workspace
```

### Migration sub-tasks

- [ ] **Rename current repo to `Bounded-Power-Framework-draft`** (or similar) in GitHub settings.
- [ ] **Create new repo `Bounded-Frameworks`** on GitHub. Initialize empty — no README, no .gitignore from GitHub's templates.
- [ ] **Build `BPF/` subfolder** containing the entire current `Bounded-Power-Framework-main` content (with all Phases 1–4 edits applied). The current root README becomes `BPF/README.md`.
- [ ] **Merge SCBP zip contents into `BPF/05-Reference/`**:
  - [ ] `!!!-IMPORTANT-Canonical Text Standard.txt` → `BPF/05-Reference/02-Canonical-Text-Standard.md` (rename to remove `!!!`, convert encoding to LF, slot into 05-Reference numbering).
  - [ ] `Civilian Red Button.txt` → `BPF/05-Reference/06-Civilian-Red-Button.md`.
  - [ ] `AUTHORITY_SURFACE_MAPPING_GUIDE_v0.02.txt` → `BPF/05-Reference/07-Authority-Surface-Mapping-Guide.md`.
- [ ] **Build `GOV/` folder** honoring GOV-MASTER.md's recommended layout (core / operations / safeguards / standards subfolders + `GOV-MASTER.md` + `GOV/README.md`).
- [ ] **Build `LT/` folder** — flat or grouped by phase. Move the 236KB JPEG to `LT/images/`. Add `LT/README.md`.
- [ ] **Build `INFRA/` folder** — three files; flag in README that it's early-stage.
- [ ] **Build placeholder folders (`DATA/`, `ECON/`, `TECH/`)** — each gets its `<X>-Framework.md` stub and a README flagging "placeholder."
- [ ] **Move `zz-Absurdity/` to root**, add a README claiming it as project workspace.
- [ ] **Write root `README.md`** that orients across all domains and introduces "The Civilizational Stack" as the umbrella framing.
- [ ] **Add `LICENSE`** (Creative Commons for docs is common; pick what matches intent).
- [ ] **Add `.gitignore`** (minimum: `.DS_Store`, `Thumbs.db`, `*.swp`).
- [ ] **Tag the first commit on the new repo as `v1.0.0`** and push the tag.

---

## Phase 6 — Post-migration sanity

After the new repo is live.

- [ ] **Fix all cross-references inside `BPF/`** that previously pointed at root-level paths.
- [ ] **Cross-link domains** — `BPF/00-Reading/02-Reasoning-GOV.md` links to `../../GOV/`; `BPF/00-Reading/03-Reasoning-LT.md` links to `../../LT/`. Reciprocal links from each domain's README back to its BPF reasoning doc.
- [ ] **Update `BPF/README.md`** to acknowledge it's now one of N domains, not the whole repo.
- [ ] **Update `-draft` repo's README** to point at the new canonical URL.
- [ ] **Regenerate the hash registry** once content is stable (worth doing only after the dust settles — possibly weeks after migration).

---

*Working checklist. Edit freely as you go.*
