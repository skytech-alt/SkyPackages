# sky-json-minify

## О пакете

Минифицирует JSON.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-json-minify-v0.1.0/sky_json_minify-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/json-minify
```

**SkyForge:**
```bash
SkyForge install skyforge-json-minify
```

## API

### `minify(text) → str`

**Параметры:**

- `text` — входная строка

**Возвращает:** `str`

**Пример:**

```python
from sky_json_minify import minify

result = minify("example text")
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
