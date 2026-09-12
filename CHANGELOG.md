# 📝 CHANGELOG & VERSION HISTORY

All notable changes to the Current Affairs Dossier repository and Rajputana Gazette Broadsheet System are documented here.

## 🚀 [v2.0] — 2026-09-12

### 🌐 Major Rajputana Broadsheet Presentation Architecture Overhaul & Metric Intelligence Hub
- **Universal Nested List Hierarchy Overhaul Across All Monthly Dossiers (Over 1,700 Bullets Healed)**:
  - Systematically audited and converted all non-standard Unicode dot bullets (`• `) across `current_affairs_2026_september.md` (403), `current_affairs_2026_june.md` (534), `current_affairs_2026_may.md` (397), `current_affairs_2026_july.md` (201), `aug_ca_cgb1-31aug_pib1-18aug.md` (128), and `IBPS_MAINS_35PLUS_MASTER_JAN_SEPT.md` (393) to standard GitHub Flavored Markdown list syntax (`  - ` / `- `).
  - Completely resolved the collapsed/squashed nested bullet bug across the entire broadsheet portal: all sub-points under news clusters now render with clean, indented hierarchical `<ul><li>` structures.
- **Universal Multi-Bullet Exam Angle Architecture (`.gazette-exam-list`)**:
  - Re-structured all multi-point `🎯 Exam Angle →` blocks across September (55), IBPS Master (129), June (61), May (35), July (30), and August (12) with standard Markdown list syntax and blank line isolation.
  - Injected dedicated `.gazette-exam-list` CSS (custom square bullet markers, 18px padding, 1.5 line height, and clean typography), transforming cramped single-line run-ons into prominent, highly readable review cards.
- **High-Frequency Metric Strip & Chrono-Timeline Broadsheet Styling**:
  - Injected authentic Rajputana Broadsheet CSS targeting `.metric-strip-container`, `.feature-panel-header`, `.panel-heading`, `.panel-title`, `.panel-tag`, `.panel-count`, `.metric-cards-grid`, `.metric-card`, `.metric-val`, `.metric-trend`, `.metric-label`, and `.metric-sub`.
  - Metric chips render in a responsive grid featuring ivory newsprint (`--paper`) card surfaces, sandstone (`--wash`) hover states, and bold terracotta (`--accent`) values.
  - Added full broadsheet styles for `.chrono-timeline-container`, `.timeline-horizontal-wrapper`, `.timeline-stepper`, `.timeline-step`, step dots/lines, and date badges.
- **Interactive Click-to-Jump Navigation (`jumpToTarget`)**:
  - Implemented the `jumpToTarget(targetId)` handler scoped strictly to the active monthly document card, preventing DOM ID collisions across tabs and ensuring smooth centered auto-scrolling with `.pulse-highlight` animations when any metric chip is clicked.
- **LaTeX Math & Currency Symbol Sanitization**:
  - Escaped all literal currency dollar figures (`\$`) across all monthly dossiers (including August, April, Q1, and IBPS Master) to prevent accidental KaTeX LaTeX math mode invocation.
- **Strict Invariants Verified (All 8 Broadsheet Tabs)**:
  - Total Verified Clusters: **589 / 589 intact**.
  - Total Exam Angle Boxes: **595 / 595 styled and rendered**.
  - Total Squashed `<li>` Elements: **0**.
  - Heading anchor hashes (`#` in `<h1..h6>`): **Strictly 0**.
  - Interactive checkboxes: **Strictly 0**.
  - Full synchronization between `current_affairs_hub.html` and `index.html`.

## 🚀 [v1.9] — 2026-09-11

### 💎 September 2026 Dossier Comprehensive Enhancement (55 Clusters) & Weekly PDF Integration
- **Exhaustive 55-Cluster Enhanced Master Dossier (`current_affairs_2026_september.md`)**:
  - Filtered, deduplicated, and extracted high-yield institutional, regulatory, economic, and defence anchors from `Sept6927cf5d2b211a2b729e125eember 2026 CA Weekly PDF 1.pdf`.
  - **7 Existing Sagas Enriched with Numerical & Statutory Anchors**:
    - **India Post Payments Bank (IPPB)**: Added ₹21.61 Lakh Crore cumulative transaction volume (₹7.41L Cr UPI, ₹36,140 Cr AePS across 12.06 Cr transactions, ₹1.55L Cr DBT) and triple FinTech launch (*“DakPay Sound Box”*, *“Digital Insurance Technology Platform”*, *“Digital Mutual Fund Platform”*).
    - **NPCI International (NIPL) UPI Grid**: Confirmed formal 11-nation roster (Singapore, UAE, France, Mauritius, Nepal, Bhutan, Qatar, Sri Lanka, Cambodia, Greece, and Uzbekistan) with dual RBI and CBU statutory greenlights.
    - **August 2026 GST & UPI Records**: Added historical peak monthly UPI volume of 24.51 billion transactions worth ₹29.82 Lakh Crore (22% YoY volume growth, 791 million daily average).
    - **MoSPI National Accounts Statistics (NAS 2026)**: Q1 FY27 Real GDP 7.8% (₹81.36 Lakh Cr), Nominal GDP 10.3% (₹88.27L Cr), Real GVA 8.2% (₹73.82L Cr), Base Year 2022-23 shift, Double Deflation Method using Output PPI, and GFCF expansion of 11.9%.
    - **Bihar–Jharkhand Sone River Accord**: Explicit volumetric water distribution (5.75 MAF to Bihar, 2.00 MAF to Jharkhand) resolving the 25-year dispute, with release protocols for Bansagar and Rihand dams.
    - **AVNL Jabalpur T-Series MBT Facility**: Added national context of ~230 annual Army tank overhauls, Avadi HVF handling ~150/year, and VFJ Jabalpur adding 80 tanks/year under ₹472 Crore outlay.
    - **Global Summits & International Honours**: Added Prime Minister Narendra Modi conferred with Uzbekistan's highest state honour for foreign dignitaries, the *“Oliy Darajali Do’stlik” Order (Order of Highest Friendship)*, by President Shavkat Mirziyoyev at Tashkent.
  - **15 New High-Yield Clusters Added to Dossier**:
    1. **SEBI IT Resilience Index (ITRI) Framework**: 100-point scale across 9 weighted parameters for all Market Infrastructure Institutions (Availability 20%, Security 20%, Integrity 10%, Governance 10%, BCP/DR 10%, Reliability 10%, Modularity 10%, Scalability 5%, Incident Handling 5%) with Industry Standards Forum (ISF) guidelines.
    2. **RBI Concessional USD-INR Swap Relaxation & Suman Ray ED Appointment**: Banks allowed daily access outside weekly windows for FCNR(B) swaps >$100M (sub-$100M stays on designated day); Suman Ray promoted to RBI Executive Director heading DICGC and Premises Department.
    3. **SBI BSBDA Branch Cash Withdrawal Revision**: Effective October 1, 2026, 4 free branch cash withdrawals per month on Product Code 1011-1701; flat ₹15 + GST per subsequent branch withdrawal; digital channels remain 100% free.
    4. **Bank of Baroda 'UPI Global Reverse Acceptance'**: First PSU bank to enable inbound foreign travellers/wallets to scan BoB merchant UPI QR codes across India for cross-border P2M settlements.
    5. **NCDEX Launches 'RAINCHNNAI' Monsoon Futures**: India's first SEBI-approved weather index futures contract hedging Chennai Northeast monsoon rainfall via Cumulative Deviation Rainfall (CDR) model (1 mm tick, max 50 lots, cash-settled).
    6. **Union Government Achieves 78% of FY27 Disinvestment Target & Jio Platforms IPO**: Mobilised ₹62,124 Crore in 5 months against ₹80,000 Crore target (6.5% LIC sale yielding ₹31,515 Cr); Jio Platforms receives SEBI nod for ₹37,700 Crore IPO (270M fresh shares; RIL 66.43%, Meta 9.98%, Google 7.73%).
    7. **DGFT Relaxes 'One Star Export House' Norms**: Exporters now eligible by meeting threshold in ANY 2 of the 3 preceding financial years under FTP 2023 (gems & jewellery excluded; 5-year validity).
    8. **PPPAC Approves ₹8,622 Crore Privatisation of 11 AAI Airports**: Chaired by DEA Secretary Anuradha Thakur; 50-year PPP concessions in 5 bundles (Amritsar+Kangra, Varanasi+Gaya+Kushinagar, Bhubaneswar+Hubballi, Raipur+Aurangabad, Tiruchirappalli+Tirupati).
    9. **AISHE Report 2023-24**: National higher education GER reaches 30.0% (female GER 31.2% vs male 28.9%, GPI 1.08 for 7th consecutive year, total enrolment 4.50 Cr, PhD enrolments up 192.9% to 3.43 lakh, STEM enrolment 1.02 Cr with 44% women).
    10. **Legal Metrology (IST) Rules 2026 & National Tribunals Data Grid**: Mandates IST (UTC+05:30) maintained solely by CSIR-NPL as sole legal reference across banking and power grids within 180 days; NTDG established across 16 tribunals under Tribunals Reforms Bill 2026.
    11. **Indian Navy Commissions DSV 'INS Nipun' & L&T Delivers 'Samarthak' MPV**: 2nd Nistar-class Diving Support Vessel commissioned at Mumbai (9,350 tonnes, built by HSL Visakhapatnam); L&T delivers 1st Multi-Purpose Vessel under ₹887 Cr contract; GSL delivers ICGS Ajit FPV.
    12. **HAL–Safran JV Finalises 'Aravalli' Engine Contract & India Joins GCAP**: 50:50 SAFHAL JV to produce 3,500–4,000 shp Aravalli engines at Tumakuru, Karnataka for 13-tonne IMRH and 12.5-tonne DBMRH; India admitted as Dialogue Partner in 6th-gen GCAP / Tempest.
    13. **Indian Army Signs $45.7M Javelin Missile LOA & Raises 1st 'Baaz Battalion'**: 100 missiles + 25 Block-1 CLUs via US FMS; dedicated drone battalion raised at Jalandhar under 11 Corps; IAF tests Khagantak-243 LRGB; DRDO tests MCPS parachute from 22,000 ft at Nyoma-Mudh Drop Zone.
    14. **National Critical Minerals Innovation Hackathon (CMiH 2026) & C-DOT Quantum Battery**: NCMM hackathon under Ministry of Mines; C-DOT releases 14 quantum products across QKD and PQC; BIS silver hallmarking (IS 2112:2025) expanded across 102 districts.
    15. **Institutional Development Accords: ADB ₹1,750 Cr Karnataka Loan & NABARD–NaBFID Pact**: ADB loan for 500 model Karnataka Public Schools (KPS); NABARD-NaBFID strategic infrastructure financing alliance; Mission Rangeen Machhli 2031 launched at Agatti, Lakshadweep.
