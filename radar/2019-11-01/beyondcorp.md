---
title:      "ZeroTrust"
ring:       trial
quadrant:   methods-and-patterns
---

ZeroTrust is a paradigm where no trust is assumed inside a known network.

With Zero Trust no assumption is made about how far something can be trusted, everything is untrusted by default and authentication and authorization happens all the time, not just once.

Frameworks such as Google's BeyondCorp are build upon that pattern.

## Motivation and History
Classical security paradigms tend to protect a certain network perimeter - such as the company intranet.
Once someone in "inside" - e.g. by working inside the company network or connecting to it via VPN - he is more or less "trusted".

With the surge of cloud technologies and microservices, the trend that everything is more distributed and people working from anywhere: That security model is not sufficient. The network perimeter is ever disappearing.

This provides challenges for authentication of subjects that used to heavily rely on network segments.


## Principles of ZeroTrust
Zero Trust, assumes that no user, service or device should be trusted by default, regardless of their location or network. It requires continuous verification of identity, strict access controls, and consistent monitoring of network activity.

**Basic principles:**
* least privilege
* assume breach
* strong identity verification
* verify explicitly


It touches and involves a lot of **areas and aspects** - such as:
* Identities & Identity Awareness
* Device & Device Authentication
* Networking & Firewall
* Application Security (Security by Design, Secure Architecture)
* Infrastructure Security
* Secure Data Handling
* Organization and Culture
* Secure Development and Delivery
* Security Monitoring & Automation

## Implementations

In 2009 Google implemented a zero trust architecture referred to as BeyondCorp. 
It uses OAuth and OpenID standards to implement Authn and Authz and shaped the way how modern ZeroTrust architectures are build.

Typical implementations involve the usage of these standards and tools for IAM and SSO (e.g. using ["keycloak"](/tools/keycloak.html)).

## Summary
While network segments and VPN connections may still have relevance in specific areas AOE is increasingly implementing ZeroTrust in all solutions, components and services.

We are implementing ZeroTrust best practices which are oriented at the BeyondCorp framework and use the standards OAuth and OpenID Connect.

## More references
* [Talk about Zero Trust](https://www.youtube.com/watch?v=fCENO_Jt3QE)



