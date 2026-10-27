# sky-roman

## О пакете

Конвертирует числа в римские и обратно.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-roman-v0.1.0/sky_roman-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/roman
```

**SkyForge:**
```bash
SkyForge install skyforge-roman
```

## API

### `to_roman(num) → str`

**Параметры:**

- `num` — целое число

**Возвращает:** `str`

**Пример:**

```python
from sky_roman import to_roman

result = to_roman(42)
print(result)
```

### `from_roman(roman) → int`

**Параметры:**

- `roman` — целое число

**Возвращает:** `int`

**Пример:**

```python
from sky_roman import from_roman

result = from_roman(10)
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
