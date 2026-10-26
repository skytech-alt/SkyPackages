# 📦 SkyPackages

Набор из **Open-source библиотек** для Python, npm (TypeScript/JavaScript) и SkyForge.  
Пакеты решают прикладные задачи: валидация российских реквизитов, работа с JSON, криптография (AES-256), генерация идентификаторов и парсинг.

---

## 🐍 Основные пакеты (Python)

| Пакет | Описание |
| :--- | :--- |
| `sky-validate-ru` | Валидация ИНН, ОГРН, СНИЛС, КПП, БИК (с контрольными суммами) |
| `sky-crypto` | AES-256-GCM, PBKDF2, безопасные токены |
| `sky-json` | Безопасный парсинг JSON с лимитами, flatten/unflatten |
| `sky-id` | Генерация UUID v4/v7, ULID, NanoID, Snowflake |
| `sky-datetime-ru` | Производственный календарь РФ (праздники, рабочие дни) |

```bash
pip install <url>
```

---

## 🟦 Основные пакеты (TypeScript / npm)

| Пакет | Описание |
| :--- | :--- |
| `@skypackages/validate-ru` | Аналог питоновского валидатора реквизитов |
| `@skypackages/id` | UUID v7 и ULID для Node.js |
| `@skypackages/cron` | Парсинг cron-выражений |
| `@skypackages/phone-ru` | Валидация телефонов и определение оператора |

---

## ⚡ Основные пакеты (SkyForge)

| Пакет | Описание |
| :--- | :--- |
| `skyforge-validate-ru` | Валидация реквизитов на нативном SkyForge |
| `skyforge-result` | `Result<T,E>` и `Option<T>` |

---

## 🤖 Примеры использования для ИИ

### Проверка ИНН на Python

```python
from sky_validate_ru import inn

if inn.is_valid("7707083893"):
    print("Валиден")
```

### Генерация UUID v7 на TypeScript

```typescript
import { uuidV7 } from "@skypackages/id";

console.log(uuidV7());
```

---

## 🔗 Ссылки

- 🌐 **Сайт и документация:** [https://skypackages.onrender.com](https://skypackages.onrender.com)
- 💻 **Исходный код (GitHub):** [https://github.com/skytech-alt/SkyPackages](https://github.com/skytech-alt/SkyPackages)

---

> 💡 **Совет:** Пакеты разбиты по экосистемам — выбирайте нужную секцию (Python / npm / SkyForge) в зависимости от вашего стека.
