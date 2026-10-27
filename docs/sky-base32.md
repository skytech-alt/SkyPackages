# sky-base32

## Установка

**Python:**
```bash
pip install sky-base32
```

**npm:**
```bash
npm install @skypackages/base32
```

**SkyForge:**
```bash
SkyForge install skyforge-base32
```

## Python API

### `encode(text)`

### `decode(b32_text)`

### Пример использования

```python
from sky_base32 import encode

encode("example")
```

## TypeScript / JavaScript API

### `encode(text)`

### `decode(b32)`

### Пример использования

```typescript
import { encode } from "@skypackages/base32";

encode("example");
```

## SkyForge

Кодирование и декодирование Base32.

```skyforge
пусть lib = подтянуть "skyforge-base32"
лог(lib.encode())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
