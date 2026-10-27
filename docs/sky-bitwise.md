# sky-bitwise

## О пакете

Битовые операции: popcount, проверка степени двойки.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-bitwise-v0.1.0/sky_bitwise-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/bitwise
```

**SkyForge:**
```bash
SkyForge install skyforge-bitwise
```

## API

### `count_bits(n) → int`

**Параметры:**

- `n` — целое число

**Возвращает:** `int`

**Пример:**

```python
from sky_bitwise import count_bits

result = count_bits(10)
print(result)
```

### `is_power_of_two(n) → bool`

**Параметры:**

- `n` — целое число

**Возвращает:** `bool`

**Пример:**

```python
from sky_bitwise import is_power_of_two

result = is_power_of_two(10)
print(result)
```

### `lowest_bit(n) → int`

**Параметры:**

- `n` — целое число

**Возвращает:** `int`

**Пример:**

```python
from sky_bitwise import lowest_bit

result = lowest_bit(10)
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
