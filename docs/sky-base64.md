# sky-base64

## О пакете

Кодирование и декодирование Base64 (включая URL-safe).

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-base64-v0.1.0/sky_base64-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/base64
```

**SkyForge:**
```bash
SkyForge install skyforge-base64
```

## API

### `encode(text) → str`

**Параметры:**

- `text` — входная строка

**Возвращает:** `str`

**Пример:**

```python
from sky_base64 import encode

result = encode("example text")
print(result)
```

### `decode(b64_text) → str`

**Параметры:**

- `b64_text` — входная строка

**Возвращает:** `str`

**Пример:**

```python
from sky_base64 import decode

result = decode("example text")
print(result)
```

### `encode_url_safe(text) → str`

**Параметры:**

- `text` — входная строка

**Возвращает:** `str`

**Пример:**

```python
from sky_base64 import encode_url_safe

result = encode_url_safe("example text")
print(result)
```

### `decode_url_safe(b64_text) → str`

**Параметры:**

- `b64_text` — входная строка

**Возвращает:** `str`

**Пример:**

```python
from sky_base64 import decode_url_safe

result = decode_url_safe("example text")
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
