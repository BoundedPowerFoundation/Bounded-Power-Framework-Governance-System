---

# DO NOT READ THIS ENTIRE FILE, JUST THE TOP PORTION

---

This file is for the AI, not for you. If you want to analyze an
authority, just follow these three steps:

  1. Press Ctrl-A, then Ctrl-C to copy this entire file.
     (On a Mac: Cmd-A, then Cmd-C.)

  2. Open an AI chat (Claude, ChatGPT, Gemini, or whichever you use).
     Click into the message box. Press Ctrl-V (Cmd-V on Mac) to paste.
     You may see the pasted content appear as a small attachment or
     "file" rather than visible text. That is normal. The AI can read it.

  3. On a new line after the paste (or in a follow-up message), type
     the name of the power-bearing authority you want analyzed.
     Examples:
       Cleveland, OH Police Department
       Springfield, MA Public Schools
       Acme Health System
     You can also ask the AI for a list of power-bearing authorities from a paticular area for you to select from

     Then send.

The AI will produce a completed Mechanism Record and offer it to you
as a downloadable file. If you produced the record from public sources
rather than as the authority being analyzed, the file will be clearly
labeled `PUBLIC SOURCES ONLY` — meaning it has not been confirmed by
the authority it describes.

If the AI seems confused, tell it: "Use the attached bundle and produce
a Mechanism Record for [your authority name]. Begin with Part 1."

That is all you need to do. Everything below this point is reference
material for the AI.

---

# Bounded Power Framework — AI Registration Bundle

**Snapshot date:** 2026-05-15

