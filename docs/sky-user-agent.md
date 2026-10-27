# sky-user-agent

## О пакете

Определяет мобильный или десктопный браузер по User-Agent.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-user-agent-v0.1.0/sky_user_agent-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/user-agent
```

**SkyForge:**
```bash
SkyForge install skyforge-user-agent
```

## API

### `is_mobile(ua) → bool`

**Параметры:**

- `ua` — первое значение

**Возвращает:** `bool`

**Пример:**

```python
from sky_user_agent import is_mobile

result = is_mobile(12)
print(result)
```

### `is_desktop(ua) → bool`

**Параметры:**

- `ua` — первое значение

**Возвращает:** `bool`

**Пример:**

```python
from sky_user_agent import is_desktop

result = is_desktop(12)
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
