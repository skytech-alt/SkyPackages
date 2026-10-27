# sky-bitwise

## Установка

**Python:**
```bash
pip install sky-bitwise
```

**npm:**
```bash
npm install @skypackages/bitwise
```

**SkyForge:**
```bash
SkyForge install skyforge-bitwise
```

## Python API

### `count_bits(n)`

### `is_power_of_two(n)`

### `lowest_bit(n)`

### Пример использования

```python
from sky_bitwise import count_bits

count_bits(42)
```

## TypeScript / JavaScript API

### `countBits(n)`

### `isPowerOfTwo(n)`

### `lowestBit(n)`

### Пример использования

```typescript
import { countBits } from "@skypackages/bitwise";

countBits(42);
```

## SkyForge

Битовые операции (popcount, power of two).

```skyforge
пусть lib = подтянуть "skyforge-bitwise"
лог(lib.count_bits())
```

## Ссылки

- [GitHub Releases](https://github.com/skytech-alt/SkyPackages/releases)
- [Все пакеты](https://skypackages.onrender.com)
