# sky-mac

## О пакете

Пакет `sky-mac` для типовых задач разработки.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-mac-v0.1.0/sky_mac-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/mac
```

**SkyForge:**
```bash
SkyForge install skyforge-mac
```

## API

### `is_valid(mac) → bool`

**Параметры:**

- `mac` — первое значение

**Возвращает:** `bool`

**Пример:**

```python
from sky_mac import is_valid

result = is_valid(12)
print(result)
```

### `format_mac(mac) → str`

**Параметры:**

- `mac` — первое значение

**Возвращает:** `str`

**Пример:**

```python
from sky_mac import format_mac

result = format_mac(12)
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
