# sky-fibonacci

## О пакете

Генерирует числа Фибоначчи.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-fibonacci-v0.1.0/sky_fibonacci-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/fibonacci
```

**SkyForge:**
```bash
SkyForge install skyforge-fibonacci
```

## API

### `fib(n) → list`

**Параметры:**

- `n` — целое число

**Возвращает:** `list`

**Пример:**

```python
from sky_fibonacci import fib

result = fib(10)
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
