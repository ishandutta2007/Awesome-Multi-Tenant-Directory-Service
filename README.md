# Awesome-Multi-Tenant-Directory-Service

# Top Multi-Tenant Directory Service Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Identity Stores, Tenant Isolation & Self-Hosted Directory Services*
**Last updated: October 2026**

This repository tracks notable **commercial multi-tenant directory platforms** and **open-source projects** that store and manage user identities, groups, and organizational hierarchies across multiple tenants — enabling B2B SaaS, enterprise identity, and federated access at scale.

**Examples** include AWS Cloud Directory, Microsoft Entra ID, JumpCloud, Okta Universal Directory, PingDirectory, OneLogin, ForgeRock Identity Directory, Frontegg, WorkOS, and Authentik (the category leaders).

**Open-source emphasis**: Multi-tenant directory services are a strong open-source domain. **Keycloak** leads with built-in multi-tenancy via realms, **Zitadel** provides multi-tenant native architecture with organizations, **Authentik** delivers flexible tenant isolation, and **Apache Syncope** handles identity governance. **OpenLDAP**, **FreeIPA**, **Samba AD**, and **389 Directory Server** provide LDAP foundations. **Ory Kratos**, **Casdoor**, and **FusionAuth** round out the ecosystem. **MaxKey**, **Janssen**, and **Gluu** provide enterprise IAM with multi-tenancy. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Microsoft Entra ID](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)**
  **The enterprise identity standard** — multi-tenant directory with B2B collaboration, conditional access, and 10,000+ SaaS app integrations . **Free tier with Microsoft 365**; Premium P1/P2 for advanced features . **Best for Microsoft-centric organizations**.

