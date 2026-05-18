---
mechanism_id: SCBP-REG-0018
mechanism_name: "Fifth Third Bank, National Association"
authority_acronym: "FITB"
status: PUBLIC_SOURCES
filed_by: third_party
domain: finance
authority_classification: both
country: US
region: OH
subregion: not_applicable
primary_postal_code: 45202
primary_address: "Fifth Third Center, 38 Fountain Square Plaza, Cincinnati, OH 45202"
primary_url: "https://www.53.com"
tax_id: "31-0854434"
registered_date: 2026-05-17
snapshot_date: 2026-05-17
last_reviewed_date: 2026-05-17
record_version: v1
authorization_date: 1858-06-17
expiration_date: UNKNOWN
renewal_interval_years: 1
funding_types:
  - private_for_profit
  - self_funded_fee_for_service
  - shareholder_capital
  - debt_capital
funding_concentration_max_pct: 100
affected_party_categories:
  - general_public
  - customers
  - employees
  - vulnerable_populations
  - non_consenting_third_parties
affected_population_estimate: 5500000
non_consenting_population_estimate: 500000
entity_size: massive
geographic_specificity: multi_state
geographic_reach: "12 states: Ohio, Alabama, Florida, Georgia, Illinois, Indiana, Kentucky, Michigan, North Carolina, South Carolina, Tennessee, West Virginia. Approximately 1,087 branches and 2,400 ATMs (plus ~54,000 fee-free network ATMs). Approximately 30 branches in Cuyahoga County. Customer base reported at approximately 5.5 million."
aggregate_threshold_count: 50
aggregate_threshold_window_days: 90
response_window_days: 30
harm_categories_declared:
  - agency_impairment
  - informational_sovereignty
  - generational_binding
algorithmic_decision_systems_used: true
dependency_count_type1: 3
dependency_count_type2: 11
dependency_count_type3: 4
capture_risk_identified: true
disclosure_completeness_assertion: false
update_obligation_committed: false
discoverability_acknowledged: false
burden_of_proof_acknowledged: false
anti_weaponization_acknowledged: false
---

**PUBLIC SOURCES ONLY** — This Mechanism Record was produced by a third party from publicly available information. It has not been reviewed, confirmed, or filed by the authority it describes. Declarations reflect what could be determined from public sources as of the snapshot date. UNKNOWN fields indicate information that could not be reasonably determined from public sources.

ANNOTATION ON AUTHORITY CHARACTER: this is the first record in the registry for a **for-profit publicly-traded financial institution** rather than a governmental, nonprofit-governmental, or nonprofit-tax-exempt authority. The framework applies to private for-profit authorities exercising power over non-consenting affected parties, but several structural features differ from prior records:
- Owners are shareholders rather than the public or charitable beneficiaries
- Fiduciary duties run to shareholders alongside regulatory obligations
- Stop paths are principally federal regulatory (OCC, FDIC, Federal Reserve, CFPB) rather than electoral or accreditation-based
- Coercive ceiling operates through contract, lien, collection, credit-reporting, and account-control authority rather than state coercion
- Many actions affecting customers are bilateral contractual but operate under severe information asymmetry and structural market power
- The framework's R03 (Institutional Capture Prohibition), R66 (Anti-Proxy), and R74 (Proxy Equivalence Expansion) standards apply with heightened force given documented repeat enforcement actions (per 2024 CFPB characterization of the authority as a "repeat offender")

---

# Mechanism Record — Fifth Third Bank, National Association

## SECTION 1 — What is this authority?

**1.1 — Mechanism name:** Fifth Third Bank, National Association (the federally chartered banking subsidiary of Fifth Third Bancorp, a publicly traded bank holding company; NASDAQ: FITB). Founded 1858 as Bank of the Ohio Valley in Cincinnati, Ohio; subsequent mergers produced the "Fifth Third" name. The combined enterprise is among the 15 largest U.S. bank holding companies with approximately $214 billion in total assets per 2023 reporting.

**1.2 — Functional description:**
The authority is a national bank operating through four principal business lines per public sources:
- *Commercial Banking* — commercial and industrial lending, commercial real estate, treasury management, capital markets services for mid-sized and large businesses
- *Consumer and Small Business Banking* (Branch Banking) — deposit accounts (checking, savings, money market, CDs), consumer lending, mortgage origination and servicing, small business banking, debit cards, ATM access
- *Consumer Lending* — residential mortgage origination and servicing; home equity loans and lines of credit; credit cards; indirect auto lending; home improvement and solar energy installation loans through contractors and installers
- *Wealth and Asset Management* — wealth planning, investment management, trust services, estate services, retail brokerage, institutional advisory

Operations:
- Approximately 1,087 branches and 2,400 ATMs across 12 states (Ohio, Alabama, Florida, Georgia, Illinois, Indiana, Kentucky, Michigan, North Carolina, South Carolina, Tennessee, West Virginia)
- Approximately 30 branches in Cuyahoga County, Ohio (the geographic anchor of this registry)
- Customer base of approximately 5.5 million per company-reported figures
- Approximately 20,000+ employees
- Approximately 54,000 fee-free network ATMs through partnerships
- Tower headquarters: Fifth Third Center, 38 Fountain Square Plaza, Cincinnati

The authority issues binding determinations including: account-opening and account-closure decisions; credit-extension decisions (loans, credit cards, mortgages); credit limit determinations; interest rate and fee determinations; overdraft and NSF determinations; deposit hold determinations; account freezes (including for legal process, suspected fraud, anti-money-laundering review); mortgage modification and foreclosure decisions; auto loan repossession decisions; collection actions including lawsuits, wage garnishment proceedings, and judgment enforcement; credit bureau reporting that propagates to credit scores affecting future credit access, employment, housing, and insurance; reports to Currency Transaction Reporting (CTR) and Suspicious Activity Reporting (SAR) regimes; account-history reporting to ChexSystems and similar systems that affect customers' ability to open accounts at other institutions; trust and fiduciary determinations affecting beneficiaries; investment advisory and fiduciary decisions; employment decisions for approximately 20,000+ employees.

**1.3 — Authority classification:**
- [ ] Direct only
- [ ] Indirect only
- [x] Both — direct (binding account, credit, lien, and collection determinations affecting customers; binding employment determinations) and indirect (credit bureau reporting, ChexSystems reporting, CTR/SAR reporting, and market signals that materially influence decisions by other actors including landlords, employers, insurers, other lenders, and government agencies; influence on regional credit availability and small business viability)

**1.4 — Domain:**
- [ ] Government
- [ ] Economic
- [ ] Technology
- [ ] Infrastructure
- [ ] Data / Information
- [ ] Education
- [ ] Healthcare
- [ ] Cultural / Religious
- [ ] Voluntary association
- [x] Other: finance

ANNOTATION: the bundle's enumerated domain values include "finance" (per the values list). Banking sits at the intersection of finance, information governance infrastructure, and economic authority. YAML uses "finance" as the most specific.

**1.5 — Statutory or constitutional basis:**
- *Charter:* National Bank Act (12 U.S.C. §1 et seq.); chartered and supervised by Office of the Comptroller of the Currency (OCC)
- *Holding company:* Bank Holding Company Act (12 U.S.C. §1841 et seq.); Federal Reserve Board supervision of Fifth Third Bancorp
- *Deposit insurance:* Federal Deposit Insurance Corporation (FDIC) insurance per 12 U.S.C. §1811 et seq.
- *Public company:* Securities Exchange Act of 1934; NASDAQ listing standards; Sarbanes-Oxley Act (15 U.S.C. §7201 et seq.); Dodd-Frank Wall Street Reform and Consumer Protection Act
- *Consumer financial protection:* Consumer Financial Protection Act (12 U.S.C. §5481 et seq.); Truth in Lending Act (Regulation Z); Truth in Savings Act (Regulation DD); Equal Credit Opportunity Act (Regulation B); Fair Credit Reporting Act (FCRA); Fair Debt Collection Practices Act (FDCPA); Real Estate Settlement Procedures Act (RESPA, Regulation X); Electronic Fund Transfer Act (Regulation E); Home Mortgage Disclosure Act (HMDA); Community Reinvestment Act (CRA); Servicemembers Civil Relief Act (SCRA); Military Lending Act
- *Anti-discrimination:* Fair Housing Act (42 U.S.C. §3601 et seq.); Equal Credit Opportunity Act; Section 1981 of the Civil Rights Act of 1866
- *Bank Secrecy Act / Anti-Money Laundering:* Bank Secrecy Act (31 U.S.C. §5311 et seq.); USA PATRIOT Act; OFAC sanctions regulations (31 CFR Chapter V); Customer Identification Program (CIP) requirements
- *Privacy:* Gramm-Leach-Bliley Act (15 U.S.C. §6801 et seq.); state privacy law including California Consumer Privacy Act and Ohio data-breach notification
- *Capital and prudential:* Basel III as implemented in U.S. regulation; Dodd-Frank stress testing (DFAST/CCAR); OCC capital rules
- *Investment advisory:* Investment Advisers Act of 1940 for certain subsidiaries; SEC and FINRA regulation of broker-dealer affiliate (Fifth Third Securities, Inc.); ERISA for retirement plan fiduciary services
- *State-specific:* state usury laws (preempted in many cases by National Bank Act); state foreclosure law; state UCC for secured transactions; Ohio nonprofit, charitable, and Attorney General oversight for some activities
- *Corporate governance:* Delaware General Corporation Law (or state of incorporation); fiduciary duties to shareholders under state corporate law

