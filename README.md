<div align="center">
  <img src="favicon.png" alt="SkyPackages Logo" width="120" />

  # SkyPackages

  **Коллекция open-source библиотек для Python, JavaScript и SkyForge. Один бренд, три экосистемы, единые конвенции и API.**

  [![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
  [![Node](https://img.shields.io/badge/Node-18%2B-339933?style=flat-square&logo=node.js&logoColor=white)](https://nodejs.org/)
  [![SkyForge](https://img.shields.io/badge/SkyForge-1.1.0.5-06b6d4?style=flat-square)](https://skyforge-docs.onrender.com)
  [![License](https://img.shields.io/badge/license-MIT-22c55e?style=flat-square)](https://opensource.org/licenses/MIT)
  [![OpenSSF Best Practices](https://www.bestpractices.dev/projects/15993/badge)](https://www.bestpractices.dev/projects/15993)
  [![CI](https://github.com/skytech-alt/SkyPackages/actions/workflows/ci.yml/badge.svg)](https://github.com/skytech-alt/SkyPackages/actions/workflows/ci.yml)

  [![Packages](https://img.shields.io/badge/packages-100-6366f1?style=flat-square)](https://skypackages.onrender.com)
  [![Releases](https://img.shields.io/badge/releases-300-a855f7?style=flat-square)](https://github.com/skytech-alt/SkyPackages/releases)
  [![Docs](https://img.shields.io/badge/docs-100%25-blue?style=flat-square)](./docs/README.md)
  [![Tests](https://img.shields.io/badge/tests-100%25-brightgreen?style=flat-square)]()
  [![OpenSSF](https://img.shields.io/badge/OpenSSF-Best%20Practices-yellow?style=flat-square)]()

  <p align="center">
    <a href="https://skypackages.onrender.com"><b>Website</b></a> •
    <a href="./docs/README.md"><b>Documentation</b></a> •
    <a href="#-каталог-пакетов"><b>Packages</b></a>
  </p>
</div>

[![Reboosty](https://reboosty-reboosty.vercel.app/api/badge?repo_url=https://github.com/skytech-alt/SkyPackages)](https://reboosty-reboosty.vercel.app/api/redirect?repo_url=https://github.com/skytech-alt/SkyPackages)

---

**100 уникальных пакетов · 300 релизов · 3 экосистемы · #1 в лидерборде SkyForge**

Сайт: **[skypackages.onrender.com](https://skypackages.onrender.com)**

## 📖 О проекте

SkyPackages закрывает задачи, которые не решают популярные западные библиотеки: валидация ИНН, ОГРН, СНИЛС, производственный календарь РФ, склонение числительных, транслитерация по ГОСТ, российские телефоны и карты МИР. Плюс универсальные утилиты, которых не хватает в стандартных библиотеках: безопасный JSON, криптография, генерация ID, cron, semver.

Каждый пакет существует в трёх версиях одновременно:

| Экосистема | Пример установки |
|---|---|
| Python | `pip install <url к .whl>` |
| npm | `npm install <url к .tgz>` |
| SkyForge | `SkyForge install skyforge-<name>` |

Пакеты собраны из одного источника, проходят одинаковые по смыслу тесты, используют общий контракт API. Если пишете на Python и JavaScript, не придётся переучиваться.

Проект независимый, не связан с какой-либо компанией. Лицензия MIT.

---

## 🚀 Быстрый старт

### Python

```python
from sky_validate_ru import inn, snils
from sky_datetime_ru import add_working_days
from datetime import date

inn.is_valid("7707083893")              # True
snils.format("11223344595")             # "112-233-445 95"
add_working_days(date(2026, 12, 31), 1) # 2026-01-09
```

Установка конкретного пакета берётся с сайта в разделе «Пакеты» или со страницы соответствующего релиза на GitHub.

### JavaScript / TypeScript

```ts
import { uuidV7 } from "@skypackages/id";
import { formatPhone } from "@skypackages/phone-ru";
import { encode } from "@skypackages/csv";

uuidV7();                     // "018f4a3e-..."
formatPhone("+79991234567");  // "+7 (999) 123-45-67"
encode([{ a: 1 }]);           // CSV с BOM для Excel
```

### SkyForge

```skyforge
пусть v = подтянуть "skyforge-validate-ru"
лог(v.инн_валиден("7707083893"))   // истина
```

## 📚 Каталог пакетов

Полный список с описанием и ссылками на скачивание: **[skypackages.onrender.com](https://skypackages.onrender.com)** или в сгенерированной документации.

### 🇷🇺 Российская специфика

| Пакет | Назначение |
|---|---|
| `sky-validate-ru` | ИНН, ОГРН, ОГРНИП, СНИЛС, КПП, БИК, счета |
| `sky-phone-ru` | Телефоны РФ, определение оператора |
| `sky-bank-card` | Валидация карт: Luhn, Visa, MasterCard, МИР |
| `sky-datetime-ru` | Производственный календарь, рабочие дни |
| `sky-plural-ru` | Склонение числительных: 1 яблоко, 2 яблока, 5 яблок |
| `sky-tax-ru` | НДС 20% и 10%: начисление и выделение |
| `sky-slug` | Транслитерация кириллицы в URL-слаги |
| `sky-fio` | *(в разработке)* Склонение ФИО по падежам |

### 🔐 Криптография и безопасность

| Пакет | Назначение |
|---|---|
| `sky-crypto` | AES-256-GCM, PBKDF2 (600 000 итераций) |
| `sky-random` | Безопасные пароли, UUID, случайные строки |
| `sky-mask` | Маскировка email, карт, телефонов для логов |
| `sky-password-strength` | Оценка пароля 0-4 с советами |
| `sky-password-gen` | Генератор паролей |
| `sky-hash` | djb2, fnv1a |
| `sky-sql-escape` | Экранирование SQL |
| `sky-html`, `sky-xml` | Экранирование HTML/XML |
| `sky-regex` | Экранирование спецсимволов для RegExp |

### 📦 Форматы данных

| Пакет | Назначение |
|---|---|
| `sky-json` | Безопасный парсинг с лимитами, flatten, deep-equal |
| `sky-csv` | CSV с точкой с запятой и BOM для Excel |
| `sky-yaml-lite`, `sky-toml`, `sky-ini` | Минимальные парсеры |
| `sky-base64`, `sky-base32`, `sky-hex` | Кодирование |
| `sky-bencode` | BitTorrent Bencode |
| `sky-json-minify`, `sky-json-pretty` | Минификация и форматирование |
| `sky-query-string` | Парсинг query string |

### 🛠 Утилиты

| Пакет | Назначение |
|---|---|
| `sky-result` | `Result<T,E>`, `Option<T>`, декоратор `@safe` |
| `sky-array` | chunk, unique, flatten, group_by, shuffle |
| `sky-object` | safe_get, deep_clone, deep_merge |
| `sky-id` | UUID v4/v7, ULID, NanoID, Snowflake |
| `sky-retry` | Retry с exponential backoff и jitter |
| `sky-duration` | Парсинг "1h 30m", "1.5 GB" |
| `sky-semver` | Сравнение версий, диапазоны `^1.2.0` |
| `sky-cron` | Парсинг cron-выражений |
| `sky-timeago` | "5 минут назад" с русскими склонениями |
| `sky-number` | Форматирование чисел: 1.5K, 2M |
| `sky-words` | Подсчёт слов, время чтения |
| `sky-color` | HEX, RGB, контрастность |
| `sky-case` | camelCase, snake_case, kebab-case |
| `sky-env` | Типизированные переменные окружения |
| `sky-diff` | Расстояние Левенштейна, построчный diff |
| `sky-http-status` | HTTP статус-коды |
| `sky-netguard` | IP, CIDR, MAC, порты |
| `sky-ipv4-validate`, `sky-ipv6-validate` | Валидация IP |
| `sky-email` | Email + определение одноразовых доменов |
| `sky-pagination`, `sky-text-wrap`, `sky-truncate`, `sky-pad` | Работа с текстом и UI |
| `sky-emoji-strip` | Удаление эмодзи |
| `sky-timestamp` | Unix timestamp ↔ ISO 8601 |
| `sky-age` | Возраст по дате рождения |
| `sky-user-agent` | Парсинг User-Agent |
| `sky-mime` | MIME-типы |

### 🧮 Алгоритмы

| Пакет | Назначение |
|---|---|
| `sky-roman` | Римские цифры |
| `sky-morse`, `sky-braille`, `sky-nato` | Кодировки |
| `sky-caesar`, `sky-rot13`, `sky-leet` | Шифры и забавы |
| `sky-fibonacci`, `sky-factorial`, `sky-prime`, `sky-gcd`, `sky-lcm` | Математика |
| `sky-palindrome`, `sky-anagram` | Работа со строками |
| `sky-bitwise`, `sky-binary`, `sky-octal` | Системы счисления |
| `sky-soundex` | Фонетический поиск |
| `sky-dice`, `sky-coin` | Генераторы случайного |
| `sky-isbn`, `sky-ean`, `sky-upc`, `sky-iban` | Валидация кодов |
| `sky-geo` | Расстояние между GPS-координатами |
| `sky-units` | Конвертер единиц |
| `sky-math` | clamp, lerp, проценты |
| `sky-i18n` | Словарь локализации |
| `sky-template` | Шаблонизатор `{key}` |
| `sky-ansi`, `sky-css-minify`, `sky-markdown` | Работа с разметкой |

## ⚙️ Как это сделано

Все пакеты генерируются одним скриптом `builder.py`, который за один запуск:

1. Создаёт файлы для Python, npm и SkyForge.
2. Ставит зависимости и прогоняет тесты (`pytest`, `vitest`, `SkyForge check`).
3. Собирает артефакты (`.whl`, `.tgz`, `.zip`).
4. Публикует релизы на GitHub через API (без `git` в PATH).
5. Создаёт или обновляет репозитории SkyForge (топик `skyforge-package`).
6. Патчит реестр пакетов в `index.html` прямо в репозитории.
7. Дёргает деплой Render.

Запуск на 10 пакетов занимает 5-10 минут, включая прогон всех тестов. За один заход — 30 новых релизов.

## 📌 Статус публикации

| Реестр | Статус |
|---|---|
| **GitHub Releases** | ✅ работает, все 300 артефактов доступны |
| **SkyForge registry** | ✅ работает, пакеты устанавливаются через `SkyForge install` |
| **PyPI** | 🟡 публикация в процессе (готовится массовая загрузка 100 пакетов) |
| **npm** | 🟡 публикация в процессе (готовится массовая загрузка) |

> До завершения публикации в основных реестрах пакеты ставятся по прямым ссылкам с GitHub Releases. Команда установки есть на сайте и в описании каждого релиза.

## 🤝 Участие

Проект открыт для contributions. Если нужно добавить пакет, которого нет, или нашли баг — создайте issue в этом репозитории.

**Правила:**

- Код с тестами (`pytest` для Python, `vitest` для TS, `SkyForge check` для SkyForge).
- Никаких внешних зависимостей, кроме стандартной библиотеки.
- Единый API во всех трёх версиях, где это возможно.
- MIT-лицензия.

## 📄 Лицензия

MIT. Используйте в коммерческих проектах, форкайте, меняйте, встраивайте. Единственное условие — сохранять уведомление об авторских правах.
