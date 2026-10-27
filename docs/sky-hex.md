# sky-hex

## О пакете

Кодирование строк в hex и обратно.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-hex-v0.1.0/sky_hex-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/hex
```

**SkyForge:**
```bash
SkyForge install skyforge-hex
```

## API

### `encode(text) → str`

**Параметры:**

- `text` — входная строка

**Возвращает:** `str`

**Пример:**

```python
from sky_hex import encode

result = encode("example text")
print(result)
```

### `decode(hex_str) → str`

**Параметры:**

- `hex_str` — строка

**Возвращает:** `str`

**Пример:**

```python
from sky_hex import decode

result = decode(5)
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
