# sky-math

## О пакете

Математические утилиты: clamp, lerp, проценты.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-math-v0.1.0/sky_math-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/math
```

**SkyForge:**
```bash
SkyForge install skyforge-math
```

## API

### `clamp(value, min_val, max_val) → float`

Ограничивает значение в диапазоне [min_val, max_val].

**Параметры:**

- `value` — проверяемое значение
- `min_val` — целое число
- `max_val` — первое значение

**Возвращает:** `float`

**Пример:**

```python
from sky_math import clamp

result = clamp(12, 10, 12)
print(result)
```

### `lerp(start, end, t) → float`

Линейная интерполяция между start и end на t (0..1).

**Параметры:**

- `start` — начальное значение
- `end` — конечное значение
- `t` — коэффициент от 0.0 до 1.0

**Возвращает:** `float`

**Пример:**

```python
from sky_math import lerp

result = lerp(12, 10, 0.5)
print(result)
```

### `percentage(part, total) → float`

Вычисляет процент part от total.

**Параметры:**

- `part` — первое значение
- `total` — общая сумма

**Возвращает:** `float`

**Пример:**

```python
from sky_math import percentage

result = percentage(12, 12)
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