- **[Okta Universal Directory](https://www.okta.com/products/universal-directory/)**
  **The market-leading independent directory** — multi-tenant user store with profile mastering, attribute mapping, and app integration . **Best for enterprise identity**.

- **[JumpCloud](https://jumpcloud.com/)**
  **The cloud directory platform** — unified directory, SSO, device management, and LDAP . **Free for up to 10 users** . **Best for SMBs wanting cloud directory**.

- **[PingDirectory](https://www.pingidentity.com/)**
  **High-performance LDAP directory** — millions of entries with sub-millisecond latency . **Best for large-scale enterprise directories**.

- **[OneLogin](https://www.onelogin.com/)**
  **Workforce identity** — directory, SSO, and MFA . **Best for mid-market enterprises**.

- **[ForgeRock Identity Directory](https://www.forgerock.com/)**
  **Enterprise directory services** — multi-tenant with high scale . **Best for large enterprises**.

- **[AWS Cloud Directory](https://aws.amazon.com/clouddirectory/)**
  **AWS's directory service** — hierarchical data store with schema-based organization . **Best for AWS-native directory applications**.

- **[Frontegg](https://frontegg.com/)**
  **Customer identity platform** — multi-tenant SSO, RBAC, and user management for B2B SaaS . **Best for product-led SaaS**.

- **[WorkOS](https://workos.com/)**
  **Enterprise SSO and directory sync** — SCIM, SSO, and audit logs for B2B SaaS . **Best for B2B SaaS companies**.

## Open-Source GitHub Projects

### Multi-Tenant Identity Platforms

- **[Keycloak](https://github.com/keycloak/keycloak)**
  **The most widely adopted open-source identity provider**, Apache-2.0 licensed with **36,000+ GitHub stars** . **Multi-tenancy via realms** — each realm is an isolated tenant with its own users, clients, and configuration . **OAuth 2.0, OIDC, SAML, and LDAP support** . **Identity brokering, user federation, and fine-grained authorization** . **The de facto open-source multi-tenant directory** — used by enterprises, governments, and SaaS providers worldwide . **Best for comprehensive multi-tenant identity**.

- **[Zitadel](https://github.com/zitadel/zitadel)**
  **Identity infrastructure with native multi-tenancy**, Apache-2.0 licensed . **Organizations and projects** provide built-in tenant isolation . **OIDC, OAuth2, SAML2, passkeys/FIDO2, and SCIM 2.0** . **API-first with modern architecture** . **Best for modern multi-tenant SaaS**.

- **[Authentik](https://github.com/goauthentik/authentik)**
  **Flexible open-source identity provider**, MIT/GPL licensed with **10,000+ GitHub stars** . **Tenant isolation via brands and flows** . **OAuth2, SAML, LDAP, and proxy support** . **Flow-based authentication customization** . **Best for flexible multi-tenant identity**.

- **[Apache Syncope](https://github.com/apache/syncope)**
  **Open-source identity governance and administration (IGA)**, Apache-2.0 licensed . **Multi-tenancy with domain isolation** . **User provisioning, de-provisioning, and access certification** . **Best for identity governance with multi-tenancy**.

- **[Ory Kratos](https://github.com/ory/kratos)**
  **Headless identity and user management**, Apache-2.0 licensed . **Multi-tenant support via projects and organizations** . **API-first with self-service flows** . **Best for headless multi-tenant identity**.

- **[Casdoor](https://github.com/casdoor/casdoor)**
  **UI-first identity and access management platform**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Organizations for multi-tenancy** . **OAuth2, OIDC, SAML, LDAP, and CAS support** . **Best for UI-driven multi-tenant IAM**.

- **[FusionAuth](https://github.com/FusionAuth/fusionauth)**
  **Open-source identity and access management**, Apache-2.0 licensed . **Tenants for multi-tenancy** . **SSO, MFA, and user management** . **Best for developer-friendly multi-tenant IdP**.

- **[MaxKey](https://github.com/dromara/MaxKey)**
  **Leading IAM/IDaaS product**, Apache-2.0 licensed . **OAuth2.x, OpenID Connect, SAML2.0, JWT, CAS, and SCIM support** . **RBAC-based unified permission control** . **Best for enterprise multi-tenant IAM**.

- **[Janssen Project](https://github.com/JanssenProject/jans)**
  **Cloud-native IAM platform under Linux Foundation**, Apache-2.0 licensed . **Auth Server (OAuth/OpenID), Agama low-code identity orchestration, and Cedarling policy decision point** . **Best for cloud-native multi-tenant IAM**.

- **[Gluu](https://github.com/GluuFederation)**
  **Open-source IAM platform**, Apache-2.0 licensed . **SSO, MFA, and identity federation** . **Best for comprehensive IAM suite**.

### LDAP Directory Services

- **[OpenLDAP](https://github.com/openldap/openldap)**
  **The standard open-source LDAP directory**, OpenLDAP Public License . **Multi-tenant via organizational units (OUs)** . **The foundation for most enterprise directories** . **Best for LDAP directory services**.

- **[FreeIPA](https://github.com/freeipa/freeipa)**
  **Identity management for Linux/Unix environments**, GPL-3.0 licensed . **LDAP, Kerberos, DNS, and certificate management** . **Best for Linux/Unix identity**.

- **[Samba AD](https://github.com/samba-team/samba)**
  **Active Directory compatible domain controller**, GPL-3.0 licensed . **Multi-tenant via domains and organizational units** . **Best for AD-compatible directory**.

- **[389 Directory Server](https://github.com/389ds/389-ds-base)**
  **Enterprise-class LDAP server from Red Hat**, GPL-3.0 licensed . **Multi-tenant via suffixes and backends** . **Best for enterprise LDAP**.

- **[Apache Directory](https://github.com/apache/directory-server)**
  **LDAP server and directory tools**, Apache-2.0 licensed . **Multi-tenant via partitions** . **Best for LDAP directory services**.

- **[OpenDJ](https://github.com/OpenIdentityPlatform/OpenDJ)**
  **LDAP directory services (ForgeRock)**, CDDL licensed . **High-performance multi-tenant directory** . **Best for enterprise LDAP**.

### Tenant Isolation & Authorization

- **[OpenFGA](https://github.com/openfga/openfga)**
  **Fine-grained authorization**, Apache-2.0 licensed . **Google Zanzibar-inspired relationship-based access control** . **Multi-tenant authorization with isolation** . **Best for multi-tenant authorization**.

- **[SpiceDB](https://github.com/authzed/spicedb)**
  **Authorization database**, Apache-2.0 licensed . **Zanzibar-inspired permissions system** . **Best for multi-tenant permissions**.

- **[Permify](https://github.com/Permify/permify)**
  **Open-source authorization service**, Apache-2.0 licensed . **Zanzibar-inspired with multi-tenancy** . **Best for multi-tenant authorization**.

- **[Cerbos](https://github.com/cerbos/cerbos)**
  **Policy-as-code authorization**, Apache-2.0 licensed . **Language-agnostic with stateless design** . **Best for multi-tenant authorization**.

### Additional Strong Open-Source Options

- **LLDAP** — Lightweight LDAP server for self-hosted identity .
- **Kanidm** — Modern identity management platform in Rust .
- **Authelia** — Authentication and authorization server .
- **Pomerium** — Identity-aware access proxy .
- **Dex** — Open-source OIDC identity provider .
- **WSO2 Identity Server** — Enterprise-grade open-source IAM .
- **OpenIAM** — Apache-licensed identity and access management .
- **go-iam** — Lightweight multi-tenant IAM server in Go .

**Frameworks for building custom multi-tenant directory solutions**: Combine **Keycloak** for comprehensive multi-tenant identity with realms . Use **Zitadel** for native multi-tenant architecture with organizations . Deploy **Authentik** for flexible tenant isolation with flow-based authentication . Choose **Apache Syncope** for identity governance with multi-tenancy . Integrate **OpenLDAP** or **FreeIPA** for LDAP directory services . Use **OpenFGA** or **SpiceDB** for multi-tenant authorization . Note that true enterprise multi-tenant directory with global scale, compliance certifications, and vendor-supported SLAs (Okta, Entra ID, PingDirectory) remains primarily commercial territory; open-source stacks provide strong identity stores, tenant isolation, and federation foundations that require integration for complete multi-tenant directory services.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Multi-tenant directory services handle sensitive identity data. Self-hosted solutions require proper security hardening, tenant isolation, access controls, and compliance with data privacy regulations (GDPR, CCPA, SOC 2).
- **Tenant isolation is critical** — a misconfiguration can expose one tenant's data to another. Keycloak realms, Zitadel organizations, and Authentik brands provide isolation boundaries but require careful configuration .
- **SCIM provisioning is essential for lifecycle management** — ensure your chosen directory supports SCIM for automated user provisioning and de-provisioning .
- **License considerations**: Keycloak uses Apache-2.0, Zitadel uses Apache-2.0, Authentik uses MIT/GPL, OpenLDAP uses OpenLDAP Public License, and FreeIPA uses GPL-3.0. Verify licensing against your use case before committing .
- The open-source ecosystem provides strong identity stores, tenant isolation, and federation foundations, but **global scale, compliance certifications, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for identity architects, platform engineers, and organizations seeking multi-tenant directory sovereignty.**
Let's make multi-tenant directory services more open, transparent, and secure.
