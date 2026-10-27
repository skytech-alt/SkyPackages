# sky-pad

## Установка

**Python:**
```bash
pip install sky-pad
```

**npm:**
```bash
npm install @skypackages/pad
```

**SkyForge:**
```bash
SkyForge install skyforge-pad
```

## Python API

### `pad_left(text, length, char)`

### `pad_right(text, length, char)`

### `pad_center(text, length, char)`

### Пример использования

```python
from sky_pad import pad_left

pad_left("example", None, None)
```

## TypeScript / JavaScript API

### `padLeft(text, length, char)`

### `padRight(text, length, char)`

### `padCenter(text, length, char)`

### Пример использования

```typescript
import { padLeft } from "@skypackages/pad";

padLeft("example", None, None);
```

## SkyForge

Выравнивание строки (слева, справа, по центру).

```skyforge
пусть lib = подтянуть "skyforge-pad"
лог(lib.pad_left())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
