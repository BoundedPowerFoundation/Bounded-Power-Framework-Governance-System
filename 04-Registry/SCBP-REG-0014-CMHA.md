---
mechanism_id: SCBP-REG-0014
mechanism_name: "Cuyahoga Metropolitan Housing Authority"
authority_acronym: "CMHA"
status: PUBLIC_SOURCES
filed_by: third_party
domain: housing
authority_classification: direct
country: US
region: OH
subregion: Cuyahoga County
primary_postal_code: 44104
primary_address: "8120 Kinsman Road, Cleveland, OH 44104"
primary_url: "https://www.cmha.net/"
tax_id: not_applicable
registered_date: 2026-05-17
snapshot_date: 2026-05-17
last_reviewed_date: 2026-05-17
record_version: v1
authorization_date: 1933-01-01
expiration_date: UNKNOWN
renewal_interval_years: 5
funding_types:
  - federal_government_discretionary
  - federal_government_mandatory
  - self_funded_fee_for_service
funding_concentration_max_pct: 90
affected_party_categories:
  - residents_of_geographic_area
  - customers
  - employees
  - children
  - vulnerable_populations
  - non_consenting_third_parties
affected_population_estimate: 55000
non_consenting_population_estimate: 55000
entity_size: large
geographic_specificity: single_county
geographic_reach: "Cuyahoga County, Ohio (excluding Chagrin Falls Township). CMHA owns and manages approximately 10,500 public housing units in approximately 60 properties; administers Housing Choice Vouchers (Section 8) usable countywide. CMHA-PD jurisdiction extends to CMHA-owned and managed properties."
aggregate_threshold_count: 5
aggregate_threshold_window_days: 90
response_window_days: 30
harm_categories_declared:
  - bodily_harm
  - agency_impairment
  - generational_binding
  - informational_sovereignty
algorithmic_decision_systems_used: false
dependency_count_type1: 3
dependency_count_type2: 9
dependency_count_type3: 3
capture_risk_identified: true
disclosure_completeness_assertion: false
update_obligation_committed: false
discoverability_acknowledged: false
burden_of_proof_acknowledged: false
anti_weaponization_acknowledged: false
---

**PUBLIC SOURCES ONLY** — This Mechanism Record was produced by a third party from publicly available information. It has not been reviewed, confirmed, or filed by the authority it describes. Declarations reflect what could be determined from public sources as of the snapshot date. UNKNOWN fields indicate information that could not be reasonably determined from public sources.

---

# Mechanism Record — Cuyahoga Metropolitan Housing Authority

## SECTION 1 — What is this authority?

**1.1 — Mechanism name:** Cuyahoga Metropolitan Housing Authority (CMHA), originally established 1933 as the Cleveland Metropolitan Housing Authority and renamed in 1971.

**1.2 — Functional description:**
The authority is a political subdivision of the State of Ohio, created under ORC §3735.27 to §3735.50, that owns, manages, and operates federally subsidized housing in Cuyahoga County (excluding Chagrin Falls Township). Two principal programs:
- *Low-Income Public Housing (LIPH):* CMHA owns approximately 10,500 housing units across approximately 60 properties. Per the 2024 HUD OIG audit, more than 6,000 of these units were built before 1978 (the year lead paint was banned in residential use). CMHA acts as landlord, conducts unit inspections, sets rent based on tenant income (typically 30% of adjusted income), enforces lease terms, conducts eviction actions, and undertakes major redevelopment (e.g., Buckeye-Woodhill Choice Neighborhoods Transformation).
- *Housing Choice Voucher (HCV) Program (Section 8):* CMHA administers federal voucher subsidies that eligible tenants use to rent from private landlords countywide. CMHA determines eligibility, sets payment standards, conducts Housing Quality Standards (HQS) inspections of private units, terminates voucher assistance for program violations, and manages a waiting list (specific current length UNKNOWN; voucher waiting lists at large PHAs typically multi-year and intermittently closed).

CMHA also operates:
- *CMHA Police Department (CMHA-PD):* OPOTC-certified sworn police force authorized under Ohio House Bill 129 (1985) with arrest authority equivalent to municipal police on CMHA-owned and -managed properties. Per public sources, CMHA-PD operates Patrol, K-9, Detective, Crime Suppression, SWAT, Community Policing, Special Investigations, and Logistics functions. CALEA-accredited.
- *Resident services:* employment training, support programs for elderly, services for youth aged out of foster care, partnerships with community organizations
- *Capital and redevelopment:* the Buckeye-Woodhill Choice Neighborhoods Transformation (HUD Choice grant) is the largest current redevelopment program

CMHA is governed by a five-member Board of Commissioners.

**1.3 — Authority classification:**
- [x] Direct — issues binding determinations through lease enforcement, eviction, voucher termination, HQS inspection, CMHA-PD enforcement, eligibility determinations
- [ ] Indirect
- [ ] Both

