# sky-truncate

## Установка

**Python:**
```bash
pip install sky-truncate
```

**npm:**
```bash
npm install @skypackages/truncate
```

**SkyForge:**
```bash
SkyForge install skyforge-truncate
```

## Python API

### `truncate(text, max_length, suffix)`

Обрезает текст до max_length, стараясь не разрывать слова.

### Пример использования

```python
from sky_truncate import truncate

truncate("example", None, None)
```

## TypeScript / JavaScript API

### `truncate(text, maxLength, suffix)`

### Пример использования

```typescript
import { truncate } from "@skypackages/truncate";

truncate("example", None, None);
```

## SkyForge

Умное обрезание текста с сохранением целых слов.

```skyforge
пусть lib = подтянуть "skyforge-truncate"
лог(lib.truncate())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
