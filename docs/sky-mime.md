# sky-mime

## О пакете

Определяет MIME-тип по расширению.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-mime-v0.1.0/sky_mime-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/mime
```

**SkyForge:**
```bash
SkyForge install skyforge-mime
```

## API

### `get_mime(extension) → str`

**Параметры:**

- `extension` — строка

**Возвращает:** `str`

**Пример:**

```python
from sky_mime import get_mime

result = get_mime(10)
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
