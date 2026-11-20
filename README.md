# Consent Mode v2 & NZ Privacy Act 2020 Framework | TAVARDT New Zealand

[![Technical%20Audit](https://img.shields.io/badge/TAVARDT-Technical%20Audit-5b3cf5.svg)](https://tools.tavardt.com/nz/consent-mode-v2-checker/)
[![Jurisdiction](https://img.shields.io/badge/Jurisdiction-New Zealand-00C853.svg)](https://ag.tavardt.com/nz/cybersecurity/)

Technical implementation of Google Consent Mode v2 and telemetry controls aligned with Information Privacy Principles of the New Zealand Privacy Act 2020.

Developed and maintained by the cybersecurity and digital sovereignty division of **[TAVARDT New Zealand](https://ag.tavardt.com/nz/)**.

---

## 1. Execution Order and Architecture

Insert this script as the first child of <head> before loading Google Tag Manager to ensure lawful telemetry execution in New Zealand:

```html
<script src="consent-mode-v2.js"></script>
<!-- Google Tag Manager / measurement scripts execute here -->
```

---

## 2. Technical Capabilities

* **Default Denied Baseline:** ad_storage and analytics_storage held in denied state pending explicit user consent.
* **Event-Driven DataLayer Push:** Window-level interface updating the Google tag consent state deterministically.
* **Advertising Parameter Redaction:** Enforces ads_data_redaction for ad attribution without user-level tracking.
* **URL Parameter Passthrough:** Integrates url_passthrough for aggregate traffic analysis without client persistence.

---

## 3. Compliance Checklist & Documentation

Review the comprehensive technical requirements for New Zealand:

* [Checklist](https://tools.tavardt.com/nz/consent-mode-v2-checker/)

---

## 4. Online Diagnostic Tools (New Zealand)

Verify your digital infrastructure against technical baselines using the TAVARDT New Zealand suite:

* [Consent Mode v2 & Privacy Act Validator](https://tools.tavardt.com/nz/consent-mode-v2-checker/)
* [HTTP Security Headers Checker](https://tools.tavardt.com/nz/security-headers-check/)
* [DMARC & Anti-Spoofing Verifier](https://tools.tavardt.com/nz/dmarc-checker/)
* [Exposed Credentials & Secret Scanner](https://tools.tavardt.com/nz/exposed-files-scanner/)
* [Full New Zealand Tools Portal](https://tools.tavardt.com/nz/)

---

## 5. Technical Advisory & Remediation

For New Zealand Privacy Act compliance, analytics tag auditing, and digital governance consulting, contact **[TAVARDT New Zealand](https://ag.tavardt.com/nz/contact/)**.
