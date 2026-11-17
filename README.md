# Awesome-IAM-Cloud-Identity-Backup
# Awesome-IAM-Cloud-Identity-Backup

## Top IAM & Cloud Identity Backup

**Curated List of SaaS Products & Open-Source GitHub Projects**



*Focused on Identity Threat Detection & Response (ITDR), Active Directory Protection, Cloud Identity Security, Identity Backup & Recovery*



**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **IAM & Cloud Identity Backup / Protection**. These solutions help organizations detect identity-based attacks, protect Active Directory and cloud identity providers (Entra ID / Okta / etc.), recover from identity compromises, and maintain resilient identity infrastructure.



**Examples** include Druva Identity Workloads Protection, CrowdStrike Falcon Identity Protection, SentinelOne Singularity Identity, Microsoft Defender for Identity, Semperis DSP, Silverfort Unified Identity Protection, Tenable.ad / Tenable Identity Exposure, Palo Alto Cortex XDR Identity, Quest On Demand Recovery, Authomize, and Zscaler ITDR (the category leaders).



**Open-source emphasis**: Full commercial ITDR and identity recovery platforms dominate enterprise adoption. However, strong open-source foundations exist for identity management, attack-path analysis, directory services, and security auditing. **BloodHound Community Edition**, **FreeIPA**, **Keycloak**, **authentik**, **Samba AD**, and related projects provide valuable building blocks. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global Identity and Access Management (IAM) and Identity Threat Detection & Response (ITDR) market is valued at approximately **$25B to $30B** (with the specialized ITDR & identity resilience segment scaling rapidly from ~$6B to $13B+ at >20% CAGR). The sector is **moderately fragmented**: hyper-scale platform providers (such as Microsoft, Palo Alto Networks, and CrowdStrike) dominate consolidated enterprise security suites, while a dynamic ecosystem of specialized pure-play vendors (such as Semperis, Silverfort, Quest, and Druva) fiercely contest hybrid Active Directory defense, forest recovery, and cross-cloud identity governance.

## SaaS/Hosted Platforms

