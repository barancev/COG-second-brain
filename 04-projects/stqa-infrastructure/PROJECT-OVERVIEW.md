---
type: project-overview
project: Инфраструктура software-testing.ru
slug: stqa-infrastructure
created: 2026-10-13
updated: 2026-10-14
status: active
tags: ["#project", "#overview", "#infrastructure"]
---

# Инфраструктура software-testing.ru

Все компоненты сайта https://www.software-testing.ru/ работают вместе и используют общую инфраструктуру.

## Информационный сайт

Основной сайт software-testing.ru — информационный ресурс по теме тестирования. Публикуются статьи и материалы по тестированию ПО.

- **URL**: https://www.software-testing.ru/
- **CMS**: Joomla 1.5 ⚠️ требует обновления — версия сильно устарела

## Форум

Форум по тестированию — раздел software-testing.ru для общения участников сообщества.

- **URL**: https://software-testing.ru/forum/
- **Движок**: Invision Power Board ⚠️ больше не поддерживается — требуется миграция на другой движок

## LMS Moodle

Система дистанционного обучения — платформа для проведения курсов.

- **URL**: https://software-testing.ru/lms/
- **Движок**: Moodle

## Сайт курсов `/edu/`

Раздел сайта, через который продаются курсы по тестированию.

- **URL**: https://www.software-testing.ru/edu/
- **CMS**: Joomla (текущее состояние)
- **План**: переписать на генераторе статических сайтов Astro; данные о курсах получать из дашборда как единого источника

## Дашборд

Система регистрации и учёта студентов. Студенты регистрируются на курсы, ведётся их учёт, выдаются сертификаты об окончании.

- **Исходный код**: `g:\devel\my\stqa\stqa\`
- **БД (регистрации и курсы)**: PostgreSQL на [sweb.ru](https://sweb.ru)
- **БД (сертификаты)**: отдельная PostgreSQL там же на sweb.ru
  - Альтернативные сервисы для PostgreSQL: [reg.cloud](https://reg.cloud/services/postgresql) · [beget.com Cloud DBaaS](https://beget.com/ru/cloud/dbaas)
- **Приложение сертификатов**: развёрнуто на [amvera.ru](https://amvera.ru)
- **Домен сертификатов**: [cert.software-testing.ru](https://cert.software-testing.ru)
- **Регистратор домена**: [webnames.ru](https://webnames.ru)

## Общая инфраструктура

### Почта
- **Почтовый сервер**: mail.holder.ru, протокол SMTP
- **Назначение**: информационные рассылки
- **Резервный вариант**: [Selectel SMTP](https://selectel.ru/services/additional/smtp/?section=documentation)

### Домены и DNS
- **Регистратор**: [webnames.ru](https://webnames.ru) (Регтайм)
- **DNS-провайдер**: webnames.ru (тот же)

### Хостинг и серверы
*(уточнить: провайдер, тарифы)*

### Базы данных
*(см. раздел Дашборд; уточнить, есть ли другие БД)*

### Платежи
*(уточнить: как принимается оплата курсов)*

### Резервные копии
*(уточнить)*

## Интеграции

| Откуда | Куда | Что передаётся | Статус |
|--------|------|----------------|--------|
| Сайт курсов `/edu/` | Дашборд | Факт оплаты → регистрация студента | ⚠️ сломано |

## Project Resources
- [[04-projects/stqa-infrastructure/BACKLOG|Задачи и баги]]

## Related
- [[04-projects/courses/PROJECT-OVERVIEW|Разработка и доработка курсов]]

## Notes
Пароли и ключи в хранилище не записывать; фиксировать только, где они хранятся.

---

*This overview helps COG organize your project-related thoughts and updates.*
