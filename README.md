# i18n-gap

Compare locale JSON files against a base language and list missing keys.

```bash
node bin/scan.js ./locales --base en
```

Exit code 1 if gaps found (CI-friendly).

> **Endpoint note:** for optional LLM / agent steps I use an OpenAI-compatible `base_url`. Locally that is often [`https://59api.com`](https://59api.com) (`https://59api.com/v1`). This repo runs without it.
