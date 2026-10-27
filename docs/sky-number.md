# sky-number

Форматирование чисел: разделители тысяч, компактное представление (1.5K, 2M), проценты и валюты.

## Установка

```bash
pip install sky-number
npm install @skypackages/number
SkyForge install sky-number
```

## API Reference

### Python

#### `def format_number(n, separator)`
Форматирует число с разделителями тысяч: 1234567 -> '1 234 567'.

#### `def _compact_helper(value, suffix)`
*Документация отсутствует.*

#### `def compact(n)`
Компактное представление: 1500 -> '1.5K', 2000000 -> '2M'.

#### `def format_percent(n, decimals)`
Форматирует проценты: 45.5 -> '45.5%'.

#### `def format_currency(n, symbol, space)`
Форматирует деньги: 1234 -> '1 234 ₽'.

### TypeScript / JavaScript

#### `formatNumber(n, separator)`
*Документация отсутствует.*

#### `compact(n)`
*Документация отсутствует.*

#### `formatPercent(n, decimals)`
*Документация отсутствует.*

#### `formatCurrency(n, symbol, space)`
*Документация отсутствует.*

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).