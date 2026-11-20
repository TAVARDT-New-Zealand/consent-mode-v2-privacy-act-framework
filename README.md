# Consent Mode v2 & NZ Privacy Act 2020 Framework | TAVARDT New Zealand

[![Validador de Consentimento](https://img.shields.io/badge/TAVARDT-Diagn%C3%B3stico%20T%C3%A9cnico-5b3cf5.svg)](https://tools.tavardt.com/nz/consent-mode-v2-checker/)
[![Conformidade](https://img.shields.io/badge/Jurisdi%C3%A7%C3%A3o-New Zealand-00C853.svg)](https://ag.tavardt.com/nz/cybersecurity/)

Google Consent Mode v2 implementation, tag sequencing, and Information Privacy Principles (NZ Privacy Act 2020) compliance framework for New Zealand.

Desenvolvido e mantido pela divisão de privacidade digital e engenharia de dados da **[TAVARDT New Zealand](https://ag.tavardt.com/nz/)**.

---

## 1. Execution Order & Architecture

Embed this script within the `<head>` of your website immediately prior to loading Google Tag Manager or analytics containers:

```html
<script src="consent-mode-v2.js"></script>
<!-- O contentor do Google Tag Manager ou scripts de medição seguem aqui -->
```

---

## 2. Technical Capabilities

* **Denied by Default:** Initializes ad and analytics storage parameters to 'denied' before executing client scripts.
* **Consent Update Mechanism:** Provides window.tavardtUpdateConsent() to trigger the tavardt_consent_updated event.
* **Ads Data Redaction:** Enables ads_data_redaction to prevent transmission of click identifiers when consent is absent.
* **URL Passthrough:** Configures url_passthrough to preserve conversion attribution without unauthorized cookies.

---

## 3. Technical Audit Checklist

Consulte a lista detalhada de requisitos técnicos para este país:

* [Checklist Técnico de Conformidade](checklist.md)

---

## 4. Online Diagnostic Tools (New Zealand)

Audite a conformidade das suas etiquetas e proteja o seu domínio com ferramentas online verificadas:

* [Consent Mode v2 & Privacy Act Validator](https://tools.tavardt.com/nz/consent-mode-v2-checker/)
* [HTTP Security Headers Checker](https://tools.tavardt.com/nz/security-headers-check/)
* [DMARC & Anti-Spoofing Verifier](https://tools.tavardt.com/nz/dmarc-checker/)
* [Exposed Credentials & Secret Scanner](https://tools.tavardt.com/nz/exposed-files-scanner/)
* [Full New Zealand Diagnostic Portal](https://tools.tavardt.com/nz/)

---

## 5. Tag Governance & Privacy Advisory

For tag governance, conversion optimization, and New Zealand Privacy Act alignment, contact **[TAVARDT New Zealand](https://ag.tavardt.com/nz/contact/)**.