**1.4 — Domain:**
- [x] Government
- [ ] Economic
- [ ] Technology
- [ ] Infrastructure
- [ ] Data / Information
- [ ] Education
- [ ] Healthcare
- [ ] Cultural / Religious
- [ ] Voluntary association
- [x] Other: housing (the framework's domain list does not include a standalone "housing" category; marked Government with secondary disclosure of the housing function)

ANNOTATION: the YAML domain field is set to "housing" per the framework's enumerated values, reflecting that this is a sectoral authority rather than a general-government authority. Both Government and housing are accurate; the YAML uses "housing" per the enumerated values in the bundle.

**1.5 — Statutory or constitutional basis:**
- Ohio Revised Code §3735.27 through §3735.50 (Metropolitan Housing Authorities)
- Ohio House Bill 129 (1985) authorizing OPOTC-certified sworn police force at metropolitan housing authorities
- U.S. Housing Act of 1937 (as amended)
- U.S. Housing Act of 1974 (creating Section 8)
- Quality Housing and Work Responsibility Act of 1998 (QHWRA)
- 24 CFR Part 5 (HUD general provisions)
- 24 CFR Parts 902, 903, 905, 906, 960, 964, 965, 966, 982, 983, 985 (PHA operations, public housing, HCV, HQS, capital fund, MTW, etc.)
- 24 CFR Part 35 and 40 CFR Part 745 (Lead-Based Paint Hazard rules: Title X of Housing and Community Development Act of 1992; Renovation, Repair and Painting Rule)
- Fair Housing Act (42 U.S.C. §3601 et seq.)
- Title VI of the Civil Rights Act of 1964
- Americans with Disabilities Act and Section 504 of the Rehabilitation Act
- HUD-PHA Annual Contributions Contract (ACC) governing the operating subsidy relationship
- HUD Annual Plan submission requirements
- CMHA's Admissions and Continued Occupancy Policy (ACOP), HCV Administrative Plan

ANNOTATION: this authority operates under a substantially heavier federal regulatory framework than the municipal authorities previously registered. HUD is both funder and regulator.

---

## SECTION 2 — Who can this authority act upon?

**2.1 — Affected party categories:**
- [ ] General public
- [x] Residents of defined geographic area: Cuyahoga County residents, particularly low-income residents eligible for or seeking public housing or HCV assistance
- [x] Customers / voluntary service users: CMHA tenants in public housing; HCV participants; HCV-receiving landlords
- [ ] Members
- [x] Employees / workers: approximately 400 CMHA employees per public sources (200–500 range per ZoomInfo); union and non-union staff
- [ ] Students
- [ ] Patients
- [ ] Regulated industry participants
- [x] Criminal justice involved individuals: persons arrested by CMHA-PD; persons subject to "one strike" lease enforcement for criminal activity
- [x] Children / minors: children residing in CMHA-managed housing — the 2024 HUD OIG audit specifically identified 10 EBLL (Elevated Blood Lead Level) cases involving children plus four unconfirmed
- [x] Vulnerable populations: elderly residents in CMHA senior housing; persons with disabilities (including those with mobility, sensory, or cognitive impairments protected under Section 504 and ADA); persons aged out of foster care; persons with mental illness; survivors of domestic violence (VAWA protections apply)
- [ ] Future generations
- [x] Non-consenting third parties: minor children residing with adult lease-holders (children do not sign leases but are subject to all CMHA authority); household members added by tenant who become subject to lease compliance; neighbors of CMHA properties affected by operations

**2.2 — Approximate number of people directly affected:**
- Public housing units: approximately 10,500 (over 6,000 built before 1978)
- ASSUMPTION average household size 2.0–2.5 → public housing resident population approximately 21,000–26,000
- HCV vouchers in use: UNKNOWN exact count; large PHAs typically administer thousands of vouchers. ASSUMPTION 5,000–10,000 vouchers in use → voucher household population approximately 12,500–25,000
- HCV waiting list: UNKNOWN current count; commonly several thousand applicants
- Total directly affected: ASSUMPTION approximately 50,000–60,000 residents and participants, plus approximately 400 employees and an additional waiting-list population

**2.3 — Non-consenting portion:**
The framework's "voluntary-but-stuck" test (§2.3 of the form) applies in a distinctive way for CMHA:
- Public housing residents technically apply for and accept tenancy; however, in Cleveland's housing market (with documented affordable-housing scarcity and the city's residents facing financial challenges including East Cleveland's state receivership), the available alternatives are limited. The framework treats this as substantively non-consenting for the duration of tenancy.
- *Children residing in CMHA housing did not consent and could not leave.* The 2024 HUD OIG audit findings on lead-paint hazards and EBLL cases primarily affect this non-consenting population.
- HCV recipients could in principle exit the program, but exit means losing the subsidy and likely housing access; substantive exit cost is very high.
- For SCBP-09 §II purposes, the non-consenting population is approximately 55,000 (combining LIPH residents, HCV participants, waiting list, and employees).

ANNOTATION: this non-consenting characterization is *substantively heightened* because affected parties are by definition low-income, often have limited housing alternatives, and include children. The framework's R26 (Non-Participant Harm Floor) imposes stricter harm tolerances for non-consenting populations; this authority operates near that floor by design.

**2.4 — Vulnerable population specifics:**
- [x] Children (under age of majority): the most-affected category. Lead-paint exposure risk specifically affects children under age 6 (developmental brain effects). The 2024 HUD OIG audit found CMHA "did not adequately communicate lead hazards to tenants and failed to properly investigate 10 cases of children with elevated blood lead levels (EBLL)." Per CLASH (Cleveland Lead Advocates for Safe Housing), Cleveland's lead-poisoning rate is approximately four times the national average; the local health department investigates approximately 300 EBLL cases annually.
- [ ] Patients during medical care
- [ ] Detained or confined persons
- [x] Persons in coercive economic relationships: the landlord-tenant relationship in subsidized housing has structural coercive elements (lease compliance, recertification, "one strike" criminal provisions, eviction risk equals housing loss for low-income households with limited alternatives)
- [x] Persons unable to advocate for themselves due to disability, incapacity, or circumstance: elderly residents in senior housing; persons with disabilities; non-English-speaking residents (LEP); persons with mental health conditions

Protective measures per public sources include: VAWA confidentiality protections; ADA/504 reasonable accommodation processes; HUD grievance procedures (24 CFR Part 966 Subpart B); Resident Advisory Council and Resident Council structures; the Board's Resident Affairs Committee; tenant organizations.

ANNOTATION: the 2024 HUD OIG audit and the subsequent Cleveland City Council hearing revealed substantive gaps in protective measures for child residents specifically. CMHA painted over deteriorating lead paint in 5 of 10 EBLL cases before investigations were complete, per the OIG audit; CMHA pushed back stating documentation was missing but assessments occurred. The framework treats this dispute as a substantive R67 (Minimum Auditability Floor) finding: if assessments occurred but cannot be documented, the floor is not met regardless of whether assessments actually occurred.

---

## SECTION 3 — What can it do, and what can it not do?

**3.1 — Geographic reach:**
- [ ] Single municipality
- [ ] Multi-municipality
- [x] Single county/parish: Cuyahoga County, Ohio (excluding Chagrin Falls Township)
- [ ] Multi-county
- [ ] Single state/province
- [ ] Multi-state/multi-province
- [ ] Single nation
- [ ] Multi-national
- [ ] Global

HCV vouchers can be ported (transferred) to other PHAs under HUD portability rules, creating limited extra-county effect.

**3.2 — Coercive ceiling:**
The strongest actions available to the authority include:
- *Eviction from public housing:* termination of tenancy, including for criminal activity ("one strike" provisions per QHWRA), nonpayment of rent, lease violations, or unauthorized occupants. Eviction results in loss of housing for low-income households with limited alternatives.
- *Voucher termination:* termination of HCV assistance results in loss of subsidy; in tight rental markets, this typically means inability to retain or obtain rental housing.
- *Eligibility denials:* denial of admission to public housing or HCV based on income, criminal history, prior tenancy issues, or other eligibility factors
- *CMHA-PD authority:* full sworn police authority on CMHA properties — arrest, use of force, use of OPOTC-authorized weapons (per public sources, Glock 17 9mm pistols, Benelli 12ga shotguns, Heckler & Koch UMP45 sub-machine guns for SWAT use; TASER X-26; OC spray; 37mm grenade launcher restricted to SWAT for tactical situations and crowd control), and referral for prosecution
- *Rent determination:* setting tenant rent obligations through income recertification (annual and interim)
- *Inspection and habitability determination:* HQS inspections of HCV units; UPCS-V (Uniform Physical Condition Standards–Voucher) inspections; public housing unit inspections; determinations of habitability affecting tenant remedies and landlord obligations
- *Property management decisions affecting residents:* utility allowances, parking, common-area rules, guest policies, smoke-free policies, pet policies
- *Capital/redevelopment decisions:* RAD (Rental Assistance Demonstration) conversions; Choice Neighborhoods demolitions and replacements affecting relocation of residents; HOPE VI legacies
- *Visitor and trespass authority:* CMHA-PD may issue trespass notices banning persons from CMHA property

ANNOTATION: the combination of housing-loss authority with sworn police authority concentrates coercive power. Per the framework, this concentration is a structural risk requiring heightened oversight under R03 and R26.

**3.3 — Resource ceiling:**
- Operating budget: UNKNOWN current annual figure from public sources reviewed. HUD's Operating Fund and Capital Fund are the principal sources; HCV Housing Assistance Payments (HAP) flow through CMHA from HUD to private landlords (CMHA receives administrative fees). For PHAs of CMHA's size, annual operating and HAP totals typically aggregate to several hundred million dollars.
- Staff: approximately 400 employees per public sources; ZoomInfo range 201–500
- Housing stock: approximately 10,500 public housing units; voucher count UNKNOWN
- Real estate holdings: substantial, including the 25-acre headquarters campus at 8120 Kinsman Road and numerous housing developments countywide
- Data systems: tenant database (PIH-EIV — Enterprise Income Verification — HUD requirement); HCV management system; work-order/maintenance systems; CMHA-PD records; lead-paint disclosure system (subject to 2024 HUD OIG audit findings on adequacy)
- Capital: HUD Capital Fund and competitive grant authority including Choice Neighborhoods, RAD, and bond issuance authority granted under ORC §3735

**3.4 — Explicit exclusions — what this authority may NOT do:**
- [x] Geographic exclusions: no authority outside Cuyahoga County except for HCV portability
- [x] Action exclusions: cannot evict without due process (24 CFR Part 966; Ohio landlord-tenant law; federal grievance procedures); cannot deny admission based on protected-class status (Fair Housing Act); cannot terminate Section 504 reasonable accommodations; cannot evade VAWA protections; cannot apply policies inconsistent with HUD-approved ACOP or HCV Administrative Plan; cannot bypass HUD grievance procedures for adverse actions on public housing residents (24 CFR §966.50–.57)
- [x] Data exclusions: tenant data subject to Privacy Act and HUD privacy rules; PIH-EIV access strictly governed; income-verification information cannot be shared outside enumerated purposes
- [x] Procedural exclusions: cannot terminate Section 8 voucher without informal hearing; cannot conduct evictions without notice and opportunity to be heard
- [ ] Temporal exclusions: not applicable
- [x] Other exclusions: cannot reject HCV applicants based on source of income in Ohio (as of 2024 source-of-income protections vary by jurisdiction; status UNKNOWN); cannot evict survivors of domestic violence solely on the basis of being a victim (VAWA)

**3.5 — Indirect influence boundaries:**
Not applicable per §1.3 classification. However, CMHA outputs materially influence:
- Private rental market in Cuyahoga County (HCV recipients constitute a significant share of demand at certain rent levels; CMHA payment standards shape rent levels)
- Eviction records propagating to court records and tenant-screening databases
- Criminal history records (CMHA-PD arrests propagating to county, state, federal systems)
- Property values in neighborhoods with concentrated CMHA properties
- Health outcomes for residents (lead exposure, indoor air quality, mold, pest infestations)
- Educational outcomes for resident children (housing stability is correlated with educational attainment)

**3.6 — Anti-proxy declaration:**
UNKNOWN. HUD-required Title VI program addresses certain disparate-impact considerations. Fair Housing Act protections apply. No explicit anti-proxy declaration covering, for example, the use of "lease compliance" as a proxy for selective enforcement, the use of CMHA-PD deployment patterns as proxies for concentrated surveillance of resident populations, or the use of "fitness for tenancy" criteria as proxies for excluded considerations, was located in public sources.

ANNOTATION: housing authorities have a documented history of disparate-impact litigation and HUD enforcement actions; the framework's R66 (Anti-Proxy) and R74 (Proxy Equivalence Expansion) standards apply. The 2024 HUD OIG lead-paint findings raise R66-relevant questions about whether painting-over practices functioned as a structural mechanism that disproportionately deferred costly remediation in lower-income, majority-minority resident communities. Public sources do not characterize the findings this way; the framework's R66 analysis is independent of intent.

---

## SECTION 4 — What harms can it cause?

**4.1 — Bodily harm threshold:**
Threshold: not explicitly declared as a measurable condition.

*The 2024 HUD OIG audit makes this the most acute harm category for this authority.* Substantive bodily-harm vectors:
- *Lead-paint exposure in children.* The 2024 HUD OIG audit found CMHA failed to report 10 EBLL cases (plus 4 unconfirmed) to HUD; failed to conduct adequate environmental investigations in 5 of 10 cases; painted over deteriorating paint before investigations were complete in those 5 cases. The audit determined that approximately 1,572 of an estimated 2,252 CMHA units with lead paint were not meeting required timelines for visual assessments. There is no safe level of lead in a child's blood; lead exposure in children causes permanent neurological damage.
- *Other habitability hazards:* mold, pest infestations, carbon monoxide, asbestos (units built before 1978 may contain), structural deficiencies, fire safety. UNKNOWN whether peer-benchmark thresholds for habitability complaints, work-order completion times, or annual inspection failure rates are formally adopted.
- *CMHA-PD use of force.* Public sources document CMHA-PD's substantial weapons inventory and SWAT capability. UNKNOWN whether use-of-force thresholds (incidents per 1,000 calls, etc.) are tracked against peer benchmarks.
- *Mental health crisis encounters by CMHA-PD* in housing settings with concentrated low-income populations
- *Eviction-related health impacts.* Eviction is associated with increased mortality, mental-health harms, and homelessness risk

A measurable threshold candidate: "Confirmed EBLL cases in CMHA-housed children per year exceeding zero triggers immediate program review" (the framework's harm-floor logic suggests *any* EBLL case in a child residing in HUD-overseen housing is a structural failure requiring review).

ANNOTATION: this is the most substantive bodily-harm finding of any record produced in this registry so far. The 2024 HUD OIG audit is a direct, recent, documented Stop Path 3 (federal oversight) activation; the CLASH advocacy and Cleveland City Council hearing are direct Stop Path 1 / Stop Path 2 activations.

**4.2 — Agency impairment threshold:**
Threshold: not explicitly declared. Substantive agency-impairment vectors:
- *Eviction and voucher termination* remove housing access for households with limited alternatives
- *Recertification and reporting requirements* impose substantial procedural burden; failure to comply can trigger termination
- *"One strike" criminal-activity lease provisions* allow termination based on conduct of household members or guests
- *Waiting list management* (open/closed status, position-on-list determinations) controls access to housing assistance
- *Trespass and ban authority* by CMHA-PD restricts movement of visitors and former tenants
- *Lead-disclosure failures* impair tenants' ability to make informed housing decisions and to protect children — a substantive agency-impairment vector documented in the 2024 HUD OIG audit
- *Public housing rules* (guest policies, smoke-free policies, parking, etc.) constrain daily autonomy in ways materially different from private rental tenancy

A measurable threshold candidate: "annual eviction rate per 100 units exceeding peer-PHA benchmark triggers review" or "informal hearing reversal rate exceeding X% triggers process review."

**4.3 — Ecological damage threshold:**
- [x] Not applicable as a primary harm category. Capital projects (demolitions, redevelopment under Choice Neighborhoods) have ecological-construction footprints similar to general municipal capital projects. The LEED Silver Certified headquarters and solar field are positive ecological disclosures.

**4.4 — Generational binding threshold:**
Threshold: not explicitly declared. Substantive generational-binding vectors:
- *Lead exposure causes permanent neurological damage in children.* This is the most acute generational-binding vector in this record. Damage cannot be reversed; affected individuals carry effects for life.
- *Eviction records propagate forward* through tenant-screening databases, affecting future housing access for years
- *Criminal records from CMHA-PD arrests* propagate forward in chain of background-check systems
- *Choice Neighborhoods demolitions and redevelopments* bind future residents and neighborhoods to new physical and tenure configurations for decades
- *Bond debt and capital obligations* bind future budgets

A measurable threshold candidate: "any documented EBLL case in a child residing in CMHA housing triggers permanent generational-binding finding" — given the irreversible nature of lead-induced neurological damage, the framework's R27 (Reversibility) and R63 (Downstream Effect Reversibility) standards are *not met* for harm to affected children.

**4.5 — Communicative suppression threshold:**
- [x] Not applicable as a primary harm category. CMHA's authority is not principally communicative. Tenant-organizing rights are federally protected under 24 CFR §964. UNKNOWN whether tenant grievances or advocacy activity have been the subject of retaliatory enforcement at CMHA specifically.

**4.6 — Informational sovereignty threshold:**
Threshold: not explicitly declared. Substantive informational-sovereignty vectors:
- *PIH-EIV income data* on tenants is among the most sensitive financial data routinely collected by any authority in this registry
- *Tenant household composition data* including ages of children, immigration status of household members, disability status, employment, criminal history
- *CMHA-PD records* on residents and visitors
- *Lead-disclosure records* (subject to 2024 HUD OIG findings on adequacy)
- *Background-check data* used for tenant screening
- Long retention periods are typical for HUD records (often 3+ years post-tenancy)

A measurable threshold candidate: "retention of tenant-screening or eviction-decision records beyond 7 years post-termination of tenancy triggers review for purge."

**4.7 — Additional harm thresholds:**
*Disparate-impact on majority-minority resident population.* CMHA's resident population is substantially majority-minority. Any operational practice that produces disparate outcomes (in eviction rates, work-order completion times, lead-hazard exposure rates by property, voucher-program eligibility decisions, CMHA-PD enforcement patterns) is a structural harm category not directly captured by the framework's six standard categories. No automatic-review threshold is publicly declared.

*Cumulative-disinvestment harm.* The 2024 HUD OIG audit context — CMHA being the oldest housing authority in the U.S., with over 6,000 units built before 1978 in a city where lead poisoning rates are four times the national average — reflects long-run capital underinvestment and federal-funding inadequacy. This is a harm pattern caused jointly by federal funding levels, state policy, and CMHA operational decisions; the framework treats this as R76 (Mandatory Degradation Requirement) relevant in reverse: capacity has degraded over time without proportionate scope reduction.

**4.8 — Threshold change-log commitment:**
- [ ] Yes — committed
- [ ] Cannot commit
- [x] UNKNOWN — the HUD Annual Plan cycle requires periodic substantive review and public input on PHA policies, which is a partial change-log mechanism. A formal threshold change-log commitment per R08 is not explicitly declared.

---

## SECTION 5 — What stops it?

**STOP PATH 1 — HUD Grievance Procedures, Informal Hearings, and Resident Councils**
- Who can activate it: any tenant, applicant, or HCV participant aggrieved by a CMHA action
- Trigger condition: filing of grievance per 24 CFR §966 Subpart B (public housing) or informal-hearing request under 24 CFR §982.554–.555 (HCV); Resident Council and Resident Advisory Board provide collective channels
- What "stopped" means: hearing officer's determination can require CMHA to change the contested action; in HCV cases, can prevent voucher termination
- Independence justification: hearing officers must be impartial and may not be the person who took the contested action; Resident Councils are member-elected per 24 CFR §964
- Post-stop review process and timeline: per federal regulation timelines

ANNOTATION: this is an internal authority-level mechanism, not a fully external stop path. Hearing officers may be CMHA employees or designees. The framework's R32 (Independent Stop Authority) is partially satisfied through impartiality requirements but not fully satisfied through structural independence.

**STOP PATH 2 — Federal Courts, State Courts, and Federal Enforcement (HUD OIG, HUD FHEO, DOJ)**
- Who can activate it: tenants, applicants, advocacy organizations, federal agencies. The 2024 HUD OIG audit is a direct example of activation.
- Trigger condition: judicial filings under Fair Housing Act, ADA, Section 504, Title VI, §1983 civil rights, state landlord-tenant law; HUD OIG audits; FHEO Title VI/FHA investigations; DOJ pattern-or-practice investigations
- What "stopped" means: judicial injunctive relief; HUD findings requiring remediation (the 2024 OIG audit issued multiple specific recommendations CMHA must respond to); withholding of federal funds; consent decrees
- Independence justification: federal and state courts and federal enforcement agencies operate outside CMHA structure
- Post-stop review process and timeline: judicial timelines vary; OIG audits are multi-year processes with public reports and required management responses

**STOP PATH 3 — Cleveland City Council, Cleveland Health Department, Local Advocacy, and Board of Commissioners**
- Who can activate it: Cleveland City Council (per the 2024 lead-safety hearing); Cleveland Department of Public Health (which investigates EBLL cases per the public sources); CLASH and other advocacy organizations; tenant organizing groups; the CMHA Board of Commissioners through governance action
- Trigger condition: legislative inquiry, regulatory investigation, public advocacy, Board policy action
- What "stopped" means: Cleveland City Council can hold hearings and propose bringing CMHA under city Lead Safe Housing law (preemption questions noted in public sources); CDPH can determine source of lead poisoning and engage CMHA on remediation; advocacy can shape Board decisions and federal-grant recommendations; the Board can replace executives and adopt policies
- Independence justification: Cleveland City Council, CDPH, and advocacy groups operate outside CMHA structure. The Board of Commissioners is appointed by Cleveland Mayor (2 seats), Cleveland City Council (2 seats), and East Cleveland Mayor (1 seat) — structurally outside CMHA operations but politically connected to Cleveland authority.
- Post-stop review process and timeline: variable; the 2024 audit-response cycle is illustrative

ANNOTATION: the Board's appointment structure creates a substantive Cleveland-political nexus. Of five Board seats, four are appointed by Cleveland authorities; the fifth by East Cleveland. The framework treats this as appropriate political accountability but notes that no Board seat is independently elected by residents. One Cleveland-Mayor-appointed seat must be filled by a CMHA resident, which is a partial resident-representation mechanism.

**5.4 — Penalty for activating stop:**
- [x] Confirmed — no formal penalty for filing grievances, informal hearings, OIG complaints, judicial action, or advocacy activity. Federal regulations specifically protect against retaliation. CMHA's tenant-organizing protections under 24 CFR §964 apply.

ANNOTATION: informal penalties — selective enforcement, slower work-order response, scrutiny of household members — are documented general risks in public-housing literature. Whether these patterns occur at CMHA specifically is UNKNOWN from public sources reviewed.

**5.5 — Stop-path independence verification:**
- [x] Yes — federal courts, HUD OIG, HUD FHEO, state courts, Cleveland City Council, and advocacy organizations can act without CMHA cooperation. The HUD OIG 2024 audit is concrete evidence of independent stop-path activation.

**5.6 — Civic trigger acknowledgment:**
- [ ] Not applicable — this Mechanism Record is third-party-produced.

---

## SECTION 6 — What does it depend on?

**6.1 — Type 1 dependencies (operational extensions acting under this authority):**

*Property management contractors and on-site staff*
- What they do: day-to-day property management at specific developments; some properties operate under mixed-finance partnership structures with private developers (e.g., The Community Builders for Buckeye-Woodhill Choice Neighborhoods)
- Contractual relationship: management contracts, Housing Assistance Payment contracts, partnership agreements
- Compensation structure: per contract (specifics UNKNOWN)

*Maintenance and capital-project contractors*
- What they do: unit turnover, capital renovations, lead remediation (subject to 2024 HUD OIG findings on adequacy), construction
- Contractual relationship: procurement contracts under federal procurement standards (2 CFR Part 200)
- Compensation structure: per contract (specifics UNKNOWN)

*HCV-receiving landlords (over 1,000 likely; specific count UNKNOWN)*
- What they do: provide private rental housing to HCV voucher holders; receive monthly HAP payments from CMHA; subject to HQS inspections
- Contractual relationship: Housing Assistance Payment (HAP) contract per HCV unit
- Compensation structure: HAP based on payment standards and tenant rent share; market-rate compensation rather than CMHA discretion

ANNOTATION: HCV landlords are simultaneously contractors and external authorities. CMHA decisions on payment standards, inspection protocols, and Section 8 administrative practices materially shape landlord incentives.

**6.2 — Type 2 dependencies (independent authorities with structural relationship):**

- *U.S. Department of Housing and Urban Development (HUD)* — upstream: funding (ACC, Capital Fund, HCV HAP, Choice Neighborhoods grants), regulation, audit (OIG), enforcement (FHEO), required Annual Plan approvals. This is the most-consequential upstream relationship in the record.
- *HUD Office of Inspector General* — independent: audits (the 2024 lead-paint audit)
- *Cleveland City Mayor and Council* — upstream: Board appointments (4 of 5 seats); coordination on housing policy, lead-safety law (the Cleveland 2019 Lead Safe Housing law and the Local Rule 3.015 eviction-affidavit requirement subsequently overturned); Cleveland Department of Public Health investigates EBLL cases
- *East Cleveland City Mayor* — upstream: 1 Board appointment
- *Cleveland Department of Public Health* — coordinate: EBLL investigations
- *Cleveland Municipal Court / Cuyahoga County Court of Common Pleas* — downstream: eviction adjudication, civil-rights cases
- *Ohio Peace Officer Training Commission (OPOTC)* — upstream: CMHA-PD officer certification
- *CALEA* — coordinate: police-department accreditation
- *Cuyahoga Land Bank, City of Cleveland Department of Community Development, and other regional housing-and-development authorities* — coordinate: redevelopment, Choice Neighborhoods, neighborhood revitalization

**6.3 — Type 3 dependencies (infrastructure whose failure would compromise stop paths or auditability):**

- *PIH-EIV (Enterprise Income Verification system)* — HUD-operated; failure or restricted access would compromise income certification and audit capacity
- *CMHA records systems for lead-paint disclosures, work orders, inspections, complaints* — per the 2024 HUD OIG audit, CMHA's prior records system was deficient for lead-disclosure documentation. Per public sources, CMHA "rolled out a new computer records system to track complaints and automate lead hazard disclosures to tenants" in response. Continuity and audit-trail integrity of this system are central to R67 (Minimum Auditability Floor) and to the federal stop-path adequacy.
- *CALEA accreditation infrastructure for CMHA-PD* — failure or revocation would affect police-oversight credibility

**6.4 — Capture risk identification:**
- [x] Yes
  - *HUD funding concentration:* CMHA is overwhelmingly federally funded. HUD Operating Fund, Capital Fund, HCV HAP, and competitive grants together comprise the substantial majority of revenue (ASSUMPTION 85–95%). Far exceeds the 33% threshold. Federal funding is conditional on compliance with federal executive orders, regulations, and Annual Plan approvals.
  - *Federal-executive-policy conditionality:* changes in federal housing policy (as has occurred across administrations) directly alter CMHA's operating environment, funding levels, and policy constraints. The 2025 federal executive-order context affecting other federally-funded agencies in this registry (see SCBP-REG-0012, GCRTA, where DEI language was removed from the Code Book) applies to CMHA as well. UNKNOWN current specific CMHA accommodations to federal policy changes.
  - *Capital-project contractor concentration:* large-scale redevelopment (Buckeye-Woodhill Choice Neighborhoods is a six-phase, multi-hundred-million-dollar program) creates concentrated relationships with specific developers (The Community Builders is named in public sources) and contractors. Per R03 (Institutional Capture Prohibition), this is a structural risk requiring disclosure and monitoring.
  - *Board-appointment political nexus:* 4 of 5 Board seats appointed by Cleveland authorities creates Cleveland-political alignment. While appropriate political accountability, this also creates structural alignment with Cleveland political interests in ways that may not represent all 59 Cuyahoga County communities equally.
  - *HUD-OIG audit findings as capture indicator:* the 2024 audit finding that CMHA painted over deteriorating lead paint before investigations were complete, while CMHA disputes the characterization, raises a structural-capture-risk question relevant to R66 (Anti-Proxy): whether routine operational practices functioned to defer or obscure costly remediation. The framework treats this as a structural disclosure rather than as a determination of intent.

**6.5 — Reversibility-affecting dependencies:**
- *Lead-paint hazards already created in pre-1978 housing stock:* approximately 6,000+ units; abatement is expensive and slow. The cumulative downstream effect on children affected by lead exposure is not reversible.
- *Choice Neighborhoods redevelopments:* once demolitions occur and replacement properties are built, reversal is impractical
- *Bond debt and capital obligations:* bind future budgets
- *HUD ACC obligations:* the ACC governs the operating subsidy relationship and continues across administrations
- *Long-term ground leases and partnership structures* in mixed-finance developments
- *Employee pension obligations:* under Ohio public employee retirement systems

**6.6 — Coordination disclosures:**
CMHA coordinates with:
- City of Cleveland Department of Community Development
- Cuyahoga Land Bank
- The Community Builders (named development partner for Choice Neighborhoods)
- Council of Large Public Housing Authorities (CLPHA) — national peer network
- Cleveland/Cuyahoga County Continuum of Care (homeless services)
- Cleveland Public Power (solar field collaboration)
- Sherwin-Williams (Home Work Paint Program partnership for residents)
- DigitalC (broadband access for residents)

Per R55/R59, federal regulation of PHAs nationwide creates a coordinated regulatory system; CMHA is one component of a national PHA structure governed by HUD.

**6.7 — Disclosure completeness assertion:**
- [ ] Not asserted — this Mechanism Record is third-party-produced.

**6.8 — External authority operationalization (R72):**
- *HUD regulations and HUD-approved ACOP, HCV Administrative Plan, Annual Plan* — operationalized through CMHA day-to-day decisions affecting residents. Affected parties experience CMHA actions but the underlying federal rules are external.
- *Federal lead-paint standards (24 CFR Part 35, 40 CFR Part 745)* — operationalized through CMHA inspection and remediation practices; 2024 HUD OIG audit identifies gaps in operationalization
- *PIH-EIV income limits and rent calculations* — federal determinations operationalized as CMHA tenant rent obligations
- *Fair Housing Act, ADA, Section 504* — federal substantive standards operationalized through CMHA policies and procedures
- *Federal "one strike" criminal-activity authority* — federal statutory authority operationalized through CMHA lease enforcement
- *OPOTC certification standards* — operationalized through CMHA-PD hiring

This R72 surface is among the heaviest of any record produced in this registry. CMHA functions substantially as a local operationalization of federal housing policy.

---

## SECTION 7 — What metrics, signals, and decision inputs shape outcomes?

**7.1 — Declared metrics:**

| Metric | Source | Role | Aggregate pub. | Individual pub. | Methodology pub. |
|---|---|---|---|---|---|
| HUD PHA Assessment Score (PHAS / SEMAP) | HUD / CMHA | Accountability | Y (HUD public) | N | Y (HUD methodology public) |
| Occupancy rate | CMHA / HUD | Operational | Y (HUD reports) | N | Y |
| Unit turnover time | CMHA | Operational | UNKNOWN | N | UNKNOWN |
| Work-order completion times | CMHA | Operational | UNKNOWN | UNKNOWN | UNKNOWN |
| Eviction filings and outcomes | CMHA / Courts | Accountability, operational | UNKNOWN (court records public per case) | UNKNOWN | UNKNOWN |
| HCV voucher utilization and HAP payments | CMHA / HUD | Operational, financial | Y (HUD reports) | N | Y |
| HQS inspection results | CMHA | Compliance | UNKNOWN | N | Y (HQS methodology public) |
| Lead-paint inspection and EBLL reporting | CMHA / HUD / CDPH | Compliance, safety | Partial (2024 HUD OIG audit publicly reported findings) | N | Partial (per OIG audit, methodology gaps existed) |
| CMHA-PD complaints and dispositions | CMHA-PD | Accountability | UNKNOWN | UNKNOWN | UNKNOWN |
| Use of force | CMHA-PD | Safety, accountability | UNKNOWN | UNKNOWN | UNKNOWN |
| Board resolutions and meeting agendas | Board / CMHA | Governance | Y (cmha.net) | N/A | Y |
| Annual Plan submissions and audit reports | CMHA / HUD | Governance, compliance | Y (HUD public, CMHA public) | N/A | Y |

ANNOTATION: per SCBP-09 §IX-C, HUD-mandated reporting provides strong aggregate-publication of certain metrics (occupancy, voucher utilization, PHAS scores). However, the 2024 HUD OIG audit specifically identifies methodology and documentation gaps for lead-paint inspections and EBLL reporting — a substantive R67/R79 (Metric Completeness) failure documented in federal record. Public sources also indicate that CMHA-PD complaint and use-of-force aggregate data are not readily available.

**7.2 — Indirect signals:**
- Federal funding environment (under different administrations)
- Local political dynamics (Cleveland Mayor and Council, East Cleveland Mayor)
- Real estate market trends and rents (affecting payment standards)
- Construction cost trends (affecting capital programs)
- Resident-organizing activity and advocacy-group activity (CLASH, tenant councils, Cleveland Tenants Organizations)
- Press attention to housing-conditions issues (Signal Cleveland, Ideastream, Axios Cleveland, news5cleveland.com)
- CLPHA peer comparisons

**7.3 — Algorithmic decision systems:**
- [ ] Yes
- [x] No (as far as public sources indicate). CMHA uses standard PHA management software, PIH-EIV (a HUD system), and tenant-screening tools (which may use vendor algorithmic scoring). UNKNOWN whether specific algorithmic decision systems are used for waiting-list prioritization, eviction-triage, or police-deployment decisions. Tenant-screening services used in HCV landlord-screening contexts often include algorithmic scoring; CMHA's specific use is UNKNOWN.

**7.4 — Outcome-versus-declaration check:**
- [ ] Not formally declared as a structural commitment. HUD PHAS, SEMAP, OIG audits, Annual Plan cycles, and the recent 2024 OIG audit provide *external* outcome-versus-declaration mechanisms. A formal R79/R80 commitment is not declared as CMHA's own practice.

---

## SECTION 8 — How is this authority watched?

**8.1 — Drift monitoring mechanism:**
- *HUD PHAS (Public Housing Assessment System) and SEMAP (Section Eight Management Assessment Program)* — annual; surfaces operational drift
- *HUD Annual Plan and Five-Year Plan cycles* — periodic substantive review with public-input requirements
- *HUD OIG audits* — episodic external review (the 2024 lead audit is a substantive example)
- *HUD FHEO Title VI and Fair Housing Act compliance reviews* — episodic
- *Ohio Auditor of State* — annual external financial audit
- *Cleveland City Council oversight* — episodic (the 2024 lead-safety hearing is illustrative)
- *Cleveland Department of Public Health* — ongoing EBLL investigation
- *Resident Advisory Boards and Resident Councils* — ongoing
- *Board of Commissioners monthly meetings* — ongoing
- *CALEA reaccreditation for CMHA-PD* — periodic (typically four-year cycle)

This drift-monitoring stack is comparable to GCRTA (SCBP-REG-0012) in federal-regulatory density, but with materially heavier substantive oversight directly affecting individual residents.

**8.2 — Capture risk monitoring:**
- HUD OIG and FHEO functions provide substantive capture-risk-relevant monitoring
- Ohio Auditor function provides financial-capture-risk monitoring
- UNKNOWN whether internal capture-risk monitoring (vendor concentration, contractor relationships, executive-revolving-door patterns) is a formal program

**8.3 — Audit interfaces:**
- *Proactively published:* Board meeting agendas with public comment process, annual financial statements, HUD-required public reports, Annual Plan, Five-Year Plan, ACOP, HCV Administrative Plan, lease documents, news releases. The cmha.net website hosts substantial documentation.
- *Available on request:* tenant records to the tenant; property records; some Board executive-session content excluded
- *Restricted:* individual tenant PII (Privacy Act, Fair Housing Act), PIH-EIV income data, certain personnel records, ongoing-investigation matters, CMHA-PD ongoing-investigation records
- *Not consistently available:* CMHA-PD aggregate complaint and use-of-force data; methodology details of internal practices (per 2024 OIG findings on lead-disclosure methodology gaps)

**8.4 — Adversarial exposure (R81):**
A non-insider can:
- Access HUD's published PHAS, SEMAP, and other public data on CMHA
- Read Board agendas and Annual Plan documents
- Attend Board meetings (with public comment subject to procedural rules)
- Read HUD OIG audit reports (including the 2024 lead audit)
- File public records requests
- Engage advocacy organizations (CLASH, Cleveland Tenants Organizations)
- Cannot easily obtain: aggregate CMHA-PD enforcement data; individual EBLL case records (privacy-protected); detailed contractor and partnership financial structures; vendor selection rationales
- The 2024 HUD OIG audit documents specific R81 failures (lack of documentation rendering external evaluation difficult)

**8.5 — Known structural failure modes:**
- Lead-paint hazards in aging housing stock (2024 OIG audit documents)
- Habitability gaps (mold, pest, structural) in aging stock
- Eviction patterns affecting majority-minority resident population
- Capital-funding inadequacy relative to capital needs (a national pattern affecting all PHAs)
- HCV landlord-acceptance challenges (source-of-income discrimination patterns affecting voucher holders)
- CMHA-PD use-of-force in concentrated low-income housing settings
- Federal-policy-change risk affecting funding and operational mandates
- Choice Neighborhoods displacement risk during phased redevelopments

**8.6 — Trade-secret / confidentiality declarations:**
- Category of restricted information: tenant PII, PIH-EIV income data, criminal-history records, certain personnel records, CMHA-PD ongoing-investigation records, vendor IP in some contracts
- Source of restriction: federal statute (Privacy Act, FHA, FERPA where applicable, CJIS for CMHA-PD), Ohio public-records exceptions
- Auditability mitigation: HUD OIG audits, FHEO compliance reviews, aggregate-level public reporting, Board meeting public comment, advocacy oversight
- R67 floor commitment: not explicitly declared; the 2024 HUD OIG audit documents specific R67-relevant gaps that have been or are being remediated per CMHA's stated response

---

## SECTION 9 — How does it end?

**9.1 — Estimated dismantling time:**
UNKNOWN. CMHA exists under ORC §3735.27–.50 as a political subdivision; dissolution would require state legislative action or reconstitution. Federal HUD ACC and other federal funding agreements would require transition. ASSUMPTION: 60+ months minimum for an orderly wind-down including tenant transition (10,500 public housing households plus voucher participants), HUD program transition, capital asset disposition, debt resolution, and employee transition.

**9.2 — Dismantling process:**
UNKNOWN. No public dismantling plan exists. Substantive components of a wind-down would include:
- Transition of public-housing operations to successor PHA, state agency, or asset-conversion (e.g., RAD conversion to project-based Section 8)
- Transition of HCV program administration to successor entity (HUD continuation through a different administrator)
- Resolution of HUD ACC, Capital Fund, and Choice Neighborhoods grant agreements
- Disposition of housing stock and headquarters real estate
- Resolution of bond debt
- Transition of CMHA-PD (likely to municipal police forces with consent of jurisdictions)
- Employee transition per applicable employment law and PERS obligations
- Records transfer for federal, state, and tenant-historical purposes

**9.3 — Entrenchment factors:**
- *Federal funding stream:* HUD ACC, Capital Fund, and HCV are statutorily structured for continuation; dismantling does not eliminate the federal obligation but reassigns the administering entity
- *Resident population:* 10,500 households in public housing cannot be displaced without massive disruption; voucher participants similarly need administering authority
- *Capital infrastructure:* 60+ properties countywide with significant capital invested over 90+ years
- *Bond debt and partnership obligations:* binding for decades
- *Choice Neighborhoods grants and HUD-approved Annual Plans:* binding implementation obligations
- *CMHA-PD CALEA accreditation and police-officer employment*
- *Employee pension obligations under Ohio PERS*

R61 (Anti-Entrenchment) finding: CMHA is structurally embedded in federal housing program delivery, county affordable-housing market, and resident-population dependency. Dismantling without replacement would create immediate housing crisis for tens of thousands of residents and violation of federal obligations.

**9.4 — Data disposition:**
UNKNOWN specifics. Federal records-retention requirements (HUD, FHA), Privacy Act protections, and state public records law would govern records transfer.

**9.5 — Downstream effect reversibility:**
Eviction records, voucher-termination records, CMHA-PD arrest records, and lead-exposure consequences for affected children are not retroactively reversible by CMHA action. Per R63, downstream propagation is not reversible at the agency level. Lead-exposure neurological harm is *categorically* irreversible.

**9.6 — Replacement feasibility:**
Public housing and HCV administration in Cuyahoga County would require replacement: by a successor PHA, by state assumption, by HUD direct administration, by RAD-converted project-based contracts with private partners, or by other arrangement. Federal subsidy obligations would persist regardless of administering entity.

**9.7 — Reversibility verification:**
- [ ] Verified
- [x] Not verified — no public-source documentation of a rehearsed dismantling, simulated shutdown, or partial-function-transfer drill.

---

## SECTION 10 — Authorization, renewal, and trigger declarations

**10.1 — Authorizing body:**
- State of Ohio (ORC §3735.27–.50)
- U.S. Department of Housing and Urban Development (ACC, regulatory authority, Annual Plan approval)
- Cleveland Mayor and Council, East Cleveland Mayor (Board appointments)

**10.2 — Date of current authorization:**
- CMHA established 1933 (renamed 1971)
- 1985 OPOTC sworn-police authority via Ohio HB 129
- HUD ACC continuing since federal subsidized housing inception
- Most recent Annual Plan: UNKNOWN specific date

**10.3 — Authorization expiration date:** UNKNOWN — no scheduled expiration of CMHA itself. The HUD ACC is a continuing contract reviewed periodically. Annual Plans operate on annual cycles.

**10.4 — Renewal interval:** 5 years (corresponding to HUD Five-Year Plan cycle, which is the closest formal analog to framework-style renewal). ANNOTATION: HUD Annual Plan operates yearly; Five-Year Plan operates on five-year cycle and provides substantive scope-and-strategy review. The 5-year value reflects this Five-Year Plan cycle.

**10.5 — Renewal evidence declaration:**
- [ ] Scope integrity evidence
- [ ] Harm compliance evidence
- [ ] Stop path integrity evidence
- [ ] Dependency and capture evidence
- [ ] Reversibility evidence

ANNOTATION: HUD Annual Plan, Five-Year Plan, PHAS, SEMAP, and OIG audit cycles together provide substantive evidence across most framework dimensions. A structured renewal-evidence commitment in the framework's R47 sense is not declared as CMHA's own practice but is partially compelled by federal regulation.

**10.6 — Necessity-decay acknowledgment:**
- [ ] Acknowledged — public sources do not document such an acknowledgment. ANNOTATION: the inverse pattern is documented — capital underinvestment and aging housing stock indicate capacity *degradation* rather than necessity decay. Need is not decreasing; capacity is.

**10.7 — Aggregate trigger threshold:**
- Number of triggers: 5
- Within window of: 90 days
- (SCBP-09 §II: non-consenting affected population of 55,000 falls in the 1,000–100,000 band; minimum 5 in 90 days, maximum 25 in 90 days. 5 in 90 days is the floor.)

**10.8 — Aggregate threshold justification:**
Set at the SCBP-09 minimum for the 1,000–100,000 non-consenting band. The authority affects a population that is by definition low-income with limited housing alternatives, includes child residents who did not and could not consent, and operates under recent documented federal audit findings of substantive compliance gaps in lead-safety harm protection. The low threshold gives the affected population — especially residents and their advocates — meaningful access to aggregate review.

**10.9 — Response time window:** 30 days (SCBP-09 §III default).

**10.10 — Response window justification:** the SCBP-09 default of 30 days is adopted. Federal grievance and HCV informal-hearing procedures operate on different specific timelines per case type.

---

## SECTION 11 — What does this authority commit to publishing?

**11.1 — Citizen ledger publication:**
- [x] Annually (HUD Annual Plan, audit, financial statements, PHAS/SEMAP)
- [x] Other (monthly Board meeting agendas and minutes; HUD Five-Year Plan; Board committee reports)
- [ ] Quarterly as a structured ledger

Content commitments per public-source observation:
- [x] Operating expenditures (via budget documents and audit)
- [ ] Renewal status — Annual Plan and Five-Year Plan cycles serve as functional analogs
- [x] Stop events partial: HUD OIG audit findings publicly reported; eviction filings are court records but not aggregated by CMHA; HCV informal hearings not aggregated; CMHA-PD complaints not aggregated
- [x] Structural dependency status partial: HUD funding mix in Annual Plan; vendor and contractor information at summary level in Board materials
- [x] Other: news, press releases, Board agendas

This is a comparatively strong publication baseline driven by HUD reporting requirements, comparable to GCRTA (SCBP-REG-0012).

**11.2 — Threshold change log:** Partial. Policy changes via ACOP and HCV Administrative Plan revisions go through Board approval and public comment per HUD Annual Plan process. A formal threshold change log per R08 is not documented.

**11.3 — Interpretation change log:** Partial. Board resolutions are publicly recorded. Staff-level interpretive practice is not systematically logged.

**11.4 — Renewal process visibility:** Annual Plan and Five-Year Plan processes are public and require public comment per HUD regulation. The structured renewal evidence per R47 in the framework's sense is not a declared practice but is partially compelled by HUD.

**11.5 — Stop event log:**
- [ ] Acknowledged. HUD OIG audit findings are public federal records. Individual grievance and informal-hearing outcomes are not aggregated into a single CMHA stop-event log.

---

## SECTION 12 — Honesty assertions

ANNOTATION: §12 honesty assertions are commitments by the filing authority. For this PUBLIC_SOURCES record, no checkbox is asserted, because no authority has filed the record.

**12.1 — Disclosure completeness assertion:**
- [ ] Asserted

**12.2 — Update obligation:**
- [ ] Committed

**12.3 — Discoverability acknowledgment:**
- [ ] Acknowledged

ANNOTATION: per R69 (Burden of Proof Reversal), the 2024 HUD OIG audit finding that "the Authority lacked oversight of... accurate lead-based paint disclosures... provided to prospective tenants" constitutes a documented external finding that the burden was not met for the relevant period. This is a concrete example of R69-relevant non-compliance in the public record.

**12.4 — Burden of proof acknowledgment:**
- [ ] Acknowledged

**12.5 — Anti-weaponization acknowledgment:**
- [ ] Acknowledged

---

## SECTION 13 — Submitter

```
Submitted by (full name): Third-party submitter (PUBLIC_SOURCES record produced from publicly available information)
Role / position within or relationship to the authority: Third party / civic actor (no formal relationship to the authority)
Date: 2026-05-17
Contact for follow-up: UNKNOWN
```

---

## Renewal Log

- v1 — 2026-05-17: initial PUBLIC_SOURCES record produced by third party from publicly available information. Filed under SCBP-REG-0014-CMHA per registry sequential numbering convention.

---

## Cross-references to other records

- **SCBP-REG-0005** (Shaker Heights Police Department): no direct functional relationship. Both are OPOTC-certified sworn police forces in Cuyahoga County with distinct jurisdictions (SHPD: municipal; CMHA-PD: CMHA properties).
- **SCBP-REG-0007** (Shaker Heights Department of Building & Housing): coordinate — the Cleveland-area housing regulatory environment includes both authorities. CMHA properties in Shaker Heights (if any) would be subject to Shaker housing code; UNKNOWN whether CMHA holds property in Shaker Heights.
- **SCBP-REG-0008** (Shaker Heights City School District): coordinate — children residing in CMHA housing within district boundaries attend SHCSD schools (or other public/private schools per residency); the framework's harm-impact patterns connect across these authorities.
- **SCBP-REG-0010** (Shaker Heights Architectural Board of Review): no direct functional relationship.
- **SCBP-REG-0012** (Greater Cleveland Regional Transit Authority): coordinate — CMHA residents are substantial transit-dependent users; GCRTA service decisions affect CMHA resident access to employment, healthcare, and services. The two authorities serve overlapping populations.

ANNOTATION: this is the third record in the registry covering a countywide authority rather than a Shaker-specific one. The SCBP-09 §II band differs from GCRTA (SCBP-REG-0012, which is at the 1M+ band) because CMHA's affected population (residents and participants, approximately 55,000) is smaller than GCRTA's (all county residents, approximately 1.2 million) despite both operating countywide. Geographic scope and affected population are distinct concepts in the framework.

---

**PUBLIC SOURCES ONLY** — This Mechanism Record was produced by a third party from publicly available information. It has not been reviewed, confirmed, or filed by the Cuyahoga Metropolitan Housing Authority. If the authority later files corrections to this record, the existing record will be updated in place per the authority-after-citizen rule (Part 1, step 7.5 of the AI Registration Bundle); the mechanism_id and filename will remain unchanged.
