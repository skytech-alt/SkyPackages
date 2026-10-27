# sky-timeago

Относительное время ('5 минут назад', 'вчера') с поддержкой русских склонений.

## Установка

```bash
pip install sky-timeago
npm install @skypackages/timeago
SkyForge install sky-timeago
```

## API Reference

### Python

#### `def _plural(n, one, few, many)`
Русское склонение: 1 минуту, 2 минуты, 5 минут.

#### `def _to_seconds(value)`
Приводит timestamp или datetime к unix-секундам.

#### `def time_ago(target, now)`
Возвращает относительное время: '5 минут назад', 'вчера', 'только что'.

### TypeScript / JavaScript

#### `timeAgo(target, now)`
*Документация отсутствует.*

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).