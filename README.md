# Global LEI & Corporate Tax ID Validator API — Python Client

[![PyPI version](https://img.shields.io/pypi/v/lei-validator-client.svg)](https://pypi.org/project/lei-validator-client/)
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/57865358-8bafe64c-1441-4fe3-ba7a-2d60bdeb7dc5)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![RapidAPI Listing](https://img.shields.io/badge/RapidAPI-Dedicated%20Listing-blueviolet)](https://rapidapi.com/noor-mkdad-apis-noor-mkdad-apis-default/api/global-lei-corporate-tax-id-validator-api)

Official zero-dependency Python client for **Global LEI & Corporate Tax ID Validator API**.

> Sub-5ms edge validation for ISO 17442 LEI (MOD 97-10), US EIN (IRS Campuses), Australian ABN/ACN (MOD-89), and UK Companies House CRN.

> 🔑 **Get your Dedicated API Key:** [Subscribe to Global LEI & Corporate Tax ID Validator API on RapidAPI](https://rapidapi.com/noor-mkdad-apis-noor-mkdad-apis-default/api/global-lei-corporate-tax-id-validator-api)

---

## 🚀 Installation

```bash
pip install lei-validator-client
```

---

## ⚡ Quickstart

```python
from lei_validator_client import LeiValidatorClient

# Zero config for sandbox testing, or pass your RapidAPI key for production
client = LeiValidatorClient(api_key="YOUR_RAPIDAPI_KEY")

result = client.validate({
    # Enter validation payload
})

print(result)
```

---

## 📚 API Reference

### `LeiValidatorClient(api_key=..., base_url=...)`
- `api_key` *(optional)*: RapidAPI Key (`x-rapidapi-key`).
- `base_url` *(optional)*: Direct edge worker override URL.

### `client.validate(payload)`
Dispatches standard validation / parse request with sub-5ms latency.

### `client.get_health()`
Checks edge isolate health and responsiveness.

---

## 🔗 Links
- 📖 [RapidAPI Documentation & Key](https://rapidapi.com/noor-mkdad-apis-noor-mkdad-apis-default/api/global-lei-corporate-tax-id-validator-api)

## 📄 License
MIT © Noor Mkdad
