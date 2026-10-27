# sky-morse

## Установка

**Python:**
```bash
pip install sky-morse
```

**npm:**
```bash
npm install @skypackages/morse
```

**SkyForge:**
```bash
SkyForge install skyforge-morse
```

## Python API

### `to_morse(text)`

### `from_morse(morse)`

### Пример использования

```python
from sky_morse import to_morse

to_morse("example")
```

## TypeScript / JavaScript API

### `toMorse(text)`

### `fromMorse(morse)`

### Пример использования

```typescript
import { toMorse } from "@skypackages/morse";

toMorse("example");
```

## SkyForge

Азбука Морзе: кодирование и декодирование.

```skyforge
пусть lib = подтянуть "skyforge-morse"
лог(lib.to_morse())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
