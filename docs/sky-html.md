# sky-html

## Установка

**Python:**
```bash
pip install sky-html
```

**npm:**
```bash
npm install @skypackages/html
```

**SkyForge:**
```bash
SkyForge install skyforge-html
```

## Python API

### `escape(text)`

Экранирует спецсимволы HTML.

### `unescape(text)`

Разэкранирует HTML-сущности.

### Пример использования

```python
from sky_html import escape

escape("example")
```

## TypeScript / JavaScript API

### `escape(text)`

### `unescape(text)`

### Пример использования

```typescript
import { escape } from "@skypackages/html";

escape("example");
```

## SkyForge

Экранирование и разэкранирование HTML-сущностей.

```skyforge
пусть lib = подтянуть "skyforge-html"
лог(lib.escape())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
