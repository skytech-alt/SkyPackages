# sky-coin

## О пакете

Орёл или решка.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-coin-v0.1.0/sky_coin-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/coin
```

**SkyForge:**
```bash
SkyForge install skyforge-coin
```

## API

### `flip() → str`

**Возвращает:** `str`

**Пример:**

```python
from sky_coin import flip

result = flip()
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
