# sky-semver

Семантическое версионирование: парсинг, сравнение и проверка диапазонов (^1.2.0, ~1.2.3).

## Установка

```bash
pip install sky-semver
npm install @skypackages/semver
SkyForge install sky-semver
```

## API Reference

### Python

#### `class Version`
- **`__str__()`**

#### `def parse(version)`
Парсит строку семантической версии: '1.2.3-alpha.1+build.5'.

#### `def _compare_prerelease(a, b)`
*Документация отсутствует.*

#### `def compare(v1, v2)`
*Документация отсутствует.*

#### `def satisfies(version, range_str)`
*Документация отсутствует.*

#### `def _satisfies_simple(version, expr)`
*Документация отсутствует.*

#### `def _satisfies_single(version, constraint)`
*Документация отсутствует.*

### TypeScript / JavaScript

#### `parse(version)`
*Документация отсутствует.*

#### `compare(v1, v2)`
*Документация отсутствует.*

#### `satisfies(version, rangeStr)`
*Документация отсутствует.*

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).