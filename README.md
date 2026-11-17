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

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Druva Identity Workloads Protection](https://www.druva.com/)**  

  Data protection capabilities focused on identity-related workloads and cloud identity resilience within the Druva platform.



- **[CrowdStrike Falcon Identity Protection](https://www.crowdstrike.com/)**  

  Identity threat detection and response module within the Falcon platform that monitors Active Directory and Entra ID for credential-based attacks.



- **[SentinelOne Singularity Identity](https://www.sentinelone.com/)**  

  Identity protection capabilities integrated into the Singularity platform for detecting and responding to identity threats.



- **[Microsoft Defender for Identity](https://www.microsoft.com/en-us/security/business/siem-and-xdr/microsoft-defender-for-identity)**  

  Cloud-based security solution that monitors on-premises Active Directory and hybrid identity signals for suspicious activity.



- **[Semperis Directory Services Protector (DSP) / Identity Resilience](https://www.semperis.com/)**  

  Specialized platform for Active Directory threat detection, change monitoring, and forest recovery after identity-based attacks.



- **[Silverfort Unified Identity Protection](https://www.silverfort.com/)**  

  Agentless identity protection platform that secures legacy and modern authentication protocols across hybrid environments.



- **[Tenable Identity Exposure (formerly Tenable.ad)](https://www.tenable.com/)**  

  Identity security solution focused on discovering attack paths, misconfigurations, and exposures in Active Directory and Entra ID.



- **[Palo Alto Cortex XDR Identity](https://www.paloaltonetworks.com/)**  

  Identity-related detection and response capabilities within the Cortex XDR platform.



- **[Quest On Demand Recovery](https://www.quest.com/)**  

  Cloud-based recovery solution for Microsoft Entra ID, hybrid identity, and related workloads.



- **[Authomize](https://www.authomize.com/)** / **[Zscaler ITDR](https://www.zscaler.com/)**  

  Identity threat detection, posture management, and access governance platforms focused on reducing identity risk.



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
