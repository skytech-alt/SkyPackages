# sky-leet

## О пакете

Leetspeak-конвертер.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-leet-v0.1.0/sky_leet-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/leet
```

**SkyForge:**
```bash
SkyForge install skyforge-leet
```

## API

### `to_leet(text) → str`

**Параметры:**

- `text` — входная строка

**Возвращает:** `str`

**Пример:**

```python
from sky_leet import to_leet

result = to_leet("example text")
print(result)
```

### `from_leet(text) → str`

**Параметры:**

- `text` — входная строка

**Возвращает:** `str`

**Пример:**

```python
from sky_leet import from_leet

result = from_leet("example text")
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
