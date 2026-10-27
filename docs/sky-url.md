# sky-url

## О пакете

Пакет `sky-url` для типовых задач разработки.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-url-v0.1.0/sky_url-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/url
```

**SkyForge:**
```bash
SkyForge install skyforge-url
```

## API

### `parse_url(url) → dict`

**Параметры:**

- `url` — аргумент функции

**Возвращает:** `dict`

**Пример:**

```python
from sky_url import parse_url

result = parse_url("https://example.com/path?x=1")
print(result)
```

### `add_utm(url, source, medium, campaign) → str`

**Параметры:**

- `url` — аргумент функции
- `source` — строка
- `medium` — аргумент функции
- `campaign` — целое число

**Возвращает:** `str`

**Пример:**

```python
from sky_url import add_utm

result = add_utm("https://example.com/path?x=1", None, None, 10)
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
