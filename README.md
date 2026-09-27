# Awesome Authentication-as-a-Service (AuthNaaS)

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> A curated list of top **Authentication-as-a-Service (AuthNaaS)**, **Identity and Access Management (IAM)**, **Single Sign-On (SSO)**, **Passwordless Authentication**, and **Identity-as-a-Service (IDaaS)** SaaS products and open-source GitHub projects.

*Focused on Identity Management, Single Sign-On (SSO), Passkeys, WebAuthn, OAuth2/OIDC, and Passwordless Authentication.*

**Last updated: March 2026**

---

## Table of Contents
- [Market Overview](#market-overview)
- [SaaS & Hosted Platforms](#saas--hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

---

## Market Overview

> **Market Size & Fragmentation:** The global Identity-as-a-Service (IDaaS) and Authentication-as-a-Service (AuthNaaS) market is estimated at **$12.8 Billion to $15.5 Billion in 2026**, with projections reaching over **$33.5 Billion by 2030** (CAGR ~25%). The broader IAM industry exceeds **$20 Billion**. The AuthNaaS sector is **moderately fragmented**—while enterprise giants (like Okta/Auth0 and Microsoft Entra) hold substantial market share in large enterprises, developer-focused authentication (Clerk, Stytch, WorkOS, Descope) and open-core solutions (Keycloak, Zitadel, Ory, SuperTokens) continue to thrive and capture rapid developer adoption.

---

## SaaS & Hosted Platforms

Below is a comparison of top cloud-hosted AuthNaaS platforms sorted by **Company Size / Valuation (Descending)**:

| SaaS Platform | Company Size / Valuation / Funding | Starting Price | Free Tier Limits | Key Features |
| :--- | :--- | :--- | :--- | :--- |
| **[Auth0](https://auth0.com/)** | **$6.5 Billion** valuation *(Acquired by Okta for $6.5B)* | $35 / month (B2C) / $23 / month (B2B) | Up to 7,500 Monthly Active Users (MAUs) & 10 social connections | Enterprise-grade identity, extensible authorization, SAML/OIDC, global compliance |
| **[WorkOS](https://workos.com/)** | **$2.0 Billion** valuation *(ARR ~$30M+, Series C)* | $125 / month per SSO/SCIM connection | Free up to 1,000,000 MAUs for User Management (AuthKit) | Enterprise SSO, SCIM Directory Sync, RBAC, Audit Logs, AuthKit UI |
| **[Stytch](https://stytch.com/)** | **$1.0 Billion** valuation *(Acquired by Twilio; $100M+ raised)* | $99 / month platform fee (beyond free limits) | Up to 10,000 MAUs, 5 SSO connections, unlimited B2B orgs | Passwordless auth, Magic links, WebAuthn/Passkeys, OTP, Biometrics |
| **[Descope](https://www.descope.com/)** | **$88 Million** total funding raised *(Est. Valuation ~$300M+)* | $249 / month (Pro Plan) | Up to 7,500 MAUs, 10 tenants, 3 SSO connections | Visual drag-and-drop workflow builder, passwordless auth, B2B SSO, no-code/low-code |
| **[Magic](https://magic.link/)** | **$83 Million** total funding raised *(Est. Valuation ~$200M+)* | $0.05 per MAU (Developer Pay-as-you-go) | Up to 1,000 free MAUs | Passwordless authentication, magic email links, WebAuthn, developer-first APIs |
| **[Clerk](https://clerk.com/)** | **$50 Million** Series C funding *(Total Funding $100M+)* | $25 / month (Pro Plan) | Up to 50,000 MAUs & 100 active organizations | React / Next.js UI components, session management, user management, multi-tenancy |
| **[FusionAuth](https://fusionauth.io/)** | Bootstrapped / High Growth *(ARR doubles annually)* | $162 / month (Starter Cloud) | 14-day free trial on Cloud *(Unlimited free users for self-hosted Community edition)* | OAuth2/OIDC/SAML/LDAP, customizable themes, self-hostable or cloud-managed |
| **[SuperTokens SaaS](https://supertokens.com/)** | **$5 Million+** funding / ARR *(YC Backed)* | $0.02 per additional MAU beyond free limit | Up to 5,000 MAUs on Managed Cloud *(Unlimited on self-hosted open-source)* | Open-core auth, session management, social login, user roles, customizable UI |
| **[Ory Cloud](https://www.ory.sh/)** | **$2.2 Million+** annual revenue *(Backed by VC)* | $70 / month (Production Plan) | Free Developer tier for testing, sandbox & evaluation | Headless identity infrastructure, zero-trust access proxy, Kratos, Hydra, Keto |
| **[Hanko Cloud](https://www.hanko.io/)** | Seed-stage *(Est. revenue ~$270K+)* | $29 / month (Pro Plan) | Up to 10,000 MAUs & 2 production projects *(1M MAU startup grant available)* | Passkey-first authentication, WebAuthn, FIDO2, customizable shadow DOM elements |

---

## Open-Source GitHub Projects

Top open-source authentication, IAM, and SSO repositories sorted by **GitHub Stars (Descending)**:

| Open-Source Project | GitHub Stars | License | Description |
| :--- | :--- | :--- | :--- |
| **[Keycloak](https://github.com/keycloak/keycloak)** | [![Keycloak Stars](https://img.shields.io/github/stars/keycloak/keycloak?style=social&color=white)](https://github.com/keycloak/keycloak/stargazers) | Apache-2.0 | Leading IAM system supporting OAuth 2.0, OpenID Connect, SAML 2.0, LDAP, and user federation. |
| **[Authentik](https://github.com/goauthentik/authentik)** | [![Authentik Stars](https://img.shields.io/github/stars/goauthentik/authentik?style=social&color=white)](https://github.com/goauthentik/authentik/stargazers) | GPL-3.0 | Modern, flexible identity provider with flow-based authentication, SAML, OAuth2, and proxy support. |
| **[Devise](https://github.com/heartcombo/devise)** | [![Devise Stars](https://img.shields.io/github/stars/heartcombo/devise?style=social&color=white)](https://github.com/heartcombo/devise/stargazers) | MIT | Modular authentication solution for Ruby on Rails applications with extensive ecosystem support. |
| **[Passport.js](https://github.com/jaredhanson/passport)** | [![Passport Stars](https://img.shields.io/github/stars/jaredhanson/passport?style=social&color=white)](https://github.com/jaredhanson/passport/stargazers) | MIT | Unobtrusive authentication middleware for Node.js with 500+ strategies (OAuth, OIDC, SAML). |
| **[Zitadel](https://github.com/zitadel/zitadel)** | [![Zitadel Stars](https://img.shields.io/github/stars/zitadel/zitadel?style=social&color=white)](https://github.com/zitadel/zitadel/stargazers) | Apache-2.0 | Cloud-native identity infrastructure with multi-tenancy, passkeys, SCIM 2.0, and audit logs. |
| **[Casdoor](https://github.com/casdoor/casdoor)** | [![Casdoor Stars](https://img.shields.io/github/stars/casdoor/casdoor?style=social&color=white)](https://github.com/casdoor/casdoor/stargazers) | Apache-2.0 | UI-first IAM platform with OAuth2/OIDC/SAML support, built-in admin dashboard, and cross-platform SDKs. |
| **[Ory Kratos](https://github.com/ory/kratos)** | [![Ory Kratos Stars](https://img.shields.io/github/stars/ory/kratos?style=social&color=white)](https://github.com/ory/kratos/stargazers) | Apache-2.0 | Headless, API-first identity and user management server in Go. Passkeys, 2FA, social sign-in. |
| **[SuperTokens](https://github.com/supertokens/supertokens-core)** | [![SuperTokens Stars](https://img.shields.io/github/stars/supertokens/supertokens-core?style=social&color=white)](https://github.com/supertokens/supertokens-core/stargazers) | Apache-2.0 | Open-source alternative to Auth0/Firebase Auth. Session management, passwordless, and social login. |
| **[MaxKey](https://github.com/dromara/MaxKey)** | [![MaxKey Stars](https://img.shields.io/github/stars/dromara/MaxKey?style=social&color=white)](https://github.com/dromara/MaxKey/stargazers) | Apache-2.0 | Leading enterprise IAM/IDaaS product supporting OAuth 2.x, OIDC, SAML 2.0, JWT, CAS, and SCIM. |
| **[Spring Security](https://github.com/spring-projects/spring-security)** | [![Spring Security Stars](https://img.shields.io/github/stars/spring-projects/spring-security?style=social&color=white)](https://github.com/spring-projects/spring-security/stargazers) | Apache-2.0 | Comprehensive authentication and authorization framework for Java and Spring applications. |
| **[Stack Auth](https://github.com/stack-auth/stack-auth)** | [![Stack Auth Stars](https://img.shields.io/github/stars/stack-auth/stack-auth?style=social&color=white)](https://github.com/stack-auth/stack-auth/stargazers) | Apache-2.0 | Open-source Auth0/Clerk alternative focused on modern Next.js/React developer experience. |
| **[Authgear](https://github.com/authgear/authgear-server)** | [![Authgear Stars](https://img.shields.io/github/stars/authgear/authgear-server?style=social&color=white)](https://github.com/authgear/authgear-server/stargazers) | Apache-2.0 | Open-source Auth0 alternative for web/mobile with passkeys, 2FA, OIDC, and passwordless authentication. |
| **[Caddy Security](https://github.com/greenpau/caddy-security)** | [![Caddy Security Stars](https://img.shields.io/github/stars/greenpau/caddy-security?style=social&color=white)](https://github.com/greenpau/caddy-security/stargazers) | Apache-2.0 | Authentication, Authorization, and Accounting (AAA) plugin for Caddy v2 with OIDC and SAML. |
| **[SSOReady](https://github.com/ssoready/ssoready)** | [![SSOReady Stars](https://img.shields.io/github/stars/ssoready/ssoready?style=social&color=white)](https://github.com/ssoready/ssoready/stargazers) | MIT | Open-source developer tools for enterprise SAML SSO and SCIM user provisioning. |
| **[ArkID](https://github.com/longguikeji/arkid)** | [![ArkID Stars](https://img.shields.io/github/stars/longguikeji/arkid?style=social&color=white)](https://github.com/longguikeji/arkid/stargazers) | Apache-2.0 | Unified identity authentication & authorization management solution supporting LDAP, OAuth2, and SAML. |
| **[Authorizer](https://github.com/authorizerdev/authorizer)** | [![Authorizer Stars](https://img.shields.io/github/stars/authorizerdev/authorizer?style=social&color=white)](https://github.com/authorizerdev/authorizer/stargazers) | Bootstrapped | Open-source auth solution for Kubernetes / Docker with GraphQL APIs, social logins, and admin panel. |
| **[SimpleSAMLphp](https://github.com/simplesamlphp/simplesamlphp)** | [![SimpleSAMLphp Stars](https://img.shields.io/github/stars/simplesamlphp/simplesamlphp?style=social&color=white)](https://github.com/simplesamlphp/simplesamlphp/stargazers) | LGPL-2.1 | Mature PHP application for SAML 2.0 service provider and identity provider federation. |
| **[Jackson (BoxyHQ)](https://github.com/boxyhq/jackson)** | [![Jackson Stars](https://img.shields.io/github/stars/boxyhq/jackson?style=social&color=white)](https://github.com/boxyhq/jackson/stargazers) | Apache-2.0 | Enterprise SSO & SCIM service for SAML/OIDC identity providers with modern developer APIs. |
| **[OpenAM](https://github.com/OpenIdentityPlatform/OpenAM)** | [![OpenAM Stars](https://img.shields.io/github/stars/OpenIdentityPlatform/OpenAM?style=social&color=white)](https://github.com/OpenIdentityPlatform/OpenAM/stargazers) | CDDL-1.0 | Open access management platform for authentication, SSO, entitlement management, and identity federation. |
| **[TheIdServer](https://github.com/Aguafrommars/TheIdServer)** | [![TheIdServer Stars](https://img.shields.io/github/stars/Aguafrommars/TheIdServer?style=social&color=white)](https://github.com/Aguafrommars/TheIdServer/stargazers) | Apache-2.0 | OpenID Connect, OAuth 2.0, WS-Fed, and SAML 2.0 Identity Provider based on Duende IdentityServer for .NET. |
| **[Idenplane](https://github.com/idenplane/idenplane)** | [![Idenplane Stars](https://img.shields.io/github/stars/idenplane/idenplane?style=social&color=white)](https://github.com/idenplane/idenplane/stargazers) | MIT | Lightweight IAM server in TypeScript/NestJS running in ~150 MB RAM with OIDC/SAML/SCIM support. |
| **[Janssen Project](https://github.com/JanssenProject/jans)** | [![Janssen Stars](https://img.shields.io/github/stars/JanssenProject/jans?style=social&color=white)](https://github.com/JanssenProject/jans/stargazers) | Apache-2.0 | Cloud-native IAM platform under the Linux Foundation featuring Agama low-code identity orchestration. |
| **[Authly](https://github.com/abhiraheja/authly)** | [![Authly Stars](https://img.shields.io/github/stars/abhiraheja/authly?style=social&color=white)](https://github.com/abhiraheja/authly/stargazers) | MIT | Self-hostable IDaaS with OAuth2/OIDC, WhatsApp OTP, multi-tenancy, and passkeys. |

---

## Architecture Guide: Choosing the Right Auth Strategy

- **For Next.js / React Apps:** [Clerk](https://clerk.com/) or [Stack Auth](https://github.com/stack-auth/stack-auth) for fastest integration and pre-built UI components.
- **For B2B Enterprise SaaS (SSO/SCIM):** [WorkOS](https://workos.com/), [SSOReady](https://github.com/ssoready/ssoready), or [BoxyHQ Jackson](https://github.com/boxyhq/jackson).
- **For Passwordless & Passkey-First:** [Stytch](https://stytch.com/), [Hanko](https://www.hanko.io/), or [Magic](https://magic.link/).
- **For Self-Hosted Enterprise IAM:** [Keycloak](https://github.com/keycloak/keycloak), [Zitadel](https://github.com/zitadel/zitadel), or [Authentik](https://github.com/goauthentik/authentik).
- **For Microservices & Custom Flows:** [Ory Kratos](https://github.com/ory/kratos) or [SuperTokens](https://github.com/supertokens/supertokens-core).

---

## How to Contribute

1. Fork this repository.
2. Add/edit entries in `README.md` following the exact tabular or bullet format.
3. Include the project name, official website / repository link, key details (pricing/stars), and licensing.
4. Submit a Pull Request with a clear title and description.

---

## Disclaimer

- This list is **community-curated** for educational and architectural reference.
- Ensure all authentication systems implement security best practices (OAuth 2.0, OpenID Connect, SAML 2.0, FIDO2 WebAuthn) and comply with privacy regulations (GDPR, CCPA, SOC2).

---

**Maintained for developers, security engineers, system architects, and platform teams.**
