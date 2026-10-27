# sky-bencode

## О пакете

Кодирование и декодирование Bencode (формат BitTorrent).

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-bencode-v0.1.0/sky_bencode-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/bencode
```

**SkyForge:**
```bash
SkyForge install skyforge-bencode
```

## API

### `encode(obj) → str`

**Параметры:**

- `obj` — второе значение

**Возвращает:** `str`

**Пример:**

```python
from sky_bencode import encode

result = encode(18)
print(result)
```

### `decode(text)`

**Параметры:**

- `text` — входная строка

**Пример:**

```python
from sky_bencode import decode

result = decode("example text")
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
