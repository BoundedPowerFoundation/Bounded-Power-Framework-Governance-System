# BPF Migration & Cleanup Checklist

Working document. Mark items with `[x]` as completed. Order is suggested, not required.

Source: review of `Bounded-Power-Framework-main` and the seven new-domain zips, May 2026.

---

## Phase 0 — Decisions before doing anything

These shape the rest of the work. Decide before Phase 4.

- [ ] **New repo name** — does the umbrella repo keep the name "Bounded-Power-Framework" (with BPF as the headline inhabitant) or get a new umbrella name?
- [ ] **Empty placeholder domains (DATA, ECON, TECH)** — include in the initial tree as visible placeholders, or leave them out until they have real content?
- [ ] **Education curation** — do a quick pass to dedupe the 27 drafts first, or import all of them under `Education/drafts/` and curate after?
- [ ] **Domain reasoning docs in BPF** — keep `BPF/00-Reading/02-Reasoning-GOV.md` and `BPF/00-Reading/03-Reasoning-LT.md` in BPF (recommended — they're BPF's framing of those domains, not the domains themselves), or move them into `GOV/` and `LT/`?
- [ ] **`zz-Absurdity/` visibility** — does it stay public in the new repo? It documents project history honestly, but contains transcripts mentioning "Sparky" and "the Sixth Estate" that aren't in canonical docs. Keep / rename / move to a private-archive / drop?
- [ ] **Foundation name** — "Bounded Power Foundation" or change it? (Affects every doc that mentions it; if changing, do it before Phase 4 so the migration captures the new name.)

---

## Phase 1 — Structural fixes to current repo (mechanical, do these first)

These are pure text edits, no judgment calls. Fixing them before migration means the rename-and-reset capture clean content rather than carrying these forward.

### High severity — framework contradicts itself

- [ ] **Duplicate `SCBP-REG-0016`** — both `SCBP-REG-0016-CEI-OH.md` and `SCBP-REG-0016-UH.md` declare `mechanism_id: SCBP-REG-0016` in their YAML. Bump one of them (e.g., UH becomes 0019, or renumber 0017/0018 to make room).
- [ ] **SCBP-08 broken Charter cross-references** — §I says "per Registry Charter §7" for operational window (Charter §7 is actually about self-review/conflict). §X references "Registry Charter §10" for operator recusal (Charter only has §§1–8; recusal is in §7). Both pointers in SCBP-08 are wrong.
- [ ] **Registration Form line 781 broken Charter cross-reference** — cites "Charter §7" for 7-day publication window. Charter §7 doesn't define any 7-day window. The 7-day window isn't actually defined in the Charter at all. Either move the definition into the Charter or remove the cross-ref.
- [ ] **`04-Registry/README.md` broken file links** — multiple links target `SCBP-REG-0001.md`; actual filename is `SCBP-REG-0001-BPF.md`. Affects: section header link, "Records filed" table link, YAML convention section, operating instructions section.
- [ ] **Root README references `99-Archive` (line 78)** — folder is actually `zz-Absurdity`. Either fix the README pointer or rename the folder.
- [ ] **Registration Form version contradiction** — header revision history lists v1–v5; footer line 795 reads "Registration Form (v4)". Pick one.

### Medium severity — visible but not load-bearing

- [ ] **Duplicate suffix `SHMC-OH`** on REG-0003 (Shaker Heights Municipal Court) and REG-0004 (City of Shaker Heights). The acronym naturally maps to the court. Pick a different suffix for the city record (e.g., `CITYSH-OH` or `SH-OH`).
- [ ] **HOA example uses non-canonical harm category `chronic_asymmetry`** in YAML. Not in R21, not in SCBP-09 §VI, not in form §4. Either add it to §4.7 as an authorized extension or remove from the YAML.
- [ ] **Hash registry artifact list points at `04-Registry/SCBP-REG-0001.md`** — file doesn't exist at that path. Fix the artifact list before the eventual hash regeneration.
- [ ] **AI Registration Bundle snapshot date is 2026-05-15, predates 2026-05-16 SCBP-08/09 revisions** — re-snapshot when convenient. The bundle says "if this bundle and the repository disagree, the repository wins," but the sync is manual.