- **Strict Invariant & Broadsheet Presentation Verification**:
  - Recompiled `current_affairs_hub.html` and `index.html` via `generate_broadsheet_hub.mjs` and `build_all.js` (hub count reaches **589 total items**).
  - Heading anchor hashes strictly verified: **0 '#' symbols in <h1..h6>**.
  - Interactive checkboxes strictly verified: **0 checkboxes**.
  - LaTeX math formatting strictly verified: literal dollar amounts safely escaped.

## 🚀 [v1.8] — 2026-09-11

### 👑 IBPS PO Mains 35+ Strike File Strategic Enhancement & September 2026 Master Integration
- **Exhaustive 40-Cluster Dedicated Master Dossier ('current_affairs_2026_september.md')**:
  - **Capital Markets & Financial Regulators**:
    - **IFSCA Market Abuse Regulations 2026 in GIFT IFSC**: Formally replaces SEBI PIT 2015 and SEBI PFUTP 2003 regimes within GIFT City; designated persons must report quarterly trades exceeding **$25,000 within 2 business days**.
    - **PFRDA Standardised 5-Category Equity Classification under MSF**: Cat A (80%–100% equity / Aggressive), Cat B (60%–80% / High Growth), Cat C (35%–60% / Balanced), Cat D (10%–35% / Conservative), Cat E (0%–10% / Debt-oriented).
    - **SEBI FPI Compliance Easing**: Relaxed granular beneficial ownership look-through norms for Category-I FPIs holding 100% of assets in sovereign G-Secs/T-Bills.
    - **SEBI Cash Market Net Settlement**: Proposed net settlement across mutual fund schemes to eliminate intraday liquidity drag; extended Angel Fund accredited investor compliance while grandfathering PPMs.
    - **SEBI & ESMA CCP Cooperation Accord**: Bilateral MoU establishing supervisory exchange and equivalence for Indian Central Counterparties.
    - **NFRA Advisory Committee**: Set up panel on Audit Quality, Assurance, and Forensic Technologies under Section 132 of Companies Act, 2013.
  - **Banking, Sovereign Credit & Central Banking**:
    - **Coastal Local Area Bank Scheduled Bank Status**: Vijayawada-headquartered Coastal LAB becomes **India's first Local Area Bank** inscribed in the **Second Schedule of the RBI Act, 1934** with full LAF/MSF access.
    - **MoF & IFC $1 Billion MSME Financing**: Ministry of Finance secures $1 Billion credit line from IFC (World Bank Group), with **$500 million disbursed directly to SIDBI**.
    - **RBI Survey Battery for MPC**: Rolled out CCS, IESH, and Rural Consumer Confidence Survey (RCCS) for benchmark policy forecasting.
    - **UCB Investment in IDPIC**: Urban Co-operative Banks permitted to acquire equity shares in IDPIC for institutional membership exempt from commercial non-SLR ceilings.
    - **LIC 9.99% Stake in ICICI Bank**: RBI approved acquisition up to 9.99% voting rights/capital to be executed within 1 year; RBI slapped ₹26.82 lakh fine on TransUnion CIBIL under CICRA 2005.
    - **IPPB 9th Foundation Day**: India Post Payments Bank marks September 1 anniversary with ₹100 crore operating profit milestone across 1.61 lakh branches.
    - **S&P Assigns 'BBB' to Bank of India**: Investment-grade rating assigned on strong capital and deposit franchise; Bandhan Bank launches 4-tier credit cards; Indian Bank opens Dubai office; Axis Bank launches 'ARISE Homecoming'.
  - **Digital Payments & FinTech Innovation**:
    - **Global Fintech Fest (GFF) 2026 (Mumbai)**: PM Modi inaugurates 5th edition; unveils 4-Point Fintech Charter (Cybersecurity, Data Ethics, Regulatory Sandbox, Consumer Protection Index) alongside Agentic AI and tokenisation.
    - **Jio Payment Solutions PA-CB Licence**: JPSL receives RBI authorization for cross-border export/import payment aggregation; partners with Citi.
    - **NPCI International (NIPL) in Uzbekistan**: Partners with HUMO (NIPC) enabling Indian tourists to scan national UZQR codes via UPI apps.
    - **Fintech Deployments**: PhonePe & Visa launch Tap to Pay, Smart Accept, and Cross-Border Scan to Pay across 14 countries; PayGlocal launches 'Flash'; India's first Tokenised Municipal Bond issued on DLT; WhatsApp in-app BBPS utility payments.
    - **IRDAI Public Insurance Registry (PIR)**: Exposure draft for single insurance repository; ₹1 crore fine levied on ICICI Lombard.
  - **Macroeconomic & Foreign Trade Milestones**:
    - **Japan Credit Rating Agency (JCR) Sovereign Upgrade**: Upgraded India's sovereign rating to **'A-' (Investment Grade)** with Stable Outlook.
    - **August 2026 Gross GST**: Reached **₹1.87 lakh crore (₹1,87,345 crore)**, recording a 14.8% YoY surge.
    - **Q1 FY27 CAD at $4.2 Billion (0.4% of GDP)**: RBI Balance of Payments data; net services receipts at $39.7 billion.
    - **MoSPI Q1 FY27 Agri GVA Growth**: Moderated to 3.6% (from 4.4% in Q1 FY26); HSBC Manufacturing PMI at 52.8.
    - **DEA E-Commerce Export FDI Amendment**: E-commerce marketplace entities permitted to hold physical inventory strictly for export purposes.
  - **National Heritage, Defence & Deep-Tech**:
    - **UNESCO Tentative List Expansion**: Added 4 sites (Rangpur-Sivasagar Assam, Andaman Penal Settlement, Nicobar Cultural Continuity, Shekhawati Havelis Rajasthan), taking tentative tally to 57.
    - **Bihar–Jharkhand Sone River Pact**: Resolved 25-year water dispute across 8 Bihar districts and Jharkhand tracts.
    - **ASI Protected Monument**: Gollala Gudi Temple (Telangana) declared Monument of National Importance.
    - **Operation BRICS Kavach**: NSG multi-agency anti-terror drill securing 18th BRICS Summit venues in New Delhi.
    - **Exercise Veer Guardian 2026**: 2nd edition bilateral air exercise between IAF and Japan JASDF at AFS Jodhpur.
    - **IAF Dronathon-2026 & Army AASHVAST Lab**: UAS/CUAS live trials at Pokhran; DG EME hardware/software vulnerability lab.
    - **AVNL Jabalpur Overhaul Facility**: ₹472 crore facility for 80 T-72/T-90 tanks/year; GE Aerospace delivers 3 F404 engines to HAL (14th Maharatna).
    - **ISRO EOS-05 Satellite**: Geosynchronous Earth Observation satellite launched via GSLV from Sriharikota.
    - **DRDO BAM-H24 Propellant**: Patented high-energy boron-nitrogen-hydrogen rocket compound with University of Hyderabad; GalaxEye wins US patent for SAR-optical imaging.
  - **Honours, Appointments & Sports**:
    - **Ramon Magsaysay Awards 2026**: Tommy Koh (Singapore), Bo Kyi (Myanmar), Runa Khan (Bangladesh).
    - **72nd National Film Awards in Ekta Nagar, Gujarat**: First ceremony held outside New Delhi since 1970 (Madras).
    - **Executive Transitions**: John Ternus appointed Apple CEO (Tim Cook becomes Executive Chairman); Vinaya Prakash Singh re-elected APPU Secretary-General (Bangkok); Anil Chakravarthy named Adobe CEO; Shenu Agarwal elected SIAM President.
    - **Sports Sagas**: Lionel Messi retires from international football (125 goals); Smriti Mandhana becomes highest run-scorer in women's cricket; Satwik-Chirag win maiden China Masters; India places 4th at Pickleball World Cup (41 medals).
