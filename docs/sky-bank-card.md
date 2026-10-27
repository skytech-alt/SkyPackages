# sky-bank-card

Валидация банковских карт: Luhn, определение платёжной системы (Visa, MasterCard, МИР), форматирование и маскировка.

## Установка

```bash
pip install sky-bank-card
npm install @skypackages/bank-card
SkyForge install sky-bank-card
```

## API Reference

### Python

#### `def _digits(card)`
*Документация отсутствует.*

#### `def luhn_check(card)`
Проверка по алгоритму Луна.

#### `def is_valid(card)`
Проверяет карту (длина 13-19 + Luhn).

#### `def detect_network(card)`
Определяет платёжную систему по BIN.

#### `def format_card(card)`
Форматирует: 4111 1111 1111 1111.

#### `def mask(card)`
Маскирует: **** **** **** 1111.

### TypeScript / JavaScript

#### `luhnCheck(card)`
*Документация отсутствует.*

#### `isValid(card)`
*Документация отсутствует.*

#### `detectNetwork(card)`
*Документация отсутствует.*

#### `formatCard(card)`
*Документация отсутствует.*

#### `mask(card)`
*Документация отсутствует.*

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).