### Low severity — housekeeping

- [ ] **No LICENSE file** — Findability §3 explicitly anticipates mirroring/forking; without a license the legal default in most jurisdictions blocks both. Add a license before public expansion.
- [ ] **No `.gitignore`, `CONTRIBUTING.md`, issue/PR templates** — minor scaffolding. Add a `.gitignore` for OS junk (`.DS_Store`, `Thumbs.db`); the rest can wait.
- [ ] **`zz-Absurdity/` filename hygiene** — inconsistent casing (`Absurdity-` vs `absurdity-`), random-string suffixes (`-&aq.md` contains a shell-unsafe `&`). Rename to consistent slugs if keeping.

---

## Phase 2 — Intellectual fixes (optional, by your call)

These are content decisions, not edits. Most are not load-bearing — the framework's logic holds without resolving them. Resolve as time/will allow.

### Worth a real decision

- [ ] **R56 self-violation** — framework requires hashed canonical artifacts; hash registry is openly out of date, which means by R56's text none of the artifacts is currently "official." Either add a §12 disclosure in SCBP-REG-0001 acknowledging the gap, or carve out a "freeze pending" state in R56 itself.
- [ ] **Voice break between README and Reasoning-BPF** — README/SCBP-01 use accessible register; Reasoning-BPF shifts hard into terminal-voice ("Terminal Boundary," "structural vocabulary is exhausted"). Either signal the shift in the reading order, or have Reasoning-BPF open with a register note.
- [ ] **README "stability" vs Reasoning-BPF "continuity is not a value"** — README §"Core principle" lists "stable enough to preserve continuity"; Reasoning-BPF says continuity is hazardous. Reconcile or note the distinction.
- [ ] **Foundation's own three-stop-path claim under its own SCBP-09 §IV** — SCBP-09 §IV says three paths that all depend on the authority's internal cooperation aren't three paths. REG-0001 declares paths that mostly run through the single maintainer. Either acknowledge it's met formally but not substantively (consistent with the dull-truth register the framework asks of others), or carve out a small-authority exception.
- [ ] **AI labor as undeclared Type 1/3 dependency** — README's primary path is "paste bundle into AI chat." By the framework's own taxonomy that's a dependency on third-party AI providers. REG-0001 declares zero Type 1 dependencies. Add a §6 disclosure.

### Framing polish

- [ ] **"Bounded Power Foundation" name does remedial work everywhere** — every reference is followed by "is the proposed name for a future custodial body that does not currently exist." Either accept this as the cost of keeping the name, or do one central acknowledgment so downstream references can stop walking it back.
- [ ] **Vestigial "citizen diagnostic" language** in Citizen Inquiry Guide — Form v5 collapsed the two-class model, but the guide still uses "citizen-produced structural diagnostic" extensively. Decide if intentional or vestigial.
- [ ] **"The Sixth Estate" appears in `zz-Absurdity` transcripts** as if it was once a project name; nowhere in canonical docs. Orphaned vocabulary will confuse readers who look it up.

---

## Phase 3 — Migration prep

After Phase 1 (and as much of Phase 2 as you want). Before touching folder structure.

- [ ] **Final commit on current repo** with a recognizable message (e.g., `pre-rename-final`).
- [ ] **Decide and write down the new repo name** (Phase 0 decision).
- [ ] **Sketch the multi-domain README** that will live at the new repo root — what does it say about the relationship between BPF, GOV, LT, etc.?
- [ ] **Decide what `zz-Absurdity/` says about the project** when seen by a new reader (Phase 0 decision).

---

## Phase 4 — Restructure into multi-domain tree

This is the actual rename-and-reset step. Proposed tree:

