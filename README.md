# Consent Mode v2 & NZ Privacy Act 2020 Framework | TAVARDT New Zealand

[![Privacy Compliance](https://img.shields.io/badge/Compliance-Consent%20Mode%20v2-5b3cf5.svg)](https://tools.tavardt.com/nz/)
[![Regulatory Standard](https://img.shields.io/badge/Region-NZD-00C853.svg)](https://ag.tavardt.com/nz/)

Google Consent Mode v2 implementation, tag sequencing, and Information Privacy Principles (NZ Privacy Act 2020) compliance framework.

Maintained by the analytics, privacy engineering, and cybersecurity division at [TAVARDT New Zealand](https://ag.tavardt.com/nz/).

---

## 1. Architecture & Execution Order

To achieve full compliance with New Zealand Privacy Act 2020 (IPPs) & CERT NZ, this snippet must be positioned in the `<head>` of your website **immediately before** your Google Tag Manager container or tracking loader:

```html
<script src="consent-mode-v2.js"></script>
<!-- Google Tag Manager / Analytics Script Follows Here -->
```

---

## 2. Core Capabilities

* **Strict Default 'Denied' Posture:** Enforces privacy by default across all advertising, telemetry, and personal identifier parameters.
* **Consent Update API:** Provides an event-driven `window.tavardtUpdateConsent()` method that triggers a structured `tavardt_consent_updated` dataLayer event.
* **Ads Data Redaction:** Automatically strips click identifiers (such as GCLID and DCLID) from ad requests when marketing consent is absent.
* **URL Passthrough:** Preserves conversion attribution across domain boundaries using cryptographic hashes without storing persistent browser cookies.

---

## 3. Compliance Documentation

Review our jurisdictional implementation guidelines:

* [Technical Checklist](checklist.md): Step-by-step audit points for tag governance under New Zealand Privacy Act 2020 (IPPs) & CERT NZ.

---

## 4. Online Diagnostic Suite

Audit your public web applications and verify tracking privacy on our regional testing platform:

* [Online HTTP Security Headers Checker](https://tools.tavardt.com/nz/security-headers-check/)
* [Exposed Credentials Scanner](https://tools.tavardt.com/nz/exposed-files-scanner/)
* [DMARC & Anti-Spoofing Verifier](https://tools.tavardt.com/nz/dmarc-checker/)
* [Complete Regional Diagnostic Suite](https://tools.tavardt.com/nz/)

For comprehensive conversion tracking audits, consent management implementation, and technical consulting, contact [TAVARDT New Zealand](https://ag.tavardt.com/nz/contact/).
