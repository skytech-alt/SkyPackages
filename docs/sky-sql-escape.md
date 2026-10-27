# sky-sql-escape

## Установка

**Python:**
```bash
pip install sky-sql-escape
```

**npm:**
```bash
npm install @skypackages/sql-escape
```

**SkyForge:**
```bash
SkyForge install skyforge-sql-escape
```

## Python API

### `escape_string(text)`

### `quote_string(text)`

### Пример использования

```python
from sky_sql_escape import escape_string

escape_string("example")
```

## TypeScript / JavaScript API

### `escapeString(text)`

### `quoteString(text)`

### Пример использования

```typescript
import { escapeString } from "@skypackages/sql-escape";

escapeString("example");
```

## SkyForge

Безопасное экранирование SQL-строк.

```skyforge
пусть lib = подтянуть "skyforge-sql-escape"
лог(lib.escape_string())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
