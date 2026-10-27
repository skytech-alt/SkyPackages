# sky-toml

## Установка

**Python:**
```bash
pip install sky-toml
```

**npm:**
```bash
npm install @skypackages/toml
```

**SkyForge:**
```bash
SkyForge install skyforge-toml
```

## Python API

### `parse(text)`

### Пример использования

```python
from sky_toml import parse

parse("example")
```

## TypeScript / JavaScript API

### `parse(text)`

### Пример использования

```typescript
import { parse } from "@skypackages/toml";

parse("example");
```

## SkyForge

Парсинг TOML (плоские ключи).

```skyforge
пусть lib = подтянуть "skyforge-toml"
лог(lib.parse())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
