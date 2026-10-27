# sky-ansi

## Установка

**Python:**
```bash
pip install sky-ansi
```

**npm:**
```bash
npm install @skypackages/ansi
```

**SkyForge:**
```bash
SkyForge install skyforge-ansi
```

## Python API

### `colorize(text, color)`

### `strip_ansi(text)`

### Пример использования

```python
from sky_ansi import colorize

colorize("example", None)
```

## TypeScript / JavaScript API

### `colorize(text, color)`

### `stripAnsi(text)`

### Пример использования

```typescript
import { colorize } from "@skypackages/ansi";

colorize("example", None);
```

## SkyForge

ANSI-цвета и стили для терминала.

```skyforge
пусть lib = подтянуть "skyforge-ansi"
лог(lib.colorize())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
