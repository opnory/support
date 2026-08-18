# Opnory End User License Agreement

**Enterprise Software License Agreement**

Effective Date: [EFFECTIVE DATE]
Last Updated: [CURRENT DATE]

**DRAFT FOR LEGAL REVIEW**

---

This Opnory End User License Agreement ("Agreement") governs the licensing and use of Opnory software ("Software") by the Customer ("Customer," "you," "your"). By downloading, installing, accessing, or using the Software, Customer agrees to be bound by this Agreement. If Customer does not agree, Customer must not use the Software.

Opnory is an enterprise AI-powered IT service desk product offered by Raell Dottin under the name Opnory. This Agreement covers the self-hosted, perpetual software license edition of Opnory ("Opnory Open Source"). The hosted subscription edition, Opnory Cloud, is governed by separate Cloud Terms of Service.

---

## 1. Definitions

| Term | Definition |
|------|------------|
| **Agreement** | This End User License Agreement, including all exhibits, schedules, and Order Forms that reference it. |
| **Opnory** | The enterprise AI-powered IT service desk product offered by Raell Dottin. |
| **Software** | The Opnory Open Source software, including executable code, source code (where provided), libraries, and associated files, as delivered to Customer. |
| **Customer** | The legal entity that purchases or acquires a license to the Software under this Agreement. |
| **Authorized User** | An individual employee, contractor, or agent of Customer authorized by Customer to access and use the Software on Customer's behalf. |
| **Documentation** | User guides, technical documentation, API references, administrator guides, and other written materials for the Software. |
| **Customer Data** | Data, content, and information that Customer or its Authorized Users submit, store, or process through the Software. |
| **Integration** | A connection between the Software and a Third-Party Service authorized and configured by Customer. |
| **Third-Party Service** | An external platform, application, or service (e.g., Slack, Microsoft Entra ID, Okta, GitHub, Jira Service Management, ServiceNow, AWS, Google Workspace) that the Software may integrate with. |
| **Order Form** | A written ordering document (including quotes, statements of work, or similar commercial instruments) referencing this Agreement that specifies the license scope, fees, and other commercial details. |
| **Maintenance & Support** | The optional annual program providing updates, bug fixes, security fixes, integration updates, technical support, and documentation updates. |
| **License Key** | Any mechanism (file, code, token) used to validate the Software license scope. |

---

## 2. License Grant

Subject to Customer's compliance with this Agreement and payment of applicable fees, Raell Dottin grants Customer a **non-exclusive, non-transferable, limited license** to:

