# sky-braille

## Установка

**Python:**
```bash
pip install sky-braille
```

**npm:**
```bash
npm install @skypackages/braille
```

**SkyForge:**
```bash
SkyForge install skyforge-braille
```

## Python API

### `to_braille(text)`

### Пример использования

```python
from sky_braille import to_braille

to_braille("example")
```

## TypeScript / JavaScript API

### `toBraille(text)`

### Пример использования

```typescript
import { toBraille } from "@skypackages/braille";

toBraille("example");
```

## SkyForge

Текст в шрифт Брайля (латиница).

```skyforge
пусть lib = подтянуть "skyforge-braille"
лог(lib.to_braille())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
