# sky-tax-ru

## Установка

**Python:**
```bash
pip install sky-tax-ru
```

**npm:**
```bash
npm install @skypackages/tax-ru
```

**SkyForge:**
```bash
SkyForge install skyforge-tax-ru
```

## Python API

### `add_vat(amount, rate)`

### `extract_vat(amount_with_vat, rate)`

### `vat_amount(amount, rate)`

### Пример использования

```python
from sky_tax_ru import add_vat

add_vat(None, None)
```

## TypeScript / JavaScript API

### `addVat(amount, rate)`

### `extractVat(amountWithVat, rate)`

### `vatAmount(amount, rate)`

### Пример использования

```typescript
import { addVat } from "@skypackages/tax-ru";

addVat(None, None);
```

## SkyForge

Расчет НДС (20%, 10%) — начисление сверху и выделение из суммы.

```skyforge
пусть lib = подтянуть "skyforge-tax-ru"
лог(lib.add_vat())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
