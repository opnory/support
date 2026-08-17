# Opnory Legal Terms

**Enterprise Software License and Subscription Terms**

Effective Date: [EFFECTIVE DATE]
Last Updated: August 17, 2026

**DRAFT FOR LEGAL REVIEW**

These terms govern the licensing and use of Opnory software ("Software") and the Opnory Cloud hosted service ("Cloud Service"). By installing, accessing, or using the Software or Cloud Service, you accept these terms. If you do not agree, you must not use the Software or Cloud Service.

The provider is **Raell Dottin, offering software and services under the name Opnory**. Opnory is a product/trade name. No LLC, corporation, or registered DBA is claimed.

---

## 1. Opnory Editions

Opnory is available in two distinct editions with different licensing and service models:

| Edition | Delivery Model | Governing Terms |
|---------|---------------|-----------------|
| **Opnory Open Source** | Self-hosted — you download, install, and operate the Software on infrastructure you select and control | **BSD-2-Clause open-source license** (see Section 2) |
| **Opnory Cloud** | Hosted subscription — Opnory operates the application using third-party cloud infrastructure | **Subscription terms** (see Section 3) |

These editions have different legal relationships, responsibilities, and data-processing practices. The Privacy Policy (PRIVACY.md) describes data handling for each edition separately.

---

## 2. Opnory Open Source — BSD-2-Clause License

### 2.1 License Grant

The source code and associated files designated as "Opnory Open Source" are licensed under the **BSD-2-Clause** license (SPDX: `BSD-2-Clause`), also known as the Simplified BSD License or FreeBSD License.

> **[OPEN SOURCE LICENSE TO BE SELECTED]** — The above reflects the intended license. The final license text must be confirmed and an unmodified `LICENSE` file placed in the repository root before any public release as open source. Do not treat this document as the license itself.

### 2.2 BSD-2-Clause Summary (Informational)

The BSD-2-Clause license permits, among other things:

- Commercial and non-commercial use
- Modification and creation of derivative works
- Redistribution in source or binary form
- Use within proprietary products

**Requirements:** You must retain the original copyright notice, the list of conditions, and the disclaimer in all copies or substantial portions of the Software.

**No warranty:** The Software is provided "as is," without warranty of any kind.

### 2.3 Precedence of Open-Source License

For code distributed under the BSD-2-Clause license, **the BSD-2-Clause license governs and takes precedence** over any conflicting restrictions in this document. This document does not override or limit rights granted by the applicable open-source license.

### 2.4 What the Open-Source License Does Not Include

The open-source license does **not** automatically grant:

- Access to Opnory Cloud (the managed hosted service)
- Paid technical support, SLAs, or managed operations
- Managed infrastructure, backups, or disaster recovery
- Managed upgrades or deployment assistance
- Commercial support, training, or professional services
- Rights to use Opnory trademarks, logos, or branding to imply endorsement
- Rights to represent modified or redistributed versions as official Opnory releases

### 2.5 Self-Hosted Responsibilities

If you self-host Opnory Open Source, **you are responsible for**:

- Selecting, provisioning, and securing infrastructure (servers, VMs, cloud accounts, Kubernetes clusters, etc.)
- Operating system, container runtime, database, and TLS configuration
- Credentials, secrets, and key management
- Backups, disaster recovery, and business continuity
- Availability, monitoring, and alerting
- Applying updates, patches, and security fixes
- Network controls, firewalls, and access policies
- Integration permissions and third-party credentials
- Compliance with laws applicable to your deployment and data

Opnory (Raell Dottin) does **not** operate, monitor, back up, secure, or control independently self-hosted deployments. The self-hosted operator assumes all operational risk.

### 2.6 Telemetry and External Calls (Self-Hosted)

> **[SELF-HOSTED TELEMETRY AND EXTERNAL DATA FLOWS TO BE CONFIRMED]**

The self-hosted Software may, depending on configuration and implementation, transmit information to external destinations including:

- Configured AI/model providers (for AI features)
- Configured third-party integrations (Slack, identity providers, ticketing systems, cloud APIs, etc.)
- Update-check or license-check endpoints (if implemented)
- Crash reporting or telemetry endpoints (if implemented)
- Opnory support/diagnostics endpoints (if implemented and enabled)

**Do not assume** that a self-hosted deployment sends no data outside your infrastructure until the actual code behavior is verified. Review the source code and configuration before deploying in environments with strict data-locality requirements.

