Spring-starter

#  1. Intro
=================

## lesson 1. Введение

+ ### `Модули Spring (out of the box)`



+ ### `Удобство и простота использования`


+ ### `Микросервисная архитектура`



+ ### `Support & Community`


+ ### `Что нужно знать для изучения курса Spring`


Для изучения курса Spring в Java полезно иметь базовые знания и опыт работы с языком программирования Java. Вот некоторые ключевые концепции и технологии, с которыми полезно ознакомиться перед изучением Spring:

`1. Java SE`: Убедитесь, что вы знакомы с основами языка Java, такими как синтаксис, типы данных, операторы, циклы и условные выражения.

`2. Java EE`: Понимание основных концепций Java Enterprise Edition (Java EE) также будет полезно при изучении Spring. Java EE предоставляет набор спецификаций и API для разработки масштабируемых и надежных приложений.

`3. SQL`: Знание языка структурированных запросов (SQL) будет полезно при работе с базами данных в Spring.

`4. ООП и принципы SOLID`: Понимание основ объектно-ориентированного программирования (ООП) и принципов SOLID (Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, Dependency Inversion) поможет вам разрабатывать гибкие и расширяемые приложения с использованием Spring.

`5. MVC`: Понимание паттерна проектирования Model-View-Controller (MVC) будет полезно при работе с Spring MVC, который предоставляет инструменты для разработки веб-приложений.

`6. Hibernate`: Знание Hibernate, фреймворка для работы с базами данных, также может быть полезным, так как Spring интегрируется с Hibernate для упрощения доступа к данным.

`7. Тестирование`: Знание основных принципов и инструментов для тестирования кода, таких как JUnit, будет полезно при разработке приложений с использованием Spring.

`8. Git`: Знание системы контроля версий Git и понимание основных команд Git помогут вам эффективно управлять и отслеживать изменения в вашем проекте.

Это лишь некоторые из ключевых концепций и технологий, которые могут быть полезны при изучении Spring в Java.

## lesson 2. Установка программного обеспечения


+ ### `Установка Java 17`


Для установки Java 17 на Windows вы можете следовать этим шагам:

Скачайте JDK: Перейдите на официальный сайт Oracle по адресу oracle.com и скачайте дистрибутив JDK для Windows. Выберите версию, соответствующую вашей операционной системе (например, Windows x64).

Установите JDK: Запустите загруженный установщик JDK и следуйте инструкциям мастера установки. По умолчанию, JDK будет установлен в папку C:\Program Files\Java\jdk-17.

Настройте переменные среды: Добавьте переменную среды JAVA_HOME, указывающую на папку, где установлен JDK. Чтобы это сделать, откройте "Системные свойства" (например, через "Панель управления" -> "Система" -> "Дополнительные параметры системы" -> "Переменные среды") и создайте новую системную переменную с именем JAVA_HOME и значением C:\Program Files\Java\jdk-17 (если вы выбрали другую папку установки, укажите соответствующий путь).

Обновите переменную среды PATH: Добавьте путь к исполняемым файлам JDK в переменную среды PATH. Чтобы это сделать, найдите переменную среды PATH в списке системных переменных, выберите ее и нажмите "Изменить". Добавьте ;%JAVA_HOME%\bin в конец значения переменной PATH (обратите внимание на точку с запятой в начале).

Проверьте установку: Откройте командную строку и введите команду java -version. Если установка прошла успешно, вы должны увидеть информацию о версии Java 17.

Теперь у вас должна быть установлена Java 17 на вашей системе Windows. Вы можете использовать ее для разработки и выполнения Java-приложений.

+ ### `Установка IntelliJ IDEA Ultimate Edition`
+ ### `Установка PostgreSQL`
+ ### `Установка Docker`
+ ### `Создание нового проекта`


## lesson 3. Inversion of Control. Dependency Injection

+ ### `Object Dependencies`
+ ### `Object Dependencies в коде`
+ ### `Inversion of Control & Dependency Injection`
+ ### `Inversion of Control & Dependency Injection в коде`
+ ### `3 способа внедрения зависимостей в объекте`


## lesson 4. IoC Container

+ ### `Spring IoC Container`
+ ### `Bean`
+ ### `Bean Definition`
+ ### `POJO`
+ ### `Основные интерфейсы IoC Container`
+ ### `3 способа создания Bean Definitions`




# 2. XML-based Configuration

## lesson 5. XML-based Configuration

+ ### `BeanFactory и ApplicationContext интерфейсы`
+ ### `ClassPathXmlApplicationContext`
+ ### `XML config`
+ ### `Идентификаторы (id) бинов как ключи в IoC Container`
+ ### `Алиасы бинов (alias)`

## lesson 6. Constructor Injection