| Platform | Description | Company Size (Valuation / Revenue) | Pricing | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Defender for Identity](https://www.microsoft.com/en-us/security/business/siem-and-xdr/microsoft-defender-for-identity)** | Cloud-based security solution that monitors on-premises Active Directory and hybrid identity signals for suspicious activity. | ~$3.85T+ Market Cap (~$245B+ Annual Revenue) | ~$5.50/user/month (annual commitment, list price); ~$6.60/user/month (month-to-month); also bundled in EMS E5 / M365 E5 Security | 30-day to 90-day free evaluation trial (available via Microsoft Defender admin portal) |
| **[Palo Alto Cortex XDR Identity](https://www.paloaltonetworks.com/)** | Identity-related detection and response capabilities integrated within the Cortex XDR platform. | ~$240B+ Market Cap (~$8B+ Annual Revenue) | Starting at ~$70.00/endpoint/year (~$5.83/endpoint/month, G-Cloud list); negotiable enterprise pricing ~$25–$45/endpoint/year | 30-day to 60-day guided Proof-of-Concept (PoC) evaluation via sales/partners |
| **[CrowdStrike Falcon Identity Protection](https://www.crowdstrike.com/)** | Identity threat detection and response module within the Falcon platform that monitors Active Directory and Entra ID for credential-based attacks. | ~$240B+ Market Cap (~$4B+ Annual Revenue) | Standalone identity protection benchmarked at ~$3.00–$5.00/active identity/month (billed annually); custom enterprise tier add-on | 15-day free trial of the Falcon platform with identity module testing enabled (no credit card required) |
| **[Zscaler ITDR](https://www.zscaler.com/)** | Identity threat detection, deception, and posture management platform focused on reducing identity risk across hybrid clouds. | ~$31B+ Market Cap (~$3.35B Annual Revenue) | Platform enterprise plans start from ~$72.00–$120.00/user/year; ITDR add-on priced via custom tiered enterprise agreements | Guided Proof-of-Concept (PoC) / free interactive identity assessment via sales (no permanent free tier) |
| **[SentinelOne Singularity Identity](https://www.sentinelone.com/)** | Identity protection capabilities integrated into the Singularity platform for detecting and responding to identity threats. | ~$8B Market Cap (~$800M+ Annual Revenue) | Starting at ~$229.99/endpoint/year on Singularity Commercial bundle (includes identity threat protection) | 14-day to 30-day Proof-of-Concept (PoC) evaluation trial upon partner/sales request |
| **[Quest On Demand Recovery](https://www.quest.com/)** | Cloud-based recovery solution for Microsoft Entra ID, hybrid identity, and related workloads. | ~$5.4B Valuation (Acquired by Clearlake Capital; ~$1B Revenue) | Starting at ~£9.18/managed user/year (approx. $11.50/user/year, G-Cloud list price) | 30-day full-featured free trial |
| **[Druva Identity Workloads Protection](https://www.druva.com/)** | Data protection capabilities focused on identity-related workloads and cloud identity resilience within the Druva Data Security Cloud. | ~$2B+ Valuation (~$200M+ ARR / ~$304M Revenue) | Endpoint/identity protection modules start at ~$4.00–$8.00/user/month; cloud workloads billed consumption-based | 30-day self-service free trial with full platform access (no credit card required) |
| **[Semperis Directory Services Protector (DSP)](https://www.semperis.com/)** | Specialized platform for Active Directory threat detection, change monitoring, and forest recovery after identity-based attacks. | ~$1B+ Unicorn Valuation (~$100M+ ARR) | Enterprise subscription scaled by protected identity count (quote-based enterprise contract; community editions free) | Free community assessment tools (Purple Knight & Forest Druid) forever; 30-day guided enterprise PoC |
| **[Silverfort Unified Identity Protection](https://www.silverfort.com/)** | Agentless identity protection platform that secures legacy and modern authentication protocols across hybrid environments. | ~$1B Unicorn Valuation (~$82M+ Revenue / 100%+ YoY ARR Growth) | Starting from ~£7.00/user/year (Silverfort Essentials, G-Cloud list) up to ~£30.00–£45.00/user/year for unified protection tiers | 14-day to 30-day custom Proof-of-Concept (PoC) trial on request |
| **[Authomize (Delinea)](https://www.delinea.com/)** | Identity threat detection, posture management (ITDR), and Cloud Infrastructure Entitlement Management (CIEM). | Acquired by Delinea ($400M+ ARR / PE-backed by TPG & Thoma Bravo) | Cloud-native platform subscription scaled per managed identity and cloud integration (enterprise quote-based) | Guided Proof-of-Concept (PoC) / free trial evaluation upon direct request |



## Open-Source GitHub Projects

- **[BloodHound Community Edition](https://github.com/SpecterOps/BloodHound)**  

  Leading open-source tool for mapping Active Directory and Entra ID relationships as a graph and identifying attack paths to high-value targets. Essential for identity security assessments.



- **[FreeIPA](https://www.freeipa.org/)**  

  Open-source identity management system for Linux/Unix environments. Combines LDAP, Kerberos, DNS, certificate authority, and policy management — a strong foundation for identity infrastructure.



- **[Keycloak](https://github.com/keycloak/keycloak)**  

  Widely adopted open-source Identity and Access Management solution supporting SSO, identity brokering, user federation, and fine-grained authorization (OIDC, SAML, OAuth 2.0).



- **[authentik](https://github.com/goauthentik/authentik)**  

  Modern open-source identity provider with a friendly UI, supporting SSO, MFA, user management, and flexible authentication flows. Popular self-hosted alternative for application identity.



- **[Samba Active Directory](https://www.samba.org/)**  

  Open-source implementation of Active Directory domain services on Linux. Enables domain controller functionality without Windows Server licenses.



- **[Kanidm](https://github.com/kanidm/kanidm)**  

  Modern, secure open-source identity management platform written in Rust, focused on simplicity, security, and ease of operation.



- **[Ory Kratos / Ory Stack](https://github.com/ory/kratos)**  

  Headless, API-first open-source identity and user management system designed for cloud-native applications.



- **[Authelia](https://github.com/authelia/authelia)**  

  Open-source authentication and authorization server providing SSO and 2FA for applications behind a reverse proxy.



- **[Impacket](https://github.com/fortra/impacket)** + related security tools  

  Collection of Python classes for working with network protocols. Widely used (alongside tools like Certipy) for Active Directory security testing and validation.



- **[adalanche](https://github.com/lkarlslund/adalanche)**  

  Open-source Active Directory and Entra ID ACL visualizer and attack-path analysis tool that complements BloodHound-style workflows.



### Additional Strong Open-Source Options

- Attack path & identity graph analysis: **BloodHound CE**, **adalanche**.

- Full identity providers / IAM: **Keycloak**, **authentik**, **Kanidm**, **Ory**.

- Linux/Unix identity domain: **FreeIPA**, **Samba AD**.

- Authentication front-end: **Authelia**.

- Security testing & validation: **Impacket**, Certipy, and related tools.

- Accepting that commercial ITDR and identity recovery platforms (Semperis, CrowdStrike Falcon Identity, Microsoft Defender for Identity, Silverfort, Tenable Identity Exposure, Quest On Demand Recovery) still lead in continuous monitoring, automated response, forest recovery, hybrid AD + Entra ID coverage, and enterprise support.



**Frameworks for building custom systems**:  

Use **BloodHound CE** for attack-path visibility → run identity services on **FreeIPA** or **Samba AD** / application IAM on **Keycloak** or **authentik** → protect access with **Authelia** → continuously validate with open security tooling. Ideal for organizations prioritizing open standards, data sovereignty, and transparent identity infrastructure.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Identity is a critical control plane. Misconfiguration of identity systems can create severe security exposure. Open-source tools provide transparency and flexibility but require skilled operators. Commercial ITDR and recovery platforms often include continuous monitoring, automated remediation, and specialized forest recovery capabilities. This list is not security, identity, or compliance advice. Always test thoroughly and follow least-privilege principles.



---

**Made for identity engineers, security architects, Blue Teams, and open-source advocates.**



Let's keep identity infrastructure resilient, transparent, and under your control.
