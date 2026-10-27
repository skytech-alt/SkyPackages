# sky-csv

## О пакете

Парсинг и генерация CSV с точкой с запятой и BOM для Excel.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-csv-v0.1.0/sky_csv-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/csv
```

**SkyForge:**
```bash
SkyForge install skyforge-csv
```

## API

### `parse_csv(text, delimiter=';') → list[dict]`

Парсит CSV в список словарей (как Excel).

**Параметры:**

- `text` — входная строка
- `delimiter` — символ-разделитель (по умолчанию `';'`)

**Возвращает:** `list[dict]`

**Пример:**

```python
from sky_csv import parse_csv

result = parse_csv("example text", 0.5)
print(result)
```

### `to_csv(data, delimiter=';', add_bom=True) → str`

Генерирует CSV с BOM для корректного открытия в Excel.

**Параметры:**

- `data` — первое значение
- `delimiter` — символ-разделитель (по умолчанию `';'`)
- `add_bom` — первое значение (по умолчанию `True`)

**Возвращает:** `str`

**Пример:**

```python
from sky_csv import to_csv

result = to_csv(12, 0.5, 12)
print(result)
```

## Типичные сценарии

- Использование в CLI, веб-приложениях и микросервисах
- Быстрое подключение без внешних зависимостей
- Единый API для Python, JavaScript и SkyForge

## Ограничения

- Пакет проверяет структуру и формат, но не заменяет проверку через внешние API (например, ФНС)
- Для некоторых задач требуется предварительная нормализация входных данных
- Зависимостей нет, но для AES-шифрования в Python версии нужен пакет `cryptography` (указан в зависимостях)

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
