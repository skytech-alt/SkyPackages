# sky-crypto

Военная криптография для Python: AES-256, PBKDF2, безопасные токены.

## Установка

```bash
pip install sky-crypto
npm install @skypackages/crypto
SkyForge install sky-crypto
```

## API Reference

### Python

#### `def encrypt(plaintext, key)`
Шифрует текст с помощью AES-256-GCM.

#### `def decrypt(encrypted_b64, key)`
Расшифровывает текст.

#### `def hash_password(password)`
Хеширует пароль с помощью PBKDF2-HMAC-SHA256.

#### `def verify_password(password, hashed)`
Проверяет пароль против хеша.

#### `def generate_token(length)`
Генерирует криптографически безопасный токен (hex).

#### `def generate_url_token(length)`
Генерирует токен, безопасный для использования в URL.

### TypeScript / JavaScript

#### `encrypt(plaintext, keyHex)`
*Документация отсутствует.*

#### `decrypt(encryptedB64, keyHex)`
*Документация отсутствует.*

#### `hashPassword(password)`
*Документация отсутствует.*

#### `verifyPassword(password, hashed)`
*Документация отсутствует.*

#### `generateToken(length)`
*Документация отсутствует.*

#### `generateUrlToken(length)`
*Документация отсутствует.*

---
Разработано в рамках проекта **SkyPackages** (SkyTechnology).