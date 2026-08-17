# Opnory Privacy Policy

Effective Date: [EFFECTIVE DATE]
Last Updated: [CURRENT DATE]

**DRAFT FOR LEGAL REVIEW**

This Privacy Policy describes how Opnory ("we," "us," or "our") collects, uses, shares, and protects information in connection with the Opnory AI-powered IT service desk software ("Software," "Product," or "Service") and our website at https://opnory.com ("Website").

---

## 1. Scope and Roles

Opnory may process information in different capacities depending on the context:

### Opnory as Controller (Business Data)
For information we collect directly in our business capacity, we act as a data controller. This may include:
- Website inquiries and contact form submissions;
- Sales and pre-sales communications;
- Support contacts and correspondence;
- Administrative account information for Opnory-hosted services;
- Marketing communications (where consent is obtained).

### Opnory as Processor (Customer Workspace Data)
When Customer deploys the Software, Opnory generally processes Customer Workspace Data on behalf of the organizational Customer. In this context, **Customer determines**:
- Which individuals are Authorized Users;
- Which knowledge sources, documents, and policies are connected;
- Which Third-Party Integrations are enabled;
- Access permissions, roles, and entitlement configurations;
- Retention and deletion policies for their workspace;
- Connected applications and data flows.

> **[CONTROLLER/PROCESSOR ROLE TO BE REVIEWED BY COUNSEL]** — The precise legal classification depends on deployment model, contractual terms, and applicable law. This policy describes anticipated practices; final classification requires counsel review.

---

## 2. Categories of Information

We collect only information necessary for the legitimate purposes described in Section 3. Categories are included only where supported by actual or intended operation.

### 2.1 Contact Information
- Name
- Work email address
- Company/organization name
- Role or title

**Source:** Website forms, sales communications, support contacts, account creation.

### 2.2 Workplace Identity (Customer Workspace)
- Slack user identity / workspace identifier
- User identifier from identity provider (e.g., Microsoft Entra ID objectId, Okta user ID)
- Group memberships and roles
- Entitlements and access profiles

**Source:** Customer-authorized identity-provider Integrations; Customer-provisioned accounts.  
**Controlled by:** Customer (Customer configures identity synchronization).

### 2.3 Support Conversations
- Questions and support requests submitted by Authorized Users
- Troubleshooting dialogue and diagnostic information
- Access requests and role/entitlement change requests
- Feedback and feature requests
- AI-generated responses and recommendations (ephemeral or stored per Customer configuration)

**Source:** Authorized User interactions with the Software via workplace communication platforms (e.g., Slack) or direct interfaces.

### 2.4 Customer Knowledge
- Documents, policies, and procedures uploaded or connected by Customer
- Knowledge-base articles and FAQs
- Vendor documentation imported by Customer
- Configuration data and runbooks

**Source:** Customer-authorized knowledge sources (file uploads, Confluence, Notion, SharePoint, Git repositories, web crawls of approved domains).  
**Controlled by:** Customer (Customer selects and manages connected sources).

### 2.5 Integration Information (When Enabled by Customer)
Where Customer configures an Integration, the Software may access:
- Ticket data (Jira Service Management, ServiceNow, Zendesk)
- Repository metadata (GitHub, GitLab, Bitbucket)
- Application and resource metadata (AWS, Google Cloud, Azure)
- Access-request status and approval history
- Identity and entitlement metadata from IAM platforms
- SaaS application metadata (Google Workspace, Microsoft 365)

**Source:** Customer-authorized Third-Party Service APIs.  
**Controlled by:** Customer (Customer enables/disables each Integration and scopes permissions).

### 2.6 Technical and Operational Information
- IP address (for authentication, fraud prevention, and network routing)
- Browser type, operating system, device characteristics
- Timestamps of access and interaction
- Application logs (errors, performance, feature usage)
- Security events (failed logins, permission changes, anomalous access)
- Audit events (administrative actions, configuration changes, data exports)

**Source:** Automated collection during Software operation and Website visits.  
**Note:** We do not deploy non-essential analytics, advertising trackers, or third-party marketing pixels on the Website as of the Effective Date. See Section 4.

---

## 3. Purposes of Processing

We process information for the following legitimate purposes:

