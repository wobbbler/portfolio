ДОП

- Отрепетируй все вопросы и ответы. Будь уверен, не трать время на «бэ-мэ».
- К собеседованию надо готовиться.

БЛОГЕРЫ
- Влад Мишустин
- Одноглазый змей
- Уголок джависта
- Сорокин Павел
- Артём Шумейко
- Eugene Suleimanov
- Максим Добрынин
- Мир IT с Антоном Павленко
- Посмотри на YouTube — там всё.


ЧТО СДЕЛАТЬ
- Сравни своё резюме с другими, пойми, что учесть, учить / добавить.
- https://www.youtube.com/watch?v=VwoD3FsJoWo — видео: резюме = реклама продукта, а не рассказ о себе.

────────────────────────────────

ТРЕБОВАНИЯ К РЕЗЮМЕ

────────────────────────────────

ПОДГОТОВКА К СОБЕСЕДОВАНИЮ

ВАЖНЫЕ ПРИНЦИПЫ
- Правдивость.
- Релевантность (только под вакансию).
- Конкретика (цифры, факты).
- Грамотность (без ошибок).
- Удобочитаемость (чёткая структура, единый шрифт).

ЧТО НЕ НУЖНО В РЕЗЮМЕ
- Фото (если не требуется явно).
- Личные данные (семейное положение, ИНН и пр.) — всем всё равно.

СТРУКТУРА И ВОСПРИЯТИЕ
- Лаконично, аккуратно, без ошибок.
- 1 страница.
- Горячие точки: сверху и слева. Низ не читают.
- Пустое место — только обоснованно.
- Резюме за 30 секунд должно показать, что ты подходишь.

ТРИ «ПРИВРАТНИКА»
1. HR / рекрутер — ключевые слова из вакансии.
2. Тимлид — глубина понимания технологий, реальный опыт.
3. Будущие коллеги — нестандартные темы (личные проекты, open-source, IT-хобби).

НАВЫКИ — С ДОКАЗАТЕЛЬСТВАМИ
- Не перечисляй всё подряд.
- Упор на проекты и роль.
- Будь готов ответить за каждый пункт.
- Пиши только то, в чём уверен.

ЯЗЫК РЕЗЮМЕ
- Украинский (переведу позже). Технические термины остаются на английском.

ДОПОЛНИТЕЛЬНЫЕ ЗАМЕТКИ ПО РЕЗЮМЕ
- Вместо размытого «О себе» — сразу «Java Backend Developer». Горячая часть — сверху и слева.
- Когда смотрят резюме, ставят плюсики. Чем они весомей и больше — тем лучше.

(с) Ссылка на видео по soft skills: https://www.youtube.com/watch?v=JKICGa4J-qc

────────────────────────────────

В РЕЗЮМЕ (ЧЕРНОВИК)
online-cv https://github.com/sharu725/online-cv потом сюда мигрируешь 
всё должно быть коротко сжато но ёмко. за 30 секунд показать что ты это ты

---

NIKITA Y. | wobbbler9@gmail.com | tg: @wobbbler

Я Java backend developer разрабатываю высоконагруженные, отказоустойчивые и маштабируемые системы на микросервисной архитектуре. Следую принципам чистой архитектуры и постоянно изучаю новые технологии, и совершенствую в том в чём я хорошо знаю 
---

ОПЫТ:

грубо говоря твой опыт разделяется на 2 группы: петы, и стек поэтому чтобы не повторяться стек это стек, а пет проекты описывай более обобщённо, как вступление сверху только про проект. а вот внутри репозитория всё как надо расписывай

ОФОРМЛЕНИЕ ПРОЕКТА В РЕПОЗИТОРИИ
можно вообще в github project
В README опиши:
- что реализовал (главное);
- конкретные задачи: реализовал, сделал, добавил, интегрировал, оркестрировал;
- инструкция запуска;
- интерактивная документация, нужные ссылки;
- кратко, без воды.

