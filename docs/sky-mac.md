# sky-mac

## Установка

**Python:**
```bash
pip install sky-mac
```

**npm:**
```bash
npm install @skypackages/mac
```

**SkyForge:**
```bash
SkyForge install skyforge-mac
```

## Python API

### `is_valid(mac)`

### `format_mac(mac)`

### Пример использования

```python
from sky_mac import is_valid

is_valid(None)
```

## TypeScript / JavaScript API

### `isValid(mac)`

### `formatMac(mac)`

### Пример использования

```typescript
import { isValid } from "@skypackages/mac";

isValid(None);
```

## SkyForge

Валидация и форматирование MAC-адресов.

```skyforge
пусть lib = подтянуть "skyforge-mac"
лог(lib.is_valid())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