---

## 3. Opnory Cloud — Subscription Terms

### 3.1 Subscription Access

Subject to these terms and an active subscription, Opnory grants you a **limited, non-exclusive, non-transferable right to access and use the Cloud Service** for your internal business purposes during the subscription term.

**This is not a perpetual license.** The Cloud Service is provided as a subscription. When the subscription ends, your access to the Cloud Service ends, subject to data export and deletion provisions below.

### 3.2 Authorized Users

You may permit your employees, contractors, and agents ("Authorized Users") to access the Cloud Service on your behalf, subject to any seat or usage limits in your subscription plan. You are responsible for:

- Provisioning and deprovisioning Authorized User accounts
- Assigning appropriate roles and permissions
- Securing administrator access and credentials
- Authorized User compliance with these terms

### 3.3 Cloud Infrastructure

The Cloud Service is operated on **[CLOUD INFRASTRUCTURE PROVIDER TO BE CONFIRMED]** (e.g., AWS, Google Cloud, Azure, or similar). Hosting regions and data residency commitments are **[HOSTING REGIONS / DATA RESIDENCY TO BE CONFIRMED]**.

Opnory may change infrastructure providers or regions with reasonable notice. Such changes do not constitute a material modification of these terms.

### 3.4 Customer Responsibilities (Cloud)

You are responsible for:

- Your Authorized Users' activities
- Accuracy and legality of Customer Data you submit
- Configuring integrations, access policies, and approval workflows
- Administrator credentials and privileged-access governance
- Compliance with laws applicable to your use of the Cloud Service
- Promptly reporting security incidents related to your account

### 3.5 Subscription Lifecycle

| Event | Description |
|-------|-------------|
| **Activation** | Access begins upon subscription confirmation and payment (if applicable) |
| **Renewal** | **[RENEWAL BEHAVIOR TO BE CONFIRMED]** — auto-renewal, manual renewal, or notice periods |
| **Cancellation** | You may cancel at any time; access continues until the end of the current paid period unless otherwise stated |
| **Expiration** | Access terminates at the end of the subscription term if not renewed |
| **Suspension** | Opnory may suspend access for: (a) security threats, (b) material breach, (c) non-payment, or (d) legal requirement |
| **Termination** | Either party may terminate for uncured material breach with 30 days' written notice. Opnory may terminate immediately for fraud, illegal activity, or security emergency. |

### 3.6 Effect of Termination / Expiration

Upon termination or expiration of your Cloud Service subscription:

- Your access to the Cloud Service ceases
- You may export your Customer Data during the **[POST-TERMINATION EXPORT PERIOD TO BE DEFINED]** window
- Opnory will delete your Customer Data from production systems within **[POST-TERMINATION DELETION PERIOD TO BE DEFINED]**
- Backups containing your data will be retained for **[BACKUP RETENTION PERIOD TO BE DEFINED]** and then securely destroyed
- Sections 2.4, 3.4, 3.6, 4, 5, 6, 7, 8, 9, 10, 11, and 12 survive termination

### 3.7 Service Changes

Opnory may modify the Cloud Service (features, integrations, APIs, UI, performance) over time. Material adverse changes will be communicated with reasonable notice. Continued use after notice constitutes acceptance.

### 3.8 Maintenance and Support

Opnory Cloud subscriptions may include support according to the applicable plan. **[SUPPORT TERMS TO BE DEFINED IN ORDER FORM OR PLAN DETAILS]**. Maintenance windows, upgrade schedules, and deprecation policies will be communicated via the service or email.

### 3.9 Availability

Opnory will use commercially reasonable efforts to maintain Cloud Service availability. **[CLOUD SERVICE SLA TO BE DEFINED]** — no uptime guarantee or service-level agreement is provided unless explicitly included in a signed Order Form or enterprise agreement.

### 3.10 Third-Party Integrations

The Cloud Service may integrate with third-party services (Slack, Microsoft Entra ID, Okta, GitHub, Jira, ServiceNow, AWS, Google Workspace, etc.). Each integration operates under its own terms. Opnory cannot guarantee uninterrupted availability of third-party services.

---

## 4. Customer Data Ownership

**You retain all rights in your Customer Data** — regardless of edition.

- **Open Source:** Data in your self-hosted deployment remains under your control.
- **Cloud:** Data processed by the Cloud Service remains yours. Opnory claims no ownership.