- **Broadsheet Hub Upgrades**:
  - Activated dedicated **September 2026 (Days 1–10)** interactive tab with 8 high-frequency metric chips and live slide-out Table of Contents.
  - Hub total expanded to **566 verified clusters** across 8 fully compiled months.
  - Strict zero-hash (`#` inside `<h1..h6>`) and zero-checkbox invariants passed 100%.
- **IBPS PO Mains 35+ Marks Guarantee Strike File Enhancement ('IBPS_MAINS_35PLUS_MASTER_JAN_SEPT.md')**:
  - Enhanced from 121 to **129 high-yield sagas**:
    - **RBI Mission SAKSHAM (Section 1)**: Large-scale capacity building and governance training for 1.40 lakh personnel across Urban Co-operative Banks (UCBs) via College of Agricultural Banking (CAB), Pune.
    - **PM RAHAT Scheme (Section 5)**: Cashless golden-hour medical treatment up to ₹1.50 lakh per victim for up to 7 days under MVAF (Motor Vehicles Act, 1988) with 24–48 hr police authentication.
    - **Urban Challenge Fund (UCF, Section 5)**: ₹1 Lakh Crore outlay (FY26–FY31); 25% Centre grant, min 50% commercial market debt/PPP; ₹5,000 Cr creditworthiness corpus for 4,223 cities.
    - **GOBARdhan Revamped Scheme (Section 5)**: ₹23,731 Cr outlay across 10 years (FY27–FY36); mandatory CGD CBG blending glidepath: 3% in FY27 ➔ 4% in FY28 ➔ 5% from FY29 onwards; ₹2 Cr/TPD capital subsidy.
    - **PM-SETU Programme (Section 5)**: ₹60,000 Cr outlay to upgrade 1,000 ITIs into Industry 4.0 Centers of Excellence under MSDE.
    - **Maritime India Vision 2030 Breakthrough (Section 6)**: India becomes world's #1 ship recycling nation 5 years ahead of schedule; 100+ Hong Kong Convention (HKC) compliant plots at Alang, Gujarat.
    - **LSEG Green Revenues Report (Section 9)**: Indian firms generated ~$110 Billion in green revenues in 2025 across solar/wind, EV charging, and green hydrogen.
    - **NITI Aayog 8th Trade Watch Quarterly (Section 9)**: Structural export pivot towards Asia, Africa, and Latin America.

## 🚀 [v1.6] — 2026-09-09

