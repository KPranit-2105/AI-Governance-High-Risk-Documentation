# Project 5: High-Risk AI Documentation & Conformity Pack

**GRC Domain:** EU AI Act Technical Documentation & Conformity Assessment  
**Role Simulated:** Lead AI Compliance Architect / Technical Auditor  
**Framework/Regulation:** EU AI Act (Articles 9–17, 43, 47, Annex IV, Annex V) · NIST AI RMF · ISO/IEC 42001  
**Project Type:** Fictional Portfolio Case Study (Audit-Defensible Artefact Pack)  

---

## Executive Summary & Recruiter Quick-Reference

This project delivers the complete 7-part Technical Documentation & Conformity Pack for **HireAssist Pro** (`NS-AI-008`), an enterprise AI recruitment screening tool deployed at **NorthStar Financial Services**. Designed to satisfy EU AI Act Articles 9–17 provider and deployer obligations, this pack contains system specifications, risk management summaries, data governance records, human oversight protocols, JSON audit logging schemas, post-market performance plans, and an official EU Declaration of Conformity.

All artefacts are provided in Markdown (`.md`), Word Document (`.docx`), and CSV Spreadsheet (`.csv`) formats.

---

## Business Problem & Scenario

Following the governance review of TalentMatch AI in Projects 2 and 3, NorthStar procured an upgraded AI recruitment solution, HireAssist Pro (`NS-AI-008` v3.1.2), from HireFlow Technologies Ltd. To satisfy EU AI Act Annex III Category 4(a) requirements prior to production go-live, NorthStar's AI Governance Programme Office compiled a comprehensive, audit-defensible Article 11 technical documentation pack combining provider technical specifications with deployer operational controls.

---

## Objective & Scope

- **Objective:** Build a complete 7-document conformity dossier demonstrating compliance across risk management (Art. 9), data governance (Art. 10), technical documentation (Art. 11), logging (Art. 12), transparency (Art. 13), human oversight (Art. 14), accuracy/robustness (Art. 15), post-market monitoring (Art. 17), and Declaration of Conformity (Art. 47).
- **Scope:** HireAssist Pro v3.1.2 SaaS integration across NorthStar's Workday ATS in Germany and the Netherlands.

---

## Artefact Inventory (Markdown, Word & CSV)

### 1. Markdown & Word Reports
| Document Title | Primary Markdown File | Word Document (`.docx`) | Primary Regulatory Reference |
|---|---|---|---|
| **Conformity Pack Overview** | [`README.md`](./README.md) | [`README.docx`](./README.docx) | Executive overview, methodology, article mapping |
| **Doc 1: System Intended Purpose** | [`01-intended-purpose.md`](./01-intended-purpose.md) | [`01-intended-purpose.docx`](./01-intended-purpose.docx) | Art. 11, Annex IV §1 & §2 |
| **Doc 2: Risk Management Summary** | [`02-risk-management-summary.md`](./02-risk-management-summary.md) | [`02-risk-management-summary.docx`](./02-risk-management-summary.docx) | Article 9 (Risk Management System) |
| **Doc 3: Data & Data Governance** | [`03-data-governance.md`](./03-data-governance.md) | [`03-data-governance.docx`](./03-data-governance.docx) | Article 10 (Data Governance) |
| **Doc 4: Human Oversight Mechanisms** | [`04-human-oversight.md`](./04-human-oversight.md) | [`04-human-oversight.docx`](./04-human-oversight.docx) | Article 14 (Human Oversight) |
| **Doc 5: Logging & Traceability** | [`05-logging-traceability.md`](./05-logging-traceability.md) | [`05-logging-traceability.docx`](./05-logging-traceability.docx) | Article 12 (Record-Keeping) |
| **Doc 6: Performance & Post-Market Monitoring** | [`06-performance-monitoring.md`](./06-performance-monitoring.md) | [`06-performance-monitoring.docx`](./06-performance-monitoring.docx) | Article 15 & Article 17 |
| **Doc 7: EU Declaration of Conformity** | [`07-declaration-of-conformity.md`](./07-declaration-of-conformity.md) | [`07-declaration-of-conformity.docx`](./07-declaration-of-conformity.docx) | Article 47 & Annex V |

