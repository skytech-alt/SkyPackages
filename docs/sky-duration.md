# sky-duration

Парсинг и форматирование временных интервалов и размеров файлов.

## Установка

```bash
pip install sky-duration
npm install @skypackages/duration
SkyForge install sky-duration
```

## API Reference

### Python

#### `def parse_size(text)`
Парсит строку размера в байты. Пример: '1.5 GB' -> 1610612736.

#### `def format_size(bytes_val)`
Форматирует байты в строку. Пример: 1610612736 -> '1.5 GB'.

#### `def parse_duration(text)`
Парсит строку времени в секунды. Пример: '1h 30m' -> 5400.

#### `def format_duration(seconds)`
Форматирует секунды в строку. Пример: 5400 -> '1h 30m'.

### TypeScript / JavaScript

#### `parseSize(text)`
*Документация отсутствует.*

#### `formatSize(bytesVal)`
*Документация отсутствует.*

#### `parseDuration(text)`
*Документация отсутствует.*

#### `formatDuration(seconds)`
*Документация отсутствует.*

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).