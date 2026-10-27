# sky-i18n

## Установка

**Python:**
```bash
pip install sky-i18n
```

**npm:**
```bash
npm install @skypackages/i18n
```

**SkyForge:**
```bash
SkyForge install skyforge-i18n
```

## Python API

### `add(lang, key, value)`

### `t(key, lang, default)`

### Пример использования

```python
from sky_i18n import add

add(None, "key", "value")
```

## TypeScript / JavaScript API

### `add(lang, key, value)`

### `t(key, lang, defaultValue)`

### Пример использования

```typescript
import { add } from "@skypackages/i18n";

add(None, "key", "value");
```

## SkyForge

Простой словарь для локализации.

```skyforge
пусть lib = подтянуть "skyforge-i18n"
лог(lib.add())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
