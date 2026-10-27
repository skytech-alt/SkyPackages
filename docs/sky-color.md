# sky-color

Работа с цветами: HEX, RGB, контрастность (WCAG), осветление и затемнение.

## Установка

```bash
pip install sky-color
npm install @skypackages/color
SkyForge install sky-color
```

## API Reference

### Python

#### `def hex_to_rgb(hex_str)`
Конвертирует HEX в RGB.

#### `def rgb_to_hex(r, g, b)`
Конвертирует RGB в HEX.

#### `def get_contrast_color(hex_str)`
Возвращает '#000000' или '#ffffff' для лучшего контраста с фоном.

#### `def lighten(hex_str, percent)`
Осветляет цвет на N процентов (0-100).

#### `def darken(hex_str, percent)`
Затемняет цвет на N процентов (0-100).

### TypeScript / JavaScript

#### `hexToRgb(hex)`
*Документация отсутствует.*

#### `rgbToHex(r, g, b)`
*Документация отсутствует.*

#### `getContrastColor(hex)`
*Документация отсутствует.*

#### `lighten(hex, percent)`
*Документация отсутствует.*

#### `darken(hex, percent)`
*Документация отсутствует.*

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).