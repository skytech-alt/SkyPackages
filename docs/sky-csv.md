# sky-csv

Парсинг и генерация CSV с точкой с запятой и BOM для Excel.

## Установка

```bash
pip install sky-csv
npm install @skypackages/csv
SkyForge install sky-csv
```

## API Reference

### Python

#### `def parse_csv(text, delimiter)`
Парсит CSV в список словарей (как Excel).

#### `def to_csv(data, delimiter, add_bom)`
Генерирует CSV с BOM для корректного открытия в Excel.

### TypeScript / JavaScript

#### `parseCsv(text, delimiter)`
*Документация отсутствует.*

#### `toCsv(data, string>[], delimiter, addBom)`
*Документация отсутствует.*

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).