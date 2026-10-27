# sky-email

Валидация и нормализация email-адресов с детектом одноразовых доменов.

## Установка

```bash
pip install sky-email
npm install @skypackages/email
SkyForge install sky-email
```

## API Reference

### Python

#### `def is_valid(email)`
Проверяет, что email валиден по форме.

#### `def normalize(email)`
Нормализует email: trim + lowercase домен (username сохраняем как есть).

#### `def get_parts(email)`
Возвращает username, domain и tld.

#### `def get_domain(email)`
Возвращает домен email или пустую строку.

#### `def is_disposable(email)`
Проверяет, что email с одноразового домена.

#### `def mask(email)`
Маскирует email: hello@world.com -> h***o@world.com.

### TypeScript / JavaScript

#### `isValid(email)`
*Документация отсутствует.*

#### `normalize(email)`
*Документация отсутствует.*

#### `getParts(email)`
*Документация отсутствует.*

#### `getDomain(email)`
*Документация отсутствует.*

#### `isDisposable(email)`
*Документация отсутствует.*

#### `mask(email)`
*Документация отсутствует.*

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).