# sky-user-agent

## Установка

**Python:**
```bash
pip install sky-user-agent
```

**npm:**
```bash
npm install @skypackages/user-agent
```

**SkyForge:**
```bash
SkyForge install skyforge-user-agent
```

## Python API

### `is_mobile(ua)`

### `is_desktop(ua)`

### Пример использования

```python
from sky_user_agent import is_mobile

is_mobile(None)
```

## TypeScript / JavaScript API

### `isMobile(ua)`

### `isDesktop(ua)`

### Пример использования

```typescript
import { isMobile } from "@skypackages/user-agent";

isMobile(None);
```

## SkyForge

Определение мобильный/десктоп по User-Agent.

```skyforge
пусть lib = подтянуть "skyforge-user-agent"
лог(lib.is_mobile())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
