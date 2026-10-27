# sky-timestamp

## Установка

**Python:**
```bash
pip install sky-timestamp
```

**npm:**
```bash
npm install @skypackages/timestamp
```

**SkyForge:**
```bash
SkyForge install skyforge-timestamp
```

## Python API

### `to_iso(ts)`

### `from_iso(iso)`

### Пример использования

```python
from sky_timestamp import to_iso

to_iso(None)
```

## TypeScript / JavaScript API

### `toIso(ts)`

### `fromIso(iso)`

### Пример использования

```typescript
import { toIso } from "@skypackages/timestamp";

toIso(None);
```

## SkyForge

Unix timestamp в ISO 8601 и обратно.

```skyforge
пусть lib = подтянуть "skyforge-timestamp"
лог(lib.to_iso())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
