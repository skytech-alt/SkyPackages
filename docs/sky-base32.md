# sky-base32

## О пакете

Кодирование и декодирование Base32.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-base32-v0.1.0/sky_base32-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/base32
```

**SkyForge:**
```bash
SkyForge install skyforge-base32
```

## API

### `encode(text) → str`

**Параметры:**

- `text` — входная строка

**Возвращает:** `str`

**Пример:**

```python
from sky_base32 import encode

result = encode("example text")
print(result)
```

### `decode(b32_text) → str`

**Параметры:**

- `b32_text` — входная строка

**Возвращает:** `str`

**Пример:**

```python
from sky_base32 import decode

result = decode("example text")
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
