# sky-object

## О пакете

Безопасная работа с объектами: safe_get, deep_clone, deep_merge.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-object-v0.1.0/sky_object-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/object
```

**SkyForge:**
```bash
SkyForge install skyforge-object
```

## API

### `safe_get(obj, path, default=None) → Any`

Безопасно получает значение по пути 'a.b.c'.

**Параметры:**

- `obj` — второе значение
- `path` — первое значение
- `default` — значение по умолчанию (по умолчанию `None`)

**Возвращает:** `Any`

**Пример:**

```python
from sky_object import safe_get

result = safe_get(18, "a.b.c", 12)
print(result)
```

### `deep_clone(obj) → Any`

Глубокая копия объекта.

**Параметры:**

- `obj` — второе значение

**Возвращает:** `Any`

**Пример:**

```python
from sky_object import deep_clone

result = deep_clone(18)
print(result)
```

### `deep_merge(target, source) → Dict[str, Any]`

Сливает два словаря рекурсивно.

**Параметры:**

- `target` — первое значение
- `source` — строка

**Возвращает:** `Dict[str, Any]`

**Пример:**

```python
from sky_object import deep_merge

result = deep_merge(12, None)
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
