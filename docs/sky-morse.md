# sky-morse

## О пакете

Азбука Морзе: кодирование и декодирование.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-morse-v0.1.0/sky_morse-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/morse
```

**SkyForge:**
```bash
SkyForge install skyforge-morse
```

## API

### `to_morse(text) → str`

**Параметры:**

- `text` — входная строка

**Возвращает:** `str`

**Пример:**

```python
from sky_morse import to_morse

result = to_morse("example text")
print(result)
```

### `from_morse(morse) → str`

**Параметры:**

- `morse` — строка

**Возвращает:** `str`

**Пример:**

```python
from sky_morse import from_morse

result = from_morse(None)
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