### 🏛️ May 2026 Complete Master Integration: RBI Circulars, Bulletins & Best 200 MCQs Parts 1 & 2 ('apdfH_3VkS8', 'hgPD65GnM1Q', 'PhHymXFO0uY')
- **Exhaustive 35-Cluster Master Dossier ('current_affairs_2026_may.md')**:
  - **Part 1 Best 200 MCQs Master Deployments**:
    - **Critical Mineral Recycling Incentive Scheme**: ₹1,500 Cr outlay over 6 years (FY26–FY31) under National Critical Mineral Mission (NCMM); 58 companies approved; 1/3rd (33.3%) reserved for MSMEs; up to 20% capex subsidy (₹50 Cr large / ₹25 Cr small ceiling); Project Management Agency JNARDDC (Nagpur).
    - **New Direct Tax Rules 2026 (SEP & Audit Trails)**: Significant Economic Presence (SEP) threshold at >₹2 Cr transaction value or >3 lakh Indian users; mandatory 7-year immutable audit trail across financial intermediaries.
    - **Panchayat Advancement Index (PAI 2.0)**: Streamlined to 150 indicators and 230 data points across 9 LSDG themes; Rank 1 Tripura (Jugal Kishore Nagar village top GP), Rank 2 Kerala; zero beginner Category D Panchayats in Tripura, Kerala, Sikkim.
    - **Inauguration of India's 1st PM MITRA Textile Park at Warangal**: Dedicated by PM Modi under ₹4,445 Cr scheme (7 approved parks: Telangana, Tamil Nadu, Gujarat, Karnataka, Madhya Pradesh, Uttar Pradesh, Maharashtra); anchored on 5F Vision.
  - **Part 2 Best 200 MCQs Master Deployments**:
    - **Cabinet Coal/Lignite Gasification Scheme**: ₹37,500 Cr outlay; up to 20% plant & machinery capital incentive; 30-year linkage tenure; targets 100 MT gasified by 2030 (75 MT current phase); single project cap ₹5,000 Cr (₹9,000 Cr for SNG/Urea), ₹12,000 Cr per corporate group.
    - **Thoothukudi Mega Greenfield Shipyard**: Tripartite MoU by MoPSW; dedicated SPV 'NSHIP-TN' promoted by VOCPA & SIPCOT; ₹24,736 Cr under National Shipbuilding Mission targeting Top-10 global by 2030 and Top-5 by 2047 (40-fold output expansion).
    - **LEADS 2025 & LEAPS Awards (7th Edition)**: DPIIT-World Bank LPI aligned 4-tier model (Exemplars, High Performers, Accelerators, Growth-Seekers); Top Exemplars: Uttar Pradesh (Landlocked), Tamil Nadu & Gujarat (Coastal), Mizoram (North-East), Delhi (UTs).
    - **Unified Bharat e-Charge (UBC) & PM E-DRIVE Deployments**: MHI launched UBC open interoperable charging platform developed by BHEL & NPCI; ₹10,900 Cr PM E-DRIVE scheme with ₹2,000 Cr for EV Public Charging Stations (1,243 chargers in Karnataka).
    - **VB-G RAM G Act, 2025 Enforced (Repealing MGNREGA 2005)**: 125 days guaranteed rural wage employment per financial year (up from 100 days); +10% distance allowance for worksites >5 km; highest-ever rural employment outlay of ₹95,692.31 Cr (60:40 general, 90:10 NE/Himalayan states); 3-day DBT processing / 15-day bank credit.
    - **Digital Bharat Nidhi (DBN) & BharatNet Phase III**: Telecommunications Act 2023 statutory rebrand of USOF funded via 5% AGR Universal Service Levy; non-lapsable rural broadband & 4G saturation expansion.
    - **BHAVYA Industrial Park Guidelines**: ₹33,668 Cr outlay over 6 years (FY27–FY32) for 100 smart industrial parks (50 in Phase 1); minimum 100 acres (general states) / 25 acres (NE/Hilly); capped at 1,000 acres; chaired by Secretary DPIIT Amardeep Singh Bhatia.
    - **Somnath Amrut Mahotsav & ₹75 Pure Silver Coin**: Commemorating 75 years of Somnath restoration (1951–2026); 99.9% pure silver, 40 grams, 44 mm, 200 serrations; ₹500 Cr Sardar Dham Education Support Yojana launched in Vadodara.
    - **3rd Advance Estimates 2025–26**: Record all-time high foodgrain output of 336.563 MT (Rice 134.024 MT, Wheat 120.657 MT, Coarse Cereals 74.47 MT, Oilseeds 41.22 MT).
  - **RBI Circulars & Bulletins Core Anchors**:
  - **RBI Deregulates FinTech Cross-Border Outward Remittances**: Discontinued prior approval mandate for AD Cat-I bank tie-ups with non-bank FinTechs for non-trade current account remittances under FEMA 1999; mandatory disclosure of exact foreign exchange credited and maximum delivery time.
  - **I4C & RBIH Strategic MoU on MuleHunter.ai™**: Indian Cyber Crime Coordination Centre (MHA) and Reserve Bank Innovation Hub (Bengaluru; CEO Sahil Kini) partner to deploy AI/ML 'MuleHunter.ai™' feeding into Digital Payment Intelligence Platform (DPIP).
  - **Major Revision of Investment Fluctuation Reserve (IFR)**:
    - Commercial Banks & Foreign Banks: IFR mandatory requirement **completely discontinued** effective May 18, 2026; existing balances moved below the line to Statutory/General Reserve or P&L and recognized as **Tier 1 (Core Capital)**.
    - PBs, SFBs & RRBs: Maintained only on balance sheet dates at minimum 2% of AFS/FVTPL (Tier 2 Capital).
    - Urban & Rural Co-op Banks (UCBs/RCBs): Retained at 5% minimum of investment portfolio (Tier 2 Capital).
  - **RBI Discussion Paper on Digital Payment Safety (Anti-Fraud Friction)**:
    - 1-Hour Lagged Credit on digital transfers >₹10,000 with unilateral sender cancellation option; instant settlement for whitelisted trusted beneficiaries (transactions >₹10,000 account for 98.5% of fraud value).
    - Trusted Person Authentication: Transfers >₹50,000 by senior citizens aged >70 years and PwDs require secondary trusted person sign-off.
    - National Digital 'Kill Switch' to instantly freeze outbound channels; ₹25 lakh annual credit cap on individual/merchant accounts.
  - **RBI Disaster Relief Loan Restructuring Directions**:
    - Automatic **suo motu** loan restructuring by banks and NBFCs across NDRF/SDRF declared disaster zones without waiting for formal borrower applications.
    - **135-day borrower opt-out window**; accounts must be standard (≤30 days overdue) on calamity date; accounts slipping into NPA upgraded back to Standard upon execution; 5% additional specific provision; 45-day invocation / 90-day implementation.
  - **Master Direction on Expected Credit Loss (ECL) Approach (Effective April 1, 2027)**:
    - Replaces 40-year 'Incurred Loss' model with 3-stage forward-looking provisioning: Stage 1 (12-month ECL; 0.40% secured, 0.25% MSME/agri, 1.00% unsecured retail); Stage 2 (Lifetime ECL, >30 days overdue, 5% floor); Stage 3 (Lifetime ECL, >90 days overdue, up to 100% unsecured).
    - Quantitative formula: $\text{ECL} = \text{PD} \times \text{LGD} \times \text{EAD}$.
    - Full transition of bank loan books to Effective Interest Rate (EIR) accounting by **March 31, 2030**.
  - **Global OTC Rupee Foreign Exchange Derivatives Reporting to CCIL**:
    - Mandatory global reporting of all deliverable and NDF Rupee OTC derivative contracts to Clearing Corporation of India Limited (CCIL).
    - 3-Phase rollout: Phase 1 (100% parent entities by July 1, 2027); Phase 2 (70%–80% related entities by January 1, 2028); Phase 3 (100% all entities globally by July 1, 2028).
  - **RBI Institutional Governance & Supervisory Milestones**:
    - 3-year mandatory cooling-off period for UCB/RCB directors completing 10 continuous years.
    - Q-SAFE Initiative: 8-member Expert Committee on Quantum Technology in FinTech chaired by Dr. Anil Prabhakar (IIT Madras).
    - Leadership appointments: Shri Rohit Jain appointed RBI Deputy Governor for 3 years (succeeding T. Rabi Sankar); Shri Gunveer Singh appointed Executive Director; Shri Elias George appointed Part-Time Chairman of Federal Bank; One MobiKwik Systems receives in-principle approval for NBFC subsidiary.
  - **SEBI 'GARUDA' Green-Channel Mechanism for AIFs**:
    - Rollout timeline slashed from 30 days to within **10 working days** of PPM filing for non-accredited funds.
    - Immediate green-channel launch for Angel Funds and Accredited Investor schemes without merchant banker certification (signed by CEO & Compliance Officer).
  - **PFRDA Retirement Income Schemes (RIS) under NPS**:
    - Post-retirement flexible drawdown up to **age 85 years** via Systematic Payout Rate (SPR, initial 4.0% payout) and Systematic Unit Redemption (SUR, fixed monthly unit redemptions).
  - **SEBI PaRRVA Framework & Mission Jagrook**:
    - Past Risk & Return Verification Agency (PaRRVA) live effective May 4, 2026 (CRA verification body + NSE PaRRVA Data Centre; CARE Ratings accredited); Mission Jagrook & SEBI Check Tool launched at 38th Foundation Day.
- **Broadsheet Hub Upgrades**:
  - May 2026 interactive tab refreshed to 22 verified clusters with high-yield metric chips.
  - Total Rajputana Gazette Broadsheet Hub items expanded to **513 verified clusters**.
  - Zero `#` heading anchor hashes verified across both HTML files.

## 🚀 [v1.5] — 2026-09-08

### 🏦 RBI Annual Report 2025–26 Master Deep-Dive Integration (Affairs Mind 'XHlm-gtTkOw')
- **Comprehensive 4-Cluster Overhaul in June Dossier ('current_affairs_2026_june.md')**:
  - **Cluster 1: Balance Sheet Surges 20.6% to ₹91.97 Lakh Crore & ₹2.89 Lakh Crore Surplus Transfer**:
    - Statutory presentation under **Section 53(2)** of RBI Act, 1934 (accounting period: April 2025 – March 2026).
    - Absolute balance sheet surge of **₹15,71,699.15 crore** to reach **₹91,97,121.08 crore** (**26.4% of GDP** vs 23.7% in FY25).
    - Surplus transfer of **₹2,88,588.45 crore** to the Central Government (FY25: ₹2,68,588.07 crore).
    - Contingent Risk Buffer (CRB) approved at upper cap of **6.50%** (ECF / Bimal Jalan range: 4.5%–7.5%); **₹1,09,379.64 crore** provisioned into Contingency Fund (CF).
    - Initial paid-up capital maintained at **₹5 crore** (nationalised January 1, 1949).
    - Foreign assets 70.9% (foreign investments ₹52.68 L Cr, gold ₹10.94 L Cr up 63.8%; net forex sales USD 53.13 Bn, net exchange gains ₹1.69 L Cr).
  - **Cluster 2: Currency Management, Counterfeits (FICNs) & Digital Rupee (e₹)**:
    - Banknotes in circulation expanded **11.9% in value** and **10.5% in volume**; ₹500 note holds highest volume share, followed by ₹10.
    - Coins in circulation rose **11.4% in value** and **4.5% in volume** (₹1, ₹2, and ₹5 account for 80.7% volume and 60.2% value).
    - ₹2000 denomination withdrawal: **98.45%** of ₹3.56 lakh crore returned to the banking system.
    - Total CBDC (e₹) in circulation reached **₹771.7 crore** as on March 31, 2026; retail programmable CBDC credited PDS food subsidies across Gujarat, Puducherry, and Chandigarh; wholesale CBDC tokenisation launched on CDs via Unified Markets Interface (UMI); cross-border CBDC MoUs with MAS and CBUAE; joined BIS Project Rialto and Mandala Phase 2.
    - FICN counterfeit detection: Reserve Bank detected only **2.4%**; commercial banks detected **97.6%**. SBI holds highest share of Currency Chests. Legacy 'Paisa Bolta Hai' replaced by the **Indian Currency Microsite**. Print trials of varnished banknotes conducted at **BRBNMPL Mysuru Press**.
  - **Cluster 3: Bank Frauds, Supervisory Reforms & Regulatory Modernisation**:
    - Systemic frauds rose 46% to **₹48,021 crore** across 10,114 cases; PSBs account for **74.5%** (₹35,709 Cr), Private banks 23.7%; Loan Advances category dominated with **₹40,774 crore** (85% of total fraud value).
    - Consolidation of Regulations: Over **11,000 circulars** condensed into **244 Master Directions**; 9,445 circulars repealed.
    - DICGC flat-rate premium maintained at **₹0.12 (12 paise) per ₹100** p.a. (0.12% p.a.); coverage ₹5 lakh; Risk-Based Premium (RBP) framework effective April 1, 2026.
    - Co-lending minimum retention lowered to **10%** (FLDG cover up to 5%).
    - FREE-AI Framework anchored on **7 Sutras** and **6 Strategic Pillars** (26 recommendations); **MuleHunter.ai™** deployed by RBIH to flag mule accounts; Digital Payment Intelligence Platform (DPIP) instituted.
  - **Cluster 4: Monetary Operations, Payment Systems & Organisational Milestones**:
    - Symmetric policy corridor retained at **50 bps** (SDF -25 bps, MSF +25 bps).
    - Call money trading hours extended to **7:00 PM**; repo/tri-party to **4:00 PM**.
    - EBLR-linked floating loans: 50.6% at PSBs and 89.2% at Private Banks.
    - UPI volume crossed **200 billion transactions** (+30% YoY), accounting for **86%** of all retail payment transactions; global merchant QR acceptance expanded to **8 countries**.
    - NGRTGS upgraded to **Version 4.0** on ISO 20022 XML standard; bank websites mandated migration to **.bank.in** domains.
    - Inward cheque clearing centralised at **Chennai Regional Office**.
    - Reserve Bank adopted **Utkarsh 2029** (3-year horizon: 2026–29); **Shri Shirish Chandra Murmu** appointed Deputy Governor succeeding M. Rajeshwar Rao; official podcast **'RBI Talks: From Paisa to Policy'** launched (Tagline: *"RBI Kehta Hai... Smart Bano, Cool Raho"*).
