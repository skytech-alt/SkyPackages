# sky-url

## Установка

**Python:**
```bash
pip install sky-url
```

**npm:**
```bash
npm install @skypackages/url
```

**SkyForge:**
```bash
SkyForge install skyforge-url
```

## Python API

### `parse_url(url)`

### `add_utm(url, source, medium, campaign)`

### Пример использования

```python
from sky_url import parse_url

parse_url(None)
```

## TypeScript / JavaScript API

### `parseUrl(url)`

### `addUtm(url, source, medium, campaign)`

### Пример использования

```typescript
import { parseUrl } from "@skypackages/url";

parseUrl(None);
```

## SkyForge

Разбор URL и генерация UTM-меток.

```skyforge
пусть lib = подтянуть "skyforge-url"
лог(lib.parse_url())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
