# sky-diff

Сравнение строк: расстояние Левенштейна, схожесть 0..1, построчный diff.

## Установка

```bash
pip install sky-diff
npm install @skypackages/diff
SkyForge install sky-diff
```

## API Reference

### Python

#### `def levenshtein(a, b)`
Расстояние редактирования (Левенштейна) между двумя строками.

#### `def similarity(a, b)`
Схожесть 0.0 .. 1.0 на основе Левенштейна.

#### `def diff_lines(a, b)`
Построчный diff в стиле unified (без заголовков).

Пример:
    >>> diff_lines("a\nb\nc", "a\nB\nc")
    [' a', '-b', '+B', ' c']

### TypeScript / JavaScript

#### `levenshtein(a, b)`
*Документация отсутствует.*

#### `similarity(a, b)`
*Документация отсутствует.*

#### `diffLines(a, b)`
*Документация отсутствует.*

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).