# sky-geo

## О пакете

Считает расстояние между GPS-координатами по формуле гаверсинуса.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-geo-v0.1.0/sky_geo-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/geo
```

**SkyForge:**
```bash
SkyForge install skyforge-geo
```

## API

### `haversine(lat1, lon1, lat2, lon2) → float`

**Параметры:**

- `lat1` — первое значение
- `lon1` — целое число
- `lat2` — первое значение
- `lon2` — целое число

**Возвращает:** `float`

**Пример:**

```python
from sky_geo import haversine

result = haversine(12, 10, 12, 10)
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
