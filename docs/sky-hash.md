# sky-hash

## О пакете

Быстрые не-криптографические хеши: djb2, fnv1a.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-hash-v0.1.0/sky_hash-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/hash
```

**SkyForge:**
```bash
SkyForge install skyforge-hash
```

## API

### `djb2(text) → int`

**Параметры:**

- `text` — входная строка

**Возвращает:** `int`

**Пример:**

```python
from sky_hash import djb2

result = djb2("example text")
print(result)
```

### `fnv1a(text) → int`

**Параметры:**

- `text` — входная строка

**Возвращает:** `int`

**Пример:**

```python
from sky_hash import fnv1a

result = fnv1a("example text")
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
