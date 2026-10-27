# sky-ipv4-validate

## О пакете

Проверяет IPv4-адреса.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-ipv4-validate-v0.1.0/sky_ipv4_validate-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/ipv4-validate
```

**SkyForge:**
```bash
SkyForge install skyforge-ipv4-validate
```

## API

### `is_valid(ip) → bool`

**Параметры:**

- `ip` — аргумент функции

**Возвращает:** `bool`

**Пример:**

```python
from sky_ipv4_validate import is_valid

result = is_valid(None)
print(result)
```

## Типичные сценарии

- Проверка реквизитов при регистрации юридического лица или ИП
- Валидация данных в форме оформления заказа
- Проверка корректности реквизитов перед отправкой в банк

## Ограничения

- Пакет проверяет структуру и формат, но не заменяет проверку через внешние API (например, ФНС)
- Для некоторых задач требуется предварительная нормализация входных данных
- Зависимостей нет, но для AES-шифрования в Python версии нужен пакет `cryptography` (указан в зависимостях)

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
