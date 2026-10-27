# sky-isbn

## Установка

**Python:**
```bash
pip install sky-isbn
```

**npm:**
```bash
npm install @skypackages/isbn
```

**SkyForge:**
```bash
SkyForge install skyforge-isbn
```

## Python API

### `is_valid_isbn10(isbn)`

### `is_valid_isbn13(isbn)`

### Пример использования

```python
from sky_isbn import is_valid_isbn10

is_valid_isbn10(None)
```

## TypeScript / JavaScript API

### `isValidIsbn10(isbn)`

### `isValidIsbn13(isbn)`

### Пример использования

```typescript
import { isValidIsbn10 } from "@skypackages/isbn";

isValidIsbn10(None);
```

## SkyForge

Валидация ISBN-10 и ISBN-13.

```skyforge
пусть lib = подтянуть "skyforge-isbn"
лог(lib.is_valid_isbn10())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
