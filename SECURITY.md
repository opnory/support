# Opnory Security Policy

## Reporting a Vulnerability

**Primary contact:** security@opnory.com

Please do not report security vulnerabilities through public GitHub issues, discussions, social media, or other public channels.

If `security@opnory.com` has not yet been configured, this is a deployment blocker — configure the alias before publishing this policy as operational.

When submitting a report, please include:

- Description of the vulnerability
- Affected component or area
- Reproduction steps
- Proof of concept where appropriate
- Security impact assessment
- Preconditions required
- Relevant logs or screenshots (redacted)
- Suggested remediation if known

Minimize collection or transmission of personal or customer data. Do not include real credentials, access tokens, private keys, or customer secrets unless absolutely necessary. If sensitive files are needed, coordinate a secure transfer method first.

---

## Supported Versions

Opnory is currently in development. Formal supported-version ranges will be published once releases begin. Security reports concerning the current codebase are still welcome.

> **[SUPPORTED RELEASE POLICY TO BE DEFINED AFTER FIRST RELEASE]**

---

## Scope

### In Scope

Examples of issues that may be in scope include vulnerabilities affecting Opnory-maintained code or hosted infrastructure, such as:

- Authentication bypass
- Authorization bypass
- Privilege escalation
- Access-control failures
- Cross-tenant data exposure
- Customer-data exposure
- Remote code execution
- Command injection
- SQL or database injection
- Server-side request forgery (SSRF)
- Cross-site scripting (XSS)
- Cross-site request forgery (CSRF) where security-relevant
- Sensitive information disclosure
- Secret or credential leakage
- Insecure integration permissions
- Improper Slack authorization
- IAM or identity-workflow bypasses
- Approval-workflow bypasses
- Unsafe privileged-action execution
- AI/tool execution vulnerabilities that permit unauthorized actions
- Prompt-injection paths that result in unauthorized disclosure or privileged actions
- Dependency vulnerabilities with meaningful exploitability in Opnory
- Security flaws in Opnory Cloud infrastructure once that service exists

Not all of these attack surfaces currently exist in the codebase. Reports are evaluated on demonstrated impact.

---

### Open Source vs. Cloud Scope

#### Opnory Open Source

Security reports may concern vulnerabilities in code maintained by Opnory.

Self-hosting operators remain responsible for their own:

- Infrastructure, networks, operating systems, cloud accounts
- Databases, TLS configuration, credentials
- Deployment configuration, IAM configuration
- Third-party integrations

This distinction does not disclaim vulnerabilities caused by Opnory application code itself.

#### Opnory Cloud

Once available, reports may also concern:

- Opnory-managed infrastructure
- Tenant isolation
- Authentication and authorization
- Data exposure in the hosted service
- Cloud-hosted integrations
- Service configuration under Opnory control

Opnory Cloud is not yet generally available.

---

## Out of Scope

The following are generally out of scope:

- Vulnerabilities exclusively in infrastructure independently operated by a self-hosted user
- Vulnerabilities solely in unsupported third-party software with no Opnory-specific impact
- Social engineering of Opnory personnel
- Physical attacks
- Denial-of-service or load testing that could disrupt service
- Spam
- Automated reports without demonstrated security impact
- Missing headers with no meaningful exploit
- Rate-limit observations without demonstrated impact
- Clickjacking on pages with no sensitive action
- Reports based only on software version banners
- Vulnerabilities requiring control of an already compromised administrator account unless a privilege boundary can still be crossed

This list is not exhaustive and is not used to dismiss legitimate findings.

---

## AI and Agent Security

Because Opnory is an AI-powered IT and access-management product, AI issues are especially relevant when they result in a real security boundary being crossed.

Examples worth reporting include:

- Prompt injection causing access to unauthorized knowledge
- Retrieval of data the requesting user should not be able to access
- AI-generated tool calls bypassing authorization
- Unauthorized privileged actions
- Approval workflow bypass
- Cross-user or cross-tenant context leakage
- Tool parameter manipulation that causes unauthorized action
- Secrets disclosed through model context
- Indirect prompt injection that changes privileged system behavior

Ordinary incorrect AI answers, hallucinations, or low-quality responses without a security consequence are generally product-quality issues rather than security vulnerabilities. Prompt injection itself is not always a vulnerability — focus is on demonstrated boundary violations or unauthorized impact.

---

## Coordinated Disclosure

We ask researchers to give us a reasonable opportunity to investigate and address a vulnerability before publishing technical details that could place users at risk. No fixed embargo period is imposed; we prefer cooperative coordination based on severity and remediation complexity.

---

## Safe Harbor

Opnory supports good-faith security research conducted:

- Within the stated scope
- Without intentionally accessing more data than necessary to demonstrate impact
- Without disrupting service
- Without exploiting findings beyond what is necessary for proof of concept
- Without using findings for extortion
- In compliance with applicable law

This language encourages coordinated research without promising legal immunity Opnory cannot provide.

> **[COUNSEL REVIEW RECOMMENDED FOR SAFE-HARBOR LANGUAGE]**

Opnory cannot bind third parties or law-enforcement agencies.

---

## Handling Accidentally Accessed Data

If you unexpectedly encounter:

- Customer data
- Personal information
- Credentials or secrets
- Private repository content

Please:

1. Stop further access where practical.
2. Avoid downloading or retaining unnecessary copies.
3. Report the exposure promptly.
4. Securely delete unnecessary copies after coordination with Opnory.

Do not destroy evidence required for investigation before coordination.

---

## Public GitHub Reports

Security vulnerabilities should not initially be filed through a public issue. If GitHub private vulnerability reporting or repository security advisories are enabled in the future, they may also be used. This `SECURITY.md` file serves as the canonical disclosure policy per GitHub convention.

---

## Dependency Vulnerabilities

Automated dependency vulnerability reports are most useful when they include:

- Affected dependency
- Affected Opnory version or commit
- Reachability or exploitability analysis
- Realistic impact assessment

Not every CVE in the dependency tree constitutes an Opnory vulnerability.

---

## Security Updates

### Opnory Open Source

Security fixes may be released as commits, patches, or new versions once formal releases exist.

### Opnory Cloud

Security fixes for infrastructure and components under Opnory control may be deployed as service updates.

> **[SECURITY RELEASE AND SUPPORT POLICY TO BE DEFINED]**

No timelines are promised at this stage.

---

## Acknowledgment and Response

Opnory intends to:

- Acknowledge reports when practical
- Investigate in good faith
- Prioritize according to severity and impact
- Coordinate remediation and disclosure where appropriate

> **[SECURITY RESPONSE TARGETS TO BE DEFINED]**

Fixed response-time guarantees (e.g., "24-hour acknowledgment," "7-day critical fix") are not currently offered.

---

## Attribution

Researchers may request public acknowledgment after remediation. Attribution is optional. Opnory does not currently operate a bug bounty program.

> **[BUG BOUNTY POLICY TO BE CONFIRMED]**

No monetary rewards, swag, CVE assignment, or hall-of-fame placement are promised unless such programs are established.

---

## Contact

**Security reports:** security@opnory.com  
**General support:** support@opnory.com  
**Privacy:** privacy@opnory.com  
**Website:** https://opnory.com