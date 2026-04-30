# CI-001 Canary Test Repo

Disposable repository for validating whether a pull_request workflow receives a dummy OPENAI_API_KEY secret in an attacker-controlled PR context.

Do not store real secrets here. Use only:

```text
OPENAI_API_KEY=ci001_dummy_canary_no_real_access
```
