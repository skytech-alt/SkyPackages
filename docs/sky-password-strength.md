# sky-password-strength

Оценка надёжности пароля (0-4) с советами на русском.

## Установка

```bash
pip install sky-password-strength
npm install @skypackages/password-strength
SkyForge install sky-password-strength
```

## API Reference

### Python

#### `class Result`

#### `def _has_sequence(password)`
Проверяет на простые последовательности типа 'abc' или '123'.

#### `def _has_repeat(password)`
Проверяет на повторы 'aaa', '111'.

#### `def evaluate(password)`
Оценивает надёжность пароля.

### TypeScript / JavaScript

#### `evaluate(password)`
*Документация отсутствует.*

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).