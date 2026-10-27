# sky-csv

## Установка

**Python:**
```bash
pip install sky-csv
```

**npm:**
```bash
npm install @skypackages/csv
```

**SkyForge:**
```bash
SkyForge install skyforge-csv
```

## Python API

### `parse_csv(text, delimiter)`

Парсит CSV в список словарей (как Excel).

### `to_csv(data, delimiter, add_bom)`

Генерирует CSV с BOM для корректного открытия в Excel.

### Пример использования

```python
from sky_csv import parse_csv

parse_csv("example", None)
```

## TypeScript / JavaScript API

### `parseCsv(text, delimiter)`

### `toCsv(data, string>[], delimiter, addBom)`

### Пример использования

```typescript
import { parseCsv } from "@skypackages/csv";

parseCsv("example", None);
```

## SkyForge

Парсинг и генерация CSV с точкой с запятой и BOM для Excel.

```skyforge
пусть lib = подтянуть "skyforge-csv"
лог(lib.parse_csv())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