ANNOTATION: this regulatory stack is the densest of any record in this registry. National banks operate under federal supervision by multiple agencies simultaneously (OCC primary; FDIC for deposit insurance; Federal Reserve for holding company; CFPB for consumer protection; SEC for securities matters; FinCEN for BSA/AML), with state regulatory residual authority for specific activities.

---

## SECTION 2 — Who can this authority act upon?

**2.1 — Affected party categories:**
- [x] General public (no opt-in required to be affected) — anyone whose name appears in a financial transaction processed by Fifth Third, anyone subject to BSA/AML reporting based on contact with a Fifth Third customer, anyone whose creditworthiness is assessed indirectly through Fifth Third's credit bureau reporting, anyone affected by Fifth Third's investment advisory or trust decisions on a connected matter
- [x] Residents of defined geographic area: residents of 12 states within branch footprint; broader U.S. residents through online banking, credit card, mortgage, and other channels
- [ ] Members
- [x] Customers / voluntary service users: approximately 5.5 million customers; including depositors, borrowers, credit card holders, mortgage holders, auto loan customers, small business banking customers, wealth management clients
- [x] Employees / workers: approximately 20,000+ employees
- [ ] Students (except as a subset)
- [ ] Patients
- [x] Regulated industry participants: depository institutions doing business with Fifth Third through correspondent banking; merchants accepting Fifth Third credit cards; mortgage servicing partners; auto dealers in indirect auto-lending relationships; solar installers and home-improvement contractors in installer-loan programs; investment advisory clients
- [ ] Criminal justice involved individuals (except as subjects of legal process holds and BSA/AML reports)
- [x] Children / minors: minor account holders (custodial accounts under UTMA/UGMA); minor beneficiaries of trust services
- [x] Vulnerable populations: elderly customers (subject to elder financial exploitation risks; protected under EFPRA and state elder abuse statutes); customers with cognitive impairments; customers with limited English proficiency; servicemembers (SCRA, MLA protections); customers with disabilities (ADA accommodation duties); low-income customers; customers in financial distress; estate beneficiaries; minor children of customers
- [ ] Future generations (except as inheritors of multi-generational trust arrangements, credit-history propagation, and family-financial consequences)
- [x] Non-consenting third parties: parties named in legal-process holds (garnishment, levy, attachment) by court order targeting a Fifth Third customer; co-signers on customer loans; joint account holders affected by single-account-holder actions; estate beneficiaries; children of customers whose financial decisions affect family stability; persons named in CTR/SAR reports based on transactions with Fifth Third customers; persons whose information is shared with credit bureaus through joint or co-signed accounts; communities affected by branch closure or lending pattern decisions

**2.2 — Approximate number of people directly affected:**
- Customers (reported): approximately 5.5 million
- Employees: approximately 20,000+
- Indirect parties (CTR/SAR reportable counterparties; credit bureau report subjects through joint accounts; merchants accepting Fifth Third cards; legal process subjects): UNKNOWN aggregate count; substantial
- Total directly affected: approximately 5.5 million customers as the core directly affected population

ANNOTATION: this is the largest affected-population estimate in any record produced in this registry. The 5.5 million customer base spans 12 states and includes consumer and business customers across deposit, loan, mortgage, credit card, auto, and wealth segments.

**2.3 — Non-consenting portion:**
The framework's "voluntary-but-stuck" test (§2.3) applies in distinctive ways for banking:
- *Bank customers are nominally consenting* (they opened accounts) but operate under information asymmetry, complex adhesion contracts with unilateral amendment clauses, mandatory arbitration provisions, and substantive switching costs (direct deposits, automatic payments, recurring transactions, mortgage servicing transfer friction, credit-relationship preservation)
- *The 2024 CFPB enforcement action found that ~35,000 customers had accounts opened in their names without their authorization* during 2010–2016 — these customers were categorically non-consenting (they did not even nominally consent to the accounts at issue)
- *The 2024 CFPB enforcement also found ~1,000 customers had vehicles repossessed* after being charged for unnecessary and duplicative collateral protection insurance coverage — these customers were non-consenting to the imposed insurance and to the resulting downstream consequences
- *Credit bureau reporting* affects customers whose negative items propagate through credit-scoring systems for 7 years or longer, with derivative effects on housing access, employment, insurance pricing, utility deposits, and other downstream financial decisions
- *ChexSystems and similar account-history reporting* can result in customers being denied accounts at other banks for up to 5 years
- *CTR/SAR reporting* under BSA/AML can attach reputational and investigative consequences to named persons without their knowledge or opportunity to respond
- *Legal-process holds* (garnishment, levy, attachment) are imposed on customers based on judgments obtained without customer participation in some cases
- *Mortgage foreclosure* in some cases removes customers from their homes after extended processes with substantial procedural complexity
- *Auto repossession* — particularly the documented 2011–2020 wrongful-repossession pattern affecting approximately 1,000 customers per the 2024 CFPB finding — is functionally non-consenting at the moment of repossession
- *Minor children, elder dependents, and disabled family members of customers* affected by customer-financial-decisions are non-consenting third parties

For SCBP-09 §II purposes, the non-consenting population is approximately 500,000, reflecting:
- Customers materially affected by binding adverse determinations (denials, account closures, fee assessments beyond contract, collection actions, foreclosure, repossession, credit bureau adverse items) per year — ASSUMPTION: 5–10% of customer base annually
- Family members and joint account holders affected by such determinations
- Third parties affected by legal process holds and reporting
- The 35,000 customers identified in the 2024 CFPB action as having unauthorized accounts opened plus 1,000 with vehicle repossessions are a discrete documented non-consenting cohort

This places the authority in the SCBP-09 §II 100,000–1,000,000 band, with threshold range 10–50 in 90 days.

ANNOTATION: this non-consenting characterization is substantive. Per the bundle's R26 (Non-Participant Harm Floor), the framework imposes stricter harm tolerances for non-consenting populations. The CFPB's 2024 characterization of Fifth Third as a "repeat offender" (citing the 2015 CFPB actions on discriminatory auto-loan pricing and illegal credit card practices, plus the 2024 enforcement) is structurally significant under R69 (Burden of Proof Reversal) — the authority has documented external findings of substantive consumer harm across multiple years.

**2.4 — Vulnerable population specifics:**
- [x] Children (under age of majority): minor account holders (UTMA/UGMA); minor beneficiaries of trusts and estate plans
- [ ] Patients during medical care
- [ ] Detained or confined persons
- [x] Persons in coercive economic relationships: borrowers under default conditions; customers in financial distress; small business owners with personal guarantees; mortgage borrowers facing foreclosure; co-signers
- [x] Persons unable to advocate for themselves due to disability, incapacity, or circumstance: elderly customers (subject to documented elder financial exploitation patterns industry-wide); customers with cognitive impairments; customers in active financial-distress crisis; customers without English proficiency; deceased customers' estates and beneficiaries; customers represented by guardians or conservators; servicemembers deployed and unable to actively manage finances

Protective measures per public sources include: SCRA and MLA protections; FCRA dispute rights; FDCPA collection limits; CFPB and OCC consumer complaint channels; Federal Reserve Consumer Help; ChexSystems dispute procedures; Truth in Lending and Truth in Savings disclosures; HMDA reporting on mortgage lending patterns; CRA examination on community reinvestment; ECOA on credit decisions; state attorney general consumer protection authority.