+ ### `Внедрение примитивных типов данных`
+ ### `Внедрение коллекций list/set`
+ ### `Внедрение ассоциативного массива map`
+ ### `Поле genericArgumentValues в BeanDefinition`
+ ### `Поле indexedArgumentValues в BeanDefinition`
+ ### `Указание атрибута type в параметрах конструктора`
+ ### `Указание атрибута name в параметрах конструктора`

## lesson 7. Factory Method Injection

+ ### `Внедрение других бинов через ref*`
+ ### `Создание новое бина CompanyRepository`
+ ### `Внедрение зависимостей через factory method`
+ ### `Атрибут factory-bean (паттерн ServiceLocator)`

## lesson 8. Property Injection

+ ### `Использование set* методов в ConnectionPool`
+ ### `Поле propertyValues в BeanDefinition`
+ ### `Упрощенный жизненный цикл бинов - Bean Lifecycle`
+ ### `Плюсы и минусы Constructor и Property Injections`
+ ### `Циклические зависимости через Property Injection`

## lesson 9. Bean Scopes

+ ### `Common Bean Scopes`
+ ### `Custom Bean Scopes`
+ ### `Web Bean Scopes`
+ ### `Prototype Bean Scope`

## lesson 10. Lifecycle Callbacks

+ ### `Измененный Bean Lifecycle`
+ ### `Initialization callbacks`
+ ### `Destruction callbacks`

## lesson 11. Injection from Properties Files

+ ### `Зачем использовать properties files`
+ ### `Создание файла application.properties`
+ ### `PropertySourcesPlaceholderConfigurer bean`
+ ### `Expression Language (EL)`
+ ### `Spring Expression Language (SpEL)`
+ ### `SpEL документация`
+ ### `System properties`

## lesson 12. BeanFactoryPostProcessor (BFPP)

+ ### `Интерфейс BeanFactoryPostProcessor`
+ ### `Как работает PropertySourcesPlaceholderConfigurer`
+ ### `Измененный Bean Lifecycle`
+ ### `Метод isAssignableFrom`

## lesson 13. Custom BeanFactoryPostProcessor

+ ### `Создание собственных BeanFactoryPostProcessor`
+ ### `Интерфейс Ordered`
+ ### `Интерфейс PriorityOrdered`


# 3. Annotation-based Configuration

## lesson 14. Annotation-based Configuration

+ ### `Подключение зависимости jakarta annotation api`
+ ### `Аннотации @PostConstruct и @PreDestroy`
+ ### `Класс CommonAnnotationBeanPostProcessor`
+ ### `context:annotation-config xml element`




## lesson 15. BeanPostProcessor (BPP)

+ ### `Интерфейс BeanPostProcessor`
+ ### `Bean Lifecycle (final version)`
+ ### `Интерфейс Aware`
+ ### `Класс ApplicationContextAwareProcessor`


## lesson 16. Custom BeanPostProcessor. Часть 1

+ ### `Создание своей аннотации @InjectBean`
+ ### `Создание InjectBeanPostProcessor`
+ ### `Утилитный класс ReflectionUtils`
+ ### `Тестирование InjectBeanPostProcessor`

## lesson 17. Custom BeanPostProcessor. Часть 2
+ ### `Создание аннотации @Transaction`
+ ### `Создание CrudRepository`
+ ### `Создание TransactionBeanPostProcessor`
+ ### `Тестирование TransactionBeanPostProcessor`
+ ### `Корректируем TransactionBeanPostProcessor`
+ ### `Создание AuditingBeanPostProcessor`


## lesson 18. @Autowired & @Value

+ ### `Аннотация @Autowired`
+ ### `Аннотация @Resource`
+ ### `Решение конлифкта бинов. @Qualifier`
+ ### `Collection injection`
+ ### `Properties injection. @Value`


## lesson 19. Classpath Scanning
+ ### `context:component-scan. Аннотации @Component`
+ ### `Замена бинов из xml на @Component`
+ ### `Тестирование функционала`

## lesson 20. Bean Definition Readers

+ ### `Component Scan classes`
+ ### `Bean Definition Readers`
+ ### `Класс ComponentScanBeanDefinitionParser`
+ ### `Класс AnnotatedBeanDefinitionReader`

## lesson 21. Type Filters

+ ### `Атрибут annotation-config`
+ ### `Атрибут name-generator`
+ ### `Атрибут resource-pattern`
+ ### `Атрибут scoped-proxy`
+ ### `Атрибут scope-resolver`
+ ### `Атрибут use-default-filters`
+ ### `5 type filters`
+ ### `Custom filters`


## lesson 22. @Scope
+ ### `Атрибут scope-resolver`
+ ### `Класс AnnotationScopeMetadataResolver`
+ ### `Аннотация @Scope`


