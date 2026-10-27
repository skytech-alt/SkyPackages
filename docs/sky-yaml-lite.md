# sky-yaml-lite

## Установка

**Python:**
```bash
pip install sky-yaml-lite
```

**npm:**
```bash
npm install @skypackages/yaml-lite
```

**SkyForge:**
```bash
SkyForge install skyforge-yaml-lite
```

## Python API

### `parse(text)`

### `dump(data)`

### Пример использования

```python
from sky_yaml_lite import parse

parse("example")
```

## TypeScript / JavaScript API

### `parse(text)`

### `dump(data, string>)`

### Пример использования

```typescript
import { parse } from "@skypackages/yaml-lite";

parse("example");
```

## SkyForge

Минимальный парсер YAML (плоские ключи).

```skyforge
пусть lib = подтянуть "skyforge-yaml-lite"
лог(lib.parse())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
