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


**ТЕХНОЛОГИЧЕСКИЙ СТЕК**
**Programming Languages & Tools:**
- Java 21, Spring Boot 3.x REST API, Maven, Git

**Design & Architecture:**
- понимание антипаттернов
- следование: SOLID
- GoF:
  - порождающие (Singleton, Factory Method, Abstract Factory, Builder)
  - структурные (Proxy, Decorator, Adapter)
  - поведенческие (Strategy, Template Method, Observer, Chain of Responsibility)
- паттерны микросервисов: Saga, CQRS, API Gateway

**Spring Security:**
- JWT, OAuth2, Basic
- Keycloak
- CORS/CSRF
- написание фильтров безопасности
- централизованная валидация токенов в микросервисах (Spring API Gateway)
- (дополнишь с канала «Уголок сельского джависта»)

**DB:**
- PostgreSQL / H2
- Hibernate / JPA, JDBC, Liquibase
- уверенная работа с реляционными данными и транзакциями (ACID)
- оптимизация запросов с помощью индексов, EXPLAIN
- понимание как работает: пул соединений (HikariCP), Hibernate кэш L1/L2

**Apache Kafka:**
- Топологии и партиционирование — ключи, расчет партиций, порядок сообщений
- Producer API — идемпотентность, транзакционные продюсеры, acks, ретраи, batch, сжатие
- Consumer API — группы, ребалансировка, таймауты (poll, session), exactly-once семантика (isolation.level=read_committed)
- Offset management — авто/ручной коммит, гарантии доставки (at-least-once, exactly-once)
- Serialization — JSON, Avro + Schema Registry
- Error handling — Dead Letter Queue, retry-топики, poison pills
- Kafka Connect — коннекторы (Debezium, JDBC)
- Kafka Streams

**Redis:**
- Структуры данных — Strings, Lists, Sets, Hashes, Sorted Sets, Bitmaps
- Persistency — RDB (снэпшоты), AOF (лог), компромиссы
- High Availability — Sentinel (failover), Cluster (шардинг)
- Pub/Sub — каналы, реальное время (без персистентности)
- Memory management — политики eviction (LRU, TTL), maxmemory, MEMORY команды
- Распределенные блокировки
- Клиенты (Lettuce), пул соединений, pipeline, выбор драйвера
- blacklist через Redis
- Redis Stack (модули RediSearch, RedisJSON)

**Full Observability cycle:**
- **логи:** SLF4J/Logback + MDC (traceId) в JSON → Filebeat → Logstash → Elasticsearch  
- **метрики:** Actuator / Micrometer, Kubernetes (kube-state-metrics, metrics-server, Node Exporter) → Metricbeat → Elasticsearch  
- **трейсинг:** Elastic APM Java agent → Elastic APM Server → Elasticsearch  
- **корреляция:** traceId в MDC связывает логи и трейсы в Kibana  
- **визуализация и алертинг:** Kibana + Kibana Alerting / ElastAlert

**DevOps:**
- **Docker:**
  - multi-stage сборки, оптимизация Dockerfile, Docker Compose, Docker Hub
- **Kubernetes:**
  - развертывание, управление через kubectl
  - создание и настройка Deployment, Service, ConfigMap, Secret, PV/PVC, Network Policies
  - настройка Ingress с traefic (...)
  - пакетный менеджер Helm
  - GitOps (ArgoCD)
  - Kubernetes Operators (Cert-Manager, использование готовых / написание своих)
  - Service Mesh: Istio
- **API Gateway:** Spring Cloud Gateway (...)
- vault: ...

**CI/CD:**
- Spring Profiles
- GitHub Actions (...)

**Testing:**
- JUnit 5, Mockito, WireMock, JaCoCo, Spring Boot Test
- Unit / интеграционные тесты (@SpringBootTest)
- Testcontainers
- Postman
- wrk2

**Additional Tools and documentation:**
- Lombok, MapStruct, Validation, Apache Commons Lang / Guava, SonarQube, OpenAPI Generator
- JavaDoc, SpringDoc OpenAPI, Swagger UI / contract first, AsyncAPI для асинхронных API (Kafka)

**Other Skills:**
- IDE: IntelliJ IDEA, VS Code
- Уверенная работа с Linux терминалом, SSH
- XXX задач на Codewars/LeetCode + ссылка
- Big O, алгоритмы и структуры данных
- Языки: русский, украинский, технический английский
---

технолгический стек вынеси кудато в низ в cv и other skilss а главное твой опыт
тогда не будет прямых точек для удара зато будет опыт 