```
<repo-root>/
├── README.md                          ← multi-domain orientation
├── LICENSE
├── .gitignore
├── BPF/                               ← current repo content
├── GOV/
├── LT/
├── Education/
├── INFRA/
├── DATA/                              ← if Phase 0 says include
├── ECON/                              ← if Phase 0 says include
├── TECH/                              ← if Phase 0 says include
└── zz-Absurdity/                      ← if Phase 0 says keep
```

### Migration sub-tasks

- [ ] **Rename current repo to `<name>-draft`** in GitHub settings.
- [ ] **Create new repo** with the agreed name. Initialize empty — no README, no .gitignore from GitHub's templates.
- [ ] **Build `BPF/` subfolder** containing the entire current `Bounded-Power-Framework-main` content. The current root README becomes `BPF/README.md`.
- [ ] **Merge SCBP zip contents into `BPF/05-Reference/`** as numbered reference docs:
  - [ ] `!!!-IMPORTANT-Canonical Text Standard.txt` → `BPF/05-Reference/02-Canonical-Text-Standard.md` (rename to remove the `!!!`, convert encoding to LF, slot into 05-Reference numbering).
  - [ ] `Civilian Red Button.txt` → `BPF/05-Reference/06-Civilian-Red-Button.md`.
  - [ ] `AUTHORITY_SURFACE_MAPPING_GUIDE_v0.02.txt` → `BPF/05-Reference/07-Authority-Surface-Mapping-Guide.md`.
- [ ] **Build `GOV/` folder** honoring GOV-MASTER.md's recommended layout (core / operations / safeguards / standards subfolders + GOV-MASTER.md at root of folder + a `GOV/README.md`).
- [ ] **Build `LT/` folder** — flat or grouped by phase. Move the 236KB JPEG to `LT/images/`. Add `LT/README.md`.
- [ ] **Build `Education/` folder** — decision-dependent. If curating first, do that and structure accordingly. If not, put everything in `Education/drafts/` with a clear `Education/README.md` flagging the state.
- [ ] **Build `INFRA/` folder** — three files; flag in README that it's early-stage.
- [ ] **Build placeholder folders (`DATA/`, `ECON/`, `TECH/`)** if Phase 0 said yes. Each gets its `<X>-Framework.md` stub and a README flagging "placeholder."
- [ ] **Move `zz-Absurdity/` to root** if keeping it.
- [ ] **Write root `README.md`** that orients across all domains and explains the relationship between BPF and the other domains.
- [ ] **Add `LICENSE`** (your choice — Creative Commons for the docs is common for this kind of project; MIT/Apache for any code; pick what matches your intent).
- [ ] **Add `.gitignore`** (minimum: `.DS_Store`, `Thumbs.db`, `*.swp`).
- [ ] **Tag the first commit on the new repo as `v1.0.0`** and push the tag.

---

## Phase 5 — Post-migration sanity

After the new repo is live.

- [ ] **Fix all cross-references inside `BPF/`** that previously pointed at root-level paths (e.g., `../README.md` references now go to `BPF/README.md` or to root `../../README.md` depending on direction).
- [ ] **Update SCBP-08 §X "Relationship to Other Documents"** if Charter section pointers were corrected in Phase 1.
- [ ] **Cross-link domains where they reference each other** — `BPF/00-Reading/02-Reasoning-GOV.md` should link to `../../GOV/`; `BPF/00-Reading/03-Reasoning-LT.md` should link to `../../LT/`. Add reciprocal links from each domain's README back to its BPF reasoning doc.
- [ ] **Update `BPF/README.md`** to acknowledge it's now one of N domains, not the whole repo.
- [ ] **Update `-draft` repo's README** to point at the new canonical URL.
- [ ] **Re-snapshot the AI Registration Bundle** with the new repository paths (`Bounded-Power-Framework` references inside the bundle will need to point at the new repo + the `BPF/` subfolder).
- [ ] **Regenerate the hash registry** once content is stable (this becomes worth doing only after the dust settles — possibly weeks after migration).

---

*Working checklist. Edit freely as you go.*