ANNOTATION: per the bundle's Part 3 §4 diagnostic prompt note on authorized harm — banking authorities by design involve certain forms of harm (interest charges, fees, default consequences, collection on legitimate debts). §4 thresholds below distinguish *authorized* contractual outcomes from *excess* harm (charges for products customers did not consent to; discriminatory pricing; wrongful repossession; account opening without consent).

---

## SECTION 3 — What can it do, and what can it not do?

**3.1 — Geographic reach:**
- [ ] Single municipality
- [ ] Multi-municipality
- [ ] Single county/parish
- [ ] Multi-county
- [ ] Single state/province
- [x] Multi-state/multi-province: 12 states for branch footprint; nationwide for credit card, online banking, and other channels
- [ ] Single nation
- [ ] Multi-national
- [ ] Global

ANNOTATION: while branch footprint is 12 states, the authority's reach via credit card issuance, mortgage origination through national channels, and online banking is effectively nationwide. Customer base of 5.5 million extends across the U.S. The 16 counties of UH (SCBP-REG-0016) is a tighter geographic concept; banking authority is broader through electronic channels.

**3.2 — Coercive ceiling:**
The strongest actions available to the authority include:
- *Account closure and account-history reporting to ChexSystems and similar systems* — can result in customer inability to open accounts at any other bank for up to 5 years; effectively functions as a "private banking ban"
- *Credit bureau adverse reporting* — propagates for 7 years on most adverse items; 10 years for bankruptcy; affects future credit, employment, housing, insurance
- *CTR and SAR reporting* — federal reports attaching investigative and reputational consequences; subjects often unaware of reports
- *Account freezes and legal-process holds* — funds inaccessible during freeze; subject must work through legal process to release
- *Mortgage foreclosure* — judicial or non-judicial process resulting in loss of home
- *Auto repossession* — physical seizure of vehicle, sometimes through self-help repossession by contracted agents
- *Wage garnishment, levy, attachment* — collection actions reaching customer funds at other institutions and wages at employers
- *Civil lawsuits for collection* — judgments enforceable through full state legal process
- *Credit limit reduction or revocation* — unilateral changes affecting customer credit access
- *Interest rate changes* — unilateral changes under credit card agreements and variable-rate products
- *Fee assessment* — overdraft, NSF, account maintenance, ATM, foreign transaction, and other fees
- *Mandatory arbitration enforcement* — preventing customer access to court for most disputes
- *Employment termination and discipline* — affecting 20,000+ employees
- *Vendor and contractor terminations*
- *Lending decisions that exclude individuals, businesses, or geographies from credit access* — collectively shape regional economic development patterns
- *Branch closure decisions* — affecting community access, particularly in lower-income or majority-minority communities (CRA-relevant)
- *Investment advisory and fiduciary decisions affecting client portfolios* — including trust administration decisions
- *Customer information sharing with affiliates and third parties* under Gramm-Leach-Bliley Act
- *Information sharing with law enforcement* under BSA/AML, USA PATRIOT Act, and judicial process

ANNOTATION: financial authority is distinctive in the framework because much of what would be coercive in other settings is *authorized by customer contract and by federal regulatory authority*. The framework recognizes this through the §4 authorized-versus-excess distinction. The coercive ceiling above reflects structurally significant authority; the routine exercise of contractual banking authority within consent and regulation is not enumerated. The 2024 CFPB findings specifically address conduct that *exceeded* authorized contractual authority (accounts opened without consent; insurance imposed beyond contractual permission).

**3.3 — Resource ceiling:**
- Total assets: approximately $214.6 billion (2023 reporting)
- 2022 revenue: approximately $5.6 billion
- 2022 operating income: approximately $3.1 billion
- 2023 net income: approximately $2.2 billion
- Employees: approximately 20,000+
- Branches: approximately 1,087
- ATMs: approximately 2,400 directly operated; 54,000+ fee-free network
- Customers: approximately 5.5 million
- Real estate holdings: substantial; including Fifth Third Center towers in major metropolitan areas
- Data systems: comprehensive banking systems including core deposit systems; loan origination systems; consumer credit decisioning systems; mortgage servicing systems; fraud detection and BSA/AML monitoring systems; investment management platforms; customer relationship management; ATM and branch operations technology
- Capital structure: substantial public equity float (S&P 500 component, NASDAQ-listed); senior and subordinated debt issuances; deposit liabilities providing primary funding
- Subsidiaries and affiliates: Fifth Third Securities, Inc. (broker-dealer); Fifth Third Insurance Services; wealth management entities; commercial finance subsidiaries; mortgage subsidiaries

**3.4 — Explicit exclusions — what this authority may NOT do:**
- [x] Geographic exclusions: authority operates principally within U.S.; cannot establish foreign branches without separate regulatory approval
- [x] Action exclusions: cannot discriminate on protected-class bases under ECOA, Fair Housing Act, Section 1981; cannot engage in unfair, deceptive, or abusive acts or practices (UDAAP) under CFPA; cannot violate Truth in Lending, Truth in Savings, FCRA, FDCPA, RESPA, EFTA, HMDA, SCRA, MLA; cannot engage in usury beyond regulatory limits (national bank federal preemption complicates state-law usury claims); cannot retain customer funds without legal authority; cannot impose fees inconsistent with disclosures; cannot impose unauthorized account products (per 2024 CFPB consent order and ban on sales goals incentivizing unauthorized accounts)
- [x] Data exclusions: GLBA constrains use and disclosure of nonpublic personal financial information; FCRA constrains use and reporting of credit information; state privacy laws apply
- [x] Procedural exclusions: cannot foreclose without legally required notice and process; cannot repossess in breach of peace; cannot collect through illegal means; cannot retaliate against customers who file regulatory complaints
- [ ] Temporal exclusions: not applicable (24-hour digital operations)
- [x] Other exclusions: capital, liquidity, and risk-management requirements under prudential regulation; BSA/AML compliance requirements; conditional charter requirements; community reinvestment obligations under CRA; cannot operate without OCC supervision and FDIC deposit insurance for the regulated activities

**3.5 — Indirect influence boundaries:**
Per §1.3 (both classifications), indirect dimensions include:
- *Credit bureau reporting* propagates customer creditworthiness data across the financial system, shaping decisions by other lenders, landlords, employers, insurers, utility companies, and government agencies
- *ChexSystems and similar account-history reporting* propagates banking-relationship data
- *CTR and SAR reporting* propagates AML-relevant data into federal investigative systems
- *Credit decisioning patterns* in aggregate shape regional credit availability and economic development
- *Branch location and closure decisions* shape community banking access (CRA-relevant)
- *Mortgage lending patterns* shape homeownership access and housing markets (HMDA reportable)
- *Small business lending patterns* shape regional small business viability
- *Investment advisory recommendations* shape client portfolio outcomes with downstream wealth-distribution effects
- *Wealth management decisions* across institutional clients shape pension and retirement outcomes for beneficiaries
- *Trust administration decisions* shape multi-generational wealth transfer
- *Industry-level policy advocacy* through American Bankers Association, Ohio Bankers League, Consumer Bankers Association, and similar industry bodies

**3.6 — Anti-proxy declaration:**
UNKNOWN. Fifth Third's ECOA compliance, Fair Housing Act compliance, CRA examination ratings, and HMDA reporting addresses certain disparate-impact considerations. Fifth Third's annual CRA Public Evaluation provides external assessment of community reinvestment performance.

No explicit anti-proxy declaration covering, for example, the use of ZIP-code-based pricing as a proxy for excluded considerations, the use of overdraft-fee patterns as proxies for distinguishing customers by income, the use of branch-closure criteria as proxies for community-level resource allocation, or the use of small-business-lending criteria as proxies for excluded considerations, was located in public sources.

ANNOTATION: the 2015 CFPB action specifically found that Fifth Third's discretionary auto loan pricing through dealer markups had a disparate impact on Black and Hispanic borrowers, resulting in $18 million in remediation. The 2024 CFPB action did not turn on explicit anti-proxy questions but did identify a sales-incentive structure that produced systemic harm. The framework's R66 (Anti-Proxy) and R74 (Proxy Equivalence Expansion) standards apply. Public sources document Fifth Third's response framings (some findings disputed, others addressed through voluntary discontinuation) but do not document a numerical anti-proxy threshold within Fifth Third's own commitments.

---

