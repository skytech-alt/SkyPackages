# sky-urltidy

Сокращение и парсинг GitHub-ссылок на релизы (gh:org/repo@tag/file).

## Установка

```bash
pip install sky-urltidy
npm install @skypackages/urltidy
SkyForge install sky-urltidy
```

## API Reference

### Python

#### `def parse(url)`
Разбирает URL релиза GitHub на компоненты.

#### `def shorten(url)`
Сокращает GitHub URL в формат gh:org/repo@tag/file.

#### `def expand(short)`
Восстанавливает полный URL из короткого формата.

#### `def guess_type(filename)`
Определяет тип пакета по расширению файла.

#### `def parse_tag(tag)`
Достает имя и версию из тега. 'sky-slug-v0.1.0' -> ('sky-slug', '0.1.0').

#### `def extract_url(text)`
Вытаскивает первый URL из текста (например, из 'pip install ...').

#### `def describe(url)`
Возвращает человекочитаемое описание пакета.

### TypeScript / JavaScript

#### `parse(url)`
*Документация отсутствует.*

#### `shorten(url)`
*Документация отсутствует.*

#### `expand(short)`
*Документация отсутствует.*

#### `guessType(filename)`
*Документация отсутствует.*

#### `parseTag(tag)`
*Документация отсутствует.*

#### `extractUrl(text)`
*Документация отсутствует.*

#### `describe(url)`
*Документация отсутствует.*

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).