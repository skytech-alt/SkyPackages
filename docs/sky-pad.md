# sky-pad

## О пакете

Выравнивает строки слева, справа или по центру.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-pad-v0.1.0/sky_pad-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/pad
```

**SkyForge:**
```bash
SkyForge install skyforge-pad
```

## API

### `pad_left(text, length, char=' ') → str`

**Параметры:**

- `text` — входная строка
- `length` — длина (по умолчанию задана в сигнатуре)
- `char` — один символ (по умолчанию `' '`)

**Возвращает:** `str`

**Пример:**

```python
from sky_pad import pad_left

result = pad_left("example text", 10, 12)
print(result)
```

### `pad_right(text, length, char=' ') → str`

**Параметры:**

- `text` — входная строка
- `length` — длина (по умолчанию задана в сигнатуре)
- `char` — один символ (по умолчанию `' '`)

**Возвращает:** `str`

**Пример:**

```python
from sky_pad import pad_right

result = pad_right("example text", 10, 12)
print(result)
```

### `pad_center(text, length, char=' ') → str`

**Параметры:**

- `text` — входная строка
- `length` — длина (по умолчанию задана в сигнатуре)
- `char` — один символ (по умолчанию `' '`)

**Возвращает:** `str`

**Пример:**

```python
from sky_pad import pad_center

result = pad_center("example text", 10, 12)
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
