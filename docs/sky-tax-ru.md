# sky-tax-ru

## О пакете

Считает НДС 20% и 10%: начисляет сверху и выделяет из суммы.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-tax-ru-v0.1.0/sky_tax_ru-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/tax-ru
```

**SkyForge:**
```bash
SkyForge install skyforge-tax-ru
```

## API

### `add_vat(amount, rate=20.0) → float`

**Параметры:**

- `amount` — сумма денег
- `rate` — процентная ставка (по умолчанию `20.0`)

**Возвращает:** `float`

**Пример:**

```python
from sky_tax_ru import add_vat

result = add_vat(10, 12)
print(result)
```

### `extract_vat(amount_with_vat, rate=20.0) → float`

**Параметры:**

- `amount_with_vat` — целое число
- `rate` — процентная ставка (по умолчанию `20.0`)

**Возвращает:** `float`

**Пример:**

```python
from sky_tax_ru import extract_vat

result = extract_vat(10, 12)
print(result)
```

### `vat_amount(amount, rate=20.0) → float`

**Параметры:**

- `amount` — сумма денег
- `rate` — процентная ставка (по умолчанию `20.0`)

**Возвращает:** `float`

**Пример:**

```python
from sky_tax_ru import vat_amount

result = vat_amount(10, 12)
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
