# sky-upc

## Установка

**Python:**
```bash
pip install sky-upc
```

**npm:**
```bash
npm install @skypackages/upc
```

**SkyForge:**
```bash
SkyForge install skyforge-upc
```

## Python API

### `is_valid(upc)`

### Пример использования

```python
from sky_upc import is_valid

is_valid(None)
```

## TypeScript / JavaScript API

### `isValid(upc)`

### Пример использования

```typescript
import { isValid } from "@skypackages/upc";

isValid(None);
```

## SkyForge

Валидация штрихкодов UPC-A.

```skyforge
пусть lib = подтянуть "skyforge-upc"
лог(lib.is_valid())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
