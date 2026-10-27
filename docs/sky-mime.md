# sky-mime

## Установка

**Python:**
```bash
pip install sky-mime
```

**npm:**
```bash
npm install @skypackages/mime
```

**SkyForge:**
```bash
SkyForge install skyforge-mime
```

## Python API

### `get_mime(extension)`

### Пример использования

```python
from sky_mime import get_mime

get_mime(None)
```

## TypeScript / JavaScript API

### `getMime(extension)`

### Пример использования

```typescript
import { getMime } from "@skypackages/mime";

getMime(None);
```

## SkyForge

Определение MIME-типа по расширению файла.

```skyforge
пусть lib = подтянуть "skyforge-mime"
лог(lib.get_mime())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
