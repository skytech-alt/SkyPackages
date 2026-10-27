# sky-isbn

## О пакете

Проверяет ISBN-10 и ISBN-13.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-isbn-v0.1.0/sky_isbn-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/isbn
```

**SkyForge:**
```bash
SkyForge install skyforge-isbn
```

## API

### `is_valid_isbn10(isbn) → bool`

**Параметры:**

- `isbn` — строка

**Возвращает:** `bool`

**Пример:**

```python
from sky_isbn import is_valid_isbn10

result = is_valid_isbn10(10)
print(result)
```

### `is_valid_isbn13(isbn) → bool`

**Параметры:**

- `isbn` — строка

**Возвращает:** `bool`

**Пример:**

```python
from sky_isbn import is_valid_isbn13

result = is_valid_isbn13(10)
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
