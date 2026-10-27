# sky-percent

## О пакете

Пакет `sky-percent` для типовых задач разработки.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-percent-v0.1.0/sky_percent-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/percent
```

**SkyForge:**
```bash
SkyForge install skyforge-percent
```

## API

### `percent_of(percent, total) → float`

**Параметры:**

- `percent` — процент
- `total` — общая сумма

**Возвращает:** `float`

**Пример:**

```python
from sky_percent import percent_of

result = percent_of(10, 12)
print(result)
```

### `percent_change(old, new) → float`

**Параметры:**

- `old` — аргумент функции
- `new` — целое число

**Возвращает:** `float`

**Пример:**

```python
from sky_percent import percent_change

result = percent_change(None, 10)
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
