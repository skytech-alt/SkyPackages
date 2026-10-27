# sky-json

Безопасный парсинг JSON с лимитами, flatten/unflatten, deep-equal сравнение.

## Установка

```bash
pip install sky-json
npm install @skypackages/json
SkyForge install sky-json
```

## API Reference

### Python

#### `class JsonError`

#### `def parse(text, max_size, max_depth)`
*Документация отсутствует.*

#### `def _check_depth(obj, max_depth, current)`
*Документация отсутствует.*

#### `def is_valid(text)`
*Документация отсутствует.*

#### `def flatten(obj, sep)`
*Документация отсутствует.*

#### `def unflatten(obj, sep)`
Обратное к flatten. Автоматически выбирает dict или list по ключу.

#### `def keys_count(obj)`
*Документация отсутствует.*

#### `def deep_equal(a, b)`
*Документация отсутствует.*

### TypeScript / JavaScript

#### `parse(text, maxSize, maxDepth)`
*Документация отсутствует.*

#### `isValid(text)`
*Документация отсутствует.*

#### `flatten(obj, sep)`
*Документация отсутствует.*

#### `unflatten(obj, unknown>, sep)`
*Документация отсутствует.*

#### `keysCount(obj)`
*Документация отсутствует.*

#### `deepEqual(a, b)`
*Документация отсутствует.*

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).