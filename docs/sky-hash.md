# sky-hash

## Установка

**Python:**
```bash
pip install sky-hash
```

**npm:**
```bash
npm install @skypackages/hash
```

**SkyForge:**
```bash
SkyForge install skyforge-hash
```

## Python API

### `djb2(text)`

### `fnv1a(text)`

### Пример использования

```python
from sky_hash import djb2

djb2("example")
```

## TypeScript / JavaScript API

### `djb2(text)`

### `fnv1a(text)`

### Пример использования

```typescript
import { djb2 } from "@skypackages/hash";

djb2("example");
```

## SkyForge

Быстрые не-криптографические хеши (djb2, fnv1a).

```skyforge
пусть lib = подтянуть "skyforge-hash"
лог(lib.djb2())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
