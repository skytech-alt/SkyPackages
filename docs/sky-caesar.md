# sky-caesar

## О пакете

Шифр Цезаря.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-caesar-v0.1.0/sky_caesar-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/caesar
```

**SkyForge:**
```bash
SkyForge install skyforge-caesar
```

## API

### `encode(text, shift) → str`

**Параметры:**

- `text` — входная строка
- `shift` — сдвиг для шифра Цезаря

**Возвращает:** `str`

**Пример:**

```python
from sky_caesar import encode

result = encode("example text", 0.5)
print(result)
```

### `decode(text, shift) → str`

**Параметры:**

- `text` — входная строка
- `shift` — сдвиг для шифра Цезаря

**Возвращает:** `str`

**Пример:**

```python
from sky_caesar import decode

result = decode("example text", 0.5)
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