Opnory does not sell Customer Data. Opnory does not use Customer Data for advertising or profiling.

---

## 5. Artificial Intelligence Features

Both editions may incorporate AI features (request interpretation, classification, knowledge retrieval, answer generation, summarization, troubleshooting recommendations, access-request preparation, workflow assistance).

### 5.1 AI Output Disclaimer

AI output is probabilistic and may be incorrect, incomplete, outdated, misinterpreted, or unsuitable for your environment. **Do not rely on AI-generated output for critical decisions without human review.**

> **Opnory may recommend, prepare, or initiate actions, but you remain responsible for your authorization policies, approval processes, system configuration, and privileged access decisions.**

Your identity systems, IAM platforms, access-governance systems, administrators, approval workflows, and policies are the authoritative source for authorization decisions. Opnory is not a substitute for your authorization authority.

### 5.2 AI Data Flows by Edition

| Edition | AI Provider Configuration | Data Sent to AI Provider |
|---------|---------------------------|--------------------------|
| **Open Source** | You may configure your own model/API provider (depending on implementation) | Determined by your configuration |
| **Cloud** | Opnory selects and configures AI providers as part of the hosted service | Request context, conversation history, knowledge snippets, integration metadata, identity context |

### 5.3 AI Provider Commitments

> **[AI PROVIDER DATA HANDLING TO BE CONFIRMED]** — The specific model provider(s), their data retention, training exclusion, deletion, residency, and enterprise guarantees must be confirmed before finalizing these terms.

> **[AI DATA USE POLICY MUST BE CONFIRMED]** — Whether Customer Data is used for model training/fine-tuning by Opnory or its providers must be confirmed by architecture and contract.

**Recommended policy (not yet a promise):** *Customer Data will not be used by Opnory to train generalized AI models by default.* Implementation and provider contracts must enforce this before the Privacy Policy makes this representation.

---

## 6. Knowledge and External Information

Both editions may retrieve and reference your knowledge-base content, policies, procedures, vendor documentation, and approved public information. You acknowledge that external information can change, third-party information may be inaccurate, and your documentation may supersede general vendor guidance.

---

## 7. Confidentiality

Each party protects the other's Confidential Information using reasonable care. Confidential Information includes: customer knowledge bases, credentials, security configurations, Customer Data, non-public Opnory technology/roadmap, pricing, commercial terms, and information designated as confidential or reasonably understood to be confidential.

Exclusions: independently developed information, publicly available information, information lawfully received from third parties, and legally compelled disclosures (with notice where permitted).

> **[COUNSEL REVIEW REQUIRED]** — Enterprise customers may negotiate separate NDAs or MSAs.

---

## 8. Security Responsibilities

### 8.1 Opnory Cloud

Opnory implements reasonable technical and organizational safeguards for the Cloud Service components under its operational control, which may include: encryption in transit (TLS 1.2+), encryption at rest, role-based access controls, vulnerability management, incident detection/response, and regular security assessments.

Opnory does **not** claim security certifications (SOC 2, ISO 27001, FedRAMP, HIPAA, PCI DSS, etc.) unless independently verified and documented.

### 8.2 Self-Hosted

The self-hosted operator is responsible for infrastructure and deployment security controls under its control (see Section 2.5). Opnory is responsible for security vulnerabilities in its own application code.

---

## 9. Warranty

**OPEN SOURCE:** The BSD-2-Clause license includes its own warranty disclaimer. The Software is provided "as is" without warranty of any kind.

**CLOUD SERVICE:** Opnory warrants that the Cloud Service will substantially conform to its documentation when used as authorized. Opnory's sole obligation for breach is to use commercially reasonable efforts to correct the non-conformity, or if not commercially reasonable, to terminate the subscription and refund a pro-rata portion of prepaid fees.

**DISCLAIMER (CLOUD):** EXCEPT AS EXPRESSLY WARRANTED ABOVE, THE CLOUD SERVICE IS PROVIDED "AS IS." OPNORY DISCLAIMS ALL OTHER WARRANTIES, INCLUDING MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, TITLE, NON-INFRINGEMENT, UNINTERRUPTED OPERATION, AND ACCURACY OF AI-GENERATED OUTPUT.

> **[COUNSEL REVIEW REQUIRED]** — Warranty terms materially affect enterprise sales.

---

## 10. LIMITATION OF LIABILITY

**TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW:**

