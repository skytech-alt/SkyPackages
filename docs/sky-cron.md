# sky-cron

Парсинг cron-выражений, вычисление следующего запуска, описание на русском.

## Установка

```bash
pip install sky-cron
npm install @skypackages/cron
SkyForge install sky-cron
```

## API Reference

### Python

#### `def _parse_field(field, min_val, max_val)`
*Документация отсутствует.*

#### `def parse(expr)`
Парсит 5-полевое cron-выражение.

#### `def is_valid(expr)`
*Документация отсутствует.*

#### `def next_run(expr, from_time)`
Вычисляет следующее время запуска после указанной даты.

#### `def describe(expr)`
Человекочитаемое описание на русском.

### TypeScript / JavaScript

#### `parse(expr)`
*Документация отсутствует.*

#### `isValid(expr)`
*Документация отсутствует.*

#### `nextRun(expr, fromTime)`
*Документация отсутствует.*

#### `describe(expr)`
*Документация отсутствует.*

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).