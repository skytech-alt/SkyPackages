# sky-units

## Установка

**Python:**
```bash
pip install sky-units
```

**npm:**
```bash
npm install @skypackages/units
```

**SkyForge:**
```bash
SkyForge install skyforge-units
```

## Python API

### `km_to_miles(km)`

### `miles_to_km(miles)`

### `kg_to_lbs(kg)`

### `celsius_to_fahrenheit(c)`

### Пример использования

```python
from sky_units import km_to_miles

km_to_miles(None)
```

## TypeScript / JavaScript API

### `kmToMiles(km)`

### `milesToKm(miles)`

### `kgToLbs(kg)`

### `celsiusToFahrenheit(c)`

### Пример использования

```typescript
import { kmToMiles } from "@skypackages/units";

kmToMiles(None);
```

## SkyForge

Конвертер единиц измерения (длина, вес, температура).

```skyforge
пусть lib = подтянуть "skyforge-units"
лог(lib.km_to_miles())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
