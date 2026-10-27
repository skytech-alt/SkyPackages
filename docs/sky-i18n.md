# sky-i18n

## О пакете

Словарь локализации.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-i18n-v0.1.0/sky_i18n-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/i18n
```

**SkyForge:**
```bash
SkyForge install skyforge-i18n
```

## API

### `add(lang, key, value) → None`

**Параметры:**

- `lang` — код языка (en, ru)
- `key` — ключ (пароль, ключ шифрования или имя поля)
- `value` — проверяемое значение

**Возвращает:** `None`

**Пример:**

```python
from sky_i18n import add

result = add(10, "secret_key", 12)
print(result)
```

### `t(key, lang='en', default=None) → str`

**Параметры:**

- `key` — ключ (пароль, ключ шифрования или имя поля)
- `lang` — код языка (en, ru) (по умолчанию `'en'`)
- `default` — значение по умолчанию (по умолчанию `None`)

**Возвращает:** `str`

**Пример:**

```python
from sky_i18n import t

result = t("secret_key", 10, 12)
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