## lesson 23. JSR 250, JSR 330

+ ### `Аббревиатура JSR`
+ ### `JSR 250`
+ ### `JSR 330`
+ ### `Класс Jsr330ScopeMetadataResolver`



# 4. Java-based Configuration

## lesson 24. Java-based Configuration
+ ### `Класс ConfigurationClassBeanDefinitionReader`
+ ### `Создание ApplicationConfiguration. @Configuration`
+ ### `Аннотация @PropertySource`
+ ### `Аннотация @ComponentScan`
+ ### `Класс AnnotationConfigApplicationContext`


## lesson 25. @Import & @ImportResource
+ ### `Класс AnnotationConfigApplicationContext`
+ ### `Аннотация @ImportResource`
+ ### `Аннотация @Import`

## lesson 26. @Bean. Часть 1

+ ### `Аннотация @Bean`
+ ### `Тестирование Java конфигурации`
+ ### `Свойства аннотации @Bean`
+ ### `Аннотация @Scope с @Bean`
+ ### `Внедрение зависимостей с @Bean`
+ ### `Конфликт имен @Bean и @Component`

## lesson 27. @Bean. Часть 2

+ ### `3-ий вариант внедрения зависимостей в @Bean`
+ ### `Cglib proxy в @Configuration`
+ ### `Свойство proxyBeanMethods в @Configuration`
+ ### `@Bean создаются через паттерн Service Locator`

## lesson 28. Profiles
+ ### `Environment Bean`
+ ### `Аннотация @Profile`
+ ### `Активация profiles через properties`
+ ### `Активация profiles через ApplicationContext`





# 5. Event Listeners


## lesson 29. Event Listeners. Часть 1
+ ### `Шаблон проектирования Listener`
+ ### `Создание события (Event)`
+ ### `Создание слушателя событий (Listener). @EventListener`
+ ### `Реализация логики для отправки события`

## lesson 30. Event Listeners. Часть 2

+ ### `Bean ApplicationEventPublisher`
+ ### `Тестирование слушателей событий`
+ ### `Listeners order`
+ ### `Listeners conditions`


# 6. Spring Boot







## lesson 31. Spring Boot. Введение

+ ### `Spring modules`
+ ### `Spring Data Configuration`
+ ### `Modules Auto Configuration`
+ ### `Conditions`
+ ### `Spring Boot Starters`
+ ### `Dependency Management`
+ ### `How to build Spring Boot Application`

## lesson 32. @Conditional

+ ### `Аннотация @Conditional`
+ ### `Класс Condition`
+ ### `Custom JpaCondition`
+ ### `Тестирование JpaCondition`
+ ### `Аннотация @Profile`
+ ### `Другие @Condition аннотации`

## lesson 33. Spring Boot. Настройка проекта

+ ### `Spring Boot Gradle Plugin`
+ ### `Spring Dependency Management Plugin`
+ ### `spring-boot-starter`
+ ### `Run Spring Boot Application`
+ ### `Autogenerated Spring Boot Project`
+ ### `Maven spring-boot-starter-parent pom`

## lesson 34. @SpringBootApplication

+ ### `Структура Spring Boot приложения`
+ ### `Что делает метод SpringApplication.run`
+ ### `Аннотация @SpringBootApplication`
+ ### `Аннотация @SpringBootConfiguration`
+ ### `Аннотация @ComponentScan`
+ ### `Аннотация @PropertySource`
+ ### `Аннотация @EnableAutoConfiguration`


## lesson 35. Lombok

+ ### `Подключение Lombok`
+ ### `Gradle Lombok Plugin`
+ ### `IntelliJ IDEA Lombok Plugin`
+ ### `Аннотации Lombok`
+ ### `Файл lombok.config`

## lesson 36. Properties

+ ### `Файл spring.properties`
+ ### `Externalized Configuration`
+ ### `Profile-specific properties`
+ ### `Spring program arguments & VM options`
+ ### `Property Placeholders & Default values`
+ ### `spring.config.location`

## lesson 37. Yaml format

+ ### `YAML - Yet Another Markup Language`
+ ### `Класс YamlPropertiesFactoryBean`
+ ### `Приоритет properties vs yaml`
+ ### `Переписывание application.properties на yaml`


## lesson 38. @ConfigurationProperties

+ ### `Класс JpaProperties`
+ ### `Класс DatabaseProperties`
+ ### `Аннотация @ConfigurationProperties`
+ ### `Аннотация @ConfigurationPropertiesScan`
+ ### `Immutable DatabaseProperties`
+ ### `DatabaseProperties as record`
+ ### `Property key names`



# 7. Logging Starter


## lesson 39. Logging Starter

