# sky-jwt-decode

## О пакете

Декодирует payload из JWT без проверки подписи.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-jwt-decode-v0.1.0/sky_jwt_decode-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/jwt-decode
```

**SkyForge:**
```bash
SkyForge install skyforge-jwt-decode
```

## API

### `decode(token) → dict`

**Параметры:**

- `token` — целое число

**Возвращает:** `dict`

**Пример:**

```python
from sky_jwt_decode import decode

result = decode(10)
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
