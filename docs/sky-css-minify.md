# sky-css-minify

## О пакете

Минифицирует CSS.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-css-minify-v0.1.0/sky_css_minify-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/css-minify
```

**SkyForge:**
```bash
SkyForge install skyforge-css-minify
```

## API

### `minify(css) → str`

**Параметры:**

- `css` — строка

**Возвращает:** `str`

**Пример:**

```python
from sky_css_minify import minify

result = minify(None)
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
