# sky-id

Генерация идентификаторов: UUID v4/v7, ULID, NanoID, Snowflake-подобные.

## Установка

```bash
pip install sky-id
npm install @skypackages/id
SkyForge install sky-id
```

## API Reference

### Python

#### `def uuid_v4()`
Классический случайный UUID v4.

#### `def uuid_v7(timestamp_ms)`
UUID v7: time-sortable, современный стандарт для БД (RFC 9562).

#### `def ulid(timestamp_ms)`
ULID: 26 символов Crockford Base32, лексикографически сортируется.

#### `def nanoid(size)`
NanoID: короткий URL-safe идентификатор.

#### `def set_node_id(node_id)`
Устанавливает ID узла (0..1023) для распределённых систем.

#### `def snowflake()`
Snowflake ID: 64-битный числовой ID, сортируется по времени.

### TypeScript / JavaScript

#### `uuidV4()`
*Документация отсутствует.*

#### `uuidV7(timestampMs?)`
*Документация отсутствует.*

#### `ulid(timestampMs?)`
*Документация отсутствует.*

#### `nanoid(size)`
*Документация отсутствует.*

#### `setNodeId(id)`
*Документация отсутствует.*

#### `snowflake()`
*Документация отсутствует.*

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).