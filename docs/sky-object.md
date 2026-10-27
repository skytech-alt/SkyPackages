# sky-object

## Установка

**Python:**
```bash
pip install sky-object
```

**npm:**
```bash
npm install @skypackages/object
```

**SkyForge:**
```bash
SkyForge install skyforge-object
```

## Python API

### `safe_get(obj, path, default)`

Безопасно получает значение по пути 'a.b.c'.

### `deep_clone(obj)`

Глубокая копия объекта.

### `deep_merge(target, source)`

Сливает два словаря рекурсивно.

### Пример использования

```python
from sky_object import safe_get

safe_get(None, None, None)
```

## TypeScript / JavaScript API

### `safeGet(obj, unknown>, path, defaultValue)`

### `deepClone(obj)`

### Пример использования

```typescript
import { safeGet } from "@skypackages/object";

safeGet(None, None, None, "value");
```

## SkyForge

Безопасная работа с объектами: deep get, merge, clone.

```skyforge
пусть lib = подтянуть "skyforge-object"
лог(lib.safe_get())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