| Purpose | Legal Basis (where applicable) |
|---------|--------------------------------|
| Providing the Software and its features | Contract performance |
| Answering support requests and troubleshooting | Contract performance / legitimate interest |
| Searching and retrieving Customer knowledge | Contract performance |
| Operating Customer-authorized Integrations | Contract performance |
| Processing access requests and approval workflows | Contract performance / legitimate interest |
| Authentication and access control | Contract performance / legal obligation (security) |
| Security monitoring, intrusion detection, fraud prevention | Legitimate interest / legal obligation |
| Product support and maintenance (with Customer consent) | Contract performance |
| Preventing abuse and enforcing terms | Legitimate interest |
| Improving Software reliability and performance | Legitimate interest |
| Legal compliance (subpoenas, regulatory requests) | Legal obligation |
| Communicating with Customers (billing, updates, security notices) | Contract performance / legitimate interest |
| Responding to Website inquiries | Legitimate interest / consent |

**We do not** process personal information for advertising, profiling, automated decision-making with legal effects, or selling to third parties.

---

## 4. Website Privacy

As of the Effective Date, the Opnory Website (https://opnory.com) is a static marketing site deployed to Cloudflare Pages. It:

- Does **not** use Google Analytics, Mixpanel, Amplitude, or similar behavioral analytics;
- Does **not** deploy advertising trackers, pixels, or retargeting scripts;
- Does **not** set non-essential cookies;
- May set essential session cookies if a future interactive feature (e.g., a login portal) is added;
- Relies on Cloudflare's infrastructure, which may process limited visitor metadata (IP, user agent, request path) for DDoS protection and network routing — this is governed by Cloudflare's privacy policy.

If we add analytics or interactive features in the future, this section will be updated with specific details and, where required, consent mechanisms.

---

## 5. Artificial Intelligence Processing

The Software uses AI systems to deliver core features (see EULA Section 7). When Authorized Users interact with AI Features, relevant context — including the user's request, conversation history, connected knowledge snippets, and integration metadata — is transmitted to the AI model provider to generate responses.

### 5.1 AI Providers
> **[AI PROVIDER DATA HANDLING TO BE CONFIRMED]** — The specific model provider(s) (e.g., OpenAI, Anthropic, self-hosted models) and their data-handling commitments must be confirmed based on actual architecture and contractual agreements before this policy is finalized.

### 5.2 Data Sent to AI Providers
May include:
- The Authorized User's natural-language request;
- Relevant conversation context;
- Retrieved knowledge-base excerpts (limited to what Customer has authorized);
- Integration metadata necessary to execute the requested action (e.g., ticket ID, repository name);
- Workplace identity context (user ID, role) for authorization-aware responses.

### 5.3 Commitments We Do Not Make (Unless Verified)
We do **not** claim, unless specifically verified and documented:
- Zero data retention by the AI provider;
- That Customer Data is excluded from model training;
- Specific data residency guarantees;
- Provider-side deletion timelines;
- Enterprise contractual terms with AI providers.

These items require confirmation from the applicable provider agreement and architecture review.

---

## 6. Data Sharing and Recipients

We share information only as described below. We do not sell personal information.

> **[CONFIRM COMPANY POLICY: NO SALE OF PERSONAL INFORMATION]** — Confirm organizational intent before making this a definitive public promise.

### Categories of Recipients

| Recipient Category | Purpose | Example |
|-------------------|---------|---------|
| **Infrastructure providers** | Hosting, compute, storage, networking | Cloudflare, AWS, or Customer's own infrastructure (self-hosted deployments) |
| **AI model providers** | Generating AI responses (see Section 5) | [TO BE CONFIRMED] |
| **Customer-authorized Integrations** | Executing actions Customer has configured | Slack, Microsoft Entra ID, Okta, GitHub, Jira, ServiceNow, AWS, Google Workspace |
| **Support and service vendors** | Customer support, incident response, reliability engineering | Contracted vendors under appropriate agreements |
| **Professional advisers** | Legal, accounting, compliance, security audit | Law firms, auditors, penetration testers |
| **Authorities** | Complying with legal process, court orders, regulatory demands | Law enforcement, data protection authorities |
| **Corporate transaction participants** | M&A due diligence, financing, reorganization (under NDA) | Potential acquirers, investors |

**Subprocessor list:** We do not publish a fixed subprocessor list because the deployment model (self-hosted vs. hosted) and Customer's Integration choices determine actual subprocessors. Customers may request a current subprocessor summary for their deployment.

---

## 7. Retention

Retention periods vary by data category, deployment model, and Customer configuration. We do not impose a single universal retention period.

| Data Category | Retention Approach |
|---------------|-------------------|
| **Contact / Business Data** | Retained while the business relationship exists and for a reasonable period thereafter for legal, accounting, and relationship-management purposes. |
| **Customer Workspace Data** | Determined by Customer configuration. Customer controls deletion of conversations, knowledge sources, and integration data. |
| **Technical / Operational Logs** | Retained for security, debugging, and reliability purposes. Typical windows: 30–90 days for application logs; longer for security/audit logs per Customer or legal requirements. |
| **AI Interaction Context** | Transient by default (processed per request). Stored only if Customer enables conversation history or audit features. |

> **[RETENTION SCHEDULE TO BE DEFINED]** — Specific retention periods, automated deletion workflows, and Customer-configurable controls must be defined in product specifications and contractual terms.

Upon termination of the Customer relationship, Customer may export or request deletion of Customer Workspace Data per the applicable agreement. Opnory will delete or return Customer Data within a commercially reasonable period after receiving valid instructions, subject to legal hold obligations.

---

## 8. Security

We implement reasonable technical and organizational safeguards appropriate to the sensitivity of the information we process. These may include:

- Encryption in transit (TLS 1.2+) for all network communications;
- Encryption at rest for stored Customer Workspace Data (where applicable to the deployment model);
- Role-based access controls and principle of least privilege for Opnory personnel;
- Vulnerability management and patching procedures;
- Security incident detection and response processes;
- Regular security assessments (scope and frequency per internal policy).

**We do not claim** any specific security certifications (SOC 2, ISO 27001, FedRAMP, HIPAA, PCI DSS, etc.) unless independently verified and documented in writing. No system can guarantee absolute security or zero vulnerabilities.

Customers are responsible for security configuration within their control (see EULA Section 13).

---

## 9. Privacy Rights

Depending on applicable jurisdiction (e.g., GDPR, CCPA/CPRA, other U.S. state laws), individuals may have rights concerning their personal information, including:

- **Access** — Request a copy of personal information we hold;
- **Correction** — Request correction of inaccurate information;
- **Deletion** — Request deletion (subject to legal exceptions);
- **Restriction** — Request restriction of processing;
- **Objection** — Object to processing based on legitimate interest;
- **Portability** — Receive data in a structured, commonly used format;
- **Appeal** — Appeal a denied request.

**Where Opnory processes information as a processor on behalf of a Customer**, individuals should generally direct rights requests to their employer/organization (the controller), which can then instruct Opnory. We will cooperate with Customer's reasonable instructions to facilitate rights fulfillment.

> **Rights are not universal.** Availability depends on jurisdiction, legal basis, and controller/processor role. This section describes potential rights; it does not create rights where none exist under law.

---

## 10. U.S. State Privacy Laws

Several U.S. states have enacted comprehensive privacy laws (California CCPA/CPRA, Virginia VCDPA, Colorado CPA, Connecticut CTDPA, Utah UCPA, and others). We monitor these developments.

> **[U.S. STATE PRIVACY REVIEW REQUIRED]** — We do not claim to meet any statutory threshold (e.g., revenue, data volume) until verified. We do not implement "Do Not Sell" or "Do Not Share" mechanisms unless required by law and applicable to our business model. Boilerplate language is avoided in favor of accurate, verified disclosures.

---

## 11. International Data Transfers

The Software may be deployed globally. Information may be processed in jurisdictions outside the individual's country of residence.

> **[INTERNATIONAL DATA TRANSFER MODEL TO BE DETERMINED]** — We have not yet established Standard Contractual Clauses, Binding Corporate Rules, adequacy determinations, or other transfer mechanisms. This requires architecture review (data residency, deployment regions) and counsel input before finalization. Customers with specific data-locality requirements should discuss deployment options with us.

---

## 12. Children's Privacy

Opnory is an enterprise/workplace product designed for organizational use by adults in a professional context. It is not directed to children under 16 (or the applicable age of digital consent in any jurisdiction), and we do not knowingly collect personal information from children for personal use. If a Customer's workplace includes individuals below the applicable age threshold (e.g., interns, apprentices), the Customer as controller manages any associated obligations.

---

## 13. Changes to This Policy

If we make material changes to this Privacy Policy, we will:

- Post the updated policy on this page with a revised "Last Updated" date;
- Notify Customers via email (for business relationship changes) or in-product notice (for workspace-impacting changes);
- Provide a reasonable transition period before materially different data uses take effect.

We will not rely on silent retroactive consent for materially different data uses.

---

## 14. Contact

**Privacy Inquiries:**  
privacy@opnory.com  
https://opnory.com  
[BUSINESS ADDRESS]

> **Note:** `privacy@opnory.com` must be configured through email routing if it does not already exist.

---

*End of Opnory Privacy Policy*