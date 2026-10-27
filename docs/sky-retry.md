# sky-retry

Умные ретраи с экспоненциальной задержкой (backoff) и jitter.

## Установка

```bash
pip install sky-retry
npm install @skypackages/retry
SkyForge install sky-retry
```

## API Reference

### Python

#### `def retry(tries, delay, backoff, jitter, exceptions)`
Декоратор для повторных попыток с экспоненциальной задержкой.

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).