- **Master Files Harmonisation**: Aligned RBI Annual Report figures across 'IBPS_MAINS_35PLUS_MASTER_JAN_SEPT.md' and recompiled 'current_affairs_hub.html' and 'index.html' (502 verified clusters, zero heading anchor hashes).

## 🚀 [v1.4] — 2026-09-08

### 🏛️ May 2026 Master Dossier & Command Center Tab (`current_affairs_2026_may.md`)
- **Option A Implementation**: Created a dedicated standalone May 2026 master dossier (`current_affairs_2026_may.md`, **11 verified clusters**) and integrated it as a pre-rendered interactive month tab (`may-2026`) in the Rajputana Gazette Broadsheet Command Center.
- **Key May 2026 Developments Covered (Affairs Mind PIB May 2026 `Eo6A88dqaRg`)**:
  - **DFS Viability Plan 2.0 for RRBs**: 3-year extension (FY26 to FY28) institutionalizing performance monitoring across 30 standardized parameters spanning CRAR, CD ratio, NPA reduction, and PSL targets.
  - **Cabinet Kharif MSP 2026–27**: Common Paddy fixed at ₹2,441/qtl; Moong yields highest margin over cost of production at 61% (MSP ₹8,780/qtl); Medium staple cotton ₹8,267/qtl, Long staple ₹8,667/qtl; guaranteed ≥50% return on $A2+FL$.
  - **The Constitution (131st Amendment) Bill, 2026**: Proposes expanding Lok Sabha strength from 543 to 850 members (815 from States, 35 from UTs) under Article 81; eliminates Article 82 delimitation freeze to fast-track 33% Women's Reservation (*Nari Shakti Vandan Adhiniyam*).
  - **India-New Zealand Free Trade Agreement (FTA)**: New Zealand grants 100% duty-free access across all 8,284 tariff lines; India liberalizes 70.03% lines (95% trade value); NZ commits $20 Billion investment over 15 years; sensitive farm goods (dairy, edible oils, sugar) strictly excluded; Indian students granted 20 hrs/week work rights.
  - **MSJE 'JEEVAN' App & 'SHATAYU' Dashboard**: Union Minister Dr. Virendra Kumar launched JEEVAN app for senior citizen welfare schemes and SHATAYU dashboard for certified geriatric caregivers; Census 2027 toll-free helpline 1901.
  - **Draft Sugarcane (Control) Order 2026**: Proposes expanding minimum statutory radial distance between new sugar mills from 15 km to 25 km under Essential Commodities Act, 1955.
  - **Supreme Court 'One Case One Data' & 'Su Sahay' AI Chatbot**: Unified digital case identity interlinking Taluka, District, High Courts, and Supreme Court; 'Su Sahay' AI judicial assistant chatbot launched by CJI (developed by NIC).
  - **MDoNER Northeast Agrarian Missions**: Mizoram Ginger Mission (₹189.79 Cr outlay; pharma-grade Mizo Ginger with 3%–8% oleoresin); Nagaland Coffee Mission (₹175 Cr outlay; ₹49.48 Cr pilot cluster; *"Coffees of Nagaland – Taste of Eminence"*).
  - **Transgender Persons (Protection of Rights) Amendment Bill 2026**: Mandatory District Medical Board certification for issuing identity certificates by District Magistrates (revising pure self-declaration).
  - **Panchayat Advancement Index (PAI 1.0) & Cell Broadcast Emergency System**: PAI 1.0 by MoPR (Manipur highest Category D beginner Panchayats; Kerala, Tripura, Sikkim zero Category D); pan-India Cell Broadcast System launched for instant geo-fenced disaster alerts.
  - **MoHFW RBSK 2.0 (Child Digital Health Cards) & NHAI 'Project Saksham'**: RBSK screened 160.82 Cr children in decadal run (FY15–FY24); RBSK 2.0 deploys Digital Health Cards (ABHA-linked); NHAI trains rural women in highway operations with Vertis Foundation.

### 🏛️ June 2026 Comprehensive Master Dossier (`current_affairs_2026_june.md`)
- **Full Four-Video Exhaustive Consolidation**: Consolidated all high-yield developments from **Affairs Mind June Part 1 & RBI Circulars**, **Affairs Mind PIB June 2026**, **Affairs Mind June Part 2 Best 200 MCQs (`RemfuD4iNUQ`)**, and **Affairs Mind June Part 1 Best 200 MCQs (`wDCwkSPTwVw`)** into a unified, authentic Rajputana Gazette Broadsheet dossier containing **58 verified clusters** and integrated it into the interactive `jun-2026` tab.
- **Section 1: Banking, Monetary Policy & Financial Regulation (17 Clusters)**:
  - **ECLGS 5.0 Split Risk Weight**: 0% risk weight on 75% guaranteed portion (settled within 30 days) and 20% on remaining 25% exposure.
  - **ARIFAC National Platform**: Jointly managed by PCI and FCC with FIU-IND as official observer under PMLA 2002.
  - **Credit Guarantee Scheme for Microfinance Institutions 2.0 (CGSMFI-2.0)**: ₹20,000 Cr pool; NCGTC implemented; large MFI limit ₹1,000 Cr; tiered guarantees (80%/75%/70%).
  - **RBI Bank Lending to REITs & InvITs**: Banks permitted to lend to listed trusts with ≥80% completed assets; aggregate exposure capped at ≤49% of assets; capital charge effective 1 April 2027.
  - **RBI Master Directions on Authorisation of PSOs**: Perpetual licenses for compliant PSOs under Section 4 PSS Act; 1-year conditional renewal; FATF voting cap <20%.
  - **TReDS Directions 2026 & CERSAI Integration**: Net worth ₹25 Cr (by March 2028); mandatory CERSAI registration of invoice assignments; re-discounting authorized across 5 platforms.
  - **Revamped Kisan Credit Card (KCC) Scheme Directions 2026**: Collateral-free limit raised to ₹2 Lakh; standardized crop seasons (Short 12 mos, Long 18 mos); Flexi KCC (₹10k–₹50k); effective 1 January 2027.
  - **Lead Bank Scheme (LBS) Modernization**: Exclusive LDM per district; DDM from NABARD; SLBC Convenor designated as GM; CD ratio review norms (60%/40%/20%).
  - **Common Landing Portal for Unclaimed Financial Assets**: *"Aapki Poonji, Aapka Adhikar"*; convergence of RBI UDGAM, IEPFA, Bima Bharosa, and SEBI tracing engines.
  - **RBI Annual Report 2025–26**: Balance sheet ₹91.97 Lakh Cr (+20.6%); ₹1.09 Lakh Cr to Contingency Fund; foreign assets 70.9%; fraud ₹48,021 Cr (PSBs 74.5%).
  - **RBI 61st MPC Meeting**: Repo rate held at 5.25%, neutral stance; SDF 5.00%, MSF 5.50%; CRR 3.00%, SLR 18.00%; FY27 GDP 6.6%, CPI 5.1%.
  - **Special USD-Rupee Forex Swap Facilities**: 3–5 year FCNR(B) and ECB/OFCB swap facilities at fixed 1.5% p.a.; CRR/SLR exempt.
  - **FPI Sovereign Debt Tax Reforms & PROI Liberalisation**: FPI G-Sec tax Nil from 1 April 2026; PROI equity investment caps raised to 10% individual and 24% aggregate.
  - **REC-PFC Mega-Merger**: President approved legal merger of REC Limited into Power Finance Corporation (PFC), consolidating >₹10 Lakh Cr power financing assets.
  - **High-Level Financial Governance & Specialized Deposit Products**: Sanjay Lohiya nominated to Central Boards of RBI and SBI; Hitesh Joshi appointed CMD of GIC Re; Tushar Mehta reappointed Solicitor General; Bank of Baroda rolled out 'bob Legend FCNR(B)' and 'bob Golden Goal Deposit' (555 days, up to 7.40%); Federal Bank launched 'FCNR Max Deposit'.
  - **Swaminathan Janakiraman Reappointed as RBI Deputy Governor**: ACC extended tenure by 2 years; oversees Supervision, Inspection, and Financial Inclusion under statutory 4-Deputy Governor structure.
  - **RBI Payments Bulletin & Acquiring Shift**: Private banks expand credit card market share to 71.1% (PSBs 23.9%, foreign banks 3.8%); UPI QR terminals surge to 7,313 lakh nationwide.
