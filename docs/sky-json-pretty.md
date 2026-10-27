# sky-json-pretty

## О пакете

Форматирует JSON с отступами.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-json-pretty-v0.1.0/sky_json_pretty-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/json-pretty
```

**SkyForge:**
```bash
SkyForge install skyforge-json-pretty
```

## API

### `pretty(text, indent=2) → str`

**Параметры:**

- `text` — входная строка
- `indent` — количество пробелов для отступа (по умолчанию `2`)

**Возвращает:** `str`

**Пример:**

```python
from sky_json_pretty import pretty

result = pretty("example text", 10)
print(result)
```

## Типичные сценарии

- Парсинг ответов от внешних API с защитой от DoS
- Сериализация и десериализация конфигураций
- Сравнение двух JSON-объектов без учёта порядка ключей

## Ограничения

- Пакет проверяет структуру и формат, но не заменяет проверку через внешние API (например, ФНС)
- Для некоторых задач требуется предварительная нормализация входных данных
- Зависимостей нет, но для AES-шифрования в Python версии нужен пакет `cryptography` (указан в зависимостях)

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
