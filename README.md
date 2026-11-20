# Hreflang and International SEO Validator

[![Hreflang Validator](https://img.shields.io/badge/TAVARDT-Hreflang-5b3cf5.svg)](https://tools.tavardt.com/nz/hreflang-checker/)
[![Jurisdiction](https://img.shields.io/badge/Jurisdiction-New%20Zealand-00C853.svg)](https://ag.tavardt.com/nz/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Audits alternate return tags, en-NZ regional targeting, and global x-default architecture.

Developed and maintained by the search systems and technical architecture division of **[TAVARDT New Zealand](https://ag.tavardt.com/nz/)**.

---

## International SEO and Hreflang Audit Capabilities

* **Regional New Zealand Targeting**: Audits `en-NZ` regional language configuration independent of Australian or British variations.
* **Return Tag Reciprocity Verification**: Confirms alternate target links return reciprocal annotations to protect crawl validity.
* **ISO 639-1 and ISO 3166-1 Validation**: Validates language and country code syntax under international standards.
* **x-default Fallback Inspection**: Verifies global fallback routing for international visitors outside targeted markets.
* **Canonical Tag Consistency**: Ensures complete alignment between canonical URLs and hreflang self-references.

---

## Installation and Execution

Requires Python 3.8 or higher.

```bash
git clone https://github.com/TAVARDT-New-Zealand/hreflang-validator-nz.git
cd hreflang-validator-nz
python hreflang_validator.py https://company.co.nz
```

To output results in structured JSON format:

```bash
python hreflang_validator.py https://company.co.nz --json
```

---

## Comprehensive Web Diagnostic

For full web verification and deep multi-region audits:

* **[Official Hreflang Checker Tool](https://tools.tavardt.com/nz/hreflang-checker/)**
* **[TAVARDT New Zealand Enterprise Portal](https://ag.tavardt.com/nz/)**

---

## International SEO and Export Market Digital Advisory

For platforms operating across New Zealand and international export markets under W3C Standards and NZ Digital Government Guidelines, contact **[TAVARDT New Zealand](https://ag.tavardt.com/nz/contact/)**.