## SECTION 4 — What harms can it cause?

ANNOTATION (per bundle Part 3 §4 diagnostic prompt): for banking authorities, the framework distinguishes *authorized* contractual outcomes (interest charges per disclosed terms, fees per disclosed terms, default consequences on legitimately contracted debts, collection on judgments) from *excess* harm (charges for products customers did not consent to; pricing patterns producing protected-class disparate impact; wrongful repossession; unauthorized account opening; UDAAP violations; data breach; account-control abuse). Thresholds below target excess harm, not authorized contractual outcomes.

**4.1 — Bodily harm threshold:**
- [x] Not applicable as a primary direct harm category. Banking authorities do not directly inflict bodily harm. Indirect bodily-harm pathways exist (financial-distress mental health consequences; foreclosure-related health impacts; eviction following foreclosure with downstream health impacts; intimate-partner-violence consequences when account control is weaponized) but these are framework-distinct from direct bodily harm. UNKNOWN whether Fifth Third has declared specific protocols on account-control-and-IPV concerns.

**4.2 — Agency impairment threshold:**
Threshold: not explicitly declared as a measurable public condition. Substantive agency-impairment vectors:
- *Account closure and ChexSystems reporting* — effectively excludes customer from banking system access
- *Account freezes and legal-process holds* — prevents customer access to funds during freeze
- *Credit denial and adverse credit reporting* — restricts customer's ability to obtain future credit
- *Mandatory arbitration clauses* — limit customer access to courts for most disputes
- *Foreclosure and repossession* — remove customer property and physical access to that property
- *Sales-practices misconduct including unauthorized account opening* (2010–2016 pattern per 2024 CFPB finding) — opened accounts in customers' names without consent, impairing customer information control and possibly damaging credit
- *Forced insurance products* (2011–2020 collateral protection insurance pattern per 2024 CFPB finding) — imposed products customers did not authorize, resulting in fees, repossession risk, and downstream consequences
- *Discriminatory pricing patterns* (2015 CFPB finding on auto loan pricing) — imposed higher costs on Black and Hispanic borrowers compared to similarly situated non-Hispanic White borrowers
- *Overdraft and NSF fee patterns* — particularly when triggered by re-ordered transactions or transactions over $5 — disproportionately affect low-balance customers
- *Cross-sell sales goals incentivizing employee misconduct* — the 2024 CFPB order bans sales goals that incentivize unauthorized account opening
- *Mortgage servicing errors* — misapplied payments, force-placed insurance, foreclosure errors

A measurable threshold candidate: "Annual unauthorized-account opening incidents exceeding zero triggers immediate review" — the framework treats zero as the appropriate floor given that opening an account without consent is categorically outside contractual authority. Other candidates: "Annual rate of overdraft fees per customer in any product line exceeding peer-benchmark by X% triggers review"; "Annual rate of consumer-finance complaints to CFPB per 100,000 customers exceeding peer-benchmark triggers review."

ANNOTATION: this is the central harm category for banking authorities. The 2024 CFPB findings document substantive agency-impairment patterns spanning 2010–2020.

**4.3 — Ecological damage threshold:**
- [x] Not applicable as a primary harm category. Banks have operational footprint (energy use in data centers and branches; paper consumption; HVAC) but this is regulated through environmental statutes rather than Fifth Third-specific. Climate-change-related transition risk and credit exposure to fossil-fuel and high-emission industries are framework-relevant indirect vectors. UNKNOWN whether Fifth Third has declared specific environmental thresholds; Fifth Third's solar-energy installation loan program (per public sources) is a positive disclosure in this dimension.

**4.4 — Generational binding threshold:**
Threshold: not explicitly declared. Substantive generational-binding vectors:
- *Credit history propagation* — adverse credit items propagate for 7+ years; bankruptcy filings for 10 years; collections, judgments, and tax liens for substantial periods. Multi-generational effects accrue when adverse history limits parental wealth-building affecting children's economic opportunities.
- *Foreclosure consequences* — loss of home equity, displacement, neighborhood and school disruption for children
- *Auto repossession consequences* — loss of transportation affecting employment, school access, healthcare access
- *Trust administration decisions* — multi-generational wealth transfer outcomes
- *Estate administration outcomes* — multi-generational consequences
- *High-cost lending patterns concentrated in specific communities* (when documented) — multi-generational wealth-distribution consequences in affected communities
- *Discriminatory pricing patterns* — multi-generational consequences on community wealth (the 2015 CFPB finding on auto loan pricing affecting Black and Hispanic borrowers is a discrete documented instance with multi-generational implications for affected families)

A measurable threshold candidate: "Annual disparate-impact findings under ECOA, Fair Housing Act, or HMDA fair lending analyses triggering remediation exceeding zero triggers structural review."

**4.5 — Communicative suppression threshold:**
Threshold: not explicitly declared. Substantive communicative-suppression vectors:
- *Mandatory arbitration clauses with class-action waivers* — limit collective customer voice in dispute resolution
- *Non-disparagement clauses* in settlement agreements — limit former employee and customer ability to discuss past harms
- *Confidentiality agreements* in employment contexts — limit employee ability to discuss internal concerns publicly
- *Trade secret claims* — limit external scrutiny of certain practices
- *Litigation-management practices including motions for protective orders* — limit document disclosure in disputes

ANNOTATION: bank customer mandatory arbitration is a substantive structural feature affecting framework analysis. The CFPB attempted to ban mandatory arbitration in financial services contracts via a 2017 rule that was rescinded by Congress under the Congressional Review Act in 2017. UH (SCBP-REG-0016) had a smaller communicative-suppression surface; Fifth Third's is substantially larger.

**4.6 — Informational sovereignty threshold:**
Threshold: not explicitly declared. Substantive informational-sovereignty vectors:
- *Comprehensive financial transaction data* on customers — among the most sensitive financial data routinely collected
- *Credit bureau reporting* propagating customer data through the financial system
- *ChexSystems and account-history reporting*
- *CTR and SAR reporting* including identifying customer identities, transactions, counterparties
- *Affiliate data sharing* under Gramm-Leach-Bliley Act
- *Marketing data sharing* under GLBA (with opt-out rights for certain categories)
- *Customer behavioral data* including online banking, mobile banking, ATM usage patterns
- *Subpoenas and legal process compliance* releasing customer data to law enforcement and litigants
- *Data breach risk* — banking data breaches expose extensive PII and financial data; substantial industry record of breaches at peer institutions

A measurable threshold candidate: "Reportable data breaches exceeding zero per year triggers immediate review and public disclosure beyond regulatory minimum."

**4.7 — Additional harm thresholds:**
*Financial harm.* The most central harm category for banking. Fees, interest charges, and credit consequences within contract are authorized. Excess harm includes UDAAP violations, fees beyond disclosure, discriminatory pricing, unauthorized products, and wrongful collection.

A measurable threshold candidate: "Annual CFPB consumer complaint volume per 100,000 customers exceeding peer-benchmark by X% triggers review" and "annual remediation payments to customers for UDAAP, ECOA, or FCRA violations exceeding $Y triggers structural review."

*Disparate-impact community harm.* Branch closure decisions, lending concentration patterns, and CRA-rated lending decisions shape regional economic outcomes. CRA Public Evaluations provide external assessment; HMDA reporting provides public data on mortgage lending patterns. The 2015 CFPB finding on discriminatory auto loan pricing is documented disparate-impact.

A measurable threshold candidate: "CRA rating below 'Outstanding' in any examination triggers internal review; rating of 'Needs to Improve' or below triggers structural review of community reinvestment practices."

*Workforce harm.* Sales-incentive structures that incentivize employee misconduct (per the 2024 CFPB ban on such structures at Fifth Third) caused harm to both customers and the affected employees, some of whom per public sources were fired if they could not meet sales goals. Workforce harm vectors include sales pressure, mandatory arbitration of employment disputes, non-compete agreements, and burnout.

**4.8 — Threshold change-log commitment:**
- [ ] Yes — committed
- [ ] Cannot commit
- [x] UNKNOWN — Fifth Third publishes annual reports, proxy statements, 10-K and 10-Q SEC filings, CRA Public Evaluations, HMDA data, and call reports filed with the OCC and FDIC. These provide partial change-log mechanisms. A formal threshold change-log commitment per R08 is not explicitly declared.

---

## SECTION 5 — What stops it?