СТРУКТУРА ОПИСАНИЯ В РЕЗЮМЕ:
- Название / тематика (FoodDelivery, BookingPlatform, BankSystem...)
- Стек: (ключевые технологии) ненадо перечислаять стек второй раз. там где "Реализовано: " вот там и пиши в общем что именно ты зделал
- Реализовано:
  - сделал …;
  - добавил …;
  - интегрировал …;
  - оркестрировал …;
  - и т.д. (немного, по делу).
---

ТЕХНОЛОГИЧЕСКИЙ СТЕК
**Programming Languages & Tools:**
Java (LTS), Spring Framework, REST API, Maven, Git. 
следование и понимание SOLID, GoF, антипаттернов и паттернов микросервисов(...)

**Spring Security:**
(JWT, OAuth2, Basic), Keycloak, CORS/CSRF, 
централизованная валидация токенов в микросервисах (API Gateway).
(дополнишь с канала «Уголок сельского джависта»)

**DB:**
PostgreSQL/H2, Hibernate/JPA, JDBC, Liquibase. 
Уверенная работа с реляционными данными и транзакциями(ACID), оптимизация запросов с помощью (...)


Apache Kafka 
1. Топологии и партиционирование — ключи, расчет партиций, порядок сообщений
2. Producer API — идемпотентность, acks, ретраи, batch, сжатие
3. Consumer API — группы, ребалансировка, таймауты (poll, session)
4. Offset management — авто/ручной коммит, гарантии доставки (at-least-once, exactly-once)
5. Serialization — JSON, Avro + Schema Registry
6. Error handling — Dead Letter Queue, retry-топики, poison pills
7. Monitoring — lag, kafka-consumer-groups, Kafka UI, Cruise Control
8. Kafka Connect — коннекторы (Debezium, JDBC)

Redis
1. Структуры данных — Strings, Lists, Sets, Hashes, Sorted Sets, Bitmaps, HyperLogLog
2. Persistency — RDB (снэпшоты), AOF (лог), компромиссы
3. High Availability — Sentinel (failover), Cluster (шардинг)
4. Pub/Sub — каналы, реальное время (без персистентности)
5. Memory management — политики eviction (LRU, TTL), maxmemory, MEMORY команды
6. Распределенные блокировки — Redlock, таймауты
7. Клиенты — пул соединений, pipeline, выбор драйвера

**full Observability cycle:**
- логи (SLF4J/Logback -> Promtail -> Loki)
- метрики (Actuator -> Micrometer -> Prometheus)
- трейсинг (OpenTelemetry -> Collector -> Tempo)
— всё в Grafana + alerting

**Resilience:** Resilience4j(CircuitBreaker, Retry, RateLimiter, Bulkhead, TimeLimiter)

**DevOps:**
- **Docker:**
  – multi-stage сборки, оптимизация Dockerfile
  – Docker Compose, публикация образов в Docker Hub
- **Kubernetes:**
  – развертывание, управление через kubectl и Kubernetes Dashboard
  – создание и настройка Deployment, Service, Ingress, ConfigMap, Secret, PersistentVolumeClaim, Network Policies
  – настройка Ingress с NGINX
  – пакетный менеджер Helm
  - Kubernetes Operators(...)
  - GitOps (ArgoCD)
- **API Gateway:** Spring Cloud Gateway, NGINX

**CI/CD:**
- Spring Profiles, GitHub Actions

**Testing:**
- JUnit 5, Mockito, Spring Boot Test
- Unit / интеграционные тесты (@SpringBootTest)
- Testcontainers
- Postman
- k6

**Additional Tools and documentation:**
- Lombok, MapStruct, Validation, Apache Commons Lang / Guava
- JavaDoc, SpringDoc OpenAPI, Swagger UI/contract first, AsyncAPI for  асинхронных API kafk-и

**Other Skills:**
- IDE: IntelliJ IDEA, VS Code
- Уверенная работа с Linux терминалом, SSH
- XXX задач на Codewars/LeetCode + ссылка
- Big O, алгоритмы и структуры данных
- Blind typing — XXX wpm
- Языки: русский, украинский, технический английский
---

технолгический стек вынеси кудато в низ в cv и other skilss а главное твой опыт
