# sky-validate-ru

**Версия:** `0.1.0` | **Экосистема:** `python`

Валидация российских реквизитов: ИНН, ОГРН, ОГРНИП, СНИЛС, КПП, БИК, расчётные и корреспондентские счета

## Установка

```bash
pip install sky-validate-ru
```

## API Reference

### `class ValidationError`
Ошибка валидации реквизита. Наследуется от ValueError для удобства.

- **`__str__()`**

### `def normalize(value)`
*Документация отсутствует.*

### `def _weights_for(bik)`
Вес 12-й цифры счёта (index 11) зависит от 7-й цифры БИК (index 6).

### `def is_valid(value, bik)`
*Документация отсутствует.*

### `def validate(value, bik)`
*Документация отсутствует.*

### `def normalize(value)`
*Документация отсутствует.*

### `def is_valid(value)`
*Документация отсутствует.*

### `def validate(value)`
*Документация отсутствует.*

### `def _checksum(digits, weights)`
*Документация отсутствует.*

### `def normalize(value)`
*Документация отсутствует.*

### `def kind(value)`
*Документация отсутствует.*

### `def is_valid(value)`
*Документация отсутствует.*

### `def validate(value)`
Возвращает нормализованный ИНН или бросает ValidationError.

### `def normalize(value)`
*Документация отсутствует.*

### `def is_valid(value)`
*Документация отсутствует.*

### `def validate(value)`
*Документация отсутствует.*

### `def normalize(value)`
*Документация отсутствует.*

### `def kind(value)`
*Документация отсутствует.*

### `def is_valid(value)`
*Документация отсутствует.*

### `def validate(value)`
*Документация отсутствует.*

### `def normalize(value)`
*Документация отсутствует.*

### `def is_valid(value)`
*Документация отсутствует.*

### `def validate(value)`
*Документация отсутствует.*

### `def format(value)`
Форматирует в XXX-XXX-XXX YY.

### `def digits_only(value)`
Убирает всё, кроме цифр.

### `def strip_separators(value)`
Убирает пробелы, дефисы, точки, подчёркивания. Верхний регистр.

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).