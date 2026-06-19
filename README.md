<div align="center">

# Привет! Меня зовут Сергей 👋

### Full-stack разработчик • PHP / Laravel • Vue.js • API-интеграции

Я разрабатываю веб-приложения, интеграционные сервисы и решения для автоматизации бизнеса.  
Основное направление моей работы — сложные интеграции с внешними API, обработка бизнес-процессов, очереди, синхронизация данных и надёжная серверная архитектура.

[![GitHub](https://img.shields.io/badge/GitHub-Slonexx-181717?style=for-the-badge&logo=github)](https://github.com/Slonexx)

</div>

---

## 👨‍💻 Обо мне

Я специализируюсь на backend-разработке на **PHP 8 и Laravel**, но также самостоятельно разрабатываю frontend на **Vue 3 и Vuetify**, проектирую базы данных и настраиваю серверное окружение.

Моя основная специализация — создание интеграционных решений для бизнеса:

- интеграции с внешними REST API;
- синхронизация заказов, товаров, остатков и контрагентов;
- автоматизация продаж и фискализации;
- подключение программ лояльности и платёжных сервисов;
- обработка webhook-событий;
- фоновые задачи, очереди и повторные попытки;
- защита от дублей и обеспечение идемпотентности;
- развёртывание и сопровождение проектов на Ubuntu-серверах.

Я стараюсь не просто реализовать функциональность, а сделать решение понятным, расширяемым и устойчивым к ошибкам внешних систем.

---

## 🚀 Основные направления и достижения

### Интеграции с МойСклад

Разрабатываю приложения и интеграционные модули для экосистемы **МойСклад**:

- обработка заказов, отгрузок, возвратов и контрагентов;
- работа с товарами, остатками, ценами и дополнительными полями;
- обработка webhook-событий;
- массовая и периодическая синхронизация данных;
- контроль лимитов API;
- защита от повторной обработки событий;
- собственная PHP-библиотека для работы с API МойСклад.

### Онлайн-кассы и платежи

Разрабатывал интеграции с кассовыми и платёжными решениями:

- **WebKassa**;
- **reKassa**;
- **Atol / AtolPay**;
- фискализация продаж и возвратов;
- поддержка разных типов оплаты;
- обработка статусов чеков и ошибок;
- работа с маркированными товарами;
- привязка касс и торговых точек.

### Маркетплейсы и программы лояльности

Работал с интеграциями:

- **Kaspi Магазин**;
- **Halyk Market**;
- **UDS**;
- выгрузка и обновление заказов;
- синхронизация товаров;
- начисление и списание бонусов;
- расчёт скидок и кешбэка;
- обработка длительных и отменённых заказов;
- импорт данных для аналитики без дублей.

### Архитектура и надёжность

В проектах использую:

- сервисный слой и разделение ответственности;
- DTO и Form Request;
- API-клиенты и менеджеры сущностей;
- Laravel Jobs и очереди;
- повторные попытки и обработку исключений;
- Redis-блокировки и rate limiting;
- идемпотентность и дедупликацию;
- логирование и Laravel Telescope;
- пакетную и асинхронную обработку запросов;
- оптимизацию Eloquent и SQL-запросов.

---

## 🛠 Технологический стек

### Backend

![PHP](https://img.shields.io/badge/PHP_8-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel_9-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL_8-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

- PHP 8.0;
- Laravel 9;
- REST API и Webhooks;
- Eloquent ORM и Query Builder;
- Laravel Queue, Scheduler и Telescope;
- Guzzle;
- ReactPHP;
- Redis;
- PHPUnit и Feature Tests.

### Frontend

![Vue.js](https://img.shields.io/badge/Vue.js_3-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![Vuetify](https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge&logo=vuetify&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

- Vue 3;
- Vuetify;
- JavaScript;
- Axios;
- Laravel Mix;
- HTML5 и CSS3;
- адаптивные административные интерфейсы.

### Серверы и инфраструктура

![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=for-the-badge&logo=apache&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

- Ubuntu Server;
- FastPanel;
- Apache / Nginx;
- PHP-FPM;
- Supervisor и systemd;
- Cron и Laravel Scheduler;
- настройка очередей и worker-процессов;
- права доступа и безопасный деплой;
- логирование и ротация логов;
- Git и SSH Deploy Keys.

---

## 🧩 Как я проектирую приложения

```text
HTTP Request
    ↓
Route
    ↓
Controller
    ↓
Form Request / DTO
    ↓
Application Service
    ↓
Domain / Business Logic
    ↓
Repository or External API Client
    ↓
Resource / API Response
```

Контроллеры отвечают за HTTP-слой, сервисы — за сценарии приложения, а отдельные клиенты — за работу с внешними API.

Я стараюсь применять **SOLID**, чистую архитектуру и шаблоны проектирования осознанно — только там, где они упрощают поддержку проекта, а не создают лишнюю сложность.

---

## 📌 Публичные проекты

### [VetMobile](https://github.com/Slonexx/VetMobile)

Один из моих публичных проектов.

### [LaravelRestAPI](https://github.com/Slonexx/LaravelRestAPI)

Проект, посвящённый разработке REST API на Laravel.

### [Vakansia](https://github.com/Slonexx/Vakansia)

Публичный учебный или экспериментальный проект.

> Большая часть моих основных проектов и коммерческих интеграций находится в закрытых репозиториях.

---

## 📈 GitHub-статистика

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Slonexx&show_icons=true&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Slonexx&layout=compact&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com?user=Slonexx&hide_border=true)

</div>

---

## 🎯 Профессиональные интересы

Сейчас я продолжаю развиваться в направлениях:

- Clean Architecture и DDD;
- проектирование интеграционных платформ;
- событийная архитектура;
- CQRS и Event Sourcing;
- Kafka, RabbitMQ и Redis Streams;
- Transactional Outbox;
- горизонтальное масштабирование;
- мониторинг и отказоустойчивость;
- автоматизация разработки с использованием AI.

---

<div align="center">

### Создаю не просто код, а работающие решения для автоматизации бизнеса

</div>
