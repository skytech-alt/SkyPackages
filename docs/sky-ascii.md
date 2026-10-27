# sky-ascii

## О пакете

Пакет `sky-ascii` для типовых задач разработки.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-ascii-v0.1.0/sky_ascii-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/ascii
```

**SkyForge:**
```bash
SkyForge install skyforge-ascii
```

## API

### `to_code(char) → int`

**Параметры:**

- `char` — один символ

**Возвращает:** `int`

**Пример:**

```python
from sky_ascii import to_code

result = to_code(12)
print(result)
```

### `to_char(code) → str`

**Параметры:**

- `code` — числовой код

**Возвращает:** `str`

**Пример:**

```python
from sky_ascii import to_char

result = to_char(65)
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
