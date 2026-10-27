# sky-pagination

Расчет пагинации и генерация диапазонов страниц (1 ... 4 5 6 ... 10).

## Установка

```bash
pip install sky-pagination
npm install @skypackages/pagination
SkyForge install sky-pagination
```

## API Reference

### Python

#### `def paginate(total_items, current_page, per_page)`
Возвращает метаданные пагинации.

#### `def get_page_range(current_page, total_pages, delta)`
Генерирует красивый диапазон страниц для UI: [1, '...', 4, 5, 6, '...', 10].

### TypeScript / JavaScript

#### `paginate(totalItems, currentPage, perPage)`
*Документация отсутствует.*

#### `getPageRange(currentPage, totalPages, delta)`
*Документация отсутствует.*

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).