+ ### `Application as a Black Box`
+ ### `Logging libraries`
+ ### `Log Levels`
+ ### `spring-boot-starter-logging dependency`
+ ### `Аннотация @Slf4j`
+ ### `Delombok annotations`
+ ### `Формат логов по умолчанию`
+ ### `logging.* properties`

## lesson 40. Logback Configuration

+ ### `Logback default xml configs`
+ ### `File Output`
+ ### `Custom log configuration`


# 8. Test Starter

## lesson 41. Test Starter

+ ### `Подключение spring-boot-starter-test`
+ ### `Транзитивные зависимости spring-boot-starter-test`
+ ### `Зависимость spring-test`
+ ### `Зависимость spring-boot-test`
+ ### `Зависимость spring-boot-test-autoconfigure`
+ ### `Пример написания Unit тестов`
+ ### `Java Gradle Plugin tasks relationship`

## lesson 42. Integration Testing. Part 1

+ ### `Основные цели Spring Integration Testing`
+ ### `Жизненный цикл тестов`
+ ### `JUnit 5 Extension Model`
+ ### `TestContext Framework`
+ ### `SpringExtension source code
  `
## lesson 43. Integration Testing. Part 2

+ ### `Создание CompanyServiceIT`
+ ### `SpringExtension via @ExtendWith`
+ ### `Аннотация @ContextConfiguration`
+ ### `Аннотация @TestPropertySource`
+ ### `Класс ApplicationContextInitializer`
+ ### `Аннотация @SpringBootTest`
+ ### `Написание первого интеграционного теста`
+ ### `Класс DependencyInjectionTestExecutionListener`

## lesson 44. Integration Testing. Part 3

+ ### `Аннотация @ActiveProfiles`
+ ### `Custom Test Annotations`
+ ### `Аннотация @TestConstructor`
+ ### `Замена @TestConstructor на spring.properties`

## lesson 45. Context Caching

+ ### `Создание нескольких ApplicationContext в тестах`
+ ### `Аннотации @MockBean и @SpyBean`
+ ### `Класс MockitoTestExecutionListener`
+ ### `Аннотация @TestConfiguration`
+ ### `Аннотация @DirtiesContext`


# 9. Data JPA Starter

## lesson 46. Data JPA Starter. Введение
+ ### `Чего не хватало в Hibernate`
+ ### `Установка PostgreSQL`
+ ### `Установка Docker`
+ ### `Postgres Docker Image`
+ ### `Подключение к postgres из IntelliJ IDEA`

## lesson 47. Data JPA Starter. Подключение

+ ### `Подключение spring-boot-starter-data-jpa`
+ ### `Зависимости spring-boot-starter-data-jpa`
+ ### `Класс HibernateJpaAutoConfiguration`
+ ### `Настройка spring.datasource и spring.jpa properties`
+ ### `Тестирование приложения`

## lesson 48. Hibernate Entities

+ ### `UML диаграмма выполненных sql скриптов`
+ ### `Создание сущности Company`
+ ### `Создание коллекции locales (ElementCollection)`
+ ### `Создание сущности User`
+ ### `Создание сущности Payment`
+ ### `Создание сущности Chat`
+ ### `Создание сущности UserChat`
+ ### `Проверка маппинга сущностей через hbm2ddl.auto`
+ ### `Аннотация @EntityScan`


# 10. Data JPA Transactions

## lesson 49. @Transactional. TestContext
+ ### `Общая структура работы с TransactionManager`
+ ### `Создание CompanyRepository IT`
+ ### `Аннотации @Transactional из Jakarta EE и Spring`
+ ### `Класс TransactionalTestExecutionListener`
+ ### `Аннотации @Commit и @Rollback`

## lesson 50. TransactionAutoConfiguration
+ ### `Класс TransactionAutoConfiguration`
+ ### `Как происходит обработка транзакций в proxy`
+ ### `Аннотация @Transactional и Cglib proxy`
+ ### `Как работает Cglib proxy с TransactionManager`
+ ### `Как подключить механизм транзакций внутри объекта (не proxy)`
+ ### `Механизм транзакций между несколькими Cglib proxy`
+
## lesson 51. @Transactional Settings
+ ### `Свойства @Transactional. transactionManager`
+ ### `Transaction propagation`
+ ### `Transaction propagation резюме`
+ ### `Transaction isolation`
+ ### `Transaction timeout`
+ ### `ReadOnly transaction`
+ ### `Transaction rollbackFor & rollbackForClassName`
+ ### `Transaction noRollbackFor & noRollbackForClassName`


## lesson 52. Manual Transactions
+ ### `Свойства объекта TransactionTemplate`
+ ### `Функционал TransactionTemplate`
+ ### `Обработка checked exceptions`
+ ### `Взаимодействие TransactionTemplate с другими Proxy`
+ ### `Вынесение @Transactional в @IT`


# 11. Data JPA Repositories

## lesson 53. Repository
+ ### `Интерфейс Repository`
+ ### `Написание теста на удаление Company`
+ ### `Класс JpaRepositoryAutoConfiguration`

## lesson 54. RepositoryQuery
+ ### `Создание Proxy на классы Repository`
+ ### `Класс QueryExecutorMethodInterceptor`
+ ### `Класс RepositoryQuery`
+ ### `Наследники Repository`

## lesson 55. PartTreeJpaQuery
+ ### `Класс PartTreeJpaQuery`
+ ### `Примеры написания запросов`
+ ### `Тестирование запросов`
+ ### `Весь список ключевых слов PartTreeJpaQuery`


## lesson 56. NamedQuery

+ ### `Недостатки PartTreeJpaQuery`
+ ### `Класс NamedQuery`
+ ### `Аннотация @NamedQuery`
+ ### `Тестирование NamedQuery`
+ ### `Аннотация @Param`

## lesson 57. @Query
+ ### `StoredProcedureJpaQuery`
+ ### `Аннотация @Query`
+ ### `Демонстрация работы @Query`
+ ### `Усовершенствованный оператор LIKE`
+ ### `Native Query`

## lesson 58. @Modifying

+ ### `Запрос на обновление через @Query`
+ ### `Аннотация @Modifying`
+ ### `Hibernate PersistenceContext`
+ ### `Свойства clearAutomatically и flushAutomatically`
+ ### `clearAutomatically и LazyInitializationException`

## lesson 59. Special parameters

+ ### `Top & First`
+ ### `TopN & FirstN`
+ ### `Класс Sort`
+ ### `Класс Pageable`

## lesson 60. Page & Slice
+ ### `Spring классы Streamable, Slice, Page`
+ ### `Демонстрация работы Slice объекта`
+ ### `Почему Slice объекта недостаточно`
+ ### `Демонстрация работы Page объекта`

## lesson 61. @EntityGraph

+ ### `Аннотация @EntityGraph`
+ ### `Именованные графы @NamedEntityGraph`
+ ### `Свойство attributePaths в @EntityGraph`
+ ### `Конфликт Pageable при получении EAGER связей`

## lesson 62. @Lock & @QueryHints

+ ### `Аннотация @Lock`
+ ### `Демонстрация пессимистических блокировок`
+ ### `Аннотация @QueryHints`

## lesson 63. Projection

+ ### `Class-based Projections`
+ ### `Generic Class-based Projections`
+ ### `Interface-based Projections`
+ ### `SpEL in Projections`

## lesson 64. Custom Repository Implementation

+ ### `Запрос фильтрации через Custom Implementation`
+ ### `Criteria API для запроса фильтрации`
+ ### `Аннотация @EnableJpaRepository`
+ ### `Тестирование запроса фильтрации`

## lesson 65. JPA Auditing
+ ### `Создание AuditingEntity`
+ ### `Аннотация @EnableJpaAuditing`
+ ### `Тестирование @CreatedDate и @LastModifiedDate`
+ ### `Аннотации @CreatedBy и @LastModifiedBy`
+ ### `Создание AuditorAware Bean`
+ ### `Тестирование @CreatedBy и @LastModifiedBy`

## lesson 66. Hibernate Envers
+ ### `Подключение Hibernate Envers`
+ ### `Создание сущности Revision`
+ ### `Аннотация @Audited`
+ ### `Аннотация @EnableEnversRepositories`
+ ### Тестирование Hibernate Envers
+ ### `Класс RevisionRepository`


## lesson 67. Querydsl

+ ### `Подключение Querydsl`
+ ### `Создание QPredicates`
+ ### `Замена Criteria API на Querydsl`
+ ### `Тестирование Querydsl`
+ ### `Класс QuerydslPredicateExecutor`


# 12. JDBC Starter


## lesson 68. JDBC Starter
+ ### `Зависимость spring-boot-starter-jdbc`
+ ### `JdbcTemplateAutoConfiguration`
+ ### `Функционал класса JdbcTemplate`
+ ### `Практика JdbcTemplate`
+ ### `Тестирование функционала`
+ ### `Подключение логов для JdbcTemplate`


## lesson 69. Batch size & Fetch size
+ ### `Batch запросы`
+ ### `Batch запрос через JdbcTemplate`
+ ### `Тестирование Batch запроса через JdbcTemplate`
+ ### `Batch запрос через NamedParameterJdbcTemplate`
+ ### `Установка batch_size в Hibernate`
+ ### `Fetch size`




# 13. Databases in tests

## lesson 70. In-Memory databases. H2
+ ### `Два варианта поднятия тестовой базы данных`
+ ### `Подключение H2 database`
+ ### `Аннотация @Sql`

## lesson 71. Testcontainers
+ ### `testcontainers lib`
+ ### `Подключение testcontainers`
+ ### `Создание IntegrationTestBase`
+ ### `Тестирование testcontainers`
+ ### `Тестовые данные (ids)`



# 14. Database Migrations

## lesson 72. Liquibase. Теория
+ ### `Устройство migration frameworks`
+ ### `Стуктура Liquibase changelog`
+ ### `Changelog master file`

## lesson 73. Liquibase. Практика

+ ### `Подключение зависимости liquibase-core`
+ ### `Класс LiquibaseAutoConfiguration`
+ ### `Создание master changelog`
+ ### `liquibase formatted sql`
+ ### `Тестирование Liquibase`
+ ### `Добавление нового changelog (envers tables)`
+ ### `md5sum`
+ ### `Использование Liquibase в тестах`


# 15. Web Starter

## lesson 74. Web Starter. Введение
+ ### `MVC и классические web-приложения`
+ ### `web-приложение на Spring Boot`
+ ### `Embedded Tomcat`
+ ### `Настройка spring-web приложения`
+ ### `Класс WebMvcAutoConfiguration`


## lesson 75. Dispatcher Servlet
+ ### `Жизненный цикл сервлетов`
+ ### `Псевдокод метода service в DispatcherServlet`
+ ### `Исходный код класса DispatcherServlet`


## lesson 76. @Controller
+ ### `Подключение зависимостей и настройка view resolver`
+ ### `Создание контроллера. @Controller`


## lesson 77. @RequestMapping
+ ### `Основные составляющие HTTP запроса и HTTP ответа`
+ ### `Основные составляющие URL`
+ ### `Аннотации @RequestMapping`


## lesson 78. Parameters, Headers, Cookies
+ ### `Parameters. @RequestParam annotation`
+ ### `Headers. @RequestHeader annotation`
+ ### `Cookies. @CookieValue annotation`
+ ### `Method params naming`
+ ### `DispatcherServlet sources`
+ ### `@PathVariable annotation`


## lesson 79. Model
+ ### `Attributes`
+ ### `Добавление Request атрибутов в Model`
+ ### `Добавление Session атрибутов в Model`
+ ### `DispatcherServlet sources`


## lesson 80. @ModelAttribute
+ ### `Упрощение работы с объектом ModelAndView`
+ ### `Динамическое создание атрибутов`
+ ### `Аннотация @ModelAttribute`
+ ### `HTML Form. LoginController`


## lesson 81. Forward, Include, Redirect
+ ### `3 вида перенаправления запросов`
+ ### `forward in Spring`
+ ### `redirect in Spring`

## lesson 82. CRUD. API Design
+ ### `API design best practices`
+ ### `CRUD. Method findAll`
+ ### `CRUD. Method findById`
+ ### `CRUD. Method create`
+ ### `CRUD. Method update`
+ ### `CRUD. Method delete`


## lesson 83. CRUD. Service Layer
+ ### `UserService. Method findAll`
+ ### `UserService. Method findById`
+ ### `UserService. Method create`
+ ### `@Transactional annotation`
+ ### `UserService. Method update`
+ ### `UserService. Method delete`
+ ### `Test UserService functionality`
+ ### `Tips. Method delete`

## lesson 84. Spring MVC Testing

+ ### `Аннотация @AutoConfigureMockMvc`
+ ### `Test findAll method`
+ ### `Transactions. spring.jpa.open-in-view property`
+ ### `Test create method`
+ ### `Problem with sending dates in params`

## lesson 85. Type Converters
+ ### `1. spring.mvc.format properties`
+ ### `2. Аннотация @DateTimeFormat`
+ ### `3. Интерфейс WebMvcConfigurer`


# 16. Thymeleaf

## lesson 86. Thymeleaf Starter. Введение
+ ### `View Resolvers`
+ ### `Thymeleaf Template Engine Intro`
+ ### `Настройка Thymeleaf в проекте`
+ ### `Использование Thymeleaf`
+ ### `Тестирование функционала`

## lesson 87. CRUD. View Layer. Часть 1
+ ### `Создание users.html для метода findAll`
+ ### `Создание user.html для метода findById`
+ ### `Тестирование функционала`
+ ### `Добавление кнопки для метода delete`

## lesson 88. CRUD. View Layer. Часть 2
+ ### `Создание registration endpoint`
+ ### `Создание registration.html`
+ ### `Тестирование функционала registration`
+ ### `redirect с сохранением введенных параметров`

## lesson 89. Filter Query
+ ### `Add UserFilter - Controller & Service layers`
+ ### `Add UserFilter - users.html`
+ ### `Тестирование функционала`

## lesson 90. Pagination. Best practices
+ ### `HTTP endpoints best practices`
+ ### `2 options of pagination implementation`
+ ### `offset-based pagination`
+ ### `PageableArgumentResolver`
+ ### `Building PageResponse`
+ ### `Тестирование функционала`


# 17. Validation Starter

## lesson 91. Validation Starter. Введение
+ ### `Подключение validation starter`
+ ### `Validation annotations`
+ ### `How to use annotations in practice`
+ ### `@Valid & @Validated`
+ ### `BindingResult object`
+ ### `Show validation errors on the page`
+ ### `Тестирование функционала`

## lesson 92. Custom validator
+ ### `Main parts in JSR 303 annotations`
+ ### `Custom annotation @UserInfo`
+ ### `Тестирование функционала`
+ ### `Configuration properties validation`
+ ### `Validation groups`

## lesson 93. @ControllerAdvice & @ExceptionHandler
+ ### `@ExceptionHandler annotation`
+ ### `Тестирование функционала`
+ ### `@ControllerAdvice annotation`
+ ### `Класс ResponseEntityExceptionHandler`


# 18. REST

## lesson 94. REST. Введение
+ ### `Проблемы Controller API`
+ ### `REST API`
+ ### `REST API Usages`

## lesson 95. REST. Практика
+ ### `@ResponseBody & findAll method`
+ ### `findById method`
+ ### `@RequestBody & create method`
+ ### `update method`
+ ### `delete method`
+ ### `@RestController`
+ ### `@RestControllerAdvice`

## lesson 96. Swagger. API docs
+ ### `Rest clients`
+ ### `Подключение springdoc`
+ ### `Сгенерированная документация для Rest Controllers`
+ ### `Swagger ui`
+ ### `Swagger annotations`

## lesson 97. Upload image
+ ### `Добавление новой колонки image в таблице users`
+ ### `Создание ImageService`
+ ### `upload images from html pages. MultipartFile`
+ ### `Тестирование функционала`

## lesson 98. Get image
+ ### `Реализация функционала на уровне service`
+ ### `Отображение картинки на html странице`
+ ### `Реализация функционала на уровне rest controller`
+ ### `Тестирование функционала`
+ ### `Отображение отсутствующей картинки`
+ ### `Класс ResponseEntity`

# 19. Security Starter

## lesson 99. Security Starter. Введение
+ ### `Понятия Аутентификация и Авторизация`
+ ### `Servlet Filters mechanism`
+ ### `Spring Servlet Filters mechanism`
+ ### `Подключение Spring Security Starter`

## lesson 100. Authentication Architecture
+ ### `Spring Security Model`
+` Spring Security Authentication Logic`
+ ### `Debug Security filters (default behaviour)`

## lesson 101. DaoAuthenticationProvider
+ ### `DaoAuthenticationProvider source code`
+ ### `Add column password into users table`
+ ### `Update entity & enum`
+ ### `Implement UserDetailsService`
+ ### `Тестирование функциональности`

## lesson 102. Form Login
+ ### `Default login page source code`
+ ### `Custom login page`
+ ### `Customise SecurityFilterChain`
+ ### `Тестирование функицонала`
+ ### `Class UsernamePasswordAuthenticationFilter`

## lesson 103. HTTP Basic Authentication

+ ### `HTTP Basic Authentication principle`
+ ### `HTTP Basic encoder & decoder`
+ ### `Customise SecurityFilterChain to support HTTP Basic`
+ ### `BasicAuthenticationFilter source code`

## lesson 104. PasswordEncoder
+ ### `Зачем шифровать пароли`
+ ### `List of password encoders`
+ ### `Implement password encode/decode in the app`
+ ### `Тестирование функционала`

## lesson 105. Logout

+ ### `LogoutFilter source code`
+ ### `Customise logout in SecurityFilterChain`
+ ### `Add button Logout on pages`
+ ### `Тестирование функционала`

## lesson 106. Authorization Architecture
+ ### `AuthorizationFilter source code and logic`
+ ### `AuthorizationFilter implementations`
+ ### `Customise authorizeHttpRequests in SecurityFilterChain`
+ ### `Тестирование функционала`

## lesson 107. Method Security

+ ### `@PreAuthorize annotation`
+ ### `@PostAuthorize annotation`
+ ### `@EnableMethodSecurity annotation`
+ ### `@Secured annotation`
+ ### `Service layer authentication`
+ ### `@PreFilter & @PostFilter annotations`


## lesson 108. Access to authenticated user

+ ### `Get current user via SecurityContextHolder`
+ ### `@CurrentSecutiryContext annotation`
+ ### `@AuthenticationPrincipal annotation`
+ ### `Thymeleaf and Spring Security integration`

## lesson 109. CSRF Filter
+ ### `Cross-Site Request Forgery`
+ ### `How to solve CSRF problem`
+ ### `Synchronizer Token Pattern`
+ ### `When to use CSRF protection`
+ ### `CsrfFilter source code`
+ ### `How to work with CSRF token`
+ ### `Class CsrfRequestDataValueProcessor`
+ ### `Тестирование функционала`

## lesson 110. Security Testing

+ ### `Исправление существующих тестов`
+ ### `spring-security-test dependency`
+ ### `1. Manually define a user in tests`
+ ### `2. @WithMockUser annotation`
+ ### `3. SecurityMockMvcRequestPostProcessor`

## lesson 111. OAuth 2.0. Теория

+ ### `Текущий Authentication функционал в приложении`
+ ### `Что такое OAuth 2`
+ ### `Как внедрить OAuth 2 в приложении`
+ ### `OAuth 2 flow types`
+ ### `OAuth 2 Authorization Code Flow`
+ ### `OAuth 2 Implicit Flow`
+ ### `OpenID Connect (OIDC)`

## lesson 112. OAuth 2.0. Практика

+ ### `Create a new project in GCP`
+ ### `Configure OAuth 2 in the project`
+ ### `Configure Login Page`
+ ### `Тестирование функционала`

## lesson 113. OAuth 2.0. Authentication Principle

+ ### `Add UserInfoEndpoint config in SecurityFilterChain`
+ ### `Create oidcUserService`
+ ### `Тестирование функционала`

## lesson 114. JWT. JSON Web Token


+ ### `How to extract info from JWT`
+ ### `JWT header`
+ ### `JWT payload`
+ ### `JWT signature`
+ ### `Code Book`

## lesson 115. Swagger Authorization
+ ### `3 options to pass authorization in Swagger`
+ ### `springdoc properties to support OAuth 2`
+ ### `@SecurityScheme configuration`
+ ### `Тестирование функционала`



# 20. i18n & l10n


## lesson 116. i18n. MessageSource

+ ### `spring.messages properties`
+ ### `IntelliJ IDEA UTF-8 settings`
+ ### `Creating MessageRestController`
+ ### `Тестирование функционала`

## lesson 117. i18n. Thymeleaf

+ ### `Login page i18n`
+ ### `How to change the language`
+ ### `LocalChangeInterceptor bean`
+ ### `LocaleResolver bean`
+ ### `Тестирование функционала`

# 21. AOP Starter

## lesson 118. AOP Starter. Введение
+ ### `Усложнение кода второстепенной логикой`
+ ### `Crosscutting concerns`
+ ### `AOP terminology`
+ ### `AOP approaches`

## lesson 119. AOP. Pointcut

+ ### `spring-boot-starter-aop dependency`
+ ### `AspectJ annotations`
+ ### `@Pointcut`
+ ### `@within`
+ ### `within`
+ ### `this & target`
+ ### `@annotation`
+ ### `args`
+ ### `@args`
+ ### `bean`
+ ### `execution`

## lesson 120. AOP. @Before Advice
+ ### `@Before annotation`
+ ### `Тестирование функционала`
+ ### `CglibAopProxy`
+ ### `Proxy interceptors`
+ ### `Spring AOP diagram`
+ ### `AopAutoConfiguration`

## lesson 121. AOP. JoinPoint. Params

+ ### `JoinPoint object`
+ ### `Get access to proxy data from advice method params`
+ ### `Тестирование функционала`
+ ### `argNames`

## lesson 122. AOP. @After Advices
+ ### `All types of advice`
+ ### `@AfterReturning annotation`
+ ### `@AfterThrowing annotation`
+ ### `@After annotation`
+ ### `Тестирование функционала`

## lesson 123. AOP. @Around Advice
+ ### `TransactionInterceptor`
+ ### `@Around annotation`
+ ### `Тестирование функционала`

## lesson 124. AOP. Best Practices
+ ### `1. Combine different Pointcut types`
+ ### `2. Move common Pointcuts to separate Aspect`
+ ### `3. Don t use @Around advice everywhere`
+ ### `4. Separate Pointcuts by business logic`
+ ### `Aspects order`


# 22. Заключение

## lesson 125. Custom Spring Boot Starter
+ ### `Create a new Gradle module`
+ ### `Define starter properties`
+ ### `Create Autoconfiguration`
+ ### `File META-INF/spring.factories`
+ ### `Move Aspects from the old to the new module`
+ ### `How to use newly created starter`
+ ### `spring-boot-configuration-processor`
+ ### `Тестирование функционала`

## lesson 126. Заключение. Путь развития

+ ### `Spring Framework Documentation`
+ ### `List of all main Spring Boot Starters`
+ ### `Java Road Map`