- NEITHER PARTY'S AGGREGATE LIABILITY WILL EXCEED **[LIABILITY CAP]**.
- NEITHER PARTY WILL BE LIABLE FOR INDIRECT, INCIDENTAL, SPECIAL, CONSEQUENTIAL, OR PUNITIVE DAMAGES, OR LOSS OF PROFITS, REVENUE, DATA, OR BUSINESS OPPORTUNITY.

Exclusions: payment obligations, confidentiality obligations, indemnification, gross negligence, willful misconduct, fraud, and liabilities that cannot be excluded by law.

> **[COUNSEL REVIEW REQUIRED]** — Liability limitations require counsel review for enforceability.

---

## 11. Indemnification

**Opnory will indemnify you** against third-party claims alleging the Software/Cloud Service (as provided by Opnory and used within scope) infringes a valid patent, copyright, or trademark, provided you: (a) promptly notify Opnory, (b) grant Opnory sole control of defense/settlement, (c) provide reasonable cooperation. Opnory may: (i) procure continued-use rights, (ii) replace/modify to be non-infringing, or (iii) terminate and refund pro-rata fees.

**You will indemnify Opnory** against third-party claims arising from: (a) your Customer Data, (b) your misuse beyond license/scope, (c) your violation of third-party integration terms, (d) your authorization policies, approval workflows, or access decisions.

> **[COUNSEL REVIEW REQUIRED]** — Indemnification provisions require counsel review.

---

## 12. Export and Sanctions

You will comply with applicable export control laws, sanctions, and trade restrictions (U.S. EAR, ITAR, OFAC). You represent you are not in an embargoed jurisdiction or on a restricted-party list. The Software/Cloud Service may not be exported in violation of applicable law.

---

## 13. Governing Law

These terms are governed by the laws of **[GOVERNING STATE]**, without regard to conflict-of-laws principles. The parties consent to the exclusive jurisdiction of state and federal courts in **[GOVERNING COUNTY]**.

> **[DISPUTE RESOLUTION APPROACH REQUIRES BUSINESS DECISION AND COUNSEL REVIEW]** — Mandatory arbitration, class-action waivers, jury waivers, or other mechanisms are not included by default. Make a deliberate business decision with counsel input.

---

## 14. Order of Precedence

In case of conflict (highest to lowest):

1. Executed Order Form(s) / Enterprise Agreement
2. These Terms
3. Documentation
4. Website terms

---

## 15. General Provisions

- **Entire Agreement.** These terms and incorporated Order Forms constitute the entire agreement.
- **Amendments.** Must be in writing, signed by both parties.
- **Waiver.** Failure to enforce does not waive rights.
- **Severability.** Invalid provisions are severed; remainder remains enforceable.
- **Assignment.** Neither party may assign without prior written consent, except to an affiliate or successor in merger/acquisition (with notice).
- **Force Majeure.** No liability for delays beyond reasonable control.
- **Notices.** Written, delivered to the email addresses or addresses in the Order Form.

---

## 16. Intellectual Property and Trademarks

- **Copyright/Open Source:** The BSD-2-Clause license governs open-source code rights.
- **Trademarks:** Opnory trademarks, logos, and branding are owned by Raell Dottin. The open-source license does **not** grant permission to: (a) falsely claim a fork is an official Opnory release, (b) imply endorsement by Opnory, or (c) misuse Opnory trademarks.
- **Third-Party Components:** Open-source components included in the Software are governed by their respective licenses.

> **[TRADEMARK POLICY TO BE CREATED]** — Formal trademark usage guidelines to be published separately.

---

## 17. Contributions

If the open-source repository accepts third-party contributions, a contribution policy is needed.

> **[CONTRIBUTION POLICY TO BE DECIDED: CLA / DCO / OTHER]** — No policy currently selected. Must be decided before accepting external contributions.

---

## 18. Security Vulnerability Reporting

> **[SECURITY CONTACT TO BE ESTABLISHED: security@opnory.com OR SECURITY.md]** — A vulnerability disclosure channel should be established before production use.

---

## 19. Contact

**Opnory — Raell Dottin**  
support@opnory.com  
privacy@opnory.com  
https://opnory.com

> **[COUNSEL REVIEW: determine whether a postal/legal-notice address must be published before final release or commercial launch.]** — The absence of a postal address may not be universally sufficient under all applicable laws, payment-provider requirements, tax requirements, customer contracts, or future jurisdictions.

---

*End of Opnory Legal Terms*