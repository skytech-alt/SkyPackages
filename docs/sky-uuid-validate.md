# sky-uuid-validate

## О пакете

Проверяет строку на соответствие формату UUID.

## Установка

**Python:**
```bash
pip install https://github.com/skytech-alt/SkyPackages/releases/download/sky-uuid-validate-v0.1.0/sky_uuid_validate-0.1.0-py3-none-any.whl
```

**npm:**
```bash
npm install @skypackages/uuid-validate
```

**SkyForge:**
```bash
SkyForge install skyforge-uuid-validate
```

## API

### `is_valid(uuid_str) → bool`

**Параметры:**

- `uuid_str` — строка

**Возвращает:** `bool`

**Пример:**

```python
from sky_uuid_validate import is_valid

result = is_valid("123e4567-e89b-12d3-a456-426614174000")
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
