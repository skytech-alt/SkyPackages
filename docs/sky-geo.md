# sky-geo

## Установка

**Python:**
```bash
pip install sky-geo
```

**npm:**
```bash
npm install @skypackages/geo
```

**SkyForge:**
```bash
SkyForge install skyforge-geo
```

## Python API

### `haversine(lat1, lon1, lat2, lon2)`

### Пример использования

```python
from sky_geo import haversine

haversine(None, None, None, None)
```

## TypeScript / JavaScript API

### `haversine(lat1, lon1, lat2, lon2)`

### Пример использования

```typescript
import { haversine } from "@skypackages/geo";

haversine(None, None, None, None);
```

## SkyForge

Расчет расстояния между GPS-координатами (формула гаверсинуса).

```skyforge
пусть lib = подтянуть "skyforge-geo"
лог(lib.haversine())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