- Install and use the Software on infrastructure owned or controlled by Customer (including virtual machines, containers, Kubernetes clusters, bare metal, or Customer's cloud accounts);
- Permit Authorized Users to access and use the Software for Customer's internal business purposes;
- Use the Documentation to support authorized use;
- Configure and operate Integrations authorized by Customer.

**Opnory is licensed, not sold.** This Agreement grants only the limited license rights expressly stated herein. All rights not expressly granted are reserved.

The scope of the license (e.g., number of Authorized Users, instances, environments, nodes, or workspaces) is defined in the applicable Order Form. If no Order Form specifies limits, the license is for Customer's reasonable internal business use by its then-current employees and contractors.

---

## 3. Perpetual License

### 3.1 Perpetual Right to Use

A valid perpetual license under this Agreement permits Customer to continue using the licensed version of the Software indefinitely, provided Customer remains in compliance with this Agreement. "Licensed version" means the specific major and minor release of the Software for which Customer holds a valid license at the time Maintenance & Support expires or is not renewed.

### 3.2 What Perpetual Does Not Include

A perpetual license does **not** automatically include perpetual rights to:

- Maintenance & Support (including updates, bug fixes, security patches, new releases, or integration updates);
- Technical support;
- Opnory Cloud hosted services;
- Third-party subscription services or APIs that the Software may integrate with;
- New features or functionality released after the perpetual license version;
- Access to source code repositories or build pipelines beyond what is delivered with the licensed version.

Third-party services (AI providers, identity providers, ticketing systems, cloud platforms, etc.) operate under their own terms and may independently require active subscriptions.

### 3.3 Maintenance & Support

Maintenance & Support is an optional annual program. Expiration or non-renewal of Maintenance & Support **does not terminate** a valid perpetual license. Customer may continue operating the licensed version but will not be entitled to future releases, updates, security fixes, or support unless Maintenance & Support is renewed or a new Order Form is executed.

---

## 4. Ownership

### 4.1 Opnory Ownership

Raell Dottin and its licensors retain all right, title, and interest in and to:

- The Software (including all copies);
- Source code, object code, algorithms, and product technology;
- Documentation;
- Trademarks, service marks, and branding ("Opnory," logos, etc.);
- All intellectual property rights therein.

This Agreement does not transfer ownership of any Opnory intellectual property to Customer.

### 4.2 Customer Data Ownership

Customer retains all right, title, and interest in and to Customer Data. Customer grants Raell Dottin only those limited rights necessary to operate the Software, provide support, maintain security, and troubleshoot problems as described in this Agreement and the Privacy Policy.

### 4.3 Feedback

If Customer provides feedback, suggestions, or feature requests ("Feedback"), Customer grants Raell Dottin a perpetual, irrevocable, royalty-free, worldwide license to use, reproduce, modify, and incorporate Feedback into Opnory products. This license does not extend to Customer Data, Customer confidential information, Customer-developed software, or Customer intellectual property generally.

---

## 5. License Restrictions

Customer will not, and will not permit any third party to:

- Copy the Software except as necessary for authorized use, backup, or disaster recovery;
- Redistribute, resell, rent, lease, or sublicense the Software (except to Authorized Users as permitted);
- Remove, alter, or obscure any copyright, trademark, or proprietary notices;
- Circumvent, disable, or tamper with any license enforcement mechanism;
- Create derivative works based on the Software (except configurations, scripts, or extensions for Customer's own authorized use);
- Reverse engineer, decompile, disassemble, or attempt to derive source code, except to the extent expressly permitted by applicable law notwithstanding this restriction (e.g., for interoperability or security research);
- Use the Software to provide commercial hosting, managed services, or service bureau services to third parties without a separate agreement;
- Benchmark or publish performance comparisons without prior written consent.

**Security Research Exception:** This Agreement does not restrict good-faith security research, authorized penetration testing, or vulnerability disclosure conducted in accordance with the Opnory Security Policy (SECURITY.md).

---

## 6. Authorized Users

Customer determines and manages its Authorized Users. Customer is responsible for:

- Provisioning and deprovisioning Authorized User accounts;
- Assigning appropriate roles, permissions, and entitlements;
- Credential security and authentication hygiene;
- Administrator access governance;
- Removing access when individuals leave the organization or change roles.

Customer's obligations under this Agreement extend to the acts and omissions of its Authorized Users.

---

## 7. Artificial Intelligence Features

### 7.1 AI Capabilities

The Software may incorporate AI functionality to:

- Interpret employee requests and natural-language input;
- Classify and route support requests;
- Search and retrieve information from Customer knowledge bases;
- Generate answers, summaries, and recommendations;
- Recommend troubleshooting steps;
- Prepare access, role, and entitlement requests;
- Recommend workflows and automation;
- Assist with Customer-authorized Integrations.

### 7.2 AI Limitations

AI output can sometimes be **incorrect, incomplete, outdated, misinterpreted, or unsuitable for Customer's particular environment**. Customer must not rely on AI-generated output for critical decisions without human review.

> **AI assists. Customer policies decide.**
>
> Opnory may recommend, prepare, or initiate actions, but Customer remains responsible for its authorization policies, approval processes, system configuration, and privileged access decisions. An AI response is not itself sufficient authorization for a sensitive action.

### 7.3 AI Provider Relationships

The Software may depend upon third-party AI/model service providers selected by Customer or Raell Dottin. Data sent to AI providers may include user requests, conversation context, retrieved knowledge snippets, integration metadata, and workplace identity context.

> **[AI PROVIDER DATA HANDLING TO BE CONFIRMED]** — The specific model provider(s), their data retention, training exclusion, deletion, residency, and enterprise guarantees must be confirmed by Customer (for self-hosted deployments) or by Raell Dottin (for Cloud) before production use.
>
> **[AI DATA USE POLICY MUST BE CONFIRMED]** — The treatment of Customer Data in connection with AI model training, fine-tuning, or improvement must be confirmed by architecture and provider contracts.

---

## 8. Identity, Access, and Privileged Operations

### 8.1 Integration with Identity and Access Systems

The Software may integrate with:

- Identity providers (Microsoft Entra ID, Okta, etc.);
- IAM platforms and access-governance systems;
- Service-management platforms (Jira Service Management, ServiceNow, etc.);
- Source-control platforms (GitHub, GitLab, etc.);
- Cloud services (AWS, GCP, Azure, etc.);
- SaaS applications (Google Workspace, Microsoft 365, etc.).

### 8.2 Customer Responsibilities

Customer remains responsible for:

- Accuracy and currency of identity data synchronized to the Software;
- Role definitions, entitlements, and group memberships;
- Approval policies and authorization rules for sensitive operations;
- Administrator access and privileged-role governance;
- Least-privilege configuration of Integrations;
- Reviewing and approving sensitive actions initiated through the Software.

### 8.3 No Independent Authorization Authority

The Software should not be relied upon as a replacement for Customer's IAM, identity, or authorization authority. Opnory is designed so that privileged actions flow through Customer's identity and policy infrastructure. Customer's identity systems, IAM systems, access-governance systems, administrators, approval workflows, and policies remain the ultimate authority for authorization decisions.

---

## 9. Knowledge and External Information

### 9.1 Customer Knowledge

The Software may index, search, and retrieve content from Customer-authorized knowledge sources, which may include:

- Internal documentation, policies, and procedures;
- IT knowledge bases and runbooks;
- Vendor documentation and approved public information;
- Configuration data and operational guides.

### 9.2 Limitations

- External information (vendor docs, public sources) can change, become outdated, or be inaccurate.
- Customer-specific documentation may supersede general vendor guidance.
- Customer controls which information sources are connected and authoritative for its environment, where the Software configuration permits.
- The Software does not independently verify the accuracy of retrieved information.

---

## 10. Third-Party Integrations

### 10.1 Integration Examples

Potential Integrations include (not all are currently implemented):

- **Communication:** Slack
- **Identity:** Microsoft Entra ID, Okta
- **Service Management:** Jira Service Management, ServiceNow
- **Developer:** GitHub, GitLab
- **Cloud & SaaS:** AWS, Google Workspace, Microsoft 365, Azure

### 10.2 Integration Terms

- Each Third-Party Service operates under its own terms of service, privacy policy, and API terms.
- APIs, functionality, and availability can change without notice.
- Customer authorizes which Integrations the Software may access.
- Raell Dottin cannot guarantee uninterrupted availability of independent Third-Party Services.
- Integration availability will vary during early access and development phases.

---

## 11. Customer Data

### 11.1 Ownership

Customer retains all rights in Customer Data.

### 11.2 Limited License to Process

Customer grants Raell Dottin a limited, non-exclusive, worldwide license to process Customer Data solely to the extent reasonably necessary to:

- Operate the Software;
- Retrieve requested information;
- Execute authorized Integrations;
- Provide AI functionality;
- Maintain security;
- Troubleshoot problems;
- Provide support (where Customer engages support).

### 11.3 Restrictions on Use

Raell Dottin will not:

- Use Customer Data for advertising or profiling;
- Sell Customer Data to third parties;
- Use Customer Data to train generalized AI models (unless confirmed otherwise per Section 7.3);
- Access Customer Data beyond what is necessary for the purposes above.

> **[AI DATA USE POLICY MUST BE CONFIRMED]**

Cross-reference: [Privacy Policy](PRIVACY.md).

---

## 12. Confidentiality

### 12.1 Mutual Obligations

Each party ("Receiving Party") will protect the other party's Confidential Information using reasonable care (no less than the care it uses for its own similar information). "Confidential Information" includes:

- Customer Data, knowledge bases, credentials, and security configurations;
- Internal policies, procedures, and operational information;
- Non-public Opnory technology, architecture, roadmap, and business information;
- Security-related information, vulnerability details, and incident data;
- Terms of this Agreement and any Order Form (except as required by law).

### 12.2 Exclusions

Confidential Information does not include information that:

- Is independently developed by the Receiving Party without use of the Disclosing Party's Confidential Information;
- Is or becomes publicly available without breach of this Agreement;
- Was lawfully received from a third party without restriction;
- Is required to be disclosed by law, provided the Receiving Party gives prompt notice (where legally permitted) and cooperates with protective measures.

### 12.3 Duration

Confidentiality obligations survive termination of this Agreement for **[CONFIDENTIALITY PERIOD TO BE DEFINED]** (recommended: 3–5 years for trade secrets, 2–3 years for other confidential information).

> **[COUNSEL REVIEW REQUIRED]** — Enterprise customers may negotiate separate NDAs or MSAs that modify or supersede this provision.

---

## 13. Security Responsibilities

### 13.1 Raell Dottin Responsibilities

Raell Dottin will implement reasonable technical and organizational safeguards for the Software, which may include:

- Secure development practices and vulnerability management;
- Security fixes and patches (delivered via Maintenance & Support or critical releases);
- Reasonable protection of any Raell Dottin-operated services Customer uses (e.g., license validation, update checks).

**No certifications claimed** (SOC 2, ISO 27001, FedRAMP, HIPAA, PCI DSS, etc.) unless independently verified and documented.

### 13.2 Customer Responsibilities

Customer is responsible for security of its deployment, including:

- Infrastructure, network, operating system, and cloud account security;
- Database security, encryption, and access controls;
- TLS configuration and certificate management;
- Credential management, secrets rotation, and key handling;
- Deployment configuration, IAM, and network policies;
- Administrator account governance and privileged access;
- Integration permissions and least-privilege configuration;
- Authorized User provisioning, authentication, and deprovisioning;
- Backup, disaster recovery, and business continuity.

### 13.3 Shared Model

| Party | Responsible For |
|-------|-----------------|
| Raell Dottin | Application code vulnerabilities, secure development, patches |
| Customer | Infrastructure, deployment, credentials, access policies, integrations |

---

## 14. Maintenance & Support

### 14.1 Optional Annual Program

Maintenance & Support is an optional annual program that may cover:

- Product updates and bug fixes;
- Security fixes and patches;
- Supported new releases and versions;
- Integration updates and compatibility maintenance;
- Technical support (response times, channels, and scope per applicable Support Terms);
- Documentation updates.

### 14.2 Terms Governed by Order Form

Exact Maintenance & Support obligations, SLAs, response times, support channels, and covered releases are established by the applicable Order Form, Support Agreement, or Statement of Work.

> **[SUPPORT TERMS]**

### 14.3 Expiration

Expiration of Maintenance & Support does not terminate the perpetual license. Customer may continue using the licensed version but is not entitled to future releases, updates, or support.

---

## 15. Updates and Versions

### 15.1 Future Versions

Future versions of the Software may:

- Add, modify, or deprecate functionality;
- Change integration behavior or supported APIs;
- Respond to security requirements;
- Adapt to third-party API changes;
- Modify AI model behavior or provider integration.

### 15.2 Perpetual License vs. Future Versions

Ownership of a perpetual license to a specific version does not entitle Customer to future versions. Entitlement to future versions requires active Maintenance & Support or a new Order Form.

### 15.3 Critical Updates

Raell Dottin may release critical security fixes outside the normal release cycle. Customers with expired Maintenance & Support may receive critical security patches at Raell Dottin's discretion, but are not guaranteed them.

---

## 16. Fees and Taxes

Commercial fees (license fees, Maintenance & Support fees) are specified in the applicable Order Form. Applicable taxes (sales, VAT, GST, withholding, etc.) are Customer's responsibility unless otherwise stated in the Order Form. Payment obligations are governed by the applicable commercial documents.

---

## 17. Open-Source Software

The Software may incorporate third-party open-source software components. The respective open-source licenses govern those components where required. This Agreement does not override or restrict rights granted by applicable open-source licenses. A reference copy of the BSD-2-Clause license (governing Opnory Open Source) is available at `LICENSE` in the Software distribution and at `licenses/BSD-2-Clause.txt` in the Opnory support repository.

---

## 18. Warranty

### 18.1 Limited Warranty

Raell Dottin warrants that the Software will substantially conform to its Documentation when used as authorized and in accordance with system requirements. This warranty lasts for **[WARRANTY PERIOD TO BE DEFINED]** (recommended: 90 days) from delivery.

### 18.2 Remedy

Raell Dottin's sole obligation and Customer's exclusive remedy for breach of the above warranty is, at Raell Dottin's option: (a) use commercially reasonable efforts to correct the non-conformity; or (b) if correction is not commercially reasonable, terminate the license and refund a pro-rata portion of the license fee paid for the affected version.

### 18.3 Disclaimer

EXCEPT AS EXPRESSLY WARRANTED IN SECTION 18.1, THE SOFTWARE IS PROVIDED "AS IS." RAELL DOTTIN DISCLAIMS ALL OTHER WARRANTIES, EXPRESS OR IMPLIED, INCLUDING:

- MERCHANTABILITY;
- FITNESS FOR A PARTICULAR PURPOSE;
- TITLE AND NON-INFRINGEMENT;
- UNINTERRUPTED OR ERROR-FREE OPERATION;
- ACCURACY OF AI-GENERATED OUTPUT;
- COMPATIBILITY WITH THIRD-PARTY SERVICES OR FUTURE PLATFORM VERSIONS.

> **[COUNSEL REVIEW REQUIRED]** — Warranty treatment materially affects enterprise sales.

---

## 19. LIMITATION OF LIABILITY

**TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW:**

- NEITHER PARTY'S AGGREGATE LIABILITY ARISING OUT OF OR RELATED TO THIS AGREEMENT WILL EXCEED **[LIABILITY CAP]**.
- NEITHER PARTY WILL BE LIABLE FOR INDIRECT, INCIDENTAL, SPECIAL, CONSEQUENTIAL, OR PUNITIVE DAMAGES, OR FOR LOSS OF PROFITS, REVENUE, DATA, OR BUSINESS OPPORTUNITY, EVEN IF ADVISED OF THE POSSIBILITY.

The foregoing limitations do not apply to:

1. Customer's payment obligations;
2. Either party's confidentiality obligations (Section 12);
3. Indemnification obligations (Section 20);
4. Liability arising from gross negligence, willful misconduct, or fraud;
5. Liabilities that cannot be excluded by applicable law.

> **[COUNSEL REVIEW REQUIRED]** — Liability limitations must be reviewed by counsel for enforceability in the governing jurisdiction.

---

## 20. Indemnification

### 20.1 Raell Dottin Indemnification

Raell Dottin will indemnify, defend, and hold harmless Customer against third-party claims alleging that the Software (as provided by Raell Dottin and used within the scope of this Agreement) infringes a valid patent, copyright, or trademark, provided Customer:

- Promptly notifies Raell Dottin in writing;
- Grants Raell Dottin sole control of defense and settlement;
- Provides reasonable cooperation.

Raell Dottin may, at its option and expense: (i) procure the right for Customer to continue use; (ii) replace or modify the Software to be non-infringing; or (iii) if neither is commercially reasonable, terminate the license and refund a pro-rata portion of fees.

### 20.2 Customer Indemnification

Customer will indemnify, defend, and hold harmless Raell Dottin against third-party claims arising from:

- Customer Data;
- Customer's misuse of the Software beyond the scope of this Agreement;
- Customer's violation of Third-Party Service terms;
- Customer's authorization policies, approval workflows, or access decisions;
- Customer's deployment configuration and infrastructure.

### 20.3 Procedure

Indemnification claims require prompt written notice, sole control of defense by the indemnifying party (with the indemnified party's reasonable cooperation), and no admission of liability by the indemnified party without consent.

> **[COUNSEL REVIEW REQUIRED]** — Indemnification provisions require counsel review for balance and enforceability.

---

## 21. Term and Termination

### 21.1 License Term

The perpetual license term begins on the Effective Date and continues indefinitely unless terminated as provided below.

### 21.2 Maintenance & Support Term

Maintenance & Support terms are annual, as specified in the applicable Order Form. Non-renewal expires Maintenance & Support but **does not terminate** the perpetual license.

### 21.3 Termination for Material Breach

Either party may terminate this Agreement for the other party's uncured material breach with **30 days' written notice**. The breaching party may cure during the notice period.

### 21.4 Immediate Termination

Raell Dottin may terminate immediately for:

- Fraud, illegal activity, or security emergency;
- Customer's unauthorized distribution or sublicensing;
- Customer's circumvention of license controls.

### 21.5 Effect of Termination

Upon termination of the perpetual license:

- Customer must cease use and destroy all copies of the Software;
- Customer may export Customer Data;
- Sections 4, 11, 12, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28 survive termination.

**Critical:** Expiration or non-renewal of Maintenance & Support is **not** termination of the perpetual license and does not trigger the above termination consequences.

---

## 22. Export Controls and Sanctions

Customer will comply with all applicable export control laws, sanctions, and trade restrictions (including U.S. EAR, ITAR, and OFAC regulations). Customer represents it is not located in, ordinarily resident in, or a national of any embargoed jurisdiction, and is not a denied party on any restricted-party list. The Software may not be accessed or used in violation of applicable law.

---

## 23. Governing Law

This Agreement is governed by the laws of **[GOVERNING STATE]**, without regard to conflict-of-laws principles. The parties consent to the exclusive jurisdiction of state and federal courts in **[GOVERNING COUNTY]**.

> **[DISPUTE RESOLUTION APPROACH REQUIRES BUSINESS DECISION AND COUNSEL REVIEW]** — Mandatory arbitration, class-action waivers, jury waivers, or other mechanisms are not included by default. The parties should make a deliberate business decision with counsel input.

---

## 24. Order of Precedence

In the event of conflict (highest to lowest priority):

1. Specifically negotiated MSA / Enterprise Agreement;
2. Order Form;
3. Data Processing Agreement (for privacy/data-processing matters);
4. This EULA;
5. Documentation;
6. Website terms.

> **[COUNSEL REVIEW REQUIRED]** — Final precedence mechanics require attorney review.

---

## 25. General Provisions

### 25.1 Entire Agreement

This Agreement, together with applicable Order Forms, constitutes the entire agreement between the parties regarding the Software and supersedes all prior or contemporaneous communications.

### 25.2 Amendment

This Agreement may only be amended in writing signed by both parties, except that Raell Dottin may update Documentation and general website terms prospectively with reasonable notice.

### 25.3 Assignment

Neither party may assign this Agreement without the other's prior written consent, except to an affiliate or in connection with a merger, acquisition, or sale of substantially all assets, provided the assignee agrees in writing to be bound. Unauthorized assignment is void.

### 25.4 Severability

If any provision is held unenforceable, the remainder remains in effect. The parties will negotiate in good faith to replace the unenforceable provision with a valid provision achieving the closest commercial effect.

### 25.5 Waiver

Failure to enforce any right does not waive that right. Waivers must be in writing.

### 25.6 Force Majeure

Neither party is liable for delays or failures due to causes beyond its reasonable control (natural disasters, war, terrorism, government action, pandemics, internet infrastructure failures).

### 25.7 Notices

Notices under this Agreement will be delivered by email to the addresses in the Order Form or to:

- Raell Dottin: support@opnory.com
- Customer: the email on file in the Order Form

> **[COUNSEL REVIEW: determine whether a postal/legal-notice address must be published before commercial launch.]**

---

## 26. Contact

**Raell Dottin**  
offering software under the name Opnory  

support@opnory.com  
https://opnory.com  
[BUSINESS ADDRESS]

---

*End of Opnory End User License Agreement*