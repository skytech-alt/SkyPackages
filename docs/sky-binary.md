# sky-binary

## О пакете

Конвертация в двоичную систему.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-binary-v0.1.0/sky_binary-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/binary
```

**SkyForge:**
```bash
SkyForge install skyforge-binary
```

## API

### `to_bin(n) → str`

**Параметры:**

- `n` — целое число

**Возвращает:** `str`

**Пример:**

```python
from sky_binary import to_bin

result = to_bin(10)
print(result)
```

### `from_bin(s) → int`

**Параметры:**

- `s` — строка

**Возвращает:** `int`

**Пример:**

```python
from sky_binary import from_bin

result = from_bin(None)
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