**STOP PATH 1 — Federal Banking Regulators (OCC, Federal Reserve, FDIC, CFPB, FinCEN)**
- Who can activate it: Office of the Comptroller of the Currency (primary federal regulator for national bank); Federal Reserve Board (holding company supervisor); FDIC (deposit insurance); Consumer Financial Protection Bureau (consumer protection enforcement); Financial Crimes Enforcement Network (BSA/AML); Office of Foreign Assets Control (sanctions)
- Trigger condition: examination findings; consumer complaints; whistleblower reports; supervisory ratings (CAMELS, MRA/MRIA); CRA examinations; HMDA analyses; UDAAP determinations
- What "stopped" means: cease and desist orders; consent orders; civil monetary penalties; restitution orders; conditions on growth or activities; capital requirements; restrictions on dividends, executive compensation, or acquisitions; ultimate authority to revoke charter or terminate deposit insurance (functionally existential for the bank)
- Independence justification: federal regulators operate outside Fifth Third structure with statutory independence
- Post-stop review process and timeline: examination cycle typically annual or more frequent; consent orders typically multi-year compliance periods; the 2015 and 2024 CFPB actions document concrete activation of this stop path

ANNOTATION: this is the strongest stop-path category. CFPB's 2024 characterization of Fifth Third as a "repeat offender" reflects multiple activation cycles. CFPB has been subject to substantial federal policy contestation; its enforcement posture has varied across administrations.

**STOP PATH 2 — State Attorneys General, State Regulators, and Civil Litigation**
- Who can activate it: state attorneys general (consumer protection authority); state banking regulators (limited for national banks due to federal preemption but residual for some matters); state insurance regulators (for insurance affiliate activities); state securities regulators; private plaintiffs through individual and class action litigation (constrained by mandatory arbitration clauses)
- Trigger condition: state consumer protection investigations; UDAP violations; private litigation
- What "stopped" means: state enforcement actions; civil judgments; consent decrees with state authorities; private settlement
- Independence justification: state authorities operate outside Fifth Third structure; private plaintiffs are independent
- Post-stop review process and timeline: variable