- **Section 2: Capital Markets, SEBI & Pensions Regulation (4 Clusters)**:
  - **SEBI Trading Framework for ETFs**: Dynamic price bands (10% expandable to 20%); Commodity ETFs ±6% with no cap; Pre-open auction; VWAP last 30 mins; effective 1 Sept 2026.
  - **BSE Saatvik 100 Index**: India's first values-based ethical index from BSE 500; base year June 20, 2005 = 1000; Financial Services top weight (37.55%, HDFC Bank #1).
  - **IRDAI Working Group on AI (WG-AI)**: 7-member group chaired by Prof. Sandeep K. Shukla (IIIT Hyderabad).
  - **PFRDA NPS Reforms & StAR NPS Platform**: Surrender permitted for critical illness; 7-day CRA notification; StAR NPS assisted onboarding via BTPL (₹200 fee); Sandbox net worth ₹10 Lakh; Nuvama Wealth SEBI mutual fund approval.
- **Section 3: Multilateral Agreements, Cross-Border Payments & Global Trade (12 Clusters)**:
  - **Cross-Border UPI to Cambodia via KHQR & Bakong**: ACLEDA Bank partnership; Cambodia 9th UPI merchant country.
  - **Fintech Credit Innovation**: BharatPe launched 'BharatPe Flex' credit-on-UPI line with YES Bank (up to 45 days interest-free).
  - **Pine Labs 'P3P' Protocol**: India's first agentic payment protocol built on UPI enabling AI-driven autonomous machine-to-machine transactions within user spend limits.
  - **Skydo Canadian MSB Licence**: First Indian cross-border payments fintech to secure foreign regulatory licensing (FINTRAC MSB).
  - **Uzbekistan Admitted to New Development Bank (NDB)**: First Central Asian member; statutory BRICS 5 founding voting power permanently safeguarded above 55%.
  - **World Bank Sovereign Financing**: \$1.5 Billion for Private Sector Development Policy Financing (DPF) and ₹4,000 Crore loan for Jal Sanrakshit Haryana Project.
  - **Bangladesh 27th Member of IBCA**: Bangladesh ratifies International Big Cat Alliance for joint Sundarbans ecological stewardship (₹150 Cr outlay, 7 species).
  - **16th BRICS Agriculture Ministers' Meeting (Indore)**: Unanimous adoption of BRICS Indore Declaration across 4 strategic pillars.
  - **India-Oman CEPA Concluded**: Duty-free export access on 99.38% of Omani tariff lines (covering 98.08% of Indian shipments); liberalized import access on 77.79% of Indian lines; sensitive farm goods excluded.
  - **India-Vietnam \$629 Million BrahMos Supersonic Missile Deal**: Second export customer after Philippines; Mach 2.8–3.0 cruise speed; ~290 km export range.
  - **ICRIER AI & Trade Benchmark**: India ranks 5th in Global CHIPS AI Index; accounts for 19.9% of global AI users; 4th largest exporter of digitally delivered services (\$328 Bn).
  - **Bangladesh FM Khalilur Rahman Elected President of 81st UNGA**: Represents Asia-Pacific Group for 1-year term beginning September 2026.
