# sky-password-gen

## О пакете

Генерирует безопасные пароли с настройкой символов.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-password-gen-v0.1.0/sky_password_gen-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/password-gen
```

**SkyForge:**
```bash
SkyForge install skyforge-password-gen
```

## API

### `generate(length=16, use_symbols=True) → str`

**Параметры:**

- `length` — длина (по умолчанию задана в сигнатуре) (по умолчанию `16`)
- `use_symbols` — строка (по умолчанию `True`)

**Возвращает:** `str`

**Пример:**

```python
from sky_password_gen import generate

result = generate(10, 18)
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
