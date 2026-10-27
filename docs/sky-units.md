# sky-units

## О пакете

Конвертирует единицы измерения.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-units-v0.1.0/sky_units-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/units
```

**SkyForge:**
```bash
SkyForge install skyforge-units
```

## API

### `km_to_miles(km) → float`

**Параметры:**

- `km` — аргумент функции

**Возвращает:** `float`

**Пример:**

```python
from sky_units import km_to_miles

result = km_to_miles(None)
print(result)
```

### `miles_to_km(miles) → float`

**Параметры:**

- `miles` — строка

**Возвращает:** `float`

**Пример:**

```python
from sky_units import miles_to_km

result = miles_to_km(None)
print(result)
```

### `kg_to_lbs(kg) → float`

**Параметры:**

- `kg` — аргумент функции

**Возвращает:** `float`

**Пример:**

```python
from sky_units import kg_to_lbs

result = kg_to_lbs(None)
print(result)
```

### `celsius_to_fahrenheit(c) → float`

**Параметры:**

- `c` — аргумент функции

**Возвращает:** `float`

**Пример:**

```python
from sky_units import celsius_to_fahrenheit

result = celsius_to_fahrenheit(None)
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