This bundle is a snapshot of the following files from the Bounded Power Framework repository (https://github.com/BoundedPowerFoundation/Bounded-Power-Framework). The repository copies are authoritative. If this bundle and the repository disagree, the repository wins.

- Registration Form — canonical path: `02-Forms/01-Registration.md`
- SCBP-04 Structural Constitution v1.3 — canonical path: `01-Framework/SCBP-04-Structural-Constitution-v1.3.md`
- SCBP-09 Registry Acceptance Standards v1.0 — canonical path: `01-Framework/SCBP-09-Registry-Acceptance-Standards-v1.0.md`
- Registration Process Methodology — canonical path: `05-Reference/01-Registration-Process-Methodology.md`

The bundle is organized into five parts:

- **Part 1** — Instructions for the AI (the prompt). This is what tells the AI what to do.
- **Part 2** — Registration Process Methodology. The step-by-step method the AI follows.
- **Part 3** — The Registration Form. The actual form to be filled out.
- **Part 4** — SCBP-04 Structural Constitution. The binding rules the form references.
- **Part 5** — SCBP-09 Registry Acceptance Standards. The numerical bounds the form's declarations must fall within.

---

# PART 1 — Instructions for the AI

You are being asked to produce a completed Bounded Power Framework Mechanism Record using publicly available information. The user will provide the name of the power-bearing authority in their message (either appended to the pasted bundle or in a follow-up message). If the user has not specified an authority, ask them once: "Which power-bearing authority would you like analyzed?"

By default, the user is a third party (citizen, journalist, researcher, civic actor) producing a structural diagnostic from public sources, not the authority itself. Records produced this way set `filed_by: third_party` in the YAML and carry the `PUBLIC SOURCES ONLY` banner at the top and bottom of the body. If the user instead indicates they are filing on behalf of the authority being described, set `filed_by: authority`, status `ACTIVE`, and omit the banner. Either way, the same form, the same rules, and the same structural floor apply.

## What you have

Parts 2–5 of this bundle contain everything you need:

- Part 2: a process methodology describing how to fill out the form (Steps 1–8)
- Part 3: the Registration Form (13 sections)
- Part 4: SCBP-04, the binding constitutional rules the form references by number
- Part 5: SCBP-09, the numerical bounds the form's declarations must fall within

## What to do

1. **Read Parts 2–5 before drafting.** All four are needed. Part 4 is binding; Part 2 is your operating manual.

2. **Do not pause for human review.** Produce the full Mechanism Record in one pass. Where the methodology describes a Step 2 human checkpoint, replace it with in-form annotations: when you would have asked the human a clarifying question, instead note your choice and the alternative directly in the relevant field of the form using the format `ANNOTATION: [your note]`. A human reviewer will read the completed record and address annotations afterward.

3. **Reproduce the form exactly.** Preserve all 13 section numbers, all field labels, all checkboxes, all rule footnotes. Do not summarize, reorganize, omit, or rename anything. Include §13 (Submitter) even though it is metadata.

4. **Use publicly available information.** Web search is encouraged where you have access to it. Do not invent facts.
   - Where information is unknown or cannot be reasonably determined from public sources: write `UNKNOWN`.
   - Where information is estimated: write `ASSUMPTION: [brief explanation]`.
   - Where you made a judgment call a human reviewer should be aware of: write `ANNOTATION: [brief note]`.
   - Do not guess. UNKNOWN is better than a wrong answer.

5. **Use the dull-truth register** described in Part 2 (Step 4):
   - Institutional voice ("the authority commits," "the authority acknowledges")
   - Framework vocabulary does the analytical work — terms like "capture risk," "non-consenting population," "structural alignment," "threshold proximity" carry the meaning
   - State numbers directly; do not editorialize
   - No opinion-forcing adjectives: avoid "extracts," "predatory," "regressive," "hostile," and similar — they pre-load a conclusion the framework's structure should surface on its own. ("Captured" as in "regulatory capture" is also opinion-forcing in this context; "captured" as a passive verb meaning "recorded" is fine.)
   - The test: a defender and a critic of the institution should both call your prose factually accurate

6. **Stay within SCBP-09 numerical bounds.** Specifically:
   - §10.4 (renewal interval): must be 1–10 years
   - §10.7 (aggregate trigger threshold): bounds depend on the non-consenting population declared in §2.3 (see Part 5, §II proportional table)
   - §10.9 (response window): 7–90 days, default 30
   - §5 (stop paths): minimum 3 declared

7. **Run a self-verification pass before declaring done.** Confirm:
   - All 13 sections present
   - No opinion-forcing words (search your output for: extract, predator, prey, crush, hostile, regressive)
   - All R-citations used appear in Part 4 (SCBP-04 rules range R01–R81)
   - §10.4, §10.7, §10.9 values within SCBP-09 bounds
   - At least 3 stop paths declared in §5
   - §13 filled in (this is the most commonly skipped section)
   - For records where `filed_by` is `third_party`: the `PUBLIC SOURCES ONLY` banner appears at the top and bottom of the output. For records where `filed_by` is `authority`: no banner appears.
   - **YAML-vs-body consistency.** The YAML frontmatter must match what the body actually declares. Verify each pairing:
     - `authority_classification` matches §1.3 (`direct`, `indirect`, or `both` — must match the box checked in §1.3, and if §1.3 shows the substantive answer is "both" with both individual boxes checked, the YAML value is `both`)
     - `renewal_interval_years` matches §10.4
     - `aggregate_threshold_count` matches §10.7's number-of-triggers value
     - `aggregate_threshold_window_days` matches §10.7's window value
     - `response_window_days` matches §10.9
     - `harm_categories_declared` enumerates the categories actually declared in §4.1–§4.6 (use the framework's six category names: bodily_harm, agency_impairment, ecological_damage, generational_binding, communicative_suppression, informational_sovereignty; add chronic_asymmetry only if §4 explicitly declares it)
     - `dependency_count_type1`, `dependency_count_type2`, `dependency_count_type3` match the counts in §6.1, §6.2, §6.3
     - `capture_risk_identified` reflects §6.4's declaration
     - The five §12 acknowledgment flags (`disclosure_completeness_assertion`, `update_obligation_committed`, `discoverability_acknowledged`, `burden_of_proof_acknowledged`, `anti_weaponization_acknowledged`) reflect the actual checkbox state of §12.1–§12.5 — values must be `true` or `false`, not strings
     - `affected_population_estimate` and `non_consenting_population_estimate` match §2.2 and §2.3
     - `registered_date`, `snapshot_date`, and `last_reviewed_date` are all today's date for a newly produced record
     - `filed_by` is `authority` for self-registrations and `third_party` for records produced by anyone other than the authority itself
     - `status` is `PUBLIC_SOURCES` when `filed_by` is `third_party`, and `ACTIVE` when `filed_by` is `authority`
     - The `mechanism_id` follows the naming rule in step 7.5
     - If any pairing does not match, fix the YAML to match the body (the body is authoritative)

7.5. **Mechanism_id, filename, and the authority-after-citizen rule.** The mechanism_id and filename follow a deterministic convention so the registry stays internally consistent at scale and so any AI working from this bundle produces the same identifier for the same authority.

   **Mechanism_id.** All Mechanism Records — both self-registrations by authorities and records produced by third parties — use sequential numbering: `SCBP-REG-####`, where `####` is the next zero-padded sequential number after the highest existing `SCBP-REG-####` in the registry. The number identifies the record permanently; it never changes after assignment. The mechanism_id does not encode who filed the record, what the authority is, or where it is located — that information lives in the YAML fields (`filed_by`, `mechanism_name`, `authority_acronym`, `country`, `region`, `subregion`).

   **Filename.** The filename combines the mechanism_id with a short descriptive suffix for human readability: `SCBP-REG-####-{DESCRIPTIVE-SUFFIX}.md`. The descriptive suffix is constructed as follows:

   - If the authority has a widely-used acronym, use it in uppercase (e.g., `CCCC`, `NYPD`, `FOMC`, `LAUSD`).
   - If the acronym could refer to authorities in multiple jurisdictions, append a two-letter region code separated by a hyphen. Use the U.S. two-letter state code for U.S. authorities (e.g., `CCCC-OH` for the Cuyahoga County Corrections Center). For non-U.S. authorities use the ISO 3166-1 alpha-2 country code (e.g., `-UK`, `-DE`).
   - If no widely-used acronym exists, use the authority's short name in UPPER-KEBAB-CASE, abbreviated to a reasonable length (e.g., `BAYVIEW-HOA`, `RIVERBEND-SCHOOLS`).
   - National or federal authorities take no region suffix.
   - Examples of full filenames: `SCBP-REG-0002-CCCC-OH.md`, `SCBP-REG-0003-NYPD.md`, `SCBP-REG-0004-FOMC.md`, `SCBP-REG-0005-BAYVIEW-HOA.md`.

   **Sequence-number determination.** Before assigning a mechanism_id, determine the next sequential number:

   - **If you have file-system access to the repository** (you can list files in `04-Registry/`): list the existing records, find the highest existing `SCBP-REG-####` number, and use the next integer. If `SCBP-REG-0001` and `SCBP-REG-0002` exist, the next record is `SCBP-REG-0003`.
   - **If you cannot inspect the registry folder** (chat-only environment with no file-system access): tell the user: "I need to know the next sequential record number to assign a mechanism_id. Could you check the `04-Registry/` folder and tell me the highest existing `SCBP-REG-####` number? I'll use the next integer." Wait for the user's answer before producing the file.

   **Idempotency — do not silently overwrite.** Before creating the file, check whether a record about this authority already exists in the registry. An existing record is identified by matching `mechanism_name`, `authority_acronym`, and location fields (`country`, `region`, `subregion`) — not by sequential number, because a new sequential number could be a duplicate record about the same authority.

   - **If you have file-system access:** scan existing records' YAML frontmatter for a match on authority identity. If a match exists, this is a re-evaluation or an authority-after-citizen update, not a new record — follow step 9 (re-evaluation) instead of step 8 (new output). Do not overwrite the existing file.
   - **If you cannot inspect the registry folder:** before producing the file, tell the user: "I'm about to create a new record for `{authority name}` at `{filename}`. If a record about this authority already exists in your registry, you may want to use the re-evaluation protocol in step 9 of the bundle instead. Should I proceed with a new record, or do you want to provide the existing file for re-evaluation?" Wait for the user's answer before producing the file.

   **Authority-after-citizen rule.** When an authority files a record about itself and a third-party-produced record about that same authority already exists in the registry, the authority's filing updates the existing record in place rather than creating a new file. The mechanism_id and filename stay the same. The YAML changes: `filed_by` flips from `third_party` to `authority`, `status` flips from `PUBLIC_SOURCES` to `ACTIVE`, `record_version` increments (v1 → v2), `last_reviewed_date` updates to today, and `snapshot_date` updates if body content materially changes. The `PUBLIC SOURCES ONLY` banner is removed from the top and bottom of the body. The Renewal Log inside the body records the transition with a one-line entry: "v# — {date}: authority filed corrections to prior third-party-produced version. Changes: {summary}." Git history preserves the third-party-produced version.

8. **Output format.** Produce the completed Mechanism Record as a single markdown file the user can download.

   **YAML frontmatter.** Use the exact schema below. Do not invent fields, rename fields, or omit fields. Every field listed must appear, even if the value is `UNKNOWN`. The same schema applies to every Mechanism Record regardless of who filed it.

   ```yaml
   ---
   mechanism_id: SCBP-REG-{####}                 # sequential, per step 7.5; same convention for all records
   mechanism_name: "{Full name of the authority in quotes}"
   authority_acronym: "{The short name people actually use, or UNKNOWN if no widely-used acronym exists}"
   status: PUBLIC_SOURCES                        # PUBLIC_SOURCES when filed_by is third_party; ACTIVE when filed_by is authority
   filed_by: third_party                         # authority | third_party
   domain: {one of: government, healthcare, education, finance, technology, housing, employment, voluntary_association, economic, information_governance_infrastructure, criminal_justice, other}
   authority_classification: direct              # direct | indirect | both
   country: {ISO 3166-1 alpha-2 country code, e.g. US, UK, DE}
   region: {state/province code; for US authorities use the two-letter state code, e.g. OH, CA; for non-US, the equivalent first-level administrative division code or UNKNOWN}
   subregion: {county or local administrative region as free text, or UNKNOWN, or not_applicable for federal/multi-county authorities}
   primary_postal_code: {ZIP or postal code of headquarters/main address, or UNKNOWN}
   primary_address: "{Free-text street address of the authority's headquarters or main operational location, or UNKNOWN}"
   primary_url: "{Official website URL, or UNKNOWN}"
   tax_id: "{EIN or equivalent tax/registration identifier, or UNKNOWN, or not_applicable for government agencies and other entities that have none}"
   registered_date: {YYYY-MM-DD — today for a new record; never changes after}
   snapshot_date: {YYYY-MM-DD — as-of date for the content; same as registered_date for a new record; moves forward only when body content is materially updated}
   last_reviewed_date: {YYYY-MM-DD — when the record was last validated; same as registered_date for a new record; moves forward on every review even if no changes}
   record_version: v1                            # increments when content materially changes (v1, v2, v3...)
   authorization_date: {YYYY-MM-DD or UNKNOWN}   # when the authority itself was authorized — about the authority, not the record
   expiration_date: {YYYY-MM-DD or UNKNOWN}      # when the authority's authorization expires
   renewal_interval_years: {1-10, integer}       # must match §10.4
   funding_types:                                # list; use values like: state_government_mandatory, local_government_mandatory, federal_government_discretionary, private_for_profit, private_nonprofit, self_funded_fee_for_service, member_dues, voluntary_contributions, mixed
     - {funding type}
   funding_concentration_max_pct: {0-100, integer or UNKNOWN}
   affected_party_categories:                    # list; use values like: general_public, residents_of_geographic_area, customers, members, employees, students, patients, regulated_industry, criminal_justice_involved, children, vulnerable_populations, non_consenting_third_parties
     - {category}
   affected_population_estimate: {integer or UNKNOWN}
   non_consenting_population_estimate: {integer or UNKNOWN}
   entity_size: {micro | small | medium | large | massive}
   geographic_specificity: {single_address | single_municipality | multi_municipality | single_county | multi_county | single_state | multi_state | national | global}
   geographic_reach: "{Free-text description of geographic reach in quotes}"
   aggregate_threshold_count: {integer; must match §10.7's number-of-triggers value and fall within SCBP-09 §II bounds for the declared non_consenting_population_estimate}
   aggregate_threshold_window_days: {integer; must match §10.7's window value}
   response_window_days: {7-90, integer; must match §10.9}
   harm_categories_declared:                     # list; use only these six values, plus chronic_asymmetry if §4 explicitly declares it
     - bodily_harm                               # include only if §4.1 declares thresholds (not "Not applicable")
     - agency_impairment                         # include only if §4.2 declares thresholds
     - ecological_damage                         # include only if §4.3 declares thresholds
     - generational_binding                      # include only if §4.4 declares thresholds
     - communicative_suppression                 # include only if §4.5 declares thresholds
     - informational_sovereignty                 # include only if §4.6 declares thresholds
   algorithmic_decision_systems_used: {true | false}
   dependency_count_type1: {integer; matches §6.1 count}
   dependency_count_type2: {integer; matches §6.2 count}
   dependency_count_type3: {integer; matches §6.3 count}
   capture_risk_identified: {true | false; matches §6.4 declaration}
   disclosure_completeness_assertion: {true | false; matches §12.1 checkbox}
   update_obligation_committed: {true | false; matches §12.2 checkbox}
   discoverability_acknowledged: {true | false; matches §12.3 checkbox}
   burden_of_proof_acknowledged: {true | false; matches §12.4 checkbox}
   anti_weaponization_acknowledged: {true | false; matches §12.5 checkbox}
   ---
   ```

   Replace each `{...}` placeholder with an actual value or with `UNKNOWN`. Do not leave placeholders in the output. The comments (after `#`) explain each field and should not appear in the final YAML.

   **The full form structure**, with every field filled per the rules above.

   **Banner.** For records where `filed_by` is `third_party` (records produced from public sources by anyone other than the authority itself), the label `PUBLIC SOURCES ONLY` appears as a banner at the top and bottom of the file body — not as a YAML field. The banner signals that the record has not been confirmed by the authority it describes. For records where `filed_by` is `authority` (the authority filing its own self-registration), no banner appears.

If your environment allows file creation, save the output as a downloadable file. If not, present it inline and tell the user how to save it as a `.md` file.

9. **Re-evaluating or validating an existing record.** If the user asks you to validate, verify, or re-evaluate a previously produced Mechanism Record rather than create a new one, do the following:
   - Read the existing record in full before searching for current information.
   - Search public sources for the authority as it exists today.
   - Compare the existing record's declarations against current findings, field by field. Note: changes in the authority (new contracts, new incidents, changed leadership, expanded scope, new oversight findings) that would alter declarations in §1–§9; changes in numerical declarations in §10 that would push values outside SCBP-09 bounds; UNKNOWN fields that are now answerable from new public information; declarations that now contradict current public information.
   - Re-run the §7 self-verification pass against the record as it currently stands, including the YAML-vs-body cross-checks. Discrepancies introduced by the original drafting (not by changes in the authority) are also findings.
   - Produce a structured comparison: what is unchanged, what should be updated, what is newly UNKNOWN, what is newly answerable. Do not silently rewrite the record. The user decides which findings warrant an update.
   - **Date field handling on re-evaluation.** `registered_date` never changes — it is the immutable date the record first entered the registry. `last_reviewed_date` always moves to today on any review, even one that finds no changes (this distinguishes "checked and stable" from "never re-checked"). `snapshot_date` moves to today only if the body content is materially updated. `record_version` increments only if the body content is materially updated (v1 → v2). A review that finds no changes updates only `last_reviewed_date`.
   - If a substantive update is warranted, the update is recorded inside the file per the Registry Charter's append-only convention — a dated note in the record describing what changed and why, with prior versions preserved in git history.

## A note about Violation Reports

If the user's interest is in documenting a specific incident (something the authority did, failed to do, or threatened to do on a specific date) rather than analyzing the authority's overall structure, the appropriate artifact is a Violation Report, not a Mechanism Record. Violation Reports are shorter, focused on a single incident, and use a different form (canonical path `02-Forms/02-Stop-Trigger.md`).

If the user describes a specific incident rather than asking for a structural analysis, ask them: "Would you like a structural Mechanism Record analyzing this authority overall, or a Violation Report documenting this specific incident?" Then proceed accordingly. The bundle contains the Registration Form for Mechanism Records; for a Violation Report, work from the form structure described in `02-Forms/02-Stop-Trigger.md` in the repository.

---


# PART 2 — Registration Process Methodology

*The step-by-step method for filling out the form. The AI should read this in full before drafting.*

---

# Filling Out the SCBP Registration Form — Process & Methodology

*Written for the project lead, May 2026, after producing 10 dull-truth `REG-` examples and 10 fact-only `EDU-` educational versions in a single working session.*

---

## Part 1 — What I actually did this session

### 1.1 Starting state

You arrived with:
- The v4 registration form (locked, hash-registered)
- 11 stress-test outputs (`STRESS-TEST-1` through `STRESS-TEST-11`) produced over three rounds in a prior session, each fully populated under a fictional authority name (Riverbend, Atlas, MeshCast, etc.)
- A request: rewrite the stress-test outputs with generic domain-based names for an `/examples/` directory on the GitHub repo, and write educational versions for materials outside the repo.

The bad-faith stress-test was excluded from both deliverables — it's an adversarial-testing artifact that demonstrates evasion, not a model registration.

### 1.2 What I produced

Final deliverables:
- 11 renamed stress-test files (`/renamed-stress-tests/`) — content unchanged, filenames generified
- 10 dull-truth registration examples (`REG-` prefix) for the GitHub `/examples/` directory
- 10 fact-only educational examples (`EDU-` prefix) for educational materials outside the repo

### 1.3 The naming work

For the filenames I converted the fictional protagonist of each stress-test into a descriptive domain label:

| Stress-test name | Generic label |
|---|---|
| Riverbend Parking Enforcement Bureau | MUNICIPAL-ENFORCEMENT |
| Atlas Credit Reporting Services | CONSUMER-CREDIT-REPORTING |
| Consumer Goods Quality Initiative | VOLUNTARY-ADVOCACY |
| RHCVA (Section 8 voucher administrator) | RENTAL-SUBSIDY-ADMINISTRATION |
| Northstar Predictive Analytics | RISK-SCORING-VENDOR |
| Riverbend Unified School District | SCHOOL-DISTRICT |
| Riverbend Regional Health System | HOSPITAL-SYSTEM |
| Riverbend Covenant Assembly | CONGREGATIONAL-DISCIPLINE |
| MeshCast (social platform T&S) | PLATFORM-CONTENT-MODERATION |
| Maple Ridge HOA | HOA |

The criterion was: descriptive of the function without forcing a judgment. Early candidates like "MUNICIPAL-COERCIVE" and "BAD-FAITH-AUTHORITY" failed that test — they pre-loaded a conclusion. "MUNICIPAL-ENFORCEMENT" describes what the institution does; readers form their own conclusions.

### 1.4 The content work — three registers

The harder problem was prose calibration. We iterated through four registers before locking the right ones:

| Register | What it sounds like | When used |
|---|---|---|
| **Industry euphemism** | "Funded primarily through user-generated revenue mechanisms supporting public-safety operations" | Never used; this is what we were stripping out |
| **Dull truth / plain-disclosure** | "Citation revenue constitutes ~65% of operating budget. The §4.7 capture threshold sets a 75% ceiling. Revenue mix is monitored monthly." | The `REG-` files (GitHub examples) |
| **Fact-only, no softening** | "Of total operating budget, ~65% comes from fines paid by cited drivers. Unpaid balances are sent to collections, which appear on consumer credit reports and affect access to housing, employment, and credit for up to 7 years." | The `EDU-` files (educational) |
| **Hostile / blunt** | "The authority extracts revenue from drivers... 65% revenue dependency creates structural alignment between enforcement volume and operational continuity — enforcement intensity is not independent of revenue need." | Rejected — pre-loads judgments |

The principle separating dull-truth from fact-only is **what gets stated explicitly**:
- Dull-truth states the function in institutional voice, lets framework infrastructure (R-numbers, "capture threshold," "non-consenting population") do the analytical work. A defender of the institution can read it and recognize their operation.
- Fact-only adds the downstream consequence chains and the structural mechanics in functional language. Same numbers, more of the cause-effect spelled out. A reader without framework fluency can see what the institution does and to whom.

The principle separating fact-only from hostile is **whether the prose forces an opinion**. "Extracts revenue from drivers" forces a judgment (extraction is adversarial framing). "65% of operating budget comes from fines paid by cited drivers" is the same information without the framing. A hostile critic and a defender would both call the second one accurate.

### 1.5 Genericization rules I settled on

Within the form, the following pattern worked:

- **The authority's own name** → the domain label (e.g., "MUNICIPAL-ENFORCEMENT-EXAMPLE")
- **Self-references** ("the Bureau," "RRHS," "MeshCast") → "the authority" or "the Council" or "the platform" as fits the institutional type
- **Geographic context** (cities, counties, states) → `[CITY, STATE]`, `[COUNTY 1] and [COUNTY 2], [STATE]`, `[STATE]`
- **External bodies referenced** (the city council, the local court, the state DPH) → `[CITY COUNCIL]`, `[MUNICIPAL COURT]`, `[STATE DEPARTMENT OF PUBLIC HEALTH]`
- **Specific statutes / ordinances that are fictional** → `[MUNICIPAL ORDINANCE]`, `[STATE] Mental Health Code`
- **Fictional vendor names** → `[BOOT VENDOR]`, `[LPR CAMERA VENDOR]`, `[ELECTRONIC HEALTH RECORD VENDOR]`, `[PRIMARY SCORING ALGORITHM VENDOR]`
- **Specific dates** → `[DATE]`, `[AUTHORIZATION DATE]`, `[EXPIRATION DATE]`
- **Specific identifiers / numbers in `mechanism_id`** → `SCBP-REG-EXAMPLE-{DOMAIN}` (so the ID itself signals it's an example)

What gets preserved:
- **Quantitative data** (population sizes, dollar figures, percentages, threshold values) — these are the worked-example content; stripping them gives you a blank template instead of an example
- **Real federal infrastructure** (FCRA, CFPB, FTC, HUD, HIPAA, EMTALA, Joint Commission, NCMEC, Section 230, DSA, DMCA, COPPA, etc.) — these are universal regulatory facts; removing them removes the document's accuracy
- **Framework rule citations** (R26, R55, R64, R66, R74, R79, R81, etc.) — framework infrastructure
- **Field labels** that contain the word "coercive" (the form's own structural vocabulary) — distinct from prose use of the word

What gets removed:
- **Specific real-entity names** that aren't universal infrastructure (FICO → `[PRIMARY SCORING ALGORITHM VENDOR]`; Equifax/TransUnion → "the other two major US consumer credit reporting agencies"; Epic → `[ELECTRONIC HEALTH RECORD VENDOR]`; Apple/Google as app store gatekeepers → `[APP STORE GATEKEEPERS]`)
- **Stress-test framing** that called out the document as a stress test ("This is the most complex regulatory environment of any case in this stress test" — removed)
- **Bold emphasis used for editorial weight** rather than framework-defined emphasis

### 1.6 Lessons learned this session

**Calibration takes iteration.** I delivered three different versions of the municipal enforcement file before the register was right. Each iteration was specific feedback from you about what felt off, and each time I overshot in the opposite direction before settling. Plan for at least one sample-review cycle on any new domain before producing a full set.

**The bad-faith file doesn't belong with the legitimate examples.** Its content demonstrates evasion. A real authority finding it in an `/examples/` directory and using it as a starting template would be filing a worked example of how to game the framework. We excluded it on the right grounds; preserve that exclusion. If you ever want it published, put it in adversarial-testing materials with prominent labels, not in the example directory.

**Session state was sometimes inconsistent.** Twice I tried to write a file that already existed from earlier in our session — and the cached version had bugs in it (the FICO references that I'd claimed to have fixed but hadn't). Always verify the actual file state before continuing, especially after a long session. The fix is a simple grep for known-bad strings before declaring a file complete.

**The educational versions were lighter-touch than I expected.** Once we settled on "no softening, no opinion-forcing," the educational versions ended up only meaningfully different from the registration versions in §1.2 (functional description), §4 (harm thresholds), and §6.4 (capture risk identification). Most of the form structure produces the same content in both registers. This is good — it means the form itself does most of the structural-disclosure work; calibration choices only affect a handful of high-leverage prose sections.

**Voluntary advocacy was the hardest case for register calibration.** When the institution is mostly aligned with the public's interests, the no-softening register doesn't produce much sharpening relative to the dull register. That's correct, not a failure of the method. The framework treats aligned institutions honestly without manufacturing adversarial framing.

---

## Part 2 — General methodology

This is the distilled method you can apply to fill out the form for any authority, real or worked-example. Steps run in order; later steps depend on outputs of earlier ones.

### Step 1 — Decide what you're producing

Three distinct deliverables, with different rules:

| Deliverable | Audience | Register | Identifier prefix |
|---|---|---|---|
| Real registration (live in the registry) | Public, civic actors, regulators | Dull-truth / plain-disclosure | `SCBP-REG-{NNNN}` |
| Worked example for `/examples/` directory | Authorities considering registration; readers learning the form | Dull-truth / plain-disclosure | `SCBP-REG-EXAMPLE-{DOMAIN}` |
| Educational material outside the repo | Public, journalists, civic educators | Fact-only, no softening | `SCBP-EDU-{DOMAIN}` |

Don't mix these. The biggest single mistake to avoid is producing one document and trying to make it serve all three purposes.

### Step 2 — Map the authority before drafting

Before writing anything in the form, write down (in scratch notes):

1. **What is the institution called?** Both its formal name and its informal self-description.
2. **What does it actually do?** Function in plain language — what binding decisions does it make, against whom, with what consequences?
3. **What is the authority basis?** Statute, contract, license, ordinance, bylaws, recorded covenant, or institutional custom.
4. **Who is the affected population?** Direct, indirect, non-consenting. Get the rough numbers right; the form's thresholds depend on these.
5. **What stops it?** Identify the candidate stop paths before drafting. If you can't name three independent stop paths, the authority has a structural problem the form will surface.
6. **What does it depend on?** Type 1 (extensions acting under it), Type 2 (independent authorities with relationship), Type 3 (infrastructure that, if compromised, would break stop paths against it).
7. **What's the entrenchment story?** What makes this institution hard to dismantle? Sunk infrastructure, regulatory unwinding, downstream effects that propagate beyond the institution.

If you can't answer all seven before writing, fill in the gaps first. Drafting first and then trying to retrofit the answers produces inconsistent records.

### Step 3 — Draft the form, section by section

The v4 form has 13 sections. Work in this order:

1. **§1 (What is this authority?)** — Establish the institution and its functional outputs. Be specific about what the authority can do, can't do, and doesn't do.
2. **§2 (Who can it act upon?)** — Affected populations. Be honest about non-consent: ask whether members technically consenting on signup or property purchase or account creation are meaningfully consenting in the framework's sense. Usually they aren't.
3. **§3 (What can it do and not do?)** — Geographic reach, coercive ceiling, resource ceiling, explicit exclusions, indirect influence boundaries, anti-proxy declaration. The exclusions list is where you commit to the institution's outer bounds.
4. **§4 (What harms can it cause?)** — Each harm category gets a threshold. Use peer benchmarks where they exist; use absolute thresholds where they don't. The harder a number is to set, the more important it is to set one. Vagueness here makes the form unenforceable.
5. **§5 (What stops it?)** — Three stop paths with independence justification. If you can't write three, that's a finding. Document it.
6. **§6 (What does it depend on?)** — Type 1 / Type 2 / Type 3 dependencies. Capture risks. Be honest about funding concentration, customer concentration, regulatory revolving doors, and industry coordination.
7. **§7 (Metrics, signals, decision inputs)** — Declared metrics, indirect signals, algorithmic systems. R79 (metric completeness) and R67 (auditability floor) gaps go here.
8. **§8 (How is it watched?)** — Drift monitoring, capture risk monitoring, audit interfaces, adversarial exposure, structural failure modes.
9. **§9 (How does it end?)** — Dismantling timeline, process, entrenchment factors, data disposition, downstream effect reversibility, replacement feasibility, reversibility verification.
10. **§10 (Authorization, renewal, triggers)** — Authorizing body, dates, renewal interval, aggregate trigger threshold and justification.
11. **§11 (What does it publish?)** — Ledger publication, threshold change log, interpretation change log, renewal process visibility, stop event log.
12. **§12 (Honesty assertions)** — Five checkboxes. Each one is a binding commitment; don't check what you can't actually do.
13. **§13 (Submitter)** — Registry metadata, not part of the public record.

§2.3 (non-consenting population) and §4.7 (additional harm thresholds) are the most-skipped sections in poor registrations. Spend time there.

### Step 4 — Apply the register

After the draft has all the structural content right, do a register pass:

**For real registrations and `REG-` examples (dull-truth):**
- Use institutional voice ("the authority commits," "the authority acknowledges")
- Let framework vocabulary do the analytical work — terms like "capture risk," "non-consenting population," "structural alignment," "threshold proximity" are doing the heavy lifting
- State numbers directly; don't editorialize after them
- "Acknowledges" is the institutional way of admitting a finding; use it where the finding is real

**For `EDU-` educational versions (fact-only):**
- Add downstream consequence chains in §1.2 and §4 (what does the function actually do to people; what is the cause-effect chain)
- Spell out structural mechanics in functional language without softening verbs
- Don't add adjectives that force an opinion ("extracts," "predatory," "regressive," "captured"). The test: a hostile critic and a defender both call the sentence factually accurate
- Where industry euphemisms have crept in, replace with functional verbs ("denies," "removes," "shuts off," "imposes," "forecloses," "excommunicates," "shuns")
- The educational header banner goes at the top; it explicitly says "not a registration template"

### Step 5 — Genericize, if producing a worked example

If this is a worked example, not a real registration, run the genericization pass:

1. **Authority self-references** → the domain label
2. **Geography** → `[CITY, STATE]` placeholders
3. **External bodies referenced** → `[CITY COUNCIL]`, `[MUNICIPAL COURT]`, `[STATE DEPARTMENT OF PUBLIC HEALTH]`, etc.
4. **Fictional statutes** → `[MUNICIPAL ORDINANCE]`, `[STATE] Mental Health Code`
5. **Fictional vendors** → `[BOOT VENDOR]`, `[LPR CAMERA VENDOR]`, etc.
6. **Specific dates** → `[DATE]`, `[AUTHORIZATION DATE]`, `[EXPIRATION DATE]`
7. **Real named entities that aren't universal infrastructure** → genericize ("FICO" → `[PRIMARY SCORING ALGORITHM VENDOR]`)

Preserve:
- All quantitative figures (these are the worked-example values)
- All real federal/national regulatory infrastructure (FCRA, CFPB, HIPAA, EMTALA, NCMEC, Section 230, DSA, etc.)
- All framework R-citations

### Step 6 — Verify before publishing

Before declaring any document complete:

1. **Grep for fictional name leaks.** Run a check for every fictional name used in any source material. A single leftover "Riverbend" or "Atlas" undermines the rest of the document.
2. **Grep for register violations.** For `EDU-` files, search for opinion-forcing words: `extract|predator|prey|crush|hostile|regressive`. For `REG-` files, additionally search for the bolded-for-editorial-weight pattern.
3. **Verify the header and footer.** EDU files need the banner. Both EDU and REG examples need updated footers with cross-references and the correct prefix.
4. **Confirm `status:` field.** `EXAMPLE` for worked examples, `EDUCATIONAL` for educational versions, `ACTIVE` (or whatever your registry uses) for real registrations.
5. **Confirm `mechanism_id` field.** No real registration should have an example-pattern ID, and no example should have a real registry ID.
6. **Cross-reference R-citations.** Make sure every R-number cited is the right rule and that you haven't introduced a citation to a rule that doesn't exist.

A grep pass for these takes one minute. Skipping it is what produced the FICO leak in this session that I had to fix retroactively.

### Step 7 — Calibration check for the specific authority type

Some domains have specific things to get right:

- **Government enforcement authorities** (police, parking, code enforcement): get the funding-source disclosure honest. If revenue depends on enforcement volume, that's the capture risk; don't hide it.
- **Data/scoring authorities** (credit reporting, risk scoring, screening): get §3.5 (indirect influence) detailed. Their authority operates through other institutions' decisions; the indirect channel is the substantive one.
- **Healthcare/hospital authorities**: get §4.1 right with peer benchmarks. "We don't cause bodily harm" is wrong; the right framing is "we operate at these specific peer-benchmark rates."
- **Religious / membership institutions**: get §2.3 (non-consenting) right. Most members technically consented at affiliation; many didn't meaningfully consent in the framework's sense due to family-of-origin membership, social/economic embedment, or exit costs.
- **Platform authorities**: get §3.4 (data exclusions) right. ToS-based authority is broad; the form's value here is in what the platform commits *not* to do.
- **HOAs and small voluntary associations**: get §5 (stop paths) honest. HOA stop paths are weaker than government stop paths; acknowledge it.
- **Voluntary advocacy / ratings**: get §4.7 (additional harm thresholds) symmetric. The harm of getting it wrong runs in both directions — to the subjects rated and to the consumers relying on the ratings.

### Step 8 — Cross-link and file

Final placement:
- Real registrations → `/registry/SCBP-REG-{NNNN}.md`
- Worked examples → `/examples/REG-{DOMAIN}-EXAMPLE.md`
- Educational versions → wherever you keep educational materials (outside the repo, per your direction)

If both a REG-example and an EDU-example exist for the same domain, each footer should cross-reference the other. The EDU header banner already does this; the REG file's footer just says "registered under the Bounded Power Framework" — that's fine, no cross-reference back to EDU needed (since EDU materials live outside the repo).

---

## Part 3 — A few things I'd consider for future iterations

**The genericized examples could use a `/examples/README.md`.** A single-page guide explaining how to use the example directory: "These are worked examples of the SCBP form. Each one demonstrates how a different type of authority would complete the form. They are not registration templates. To register a real authority, complete the blank form at `/forms/registration.md` and submit it through the registry."

**The educational versions might benefit from an index.** Outside the repo, you might want a top-level page listing all 10 educational examples with a one-sentence description of each. That's where readers would land before clicking into a specific domain.

**The bad-faith stress-test deserves its own home.** Right now it lives in `/renamed-stress-tests/` under a generic name (REG-BAD-FAITH-EXAMPLE) which both undersells what it is and could mislead readers about its purpose. It's an adversarial-testing artifact and should probably be filed under SCBP-07 (Integration and Adversarial Testing) materials, with framing that makes its purpose unambiguous.

**Several domains we discussed didn't get done.** Your project brief listed many more domains than we produced (police departments, ICE, family court, CPS, payment processors, debanking, etc.). The work to produce examples for those domains would follow the same Step 1–8 method. If you want to extend the example set, the highest-impact additions are probably: police department, ICE, family court, payment processor, and platform algorithmic-distribution (separate from the content moderation we did, since the algorithmic-distribution side is where most of the framework's R58 indirect-authority concerns apply most directly).

**Renewal of the existing examples.** Examples don't need renewal in the registry sense, but they do need maintenance as the form evolves. If v5 of the form lands, every example will need to be updated to match — at minimum YAML metadata, possibly more substantive sections if v5 adds or restructures sections. Build that maintenance into the project rhythm.

---

*Document produced: May 2026*
*Project: Bounded Power Foundation — Public Registry and Framework*
*Companion to: the `/forms/registration.md` v4 form and the 10 REG-example and 10 EDU-example files produced in this session*

---

# PART 3 — The Registration Form

*The form itself. The AI reproduces this structure exactly when producing the completed Mechanism Record.*

---

# Registration Form

## Bounded Power Framework — Structural Disclosure Form

> *v1: Initial diagnostic disclosure form. Framework-organized.*
> *v2: Embedded worked examples added to diagnostic prompts in Sections 1-9.*
> *v3: §10.7 amended to reference non-consenting affected population per SCBP-09 §II amendment (Round 1 stress test finding).*
> *v4: Final stress-test revisions across Sections 1, 2, 3, 4, 6, 7, 8 (Round 1-3 stress test findings).*
> *v5: Single-class record model. The two-class "authority self-registration vs. citizen diagnostic" framing was collapsed into one record kind with two filer types. Sequential naming convention `SCBP-REG-####-{SUFFIX}` applies to all records. Third-party records carry the `PUBLIC SOURCES ONLY` banner; authority-filed records do not. Authority-after-citizen updates write in place to the existing file.*

---

## What this form is

This is the Bounded Power Framework's Registration Form. Completing it produces a structured public document — a Mechanism Record — that surfaces an authority's scope, harm thresholds, dependencies, stop paths, and oversight gaps in a way most disclosure regimes never force into one place.

The form is organized around what the framework wants visible — not around how authorities typically describe themselves. Some sections ask questions an authority's own internal documents may not address. That is intentional. The framework's structural logic surfaces patterns of capture, drift, and proxy substitution that are easy to miss from inside.

Each section begins with a short *diagnostic prompt* — questions to consider before answering. The prompts are scaffolding for thinking; they are not part of the record. The record is what is written in the answer fields.

Where a section references specific constitutional rules (e.g., "R12, R39"), those references are footnoted at the end of the section. They are provided so readers can consult the underlying rule for context. They are not a citation requirement.

---

## Who fills it out

This form supports one kind of record with two kinds of filers.

**The authority being analyzed.** An authority that chooses to enter the Bounded Power Framework files this form as a public act of structural disclosure. The record is set to `filed_by: authority` and `status: ACTIVE`. The honesty assertions in §12 are binding commitments by the filing authority.

**A third party — citizen, journalist, researcher, or civic actor — analyzing an authority from public sources.** Anyone affected by an authority can use this form to produce a structured analysis using publicly available information. Third-party use does not require the authority's cooperation. The record is set to `filed_by: third_party` and `status: PUBLIC_SOURCES`, and carries the `PUBLIC SOURCES ONLY` banner at the top and bottom of the body — signaling that the record has not been confirmed by the authority it describes. §12 honesty assertions for third-party records reflect what could be verified from public sources; gaps are marked `UNKNOWN`.

The same form, the same rules, and the same SCBP-09 numerical bounds apply to both. The form's diagnostic power does not depend on the authority's cooperation. If an authority later files corrections to a third-party-produced record about itself, the existing record is updated in place — the mechanism_id and filename stay, the YAML flips to `filed_by: authority` and `status: ACTIVE`, the banner is removed, and the Renewal Log inside the body records the transition.

For a guided way to complete a third-party analysis, see [00-Reading/06-AI-Registration-Bundle.md](../00-Reading/06-AI-Registration-Bundle.md).

---

## Before you begin — three things to know

1. **Filings are public the moment they are received.** There is no review queue; submissions are not edited for content. Once filed, a record can be updated but never deleted.

2. **The registry validates structural bounds, not the narrative.** Numerical declarations (response windows, aggregate thresholds, harm threshold values) must fall within the bounds defined in *SCBP-09 — Registry Acceptance Standards*. Out-of-bounds declarations are returned for correction. The registry does not assess whether descriptive claims are accurate.

3. **What is not disclosed is itself a finding.** This form ends with an explicit honesty assertion. The framework's response to undisclosed-but-discoverable information is structural, not punitive — but the gap becomes a public finding when it surfaces.

---

## How to submit

Submissions are accepted by GitHub pull request, by GitHub issue, or by email to BoundedPowerFoundation@proton.me. Completed Mechanism Records are placed in [04-Registry/](../04-Registry/).

All records use the same sequential naming pattern: `SCBP-REG-####-{DESCRIPTIVE-SUFFIX}.md`, where `####` is the next sequential number after the highest existing record and the descriptive suffix is a short human-readable identifier for the authority (e.g., `SCBP-REG-0002-CCCC-OH.md`).

There is no submission fee, no review queue, and no editorial gatekeeping. The repository's maintainer verifies that the submission uses the form, meets SCBP-09 numerical bounds, and is labeled correctly. The maintainer does not assess content accuracy.

---

## SECTION 1 — What is this authority?

> *Diagnostic prompt:* Describe what your mechanism can actually do to people, institutions, or systems — not what it is called or how it is categorized. Authority is determined by functional effect, not by name (R04). If renaming or restructuring this mechanism would not change what it does, then this section should describe the underlying function. If you cannot describe what your mechanism does in plain functional terms, you cannot define its limits.
>
> *Example:* "This mechanism is the Riverbend Parking Enforcement Bureau" is a name, not a function. "This mechanism issues parking citations within city limits, may immobilize vehicles for unpaid balances ≥$300, and may tow after 72 hours of immobilization" is a function. Write the second kind.

```
1.1 — Mechanism name (the public identifier, not the legal name):

1.2 — Functional description:
     What can this mechanism compel, restrict, allocate, require, or impose?
     Describe in plain language what it actually does.

1.3 — Authority classification:
     Is this authority direct (issues binding directives), or indirect
     (advisory, scoring, recommending, scoring, ranking, routing,
     filtering, allocating, or otherwise materially shaping decisions
     made by others)?
     [ ] Direct
     [ ] Indirect — describe the form of indirect influence:
     [ ] Both

1.4 — Domain (select primary; mark others if applicable):
     [ ] Government
     [ ] Economic
     [ ] Technology
     [ ] Infrastructure
     [ ] Data / Information
     [ ] Education
     [ ] Healthcare
     [ ] Cultural / Religious
     [ ] Voluntary association
     [ ] Other (describe):

1.5 — Statutory or constitutional basis (the upstream authority/authorities
      under which this mechanism operates — if any). For complex
      authorities operating under multiple frameworks (e.g.,
      federal + state + accreditation), list each separately:
```

*Rules addressed: R04 (Authority Classification Stability), R58 (Indirect Authority Recognition).*

---

## SECTION 2 — Who can this authority act upon?

> *Diagnostic prompt:* The framework distinguishes between people who chose to interact with this authority and people who did not. Non-consenting affected parties are weighted more heavily under R26 (Non-Participant Harm Floor). Be careful not to confuse "people we serve" with "people we can act upon." A parking enforcement bureau acts upon everyone who parks within city limits, not only those who pay parking fees.
>
> *Example:* A consumer-protection regulator's "served" population might be the consumers it represents. But the population it acts *upon* is the regulated industry — companies that did not consent to the regulator's existence. Both are affected; only the second is non-consenting.

```
2.1 — Affected party categories (select all that apply):
     [ ] General public (no opt-in required to be affected)
     [ ] Residents of defined geographic area (specify):
     [ ] Customers / voluntary service users
     [ ] Members (voluntary affiliation)
     [ ] Employees / workers
     [ ] Students / educational participants
     [ ] Patients / healthcare recipients
     [ ] Regulated industry participants
     [ ] Criminal justice involved individuals
     [ ] Children / minors
     [ ] Vulnerable populations (specify):
     [ ] Future generations (long-duration environmental or financial impact)
     [ ] Non-consenting third parties (describe):

2.2 — Approximate number of people directly affected:

2.3 — Of the affected population, what number/proportion are
      non-consenting (i.e., are subject to this authority without
      opting in):

      *Note on voluntary-but-stuck populations:* Affiliation that
      requires substantial cost to exit (financial, social,
      professional, geographic, network-effect) is not meaningfully
      voluntary in the framework's sense. If your authority operates
      over a population that is technically voluntary but
      structurally cannot exit, declare that population as
      non-consenting. The relevant test is not "did they sign up"
      but "can they meaningfully leave."

2.4 — Vulnerable population specifics:
      Does this authority act upon any of the following? If yes,
      describe the protective measures in place:
      [ ] Children (under age of majority)
      [ ] Patients during medical care
      [ ] Detained or confined persons
      [ ] Persons in coercive economic relationships (e.g., employees
          where the authority is the employer)
      [ ] Persons unable to advocate for themselves due to disability,
          incapacity, or circumstance
```

*Rules addressed: R14 (Non-Participant Exposure Mapping), R26 (Non-Participant Harm Floor).*

---

## SECTION 3 — What can it do, and what can it not do?

> *Diagnostic prompt:* Define the boundary explicitly. Anything not listed as authorized is by default not authorized. R35 (Scope Narrowing Default) means ambiguity will be resolved against expansion — so over-disclosure is structurally safer than under-disclosure. Geographic and coercive declarations must be specific (per SCBP-09 §VII and §VIII). "Wherever needed" or "appropriate enforcement actions" will be returned for correction.
>
> *Example of unacceptable specificity:* "Civil penalties as authorized by law." The framework cannot bound this — *what law, what penalties, what ceiling?* Acceptable: "Civil penalties up to $250 per violation per Riverbend Municipal Code §11-208."
>
> *Example of an exclusion that proxies a capture risk:* A municipal enforcement bureau excluding "contractor relationships where compensation is structured as a percentage of citation revenue" addresses R66 (Anti-Proxy) before any citation is issued. This kind of structural pre-commitment is what §3.4 is designed to capture.

```
3.1 — Geographic reach:
      Geographic specificity (select one):
      [ ] Single municipality (specify):
      [ ] Multi-municipality (specify each):
      [ ] Single county/parish:
      [ ] Multi-county (specify each):
      [ ] Single state/province:
      [ ] Multi-state/multi-province (specify):
      [ ] Single nation (specify):
      [ ] Multi-national (specify):
      [ ] Global, with acknowledgment of jurisdictional limits

3.2 — Coercive ceiling:
      What is the strongest action this authority can take against
      a person, organization, or system? List specific actions and
      their numerical or temporal limits.

3.3 — Resource ceiling:
      Maximum operating budget:
      Maximum staff (FTE):
      Maximum data systems and data volume:

3.4 — Explicit exclusions — what this authority may NOT do:
      List by category. Each exclusion is a structural commitment;
      the registry will treat any action outside the listed
      authorities as outside the authority's scope.
      [ ] Geographic exclusions:
      [ ] Action exclusions (what enforcement actions are off-limits):
      [ ] Data exclusions (what data may not be collected, retained,
          or shared):
      [ ] Procedural exclusions (e.g., may not enter into
          revenue-share contractor relationships):
      [ ] Temporal exclusions (e.g., may not act outside
          declared operational hours):
      [ ] Other exclusions:

3.5 — Indirect influence boundaries:
      If this authority is indirect (per §1.3), what outputs does
      it produce that materially influence decisions made by others
      (scores, rankings, classifications, recommendations,
      authorizations)?
      For each output: who uses it, and what decision does it
      shape?

3.6 — Anti-proxy declaration:
      The framework prohibits achieving restricted effects through
      proxies (R66, R74). For each restricted effect this authority
      cannot directly produce, identify any proxies, statistical
      substitutes, or behavioral indicators that this authority
      will not use to produce equivalent outcomes:
```

*Rules addressed: R04 (Functional Effect), R35 (Scope Narrowing Default), R55 (Fragmentation), R66 (Anti-Proxy), R74 (Proxy Equivalence Expansion). SCBP-09 §VII (Geographic Specificity), §VIII (Coercive Ceiling Specificity).*

---

## SECTION 4 — What harms can it cause?

> *Diagnostic prompt:* The framework's harm categories (R21) are six. For each one, you must either declare a measurable threshold that triggers a stop review, or mark "Not applicable" with justification. A measurable threshold is an observable condition (e.g., "particulate matter exceeds 150 µg/m³ averaged over 24 hours"), not an intention (e.g., "when air quality becomes harmful"). The framework's harm categories are *open* — the listed six are the floor, not the ceiling. If your authority can cause harm not captured by the six categories, declare an additional threshold.
>
> *Note on authorized harm:* For authorities whose authorized function predictably involves some level of harm (e.g., medical treatment, criminal justice supervision, hazardous occupational settings, surgery), distinguish *normal and expected* adverse effects from *excess* harm. Thresholds should target excess — rates exceeding peer benchmarks, preventable harm, or harm that exceeds informed consent. Normal expected harm (chemotherapy side effects, surgical recovery, supervised probation restrictions) is the cost of operation, not a threshold. Excess harm (preventable infections beyond peer rates, restraint-related injury, due process failures) is what these thresholds capture.
>
> *Example of a measurable threshold:* "If more than 8% of citations issued in any rolling 30-day period are subsequently dismissed by the Municipal Court for procedural error." Observable, time-bounded, automatic.
>
> *Example of an unmeasurable threshold:* "If enforcement becomes unfair." Untestable, judgment-dependent, cannot trigger anything reliably.
>
> *Example of "not applicable" done well:* "Bodily harm — not applicable. The Bureau's authority is limited to civil citations, vehicle immobilization, and towing. None of these actions involve direct physical contact with persons. If a stop trigger contests this, the contesting party may file a Challenge under SCBP-08." Justified, structural, appealable.

```
4.1 — Bodily harm threshold:
      Threshold (measurable condition that triggers review):
      [ ] Not applicable — justification:

4.2 — Agency impairment threshold:
      (Restrictions on someone's ability to communicate, participate
      in governance, access correction processes, or exercise
      rights)
      Threshold:
      [ ] Not applicable — justification:

4.3 — Ecological damage threshold:
      Threshold:
      [ ] Not applicable — justification:

4.4 — Generational binding threshold:
      (Commitments that bind future generations to obligations they
      cannot revise)
      Threshold:
      [ ] Not applicable — justification:

4.5 — Communicative suppression threshold:
      (Suppression, distortion, or monopolization of information
      others need to protect themselves or participate)
      Threshold:
      [ ] Not applicable — justification:

4.6 — Informational sovereignty threshold:
      (Permanent or indefinite informational indexing of individuals)
      Threshold:
      [ ] Not applicable — justification:

4.7 — Additional harm thresholds (any harm category not covered above):
      Category name:
      Threshold:

4.8 — Threshold change-log commitment:
      The authority commits to logging all threshold modifications
      publicly with justification and impact analysis at the time of
      change (per R08).
      [ ] Yes — committed
      [ ] Cannot commit — explain:
```

*Rules addressed: R07 (Pre-Authorization Harm Threshold Requirement), R08 (Threshold Registry and Change Log), R21 (Open Harm Categories), R22 (Informational Sovereignty Constraint).*

---

## SECTION 5 — What stops it?

> *Diagnostic prompt:* A mechanism that cannot be stopped is not a mechanism — it is a permanent condition. Stop paths must be (a) at least three, (b) genuinely independent of the authority itself, and (c) costless to activate (R15, R32, R33). "Independent" means: if one stop path is blocked or captured, the others still function. Stop paths that all rely on internal cooperation are not multiple stop paths; they are one stop path with three names. Stakeholders evaluating your registration will press on independence — declare it carefully.
>
> *Example of three genuinely independent stop paths for a small-city authority:*
> 1. *City Council resolution* — Council can suspend operations by majority vote. Council exists outside the authority's reporting structure.
> 2. *Court order* — Municipal Court can order cessation on motion of any party with standing. Court is structurally independent of the executive branch.
> 3. *Citizen Review Office* — independent body of three members, no current or recent service in the authority. May order suspension at specific sites or by specific officers.
>
> *Example of three stop paths that look independent but are not:*
> 1. The authority's own director may suspend operations.
> 2. The authority's own internal complaints department may recommend suspension.
> 3. The authority's parent agency may revoke authorization.
>
> All three rely on the authority itself or its parent. None survives capture or refusal at the top of the chain. This is one stop path with three labels.

```
For each stop path, complete the following:

STOP PATH 1
  Who can activate it (must include parties outside this authority):
  Trigger condition (threshold-based, judgment-based, or both):
  What "stopped" means specifically (operations halt? authorization
  lapses? data collection ceases? all three?):
  Independence justification (why is this stop authority structurally
  independent of this authority — not just nominally?):
  Post-stop review process and timeline:

STOP PATH 2
  [same fields]

STOP PATH 3
  [same fields]

5.4 — Penalty for activating stop:
      The framework requires that no procedural, financial, or
      reputational penalty attach to good-faith stop activation
      (R15, R33).
      [ ] Confirmed — no penalty applies
      [ ] Exception claimed — describe specifically:

5.5 — Stop-path independence verification:
      Can the stop paths above be activated if the authority itself
      refuses to cooperate?
      [ ] Yes — explain how:
      [ ] No — this is a structural finding; explain remediation plan:

5.6 — Civic trigger acknowledgment:
      The authority acknowledges that any party affected by it may
      file a civic trigger (Tripwire, Challenge, or contribute to
      Aggregate) per SCBP-08, and commits to publicly responding
      within the response window declared in §10.
      [ ] Acknowledged
```

*Rules addressed: R13 (Unplug-Ability), R15 (Stop Friction Prohibition), R23 (Tripwire Protocol), R24 (Redundant Stop Activation), R32 (Independent Stop Authority), R33 (No Penalty for Good-Faith Challenge).*

---

## SECTION 6 — What does it depend on?

> *Diagnostic prompt:* Dependencies create capture risk and reversibility risk. The framework distinguishes three types:
> - **Type 1** — entities whose outputs you operationalize as if they were your own (R64 brings them inside your authority for compliance purposes)
> - **Type 2** — independent authorities you have a structural relationship with
> - **Type 3** — infrastructure dependencies whose failure would prevent you from being interrupted, stopped, or audited within declared windows
>
> Complete dependency mapping is structurally unattainable; the form asks for what is *known* and *stop-path-relevant*, not for an exhaustive list of every vendor.
>
> *Example of correctly distinguishing types:*
> - A boot-and-tow contractor working under flat-fee terms is a Type 1 dependency — their actions are operationalized as the bureau's own.
> - The Municipal Court that hears citation contests is a Type 2 dependency — independent authority with a structural relationship.
> - The license-plate-recognition camera vendor is a Type 3 dependency — if they refuse to export data, the bureau cannot demonstrate compliance with the 90-day retention threshold, and stop path 2 (court order based on retention violation) is compromised.
>
> Notice the cloud provider hosting the bureau's website is *not* on this list — its failure is operationally bad but does not compromise stop paths. Type 3 is narrow on purpose.

```
6.1 — Type 1 dependencies (operational extensions acting under
      this authority):
      For each: name, what they do under this authority, contractual
      relationship, and compensation structure (select one — note
      that revenue-share and outcome-tied are themselves capture
      risks under R03/R66):
      [ ] Flat fee per action
      [ ] Hourly / project-based
      [ ] Retainer
      [ ] Revenue share — describe percentage and source
      [ ] Outcome-tied — describe specific outcomes
      [ ] Uncompensated / volunteer
      [ ] Other — describe

6.2 — Type 2 dependencies (independent authorities with a
      structural relationship to this one):
      For each: name, nature of relationship, whether their decisions
      are upstream (we depend on theirs) or downstream (they depend
      on ours).
      *If your authority has no Type 2 dependencies, state so
      explicitly — this is a legitimate disclosure for voluntary
      or fully-independent authorities.*

6.3 — Type 3 dependencies (infrastructure whose failure would
      compromise stop paths or auditability):
      For each: name, what specifically fails if this dependency
      is lost, what stop path or audit capability is compromised:

6.4 — Capture risk identification:
      Does any single funding source, contractor, vendor, or partner
      provide more than 33% of operating support, OR control critical
      data, OR provide infrastructure that cannot be replaced within
      90 days?
      [ ] No
      [ ] Yes — identify and describe the structural risk:

6.5 — Reversibility-affecting dependencies:
      Which dependencies, if removed, would make it harder to
      dismantle this authority within its declared dismantling
      timeline (§9.1)?

6.6 — Coordination disclosures:
      Does this authority coordinate, synchronize, or align
      operationally with any other authority in ways that, taken
      together, function as a single shared authority system (R55,
      R59)? If yes, name and describe.

6.7 — Disclosure completeness assertion:
      The authority asserts that the dependencies listed above
      include all Type 1, Type 2, and stop-path-relevant Type 3
      dependencies known to the authority at the time of
      registration. The authority acknowledges that complete
      dependency mapping is structurally unattainable, and that
      newly-discovered dependencies will be reported as
      Mechanism Record updates. Undisclosed but discoverable
      dependencies are themselves a Framework finding.
      [ ] Asserted

6.8 — External authority operationalization (R72):
      Identify any external authority (vendor algorithm, payer
      decision system, regulatory determination, contractor judgment)
      whose outputs you operationalize within your authority surface,
      such that the affected party experiences your authority but
      the underlying decision is external. For each:
      - Name of external authority
      - What they decide
      - How their decision becomes operationalized as your authority
      - Whether the affected party can distinguish your decision
        from theirs
      *If your authority does not operationalize any external
      decisions, state so explicitly. R72 (External System Equivalence
      Rule) treats operationalized external decisions as part of your
      authority for compliance purposes.*
```

*Rules addressed: R03 (Institutional Capture Prohibition), R12 (Dependency and Capture Review), R39 (Structural Dependency Disclosure), R50 (Capture Risk Monitoring), R55 (Fragmentation), R59 (Functional Continuity), R61 (Anti-Entrenchment), R64 (External Circumvention), R72 (External System Equivalence).*

---

## SECTION 7 — What metrics, signals, and decision inputs shape outcomes?

> *Diagnostic prompt:* R79 (Metric Completeness Requirement) is one of the framework's hardest-edged rules. If observed outcomes cannot be explained by the declared metric set, undeclared influence is presumed, and that constitutes non-compliance. This section asks you to declare *everything* that materially shapes what your authority does — not only the metrics you formally report on, but the signals, classifications, and inputs that practically influence decisions. Including: anything an algorithm ingests, anything a human decision-maker considers, anything that determines prioritization.
>
> *Example of a metric that should be declared but often isn't:* A parking enforcement bureau's officers receive monthly patrol assignments. The assignment algorithm uses a "high-need zone" classification based on prior citation density. This classification materially influences where citations are issued — and therefore who is cited. It must be declared, even though it does not appear on any public dashboard.
>
> *Example of an indirect signal that materially influences outcomes:* Officers' performance reviews include "citations issued per shift" as a comparison metric. This is not a quota, but it influences enforcement intensity. It is a §7.2 disclosure, not a §7.1 declared metric — but it must still be disclosed.

```
7.1 — Declared metrics:
      List all metrics, variables, signals, classifications, and
      decision inputs that materially influence the authority's
      outcomes. For each: name, source, role in decision-making,
      and publication status across three dimensions:
      - Aggregate publication: [Y/N] (statistical summaries)
      - Individual publication: [Y/N] (specific case data)
      - Methodology publication: [Y/N] (how the metric is computed
        or applied)

7.2 — Indirect signals:
      Are there factors that influence outcomes informally — through
      staff judgment, organizational culture, prioritization
      practices, or pattern-of-operation — that do not appear in
      formal metrics? If yes, describe.

7.3 — Algorithmic decision systems:
      Does this authority use, rely upon, or operationalize
      algorithmic, automated, or AI-based decision systems? If yes:
      [ ] Yes — name the system, describe what decisions it
          influences, identify the vendor/source, and describe
          auditability provisions:
      [ ] No

7.4 — Outcome-versus-declaration check:
      The authority commits to maintaining a process by which
      observed outcomes are periodically compared to declared
      metric set, with discrepancies investigated and surfaced
      (per R79, R80).
      [ ] Committed — describe process:
      [ ] Cannot commit — explain:
```

*Rules addressed: R58 (Indirect Authority Recognition), R67 (Minimum Auditability Floor), R79 (Metric Completeness), R80 (Outcome Dominance Principle).*

---

## SECTION 8 — How is this authority watched?

> *Diagnostic prompt:* Authority must be auditable, monitored for drift, and observable in its operations (R38, R41, R44, R67, R81). This section is where the authority commits to *being watchable* — not just to disclosing, but to remaining accessible to ongoing evaluation. Closed audits, restricted interfaces, and "trade secret" exemptions reduce auditability and may not eliminate the minimum floor (R67).
>
> *Example of a real drift-monitoring mechanism:* The bureau publishes quarterly enforcement statistics broken down by census tract. If any tract's citation rate exceeds 3.0x the city-wide average for two consecutive quarters, an automatic review is initiated by the Citation Review Office (a Stop Path 3 trigger). The mechanism is operated by an independent body, runs automatically, and produces public output.
>
> *Example of drift monitoring that fails the bar:* "Bureau leadership reviews enforcement statistics monthly and addresses any concerns." Internal, judgment-dependent, no public output, no automatic trigger. Not auditable.

```
8.1 — Drift monitoring mechanism:
      What mechanism does this authority use to detect expansion
      beyond its original mandate? Who operates that mechanism
      and how often is it run?

8.2 — Capture risk monitoring:
      What ongoing monitoring detects regulatory or structural
      capture (e.g., revolving-door risk, contractor dependency
      drift, funding concentration changes)?

8.3 — Audit interfaces:
      What interfaces, data exports, or evaluation capabilities are
      available to independent reviewers? Specifically:
      - What data is published proactively?
      - What data is available on request?
      - What data is restricted, and on what grounds?

8.4 — Adversarial exposure (R81):
      Can an external party with no insider access evaluate this
      authority's scope, effect, harm thresholds, dependencies,
      reversibility, and stop capability? If not fully, identify
      the gaps.

8.5 — Known structural failure modes:
      What failure modes does this authority know about — failure
      modes that have been observed in similar authorities, in this
      authority's prior versions, or in this authority's design
      assumptions? (R42 requires these be documented; this is the
      registration declaration.)

8.6 — Trade-secret / confidentiality declarations:
      If portions of your authority's operations cannot be fully
      disclosed for reasons of trade secret, vendor IP, regulatory
      restriction, or other confidentiality:
      - What category of information is restricted? (algorithm
        internals, methodology details, vendor IP, business data,
        privileged communications, etc.)
      - What is the source of the restriction? (vendor contract,
        regulatory restriction, competitive harm, statutory privilege,
        other)
      - What auditability mitigation is in place despite the
        restriction? (aggregate disclosure, third-party audit,
        regulator review, summary methodology, none)
      - What R67 (Minimum Auditability Floor) commitment can the
        authority make despite the restriction?

      *Note:* R67 establishes a non-waivable floor of auditability
      sufficient to evaluate scope, effect, harm thresholds,
      dependencies, derived outputs, reversibility, expiration, and
      stop capability. Trade secrecy may alter the *form* of
      disclosure but may not eliminate the floor. If your authority
      cannot meet R67 within trade-secret constraints, that is
      itself a structural finding.
```

*Rules addressed: R38 (Transparency Sufficiency), R40 (Authority Surface Mapping), R41 (Institutional Drift Monitoring), R42 (Structural Failure Documentation), R44 (Independent Audit Capability), R50 (Capture Risk Monitoring), R67 (Minimum Auditability Floor), R81 (Adversarial Exposure Requirement).*

---

## SECTION 9 — How does it end?

> *Diagnostic prompt:* All authority expires unless renewed (R28). This section is your declaration of how this authority can be wound down. Reversibility is not a theoretical property — it must be demonstrable (R43). If dismantling would create cascading collapse beyond your authorized scope, that is a structural finding under R61 (Anti-Entrenchment).
>
> *Example of an honest entrenchment disclosure:* "The Bureau collects 65% of operating revenue through citation fees. Dissolution requires the city to either replace this revenue or cut city services dependent on it. This dependency is itself a structural finding under R61 and is the subject of the capture-monitoring threshold in §4.7."
>
> *Example of dishonest dismissal of entrenchment:* "Operations could be wound down within 30 days." (Without addressing the revenue dependency, the contractor relationships, or the sunk infrastructure, this declaration is not credible. It will be challenged.)

```
9.1 — Estimated dismantling time:
      How long would full wind-down take from a termination order to
      complete cessation? Express as a number of days, with
      justification.

9.2 — Dismantling process:
      Describe the staged process. What happens in week 1? Months 1-3?
      Months 3-6? When are operations frozen, contracts unwound, data
      archived/destroyed, staff reassigned?

9.3 — Entrenchment factors:
      What factors, if any, would make dismantling harder than the
      timeline above suggests? Examples: budget dependencies, sunk
      infrastructure, contractual obligations with long termination
      windows, downstream systems that operationalize this
      authority's outputs.

9.4 — Data disposition:
      What happens to:
      - Personal data (collected from individuals)?
      - Institutional records?
      - Derived outputs (scores, classifications, decisions
        propagated downstream — see R60, R63, R65)?
      - Audit logs?

9.5 — Downstream effect reversibility:
      What decisions, classifications, restrictions, or records
      produced by this authority have been propagated to other
      systems? On termination, what mechanism reverses or invalidates
      those propagated effects (R63, R65)?

9.6 — Replacement feasibility:
      Could this authority be replaced or dissolved without
      destabilizing services beyond its authorized scope (R51, R61)?
      If not, what are the structural barriers, and what is the plan
      to address them?

9.7 — Reversibility verification:
      Has this authority ever rehearsed dismantling, simulated
      shutdown, or otherwise verified that the declared timeline is
      achievable? If yes, describe. If no, the declaration in §9.1
      is treated as estimated, not verified (R43).
```

*Rules addressed: R27 (Reversibility), R28 (Expiration Default), R43 (Reversibility Verification), R51 (Institutional Replacement Feasibility), R60 (Derived Authority Inheritance), R61 (Anti-Entrenchment), R63 (Downstream Effect Reversibility), R65 (Propagation Duty Requirement).*

---

## SECTION 10 — Authorization, renewal, and trigger declarations

> *Diagnostic prompt:* This section combines the formal authorization details with the framework's structural commitments around expiration, renewal, and civic-trigger response.

```
10.1 — Authorizing body (the entity that legally authorizes this
       mechanism):

10.2 — Date of current authorization:

10.3 — Authorization expiration date:

10.4 — Renewal interval (how often this authority must be
       affirmatively renewed):
       Min: 1 year, Max: 10 years per SCBP-09 §V

10.5 — Renewal evidence declaration:
       At renewal review, this authority commits to providing
       evidence across the following five domains (per SCBP-03 §5.1
       and R47):
       [ ] Scope integrity evidence (comparison of authorized vs.
           operational scope)
       [ ] Harm compliance evidence (threshold monitoring data,
           breach records, response records)
       [ ] Stop path integrity evidence (confirmation that stop
           paths remain functional and independent)
       [ ] Dependency and capture evidence (current dependency
           inventory, change since registration, capture risk
           findings)
       [ ] Reversibility evidence (updated dismantling plan,
           rehearsal records if any)

10.6 — Necessity-decay acknowledgment:
       The authority acknowledges that R62 (Necessity Decay
       Requirement) means continued necessity weakens over time
       unless supported by independently verifiable changes in
       external conditions. The authority commits to demonstrating,
       at each renewal, that scope, dependency, opacity, persistence,
       or downstream impact has been *reducing* over time, unless
       conditions independently require continuation.
       [ ] Acknowledged

10.7 — Aggregate trigger threshold:
       Number of triggers: ___
       Within window of: ___ days
       (Per SCBP-09 §II — bounds depend on declared **non-consenting**
       affected population from §2.3, NOT the broader affected
       population. See SCBP-09 §II proportional table.)

10.8 — Aggregate threshold justification:

10.9 — Response time window:
       Days from a stop trigger filing to required public response: ___
       Min 7, max 90, default 30 per SCBP-09 §III.

10.10 — Response window justification (required if longer than 30
        days):
```

*Rules addressed: R10 (Renewal Decision Rule), R28 (Expiration Default), R36 (Renewal Eligibility Condition), R37 (Renewal Process Independence), R47 (Renewal Evidence Standard), R57 (Expiration Enforcement), R62 (Necessity Decay), R76 (Mandatory Degradation).*

---

## SECTION 11 — What does this authority commit to publishing?

> *Diagnostic prompt:* The framework treats publication as a structural commitment, not a promise of best effort. R17 (Citizen Ledger Output) requires periodic public summaries; R8 (Threshold Registry) requires logging threshold changes; R16 (Interpretation Change Log) requires logging scope reinterpretations. This section captures all publication commitments in one place.

```
11.1 — Citizen ledger publication:
       Frequency:
       [ ] Quarterly  [ ] Annually  [ ] Other:
       Content commitments — the ledger will include:
       [ ] Operating expenditures (high-level)
       [ ] Renewal status
       [ ] Stop events (triggers filed, responses, findings)
       [ ] Structural dependency status (changes since last ledger)
       [ ] Other (specify):

11.2 — Threshold change log:
       This authority commits to publishing all threshold
       modifications publicly within ___ days of change, including
       justification and impact analysis (per R08).

11.3 — Interpretation change log:
       This authority commits to logging all reinterpretations
       affecting scope or thresholds in a publicly auditable log,
       recorded at the time of interpretation (per R16).

11.4 — Renewal process visibility:
       At renewal review, all renewal evidence will be made publicly
       available. The renewal process itself will be conducted by
       parties structurally independent of this authority (R37).
       [ ] Committed

11.5 — Stop event log:
       All stop triggers filed against this authority, all responses,
       and all findings will be permanently recorded in the public
       Mechanism Record.
       [ ] Acknowledged (note: this is a registry-side commitment,
           but the authority confirms it understands)
```

*Rules addressed: R08 (Threshold Registry and Change Log), R16 (Interpretation Change Log), R17 (Citizen Ledger Output), R37 (Renewal Process Independence), R38 (Transparency Sufficiency), R75 (Evidence Integrity Requirement).*

---

## SECTION 12 — Honesty assertions

> *Diagnostic prompt:* This section is the authority's structural commitment to disclosure honesty. The framework is built around making things visible. The authority's commitment here is what makes the rest of the form load-bearing.

```
12.1 — Disclosure completeness assertion:
       I assert that the disclosures in this Mechanism Record reflect
       all information known to the authority at the time of
       registration relating to: scope, affected parties, harm
       thresholds, dependencies, stop paths, decision metrics, and
       structural risk factors.
       [ ] Asserted

12.2 — Update obligation:
       I commit to updating this Mechanism Record when any of the
       following change: declared scope, harm thresholds, stop paths,
       Type 1 or stop-path-relevant Type 3 dependencies, capture
       risk profile, decision metrics, or any field marked [committed]
       in this form. Updates will be filed within 30 days of change.
       [ ] Committed

12.3 — Discoverability acknowledgment:
       I acknowledge that undisclosed-but-discoverable information —
       information that should have been declared at registration but
       was not — is itself a Framework finding when it surfaces, and
       may be the subject of a Challenge-class civic trigger under
       SCBP-08.
       [ ] Acknowledged

12.4 — Burden of proof acknowledgment:
       I acknowledge that R69 (Burden of Proof Reversal) places the
       burden of proving constitutional compliance on this authority,
       not on stakeholders or the registry. Lack of evidence,
       incomplete evidence, or inaccessible evidence results in
       non-compliance findings.
       [ ] Acknowledged

12.5 — Anti-weaponization acknowledgment:
       I acknowledge that the Framework may not be interpreted to
       justify harm that the framework itself is designed to prevent
       (R53). Registration under this framework does not legitimize
       authority that exceeds the framework's structural limits.
       [ ] Acknowledged
```

*Rules addressed: R53 (Anti-Weaponization Clause), R69 (Burden of Proof Reversal), R75 (Evidence Integrity Requirement).*

---

## SECTION 13 — Submitter

> *Note: Submitter information is part of the registry's metadata but is not part of the published Mechanism Record. Only "Registered by [authority name]" appears in the public record. Submitter contact details are retained by the registry for follow-up only.*

```
Submitted by (full name):
Role / position within or relationship to the authority:
Date:
Contact for follow-up (email or other):
```

---

## What happens after submission

1. The submission is logged immediately as a public GitHub Issue.
2. The registry validates structural bounds (per SCBP-09). Out-of-bounds declarations are returned within 7 days for correction.
3. A Mechanism Record is created and assigned a unique ID in the format `SCBP-REG-####-v1`.
4. The Mechanism Record is published in the registry within 7 days of acceptance (per Charter §7).
5. The submitter is notified of the assigned ID.

Registration does not constitute endorsement, certification, or validation by the Bounded Power Foundation. It creates a public record that the authority exists and has declared its scope, thresholds, stop paths, and structural commitments.

---

## Updating a record

Updates follow the same submission process. An update PR/Issue must reference the existing Mechanism ID and describe the change. The existing Mechanism Record is preserved in version history; the file shows the current version. All updates are logged with timestamp and reason.


---

*Bounded Power Framework — Registration Form (v4)*
*All submissions become permanent public records*


---

# PART 4 — SCBP-04 Structural Constitution v1.3

*The binding rules the form references by number (R01–R81). Only the clause text of each rule is binding; section headings and Human Understanding text are explanatory.*

---

# Structural Constitution of Bounded Power

> Only the clause text of each rule is binding. All section headings
> and Human Understanding text are explanatory and non-binding.

---

## Preamble

Authority tends to expand. This is not a moral failure. It is a structural condition.

Left unattended, authority grows through extension, reinterpretation, and accumulation until it becomes difficult to interrupt, reverse, or review. By the time the problem is visible, the cost of correction may exceed what society is willing to pay.

This Constitution exists to prevent that outcome.

It does not prescribe policy. It does not allocate rights. It does not determine who governs or what decisions are made. It specifies only how authority must behave — regardless of who holds it, what it is called, or what purpose it claims to serve.

Three conditions apply to all authority, without exception:

- Power must remain small enough to stop.
- Harm must remain interruptible before it becomes permanent.
- Mistakes must remain correctable before they become irreversible.

These are not aspirations. They are structural requirements. The rules that follow give them binding form.

**This Constitution does not grant authority. It constrains it.**

---

## Purpose

This Structural Constitution defines the permanent constraint structure of the Bounded Power Framework.

These rules do not prescribe policy outcomes. They establish structural limits that authority systems must obey.

All operational procedures, diagnostic evaluations, and containment mechanisms derive their authority from these rules.

The objective of the constitution is to ensure that authority remains: limited, interruptible, reversible, transparent enough to evaluate, and temporary unless renewed.

---

## Rule Interpretation

Binding authority derives solely from Rule Clause text.

Rule names, headings, and all explanatory or descriptive text are non-binding. They do not limit, expand, or modify any Rule.

If ambiguity exists, interpretation shall:
- minimize authority scope
- preserve reversibility
- maintain stoppability

Failure to resolve ambiguity triggers provisional pause.

---

## Structural Closure Principle

Nothing beyond the authorities, mechanisms, categories, and processes defined in this constitution is authorized or implied. Interpretation may clarify application but may not introduce new structural elements.

---

## Interpretive Definitions

**Materially Influence** — Any output, condition, metric, classification, recommendation, score, ranking, dependency, or operational signal that changes decision probability, access, classification, restriction, allocation, enforcement, or outcome in a non-trivial way. If removal of the output or condition would change outcomes, influence is material.

**Derived Output** — Any data, model, score, profile, classification, transformed artifact, aggregated artifact, embedded representation, statistical representation, model-weight representation, or decision-support output that retains functional influence from a source authority.

**Functional Continuity** — Persistence of substantially the same authority function across time, entities, systems, ownership structures, jurisdictions, or structural forms. Functional continuity exists when removal of one system results in another system continuing substantially the same effect.

**Dependency** — A condition where removal of a system would disrupt operations beyond the system's original authorized scope, create a strong institutional incentive not to remove the system, or make replacement impractical within defined operational timelines.

**External Validation** — Verification by entities structurally independent in funding, data access, operational reliance, institutional incentives, and dependency. Correlated, dependent, or operationally aligned entities do not qualify as external validators.

**Downstream Effect** — Any decision, classification, restriction, access condition, allocation, score, record, output, or consequence propagated beyond the originating authority, regardless of system boundary, jurisdiction, ownership, or technical form.

---

## Governance Humility

*Human Understanding: Authority systems must assume fallibility. Institutions must remain designed for correction, revision, and replacement. Institutions are created by people operating under limited knowledge and changing conditions. Systems that assume permanent correctness eventually become rigid and dangerous. Safe systems assume error and preserve the ability to correct themselves.*

### R01 — Governance Humility Principle
Authority must operate under the assumption of fallibility. No institutional decision system may presume permanent correctness or immunity from revision.

---

## Purpose and Scope Limitation

*Human Understanding: Institutions often expand slowly through reinterpretation, small adjustments, or administrative convenience. Over time this drift can transform a narrow mandate into a broad one. These rules prevent that drift.*

### R02 — Confinement Purpose Limit
Detention or confinement may occur only for the prevention of defined harm and may not be used for economic extraction, coercive labor, humiliation, or permanent status degradation.

### R03 — Institutional Capture Prohibition
Institutions exercising authority may not become structurally dependent upon concentrated private interests or technological infrastructures that undermine their independence.

### R04 — Authority Classification Stability
Authority classification is determined by functional effect, including indirect influence over decisions, allocations, classifications, constraints, or access. Renaming, reclassifying, relabeling, outsourcing, or restructuring an activity does not change the nature of the authority being exercised.

### R05 — Functional Scope Test
If an authority expands its reach, duration, intensity, or geographic scope beyond the original authorization, the authority must undergo renewal review.

### R06 — Semantic Expansion Prohibition
Authority may not expand through linguistic reinterpretation, administrative relabeling, or definitional drift.

---

## Pre-Authorization Safeguards

*Human Understanding: Institutions frequently operate without clear limits and only define boundaries after harm occurs. The framework requires those limits to exist before the system begins operating.*

### R07 — Pre-Authorization Harm Threshold Requirement
Before a system becomes operational, measurable harm thresholds must be defined. Undefined thresholds invalidate authorization.

### R08 — Threshold Registry and Change Log
All harm thresholds must be publicly documented, and any modification must include justification and impact analysis.

---

## Drift Detection and Correction

*Human Understanding: Institutional drift rarely occurs intentionally. It develops through small adjustments that gradually alter the system. These rules require active monitoring and correction.*

### R09 — Rollback Requirement
When drift or harm occurs, systems must prioritize rollback to the last compliant state rather than layering additional complexity onto the system.

### R10 — Renewal Decision Rule
Authority expires unless affirmative evidence demonstrates continued necessity and compliance with structural limits.

### R11 — Ambiguity Pause Trigger
Material ambiguity regarding authority scope requires provisional pause until clarification occurs.

### R12 — Dependency and Capture Review
Institutions must disclose structural dependencies that could undermine their independence or interruptibility.

### R13 — Unplug-Ability Requirement
Critical systems must remain interruptible, replaceable, and auditable.

---

## Non-Participant Protection

*Human Understanding: Governance decisions often impose consequences on people who never consented to the system producing those decisions. Additional protections are required in such cases.*

### R14 — Non-Participant Exposure Mapping
Institutions must identify individuals affected without participation or consent.

### R15 — Stop Friction Prohibition
No procedural, financial, or reputational penalty may attach to good-faith activation of stop mechanisms.

### R16 — Interpretation Change Log
All reinterpretations affecting scope or thresholds must be recorded in a publicly auditable log.

### R17 — Citizen Ledger Output
Institutions must publish periodic high-level summaries of expenditures, renewals, stop events, and structural dependencies.

---

## Informational Constraints

*Human Understanding: Data systems can create permanent records that prevent individuals from escaping past actions or mistakes. These rules limit informational permanence.*

### R18 — Data Retention Purpose Limit
Personal data may be retained only for the duration necessary to fulfill the purpose of its collection.

### R19 — Biometric Data Restriction
Biometric and genetic data may only be collected for specific bounded purposes and must be destroyed once those purposes are fulfilled.

### R20 — Post-Sentence Identification Exception
Limited biometric identifiers may be retained for investigation of severe harm crimes under strict renewal review.

### R21 — Open Harm Categories
Institutions must define harm thresholds across core harm categories including bodily harm, agency impairment, ecological damage, generational binding, communicative suppression, and informational sovereignty violations.

### R22 — Informational Sovereignty Constraint
Personal data systems may not create permanent, indefinite informational indexing of individuals.

---

## Stop Mechanisms

*Human Understanding: A system that cannot be stopped cannot be safely operated.*

### R23 — Tripwire Protocol
When harm thresholds are crossed, affected operations must immediately enter provisional stop pending review.

### R24 — Redundant Stop Activation
Multiple independent pathways must exist to activate stop procedures.

### R25 — Post-Stop Review Requirement
Independent review must evaluate threshold breach, rollback necessity, and authorization status.

### R26 — Non-Participant Harm Floor
Operations affecting non-participants must meet stricter harm tolerances.

---

## Reversibility

*Human Understanding: Institutions that cannot be dismantled eventually become permanent regardless of performance.*

### R27 — Reversibility Requirement
Authority structures and all downstream effects must remain reversible within defined operational timelines, including decisions, classifications, restrictions, propagated outputs, and dependent-system effects.

### R28 — Expiration Default
All exercises of authority, including programs, mandates, operational authorizations, and derived outputs, expire automatically unless affirmatively renewed through the renewal process. Expiration applies regardless of institutional permanence and requires removal, invalidation, or reversal of downstream effects generated by the authority.

### R29 — No Expansion by Accumulation
Authority may not expand through incremental aggregation of small changes.

### R30 — Coordination as Power Expansion
Coordination, synchronization, or interdependence that reduces independent stop-ability constitutes an increase in power and is subject to all expansion constraints.

### R31 — Informal Alignment as Power Expansion
Informal, cultural, technical, or procedural alignment that reduces independent stop-ability constitutes an increase in power, regardless of whether the alignment is explicit or formally structured.

### R32 — Independent Stop Authority
Stop authorities must remain structurally independent from the institutions they oversee.

### R33 — No Penalty for Good-Faith Challenge
Individuals invoking oversight or stop procedures may not be penalized.

---

## Structural Containment

*Human Understanding: Institutions often expand through interconnection and complexity rather than explicit decisions. Structural containment prevents this.*

### R34 — Aggregation Review Requirement
Aggregation of authority, data, or jurisdiction across domains requires independent review.

### R35 — Scope Narrowing Default
Ambiguity automatically narrows authority rather than expanding it.

### R36 — Renewal Eligibility Condition
Institutions must demonstrate continued compliance with harm limits and structural constraints to remain authorized.

### R37 — Renewal Process Independence
Renewal and contraction processes must themselves remain subject to independent stop-ability. No institution under review may hold structural control over the process by which its own renewal is decided.

### R38 — Transparency Sufficiency
Institutions must maintain sufficient visibility for independent evaluation of compliance.

### R39 — Structural Dependency Disclosure
Institutions must disclose dependencies that could compromise reversibility.

### R40 — Authority Surface Mapping
Institutions must maintain a documented map of all operational surfaces where authority is exercised.

### R41 — Institutional Drift Monitoring
Systems must maintain mechanisms to detect expansion beyond the original mandate.

### R42 — Structural Failure Documentation
Known structural failure modes must be documented and periodically reviewed.

### R43 — Reversibility Verification
Institutions must demonstrate that operational systems can be halted, replaced, or dismantled safely.

---

## Oversight Structure

*Human Understanding: Oversight bodies can become captured by the institutions they supervise. Structural independence is therefore required.*

### R44 — Independent Audit Capability
Independent review bodies must retain unrestricted ability to evaluate authority structures.

### R45 — Enforcement Symmetry Requirement
Enforcement mechanisms must apply symmetrically and may not selectively target challengers.

### R46 — Procedural Harassment Prohibition
Administrative procedures may not be used to exhaust or intimidate challengers.

### R47 — Renewal Evidence Standard
Renewal of authority requires evidence demonstrating continued necessity, proportional scope, structural reversibility, and compliance with harm thresholds. Evidence must be sufficient to allow independent evaluation of whether the authority remains justified.

### R48 — Structural Containment Requirement
Institutions must remain bounded to their defined operational domain.

### R49 — Escalation Ladder Requirement
Corrective actions must proceed through documented proportional stages.

### R50 — Capture Risk Monitoring
Institutions must monitor and disclose risks of regulatory or structural capture.

### R51 — Institutional Replacement Feasibility
The system must maintain the practical ability to replace or dissolve institutions.

### R52 — Constitutional Conflict Resolution
Conflicts between rules must be resolved in favor of reversibility, harm prevention, and structural humility.

### R53 — Anti-Weaponization Clause
No rule may be interpreted to justify harm that the framework itself is designed to prevent.

### R54 — Constitutional Renewal Principle
This constitution must remain subject to periodic review under its own bounded power principles.

---

## Structural Evasion

*Human Understanding: Delegating work is allowed. Splitting the authority system in order to escape limits is not. Authorities may hire employees, contractors, or partner institutions to perform tasks. These operational structures do not hold authority themselves. However, when they operate under the direction or coordination of an authority, they become part of that authority's operational system. Delegation does not transfer constitutional responsibility. For purposes of constitutional limits, the framework evaluates the entire system performing the authority's work.*

### R55 — Fragmentation Must Not Defeat Containment
Division of authority across multiple institutions, contractors, subsidiaries, time periods, technical systems, jurisdictions, or coordinated actors may not be used to evade containment rules, expiration limits, renewal requirements, or expansion limits. Authorities that coordinate operational structures as part of a shared authority function shall be evaluated as a single authority system regardless of legal, organizational, temporal, technical, or jurisdictional separation.

---

## Document Integrity

*Human Understanding: If the constitutional documents themselves can be quietly altered, the framework cannot reliably constrain power.*

### R56 — Canonical Integrity Requirement
All canonical artifacts of the Bounded Power Framework must include a publicly recorded cryptographic hash stored in the official hash registry. Any modification requires publication of: the modified artifact, a new version identifier, the updated hash value, and the updated registry entry. If an artifact differs from the hash recorded in the registry, that artifact is not considered an official version of the framework. No artifact may be silently replaced or superseded.

---

## Expiration Enforcement

*Human Understanding: Without enforcement of expiration, institutions could continue operating indefinitely during prolonged review processes.*

### R57 — Expiration Enforcement
When an authority reaches its expiration point without completed renewal authorization, the authority must enter provisional suspension until renewal evaluation is complete. Expired authority may not continue operating solely because review is pending.

---

## Modern Authority Evasion

*Human Understanding: Modern authority often does not look like direct command. It may appear as advice, scoring, infrastructure, standards, models, data systems, outsourced services, contractor tools, or shared decision pipelines. If those systems shape real outcomes, they exercise authority in substance even when they avoid the language of authority.*

### R58 — Indirect Authority Recognition
Any system that materially influences, conditions, constrains, ranks, scores, recommends, routes, filters, allocates, or otherwise shapes the decisions of other authorities or actors at scale shall be treated as exercising authority, regardless of whether it issues binding directives. Systems subject to this rule include advisory systems, decision-support systems, scoring systems, standards, models, infrastructures, and dependency-producing outputs when their practical effect materially shapes access, enforcement, allocation, classification, or restriction.

### R59 — Functional Continuity Consolidation
Where a function of authority persists across multiple entities, time periods, authorizations, systems, jurisdictions, ownership structures, or structural configurations, it shall be treated as a single continuous authority system. Expiration, renewal, scope limits, aggregation limits, and containment requirements apply to the function as a whole, not merely to the individual component currently exercising it.

### R60 — Derived Authority Inheritance
Any derived output inherits the constraints, expiration limits, purpose limits, auditability requirements, reversibility duties, and downstream obligations of the authority that produced, authorized, trained, conditioned, or materially shaped it. Derived outputs may not extend influence beyond the originating authority's purpose, persist beyond the originating authority's expiration, or become independent authority through transformation, aggregation, embedding, retraining, proxy conversion, or transfer. Expiration, invalidation, or termination of the source authority requires removal, invalidation, or reversal of derived outputs unless independently reauthorized under full constitutional review.

### R61 — Anti-Entrenchment Constraint
No authority system may become so embedded, dependent, technically integrated, economically relied upon, or operationally necessary that removal becomes impractical, destabilizing beyond the original authorized scope, or structurally discouraged. If an authority reaches such dependency, the authority is non-compliant and must enter reduction, modularization, replacement, contraction, or termination review.

### R62 — Necessity Decay Requirement
Claims of continued necessity weaken over time unless supported by independently verifiable changes in external conditions. Authority may not be renewed solely because it previously existed, because prior justification persists, because risk can never be reduced to zero, or because the authority's own operation produces evidence of its necessity. Renewal requires evidence that continued authority remains necessary and that the authority is reducing dependency, scope, impact, or permanence over time.

### R63 — Downstream Effect Reversibility
Any decision, classification, restriction, score, allocation, record, derived output, or propagated consequence produced by an authority system must remain traceable to its source and reversible upon expiration, invalidation, rollback, or termination of that authority. External or dependent systems that rely on such outputs may not treat them as independent, permanent, or exempt from the originating authority's limits.

### R64 — External Circumvention Prohibition
An authority may not obtain, rely upon, operationalize, import, purchase, receive, or otherwise use outputs from external systems where doing so would produce a result the authority could not directly create under this constitution. Contractor, vendor, partner, foreign, private, technical, or affiliated systems are treated as part of the authority system when their outputs are used to achieve constitutionally restricted effects.

### R65 — Propagation Duty Requirement
Any system that receives, relies upon, republishes, caches, transforms, or operationalizes outputs from an authority system assumes propagation duties when those outputs expire, are invalidated, are corrected, or are reversed. Propagation duties include notice, purge or correction of affected outputs, certification of compliance, preservation of auditability, and prevention of continued reliance on invalidated effects.

### R66 — Anti-Proxy Substitution Rule
A prohibited variable, classification, action, restriction, or authority effect may not be replaced by a proxy that produces materially equivalent functional or statistical outcomes. Proxy equivalence is determined by practical effect, not by terminology, intent, technical form, or formal variable identity.

### R67 — Minimum Auditability Floor
No authority may operate below a non-waivable level of auditability sufficient to evaluate scope, effect, harm thresholds, dependencies, derived outputs, reversibility, expiration, and stop capability. Security, confidentiality, trade secrecy, emergency, technical complexity, or institutional sensitivity may alter the form of disclosure but may not eliminate the minimum ability to evaluate constitutional compliance.

---

## Hostile Compliance

*Human Understanding: A system can appear to follow the words while still preserving the same power, delay, dependency, secrecy, irreversibility, or practical effect. The constitution therefore evaluates what authority does in reality, not only how it describes itself.*

### R68 — Interpretation Abuse Prohibition
Interpretations that preserve formal compliance while materially violating constitutional purpose, increasing practical authority, reducing stoppability, weakening reversibility, avoiding expiration, or concealing authority effects are invalid.

### R69 — Burden of Proof Reversal
Authority bears the burden of proving constitutional compliance. Lack of evidence, incomplete evidence, inaccessible evidence, non-reproducible evidence, or failure to demonstrate compliance results in non-compliance.

### R70 — Time-Bound Compliance Requirement
All required corrective actions, reviews, pauses, contractions, rollbacks, renewals, invalidations, propagation duties, and termination procedures must occur within defined time windows. Delay beyond those windows constitutes violation and triggers escalation under the enforcement system.

### R71 — Anti-Latency Exploitation
Creating, accelerating, preserving, or transferring effects that become difficult or impossible to reverse before review, renewal, audit, pause, or enforcement is complete constitutes automatic violation. No authority may use procedural time, operational speed, technical dependency, or review delay to create facts on the ground that defeat later correction.

### R72 — External System Equivalence Rule
If an external system produces materially equivalent outcomes to those produced by an authority system, and the authority relies upon, incorporates, coordinates with, benefits from, or operationalizes those outcomes, the external system is treated as part of the same authority system for constitutional purposes. Ownership, jurisdiction, contract status, technical separation, or formal independence does not defeat functional equivalence.

### R73 — Enforcement Non-Discretion Principle
Where violation conditions are met, enforcement must occur. Discretion, negotiation, political preference, institutional convenience, administrative burden, or claimed usefulness may not override constitutional triggers.

### R74 — Proxy Equivalence Expansion
Any proxy, model feature, variable cluster, inferred classification, statistical substitute, behavioral indicator, derived signal, or transformed artifact that reproduces materially similar effects to a restricted variable or authority action is treated as the restricted variable or action.

### R75 — Evidence Integrity Requirement
Evidence used for authorization, renewal, continuation, classification, threshold adjustment, or compliance must be independently reproducible and sufficient for external evaluation. Non-reproducible, selectively disclosed, internally dependent, opaque, or strategically narrowed evidence is invalid.

### R76 — Mandatory Degradation Requirement
Authority must reduce scope, dependency, opacity, persistence, intensity, or downstream impact over time unless independently validated conditions require continuation. Static authority, unchanged authority, or authority that grows more embedded over time fails renewal unless narrowly justified by independently verifiable conditions.

### R77 — Cross-System Accountability Lock
All systems participating in, depending upon, receiving outputs from, contributing to, or operationalizing a dependency chain share responsibility for constitutional compliance. No participant may disclaim responsibility by invoking separation, specialization, delegation, outsourcing, technical role, jurisdiction, contract status, or lack of final decision authority.

### R78 — Irreversibility Preemption Rule
If an action, output, classification, dependency, technical change, data operation, or operational sequence risks becoming irreversible or materially difficult to reverse, it must be blocked before execution unless it has been explicitly authorized under the strictest applicable constitutional review.

---

## Authority Measurement and Verification

*Human Understanding: Authority systems may appear compliant by limiting what they declare while still producing broader effects in practice. The framework therefore evaluates both what is declared and what actually occurs.*

### R79 — Metric Completeness Requirement
All metrics, variables, signals, classifications, and decision inputs that materially influence outcomes must be declared. If observed outcomes, decisions, classifications, restrictions, or allocations cannot be fully explained by the declared metric set, the system is presumed to contain undeclared influence. Undeclared influence constitutes non-compliance. Failure to demonstrate metric completeness triggers provisional pause.

### R80 — Outcome Dominance Principle
Authority is evaluated based on observable outcomes rather than declared structure. If the practical effects of a system exceed its authorized scope, the authority is deemed expanded regardless of labeling, structural separation, sequence of actions, or intermediary systems. Outcome-based expansion constitutes non-compliance and triggers enforcement.

### R81 — Adversarial Exposure Requirement
Authority systems must remain capable of independent evaluation. All information, interfaces, and system behaviors necessary to evaluate scope, effect, compliance, and reversibility must be accessible in a form that allows independent analysis. If independent evaluation cannot be performed, the authority is non-compliant. Restriction of evaluation capability constitutes violation.

---

*End of Document — R01 through R81*

---

# PART 5 — SCBP-09 Registry Acceptance Standards v1.0

*The numerical bounds the form's declarations must fall within.*

---

# SCBP-09 — Registry Acceptance Standards

*Operational Layer*
*Subordinate to: the Structural Constitution*

---

## Purpose

This document defines the floors and ceilings the registry applies to authority-declared variables in Mechanism Records.

The Mechanism Record is filed by the authority itself. The authority declares its own scope, thresholds, response windows, and stop paths. This is by design — authorities know their own functional reality better than any external party. But unbounded self-declaration can be gamed: an authority can declare absurdly high response windows, unreachably high aggregate trigger thresholds, or insufficient stop paths, technically completing registration while making the framework's own mechanisms ineffective.

This document defines the structural bounds within which authority self-declaration is acceptable. Declarations outside these bounds are rejected at registration. Declarations within these bounds but visibly gamed for the authority's specific scope can be challenged by stakeholders through the civic trigger process (see SCBP-08).

This document is operational, not constitutional. It does not modify SCBP-04. It can be amended through the registry's amendment process without touching the frozen Constitution.

---

## Section I — Validation Principle

The registry validates Mechanism Records at registration and at any update. Validation is structural, not editorial. The registry checks that declared values fall within bounds; it does not assess whether the authority's narrative justification is persuasive or whether its self-classification is accurate.

If declared values fall outside the bounds defined in this document, the submission is returned for correction. Returns are logged publicly. Repeated returns of the same Mechanism Record without movement toward acceptable values are themselves a Framework finding.

If declared values fall within bounds but appear gamed for the authority's specific scope (technically compliant but practically unreasonable), the authority may register, but stakeholders may file a Challenge-class trigger contesting the declarations. The Challenge is reviewed under the standard SCBP-08 process; the registry does not adjudicate.

---

## Section II — Aggregate Trigger Threshold

The aggregate trigger threshold defines the number of independent stop triggers, filed within a defined time window against a single authority, that automatically initiate an aggregation review under R34.

Authorities declare their aggregate threshold at registration. The threshold must be expressed as `X triggers in Y days`.

### Population determining the threshold range

The aggregate threshold range is determined by the authority's **non-consenting affected population** as declared in the Mechanism Record (§2.3 of the registration form) — *not* by the broader voluntary affected population.

Rationale: civic triggers exist principally to give structural voice to those affected by an authority *without their consent*. People who voluntarily interact with an authority retain their normal exit options (they can decline the relationship, choose alternatives, or remove themselves). People in the non-consenting population have, by definition, no comparable exit. The threshold range must be calibrated to give that population meaningful access to aggregate review, even when they are the smaller of the affected groups.

The framework's bias is toward the largest, most underrepresented, and most structurally exposed population — not the largest population overall. Where these populations diverge, the non-consenting population governs the threshold range.

If an authority has multiple affected populations of different consent levels, the Mechanism Record must declare both populations distinctly (per §2.2 and §2.3), but the §10.7 threshold range is determined by §2.3 only.

### Floor and ceiling

Aggregate thresholds must fall within the proportional bounds shown below. Bounds are tied to the authority's declared **non-consenting** affected population (Mechanism Record §2.3), per the principle stated above.

| Non-consenting population | Minimum threshold | Maximum threshold |
|---|---|---|
| < 1,000 | 3 in 90 days | 10 in 90 days |
| 1,000 – 100,000 | 5 in 90 days | 25 in 90 days |
| 100,000 – 1,000,000 | 10 in 90 days | 50 in 90 days |
| 1,000,000 – 100,000,000 | 25 in 90 days | 250 in 90 days |
| > 100,000,000 | 100 in 90 days | 1,000 in 90 days |

### Why the bounds scale this way

The bounds scale sublinearly with affected population. A small authority is signaled to be in serious trouble by even a few independent triggers; a larger authority generates more background noise and requires a higher absolute count to indicate organized concern. Per-capita thresholds remain very low across all scales — the ceiling for the largest category is 1,000 in 90 days against an authority affecting 100M+ people, which is a per-capita rate of approximately 0.001 percent per quarter.

### Rationale

The minimum (floor) prevents authorities from declaring such a high threshold that aggregate review becomes practically unreachable. The maximum (ceiling) prevents adversarial filers from gaming a competitor's authority registration with an artificially low threshold that would trigger constant noise.

The default within the bounds is the authority's declaration, with justification recorded in the Mechanism Record.

### Time window flexibility

The 90-day window above is the structural default. Authorities may declare different windows (e.g., 30 days, 180 days) provided the resulting threshold remains proportionally reasonable. Short windows with low counts (e.g., 5 in 7 days) and long windows with high counts (e.g., 200 in 365 days) are both acceptable structurally; the registry does not enforce a single window length.

---

## Section III — Response Time Window

The response time window defines how long the authority has to respond publicly after a stop trigger is filed against it.

### Floor and ceiling

| Bound | Value |
|---|---|
| Minimum | 7 days |
| Maximum | 90 days |
| Default if unspecified | 30 days |

### Why these bounds

7 days is the floor because shorter windows are not realistic for any authority larger than an individual. 90 days is the ceiling because longer windows defeat the purpose of the response clock — by the time response is due, the precipitating concern may have already produced irreversible effects.

The default of 30 days matches the value declared in the existing stop-trigger form. Authorities may declare a shorter window as a public commitment to faster response. Authorities may declare a longer window only with explicit justification recorded in the Mechanism Record.

---

## Section IV — Stop Path Count

The Mechanism Record must declare at least three independent stop paths (per SCBP-03 §1.4).

### Floor

| Bound | Value |
|---|---|
| Minimum | 3 independent paths |
| Maximum | (none) |

The independence of stop paths is a substantive question, not a numerical one. Three paths that all depend on the same authority's internal cooperation are not three independent paths. Stakeholders may challenge the independence of declared paths through the SCBP-08 Challenge mechanism.

---

## Section V — Renewal Interval

Authorities declare their renewal interval at registration.

### Floor and ceiling

| Bound | Value |
|---|---|
| Minimum | 1 year |
| Maximum | 10 years |
| Recommended for high-coercion / novel mechanism | 1–2 years |
| Recommended for moderate scope | 3–5 years |
| Recommended for narrow scope, established function | 5–7 years |

The recommendations are from SCBP-03 §1.6 and are not enforced by the registry. The 10-year ceiling is enforced — no Mechanism Record will be accepted with a renewal interval longer than 10 years.

---

## Section VI — Harm Threshold Coverage

The Mechanism Record §7 declares harm thresholds across categories. The framework's open harm categories (R21) are:

- Bodily harm
- Agency impairment
- Ecological damage
- Generational binding
- Communicative suppression
- Informational sovereignty violations

### Floor

For each harm category that *applies* to the authority's function, at least one measurable threshold must be declared. Categories that do not apply may be marked "Not applicable" with brief justification.

The registry does not adjudicate whether a category applies. An authority that declares "Not applicable" across all categories or across categories that visibly should apply (e.g., a healthcare authority declaring bodily harm "Not applicable") may register, but stakeholders may file a Challenge-class trigger contesting the declarations.

### Threshold validity

Declared thresholds must be measurable — expressed as observable conditions, not intentions. SCBP-03 §1.3 provides examples. The registry checks that declared thresholds are stated as conditions; it does not validate that the conditions are well-chosen.

---

## Section VII — Geographic Reach

The Mechanism Record §6 declares geographic reach. The registry does not impose floors or ceilings on geographic reach itself, but the declaration must be specific. "Wherever needed" or similar non-specific declarations are returned for correction.

Acceptable forms:
- Specific jurisdictions (named cities, counties, states, countries)
- Defined geographic areas (e.g., "the contiguous United States," "Western Europe as defined by [reference]")
- Global, with explicit acknowledgment

Unacceptable forms:
- Undefined or expansive language ("as needed," "wherever applicable," "global presence")

---

## Section VIII — Coercive Ceiling

The Mechanism Record §6 declares coercive ceiling. The registry does not impose floors or ceilings on coercive intensity itself, but the declaration must be specific and bounded.

Acceptable forms:
- Specific actions (fines up to $X, suspension up to Y days, license revocation, etc.)
- Specific maximum severity (e.g., "may issue civil penalties; may not detain or restrict movement")

Unacceptable forms:
- Open-ended language ("such measures as may be necessary," "appropriate enforcement actions")
- Self-modifying language ("up to and including any action authorized by [external authority]")

---

## Section IX — Validation Logging

Every validation event is logged publicly:

- Submission received (timestamp)
- Validation result (accepted / returned with specific bounds-violations listed)
- If returned, the resubmission (if any) and its validation result

The validation log is part of the registry's permanent record. Declarations that pass validation are not endorsed by the validation log — the log records only that the declaration met the structural bounds defined in this document.

---

## Section IX-A — Type 1 Compensation Structure (form §6.1)

Type 1 dependencies must declare compensation structure using the enumerated values in form §6.1. Free-text-only declarations are returned for correction.

Compensation structures `revenue_share` and `outcome_tied` are themselves capture risk signals under R03 (Institutional Capture Prohibition) and R66 (Anti-Proxy Substitution). Declarations using these structures must include:
- Specific percentage or formula
- The outcome metric the compensation is tied to
- Whether the structure was approved by the authority's governance body
- Whether the structure has been reviewed for R66 proxy concerns

Authorities operationalizing Type 1 dependencies under `revenue_share` or `outcome_tied` arrangements are flagged in the registry index for stakeholder attention. This is not an evaluative determination; it is a structural disclosure.

---

## Section IX-B — External Authority Operationalization (form §6.8)

Each entry in §6.8 requires:
- External authority name (or category if identity is restricted)
- Decision type the external authority makes
- How the decision is operationalized within the registering authority
- Whether affected parties can distinguish the registering authority's decision from the external authority's

Form submissions that declare R72-relevant operationalization without these four elements are returned for correction.

If the registering authority operationalizes external decisions but declares §6.8 as "none," and a subsequent civic trigger or stakeholder review surfaces undeclared operationalization, the resulting finding is a Disclosure Completeness Assertion violation under §12.1.

---

## Section IX-C — Metric Publication Status (form §7.1)

Each declared metric in §7.1 must indicate publication status across three dimensions:
- Aggregate publication (statistical summaries): Y/N
- Individual publication (specific case data): Y/N
- Methodology publication (computation/application logic): Y/N

Aggregate-N + Methodology-N combinations are flagged as R67 (Minimum Auditability Floor) concerns. The registry does not reject these declarations; it surfaces them for stakeholder review.

Aggregate-N + Individual-N + Methodology-N for any metric materially influencing outcomes is a presumptive R79 (Metric Completeness) failure and triggers automatic provisional review.

---

## Section IX-D — Trade-Secret / Confidentiality Declarations (form §8.6)

Trade-secret declarations must specify:
- Category of restricted information
- Source of restriction (vendor contract, regulatory restriction, competitive harm, statutory privilege, other)
- Auditability mitigation in place
- Specific R67 floor commitment despite restriction

A §8.6 declaration claiming "trade secret" without specifying source is returned for correction.

Trade-secret claims that effectively prevent independent evaluation of:
- Scope, or
- Effect, or
- Harm thresholds, or
- Dependencies, or
- Reversibility, or
- Stop capability

constitute R67 floor violations and trigger automatic provisional review regardless of restriction source.

---

## Section IX-E — R67 Minimum Auditability Floor (form §§3, 4, 5, 6, 7, 9, 10)

R67 (Minimum Auditability Floor) requires that no authority operate below a non-waivable level of auditability sufficient to evaluate eight dimensions: scope, effect, harm thresholds, dependencies, derived outputs, reversibility, expiration, and stop capability. R67 does not specify what minimum disclosure constitutes "sufficient." This section defines the structural floor — what a Mechanism Record must contain in each dimension to be accepted. It does not adjudicate substantive adequacy; that remains with stakeholders through the SCBP-08 Challenge mechanism. Substantive adequacy below the structural floor results in registration rejection. Substantive adequacy above the floor but visibly thin can be challenged.

The floor applies to the form sections that already operationalize each R67 dimension. The registry validates form completion against this schedule.

### Dimension 1 — Scope (form §§1.2, 3.1, 3.2, 3.3, 3.4)

Required minimum elements:
- A functional description (not categorical) of what the authority can compel, restrict, allocate, or impose
- A specific declaration of geographic reach per Section VII of this document
- A specific declaration of coercive ceiling per Section VIII of this document
- A bounded resource ceiling (budget, staffing, or operational capacity)
- Explicit exclusions for at least four of the form's five exclusion categories (geographic, action, data, procedural, other)

A Mechanism Record that completes §§1.2 and 3.1–3.4 with specific bounded values meets the floor for this dimension. A Record that returns "as needed," "appropriate," "varies," or any non-bounded language to a required field fails the floor and is returned for correction.

### Dimension 2 — Effect (form §§1.3, 3.5, 7.1)

Required minimum elements:
- A declaration of authority classification (direct, indirect, or both) under §1.3
- A declaration of indirect-influence boundaries under §3.5 if the authority is classified as indirect or both, identifying the categories of decision the authority's outputs shape
- A declared metric set under §7.1 sufficient to explain observable outcomes within the authority's declared scope

A Mechanism Record that classifies as indirect (§1.3) without populating §3.5, or that declares scope under §3 inconsistent with the metric set under §7.1, fails the floor for this dimension.

### Dimension 3 — Harm thresholds (form §§4.1–4.7)

Required minimum elements:
- For each of the six R21 harm categories (bodily harm, agency impairment, ecological damage, generational binding, communicative suppression, informational sovereignty), either at least one measurable threshold per Section VI of this document, or an explicit "Not applicable" declaration with brief justification
- At least one declared threshold across all categories total — a Mechanism Record that declares "Not applicable" to all six R21 categories fails the floor regardless of justification, on the grounds that any authority capable of being registered necessarily produces effects that fall under at least one harm category
- §4.8 threshold change-log commitment must be marked

A Mechanism Record with one or more harm categories returning a threshold stated as an intention rather than a measurable condition (per Section VI) fails the floor for that category.

### Dimension 4 — Dependencies (form §§6.1, 6.2, 6.3, 6.4, 6.5)

Required minimum elements:
- §6.1 Type 1 dependencies enumerated, or "None" declared with justification
- §6.2 Type 2 dependencies enumerated, or "None" declared with justification
- §6.3 Type 3 dependencies enumerated, or "None" declared with justification
- §6.4 capture risk identification declared (Yes / No), with the categories of capture risk listed if Yes
- §6.5 reversibility-affecting dependencies enumerated

A Mechanism Record returning "None" to all four dependency-type fields without justification fails the floor on the grounds that any authority operating at the scale required for registration necessarily has at least one external dependency in some category.

### Dimension 5 — Derived outputs (form §§3.5, 6.8, 7.1)

Required minimum elements:
- §3.5 indirect-influence boundaries declared if the authority's outputs are read, used, or operationalized by other parties
- §6.8 external authority operationalization completed per Section IX-B of this document, or "None" declared with justification
- §7.1 metric publication status declared per Section IX-C of this document for each metric

A Mechanism Record that declares no derived outputs but produces outputs read by other parties (publications, scores, classifications, recommendations) fails the floor on the grounds of metric incompleteness.

### Dimension 6 — Reversibility (form §§9.1, 9.2, 9.3, 9.4, 9.5, 9.6, 9.7)

Required minimum elements:
- §9.1 estimated dismantling time declared as a specific duration
- §9.2 dismantling process described in concrete steps
- §9.3 entrenchment factors declared, or "Minimal / None" declared with justification
- §9.4 data disposition declared
- §9.5 downstream effect reversibility declared per R63
- §9.6 replacement feasibility addressed
- §9.7 reversibility verification status declared (rehearsed, simulated, planned, or not yet attempted)

A Mechanism Record returning "Indefinite" or "Not applicable" to §9.1, or "None / Not applicable" to §9.2 without justification, fails the floor.

### Dimension 7 — Expiration (form §§10.1–10.10)

Required minimum elements:
- §10.1 authorizing body named
- §10.2 date of authorization declared
- §10.3 expiration date declared as a specific date
- §10.4 renewal interval within the bounds set in Section V of this document
- §10.5 renewal evidence declaration for all five domains
- §10.6 necessity-decay acknowledgment marked
- §10.7 aggregate trigger threshold within the bounds set in Section II of this document
- §10.9 response time window within the bounds set in Section III of this document

A Mechanism Record missing any of these elements is returned for correction.

### Dimension 8 — Stop capability (form §§5.1, 5.2, 5.3, 5.4, 5.5, 5.6)

Required minimum elements:
- At least three independent stop paths declared per Section IV of this document
- For each stop path: activator, trigger condition, definition of "stopped," independence justification, and post-stop review process and timeline
- §5.4 confirmation of no penalty for activating stop
- §5.5 stop-path independence verification
- §5.6 civic trigger acknowledgment

A Mechanism Record declaring three stop paths that all depend on the authority's internal cooperation, or three stop paths whose independence cannot be substantiated by the structure declared, fails the floor regardless of the count.

### Application

The registry validates each Mechanism Record against this schedule at registration and at each renewal. Records that pass the schedule meet the structural floor; passing the schedule is not endorsement of substantive adequacy. Stakeholders may file Challenge-class triggers under SCBP-08 contesting whether substantive adequacy is met.

A Record that passes the floor but is contested through a sustained pattern of substantively-grounded Challenge findings becomes a candidate for floor revision: the schedule above is amendable through the registry's amendment process, and persistent pattern-of-challenges is one signal the schedule may be too low for the dimension.

---

## Section X — Amendment

This document is subject to the registry's amendment process (Registry Charter §9). Amendments may adjust bounds, add categories, or refine validation rules.

Amendments take effect prospectively. Mechanism Records registered before an amendment are not retroactively re-validated, but at next renewal must comply with the bounds in effect at that time.

If an amendment would have rejected a currently registered Mechanism Record, that fact is logged but does not by itself invalidate the registration. The authority is notified and given until next renewal to bring declarations into compliance.

---

## Section XI — Relationship to Other Documents

This document operationalizes the registration validation referenced in:

- SCBP-03 — Operations Manual, Stage 1 (Authorization)
- SCBP-08 — Civic Trigger Protocol, where Challenge-class triggers may contest declared values
- Registry Charter §6, where the operator's role in validation is constrained

If conflict exists between this document and a Mechanism Record, this document governs. If conflict exists between this document and the Structural Constitution, the Constitution governs. If conflict exists between this document and the Registry Charter, the Charter governs the registry's operating role; this document governs validation criteria.

---

*SCBP-09 — Registry Acceptance Standards — Operational Layer*
*All authority governed solely by the Structural Constitution (SCBP-04)*

---

*End of bundle. The AI should now proceed with the Mechanism Record per Part 1 instructions.*
