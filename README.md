Nikita Y. | wobbbler9@gmail.com | tg: @wobbbler
---
Java backend developer 
---
**опыт**
-
-
-
---
**ТЕХНОЛОГИЧЕСКИЙ СТЕК**
**Programming Languages & Tools:**
- Java, Spring, Maven, Git

**Design & Architecture:**
- REST API
- понимание антипаттернов
- Применяю: SOLID. GoF: порождающие, структурные, поведенческие. Domain-Driven Design(DDD)
- паттерны микросервисов: API Gateway, Database per Service, Способы коммуникации: синхронная через REST, асинхронная через Message Broker. Saga, CQRS

**Spring Security:**
...

**DB:**
- MSSQL / H2
- Hibernate / JPA, JDBC, Liquibase
- уверенная работа с реляционными данными и транзакциями (ACID)
- оптимизация запросов с помощью: индексов, EXPLAIN
- понимание как работает: пул соединений (HikariCP), Hibernate кэш L1/L2

**NoSQL:**
- mongoDB:
  - ...
- redis
  - ...
  - когда освоишь напишешь более общими понятиями 

**Apache Kafka:**
- Топологии и партиционирование — ключи, расчет партиций, порядок сообщений
- Producer API — идемпотентность, транзакционные продюсеры, acks, ретраи, batch, сжатие
- Consumer API — группы, ребалансировка, таймауты (poll, session), exactly-once семантика (isolation.level=read_committed)
- Offset management — авто/ручной коммит, гарантии доставки (at-least-once, exactly-once)
- Serialization — JSON, Avro + Schema Registry
- Error handling — Dead Letter Queue, retry-топики, poison pills
- Kafka Connect — коннекторы (Debezium, JDBC)
- Kafka Streams
- когда освоишь напишешь более общими понятиями 


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
- - когда освоишь напишешь более общими понятиями 

**Full Observability cycle:**
- **логи:** SLF4J/Logback + MDC (traceId) в JSON → Promtail → Loki
- **метрики:** Prometheus (kube-state-metrics, node-exporter, приложения через Micrometer)
- **трейсинг:** Tempo 
- **корреляция:** через Grafana Explore, связь логов, метрик и трейсов по лейблам
- **визуализация и алертинг:** Grafana/Alerting
- JVM-инструменты (GraalVM, JFR). 


**DevOps:**
- **Docker:**
  - multi-stage сборки, оптимизация Dockerfile, Docker Compose, Docker Hub
- **Kubernetes:**
  - развертывание, управление через kubectl
  - обьекты k8s: Deployment, Service, ConfigMap, PV/PVC, Network Policies
  - пакетный менеджер Helm + Kustomize 
  - GitOps (ArgoCD)
  - Kubernetes Operators (Cert-Manager, использование готовых / написание своих, External Secrets...)
  - Service Mesh: Istio для полноценного управления трафика
- **secret manager**:k8s Secret, HashiCorp Vault(...)
- Уверенная работа с **Linux**(...)

**CI/CD:**
- Spring Profiles
- GitHub Actions (...)

**Testing:**
- JUnit 5, Mockito, WireMock, Spring Boot Test
- Unit / интеграционные тесты (@SpringBootTest)
- Testcontainers
- Postman
- k6  

**для отказоустойчивости**
- **Resilience4j**: ...

**Additional Tools and documentation:**
Lombok, Validation, JavaDoc, SpringDoc OpenAPI & Swagger UI, OpenAPI Generator & Contract First, API Versioning, AsyncAPI

**Other Skills:**
- IDE: IntelliJ IDEA, VS Code, NVIM
- XXX задач на Codewars/LeetCode + ссылка
- Big O, алгоритмы и структуры данных
- blind typing XX wpm
- Языки: русский, украинский, технический английский
---

технолгический стек вынеси кудато в низ в cv и other skilss а главное твой опыт
тогда не будет прямых точек для удара зато будет опыт 