**STOP PATH 3 — SEC, FINRA, Shareholders, Media, and Whistleblowers**
- Who can activate it: Securities and Exchange Commission (10b-5 enforcement, disclosure violations, accounting issues); FINRA (broker-dealer affiliate); shareholders through proxy votes, derivative suits, and Securities Class Actions; financial media (Reuters, Bloomberg, Wall Street Journal, Cincinnati Business Courier, Banking Dive, Compliance Week); CFPB whistleblower program; SEC whistleblower program; OSHA whistleblower protection; ratings agencies (Moody's, S&P, Fitch, DBRS Morningstar); short-sellers and activist investors
- Trigger condition: variable
- What "stopped" means: SEC enforcement; reputational consequences affecting stock price; shareholder pressure on board and management; credit rating downgrade affecting cost of capital; activist investor pressure on strategic decisions
- Independence justification: SEC, FINRA, shareholders, media, ratings agencies operate outside Fifth Third structure
- Post-stop review process and timeline: variable

ANNOTATION: shareholder stop-path is distinctive for for-profit publicly-traded authorities. The framework recognizes shareholder action as a stop path but notes that shareholder interests do not perfectly align with affected-party interests. Shareholders may favor maximization of returns even when this conflicts with affected-party welfare. R03 (Institutional Capture Prohibition) addresses this misalignment risk.

**5.4 — Penalty for activating stop:**
- [x] Confirmed — federal protections against retaliation include CFPA whistleblower protections; Dodd-Frank whistleblower protections; SEC whistleblower protections; OSHA whistleblower protections; FCRA dispute protections; ECOA anti-retaliation. No formal customer-side penalty for filing CFPB, OCC, state AG, or other regulatory complaints.

ANNOTATION: informal penalties — account closure following dispute filing; aggressive collection of disputed items; mandatory arbitration enforcement; credit-rating consequences for filing customers — are documented general risks in banking literature. Whether these patterns occur at Fifth Third specifically is UNKNOWN.

**5.5 — Stop-path independence verification:**
- [x] Yes — federal regulators, state authorities, SEC, FINRA, shareholders, courts, and media can act without Fifth Third cooperation. The 2015 and 2024 CFPB enforcement actions are concrete evidence of independent stop-path activation.

**5.6 — Civic trigger acknowledgment:**
- [ ] Not applicable — this Mechanism Record is third-party-produced.

---

## SECTION 6 — What does it depend on?

**6.1 — Type 1 dependencies (operational extensions acting under this authority):**

*Branch and operations employees (~20,000+)*
- What they do: customer service, account opening, lending decisions, branch management, operations
- Contractual relationship: employment; some union representation in certain operations classifications (UNKNOWN specifics)
- Compensation structure: salary; some sales-incentive structures historically (the 2024 CFPB consent order banned sales goals incentivizing unauthorized account opening; current compensation structure post-consent-order UNKNOWN beyond the consent terms)

*Independent contractors and vendors*
- What they do: technology services, marketing, collections agencies, repossession agents, legal services, mortgage servicing partners, audit firms, security services
- Contractual relationship: vendor contracts
- Compensation structure: per contract

*Indirect lending channels (auto dealers; home-improvement and solar installers)*
- What they do: originate loans on Fifth Third behalf at point of sale; some discretion on pricing within Fifth Third parameters (the 2015 CFPB finding on auto-dealer markup-discretion was specifically about this dependency)
- Contractual relationship: dealer agreements; installer-loan agreements
- Compensation structure: typically dealer reserve or installer compensation as a percentage of loan or markup spread

ANNOTATION: the indirect lending dependency was central to the 2015 CFPB action. Per R64 (External Circumvention), Fifth Third operationalized dealer discretion in pricing, and the resulting pricing patterns produced disparate impact on Black and Hispanic borrowers. The framework treats this as a structural Type 1 dependency vulnerability.

**6.2 — Type 2 dependencies (independent authorities with structural relationship):**

- *Office of the Comptroller of the Currency (OCC)* — upstream: chartering, primary federal supervision, examination, enforcement
- *Federal Reserve Board* — upstream: bank holding company supervision; monetary policy affecting funding costs; payment systems access; emergency liquidity through discount window
- *Federal Deposit Insurance Corporation (FDIC)* — upstream: deposit insurance; resolution authority in case of failure
- *Consumer Financial Protection Bureau (CFPB)* — upstream: consumer protection examination, supervision, enforcement (the 2015 and 2024 enforcement actions are direct activations)
- *Financial Crimes Enforcement Network (FinCEN)* — upstream: BSA/AML reporting infrastructure and rule-making
- *Securities and Exchange Commission (SEC)* — upstream: public-company disclosure regulation; enforcement
- *Internal Revenue Service* — upstream: tax administration; 1099 and other information reporting requirements
- *Federal Reserve / OCC / FDIC joint stress testing (DFAST/CCAR)* — upstream: capital planning and stress testing requirements
- *NASDAQ* — coordinate: listing standards
- *FINRA* — upstream: broker-dealer affiliate supervision
- *Federal Housing Finance Agency, Fannie Mae, Freddie Mac, Ginnie Mae* — coordinate: mortgage securitization market participation
- *State attorneys general and state regulators* — upstream: residual state authority

**6.3 — Type 3 dependencies (infrastructure whose failure would compromise stop paths or auditability):**

- *Fedwire and ACH payment systems operated by the Federal Reserve* — failure would compromise transaction processing
- *Credit bureau reporting infrastructure (Equifax, Experian, TransUnion)* — failure would compromise creditworthiness assessment and customer-credit consequences
- *Core banking systems and customer information systems* — failure would compromise audit trail for stop-path purposes
- *FedNow / clearinghouse settlement* — failure would compromise instant payment systems

**6.4 — Capture risk identification:**
- [x] Yes
  - *Shareholder concentration:* S&P 500 component with substantial institutional ownership. Institutional investors typically focus on financial performance and may not weight affected-party considerations equally
  - *Federal-regulator-policy conditionality:* the CFPB has been subject to substantial policy contestation across administrations; consumer-protection enforcement posture has varied. Per R64 (External Circumvention) and R03 (Institutional Capture Prohibition), this regulatory volatility produces structural alignment risk
  - *Sales-incentive structures historically* (2010–2016 per 2024 CFPB finding) — produced systemic harm; banned by 2024 consent order for the specific behavior of incentivizing unauthorized account opening
  - *Repeat-offender pattern* — 2015 CFPB actions ($18M + $3.5M); 2024 CFPB action ($20M plus $35,000-customer remediation). The CFPB Director's 2024 characterization of Fifth Third as a "repeat offender" is documented public-source evidence relevant under R69 (Burden of Proof Reversal)
  - *Mandatory arbitration clauses with class-action waivers* in most customer contracts — limit collective customer voice in dispute resolution; structurally aligned with bank interest
  - *Industry trade association influence* (American Bankers Association, Ohio Bankers League, Consumer Bankers Association) — shapes regulatory environment affecting consumer protection rules
  - *Capital-markets and ratings-agency dependency* — bank cost-of-capital depends on credit ratings; ratings agencies are paid by issuers
  - *Auditor dependency:* external auditor relationship is structural; auditor independence concerns are general to the industry
  - *Branch-closure decisions in lower-income or majority-minority communities* — pattern attracted CRA-related attention historically across the industry; UH-specific patterns UNKNOWN
  - *Lobbying and political contributions* through corporate PAC and trade associations — shape regulatory environment

**6.5 — Reversibility-affecting dependencies:**
- *Customer credit-history adverse items* — propagate for 7+ years through credit bureaus; not retroactively reversible at the bank level
- *Foreclosure and repossession outcomes* — properties and vehicles transferred; customers displaced; not reversible
- *Discriminatory pricing harm to affected customers* (2015 finding) — remediated through monetary payments but underlying wealth-stripping effects not fully reversible
- *Unauthorized accounts opened in customer names* (2010–2016 pattern) — accounts can be closed but the credit and identification consequences propagate
- *Long-term loan portfolios and securitization commitments* — bind future activity
- *Branch real estate, technology, and other capital sunk*
- *Customer relationships and data accumulated over 167-year history*

**6.6 — Coordination disclosures:**
Fifth Third coordinates with:
- American Bankers Association, Consumer Bankers Association, Ohio Bankers League
- Federal Reserve Bank of Cleveland (Fourth Federal Reserve District)
- Other major regional banks through correspondent relationships
- Visa, Mastercard, and other payment networks
- Credit bureaus (Equifax, Experian, TransUnion) through Fair Credit Reporting Act information furnisher relationship
- ChexSystems and similar deposit-account-reporting agencies
- FinCEN through BSA/AML reporting infrastructure
- The Clearing House for payment processing
- Fannie Mae, Freddie Mac for mortgage securitization

Per R55/R59, the U.S. banking system is a coordinated regulatory system of which Fifth Third is one component.

**6.7 — Disclosure completeness assertion:**
- [ ] Not asserted — this Mechanism Record is third-party-produced.

**6.8 — External authority operationalization (R72):**
- *BSA/AML and OFAC sanctions screening* — federal mandates operationalized through Fifth Third systems; customers experience account-related actions but underlying decisions are federally compelled
- *FCRA dispute and information furnisher requirements* — federal mandate operationalized through Fifth Third dispute processes
- *Truth in Lending, Truth in Savings, RESPA disclosure mandates* — federal mandates operationalized through Fifth Third disclosure documents
- *FATCA and IRS information reporting* — federal mandates operationalized through customer information collection
- *Federal court legal-process compliance (garnishments, levies, attachments, subpoenas)* — court orders operationalized through Fifth Third holds and disclosures
- *Federal Reserve monetary policy* — operationalized through Fifth Third rate-setting
- *NACHA ACH rules and Federal Reserve payment system rules* — operationalized through Fifth Third payment processing
- *Capital and prudential rules (Basel III as implemented)* — operationalized through Fifth Third capital allocation

This R72 surface is substantial. Customers often experience "the bank did this" without distinguishing whether the action originates from Fifth Third discretion, federal regulator mandate, court order, or industry standard.

---

## SECTION 7 — What metrics, signals, and decision inputs shape outcomes?

**7.1 — Declared metrics:**

| Metric | Source | Role | Aggregate pub. | Individual pub. | Methodology pub. |
|---|---|---|---|---|---|
| Capital and asset metrics (10-K, call reports) | Fifth Third / SEC / OCC | Financial, prudential | Y | N/A | Y |
| CAMELS supervisory rating | OCC / Fifth Third | Supervisory | N (confidential) | N | Y (general framework public) |
| CRA Public Evaluation | OCC | Community reinvestment | Y | N | Y |
| HMDA mortgage lending data | CFPB / FFIEC | Fair lending | Y (LAR public) | Anonymized | Y |
| CFPB consumer complaint database | CFPB | Consumer harm | Y (aggregate; some individual narratives published with consent) | Partial | Y |
| Consumer protection enforcement actions (2015, 2024) | CFPB | Accountability | Y | N | Y |
| Credit ratings (Moody's, S&P, Fitch, DBRS) | rating agencies | Capital markets | Y | N/A | Y |
| Stress test results (DFAST/CCAR) | Federal Reserve / Fifth Third | Prudential | Y (selected results) | N/A | Y |
| 10-K, 10-Q, 8-K SEC filings | Fifth Third / SEC | Public-company disclosure | Y | N/A | Y |
| Proxy statement and executive compensation | Fifth Third / SEC | Public-company disclosure | Y | N/A | Y |
| Call reports filed with FFIEC | Fifth Third / regulators | Financial | Y | N/A | Y |
| Annual report and ESG/sustainability reports | Fifth Third | Voluntary disclosure | Y (when published) | N/A | Partial |

ANNOTATION: per SCBP-09 §IX-C, public-company and federal-banking-regulator reporting provides strong aggregate publication for financial, supervisory (CRA, public examinations), and disclosure dimensions. R67 floor is strong for many dimensions, with the notable confidentiality of CAMELS ratings and Matters Requiring Attention (MRA/MRIA) as supervisory examination findings.

**7.2 — Indirect signals:**
- Stock price (FITB on NASDAQ)
- Analyst ratings and equity research
- Bond spreads and credit default swap pricing
- Deposit growth and market share trends
- Customer satisfaction surveys (J.D. Power, etc.)
- Employee satisfaction surveys (Glassdoor, etc.)
- "World's Most Ethical Companies" (Ethisphere) recognitions (Fifth Third has received this recognition multiple years per public sources)
- "JUST Capital" rankings (Fifth Third has been recognized in this index for several years)
- ESG ratings (MSCI, Sustainalytics, etc.)

ANNOTATION: external recognitions like Ethisphere and JUST Capital provide external signals. The 2015 and 2024 CFPB enforcement findings, however, suggest these external evaluations and the regulatory consumer-protection record can produce divergent signals — Fifth Third is simultaneously recognized as "ethical" by one framework while subject to "repeat offender" characterization by federal regulators. The framework treats both signals as valid in different dimensions; neither alone is dispositive.

**7.3 — Algorithmic decision systems:**
- [x] Yes — substantially. Banking authorities of Fifth Third's scale deploy substantial algorithmic decision systems including: credit decisioning models (loan approval, credit card approval, mortgage underwriting); pricing models (interest rate setting for borrowers); fraud detection systems; BSA/AML transaction monitoring; collection prioritization models; customer-attrition prediction; cross-sell propensity models; deposit-pricing models; CRE underwriting models; ALCO interest rate risk models; capital allocation models. The CFPB has published guidance on algorithmic decision-making in consumer financial services. UH-specific algorithmic deployment details are UNKNOWN from public sources reviewed.
- ANNOTATION: marked Yes in the YAML because algorithmic decisioning is substantively present at any bank of this scale. Documentation specifics for Fifth Third's particular systems are UNKNOWN.

**7.4 — Outcome-versus-declaration check:**
- [ ] Not formally declared as a structural commitment. CFPB examinations, CRA examinations, HMDA analyses, OCC examinations, and consumer complaint volumes provide *external* outcome-versus-declaration mechanisms. A formal R79/R80 commitment is not explicitly declared.

---

## SECTION 8 — How is this authority watched?

**8.1 — Drift monitoring mechanism:**
- *OCC examination cycle* — typically annual for large banks
- *Federal Reserve holding company supervision* — ongoing
- *CFPB examination and supervision* — periodic; consumer complaint database continuously updated
- *FDIC supervision* — coordinate with OCC
- *Annual proxy statement and 10-K disclosure* — annual
- *Quarterly 10-Q disclosure* — quarterly
- *Stress testing (DFAST/CCAR)* — annual
- *External auditor* — annual
- *Internal Audit* — ongoing internal
- *Compliance and risk management functions* — ongoing internal
- *Board committees including Risk Committee and Audit Committee* — ongoing
- *Credit rating agency review* — periodic
- *Equity analyst coverage* — ongoing
- *Customer complaint and ombudsman processes* — ongoing
- *Press and external analyst coverage* — ongoing

**8.2 — Capture risk monitoring:**
- OCC, Federal Reserve, FDIC, CFPB, and SEC examination functions
- Independent Board committees including Audit Committee with required independent directors
- External auditor reporting to Audit Committee
- Whistleblower hotlines and protections
- UNKNOWN whether internal capture-risk monitoring covers sales-incentive design, third-party relationship management, and similar specific patterns identified in past enforcement actions

**8.3 — Audit interfaces:**
- *Proactively published:* SEC filings (10-K, 10-Q, 8-K, proxy statement), call reports, CRA Public Evaluation, HMDA Loan Application Register (anonymized), CFPB consumer complaint database, news releases, voluntary ESG/sustainability reports, annual report
- *Available on request:* individual customer records to the customer under various federal and state laws
- *Restricted:* CAMELS supervisory ratings; MRA/MRIA examination findings; internal risk and audit reports; quality of loan portfolio detail; proprietary modeling; customer PII; trade secret information; certain personnel records; pending regulatory matters; pending litigation; certain BSA/AML information
- *Specifically protected:* bank examination privilege limits external access to confidential supervisory information

ANNOTATION: SCBP-09 §IX-E Dimensions 1 (scope), 2 (effect), 6 (reversibility), and 7 (expiration) are partially met through federal-mandate public disclosure. Dimensions 3 (harm thresholds), 4 (dependencies), 5 (derived outputs), and 8 (stop capability) are partially met but with substantive gaps preserved by examination privilege and trade-secret claims. The R67 (Minimum Auditability Floor) for the banking domain has substantive carve-outs.

**8.4 — Adversarial exposure (R81):**
A non-insider can:
- Access SEC filings and other federal public data
- Read CFPB consumer complaint database
- Read CRA Public Evaluation
- Read HMDA data
- Read enforcement orders (the 2015 and 2024 CFPB orders are accessible)
- Read 10-K and proxy statements with executive compensation
- File complaints with CFPB, OCC, state AG
- Access individual customer records as the customer
- Cannot easily obtain: confidential supervisory information; internal risk reports; quality-of-loan-portfolio granular detail; proprietary modeling; specific customer-affecting algorithmic decisioning systems and their fairness audits; aggregate complaint disposition data at unit or department level

**8.5 — Known structural failure modes:**
- Sales-incentive structures producing unauthorized accounts (the 2010–2016 pattern per 2024 CFPB finding)
- Forced or duplicative insurance products imposed on borrowers (the 2011–2020 collateral protection insurance pattern per 2024 CFPB finding)
- Discriminatory pricing through dealer discretion in indirect auto lending (the 2015 CFPB finding)
- Overdraft and NSF fee patterns with disproportionate impact on lower-balance customers (industry-wide pattern; UH-specific UNKNOWN)
- Mortgage servicing errors and foreclosure errors (industry-wide pattern)
- Data breaches and cybersecurity incidents (industry-wide pattern; UH-specific UNKNOWN)
- BSA/AML compliance failures (industry-wide enforcement pattern)
- Branch closure decisions affecting community access
- Workforce sales pressure and mandatory arbitration of employment disputes

**8.6 — Trade-secret / confidentiality declarations:**
- Category of restricted information: customer PII (GLBA, state privacy law); confidential supervisory information (bank examination privilege); BSA/AML information (federal statute); proprietary modeling; trade-secret information; certain personnel records; pending litigation; certain corporate strategic information
- Source of restriction: federal statute, agency regulation, state law, contractual NDAs
- Auditability mitigation: aggregate public reporting via SEC, FFIEC call reports, CFPB complaint database, CRA Public Evaluation, HMDA; federal regulator access under specific statutory frameworks
- R67 floor commitment: not explicitly declared; the framework's R67 floor is partially met through federal mandate but partially constrained by examination privilege

---

## SECTION 9 — How does it end?

**9.1 — Estimated dismantling time:**
UNKNOWN. Fifth Third is a publicly traded for-profit corporation with a federally chartered banking subsidiary. Dissolution would require Board action, shareholder approval, FDIC resolution authority for the bank (depositors are insured up to $250,000 per depositor per ownership category), OCC charter termination, SEC delisting, and bond-defeasance arrangements. ASSUMPTION: 36–120 months for an orderly wind-down or acquisition; bank failure resolution under FDIC authority can proceed more quickly (weekend resolution is common for FDIC-managed bank failures).

ANNOTATION: large bank holding companies generally do not voluntarily "dissolve" — they more typically merge with or are acquired by other systems. Fifth Third has engaged in acquisitions historically (the bank's growth through acquisition is documented in public sources, including the predecessor mergers that produced the "Fifth Third" name). Genuine voluntary dissolution at this scale would be unusual.

**9.2 — Dismantling process:**
UNKNOWN. No public dismantling plan exists beyond regulatory resolution planning required under Dodd-Frank Title I for large bank holding companies (the "living will" requirement). Components of a wind-down would include:
- Customer transition (deposit account transfer, loan servicing transfer, credit card portfolio sale)
- Employee transition (20,000+ employees)
- Branch real estate disposition (1,087+ locations)
- ATM disposition (2,400 directly operated)
- Resolution of FDIC deposit insurance assessment and bank charter
- SEC delisting and shareholder distribution
- Debt resolution including senior and subordinated debt
- Subsidiary and affiliate transitions (Fifth Third Securities; insurance affiliate; wealth management entities)
- Records transfer for federal regulatory and customer-historical purposes
- Pension and benefit plan obligations resolution

**9.3 — Entrenchment factors:**
- *Customer dependency:* 5.5 million customers with account relationships; transition is substantively complex
- *Workforce dependency:* 20,000+ employees and their families
- *Regional banking capacity:* particularly in markets where Fifth Third has substantial branch concentration
- *FDIC-insured deposit relationships:* substantial deposit base
- *Capital markets relationships:* outstanding senior and subordinated debt
- *Customer information and credit-history databases* accumulated over 167-year history
- *Shareholder interests:* S&P 500 component with substantial institutional ownership
- *Real estate and technology infrastructure:* 1,087 branches plus headquarters

R61 (Anti-Entrenchment) finding: Fifth Third is structurally embedded in regional banking, U.S. consumer finance, and capital markets. Dismantling without acquisition or successor would create immediate banking-access disruption for 5.5 million customers. Acquisition or asset transition to other systems is the realistic wind-down pathway, not dissolution.

**9.4 — Data disposition:**
UNKNOWN specifics. FCRA, GLBA, IRS, BSA/AML, and state law retention requirements apply. Disposition to successor entity or designated records custodian per applicable law.

**9.5 — Downstream effect reversibility:**
Customer credit-history adverse items, foreclosure outcomes, repossession outcomes, discriminatory-pricing-related wealth-stripping, unauthorized-account credit consequences, and CTR/SAR-related federal information records are largely not reversible at the bank level. Per R63, downstream propagation is not reversible.

**9.6 — Replacement feasibility:**
Banking services in Fifth Third's 12-state footprint would require replacement: by acquisition by another bank holding company, by FDIC-managed resolution with deposit transfer to acquirer, by customer migration to other institutions, or by combination. FDIC deposit insurance and continued banking-access obligations would shape transition.

**9.7 — Reversibility verification:**
- [ ] Verified
- [x] Not verified — Dodd-Frank Title I "living will" requirement creates a partial verification mechanism (large bank holding companies must submit resolution plans to Federal Reserve and FDIC). UNKNOWN whether Fifth Third's living will is fully public.

---

## SECTION 10 — Authorization, renewal, and trigger declarations

**10.1 — Authorizing body:**
- Office of the Comptroller of the Currency (national bank charter)
- Federal Reserve Board (bank holding company status)
- Federal Deposit Insurance Corporation (deposit insurance)
- State of incorporation (Ohio; corporate existence)
- Securities and Exchange Commission and NASDAQ (public-company status)
- Board of Directors (governance)
- Shareholders (ultimate ownership)

**10.2 — Date of current authorization:**
- Founded 1858 (167 years ago)
- National bank charter: continuing under OCC supervision
- Holding company status: continuing under Federal Reserve supervision
- NASDAQ listing: continuing
- Most recent 10-K: 2024 fiscal year filing (filed Feb 2025)
- Most recent annual proxy: 2025
- Most recent OCC examination cycle: continuing (specific examination dates confidential)

**10.3 — Authorization expiration date:** UNKNOWN — no scheduled expiration of the bank charter; authority continues so long as regulatory compliance and capital requirements are maintained.

**10.4 — Renewal interval:** 1 year (corresponding to annual OCC examination cycle, annual proxy and 10-K, annual stress testing, and annual external audit cycle, which together constitute the most substantive periodic review framework for a large bank). ANNOTATION: this is the shortest renewal interval among records in this registry, reflecting the dense and continuous federal supervisory framework for banks.

**10.5 — Renewal evidence declaration:**
- [ ] Scope integrity evidence
- [ ] Harm compliance evidence
- [ ] Stop path integrity evidence
- [ ] Dependency and capture evidence
- [ ] Reversibility evidence

ANNOTATION: federal banking supervision provides substantive external evidence across most framework dimensions. A structured renewal-evidence commitment in the R47 framework sense is not declared as Fifth Third's own practice but is heavily compelled by federal regulation.

**10.6 — Necessity-decay acknowledgment:**
- [ ] Acknowledged — public sources do not document such an acknowledgment.

**10.7 — Aggregate trigger threshold:**
- Number of triggers: 50
- Within window of: 90 days
- (SCBP-09 §II: non-consenting affected population of 500,000 falls in the 100,000–1,000,000 band; minimum 10 in 90 days, maximum 50 in 90 days. The value 50 in 90 days is at the *ceiling* of the band — consistent with UH (SCBP-REG-0016) given the very large customer population and substantial routine grievance volume, while still representing organized concern when reached.)

**10.8 — Aggregate threshold justification:**
The 50-in-90-days threshold is set at the SCBP-09 ceiling of the 100,000–1,000,000 band. Rationale:
- Banking authorities of Fifth Third's scale receive routine customer complaint volume (per CFPB consumer complaint database, large banks log thousands of complaints annually including non-systemic matters)
- A floor-level threshold (10 in 90 days) could trigger constant review without indicating systemic concern
- A ceiling-level threshold (50 in 90 days) represents 0.01% of the non-consenting population per quarter — substantively low rate indicating organized concern

ANNOTATION: this matches the §10.7 declaration for UH (SCBP-REG-0016). For Fifth Third, the rationale is structurally similar but stakeholders may reasonably contest under SCBP-08 given the documented repeat-offender pattern. A reviewer may want to argue for a lower threshold given the elevated R69 burden-of-proof posture documented in the 2015 and 2024 CFPB findings.

**10.9 — Response time window:** 30 days (SCBP-09 §III default).

**10.10 — Response window justification:** the SCBP-09 default of 30 days is adopted.

---

## SECTION 11 — What does this authority commit to publishing?

**11.1 — Citizen ledger publication:**
- [x] Annually (10-K, proxy statement, CRA Public Evaluation when issued, HMDA Loan Application Register)
- [x] Quarterly (10-Q, call reports, dividend declarations)
- [x] Other (8-K material event filings as required; voluntary ESG/sustainability reports; periodic CFPB complaint database updates by CFPB)

Content commitments per public-source observation:
- [x] Operating expenditures (via 10-K and 10-Q)
- [ ] Renewal status — OCC examination findings (CAMELS) are confidential, but enforcement orders when issued become public
- [x] Stop events partial: federal enforcement orders are public; private litigation is court record; the 2015 and 2024 CFPB orders are documented public events
- [x] Structural dependency status partial: 10-K Item 3 (legal proceedings); proxy statement related-party transactions; vendor disclosure at summary level
- [x] Other: stock exchange filings, news releases, press releases, executive compensation in proxy statement, audited financial statements

This is a strong publication baseline driven by SEC, federal banking regulator, and capital market reporting requirements — comparable in breadth to other regulated public companies, with stricter and more frequent disclosure than for nonprofit hospitals (SCBP-REG-0016) or housing authorities (SCBP-REG-0014).

**11.2 — Threshold change log:** Partial. SEC filings document policy changes; consent orders document specific operational changes (the 2024 consent order specifically banned sales goals incentivizing unauthorized account opening). A formal threshold change log per R08 is not documented.

**11.3 — Interpretation change log:** Partial. Material policy changes appear in SEC filings; operational interpretation is generally internal. A formal interpretation change log per R16 is not documented.

**11.4 — Renewal process visibility:** annual external audit, annual proxy, annual stress testing results; OCC examination results are confidential except for enforcement actions which become public. The structured renewal evidence per R47 is not a declared Fifth Third practice but is substantially compelled by external regulation.

**11.5 — Stop event log:**
- [ ] Acknowledged. Federal enforcement orders are public; private litigation is court record; CFPB consumer complaint database is public. A single Fifth Third stop-event log is not maintained.

---

## SECTION 12 — Honesty assertions

ANNOTATION: §12 honesty assertions are commitments by the filing authority. For this PUBLIC_SOURCES record, no checkbox is asserted, because no authority has filed the record.

**12.1 — Disclosure completeness assertion:**
- [ ] Asserted

**12.2 — Update obligation:**
- [ ] Committed

**12.3 — Discoverability acknowledgment:**
- [ ] Acknowledged

ANNOTATION: per R69 (Burden of Proof Reversal), the CFPB's 2024 characterization of Fifth Third as a "repeat offender" — combining the 2015 actions on discriminatory auto-loan pricing and illegal credit card practices with the 2024 action on unauthorized account opening and wrongful auto repossession — constitutes documented external evidence of patterns relevant under R69. The framework's burden-of-proof posture is structurally elevated for this authority.

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

- v1 — 2026-05-17: initial PUBLIC_SOURCES record produced by third party from publicly available information. Filed under SCBP-REG-0018-FITB per registry sequential numbering convention.

---

## Cross-references to other records

- **SCBP-REG-0005** (Shaker Heights Police Department): no direct functional relationship
- **SCBP-REG-0007** (Shaker Heights Department of Building & Housing): no direct functional relationship; bank may hold mortgages on Shaker Heights properties subject to POS requirements
- **SCBP-REG-0008** (Shaker Heights City School District): no direct functional relationship; bank may provide treasury services to district (UNKNOWN specifics)
- **SCBP-REG-0010** (Shaker Heights Architectural Board of Review): no direct functional relationship
- **SCBP-REG-0012** (Greater Cleveland Regional Transit Authority): coordinate — bank may provide payment services to GCRTA (UNKNOWN specifics); Fifth Third sponsors regional events that include GCRTA-served venues
- **SCBP-REG-0014** (Cuyahoga Metropolitan Housing Authority): coordinate — Fifth Third may participate in HCV-receiving landlord financing or low-income housing tax credit transactions touching CMHA properties (UNKNOWN specifics); Fifth Third branches operate in neighborhoods with concentrated CMHA properties
- **SCBP-REG-0016** (University Hospitals Health System): coordinate — Fifth Third likely provides various banking and treasury services to UH; UH employees may bank with Fifth Third; framework cross-reference is operational rather than structural

ANNOTATION: this is the first record in this registry for a *for-profit publicly-traded* authority. Several structural features distinguish it from prior records:
- Owners are shareholders rather than the public, charitable beneficiaries, or members
- Fiduciary duties run to shareholders alongside regulatory obligations — a structural feature framework-relevant under R03 (Institutional Capture Prohibition)
- Stop paths are principally federal regulatory rather than electoral or accreditation-based
- The "repeat offender" characterization in the 2024 CFPB action provides documented R69 (Burden of Proof Reversal) basis distinctive to this record
- Mandatory arbitration with class-action waivers is a substantive communicative-suppression feature distinctive to this record
- Coercive ceiling operates through contract, lien, collection, credit-reporting, and account-control authority rather than state coercion or medical authority
- Renewal interval is the shortest (1 year) among records in this registry, reflecting the dense and continuous federal supervisory framework for banks

---

**PUBLIC SOURCES ONLY** — This Mechanism Record was produced by a third party from publicly available information. It has not been reviewed, confirmed, or filed by Fifth Third Bank or Fifth Third Bancorp. If the authority later files corrections to this record, the existing record will be updated in place per the authority-after-citizen rule (Part 1, step 7.5 of the AI Registration Bundle); the mechanism_id and filename will remain unchanged.
