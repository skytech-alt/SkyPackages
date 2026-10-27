# sky-anagram

## О пакете

Проверяет, являются ли две строки анаграммами.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-anagram-v0.1.0/sky_anagram-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/anagram
```

**SkyForge:**
```bash
SkyForge install skyforge-anagram
```

## API

### `is_anagram(a, b) → bool`

**Параметры:**

- `a` — первое значение
- `b` — второе значение

**Возвращает:** `bool`

**Пример:**

```python
from sky_anagram import is_anagram

result = is_anagram(12, 18)
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
