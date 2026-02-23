NIKITA Y. | wobbbler9@gmail.com | tg: @wobbbler

Я Java backend developer разрабатываю высоконагруженные, отказоустойчивые и маштабируемые системы на микросервисной архитектуре. Следую принципам чистой архитектуры и постоянно изучаю новые технологии, и совершенствуюсь в изученом 
---

опыт

---
**ТЕХНОЛОГИЧЕСКИЙ СТЕК**
**Programming Languages & Tools:**
- Java 21, Spring Boot 3.x, REST API, Maven, Git

**Design & Architecture:**
- понимание антипаттернов
- Применяю: SOLID
- GoF:
  - порождающие (Singleton, Factory Method, Abstract Factory, Builder)
  - структурные (Proxy, Decorator, Adapter)
  - поведенческие (Strategy, Template Method, Observer, Chain of Responsibility)
- Domain-Driven Design: Bounded Context, Aggregate, Value Object, Domain Events
- паттерны микросервисов: Saga, CQRS + Event Sourcing, API Gateway

**Spring Security:**
- JWT/OAuth2, Basic Auth
- Keycloak
- CORS/CSRF
- написание фильтров безопасности
- централизованная валидация токенов в микросервисах (Spring API Gateway)
- (дополнишь с канала «Уголок сельского джависта»)

**DB:**
- PostgreSQL / H2
- Hibernate / JPA, JDBC, Liquibase
- уверенная работа с реляционными данными и транзакциями (ACID)
- оптимизация запросов с помощью: индексов, EXPLAIN
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
- **визуализация и алертинг:** Kibana + Kibana Alerting 

**DevOps:**
- **Docker:**
  - multi-stage сборки, оптимизация Dockerfile, Docker Compose, Docker Hub
- **Kubernetes:**
  - развертывание, управление через kubectl
  - обьекты k8s: Deployment, Service, ConfigMap, PV/PVC, Network Policies
  - настройка Ingress с Traefik (...)
  - пакетный менеджер Helm
  - GitOps (ArgoCD)
  - Kubernetes Operators (Cert-Manager, использование готовых / написание своих, External Secrets...)
  - Service Mesh: Istio
- **API Gateway:** Spring Cloud Gateway (...)
- **secret manager**:k8s Secret, HashiCorp Vault(...) 

**CI/CD:**
- Spring Profiles
- GitHub Actions 

**Testing:**
- JUnit 5, Mockito, WireMock, JaCoCo, Spring Boot Test
- Unit / интеграционные тесты (@SpringBootTest)
- Testcontainers
- Postman
- wrk2

**Additional Tools and documentation:**
- Lombok, MapStruct, Validation, Apache Commons Lang / Guava, SonarQube, OpenAPI Generator
- JavaDoc, SpringDoc OpenAPI, Swagger UI / contract first

**Other Skills:**
- IDE: IntelliJ IDEA, VS Code, NVIM
- Уверенная работа с Linux
- XXX задач на Codewars/LeetCode + ссылка
- Big O, алгоритмы и структуры данных
- blind typing XX wpm
- Языки: русский, украинский, технический английский
---

технолгический стек вынеси кудато в низ в cv и other skilss а главное твой опыт
тогда не будет прямых точек для удара зато будет опыт 
