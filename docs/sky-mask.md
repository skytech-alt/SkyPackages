# sky-mask

Маскировка чувствительных данных (email, карты, телефоны) для логов.

## Установка

```bash
pip install sky-mask
npm install @skypackages/mask
SkyForge install sky-mask
```

## API Reference

### Python

#### `def mask_email(email)`
Маскирует email: hello@world.com -> h***o@world.com.

#### `def mask_card(card)`
Маскирует номер карты: 1234 5678 9012 3456 -> **** **** **** 3456.

#### `def mask_phone(phone)`
Маскирует телефон: +79991234567 -> +7 (***) ***-45-67.

#### `def mask_custom(text, visible_start, visible_end, mask_char)`
Кастомная маскировка: оставляет N символов в начале и в конце.

### TypeScript / JavaScript

#### `maskEmail(email)`
*Документация отсутствует.*

#### `maskCard(card)`
*Документация отсутствует.*

#### `maskPhone(phone)`
*Документация отсутствует.*

#### `maskCustom(text, visibleStart, visibleEnd, maskChar)`
*Документация отсутствует.*

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).