- **Section 4: National Initiatives, Industrial Policy & Strategic Infrastructure (25 Clusters)**:
  - **MNRE Green Hydrogen Certification Scheme of India (GHCI)**: Well-to-gate GHG emission cap ≤2.0 kg CO2 eq/kg H2; 2030 target 5 MMT capacity & 125 GW RE; ₹8 Lakh Cr investment; BEE as Nodal Authority; 6 dedicated state policies.
  - **PLI Scheme for Textiles Rationalization**: Minimum investment thresholds halved (Part 1: ₹300 Cr → ₹150 Cr; Part 2: ₹100 Cr → ₹50 Cr); incremental turnover requirement reduced from 25% to 10% p.a.; Round 3 adds 8 MMF apparel and 9 MMF fabric HSN codes; 22 new applicants approved (₹12,822 Cr committed).
  - **WPI Base Revision & Targeted Mean Imputation**: DPIIT transitioning WPI to 2022-23 base year; replacing Carry Forward method with Targeted Mean Imputation for missing quotes; May 2026 headline inflation at 9.68%, food index at 4.49%.
  - **MHA & I4C GrM and MRM Portals**: Grievance Redressal Mechanism (GrM) for faster unfreezing/lien removal of innocent bank accounts; Money Restoration Module (MRM) for automated cyber fraud refunds via 14-digit acknowledgment number; National Helpline 1930; I4C established Oct 2018.
  - **First Municipality-Developed SEZ in India (Puducherry)**: Oulgaret Municipality develops Thattanchavady IT/ITES SEZ (India's first ULB-developed SEZ); PIPDIC develops Karasur Multi-Sector SEZ; National Health Accounts (NHA) FY23: GHE rose to 1.43% of GDP (48% of THE), OOPE plunged to 39.4% of THE.
  - **Mission Mausam & 'SkyCast' Fog Forecasting**: Outlay ₹2,000 Cr over 2 years (2024–2026); WiFEX experiment by IITM Pune & IMD yields SkyCast numerical prediction deployed at IGI Delhi and Jewar; up to 50% forecasting accuracy improvement.
  - **PM SVANidhi Revised Norms & 'Samadhan Didi' AI Chatbot**: Working capital loan tranches enhanced (Tranche 1: ₹15,000 / 12 mos; Tranche 2: ₹25,000 / 18 mos; Tranche 3: ₹50,000 / 36 mos); UPI-linked RuPay Credit Card (₹10,000–₹30,000, 5-yr validity); 'Samadhan Didi' AI voice chatbot launched for CPGRAMS at Kartavya Bhawan.
  - **Surha Taal Bird Sanctuary Declared Ramsar Wetland**: Oxbow lake of Ganga in Ballia, UP (Jai Prakash Narayan Bird Sanctuary); India ranks #1 in Asia and #3 globally (after UK 176 and Mexico 144); Top Indian states: Tamil Nadu (20), UP (13), Odisha (6).
  - **IN-SPACe TAF Grants & NITI Aayog Semiconductor Academy**: 3 space startups selected under TAF (Astrobase developing 800 kN reusable closed-cycle liquid rocket engine, SataSure, TM2SPACE); NITI Aayog proposes National Fab Academy with AICTE across 4 partner corridors (US, EU, Japan, South Korea).
  - **MCA Expands Schedule VII for Social Stock Exchanges**: Subscription to Zero Coupon Zero Principal (ZCZP) instruments on SSEs qualified as eligible CSR activity under Section 135; net profit threshold proposed to double to ₹10 Cr.
  - **MoSPI FY26 Annual Estimates & LPPI Port Awards**: Nominal GVA grew 9.1% to ₹314.87 Lakh Cr; Tertiary sector surged 11.0%, Manufacturing 10.7%; DPA Kandla wins Best Port (<0.5M TEU); Sikka Port tops Liquid Bulk Cargo.
  - **Investiture Ceremony 2026 & Clean Mobility Debut**: Gaganyaan astronaut Air Commodore Prasanth Balakrishnan Nair (*Papa*) conferred Kirti Chakra; INSV Tarini circumnavigators Lt Cdr Dilna K. & Lt Cdr Roopa A. conferred Shaurya Chakra; Nitin Gadkari launches Hero Splendor+ & HF Deluxe Flex Fuel (E20 to E85).
  - **Garden Reach Shipbuilders & Engineers (GRSE) Elevated to India's 29th Navratna CPSE**: Kolkata shipyard granted Navratna autonomy (up to ₹1,000 Cr or 15% net worth per project); delivered India's 1st warship INS Ajay in 1961; PM commissioned INS Dunagiri, INS Sanshodhak, INS Agray.
  - **Great Nicobar Island Greenfield Civil-Military Airport**: Union Cabinet cleared ₹13,000 Cr dual-use airport with 4,000m runway at strategic Malacca Strait entrance (handling 25% global trade / 80% East Asia oil).
  - **India's First Commercial Coal-to-Ammonium Nitrate Plant (Lakhanpur, Odisha)**: Developed by BCGCL (Coal India 51% + BHEL 49%) under 100 MT National Coal Gasification Mission 2030; President Murmu's native birthplace Pahadpur (Mayurbhanj) declared Model Solar Village.
  - **Defence Artillery & NDA Gender Inclusion**: Indigenous Garudastra 120mm vehicle-mounted mobile mortar system tested at Mhow, MP (by Nibe Limited); first historic batch of 17 women cadets commissioned from NDA Khadakwasla (148th Course).
  - **NIXI 23rd Foundation Day**: Launched 4 national platforms (IX Portal, myIRINN Portal, .IN Auction Portal, AI WHOIS Screening Platform).
  - **Extended PMSMA (E-PMSMA) & Assam-Nagaland Petroleum Pact**: MCP card risk stickers (Green = No Risk, Red = High-Risk Pregnancy); 4 additional monthly sessions, 45-day post-delivery tracking; Assam-Nagaland border oil MoU; IIT Delhi leads India in QS 2027 (Rank 118).
  - **Chenab-Beas Link Tunnel Project (₹2,352 Cr)**: 8.7 km trans-basin diversion tunnel in Lahaul-Spiti, HP executed by NHPC to divert surplus Chenab waters into Beas river system.
  - **FCI QR Code Tagging Scale-Up**: Mandatory encrypted 2D QR codes on grain gunny bags across Andhra Pradesh, Telangana, and Odisha for real-time farm-to-depot traceability.
  - **National Family Health Survey (NFHS-6)**: TFR stable at 2.0 (below 2.1 replacement level); CPR at 69.1%; rotavirus vaccination surges to 85.4%; full childhood immunization reaches 87.1%.
  - **West Bengal 'Annapurna Yojana' (₹3,000/Month)**: Flagship monthly direct benefit transfer replacing Lakshmi Bhandar; AIC T-Hub launches Cohort 3 of 'ORBIT' space accelerator; Indian Haj Mission wins two Labbaytum Awards.
- **Hub Architecture Updated**:
  - `generate_broadsheet_hub.mjs` enhanced to parse `current_affairs_2026_june.md`, render dedicated `juneDocument`, add `junMetricCards`, and populate interactive sidebar links. Total curated repository clusters expanded to **488 stories** (August: 133, July: 30, June: 58, Q1: 91, IBPS Master: 121, April: 55).
  - Verified **0 `#` heading anchor hashes** across both HTML builds.

---

## 🚀 [v1.3] — 2026-09-07

### 📚 Affairs Mind August 2026 (Part 1 & 2) 400 MCQs Master Integration
- **Merged 12 Verified News Clusters (+178 lines)**: Integrated high-yield banking, regulatory, cabinet, and index developments extracted and cross-verified from Affairs Mind August Part 1 & Part 2 Best 200 MCQs into `aug_ca_cgb1-31aug_pib1-18aug.md`.
  - **Regulatory & Banking Conduct**: RBI 6-month deferral of Basel Pillar 3 disclosure framework to 1 April 2027; RBI Directives on Loan Recovery & Recovery Agents (calling hours 8 AM–7 PM, DRA certification); Basel III Additional Tier-1 (AT-1) Bonds loss absorption norms (5.5% CET1 trigger).
  - **Macro Economy & Banking**: RBI Financial Stability Report (FSR) 29th Issue (GNPA at 12-year low of 2.8%, CRAR 16.8%, CET1 13.9%); appointment of P R Seshadri as MD & CEO of South Indian Bank (Thrissur, Kerala).
  - **Flagship Schemes & Infrastructure**: PM E-DRIVE Scheme (₹10,900 Cr replacing FAME-II, Aadhaar e-Vouchers); Rationalization of Central Agriculture Schemes into PM-RKVY & Krishonnati Yojana (₹1.01 Lakh Cr total outlay).
  - **Science & Climate**: Mission Mausam under MoES (₹2,000 Cr over 2 years, 50+ Doppler radars, IMD 150 years).
  - **Indices & Culture**: All India Survey on Higher Education (AISHE 2023-24: 4.33 Cr total enrolment, female GER 28.5% > male 28.3%, GPI 1.01); Sarnath Buddhist Site nominated to UNESCO Tentative List; World Wide Web Day (August 1); Ladakh declared 23 ancient monuments as protected heritage.
- **Standalone Reference File**: Created `affairs_mind_august_2026_mcqs_notes.md` cataloging all 12 items.
- **Broadsheet Hub Recompiled**: August coverage expanded from 121 to **133 curated stories**, with zero heading anchor hashes.

### 🏛️ July 2026 RBI & Macro Consolidated Master Dossier (`current_affairs_2026_july.md`)
- **Option B Implementation**: Created a dedicated standalone July 2026 dossier (`current_affairs_2026_july.md`, 533 lines) and integrated it as a fully interactive pre-rendered month tab (`jul-2026`) in the Rajputana Gazette Broadsheet Command Center.
- **30 High-Yield Topics Covered**:
  - **RBI Monthly Bulletin**: State of the Economy, core inflation deceleration to 3.1%, RBI-DPI surging to 445.50 (+12.6% YoY).
  - **External Debt Profile**: India's external debt at \$663.8 Bn (Debt-to-GDP at 18.7%, US Dollar denomination 53.8%).
  - **FPI Debt Limits & Export Realisation**: G-Sec FPI limit 6.0%, SDL limit 2.0%, FAR expanded to 15/30/40-yr tenors, export realisation window restored to 9 months.
  - **RBI Financial Inclusion (FI) Index**: Reached 64.2 (progressing towards 70.0); zero base year; Usage (45%) > Access (35%) > Quality (20%).
  - **RBI Master Direction on Wilful Defaulters & Large Defaulters**: ₹25 Lakhs threshold for wilful, ₹1 Crore for large defaulters; Identification Committee (ED + 2 GMs/DGMs) + Review Committee (MD/CEO + 2 independent directors); 6-month timeline post non-performing classification; 5-year bar on institutional credit post settlement.
  - **RBI Master Directions on Fraud Risk Management**: Operationalization of SC *Rajesh Agarwal* ruling; 21-day Show Cause Notice (SCN) and reasoned speaking order requirement; Special Committee of the Board for Monitoring and Follow-up of Frauds (SCBF).
  - **Liberalised Remittance Scheme (LRS) to IFSC GIFT City**: Permissible remittances up to \$250,000 to Foreign Currency Accounts (FCAs) in GIFT City; educational remittances to foreign universities.
  - **Prompt Corrective Action (PCA) Framework for UCBs**: Mandatory applicability to Tier 3 & Tier 4 UCBs (deposits > ₹100 Cr); risk thresholds tied to Net NPA >6% and CRAR breaches.
  - **Domestic Money Transfer (DMT) & Cash KYC**: ₹50,000/month cap on cash transfers, mandatory mobile OTP verification for remitter registration.
  - **Commercial Bank Dividend Declaration Norms**: CRAR ≥11.5% requirement, Net NPA <6%, dividend payout cap of 50%.
  - **Trade Receivables Discounting System (TReDS) & CERSAI**: Mandatory CERSAI registration to prevent duplicate factoring; RXIL (first platform, 2016); ₹25 Cr net worth compliance by 31 March 2027.
  - **Sahamati Foundation Recognized as SRO**: Official SRO for Account Aggregators; Section 8 entity, PRAVAAH portal application, 10% equity holding cap.
  - **Payment System Metrics (Card Divergence)**: Debit card spend contracted to ₹4.5 Lakh Cr due to UPI migration; credit card spend scaled past ₹18.8 Lakh Cr (private banks hold 71.1%, foreign banks dropped to 3.8%).
  - **Small Savings Schemes (SSS) Interest Rates**: Q2 FY25 rates; Sukanya Samriddhi & SCSS at 8.2%; PPF 7.1%; KVP 7.5% (115 months); Post Office MIS ₹9L/₹15L limits; Shyamala Gopinath formula.
  - **SBI ₹10,000 Cr Infrastructure Bonds**: 15-year maturity at 7.36% coupon; CRR & SLR reserve requirements exempt under RBI affordable housing/infra refinance norms.
  - **NABARD 43rd Foundation Day**: Celebrated 12 July 2024 (established 12 July 1982 under Act 61 of 1981 via B. Sivaraman Committee recommendation; RIDF cumulative disbursements > ₹5.5 Lakh Cr).
  - **Three New Criminal Laws Enacted**: BNS, BNSS, and BSA took effect nationwide on 1 July 2024.
  - **Public Examinations (Prevention of Unfair Means) Act & Rules**: Penalizes exam leaks; ₹1 Cr minimum fine & 5-10 yrs jail for syndicates; covers IBPS, UPSC, SSC, RRB, NTA.
  - **Vadhavan Mega Major Port**: ₹76,220 Cr greenfield port in Palghar, Maharashtra (SPV: JNPA 74% + MMB 26%).
  - **NITI Aayog SDG India Index 2023–24**: Composite score improved to 67; Uttarakhand & Kerala tied for #1 rank (score 79); Bihar lowest (57).
  - **Global Peace Index 2024 (IEP Sydney)**: India ranked 116th; Iceland #1 most peaceful for 17 consecutive years.
  - **Global Liveability Index 2024 (EIU)**: Vienna #1 (score 98.4, 3rd year running); Damascus 173rd (bottom); New Delhi & Mumbai tied at 140th.
  - **The State of Food Security and Nutrition in the World (SOFI) Report**: FAO/UN joint report; 733M people facing hunger (1 in 11); 582M still undernourished by 2030 (SDG 2 gap).
  - **Sustainable Development Report 2024 (SDR — SDSN)**: India ranked 109th (score 64.0); Finland #1 (4th year running); South Sudan 167th.
  - **Performance Grading Index for Districts (PGI-D)**: 600 points across 83 indicators; Daksha (>90%) & Utkarsh (81-90%); Punjab & Chandigarh lead.
  - **Henley Passport Index 2024 (July Edition)**: India 82nd (58 visa-free destinations); Singapore #1 (195 destinations); Afghanistan 103rd (26 destinations).
  - **National Statistics Day (June 29) & P.C. Mahalanobis Legacy**: Father of Indian Statistics; Second Five-Year Plan heavy industry model; Indian Statistical Institute (1931).
  - **National Fish Farmers' Day (10 July) & PMMSY**: Honors Dr. Hiralal Chaudhuri & Dr. K.H. Alikunhi (1957 hypophysation); India #2 fish producer (~8% share); PMMSY ₹20,050 Cr.
  - **Commemorative Days & Milestones**: National Doctors' Day (1 July, Dr. B.C. Roy); Kargil Vijay Diwas (26 July, 25th Silver Jubilee); Global Tiger Day (29 July, 3,682 tigers in India = 75% of world population).
  - **Project Finance Draft Guidelines**: 5% standard asset provisioning during construction phase; DCCO compliance.
- **Hub Architecture Updated**:
  - `generate_broadsheet_hub.mjs` enhanced to parse `current_affairs_2026_july.md`, render dedicated `julyDocument`, add `julMetricCards`, and populate interactive sidebar links.
  - Heading anchor hashes strictly eliminated (0 `#` symbols).

---

## 🚀 [v1.2] — 2026-09-07

### 📰 August 2026 PIB Integration (19th–27th August)
- **Merged PIB Releases**: Extracted and synthesized key dispatches from official PIB daily releases dated 19th to 27th August 2026 into `aug_ca_cgb1-31aug_pib1-18aug.md` (+242 lines, title updated to *1st–31st August 2026, incl. PIB 1st–27th Aug*). Total August items expanded to 121 verified news stories.
- **Standalone PIB Document**: Created `pib_19_27_august_2026.md` cataloging raw notes categorized across canonical exam sections.
- **Broadsheet Hub Compilation**: Recompiled `current_affairs_hub.html` and `index.html` with all newly added August PIB stories.

### 🧹 Permanent Heading Hash (`#`) Purge & GitHub Pages Deployment Fix
- **Root Cause Identified**: GitHub Pages was serving an older build (commit `b3aceab` v1.0) because without a `.nojekyll` file, GitHub's default Jekyll builder stalled on the large single-page HTML file and failed to deploy commit `136e80f` (v1.1).
- **Added `.nojekyll`**: Bypasses Jekyll processing completely, forcing GitHub Pages to serve `index.html` directly from the static file server.
- **Double-Lock Heading Anchor Removal**:
  - Pre-build parser option: `permalink: false` set on `markdown-it-anchor`.
  - Build-time sanitize pass: Regex-stripped all `<a class="header-anchor">` tags from the final generated HTML before saving.
  - Hardened CSS: Added explicit `content: none !important;` and `display: none !important;` rules for `h1..h6` pseudo-elements and anchors.

---

## 🚀 [v1.1] — 2026-09-06

### 🎯 35+ Strike File Exam Angle Streamlining
- **Removed Redundant Trap Labels**: Cleaned `IBPS_MAINS_35PLUS_MASTER_JAN_SEPT.md` (and modular source generators `ibps_full_sec*.mjs`) by stripping `[THE EXAMINER'S TRAP MATRIX]` and repetitive `Trap A / Trap B / Trap C` bullet prefixes across all 121 case items.
- **Unified Clean Syntax**: All exam angle blocks now begin cleanly with `🎯 Exam Angle →` followed directly by specific topic takeaway bullets (e.g., `• Corridor Math: ...`, `• Stance Confusion: ...`, `• Target MCQ Form: ...`).
- **Preserved 100% Core Fact Discipline**: All distractor logic, numerical thresholds, committee origins, and model MCQ questions remain intact without loss of information.

### 🎨 Broadsheet Hub & Typography
- **Disabled Autolinking (`linkify: false`)**: Set `linkify: false` across both build-time and client-side parsers to prevent proper nouns containing periods (such as `MuleHunter.AI`, `Vyoma.AI`, and `maandhan.in`) from converting into unintentional blue underlined external hyperlinks.
- **Eliminated Heading Anchor Permalinks**: Removed the unsightly `#` symbols appearing after section headings across all documents by removing the `linkInsideHeader` permalink option in `converter.js` and adding defensive CSS rules (`.header-anchor, .anchor-symbol { display: none !important; }`).
- **Preserved TOC & Navigation**: All slug IDs (`id="1-rbi-policy..."`) remain intact so table of contents, sidebar index, and search jump links function smoothly.
- **Web App Mirror Sync**: Synchronized `current_affairs_hub.html` and `index.html` with all v1.1 refinements.

---

## 🚀 [v1.0] — 2026-09-06

### Initial Master Release
- **👑 35+ Strike File**: Standalone master dossier (`IBPS_MAINS_35PLUS_MASTER_JAN_SEPT.md`) with 121 verified news stories + 5 comprehensive reference strike grids (Sports, Days, UNESCO/Ramsar, Defence, Static Banking).
- **April 2026 Dossier**: Unified Parts 1 & 2 into `current_affairs_2026_april.md` with 55 news items organized across all 10 canonical sections.
- **Q1 2026 Consolidated Dossier**: `current_affairs_2026_q1_jan_mar.md` with 91 news items across 10 sections.
- **August 2026 Dossier**: `aug_ca_cgb1-31aug_pib1-18aug.md` with 110 news items.
- **Rajputana Gazette Broadsheet Hub**: Interactive command center (`current_affairs_hub.html` / `index.html`) featuring:
  - Lexend font applied across body, headings, cards, and UI.
  - Non-sticky header with full-width broadsheet dateline strip.
  - Fullscreen Reading Mode (Shortcut: `F`).
  - Terracotta single-line exam boxes (`🎯 EXAM ANGLE`) with inline study mastery checkboxes.
  - Instant multi-month switcher (`👑 35+ Strike File`, `August 2026`, `April 2026`, `Q1 (Jan–Mar)`).
  - Collapsible sidebar with real-time topic filtering.
- **Repository Infrastructure**: Clean `.gitignore` ignoring backup/cache files and `README.md` establishing the strict approval-first push protocol.
