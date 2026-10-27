# sky-base64

## Установка

**Python:**
```bash
pip install sky-base64
```

**npm:**
```bash
npm install @skypackages/base64
```

**SkyForge:**
```bash
SkyForge install skyforge-base64
```

## Python API

### `encode(text)`

### `decode(b64_text)`

### `encode_url_safe(text)`

### `decode_url_safe(b64_text)`

### Пример использования

```python
from sky_base64 import encode

encode("example")
```

## TypeScript / JavaScript API

### `encode(text)`

### `decode(b64)`

### `encodeUrlSafe(text)`

### `decodeUrlSafe(b64)`

### Пример использования

```typescript
import { encode } from "@skypackages/base64";

encode("example");
```

## SkyForge

Кодирование и декодирование Base64 (включая URL-safe).

```skyforge
пусть lib = подтянуть "skyforge-base64"
лог(lib.encode())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
