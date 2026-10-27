# sky-result

Result<T,E> и Option<T> для Python. Без исключений, только явные типы.

## Установка

```bash
pip install sky-result
npm install @skypackages/result
SkyForge install sky-result
```

## API Reference

### Python

#### `class Some`
- **`map(fn)`**
- **`unwrap()`**
- **`unwrap_or(default)`**

#### `class Nothing`
- **`map(fn)`**
- **`unwrap()`**
- **`unwrap_or(default)`**

#### `class Ok`
- **`map(fn)`**
- **`map_err(fn)`**
- **`bind(fn)`**
- **`unwrap()`**
- **`unwrap_or(default)`**

#### `class Err`
- **`map(fn)`**
- **`map_err(fn)`**
- **`bind(fn)`**
- **`unwrap()`**
- **`unwrap_or(default)`**

#### `def some(value)`
*Документация отсутствует.*

#### `def nothing()`
*Документация отсутствует.*

#### `def ok(value)`
*Документация отсутствует.*

#### `def err(error)`
*Документация отсутствует.*

#### `def safe(fn)`
*Документация отсутствует.*

### TypeScript / JavaScript

#### `nothing()`
*Документация отсутствует.*

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).