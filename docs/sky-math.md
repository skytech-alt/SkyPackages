# sky-math

## Установка

**Python:**
```bash
pip install sky-math
```

**npm:**
```bash
npm install @skypackages/math
```

**SkyForge:**
```bash
SkyForge install skyforge-math
```

## Python API

### `clamp(value, min_val, max_val)`

Ограничивает значение в диапазоне [min_val, max_val].

### `lerp(start, end, t)`

Линейная интерполяция между start и end на t (0..1).

### `percentage(part, total)`

Вычисляет процент part от total.

### Пример использования

```python
from sky_math import clamp

clamp("value", None, None)
```

## TypeScript / JavaScript API

### `clamp(value, minVal, maxVal)`

### `lerp(start, end, t)`

### `percentage(part, total)`

### Пример использования

```typescript
import { clamp } from "@skypackages/math";

clamp("value", None, None);
```

## SkyForge

Математические утилиты: clamp, lerp, проценты.

```skyforge
пусть lib = подтянуть "skyforge-math"
лог(lib.clamp())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
