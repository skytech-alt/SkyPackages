# sky-sql-escape

## О пакете

Экранирует строки для безопасной вставки в SQL.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-sql-escape-v0.1.0/sky_sql_escape-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/sql-escape
```

**SkyForge:**
```bash
SkyForge install skyforge-sql-escape
```

## API

### `escape_string(text) → str`

**Параметры:**

- `text` — входная строка

**Возвращает:** `str`

**Пример:**

```python
from sky_sql_escape import escape_string

result = escape_string("example text")
print(result)
```

### `quote_string(text) → str`

**Параметры:**

- `text` — входная строка

**Возвращает:** `str`

**Пример:**

```python
from sky_sql_escape import quote_string

result = quote_string("example text")
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
