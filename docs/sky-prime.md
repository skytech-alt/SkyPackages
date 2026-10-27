# sky-prime

## О пакете

Проверяет числа на простоту.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-prime-v0.1.0/sky_prime-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/prime
```

**SkyForge:**
```bash
SkyForge install skyforge-prime
```

## API

### `is_prime(n) → bool`

**Параметры:**

- `n` — целое число

**Возвращает:** `bool`

**Пример:**

```python
from sky_prime import is_prime

result = is_prime(10)
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
