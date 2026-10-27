# sky-ean

## Установка

**Python:**
```bash
pip install sky-ean
```

**npm:**
```bash
npm install @skypackages/ean
```

**SkyForge:**
```bash
SkyForge install skyforge-ean
```

## Python API

### `is_valid(ean)`

### Пример использования

```python
from sky_ean import is_valid

is_valid(None)
```

## TypeScript / JavaScript API

### `isValid(ean)`

### Пример использования

```typescript
import { isValid } from "@skypackages/ean";

isValid(None);
```

## SkyForge

Валидация штрихкодов EAN-13.

```skyforge
пусть lib = подтянуть "skyforge-ean"
лог(lib.is_valid())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
