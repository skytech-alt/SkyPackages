# sky-html

## О пакете

Экранирование HTML-сущностей для защиты от XSS.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-html-v0.1.0/sky_html-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/html
```

**SkyForge:**
```bash
SkyForge install skyforge-html
```

## API

### `escape(text) → str`

Экранирует спецсимволы HTML.

**Параметры:**

- `text` — входная строка

**Возвращает:** `str`

**Пример:**

```python
from sky_html import escape

result = escape("example text")
print(result)
```

### `unescape(text) → str`

Разэкранирует HTML-сущности.

**Параметры:**

- `text` — входная строка

**Возвращает:** `str`

**Пример:**

```python
from sky_html import unescape

result = unescape("example text")
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
