# sky-uuid-short

## О пакете

Генерирует короткий UUID в base62.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-uuid-short-v0.1.0/sky_uuid_short-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/uuid-short
```

**SkyForge:**
```bash
SkyForge install skyforge-uuid-short
```

## API

### `generate() → str`

**Возвращает:** `str`

**Пример:**

```python
from sky_uuid_short import generate

result = generate()
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
