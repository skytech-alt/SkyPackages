# sky-palindrome

## О пакете

Проверяет строку на палиндром.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-palindrome-v0.1.0/sky_palindrome-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/palindrome
```

**SkyForge:**
```bash
SkyForge install skyforge-palindrome
```

## API

### `is_palindrome(text) → bool`

**Параметры:**

- `text` — входная строка

**Возвращает:** `bool`

**Пример:**

```python
from sky_palindrome import is_palindrome

result = is_palindrome("example text")
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
