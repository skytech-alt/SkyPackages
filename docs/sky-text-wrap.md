# sky-text-wrap

## О пакете

Переносит текст по словам.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-text-wrap-v0.1.0/sky_text_wrap-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/text-wrap
```

**SkyForge:**
```bash
SkyForge install skyforge-text-wrap
```

## API

### `wrap(text, width) → str`

**Параметры:**

- `text` — входная строка
- `width` — коэффициент от 0.0 до 1.0

**Возвращает:** `str`

**Пример:**

```python
from sky_text_wrap import wrap

result = wrap("example text", 0.5)
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