### 2. Tabular Data & CSV Spreadsheets
| Dataset Title | CSV File (`.csv`) | Primary Content |
|---|---|---|
| **System Identification Metadata** | [`system-identification-metadata.csv`](./system-identification-metadata.csv) | System ID, provider, deployer, version, Annex III category |
| **Known Limitations & Mitigations** | [`known-limitations-and-mitigations.csv`](./known-limitations-and-mitigations.csv) | Technical limitations, descriptions, and operational mitigations |
| **Pre-Deployment Risk Evaluations** | [`pre-deployment-risk-evaluations.csv`](./pre-deployment-risk-evaluations.csv) | Mandatory pre-deployment evaluation gates and standards |
| **Foreseeable Misuse Scenarios** | [`foreseeable-misuse-scenarios.csv`](./foreseeable-misuse-scenarios.csv) | Misuse scenarios, risk impact, and preventative controls |
| **Training Dataset Description** | [`training-dataset-description.csv`](./training-dataset-description.csv) | Training data source, scope, volume, and preprocessing |
| **Data Relevance & Representativeness** | [`data-relevance-representativeness.csv`](./data-relevance-representativeness.csv) | Evaluation of data representativeness across target jurisdictions |
| **GDPR Data Categories Processed** | [`gdpr-data-categories-processed.csv`](./gdpr-data-categories-processed.csv) | Personal data fields ingested and minimisation status |
| **GDPR Lawful Basis Mapping** | [`gdpr-lawful-basis-mapping.csv`](./gdpr-lawful-basis-mapping.csv) | Legal basis for data processing under GDPR Article 6 & 9 |
| **Data Governance Controls** | [`data-governance-controls.csv`](./data-governance-controls.csv) | Data quality, bias checking, and sanitization controls |
| **System Features Supporting Oversight** | [`system-features-supporting-oversight.csv`](./system-features-supporting-oversight.csv) | Technical UI/UX features designed for human oversight |
| **Oversight Effectiveness KPIs** | [`oversight-effectiveness-kpis.csv`](./oversight-effectiveness-kpis.csv) | Metrics measuring reviewer override and review time |
| **Log Event Requirements** | [`log-event-requirements.csv`](./log-event-requirements.csv) | Mandatory audit log event categories under Article 12 |
| **Provider Logging Architecture** | [`provider-logging-architecture.csv`](./provider-logging-architecture.csv) | Vendor API layer log retention and access rights |
| **Deployer Logging Architecture** | [`deployer-logging-architecture.csv`](./deployer-logging-architecture.csv) | NorthStar ATS layer audit log retention and storage |
| **Log Integrity Controls** | [`log-integrity-controls.csv`](./log-integrity-controls.csv) | Encryption, immutability, and access security controls |
| **Log Review Cadence** | [`log-review-cadence.csv`](./log-review-cadence.csv) | Active log monitoring frequency and owners |
| **Logging Limitations & Gaps** | [`logging-limitations-and-gaps.csv`](./logging-limitations-and-gaps.csv) | Technical logging constraints and operational mitigations |
| **Model Performance KPIs** | [`model-performance-kpis.csv`](./model-performance-kpis.csv) | Shortlist acceptance, conversion, and accuracy thresholds |
| **Fairness Monitoring KPIs** | [`fairness-monitoring-kpis.csv`](./fairness-monitoring-kpis.csv) | Demographic parity ratio ($\ge 0.80$) and proxy metrics |
| **Oversight Quality KPIs** | [`oversight-quality-kpis.csv`](./oversight-quality-kpis.csv) | Override rate ranges (10–40%) and review time alerts |
| **Monitoring Cadence & Owners** | [`monitoring-cadence-and-owners.csv`](./monitoring-cadence-and-owners.csv) | Daily, monthly, quarterly, and annual review owners |
| **Model Revalidation Triggers** | [`model-revalidation-triggers.csv`](./model-revalidation-triggers.csv) | Quantitative triggers initiating model re-testing |
| **Conformity Assessment Summary** | [`conformity-assessment-summary.csv`](./conformity-assessment-summary.csv) | Article 9–17 audit compliance status matrix |

---

## Key Findings & Conformity Verdict

- **Conformity Pathway:** Internal Control Procedure under Article 43(2) and Annex VI.
- **Human Oversight Enforced:** 100% of candidate rejections and shortlists require active HR coordinator sign-off (`CTRL-POL-005`); passive acceptance is technically blocked.
- **Log Traceability:** Full decision reconstruction capability combining input CV hashes, AI confidence scores, explanation strings, reviewer override rationales, and timestamps.

---

## Skills Demonstrated

- **Conformity Architecture:** Compiling full Annex IV technical documentation packs for EU regulatory submission.
- **Technical Log Design:** Structuring JSON audit log schemas matching Article 12 record-keeping requirements.
- **Post-Market Monitoring:** Designing demographic parity metrics ($	ext{DPR} \ge 0.80$) and model drift revalidation triggers.
- **Provider-Deployer Synthesis:** Blending vendor model card documentation with organizational operational controls.

---

## Portfolio Disclaimer

*This project is a simulated GRC portfolio case study developed for demonstration purposes. All company names, employee personas, and system telemetry are fictional. Real-world regulatory compliance requires formal legal and technical evaluation by qualified professionals.*
