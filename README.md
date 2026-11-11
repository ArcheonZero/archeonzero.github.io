# Archeon Zero — точка сборки

Сайт-визитка **Archeon Zero**: визитка-концентратор проектов, статей и площадок,
развёрнутая на GitHub Pages и открытая по адресу **[archeonzero.ru](https://archeonzero.ru)**.

> **«Точка сборки, а не визитка»** — нижняя граница, с которой начинается движение
> вверх: проекты и тексты, которые собираются и расходятся по площадкам.

---

## Статус

- ✦ Домен подключён, `CNAME` в репозитории — сайт живёт на [archeonzero.ru](https://archeonzero.ru).
- ✦ Запущен цикл статей **DevCrm** — разработка локальной CRM на WPF.

---

## Содержимое репозитория

| Файл / папка | Что это |
|------|---------|
| `index.html` | Главная страница — визитка со всеми разделами |
| `themes.css` | Тематическая раскраска (7 тем, переключаются кнопкой) |
| `CNAME` | Кастомный домен `archeonzero.ru` |
| `articles/devcrm/` | Статьи цикла DevCrm (html + иллюстрации в `articles/devcrm/img/`) |
| `ArcheonZreborn.html` | Повесть «Archeon Z: перерождение» (текст) |
| `AZ_Glava_1.html` | Полная первая глава повести (3 части) |
| `README.md` | Этот файл |

---

## Статьи: цикл DevCrm — CRM на WPF

Живой лог разработки локальной CRM: от «меня парализовало перед собственным проектом»
до рабочего приложения. Без прикрас — с багами, рефакторингом и архитектурой, которая
выстраивается по ходу дела.

✦ [DevCrm 00 — Меня парализовало перед собственным проектом CRM на WPF: ни назад, ни вперёд](https://archeonzero.ru/articles/devcrm/devcrm-00-razrabotka-crm-na-wpf.html)

Стек цикла: C# / .NET 8 · WPF · MVVM · SQLite (Microsoft.Data.Sqlite).
Код проекта — в репозитории [CrmArcheonzero](https://github.com/ArcheonZero/CrmArcheonzero).

---

## Возможности site-v12

- **7 тем оформления** — тёмная «терминальная», «редакция», фрактальная, мягкая,
  янтарная, изумрудная, аметистовая. Переключаются плавающей кнопкой, выбор
  сохраняется в `localStorage`.
- **6 форм логотипа** — дерево, сфера, глобус, ловец снов, ветви, AZ-знак.
  Рекурсивный фрактал и формы на CSS-переменных (`--logo-*`) перекрашиваются под тему.
- **Разделы**: Проекты · Статьи · Площадки · Контакты.
- **Повесть** — `ArcheonZreborn.html` и `AZ_Glava_1.html` приведены к общему стилю
  главной (темы, логотип, футер).

---

## Проекты

- CRM Archeonzero (WPF) — [репозиторий](https://github.com/ArcheonZero/CrmArcheonzero)
- CRM Web — [репозиторий](https://github.com/ArcheonZero/CrmWebArcheonzero)
- Mobile CRM — [CrmBlzAZ9.Mob](https://github.com/ArcheonZero/CrmBlzAZ9.Mob) · [CrmAZAdrXam](https://github.com/ArcheonZero/CrmAZAdrXam)
- Archeonzero CMS (PHP)
- Инструменты для архива (Python)
- LLMRouter

---

## Площадки

[Дзен](https://dzen.ru/archeonzero) · [vc.ru](https://vc.ru/id6054863) · [Teletype](https://teletype.in/@archeonzero) · [Blogger](https://archeonzero.blogspot.com) · [VK](https://vk.ru/archeonzeroclub) · [GitHub](https://github.com/ArcheonZero) · ЖЖ (LiveJournal) · LiveInternet

---

## Запуск локально

Просто откройте `index.html` в браузере:

```bash
start index.html      # Windows
open index.html       # macOS/Linux
```

Никакой сборки не нужно — статика на чистом HTML/CSS/JS.

---

## Авторство

Коммиты идут от **Archeon Zero**. Почта: archeonzero@yandex.ru
