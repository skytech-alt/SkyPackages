# sky-ansi

## О пакете

ANSI-цвета для терминала.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-ansi-v0.1.0/sky_ansi-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/ansi
```

**SkyForge:**
```bash
SkyForge install skyforge-ansi
```

## API

### `colorize(text, color) → str`

**Параметры:**

- `text` — входная строка
- `color` — аргумент функции

**Возвращает:** `str`

**Пример:**

```python
from sky_ansi import colorize

result = colorize("example text", None)
print(result)
```

### `strip_ansi(text) → str`

**Параметры:**

- `text` — входная строка

**Возвращает:** `str`

**Пример:**

```python
from sky_ansi import strip_ansi

result = strip_ansi("example text")
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
