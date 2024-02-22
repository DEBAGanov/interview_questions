Spring-starter


Нажмите ★, если вам нравится проект. Ваш вклад сердечно ♡ приветствуется.

Если вам интересно мое резюме: https://github.com/DEBAGanov


# Содержание

# [1. Intro ](#1.-Intro)


## [lesson 1. Введение ](#lesson-1.-Введение)

1. [Модули Spring (out of the box) ](#Модули-Spring-(out-of-the-box))
2. [Удобство и простота использования ](#Удобство-и-простота-использования)
3. [Микросервисная архитектура ](#Микросервисная-архитектура)
4. [Support & Community ](#Support-&-Community)
5. [Что нужно знать для изучения курса Spring ](#Что-нужно-знать-для-изучения-курса-Spring)


## [lesson 2. Установка программного обеспечения ](#lesson-2.-Установка-программного-обеспечения)


6. [Установка Java 17 ](#Установка-Java-17)
7. [Установка IntelliJ IDEA Ultimate Edition ](#Установка-IntelliJ-IDEA-Ultimate-Edition)
8. [Установка PostgreSQL ](#Установка-PostgreSQL)
9. [Установка Docker ](#Установка-Docker)
10. [Создание нового проекта ](#Создание-нового-проекта)


## [lesson 3. Inversion of Control. Dependency Injection ](#lesson-3.-Inversion-of-Control.-Dependency-Injection)

11. [Object Dependencies ](#Object-Dependencies)
12. [Object Dependencies в коде ](#Object-Dependencies-в-коде)
13. [Inversion of Control & Dependency Injection ](#Inversion-of-Control-&-Dependency-Injection)
14. [Inversion of Control & Dependency Injection в коде ](#Inversion-of-Control-&-Dependency-Injection-в-коде)
15. [3 способа внедрения зависимостей в объекте ](#3-способа-внедрения-зависимостей-в-объекте)

## [lesson 4. IoC Container ](#lesson-4.-IoC-Container)

16. [Spring IoC Container ](#Spring-IoC-Container)
17. [Bean ](#Bean)
18. [Bean Definition ](#Bean-Definition)
19. [POJO ](POJO)
20. [Основные интерфейсы IoC Container ](#Основные-интерфейсы-IoC-Container)
21. [3 способа создания Bean Definitions ](#3-способа-создания-Bean-Definitions)

# [2. XML-based Configuration](#2.-XML-based-Configuration)

## [lesson 5. XML-based Configuration](#lesson-5.-XML-based-Configuration)

22. [BeanFactory и ApplicationContext интерфейсы ](#BeanFactory-и-ApplicationContext-интерфейсы)
23. [ClassPathXmlApplicationContext ](#ClassPathXmlApplicationContext)
24. [XML config ](#XML-config)
25. [Идентификаторы (id) бинов как ключи в IoC Container ](#Идентификаторы-(id)-бинов-как-ключи-в-IoC-Container)
26. [Алиасы бинов (alias) ](#Алиасы-бинов-(alias))

## [lesson 6. Constructor Injection](#lesson-6.-Constructor-Injection)

27. [Внедрение примитивных типов данных ](#Внедрение-примитивных-типов-данных)
28. [Внедрение коллекций list/set ](#Внедрение-коллекций-list/set)
29. [Внедрение ассоциативного массива map ](#Внедрение-ассоциативного-массива-map)
30. [Поле genericArgumentValues в BeanDefinition ](#Поле-genericArgumentValues-в-BeanDefinition)
31. [Поле indexedArgumentValues в BeanDefinition ](#Поле-indexedArgumentValues-в-BeanDefinition)
32. [Указание атрибута type в параметрах конструктора ](#Указание-атрибута-type-в-параметрах-конструктора)
33. [Указание атрибута name в параметрах конструктора ](#Указание-атрибута-name-в-параметрах-конструктора)

## [lesson 7. Factory Method Injection ](#lesson-7.-Factory-Method-Injection)

34. [Внедрение других бинов через ref* ](#Внедрение-других-бинов-через-ref*)
35. [Создание новое бина CompanyRepository ](#Создание-новое-бина-CompanyRepository)
36. [Внедрение зависимостей через factory method ](#Внедрение-зависимостей-через-factory-method)
37. [Атрибут factory-bean (паттерн ServiceLocator) ](#Атрибут-factory-bean-(паттерн-ServiceLocator))

## [lesson 8. Property Injection ](#lesson-8.-Property-Injection)

38. [Использование set* методов в ConnectionPool ](#Использование-set*-методов-в-ConnectionPool)
39. [Поле propertyValues в BeanDefinition ](#Поле-propertyValues-в-BeanDefinition)
40. [Упрощенный жизненный цикл бинов - Bean Lifecycle ](#Упрощенный-жизненный-цикл-бинов---Bean-Lifecycle)
41. [Плюсы и минусы Constructor и Property Injections ](#Плюсы-и-минусы-Constructor-и-Property-Injections)
42. [Циклические зависимости через Property Injection ](#Циклические-зависимости-через-Property-Injection)

## [lesson 9. Bean Scopes ](#lesson-9.-Bean-Scopes)

43. [Common Bean Scopes ](#Common-Bean-Scopes)
44. [Custom Bean Scopes ](#Custom-Bean-Scopes)
45. [Web Bean Scopes ](#Web-Bean-Scopes)
46. [Prototype Bean Scope ](#Prototype-Bean-Scope)

## [lesson 10. Lifecycle Callbacks ](#lesson-9.-Bean-Scopes)

47. [Измененный Bean Lifecycle ](#Измененный-Bean-Lifecycle)
48. [Initialization callbacks ](#Initialization-callbacks)
49. [Destruction callbacks ](#Destruction-callbacks)

## [lesson 11. Injection from Properties Files ](#lesson-11.-Injection-from-Properties-Files)

50. [Зачем использовать properties files ](#Зачем-использовать-properties-files)
51. [Создание файла application.properties ](#Создание-файла-application.properties)
52. [PropertySourcesPlaceholderConfigurer bean ](#PropertySourcesPlaceholderConfigurer-bean)
53. [Expression Language (EL) ](#Expression-Language-(EL))
54. [Spring Expression Language (SpEL) ](#Spring-Expression-Language-(SpEL))
55. [SpEL документация ](#SpEL-документация)
56. [System properties ](#System-properties)

## [lesson 12. BeanFactoryPostProcessor (BFPP) ](#lesson-12.-BeanFactoryPostProcessor-(BFPP))

57. [Интерфейс BeanFactoryPostProcessor ](#Интерфейс-BeanFactoryPostProcessor)
58. [Как работает PropertySourcesPlaceholderConfigurer ](#Как-работает-PropertySourcesPlaceholderConfigurer)
59. [Измененный Bean Lifecycle ](#Измененный-Bean-Lifecycle)
60. [Метод isAssignableFrom ](#Метод-isAssignableFrom)

## [lesson 13. Custom BeanFactoryPostProcessor ](#lesson-13.-Custom-BeanFactoryPostProcessor)

61. [Создание собственных BeanFactoryPostProcessor ](#Создание-собственных-BeanFactoryPostProcessor)
62. [Интерфейс Ordered ](#Интерфейс-Ordered)
63. [Интерфейс PriorityOrdered ](#Интерфейс-PriorityOrdered)


# 3. [Annotation-based Configuration ](#Annotation-based-Configuration)

## [lesson 14. Annotation-based Configuration ](#lesson-14.-Annotation-based-Configuration)

64. [Подключение зависимости jakarta annotation api ](#Подключение-зависимости-jakarta-annotation-api)
65. [Аннотации @PostConstruct и @PreDestroy ](#Аннотации-@PostConstruct-и-@PreDestroy)
66. [Класс CommonAnnotationBeanPostProcessor ](#Класс-CommonAnnotationBeanPostProcessor)
67. [context:annotation-config xml element ](#context:-annotation-config-xml-element)




## [lesson 15. BeanPostProcessor (BPP) ](#lesson-15.-BeanPostProcessor-(BPP))

68. [Интерфейс BeanPostProcessor ](#Интерфейс-BeanPostProcessor)
69. [Bean Lifecycle (final version) ](#Bean-Lifecycle-(final-version))
70. [Интерфейс Aware ](#Интерфейс-Aware)
71. [Класс ApplicationContextAwareProcessor ](#Класс-ApplicationContextAwareProcessor)


## [lesson 16. Custom BeanPostProcessor. Часть 1 ](#lesson-16.-Custom-BeanPostProcessor.-Часть-1)

72. [Создание своей аннотации @InjectBean ](#Создание-своей-аннотации-@InjectBean)
73. [Создание InjectBeanPostProcessor ](#Создание-InjectBeanPostProcessor)
74. [Утилитный класс ReflectionUtils ](#Утилитный-класс-ReflectionUtils)
75. [Тестирование InjectBeanPostProcessor ](#Тестирование-InjectBeanPostProcessor)

## [lesson 17. Custom BeanPostProcessor. Часть 2 ](#lesson-17.-Custom-BeanPostProcessor.-Часть-2)
76. [Создание аннотации @Transaction ](#Создание-аннотации-@Transaction)
77. [Создание CrudRepository ](#Создание-CrudRepository)
78. [Создание TransactionBeanPostProcessor ](#Создание-TransactionBeanPostProcessor)
79. [Тестирование TransactionBeanPostProcessor ](#Тестирование-TransactionBeanPostProcessor)
80. [Корректируем TransactionBeanPostProcessor ](#Корректируем-TransactionBeanPostProcessor)
81. [Создание AuditingBeanPostProcessor ](#Создание-AuditingBeanPostProcessor)


## [lesson 18. @Autowired & @Value ](#lesson-18.-@Autowired-&-@Value)

82. [Аннотация @Autowired ](#Аннотация-@Autowired)
83. [Аннотация @Resource ](#Аннотация-@Resource)
84. [Решение конлифкта бинов. @Qualifier ](#Решение-конлифкта-бинов.-@Qualifier)
85. [Collection injection ](#Collection-injection)
86. [Properties injection. @Value ](#Properties-injection.-@Value)


## [lesson 19. Classpath Scanning ](#lesson-19.-Classpath-Scanning)
87. [context:component-scan. Аннотации @Component ](#context:-component-scan.-Аннотации-@Component)
88. [Замена бинов из xml на @Component ](#Замена-бинов-из-xml-на-@Component)
89. [Тестирование функционала ](#Тестирование-функционала)

## [lesson 20. Bean Definition Readers ](#lesson-20.-Bean-Definition-Readers)

90. [Component Scan classes ](#Component-Scan-classes)
91. [Bean Definition Readers ](#Bean-Definition-Readers)
92. [Класс ComponentScanBeanDefinitionParser ](#Класс-ComponentScanBeanDefinitionParser)
93. [Класс AnnotatedBeanDefinitionReader ](#Класс-AnnotatedBeanDefinitionReader)

## [lesson 21. Type Filters ](#lesson-21.-Type-Filters)

94. [Атрибут annotation-config ](#Атрибут-annotation-config)
95. [Атрибут name-generator ](#Атрибут-name-generator)
96. [Атрибут resource-pattern ](#Атрибут-resource-pattern)
97. [Атрибут scoped-proxy ](#Атрибут-scoped-proxy)
98. [Атрибут scope-resolver ](#Атрибут-scope-resolver)
99. [Атрибут use-default-filters ](#Атрибут-use-default-filters)
100. [ 5 type filters ](#-5-type-filters)
101. [ Custom filters ](#-Custom-filters)


## [lesson 22. @Scope ](#lesson-22.-@Scope)
102. [Атрибут scope-resolver ](#Атрибут-scope-resolver)
103. [Класс AnnotationScopeMetadataResolver ](#Класс-AnnotationScopeMetadataResolver)
104. [Аннотация @Scope ](#Аннотация-@Scope)


## [lesson 23. JSR 250, JSR 330 ](#lesson-23.-JSR-250,-JSR-330)

105. [Аббревиатура JSR ](#Аббревиатура-JSR)
106. [JSR 250 ](#JSR-250)
107. [JSR 330 ](#JSR-330)
108. [Класс Jsr330ScopeMetadataResolver ](#Класс-Jsr330ScopeMetadataResolver)



# 4. [Java-based Configuration ](#Java-based-Configuration)

## [lesson 24. Java-based Configuration ](#lesson-24.-Java-based-Configuration)
109. [Класс ConfigurationClassBeanDefinitionReader ](#Класс-ConfigurationClassBeanDefinitionReader)
110. [Создание ApplicationConfiguration. @Configuration ](#Создание-ApplicationConfiguration.-@Configuration)
111. [Аннотация @PropertySource ](#Аннотация-@PropertySource)
112. [Аннотация @ComponentScan ](#Аннотация-@ComponentScan)
113. [Класс AnnotationConfigApplicationContext ](#Класс-AnnotationConfigApplicationContext)


## [lesson 25. @Import & @ImportResource ](#lesson-25.-@Import-&-@ImportResource)
114. [Класс AnnotationConfigApplicationContext ](#Класс-AnnotationConfigApplicationContext)
115. [Аннотация @ImportResource ](#Аннотация-@ImportResource)
116. [Аннотация @Import ](#Аннотация-@Import)

## [lesson 26. @Bean. Часть 1 ](#lesson-26.-@Bean.-Часть-1)

117. [Аннотация @Bean ](#Аннотация-@Bean)
118. [Тестирование Java конфигурации ](#Тестирование-Java-конфигурации)
119. [Свойства аннотации @Bean ](#Свойства-аннотации-@Bean)
120. [Аннотация @Scope с @Bean ](#Аннотация-@Scope-с-@Bean)
121. [Внедрение зависимостей с @Bean ](#Внедрение-зависимостей-с-@Bean)
122. [Конфликт имен @Bean и @Component ](#Конфликт-имен-@Bean-и-@Component)

## [lesson 27. @Bean. Часть 2 ](#lesson-27.-@Bean.-Часть-2)

123. [3-ий вариант внедрения зависимостей в @Bean ](#3-ий-вариант-внедрения-зависимостей-в-@Bean)
124. [Cglib proxy в @Configuration ](#Cglib-proxy-в-@Configuration)
125. [Свойство proxyBeanMethods в @Configuration ](#Свойство-proxyBeanMethods-в-@Configuration)
126. [@Bean создаются через паттерн Service Locator ](#@Bean-создаются-через-паттерн-Service-Locator)

## [lesson 28. Profiles ](#lesson-28.-Profiles)
127. [Environment Bean ](#Environment-Bean)
128. [Аннотация @Profile ](#Аннотация-@Profile)
129. [Активация profiles через properties ](#Активация-profiles-через-properties)
130. [Активация profiles через ApplicationContext ](#Активация-profiles-через-ApplicationContext)



# 5. [Event Listeners ](#-Event-Listeners)


## [lesson 29. Event Listeners. Часть 1 ](#lesson-29.-Event-Listeners.-Часть-1)
131. [Шаблон проектирования Listener ](#Шаблон-проектирования-Listener)
132. [Создание события (Event) ](#Создание-события-(Event))
133. [Создание слушателя событий (Listener). @EventListener ](#Создание-слушателя-событий-(Listener).-@EventListener)
134. [Реализация логики для отправки события ](#Реализация-логики-для-отправки-события)

## [lesson 30. Event Listeners. Часть 2 ](#lesson-30.-Event-Listeners.-Часть-2)

135. [Bean ApplicationEventPublisher ](#Bean-ApplicationEventPublisher)
136. [Тестирование слушателей событий ](#Тестирование-слушателей-событий)
137. [Listeners order ](#Listeners-order)
138. [Listeners conditions ](#Listeners-conditions)


# 6. [Spring Boot ](#Spring-Boot)


## [lesson 31. Spring Boot. Введение ](#lesson-31.-Spring-Boot.-Введение)

139. [Spring modules ](#Spring-modules)
140. [Spring Data Configuration ](#Spring-Data-Configuration)
141. [Modules Auto Configuration ](#Modules-Auto-Configuration)
142. [Conditions ](#Conditions)
143. [Spring Boot Starters ](#Spring-Boot-Starters)
144. [Dependency Management ](#Dependency-Management)
145. [How to build Spring Boot Application ](#How-to-build-Spring-Boot-Application)

## [lesson 32. @Conditional ](#lesson-32.-@Conditional)

146. [Аннотация @Conditional ](#Аннотация-@Conditional)
147. [Класс Condition ](#Класс-Condition)
148. [Custom JpaCondition ](#Custom-JpaCondition)
149. [Тестирование JpaCondition ](#Тестирование-JpaCondition)
150. [Аннотация @Profile ](#Аннотация-@Profile)
151. [Другие @Condition аннотации ](#Другие-@Condition-аннотации)


## [lesson 33. Spring Boot. Настройка проекта ](lesson-33.-Spring-Boot.-Настройка-проекта)

152. [Spring Boot Gradle Plugin ](#Spring-Boot-Gradle-Plugin)
153. [Spring Dependency Management Plugin ](#Spring-Dependency-Management-Plugin)
154. [spring-boot-starter ](#spring-boot-starter)
155. [Run Spring Boot Application ](#Run-Spring-Boot-Application)
156. [Autogenerated Spring Boot Project ](#Autogenerated-Spring-Boot-Project)
157. [Maven spring-boot-starter-parent pom ](#Maven-spring-boot-starter-parent-pom)

## [lesson 34. @SpringBootApplication ](#lesson-34.-@SpringBootApplication)

158. [Структура Spring Boot приложения ](#Структура-Spring-Boot-приложения)
159. [Что делает метод SpringApplication.run ](#Что-делает-метод-SpringApplication.run)
160. [Аннотация @SpringBootApplication ](#Аннотация-@SpringBootApplication)
161. [Аннотация @SpringBootConfiguration ](#Аннотация-@SpringBootConfiguration)
162. [Аннотация @ComponentScan ](#Аннотация-@ComponentScan)
163. [Аннотация @PropertySource ](#Аннотация-@PropertySource)
164. [Аннотация @EnableAutoConfiguration ](#Аннотация-@EnableAutoConfiguration)


## [lesson 35. Lombok ](#lesson-35.-Lombok)

165. [Подключение Lombok ](#Подключение-Lombok)
166. [Gradle Lombok Plugin ](#Gradle-Lombok-Plugin)
167. [IntelliJ IDEA Lombok Plugin ](#IntelliJ-IDEA-Lombok-Plugin)
168. [Аннотации Lombok ](#Аннотации-Lombok)
169. [Файл lombok.config ](#Файл-lombok.config)

## [lesson 36. Properties ](#lesson-36.-Properties)

170. [Файл spring.properties ](#Файл-spring.properties)
171. [Externalized Configuration ](#Externalized-Configuration)
172. [Profile-specific properties ](#Profile-specific-properties)
173. [Spring program arguments & VM options ](#Spring-program-arguments-&-VM-options)
174. [Property Placeholders & Default values ](#Property-Placeholders-&-Default-values)
175. [spring.config.location ](#spring.config.location)

## [lesson 37. Yaml format ](#lesson-37.-Yaml-format)

176. [YAML - Yet Another Markup Language ](#YAML---Yet-Another-Markup-Language)
177. [Класс YamlPropertiesFactoryBean ](#Класс-YamlPropertiesFactoryBean)
178. [Приоритет properties vs yaml ](#Приоритет-properties-vs-yaml)
179. [Переписывание application.properties на yaml ](#Переписывание-application.properties-на-yaml)


## [lesson 38. @ConfigurationProperties ](#lesson-38.-@ConfigurationProperties)

180. [Класс JpaProperties ](#Класс-JpaProperties)
181. [Класс DatabaseProperties ](#Класс-DatabaseProperties)
182. [Аннотация @ConfigurationProperties ](#Аннотация-@ConfigurationProperties)
183. [Аннотация @ConfigurationPropertiesScan ](#Аннотация-@ConfigurationPropertiesScan)
184. [Immutable DatabaseProperties ](#Immutable-DatabaseProperties)
185. [DatabaseProperties as record ](#DatabaseProperties-as-record)
186. [Property key names ](#Property-key-names)



# [7. Logging Starter ](#7.-Logging-Starter)


## [lesson 39. Logging Starter ](#lesson-39.-Logging-Starter)

190. [Application as a Black Box ](#Application-as-a-Black-Box)
191. [Logging libraries ](#Logging-libraries)
192. [Log Levels ](#Log-Levels)
193. [spring-boot-starter-logging dependency ](#spring-boot-starter-logging-dependency)
194. [Аннотация @Slf4j ](#Аннотация-@Slf4j)
195. [Delombok annotations ](#Delombok-annotations)
196. [Формат логов по умолчанию ](#Формат-логов-по-умолчанию)
197. [logging.* properties ](#logging.*-properties)

## [lesson 40. Logback Configuration ](#lesson-40.-Logback-Configuration)

198. [Logback default xml configs ](#Logback-default-xml-configs)
199. [File Output ](#File-Output)
200. [Custom log configuration ](#Custom-log-configuration)


# [8. Test Starter ](#8.-Test-Starter)

## [lesson 41. Test Starter ](#lesson-41.-Test-Starter)

201. [Подключение spring-boot-starter-test ](#Подключение-spring-boot-starter-test)
202. [Транзитивные зависимости spring-boot-starter-test ](#Транзитивные-зависимости-spring-boot-starter-test)
203. [Зависимость spring-test ](#Зависимость-spring-test)
204. [Зависимость spring-boot-test ](#Зависимость-spring-boot-test)
205. [Зависимость spring-boot-test-autoconfigure ](#Зависимость-spring-boot-test-autoconfigure)
206. [Пример написания Unit тестов ](#Пример-написания-Unit-тестов)
207. [Java Gradle Plugin tasks relationship ](#Java-Gradle-Plugin-tasks-relationship)

## [lesson 42. Integration Testing. Part 1 ](#lesson-42.-Integration-Testing.-Part-1)

208. [Основные цели Spring Integration Testing ](#Основные-цели-Spring-Integration-Testing)
209. [Жизненный цикл тестов ](#Жизненный-цикл-тестов)
210. [JUnit 5 Extension Model ](#JUnit-5-Extension-Model)
211. [TestContext Framework ](#TestContext-Framework)
212. [SpringExtension source code ](#SpringExtension-source-code)

## [lesson 43. Integration Testing. Part 2 ](#lesson-43.-Integration-Testing.-Part-2)

213. [Создание CompanyServiceIT ](#Создание-CompanyServiceIT)
214. [SpringExtension via @ExtendWith ](#SpringExtension-via-@ExtendWith)
215. [Аннотация @ContextConfiguration ](#Аннотация-@ContextConfiguration)
216. [Аннотация @TestPropertySource ](#Аннотация-@TestPropertySource)
217. [Класс ApplicationContextInitializer ](#Класс-ApplicationContextInitializer)
218. [Аннотация @SpringBootTest ](#Аннотация-@SpringBootTest)
219. [Написание первого интеграционного теста ](#Написание-первого-интеграционного-теста)
220. [Класс DependencyInjectionTestExecutionListener ](#Класс-DependencyInjectionTestExecutionListener)

## [lesson 44. Integration Testing. Part 3 ](#lesson-44.-Integration-Testing.-Part-3)

221. [Аннотация @ActiveProfiles ](#Аннотация-@ActiveProfiles)
222. [Custom Test Annotations ](#Custom-Test-Annotations)
223. [Аннотация @TestConstructor ](#Аннотация-@TestConstructor)
224. [Замена @TestConstructor на spring.properties ](#Замена-@TestConstructor-на-spring.properties)

## [lesson 45. Context Caching ](#lesson-45.-Context-Caching)

225. [Создание нескольких ApplicationContext в тестах ](#Создание-нескольких-ApplicationContext-в-тестах)
226. [Аннотации @MockBean и @SpyBean ](#Аннотации-@MockBean-и-@SpyBean)
227. [Класс MockitoTestExecutionListener ](#Класс-MockitoTestExecutionListener)
228. [Аннотация @TestConfiguration ](#Аннотация-@TestConfiguration)
229. [Аннотация @DirtiesContext ](#Аннотация-@DirtiesContext)


# [9. Data JPA Starter ](#9.-Data-JPA-Starter)

## [lesson 46. Data JPA Starter. Введение ](#lesson-46.-Data-JPA-Starter.-Введение)
230. [Чего не хватало в Hibernate ](#Чего-не-хватало-в-Hibernate)
231. [Установка PostgreSQL ](#Установка-PostgreSQL)
232. [Установка Docker ](#Установка-Docker)
233. [Postgres Docker Image ](#Postgres-Docker-Image)
234. [Подключение к postgres из IntelliJ IDEA ](#Подключение-к-postgres-из-IntelliJ-IDEA)

## [lesson 47. Data JPA Starter. Подключение ](#lesson-47.-Data-JPA-Starter.-Подключение)

235. [Подключение spring-boot-starter-data-jpa ](#Подключение-spring-boot-starter-data-jpa)
236. [Зависимости spring-boot-starter-data-jpa ](#Зависимости-spring-boot-starter-data-jpa)
237. [Класс HibernateJpaAutoConfiguration ](#Класс-HibernateJpaAutoConfiguration)
238. [Настройка spring.datasource и spring.jpa properties ](#Настройка-spring.datasource-и-spring.jpa-properties)
239. [Тестирование приложения ](#Тестирование-приложения)

## [lesson 48. Hibernate Entities ](#lesson-48.-Hibernate-Entities)

240. [UML диаграмма выполненных sql скриптов ](#UML-диаграмма-выполненных-sql-скриптов)
241. [Создание сущности Company ](#Создание-сущности-Company)
242. [Создание коллекции locales (ElementCollection) ](#Создание-коллекции-locales-(ElementCollection))
243. [Создание сущности User ](#Создание-сущности-User)
244. [Создание сущности Payment ](#Создание-сущности-Payment)
245. [Создание сущности Chat ](#Создание-сущности-Chat)
246. [Создание сущности UserChat ](#Создание-сущности-UserChat)
247. [Проверка маппинга сущностей через hbm2ddl.auto ](#Проверка-маппинга-сущностей-через-hbm2ddl.auto)
248. [Аннотация @EntityScan ](#Аннотация-@EntityScan)


# [10. Data JPA Transactions ](#10.-Data-JPA-Transactions)

## [lesson 49. @Transactional. TestContext ](#lesson-49.-@Transactional.-TestContext)
249. [Общая структура работы с TransactionManager ](#Общая-структура-работы-с-TransactionManager)
250. [Создание CompanyRepository IT ](#Создание-CompanyRepository-IT)
251. [Аннотации @Transactional из Jakarta EE и Spring ](#Аннотации-@Transactional-из-Jakarta-EE-и-Spring)
252. [Класс TransactionalTestExecutionListener ](#Класс-TransactionalTestExecutionListener)
253. [Аннотации @Commit и @Rollback ](#Аннотации-@Commit-и-@Rollback)

## [lesson 50. TransactionAutoConfiguration ](#lesson-49.-@Transactional.-TestContext)
254. [Класс TransactionAutoConfigurationКак происходит обработка транзакций в proxy ](#Класс-TransactionAutoConfigurationКак-происходит-обработка-транзакций-в-proxy)
255. [Аннотация @Transactional и Cglib proxy ](#Аннотация-@Transactional-и-Cglib-proxy)
256. [Как работает Cglib proxy с TransactionManager ](#Как-работает-Cglib-proxy-с-TransactionManager)
257. [Как подключить механизм транзакций внутри объекта (не proxy) ](#Как-подключить-механизм-транзакций-внутри-объекта-(не-proxy))
258. [Механизм транзакций между несколькими Cglib proxy ](#Механизм-транзакций-между-несколькими-Cglib-proxy)

## [lesson 51. @Transactional Settings ](#lesson-51.-@Transactional-Settings)
259. [Свойства @Transactional. transactionManager ](#Свойства-@Transactional.-transactionManager)
260. [Transaction propagation ](#Transaction-propagation)
261. [Transaction propagation резюме ](#Transaction-propagation-резюме)
262. [Transaction isolation ](#Transaction-isolation)
263. [Transaction timeout ](#Transaction-timeout)
264. [ReadOnly transaction ](#ReadOnly-transaction)
265. [Transaction rollbackFor & rollbackForClassName ](#Transaction-rollbackFor-&-rollbackForClassName)
266. [Transaction noRollbackFor & noRollbackForClassName ](#Transaction-noRollbackFor-&-noRollbackForClassName)


## [lesson 52. Manual Transactions ](#lesson-52.-Manual-Transactions)
267. [Свойства объекта TransactionTemplate ](#Свойства-объекта-TransactionTemplate)
268. [Функционал TransactionTemplate ](#Функционал-TransactionTemplate)
269. [Обработка checked exceptions ](#Обработка-checked-exceptions)
270. [Взаимодействие TransactionTemplate с другими Proxy ](#Взаимодействие-TransactionTemplate-с-другими-Proxy)
271. [Вынесение @Transactional в @IT ](#Вынесение-@Transactional-в-@IT)


# [11. Data JPA Repositories ](#11.-Data-JPA-Repositories)

## [lesson 53. Repository ](#lesson-53.-Repository)
272. [Интерфейс Repository ](#Интерфейс-Repository)
273. [Написание теста на удаление Company ](#Написание-теста-на-удаление-Company)
274. [Класс JpaRepositoryAutoConfiguration ](#Класс-JpaRepositoryAutoConfiguration)

## [lesson 54. RepositoryQuery ](#lesson-54.-RepositoryQuery)
275. [Создание Proxy на классы Repository ](#Создание-Proxy-на-классы-Repository)
276. [Класс QueryExecutorMethodInterceptor ](#Класс-QueryExecutorMethodInterceptor)
277. [Класс RepositoryQuery ](#Класс-RepositoryQuery)
278. [Наследники Repository ](#Наследники-Repository)

## [lesson 55. PartTreeJpaQuery ](#lesson-55.-PartTreeJpaQuery)
279. [Класс PartTreeJpaQuery ](#Класс-PartTreeJpaQuery)
280. [Примеры написания запросов ](#Примеры-написания-запросов)
281. [Тестирование запросов ](#Тестирование-запросов)
282. [Весь список ключевых слов PartTreeJpaQuery ](#Весь-список-ключевых-слов-PartTreeJpaQuery)


## [lesson 56. NamedQuery ](#lesson-56.-NamedQuery)

283. [Недостатки PartTreeJpaQuery ](#Недостатки-PartTreeJpaQuery)
284. [Класс NamedQuery ](#Класс-NamedQuery)
285. [Аннотация @NamedQuery ](#Аннотация-@NamedQuery)
286. [Тестирование NamedQuery ](#Тестирование-NamedQuery)
287. [Аннотация @Param ](#Аннотация-@Param)

## [lesson 57. @Query ](#lesson-57.-@Query)
288. [StoredProcedureJpaQuery ](#StoredProcedureJpaQuery)
289. [Аннотация @Query ](#Аннотация-@Query)
290. [Демонстрация работы @Query ](#Демонстрация-работы-@Query)
291. [Усовершенствованный оператор LIKE ](#Усовершенствованный-оператор-LIKE)
292. [Native Query ](#Native-Query)

## [lesson 58. @Modifying ](#lesson-58.-@Modifying)

293. [Запрос на обновление через @Query ](#Запрос-на-обновление-через-@Query)
294. [Аннотация @Modifying ](#Аннотация-@Modifying)
295. [Hibernate PersistenceContext ](#Hibernate-PersistenceContext)
296. [Свойства clearAutomatically и flushAutomatically ](#Свойства-clearAutomatically-и-flushAutomatically)
297. [clearAutomatically и LazyInitializationException ](#clearAutomatically-и-LazyInitializationException)

## [lesson 59. Special parameters ](#lesson-59.-Special-parameters)

298. [Top & First](#Top-&-First)
299. [TopN & FirstN](#TopN-&-FirstN)
300. [Класс Sort](#Класс-Sort)
301. [Класс Pageable ](#Класс-Pageable)

## [lesson 60. Page & Slice ](#lesson-60.-Page-&-Slice)
302. [Spring классы Streamable, Slice, Page ](#Spring-классы-Streamable,-Slice,-Page)
303. [Демонстрация работы Slice объекта ](#Демонстрация-работы-Slice-объекта)
304. [Почему Slice объекта недостаточно ](#Почему-Slice-объекта-недостаточно)
305. [Демонстрация работы Page объекта ](#Демонстрация-работы-Page-объекта)

## [lesson 61. @EntityGraph ](#lesson-61.-@EntityGraph)

306. [Аннотация @EntityGraph ](#Аннотация-@EntityGraph)
307. [Именованные графы @NamedEntityGraph ](#Именованные-графы-@NamedEntityGraph)
308. [Свойство attributePaths в @EntityGraph ](#Свойство-attributePaths-в-@EntityGraph)
309. [Конфликт Pageable при получении EAGER связей ](#Конфликт-Pageable-при-получении-EAGER-связей)

## [lesson 62. @Lock & @QueryHints ](#lesson-62.-@Lock-&-@QueryHints)

310. [Аннотация @Lock ](#Аннотация-@Lock)
311. [Демонстрация пессимистических блокировок ](#Демонстрация-пессимистических-блокировок)
312. [Аннотация @QueryHints ](#Аннотация-@QueryHints)

## [lesson 63. Projection ](#lesson-63.-Projection)

313. [Class-based Projections ](#Class-based-Projections)
314. [Generic Class-based Projections ](#Generic-Class-based-Projections)
315. [Interface-based Projections ](#Interface-based-Projections)
316. [SpEL in Projections ](#SpEL-in-Projections)

## [lesson 64. Custom Repository Implementation ](#lesson-64.-Custom-Repository-Implementation)

317. [Запрос фильтрации через Custom Implementation ](#Запрос-фильтрации-через-Custom-Implementation)
318. [Criteria API для запроса фильтрации ](#Criteria-API-для-запроса-фильтрации)
319. [Аннотация @EnableJpaRepository ](#Аннотация-@EnableJpaRepository)
320. [Тестирование запроса фильтрации ](#Тестирование-запроса-фильтрации)

## [lesson 65. JPA Auditing ](#lesson-65.-JPA-Auditing)
321. [Создание AuditingEntity ](#Создание-AuditingEntity)
322. [Аннотация @EnableJpaAuditing ](#Аннотация-@EnableJpaAuditing)
323. [Тестирование @CreatedDate и @LastModifiedDate ](#Тестирование-@CreatedDate-и-@LastModifiedDate)
324. [Аннотации @CreatedBy и @LastModifiedBy ](#Аннотации-@CreatedBy-и-@LastModifiedBy)
325. [Создание AuditorAware Bean ](#Создание-AuditorAware-Bean)
326. [Тестирование @CreatedBy и @LastModifiedBy ](#Тестирование-@CreatedBy-и-@LastModifiedBy)

## [lesson 66. Hibernate Envers ](#lesson-66.-Hibernate-Envers)
327. [Подключение Hibernate Envers ](#Подключение-Hibernate-Envers)
328. [Создание сущности Revision ](#Создание-сущности-Revision)
329. [Аннотация @Audited ](#Аннотация-@Audited)
330. [Аннотация @EnableEnversRepositories ](#Аннотация-@EnableEnversRepositories)
331. [Тестирование Hibernate Envers ](#Тестирование-Hibernate-Envers)
332. [Класс RevisionRepository ](#Класс-RevisionRepository)


## [lesson 67. Querydsl ](#lesson-67.-Querydsl)

333. [Подключение Querydsl ](#Подключение-Querydsl)
334. [Создание QPredicates ](#Создание-QPredicates)
335. [Замена Criteria API на Querydsl ](#Замена-Criteria-API-на-Querydsl)
336. [Тестирование Querydsl ](#Тестирование-Querydsl)
337. [Класс QuerydslPredicateExecutor ](#Класс-QuerydslPredicateExecutor)


# [12. JDBC Starter ](#12.-JDBC-Starter)


## [lesson 68. JDBC Starter ](#lesson-68.-JDBC-Starter)
338. [Зависимость spring-boot-starter-jdbc ](#Зависимость-spring-boot-starter-jdbc)
339. [JdbcTemplateAutoConfiguration ](#JdbcTemplateAutoConfiguration)
340. [Функционал класса JdbcTemplate ](#Функционал-класса-JdbcTemplate)
341. [Практика JdbcTemplate ](#Практика-JdbcTemplate)
342. [Тестирование функционала ](#Тестирование-функционала)
343. [Подключение логов для JdbcTemplate ](#Подключение-логов-для-JdbcTemplate)


## [lesson 69. Batch size & Fetch size ](#lesson-69.-Batch-size-&-Fetch-size)
344. [Batch запросы ](#Batch-запросы)
345. [Batch запрос через JdbcTemplate ](#Batch-запрос-через-JdbcTemplate)
346. [Тестирование Batch запроса через JdbcTemplate ](#Тестирование-Batch-запроса-через-JdbcTemplate)
347. [Batch запрос через NamedParameterJdbcTemplate ](#Batch-запрос-через-NamedParameterJdbcTemplate)
348. [Установка batch_size в Hibernate ](#Установка-batch_size-в-Hibernate)
349. [Fetch size ](#Fetch-size)




# [13. Databases in tests ](#13.-Databases-in-tests)

## [lesson 70. In-Memory databases. H2 ](#lesson-70.-In-Memory-databases.-H2)
350. [Два варианта поднятия тестовой базы данных ](#Два-варианта-поднятия-тестовой-базы-данных)
351. [Подключение H2 database ](#Подключение-H2-database)
352. [Аннотация @Sql ](#Аннотация-@Sql)

## [lesson 71. Testcontainers ](#lesson-71.-Testcontainers)
353. [testcontainers lib ](#testcontainers-lib)
354. [Подключение testcontainers ](#Подключение-testcontainers)
355. [Создание IntegrationTestBase ](#Создание-IntegrationTestBase)
356. [Тестирование testcontainers ](#Тестирование-testcontainers)
357. [Тестовые данные (ids) ](#Тестовые-данные-(ids))



# [14. Database Migrations ](#14.-Database-Migrations)

## [lesson 72. Liquibase. Теория ](#lesson-72.-Liquibase.-Теория)
358. [Устройство migration frameworks ](#Устройство-migration-frameworks)
359. [Стуктура Liquibase changelog ](#Стуктура-Liquibase-changelog)
360. [Changelog master file ](#Changelog-master-file)

## [lesson 73. Liquibase. Практика ](#lesson-73.-Liquibase.-Практика)

361. [Подключение зависимости liquibase-core ](#Подключение-зависимости-liquibase-core)
362. [Класс LiquibaseAutoConfiguration ](#Класс-LiquibaseAutoConfiguration)
363. [Создание master changelog ](#Создание-master-changelog)
364. [liquibase formatted sql ](#liquibase-formatted-sql)
365. [Тестирование Liquibase ](#Тестирование-Liquibase)
366. [Добавление нового changelog (envers tables) ](#Добавление-нового-changelog-(envers-tables))
367. [md5sum ](#md5sum)
368. [Использование Liquibase в тестах ](#Использование-Liquibase-в-тестах)


# [15. Web Starter ](#15.-Web-Starter)

## [lesson 74. Web Starter. Введение ](#lesson-74.-Web-Starter.-Введение)
369. [MVC и классические web-приложения ](#MVC-и-классические-web-приложения)
370. [web-приложение на Spring Boot ](#web-приложение-на-Spring-Boot)
371. [Embedded Tomcat ](#Embedded-Tomcat)
372. [Настройка spring-web приложения ](#Настройка-spring-web-приложения)
373. [Класс WebMvcAutoConfiguration ](#Класс-WebMvcAutoConfiguration)


## [lesson 75. Dispatcher Servlet ](#lesson-75.-Dispatcher-Servlet)
374. [Жизненный цикл сервлетов ](#Жизненный-цикл-сервлетов)
375. [Псевдокод метода service в DispatcherServlet ](#Псевдокод-метода-service-в-DispatcherServlet)
376. [Исходный код класса DispatcherServlet ](#Исходный-код-класса-DispatcherServlet)


## [lesson 76. @Controller ](#lesson-76.-@Controller)
377. [Подключение зависимостей и настройка view resolver ](#Подключение-зависимостей-и-настройка-view-resolver)
378. [Создание контроллера. @Controller ](#Создание-контроллера.-@Controller)


## [lesson 77. @RequestMapping ](#lesson-77.-@RequestMapping)
379. [Основные составляющие HTTP запроса и HTTP ответа ](#Основные-составляющие-HTTP-запроса-и-HTTP-ответа)
380. [Основные составляющие URL ](#Основные-составляющие-URL)
381. [Аннотации @RequestMapping ](#Аннотации-@RequestMapping)


## [lesson 78. Parameters, Headers, Cookies ](#lesson-78.-Parameters,-Headers,-Cookies)
382. [Parameters. @RequestParam annotation ](#Parameters.-@RequestParam-annotation)
383. [Headers. @RequestHeader annotation ](#Headers.-@RequestHeader-annotation)
384. [Cookies. @CookieValue annotation ](#Cookies.-@CookieValue-annotation)
385. [Method params naming ](#Method-params-naming)
386. [DispatcherServlet sources ](#DispatcherServlet-sources)
387. [@PathVariable annotation ](#@PathVariable-annotation)


## [lesson 79. Model ](#lesson-79.-Model)
388. [Attributes ](#Attributes)
389. [Добавление Request атрибутов в Model ](#Добавление-Request-атрибутов-в-Model)
390. [Добавление Session атрибутов в Model ](#Добавление-Session-атрибутов-в-Model)
391. [DispatcherServlet sources ](#DispatcherServlet-sources)


## [lesson 80. @ModelAttribute ](#lesson-80.-@ModelAttribute)
392. [Упрощение работы с объектом ModelAndView ](#Упрощение-работы-с-объектом-ModelAndView)
393. [Динамическое создание атрибутов ](#Динамическое-создание-атрибутов)
394. [Аннотация @ModelAttribute ](#Аннотация-@ModelAttribute)
395. [HTML Form. LoginController ](#HTML-Form.-LoginController)


## [lesson 81. Forward, Include, Redirect ](#lesson-81.-Forward,-Include,-Redirect)
396. [3 вида перенаправления запросов ](#3-вида-перенаправления-запросов)
397. [forward in Spring ](#forward-in-Spring)
398. [redirect in Spring ](#redirect-in-Spring)

## [lesson 82. CRUD. API Design ](#lesson-82.-CRUD.-API-Design)
399. [API design best practices ](#API-design-best-practices)
400. [CRUD. Method findAll ](#CRUD.-Method-findAll)
401. [CRUD. Method findById ](#CRUD.-Method-findById)
402. [CRUD. Method create ](#CRUD.-Method-create)
403. [CRUD. Method update ](#CRUD.-Method-update)
404. [CRUD. Method delete ](#CRUD.-Method-delete)


## [lesson 83. CRUD. Service Layer ](#lesson-83.-CRUD.-Service-Layer)
405. [UserService. Method findAll ](#UserService.-Method-findAll)
406. [UserService. Method findById ](#UserService.-Method-findById)
407. [UserService. Method create ](#UserService.-Method-create)
408. [@Transactional annotation ](#@Transactional-annotation)
409. [UserService. Method update ](#UserService.-Method-update)
410. [UserService. Method delete ](#UserService.-Method-delete)
411. [Test UserService functionality ](#Test-UserService-functionality)
412. [Tips. Method delete ](#Tips.-Method-delete)

## [lesson 84. Spring MVC Testing ](#lesson-84.-Spring-MVC-Testing)

413. [Аннотация @AutoConfigureMockMvc ](#Аннотация-@AutoConfigureMockMvc)
414. [Test findAll method ](#Test-findAll-method)
415. [Transactions. spring.jpa.open-in-view property ](#Transactions.-spring.jpa.open-in-view-property)
416. [Test create method ](#Test-create-method)
417. [Problem with sending dates in params ](#Problem-with-sending-dates-in-params)

## [lesson 85. Type Converters ](#lesson-85.-Type-Converters)
418. [spring.mvc.format properties ](#spring.mvc.format-properties)
419. [Аннотация @DateTimeFormat ](#Аннотация-@DateTimeFormat)
420. [Интерфейс WebMvcConfigurer ](#Интерфейс-WebMvcConfigurer)


# [16. Thymeleaf ](#16.-Thymeleaf)

## [lesson 86. Thymeleaf Starter. Введение ](#lesson-86.-Thymeleaf-Starter.-Введение)
421. [View Resolvers ](#View-Resolvers)
422. [Thymeleaf Template Engine Intro ](#Thymeleaf-Template-Engine-Intro)
423. [Настройка Thymeleaf в проекте ](#Настройка-Thymeleaf-в-проекте)
424. [Использование Thymeleaf ](#Использование-Thymeleaf)
425. [Тестирование функционала ](#Тестирование-функционала)

## [lesson 87. CRUD. View Layer. Часть 1 ](#lesson-87.-CRUD.-View-Layer.-Часть-1)
426. [Создание users.html для метода findAll ](#Создание-users.html-для-метода-findAll)
427. [Создание user.html для метода findById ](#Создание-user.html-для-метода-findById)
428. [Тестирование функционала ](#Тестирование-функционала)
429. [Добавление кнопки для метода delete ](#Добавление-кнопки-для-метода-delete)

## [lesson 88. CRUD. View Layer. Часть 2 ](#lesson-88.-CRUD.-View-Layer.-Часть-2)
430. [Создание registration endpoint ](#Создание-registration-endpoint)
431. [Создание registration.html ](#Создание-registration.html)
432. [Тестирование функционала registration ](#Тестирование-функционала-registration)
433. [redirect с сохранением введенных параметров ](#redirect-с-сохранением-введенных-параметров)

## [lesson 89. Filter Query ](#lesson-89.-Filter-Query)
434. [Add UserFilter - Controller & Service layers ](#Add-UserFilter---Controller-&-Service-layers)
435. [Add UserFilter - users.html ](#Add-UserFilter---users.html)
436. [Тестирование функционала ](#Тестирование-функционала)

## [lesson 90. Pagination. Best practices ](#lesson-90.-Pagination.-Best-practices)
437. [HTTP endpoints best practices ](#HTTP-endpoints-best-practices)
438. [2 options of pagination implementation ](#2-options-of-pagination-implementation)
439. [offset-based pagination ](#offset-based-pagination)
440. [PageableArgumentResolver ](#PageableArgumentResolver)
441. [Building PageResponse ](#Building-PageResponse)
442. [Тестирование функционала ](#Тестирование-функционала)


# [17. Validation Starter ](#17.-Validation-Starter)

## [lesson 91. Validation Starter. Введение ](#lesson-91.-Validation-Starter.-Введение)
443. [Подключение validation starter ](#Подключение-validation-starter)
444. [Validation annotations ](#Validation-annotations)
445. [How to use annotations in practice ](#How-to-use-annotations-in-practice)
446. [@Valid & @Validated ](#@Valid-&-@Validated)
447. [BindingResult object ](#BindingResult-object)
448. [Show validation errors on the page ](#Show-validation-errors-on-the-page)
449. [Тестирование функционала ](#Тестирование-функционала)

## [lesson 92. Custom validator ](#lesson-92.-Custom-validator)
450. [Main parts in JSR 303 annotations ](#Main-parts-in-JSR-303-annotations)
451. [Custom annotation @UserInfo ](#Custom-annotation-@UserInfo)
452. [Тестирование функционала ](#Тестирование-функционала)
453. [Configuration properties validation ](#Configuration-properties-validation)
454. [Validation groups ](#Validation-groups)

## [lesson 93. @ControllerAdvice & @ExceptionHandler ](#lesson-93.-@ControllerAdvice-&-@ExceptionHandler)
455. [@ExceptionHandler annotation ](#@ExceptionHandler-annotation)
456. [Тестирование функционала ](#Тестирование-функционала)
457. [@ControllerAdvice annotation ](#@ControllerAdvice-annotation)
458. [Класс ResponseEntityExceptionHandler ](#Класс-ResponseEntityExceptionHandler)


# [18. REST ](#18.-REST)

## [lesson 94. REST. Введение ](#lesson-94.-REST.-Введение)
459. [Проблемы Controller API ](#Проблемы-Controller-API)
460. [REST API ](#REST-API)
461. [REST API Usages ](#REST-API-Usages)

## [lesson 95. REST. Практика ](#lesson-95.-REST.-Практика)
462. [@ResponseBody & findAll method ](#@ResponseBody-&-findAll-method)
463. [findById method ](#findById-method)
464. [@RequestBody & create method ](#@RequestBody-&-create-method)
465. [update method ](#update-method)
466. [delete method ](#delete-method)
467. [@RestController ](#@RestController)
468. [@RestControllerAdvice ](#@RestControllerAdvice)

## [lesson 96. Swagger. API docs ](#lesson-96.-Swagger.-API-docs)
469. [Rest clients ](#Rest-clients)
470. [Подключение springdoc ](#Подключение-springdoc)
471. [Сгенерированная документация для Rest Controllers ](#Сгенерированная-документация-для-Rest-Controllers)
472. [Swagger ui ](#Swagger-ui)
473. [Swagger annotations ](#Swagger-annotations)

## [lesson 97. Upload image ](#lesson-97.-Upload-image)
474. [Добавление новой колонки image в таблице users ](#Добавление-новой-колонки-image-в-таблице-users)
475. [Создание ImageService ](#Создание-ImageService)
476. [upload images from html pages. MultipartFile ](#upload-images-from-html-pages.-MultipartFile)
477. [Тестирование функционала ](#Тестирование-функционала)

## [lesson 98. Get image ](#lesson-98.-Get-image)
478. [Реализация функционала на уровне service ](#Реализация-функционала-на-уровне-service)
479. [Отображение картинки на html странице ](#Отображение-картинки-на-html-странице)
480. [Реализация функционала на уровне rest controller ](#Реализация-функционала-на-уровне-rest-controller)
481. [Тестирование функционала ](#Тестирование-функционала)
482. [Отображение отсутствующей картинки ](#Отображение-отсутствующей-картинки)
483. [Класс ResponseEntity ](#Класс-ResponseEntity)

# [19. Security Starter ](#19.-Security-Starter)

## [lesson 99. Security Starter. Введение ](#lesson-99.-Security-Starter.-Введение)
484. [Понятия Аутентификация и Авторизация ](#Понятия-Аутентификация-и-Авторизация)
485. [Servlet Filters mechanism ](#Servlet-Filters-mechanism)
486. [Spring Servlet Filters mechanism ](#Spring-Servlet-Filters-mechanism)
487. [Подключение Spring Security Starter ](#Подключение-Spring-Security-Starter)

## [lesson 100. Authentication Architecture ](#lesson-100.-Authentication-Architecture)
488. [Spring Security Model ](#работа-для-студентов)
489. [Spring Security Authentication Logic ](#работа-для-студентов)
490. [Debug Security filters (default behaviour) ](#работа-для-студентов)

## [lesson 101. DaoAuthenticationProvider ](#lesson-101.-DaoAuthenticationProvider)
491. [DaoAuthenticationProvider source code ](#DaoAuthenticationProvider-source-code)
492. [Add column password into users table ](#Add-column-password-into-users-table)
493. [Update entity & enum ](#Update-entity-&-enum)
494. [Implement UserDetailsService ](#Implement-UserDetailsService)
495. [Тестирование функциональности ](#Тестирование-функциональности)

## [lesson 102. Form Login ](#lesson-102.-Form-Login)
496. [Default login page source code ](#Default-login-page-source-code)
497. [Custom login page ](#Custom-login-page)
498. [Customise SecurityFilterChain ](#Customise-SecurityFilterChain)
499. [Тестирование функицонала ](#Тестирование-функицонала)
500. [Class UsernamePasswordAuthenticationFilter ](#Class-UsernamePasswordAuthenticationFilter)

## [lesson 103. HTTP Basic Authentication ](#lesson-103.-HTTP-Basic-Authentication)

501. [HTTP Basic Authentication principle ](#HTTP-Basic-Authentication-principle)
502. [HTTP Basic encoder & decoder ](#HTTP-Basic-encoder-&-decoder)
503. [Customise SecurityFilterChain to support HTTP Basic ](#Customise-SecurityFilterChain-to-support-HTTP-Basic)
504. [BasicAuthenticationFilter source code ](#BasicAuthenticationFilter-source-code)

## [lesson 104. PasswordEncoder ](#lesson-104.-PasswordEncoder)
505. [Зачем шифровать пароли ](#Зачем-шифровать-пароли)
506. [List of password encoders ](#List-of-password-encoders)
507. [Implement password encode/decode in the app ](#Implement-password-encode/decode-in-the-app)
508. [Тестирование функционала ](#Тестирование-функционала)

## [lesson 105. Logout ](#lesson-105.-Logout)

509. [LogoutFilter source code ](#LogoutFilter-source-code)
510. [Customise logout in SecurityFilterChain ](#Customise-logout-in-SecurityFilterChain)
511. [Add button Logout on pages ](#Add-button-Logout-on-pages)
512. [Тестирование функционала ](#Тестирование-функционала)

## [lesson 106. Authorization Architecture ](#lesson-106.-Authorization-Architecture)
513. [AuthorizationFilter source code and logic ](#LogoutFilter-source-code)
514. [AuthorizationFilter implementations ](#Customise-logout-in-SecurityFilterChain)
515. [Customise authorizeHttpRequests in SecurityFilterChain ](#Add-button-Logout-on-pages)
516. [Тестирование функционала ](#Тестирование-функционала)

## [lesson 107. Method Security ](#lesson-107.-Method-Security)

517. [@PreAuthorize annotation ](#@PreAuthorize-annotation)
518. [@PostAuthorize annotation ](#@PostAuthorize-annotation)
519. [@EnableMethodSecurity annotation ](#@EnableMethodSecurity-annotation)
520. [@Secured annotation ](#@Secured-annotation)
521. [Service layer authentication ](#Service-layer-authentication)
522. [@PreFilter & @PostFilter annotations ](#@PreFilter-&-@PostFilter-annotations)


## [lesson 108. Access to authenticated user ](#lesson-108.-Access-to-authenticated-user)

523. [Get current user via SecurityContextHolder ](#Get-current-user-via-SecurityContextHolder)
524. [@CurrentSecutiryContext annotation ](#@CurrentSecutiryContext-annotation)
525. [@AuthenticationPrincipal annotation ](#@AuthenticationPrincipal-annotation)
526. [Thymeleaf and Spring Security integration ](#Thymeleaf-and-Spring-Security-integration)

## [lesson 109. CSRF Filter ](#lesson-109.-CSRF-Filter)
527. [Cross-Site Request Forgery ](#Cross-Site-Request-Forgery)
528. [How to solve CSRF problem ](#How-to-solve-CSRF-problem)
529. [Synchronizer Token Pattern ](#Synchronizer-Token-Pattern)
530. [When to use CSRF protection ](#When-to-use-CSRF-protection)
531. [CsrfFilter source code ](#CsrfFilter-source-code)
532. [How to work with CSRF token ](#How-to-work-with-CSRF-token)
533. [Class CsrfRequestDataValueProcessor ](#Class-CsrfRequestDataValueProcessor)
534. [Тестирование функционала ](#Тестирование-функционала)

## [lesson 110. Security Testing ](#lesson-110.-Security-Testing)

536. [Исправление существующих тестов ](#Исправление-существующих-тестов)
537. [spring-security-test dependency ](#spring-security-test-dependency)
538. [1. Manually define a user in tests ](#1.-Manually-define-a-user-in-tests)
539. [2. @WithMockUser annotation ](#2.-@WithMockUser-annotation)
540. [3. SecurityMockMvcRequestPostProcessor ](#3.-SecurityMockMvcRequestPostProcessor)

## [lesson 111. OAuth 2.0. Теория ](#lesson-111.-OAuth-2.0.-Теория)

541. [Текущий Authentication функционал в приложении ](#Текущий-Authentication-функционал-в-приложении)
542. [Что такое OAuth 2 ](#Что-такое-OAuth-2)
543. [Как внедрить OAuth 2 в приложении ](#Как-внедрить-OAuth-2-в-приложении)
544. [OAuth 2 flow types ](#OAuth-2-flow-types)
545. [OAuth 2 Authorization Code Flow ](#OAuth-2-Authorization-Code-Flow)
546. [OAuth 2 Implicit Flow ](#OAuth-2-Implicit-Flow)
547. [OpenID Connect (OIDC) ](#OpenID-Connect-(OIDC))

## [lesson 112. OAuth 2.0. Практика ](#lesson-112.-OAuth-2.0.-Практика)

548. [Create a new project in GCP ](#Create-a-new-project-in-GCP)
549. [Configure OAuth 2 in the project ](#Configure-OAuth-2-in-the-project)
550. [Configure Login Page ](#Configure-Login-Page)
551. [Тестирование функционала ](#Тестирование-функционала)

## [lesson 113. OAuth 2.0. Authentication Principle ](#lesson-113.-OAuth-2.0.-Authentication-Principle)

552. [Add UserInfoEndpoint config in SecurityFilterChain ](#Add-UserInfoEndpoint-config-in-SecurityFilterChain)
553. [Create oidcUserService ](#Create-oidcUserService)
554. [Тестирование функционала ](#Тестирование-функционала)

## [lesson 114. JWT. JSON Web Token ](#lesson-114.-JWT.-JSON-Web-Token)


555. [How to extract info from JWT ](#How-to-extract-info-from-JWT)
556. [JWT header ](#JWT-header)
557. [JWT payload ](#JWT-payload)
558. [JWT signature ](#JWT-signature)
559. [Code Book ](#Code-Book)

## [lesson 115. Swagger Authorization ](#lesson-115.-Swagger-Authorization)
560. [3 options to pass authorization in Swagger ](#3-options-to-pass-authorization-in-Swagger)
561. [springdoc properties to support OAuth 2 ](#springdoc-properties-to-support-OAuth-2)
562. [@SecurityScheme configuration ](#@SecurityScheme-configuration)
563. [Тестирование функционала ](#Тестирование-функционала)



# [20. i18n & l10n ](#20.-i18n-&-l10n)


## [lesson 116. i18n. MessageSource ](#lesson-116.-i18n.-MessageSource)

564. [spring.messages properties ](#spring.messages-properties)
565. [IntelliJ IDEA UTF-8 settings ](#IntelliJ-IDEA-UTF-8-settings)
566. [Creating MessageRestController ](#Creating-MessageRestController)
567. [Тестирование функционала ](#Тестирование-функционала)

## [lesson 117. i18n. Thymeleaf ](#lesson-117.-i18n.-Thymeleaf)

568. [Login page i18n ](#Login-page-i18n)
569. [How to change the language ](#How-to-change-the-language)
570. [LocalChangeInterceptor bean ](#LocalChangeInterceptor-bean)
571. [LocaleResolver bean ](#LocaleResolver-bean)
572. [Тестирование функционала ](#Тестирование-функционала)

# [21. AOP Starter ](#21.-AOP-Starter)

## [lesson 118. AOP Starter. Введение ](#lesson-118.-AOP-Starter.-Введение)
573. [Усложнение кода второстепенной логикой ](#Усложнение-кода-второстепенной-логикой)
574. [Crosscutting concerns ](#Crosscutting-concerns)
575. [AOP terminology ](#AOP-terminology)
576. [AOP approaches ](#AOP-approaches)

## [lesson 119. AOP. Pointcut ](#lesson-119.-AOP.-Pointcut)

577. [spring-boot-starter-aop dependency ](#spring-boot-starter-aop-dependency)
578. [AspectJ annotations ](#AspectJ-annotations)
579. [@Pointcut ](#@Pointcut)
580. [@within ](#@within)
581. [within ](#within)
582. [this & target ](#this-&-target)
583. [@annotation ](#@annotation)
584. [args ](#args)
585. [@args ](#@args)
586. [bean ](#bean)
587. [execution ](#execution)

## [lesson 120. AOP. @Before Advice ](#lesson-120.-AOP.-@Before-Advice)
588. [@Before annotation ](#@Before-annotation)
589. [Тестирование функционала ](#Тестирование-функционала)
590. [CglibAopProxy ](#CglibAopProxy)
591. [Proxy interceptors ](#Proxy-interceptors)
592. [Spring AOP diagram ](#Spring-AOP-diagram)
593. [AopAutoConfiguration ](#AopAutoConfiguration)

## [lesson 121. AOP. JoinPoint. Params ](#lesson-121.-AOP.-JoinPoint.-Params)

594. [JoinPoint object ](#JoinPoint-object)
595. [Get access to proxy data from advice method params ](#Get-access-to-proxy-data-from-advice-method-params)
596. [Тестирование функционала ](#Тестирование-функционала)
597. [argNames ](#argNames)

## [lesson 122. AOP. @After Advices ](#lesson-122.-AOP.-@After-Advices)
598. [All types of advice ](#All-types-of-advice)
599. [@AfterReturning annotation ](#@AfterReturning-annotation)
600. [@AfterThrowing annotation ](#@AfterThrowing-annotation)
601. [@After annotation ](#@After-annotation)
602. [Тестирование функционала ](#Тестирование-функционала)

## [lesson 123. AOP. @Around Advice ](#lesson-123.-AOP.-@Around-Advice)
603. [TransactionInterceptor ](#TransactionInterceptor)
604. [@Around annotation ](#@Around-annotation)
605. [Тестирование функционала ](#Тестирование-функционала)

## [lesson 124. AOP. Best Practices ](#lesson-124.-AOP.-Best-Practices)
606. [1. Combine different Pointcut types ](#1.-Combine-different-Pointcut-types)
607. [2. Move common Pointcuts to separate Aspect ](#2.-Move-common-Pointcuts-to-separate-Aspect)
608. [3. Don t use @Around advice everywhere ](#3.-Don-t-use-@Around-advice-everywhere)
609. [4. Separate Pointcuts by business logic ](#4.-Separate-Pointcuts-by-business-logic)
610. [Aspects order ](#Aspects-order)


# [22. Заключение ](#22.-Заключение)

## [lesson 125. Custom Spring Boot Starter ](#lesson-125.-Custom-Spring-Boot-Starter)
611. [Create a new Gradle module ](#Create-a-new-Gradle-module)
612. [Define starter properties ](#Define-starter-properties)
613. [Create Autoconfiguration ](#Create-Autoconfiguration)
614. [File META-INF/spring.factories ](#File-META-INF/spring.factories)
615. [Move Aspects from the old to the new module ](#Move-Aspects-from-the-old-to-the-new-module)
616. [How to use newly created starter ](#How-to-use-newly-created-starter)
617. [spring-boot-configuration-processor ](#spring-boot-configuration-processor)
618. [Тестирование функционала ](#Тестирование-функционала)

## [lesson 126. Заключение. Путь развития ](#lesson-126.-Заключение.-Путь-развития)

619. [Spring Framework Documentation ](#Spring-Framework-Documentation)
620. [List of all main Spring Boot Starters ](#List-of-all-main-Spring-Boot-Starters)
621. [Java Road Map ](#Java-Road-Map)

========================================================================================
# `1. Intro`


## `lesson 1. Введение`


### 1.`Модули Spring (out of the box)`
Spring Framework - это платформа для разработки Java-приложений, которая предоставляет обширный набор инструментов и модулей для упрощения создания приложений. Вот некоторые из основных модулей Spring:

+ Spring Core Container - этот модуль предоставляет основные функции фреймворка, такие как управление бинами, внедрение зависимостей и управление жизненным циклом бинов.
+ Spring AOP (Aspect-Oriented Programming) - этот модуль позволяет создавать аспектно-ориентированные аспекты, такие как логирование, транзакции и безопасность.
+ Spring JDBC (Java Database Connectivity) - модуль, предоставляющий удобные средства для работы с базами данных и упрощающий кодирование доступа к данным.
+ Spring MVC (Model-View-Controller) - этот модуль предоставляет возможность создания веб-приложений с использованием шаблона проектирования MVC.
+ Spring Security - модуль для обеспечения безопасности приложений, включающий функции аутентификации, авторизации и защиты от атак.

### 2.`Удобство и простота использования`

### 3.`Микросервисная архитектура`
Микросервисная архитектура - это подход к построению приложения в виде набора независимо развертываемых сервисов Вместо того, чтобы создавать монолитное приложение, микросервисная архитектура разделяет его на отдельные компоненты, называемые микросервисами. Каждый микросервис выполняет определенную функцию и может быть разработан, развернут и масштабирован независимо от других сервисов.

Преимущества микросервисной архитектуры
Микросервисная архитектура имеет несколько преимуществ, включая:

1. Гибкость и масштабируемость: Микросервисы могут быть разработаны и развернуты независимо друг от друга, что позволяет гибко масштабировать и изменять отдельные компоненты приложения.

2. Легкость в разработке и поддержке: Разделение приложения на микросервисы упрощает разработку и поддержку, поскольку каждый сервис может быть разработан и поддерживаться отдельной командой.

3. Улучшенная отказоустойчивость: Если один микросервис выходит из строя, остальные микросервисы продолжают работать нормально, что повышает отказоустойчивость системы.

4. Технологическая свобода: Каждый микросервис может использовать разные технологии и языки программирования, что позволяет выбрать наиболее подходящие инструменты для каждой конкретной задачи.

Примеры использования микросервисной архитектуры
Микросервисная архитектура широко применяется в различных областях, включая:

1. Веб-приложения: Микросервисная архитектура позволяет разделить функциональность веб-приложения на отдельные сервисы, такие как аутентификация, обработка платежей и управление контентом.

2. Интернет вещей (IoT): Микросервисная архитектура может быть использована для разработки и управления сложными системами IoT, где различные устройства и сервисы взаимодействуют между собой.

3. Облачные вычисления: Облачные провайдеры, такие как Amazon Web Services (AWS), используют микросервисную архитектуру для предоставления различных сервисов, таких как хранение данных, обработка изображений и машинное обучение.

4. API-сервисы: Микросервисная архитектура может быть использована для создания API-сервисов, которые предоставляют доступ к функциональности приложения через стандартные интерфейсы, такие как REST API.

Заключение
Микросервисная архитектура - это подход к построению приложений, который разделяет их на независимо развертываемые сервисы. Она обладает преимуществами гибкости, масштабируемости, легкости в разработке и поддержке, а также улучшенной отказоустойчивости. Микросервисная архитектура широко применяется в различных областях, включая веб-приложения, IoT, облачные вычисления и API-сервисы.


### 4.`Support & Community`

### 5.`Что нужно знать для изучения курса Spring`


## `lesson 2. Установка программного обеспечения`



### 6.`Установка Java 17`

Для установки Java 17 на Mac и Windows, вам потребуется выполнить следующие шаги:

+ Для Windows:

Скачайте установщик JDK с сайта AdoptOpenJDK.
Выберите соответствующую версию в зависимости от разрядности вашей операционной системы: Windows 32bit или Windows 64bit.
Установите JDK, следуя инструкциям установщика.

+ Для Mac:

Перейдите на сайт adoptium.net.
Скачайте установщик для Mac.
Установите JDK, следуя инструкциям установщика.
Примечание: После установки JDK, убедитесь, что переменная окружения JAVA_HOME указывает на установленный JDK.

### 7.`Установка IntelliJ IDEA Ultimate Edition`

### 8.`Установка PostgreSQL`

Для установки PostgreSQL на Windows, вы можете использовать следующие шаги:

+ Эти шаги должны помочь вам установить PostgreSQL на Windows.

Скачайте установочный файл PostgreSQL с официального сайта по ссылке: https://www.postgresql.org/download/windows/ . Запустите установочный файл и следуйте инструкциям мастера установки, нажимая "Next" для перехода к следующему шагу.

Выберите необходимые компоненты для установки, такие как клиентские утилиты, сервер и дополнительные инструменты.

Укажите порт для сервера PostgreSQL (по умолчанию 5432) и настройте другие параметры, если необходимо.

Создайте пароль для пользователя "postgres" и завершите установку, нажав "Next" и затем "Finish".

После установки, вы можете запустить PostgreSQL, используя командную строку или другие утилиты.




+ Установка PostgreSQL на Mac
Для установки PostgreSQL на Mac, вы можете воспользоваться следующими шагами:

Используйте Homebrew для установки PostgreSQL на Mac OS. Вы можете выполнить следующие команды в терминале:
```
brew install postgresql
```

После установки, вы можете запустить PostgreSQL, используя командную строку или другие утилиты.

Для управления PostgreSQL на Mac, вы можете использовать различные инструменты, такие как PgAdmin или другие графические интерфейсы.

Эти шаги помогут вам установить PostgreSQL на Mac OS.

### 9.`Установка Docker`

Для установки Docker на Windows и Mac, вам потребуется скачать и установить Docker Desktop. Вот краткое руководство по установке:

+ Windows:

Скачайте и установите Docker Desktop для Windows с официального сайта Docker.
Убедитесь, что ваша операционная система соответствует системным требованиям Docker Desktop.
После установки запустите Docker Desktop и следуйте инструкциям по настройке.

+ Mac:

Скачайте и установите Docker Desktop для Mac с официального сайта Docker.
Убедитесь, что ваша операционная система соответствует системным требованиям Docker Desktop.
После установки запустите Docker Desktop и следуйте инструкциям по настройке.

### 10.`Создание нового проекта`

Для создания нового проекта Spring вы можете использовать Spring Initializr, который позволяет быстро и легко настроить и сгенерировать проект Spring. Вот как вы можете это сделать:

+ Используйте Spring Initializr: Вы можете использовать Spring Initializr, доступный по адресу https://start.spring.io/, чтобы создать новый проект Spring. Выберите необходимые зависимости и настройки проекта, а затем сгенерируйте проект.
+ Выберите необходимые зависимости: При создании проекта Spring вы можете выбрать необходимые зависимости, такие как Spring Boot, JDK, Maven и другие, в зависимости от ваших потребностей.
+ Структура проекта: После создания проекта вы увидите стандартную структуру проекта, которая включает каталоги src/main/java для исходного кода и pom.xml для управления зависимостями с помощью Maven.
+ Дополнительные настройки: В зависимости от ваших потребностей, вы также можете добавить дополнительные настройки, такие как настройку базы данных, настройку безопасности, создание контроллеров и служб и другие.


## `lesson 3. Inversion of Control. Dependency Injection`

### 11.`Object Dependencies`
Object Dependencies (зависимости объектов) относятся к концепции Dependency Injection (DI), которая используется в разработке программного обеспечения. DI представляет собой способ управления зависимостями между объектами в приложении. В контексте программирования DI позволяет внедрять зависимости в объекты, что обеспечивает более гибкую и управляемую архитектуру приложения.

Источник указывает, что DI является частью концепции Inversion of Control (IoC), которая изменяет способ, которым объекты получают свои зависимости. Вместо того, чтобы объект самостоятельно создавать свои зависимости, они внедряются в объект извне.

Источник уточняет, что Dependency Injection (DI) может использоваться для управления зависимостями в различных технологиях, таких как Spring Framework в Java.

Таким образом, Object Dependencies (зависимости объектов) в контексте программирования относятся к способу управления зависимостями между объектами в приложении с использованием концепции Dependency Injection (DI).


### 12.`Object Dependencies в коде`

### 13.`Inversion of Control & Dependency Injection`

### 14.`Inversion of Control & Dependency Injection в коде`

### 15.`3 способа внедрения зависимостей в объекте`

## `lesson 4. IoC Container`


### 16.`Spring IoC Container`

Spring IoC Container - это часть Spring Framework, которая реализует принцип инверсии управления (Inversion of Control, IoC). Он отвечает за создание объектов, их связывание и управление их жизненным циклом. IoC Container позволяет создавать и управлять зависимостями между объектами, что упрощает разработку приложений и делает их более гибкими и легкими для тестирования.

Пример использования Spring IoC Container:

ApplicationContext context = new ClassPathXmlApplicationContext("services.xml");
Этот код инициализирует контейнер приложения Spring и загружает конфигурацию из файла "services.xml".

Spring IoC Container также известен как Spring Container и предоставляет механизм для управления объектами приложения и их зависимостями.

Итак, Spring IoC Container играет важную роль в управлении объектами и их зависимостями в приложениях, обеспечивая гибкость и удобство в разработке.

### 17.`Bean`

Bean - это ключевое понятие в Spring Framework. Это объекты, которые являются основой вашего приложения и управляются контейнером управления инверсией управления (IoC) Spring. Bean - это объект, который создается, собирается и управляется контейнером управления инверсией управления Spring IoC. Он может быть описан с помощью аннотаций, таких как @Bean, @Component и других, или с использованием XML-конфигурации. Bean также может иметь различные характеристики, такие как класс, имя, область видимости и другие.

Дополнительно, bean в Spring Framework также связан с понятием Dependency Injection (DI). Он играет важную роль в создании гибкой и модульной архитектуры приложения, позволяя внедрять зависимости между компонентами приложения.

Итак, bean в Spring Framework представляет собой объект, управляемый контейнером управления инверсией управления Spring IoC, который обеспечивает гибкую и модульную архитектуру приложения.

### 18.`Bean Definition`

Bean - ключевой концепт Spring Framework. Понимание этого понятия критично для освоения фреймворка и его эффективного использования. В Spring объекты, которые составляют основу вашего приложения и управляются контейнером управления инверсией управления (IoC) Spring, называются beans. Bean - это объект, который создается, собирается и управляется контейнером управления инверсией управления Spring IoC.


Пример использования bean в Spring можно увидеть в следующем коде:
```java
@Configuration
public class LessonsConfiguration {
    @Bean
    public BeanWithDependency beanWithDependency() {
        return new BeanWithDependency(greetingService());
    }

    @Bean
    public GreetingService greetingService() {
        return new GreetingServiceImpl();
    }
}
```

### 19.`POJO`

POJO в контексте Spring означает "Plain Old Java Object" (Простой Старый Java-Объект). Это обычный Java-объект, который не зависит от каких-либо специфических библиотек или фреймворков. В Spring фреймворке, POJO используются для создания компонентов, которые могут быть управляемыми контейнером Spring.

Spring - это фреймворк для разработки приложений на языке Java. Он предоставляет множество готовых решений для упрощения разработки, таких как управление зависимостями, внедрение зависимостей, управление транзакциями и многое другое.

Пример простого POJO класса в Spring может выглядеть следующим образом:
```java
public class User {
    private String name;
    private int age;

    // геттеры и сеттеры
}
```

В этом примере, класс User является простым Java-объектом без зависимостей от каких-либо специфических библиотек или фреймворков, что соответствует определению POJO.

Заключение
POJO в Spring представляет собой обычные Java-объекты, которые используются для создания компонентов в приложениях, не зависящих от специфических библиотек или фреймворков. Spring фреймворк облегчает использование POJO для создания управляемых компонентов в приложениях на языке Java.

### 20.`Основные интерфейсы IoC Container`

IoC Container (Inversion of Control Container) предоставляет различные интерфейсы для управления зависимостями и контроля жизненного цикла объектов.

Из поисковых результатов видно, что основные интерфейсы IoC Container включают:

+ ApplicationContext в Spring Framework, который предоставляет механизм для управления конфигурацией приложения, создания бинов и управления их жизненным циклом.
+ XML-конфигурации в Spring Framework, которая позволяет определять бины и их зависимости в XML-файлах.
+ BeanFactory в Spring Framework, предоставляющая расширенную модель конфигурации и управления бинами.
+ Container interface в PHP, такой как в Laravel, который предоставляет методы для регистрации и разрешения зависимостей.
+ Inversion of Control (IoC), который предоставляет механизм для управления созданием и жизненным циклом объектов.


Эти интерфейсы играют важную роль в управлении зависимостями и жизненным циклом объектов в различных фреймворках и языках программирования.


### 21.`3 способа создания Bean Definitions`

В Spring Framework существует несколько способов создания определений бинов. Некоторые из них включают:

1. Аннотации (@Component, @Service, @Repository, @Controller): В Spring Framework можно использовать аннотации, такие как @Component, @Service, @Repository, @Controller для создания определений бинов. Например:
import org.springframework.stereotype.Component;
```java
@Component
public class SimpleBean {
    public String hello() {
        return "Hello world!";
    }
}
```

2. XML-конфигурация: Другим способом создания определений бинов в Spring Framework является использование XML-конфигурации. Это позволяет определять бины в XML-файлах. Например:

```xml
<bean id="simpleBean" class="com.example.SimpleBean">
    <property name="message" value="Hello world!" />
</bean>
```

3. Java-конфигурация: Также возможно создавать определения бинов в Spring Framework с помощью Java-конфигурации, что позволяет определять бины в коде на Java.
```java
@Configuration
public class AppConfig {
    @Bean
    public SimpleBean simpleBean() {
        return new SimpleBean();
    }
}
```


Эти способы предоставляют различные подходы к созданию определений бинов в Spring Framework, и выбор конкретного способа может зависеть от конкретных потребностей проекта.

# 2. XML-based Configuration

## lesson 5. XML-based Configuration


### 22.`BeanFactory и ApplicationContext интерфейсы`

BeanFactory и ApplicationContext - это интерфейсы в Spring Framework, используемые для управления, конфигурирования и манипулирования бинами.

BeanFactory предоставляет основные функции для управления и манипулирования бинами в программном виде, в то время как ApplicationContext предоставляет дополнительные функции, такие как доступ к ресурсам, распространение событий на бины, загрузку нескольких (иерархических) контекстов и другие возможности в более ориентированном на фреймворк стиле.

ApplicationContext расширяет функциональность BeanFactory и предоставляет дополнительные возможности, такие как доступ к ресурсам, распространение событий на бины, загрузку нескольких (иерархических) контекстов и другие возможности в более ориентированном на фреймворк стиле.

Важно отметить, что ApplicationContext предоставляет дополнительные функции, такие как MessageSource, доступ к ресурсам, распространение событий на бины, загрузку нескольких (иерархических) контекстов и другие возможности в более ориентированном на фреймворк стиле.

Различия между BeanFactory и ApplicationContext:

+ Интерфейсы IOC (Inversion of Control):

BeanFactory является основным интерфейсом для доступа к контейнеру Spring, обеспечивающим управление бинами и их зависимостями через механизм IOC.
ApplicationContext расширяет функциональность BeanFactory и предоставляет дополнительные возможности, такие как обработка событий, межбиновые ссылки, доступ к ресурсам и многое другое.

+ Производительность и гибкость:

ApplicationContext обычно предпочтительнее для большинства приложений из-за своей более высокой производительности и гибкости.
BeanFactory может быть полезен в случаях, когда требуется минимальная конфигурация и ленивая инициализация бинов.

+ Поддержка аннотаций:

ApplicationContext обеспечивает поддержку аннотаций для внедрения зависимостей и управления бинами, что делает его более удобным в использовании в современных приложениях.

+ Обработка событий:

ApplicationContext предоставляет возможность обработки событий, что позволяет реагировать на различные события в контейнере Spring.


+ Межбиновые ссылки и доступ к ресурсам:

ApplicationContext позволяет легко устанавливать межбиновые ссылки и получать доступ к различным ресурсам, таким как файлы, URL-адреса и т. д..


В заключение, хотя BeanFactory и ApplicationContext оба предоставляют возможности управления бинами в Spring Framework, ApplicationContext предоставляет более широкий спектр функциональности и обычно является предпочтительным выбором для большинства приложений.

### 23.`ClassPathXmlApplicationContext`

ClassPathXmlApplicationContext - это класс в Spring Framework, который позволяет загружать конфигурацию бинов из XML-файлов, находящихся в classpath, и автоматически обновлять контекст.

Пример использования ClassPathXmlApplicationContext:

ApplicationContext context = new ClassPathXmlApplicationContext("applicationContext.xml");
Person person = (Person) context.getBean("person");
System.out.println(person.getId() + ":" + person.getName());
ClassPathXmlApplicationContext также позволяет использовать несколько XML-файлов конфигурации для инициализации контейнера Spring. В этом случае бины, определенные в последних загруженных файлах, переопределят бины, определенные в ранее загруженных файлах.

Конструкторы ClassPathXmlApplicationContext
ClassPathXmlApplicationContext имеет несколько конструкторов для загрузки определений бинов из XML-файлов и автоматического обновления контекста. Некоторые из них включают:

+ ClassPathXmlApplicationContext(String configLocation)
+ ClassPathXmlApplicationContext(String... configLocations)
+ ClassPathXmlApplicationContext(String[] configLocations, boolean refresh)


Этот класс также полезен для тестовых сред и демонстрационных целей.

Префикс classpath:* При конструировании контекста приложения, иногда можно использовать префикс classpath*:.

Этот класс также полезен для тестовых сред и демонстрационных целей.

Заключение
ClassPathXmlApplicationContext в Spring Framework предоставляет удобный способ загрузки конфигурации бинов из XML-файлов, находящихся в classpath, и автоматического обновления контекста. Он также поддерживает использование нескольких XML-файлов конфигурации и предоставляет различные конструкторы для удобства использования.

### 24.`XML config`

XML-конфигурация Spring Framework используется для настройки бинов, внедрения зависимостей и других аспектов приложения. В XML-файле можно определить бины, их зависимости, свойства и другие настройки. Пример XML-конфигурации может выглядеть следующим образом:
```xml
<beans xmlns="http://www.springframework.org/schema/beans"
       xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
       xsi:schemaLocation="http://www.springframework.org/schema/beans http://www.springframework.org/schema/beans/spring-beans.xsd">

    <bean id="exampleBean" class="com.example.ExampleBean">
        <property name="property1" value="someValue"/>
        <property name="property2" ref="anotherBean"/>
    </bean>

    <bean id="anotherBean" class="com.example.AnotherBean">
        <!-- настройки для другого бина -->
    </bean>

</beans>
```
Здесь <beans> - корневой элемент, в котором определяются все бины приложения. <bean> используется для определения бина, его id, класса и свойств. Внутри <property> можно указать значение свойства или ссылку на другой бин.

Основные элементы XML-конфигурации Spring включают в себя:

<beans>: Этот элемент является корневым элементом XML-конфигурации Spring. Он содержит определения бинов и другие конфигурационные элементы.
<bean>: Этот элемент определяет отдельный бин в контейнере Spring. Он содержит информацию о классе бина, его зависимостях и других настройках.
<property>: Этот элемент используется для внедрения значений свойств в бины. Например, это может быть ссылка на другой бин или просто значение.
<constructor-arg>: Этот элемент определяет аргументы конструктора для инъекции зависимостей.

XML-конфигурация Spring предоставляет гибкость и читаемость, но в современных приложениях часто используется аннотационный подход для конфигурации Spring.


### 25.`Идентификаторы (id) бинов как ключи в IoC Container`

В контейнере управления инверсией управления (IoC) идентификаторы (id) бинов используются в качестве ключей для доступа к объектам, зарегистрированным в контейнере. Вот некоторые ключевые моменты:

Spring IoC Container и типы бинов:

+ В Spring IoC Container существуют различные типы бинов, такие как singleton, prototype, request и session.
+ Бины типа singleton создаются один раз и используются повсюду в приложении, в то время как бины типа prototype создаются каждый раз при запросе.
+ Бины типа request и session связаны с HTTP-запросами и сеансами соответственно.


Регистрация бинов в IoC Container:

+ Бины регистрируются в контейнере с помощью аннотаций, таких как @Bean и @Component.
+ Аннотация @Bean используется для указания методов, которые возвращают объекты, которые должны быть зарегистрированы в контейнере.
+ Аннотация @Component используется для автоматической регистрации классов в контейнере.


Использование идентификаторов (id) бинов:

+ Идентификаторы (id) бинов используются в качестве ключей для доступа к зарегистрированным объектам в контейнере.
+ Эти идентификаторы могут быть использованы для получения бинов из контейнера с помощью метода getBean().
+ Инверсия управления (IoC) и внедрение зависимостей (DI):

IoC и DI являются ключевыми концепциями в управлении зависимостями в приложениях.
В IoC контейнере объекты не создаются вручную, а управление их жизненным циклом осуществляется контейнером.
DI позволяет внедрять зависимости в объекты, что упрощает управление зависимостями и повышает гибкость приложения.
Таким образом, идентификаторы (id) бинов играют важную роль в IoC Container, обеспечивая уникальный доступ к зарегистрированным объектам и управляя их жизненным циклом.

### 26.`Алиасы бинов (alias)`

В Spring Framework алиасы бинов используются для предоставления альтернативных имен для бинов. Например, если у вас есть бин с именем "myBean", вы можете создать алиас "myAlias" для этого бина. Это может быть полезно для улучшения читаемости кода или обеспечения совместимости с другими системами.

Примеры использования алиасов в Spring:

+ В XML-конфигурации Spring:
```xml
<bean id="myBean" class="com.example.MyClass" />
<alias name="myAlias" alias="myBean" />
```

В этом примере "myAlias" является алиасом для бина "myBean".


+ В Java-конфигурации Spring:
```java
@Component("myBean")
public class MyClass {
    // Код класса
}
```

В этом случае "myBean" может быть использован как основное имя бина, а затем созданы алиасы для него.

Эти примеры демонстрируют, как можно использовать алиасы для бинов в Spring Framework


## `lesson 6. Constructor Injection`


### 27.`Внедрение примитивных типов данных`

В Spring Framework внедрение примитивных типов данных может осуществляться с помощью различных механизмов, таких как аннотации @Value и @Autowired. Давайте рассмотрим примеры внедрения примитивных типов данных в Spring.

1. Внедрение примитивных типов данных с помощью аннотации @Value: Пример внедрения значения примитивного типа данных с использованием аннотации @Value:
```java
import org.springframework.beans.factory.annotation.Value;

public class MyBean {
    @Value("10")
    private int myNumber;
    // Другие поля и методы класса
}
```

Этот пример демонстрирует внедрение значения примитивного типа данных (в данном случае, целочисленного) с использованием аннотации @Value.

2. Внедрение примитивных типов данных с помощью @Autowired: Внедрение примитивных типов данных с использованием @Autowired может осуществляться через конструктор, сеттеры или поля. Например:

+ Внедрение через конструктор:
```java
public class MyBean {
    private int myNumber;

    @Autowired
    public MyBean(@Value("10") int myNumber) {
        this.myNumber = myNumber;
    }
    // Другие поля и методы класса
}
```

Этот пример демонстрирует внедрение значения примитивного типа данных через конструктор с использованием аннотации @Autowired и @Value.

+ Внедрение через сеттеры или поля:
```java
public class MyBean {
    @Value("10")
    private int myNumber;
    // Другие поля и методы класса
}
```

В этом примере значение примитивного типа данных внедряется непосредственно в поле класса с использованием аннотации @Value.

Таким образом, в Spring Framework существует несколько способов внедрения примитивных типов данных, таких как целые числа, строки и булевы значения, с использованием различных аннотаций и механизмов внедрения зависимостей.

### 28.`Внедрение коллекций list/set`

Spring Framework предоставляет возможность использовать внедрение коллекций (list/set) с помощью конструктора. Это позволяет передавать коллекции объектов в качестве зависимостей. Вот примеры:

+ Пример внедрения списка (List) с использованием конструктора:
```java
public class CollectionExample {
    private List<String> myList;

    public CollectionExample(List<String> myList) {
        this.myList = myList;
    }
}
```

+ Пример внедрения множества (Set) с использованием конструктора:
```java
public class CollectionExample {
    private Set<Integer> mySet;

    public CollectionExample(Set<Integer> mySet) {
        this.mySet = mySet;
    }
}
```
В обоих примерах Spring будет автоматически внедрять соответствующие коллекции при создании экземпляра класса CollectionExample.


### 29.`Внедрение ассоциативного массива map`

Spring предоставляет возможность использовать ассоциативные массивы, такие как Map, для хранения пар ключ-значение. Вот пример внедрения ассоциативного массива Map в Spring:
```java
import java.util.Map;

public class MyBean {
    private Map<String, String> myMap;

    // Геттер и сеттер для myMap
    public Map<String, String> getMyMap() {
        return myMap;
    }

    public void setMyMap(Map<String, String> myMap) {
        this.myMap = myMap;
    }
}
```
В этом примере класс MyBean содержит поле myMap, которое представляет ассоциативный массив Map с ключами и значениями типа String. Этот Map может быть внедрен в другие компоненты Spring, такие как сервисы или контроллеры, для удобного доступа к данным.

Использование Map в Spring позволяет эффективно управлять парами ключ-значение и обеспечивает гибкость при работе с данными в приложении.

### 30.`Поле genericArgumentValues в BeanDefinition`

### 31.`Поле indexedArgumentValues в BeanDefinition`

### 32.`Указание атрибута type в параметрах конструктора`

### 33.`Указание атрибута name в параметрах конструктора`

## `lesson 7. Factory Method Injection`


### 34.`Внедрение других бинов через ref*`

### 35.`Создание новое бина CompanyRepository`

### 36.`Внедрение зависимостей через factory method`

### 37.`Атрибут factory-bean (паттерн ServiceLocator)`

## `lesson 8. Property Injection`


### 38.`Использование set* методов в ConnectionPool`

### 39.`Поле propertyValues в BeanDefinition`

### 40.`Упрощенный жизненный цикл бинов - Bean Lifecycle`

### 41.`Плюсы и минусы Constructor и Property Injections`

### 42.`Циклические зависимости через Property Injection`

## `lesson 9. Bean Scopes`


### 43.`Common Bean Scopes`

### 44.`Custom Bean Scopes`

### 45.`Web Bean Scopes`

### 46.`Prototype Bean Scope`

## `lesson 10. Lifecycle Callbacks`


### 47.`Измененный Bean Lifecycle`

### 48.`Initialization callbacks`

### 49.`Destruction callbacks`

## `lesson 11. Injection from Properties Files`


### 50.`Зачем использовать properties files`

### 51.`Создание файла application.properties`

### 52.`PropertySourcesPlaceholderConfigurer bean`

### 53.`Expression Language (EL)`

### 54.`Spring Expression Language (SpEL)`

### 55.`SpEL документация`

### 56.`System properties`

## `lesson 12. BeanFactoryPostProcessor (BFPP)`


### 57.`Интерфейс BeanFactoryPostProcessor`

### 58.`Как работает PropertySourcesPlaceholderConfigurer`

### 59.`Измененный Bean Lifecycle`

### 60.`Метод isAssignableFrom`

## `lesson 13. Custom BeanFactoryPostProcessor`

### 61.`Создание собственных BeanFactoryPostProcessor`
### 62.`Интерфейс Ordered`
### 63.`Интерфейс PriorityOrdered`


# 3.`Annotation-based Configuration`

## `lesson 14. Annotation-based Configuration`

### 64.`Подключение зависимости jakarta annotation api`
### 65.`Аннотации @PostConstruct и @PreDestroy`
### 66.`Класс CommonAnnotationBeanPostProcessor`
### 67.`context:annotation-config xml element`




## `lesson 15. BeanPostProcessor (BPP)`

### 68.`Интерфейс BeanPostProcessor`
### 69.`Bean Lifecycle (final version)`
### 70.`Интерфейс Aware`
### 71.`Класс ApplicationContextAwareProcessor`


## `lesson 16. Custom BeanPostProcessor. Часть 1`

### 72.`Создание своей аннотации @InjectBean`
### 73.`Создание InjectBeanPostProcessor`
### 74.`Утилитный класс ReflectionUtils`
### 75.`Тестирование InjectBeanPostProcessor`

## `lesson 17. Custom BeanPostProcessor. Часть 2`

### 76.`Создание аннотации @Transaction`
### 77.`Создание CrudRepository`
### 78.`Создание TransactionBeanPostProcessor`
### 79.`Тестирование TransactionBeanPostProcessor`
### 80.`Корректируем TransactionBeanPostProcessor`
### 81.`Создание AuditingBeanPostProcessor`


## `lesson 18. @Autowired & @Value`

### 82.`Аннотация @Autowired`
### 83.`Аннотация @Resource`
### 84.`Решение конлифкта бинов. @Qualifier`
### 85.`Collection injection`
### 86.`Properties injection. @Value`


## `lesson 19. Classpath Scanning`

### 87.`context:component-scan. Аннотации @Component`
### 88.`Замена бинов из xml на @Component`
### 89.`Тестирование функционала`

## `lesson 20. Bean Definition Readers`

### 90.`Component Scan classes`
### 91.`Bean Definition Readers`
### 92.`Класс ComponentScanBeanDefinitionParser`
### 93.`Класс AnnotatedBeanDefinitionReader`

## `lesson 21. Type Filters`

### 94.`Атрибут annotation-config`
### 95.`Атрибут name-generator`
### 96.`Атрибут resource-pattern`
### 97.`Атрибут scoped-proxy`
### 98.`Атрибут scope-resolver`
### 99.`Атрибут use-default-filters`
### 100.`5 type filters`
### 101.`Custom filters`


## `lesson 22. @Scope`
### 102.`Атрибут scope-resolver`
### 103.`Класс AnnotationScopeMetadataResolver`
### 104.`Аннотация @Scope`


## `lesson 23. JSR 250, JSR 330`

### 105.`Аббревиатура JSR`
### 106.`JSR 250`
### 107.`JSR 330`
### 108.`Класс Jsr330ScopeMetadataResolver`



# 4.`Java-based Configuration`

## `lesson 24. Java-based Configuration`

### 109.`Класс ConfigurationClassBeanDefinitionReader`
### 110.`Создание ApplicationConfiguration. @Configuration`
### 111.`Аннотация @PropertySource`
### 112.`Аннотация @ComponentScan`
### 113.`Класс AnnotationConfigApplicationContext`


## `lesson 25. @Import & @ImportResource`

### 114.`Класс AnnotationConfigApplicationContext`
### 115.`Аннотация @ImportResource`
### 116.`Аннотация @Import`

## `lesson 26. @Bean. Часть 1`

### 117.`Аннотация @Bean`
### 118.`Тестирование Java конфигурации`
### 119.`Свойства аннотации @Bean`
### 120.`Аннотация @Scope с @Bean`
### 121.`Внедрение зависимостей с @Bean`
### 122.`Конфликт имен @Bean и @Component`

## `lesson 27. @Bean. Часть 2`

### 123.`3-ий вариант внедрения зависимостей в @Bean`
### 124.`Cglib proxy в @Configuration`
### 125.`Свойство proxyBeanMethods в @Configuration`
### 126.`@Bean создаются через паттерн Service Locator`

## `lesson 28. Profiles`

### 127.`Environment Bean`
### 128.`Аннотация @Profile`
### 129.`Активация profiles через properties`
### 130.`Активация profiles через ApplicationContext`



# 5.`Event Listeners`


## `lesson 29. Event Listeners. Часть 1`

### 131.`Шаблон проектирования Listener`
### 132.`Создание события (Event)`
### 133.`Создание слушателя событий (Listener). @EventListener`
### 134.`Реализация логики для отправки события`

## `lesson 30. Event Listeners. Часть 2`

### 135.`Bean ApplicationEventPublisher`
### 136.`Тестирование слушателей событий`
### 137.`Listeners order`
### 138.`Listeners conditions`


# 6.`Spring Boot`


## `lesson 31. Spring Boot. Введение`

### 139.`Spring modules`
### 140.`Spring Data Configuration`
### 141.`Modules Auto Configuration`
### 142.`Conditions`
### 143.`Spring Boot Starters`
### 144.`Dependency Management`
### 145.`How to build Spring Boot Application`

## `lesson 32. @Conditional`

### 146.`Аннотация @Conditional`
### 147.`Класс Condition`
### 148.`Custom JpaCondition`
### 149.`Тестирование JpaCondition`
### 150.`Аннотация @Profile`
### 151.`Другие @Condition аннотации`


## `lesson 33. Spring Boot. Настройка проекта`

### 152.`Spring Boot Gradle Plugin`
### 153.`Spring Dependency Management Plugin`
### 154.`spring-boot-starter`
### 155.`Run Spring Boot Application`
### 156.`Autogenerated Spring Boot Project`
### 157.`Maven spring-boot-starter-parent pom`

## `lesson 34. @SpringBootApplication`

### 158.`Структура Spring Boot приложения`
### 159.`Что делает метод SpringApplication.run`
### 160.`Аннотация @SpringBootApplication`
### 161.`Аннотация @SpringBootConfiguration`
### 162.`Аннотация @ComponentScan`
### 163.`Аннотация @PropertySource`
### 164.`Аннотация @EnableAutoConfiguration`


## `lesson 35. Lombok`

### 165.`Подключение Lombok`
### 166.`Gradle Lombok Plugin`
### 167.`IntelliJ IDEA Lombok Plugin`
### 168.`Аннотации Lombok`
### 169.`Файл lombok.config`

## `lesson 36. Properties`

### 170.`Файл spring.properties`
### 171.`Externalized Configuration`
### 172.`Profile-specific properties`
### 173.`Spring program arguments & VM options`
### 174.`Property Placeholders & Default values`
### 175.`spring.config.location`

## `lesson 37. Yaml format`

### 176.`YAML - Yet Another Markup Language`
### 177.`Класс YamlPropertiesFactoryBean`
### 178.`Приоритет properties vs yaml`
### 179.`Переписывание application.properties на yaml`


## `lesson 38. @ConfigurationProperties`

180.`Класс JpaProperties`
181.`Класс DatabaseProperties`
182.`Аннотация @ConfigurationProperties`
183.`Аннотация @ConfigurationPropertiesScan`
184.`Immutable DatabaseProperties`
185.`DatabaseProperties as record`
186.`Property key names`



#`7. Logging Starter`


## `lesson 39. Logging Starter`

190.`Application as a Black Box`
191.`Logging libraries`
192.`Log Levels`
193.`spring-boot-starter-logging dependency`
194.`Аннотация @Slf4j`
195.`Delombok annotations`
196.`Формат логов по умолчанию`
197.`logging.* properties`

## `lesson 40. Logback Configuration`

198.`Logback default xml configs`
199.`File Output`
200.`Custom log configuration`


# `8. Test Starter`

## `lesson 41. Test Starter`

### 201.`Подключение spring-boot-starter-test`
### 202.`Транзитивные зависимости spring-boot-starter-test`
### 203.`Зависимость spring-test`
### 204.`Зависимость spring-boot-test`
### 205.`Зависимость spring-boot-test-autoconfigure`
### 206.`Пример написания Unit тестов`
### 207.`Java Gradle Plugin tasks relationship`

## `lesson 42. Integration Testing. Part 1`

### 208.`Основные цели Spring Integration Testing`
### 209.`Жизненный цикл тестов`
### 210.`JUnit 5 Extension Model`
### 211.`TestContext Framework`
### 212.`SpringExtension source code`

## `lesson 43. Integration Testing. Part 2`

### 213.`Создание CompanyServiceIT`
### 214.`SpringExtension via @ExtendWith`
### 215.`Аннотация @ContextConfiguration`
### 216.`Аннотация @TestPropertySource`
### 217.`Класс ApplicationContextInitializer`
### 218.`Аннотация @SpringBootTest`
### 219.`Написание первого интеграционного теста`
### 220.`Класс DependencyInjectionTestExecutionListener`

## `lesson 44. Integration Testing. Part 3`

### 221.`Аннотация @ActiveProfiles`
### 222.`Custom Test Annotations`
### 223.`Аннотация @TestConstructor`
### 224.`Замена @TestConstructor на spring.properties`

## `lesson 45. Context Caching`

### 225.`Создание нескольких ApplicationContext в тестах`
### 226.`Аннотации @MockBean и @SpyBean`
### 227.`Класс MockitoTestExecutionListener`
### 228.`Аннотация @TestConfiguration`
### 229.`Аннотация @DirtiesContext`


#`9. Data JPA Starter`

## `lesson 46. Data JPA Starter. Введение`

### 230.`Чего не хватало в Hibernate`
### 231.`Установка PostgreSQL`
### 232.`Установка Docker`
### 233.`Postgres Docker Image`
### 234.`Подключение к postgres из IntelliJ IDEA`

## `lesson 47. Data JPA Starter. Подключение`

### 235.`Подключение spring-boot-starter-data-jpa`
### 236.`Зависимости spring-boot-starter-data-jpa`
### 237.`Класс HibernateJpaAutoConfiguration`
### 238.`Настройка spring.datasource и spring.jpa properties`
### 239.`Тестирование приложения`

## `lesson 48. Hibernate Entities`

### 240.`UML диаграмма выполненных sql скриптов`
### 241.`Создание сущности Company`
### 242.`Создание коллекции locales (ElementCollection)`
### 243.`Создание сущности User`
### 244.`Создание сущности Payment`
### 245.`Создание сущности Chat`
### 246.`Создание сущности UserChat`
### 247.`Проверка маппинга сущностей через hbm2ddl.auto`
### 248.`Аннотация @EntityScan`


#`10. Data JPA Transactions`

## `lesson 49. @Transactional. TestContext`

### 249.`Общая структура работы с TransactionManager`
### 250.`Создание CompanyRepository IT`
### 251.`Аннотации @Transactional из Jakarta EE и Spring`
### 252.`Класс TransactionalTestExecutionListener`
### 253.`Аннотации @Commit и @Rollback`

## `lesson 50. TransactionAutoConfiguration`

### 254.`Класс TransactionAutoConfigurationКак происходит обработка транзакций в proxy`
### 255.`Аннотация @Transactional и Cglib proxy`
### 256.`Как работает Cglib proxy с TransactionManager`
### 257.`Как подключить механизм транзакций внутри объекта (не proxy)`
### 258.`Механизм транзакций между несколькими Cglib proxy`

## `lesson 51. @Transactional Settings`

### 259.`Свойства @Transactional. transactionManager`
### 260.`Transaction propagation`
### 261.`Transaction propagation резюме`
### 262.`Transaction isolation`
### 263.`Transaction timeout`
### 264.`ReadOnly transaction`
### 265.`Transaction rollbackFor & rollbackForClassName`
### 266.`Transaction noRollbackFor & noRollbackForClassName`


## `lesson 52. Manual Transactions`

### 267.`Свойства объекта TransactionTemplate`
### 268.`Функционал TransactionTemplate`
### 269.`Обработка checked exceptions`
### 270.`Взаимодействие TransactionTemplate с другими Proxy`
### 271.`Вынесение @Transactional в @IT`


#`11. Data JPA Repositories`

## `lesson 53. Repository`

### 272.`Интерфейс Repository`
### 273.`Написание теста на удаление Company`
### 274.`Класс JpaRepositoryAutoConfiguration`

## `lesson 54. RepositoryQuery`

### 275.`Создание Proxy на классы Repository`
### 276.`Класс QueryExecutorMethodInterceptor`
### 277.`Класс RepositoryQuery`
### 278.`Наследники Repository`

## `lesson 55. PartTreeJpaQuery`

### 279.`Класс PartTreeJpaQuery`
### 280.`Примеры написания запросов`
### 281.`Тестирование запросов`
### 282.`Весь список ключевых слов PartTreeJpaQuery`


## `lesson 56. NamedQuery`

### 283.`Недостатки PartTreeJpaQuery`
### 284.`Класс NamedQuery`
### 285.`Аннотация @NamedQuery`
### 286.`Тестирование NamedQuery`
### 287.`Аннотация @Param`

## `lesson 57. @Query`

### 288.`StoredProcedureJpaQuery`
### 289.`Аннотация @Query`
### 290.`Демонстрация работы @Query`
### 291.`Усовершенствованный оператор LIKE`
### 292.`Native Query`

## `lesson 58. @Modifying`

### 293.`Запрос на обновление через @Query`
### 294.`Аннотация @Modifying`
### 295.`Hibernate PersistenceContext`
### 296.`Свойства clearAutomatically и flushAutomatically`
### 297.`clearAutomatically и LazyInitializationException`

## `lesson 59. Special parameters`

### 298.`Top & First`
### 299.`TopN & FirstN`
### 300.`Класс Sort`
### 301.`Класс Pageable`

## `lesson 60. Page & Slice`

### 302.`Spring классы Streamable, Slice, Page`
### 303.`Демонстрация работы Slice объекта`
### 304.`Почему Slice объекта недостаточно`
### 305.`Демонстрация работы Page объекта`

## `lesson 61. @EntityGraph`

### 306.`Аннотация @EntityGraph`
### 307.`Именованные графы @NamedEntityGraph`
### 308.`Свойство attributePaths в @EntityGraph`
### 309.`Конфликт Pageable при получении EAGER связей`

## `lesson 62. @Lock & @QueryHints`

### 310.`Аннотация @Lock`
### 311.`Демонстрация пессимистических блокировок`
### 312.`Аннотация @QueryHints`

## `lesson 63. Projection`

### 313.`Class-based Projections`
### 314.`Generic Class-based Projections`
### 315.`Interface-based Projections`
### 316.`SpEL in Projections`

## `lesson 64. Custom Repository Implementation`

### 317.`Запрос фильтрации через Custom Implementation`
### 318.`Criteria API для запроса фильтрации`
### 319.`Аннотация @EnableJpaRepository`
### 320.`Тестирование запроса фильтрации`

## `lesson 65. JPA Auditing`

### 321.`Создание AuditingEntity`
### 322.`Аннотация @EnableJpaAuditing`
### 323.`Тестирование @CreatedDate и @LastModifiedDate`
### 324.`Аннотации @CreatedBy и @LastModifiedBy`
### 325.`Создание AuditorAware Bean`
### 326.`Тестирование @CreatedBy и @LastModifiedBy`

## `lesson 66. Hibernate Envers`

### 327.`Подключение Hibernate Envers`
### 328.`Создание сущности Revision`
### 329.`Аннотация @Audited`
### 330.`Аннотация @EnableEnversRepositories`
### 331.`Тестирование Hibernate Envers`
### 332.`Класс RevisionRepository`


## `lesson 67. Querydsl`

### 333.`Подключение Querydsl`
### 334.`Создание QPredicates`
### 335.`Замена Criteria API на Querydsl`
### 336.`Тестирование Querydsl`
### 337.`Класс QuerydslPredicateExecutor`


# `12. JDBC Starter`


## `lesson 68. JDBC Starter`

### 338.`Зависимость spring-boot-starter-jdbc`
### 339.`JdbcTemplateAutoConfiguration`
### 340.`Функционал класса JdbcTemplate`
### 341.`Практика JdbcTemplate`
### 342.`Тестирование функционала`
### 343.`Подключение логов для JdbcTemplate`


## `lesson 69. Batch size & Fetch size`

### 344.`Batch запросы`
### 345.`Batch запрос через JdbcTemplate`
### 346.`Тестирование Batch запроса через JdbcTemplate`
### 347.`Batch запрос через NamedParameterJdbcTemplate`
### 348.`Установка batch_size в Hibernate`
### 349.`Fetch size`




# `13. Databases in tests`

## `lesson 70. In-Memory databases. H2`

### 350.`Два варианта поднятия тестовой базы данных`
### 351.`Подключение H2 database`
### 352.`Аннотация @Sql`

## `lesson 71. Testcontainers`
### 353.`testcontainers lib`
### 354.`Подключение testcontainers`
### 355.`Создание IntegrationTestBase`
### 356.`Тестирование testcontainers`
### 357.`Тестовые данные (ids)`



# `14. Database Migrations`

## `lesson 72. Liquibase. Теория`

### 358.`Устройство migration frameworks`
### 359.`Стуктура Liquibase changelog`
### 360.`Changelog master file`

## `lesson 73. Liquibase. Практика`

### 361.`Подключение зависимости liquibase-core`
### 362.`Класс LiquibaseAutoConfiguration`
### 363.`Создание master changelog`
### 364.`liquibase formatted sql`
### 365.`Тестирование Liquibase`
### 366.`Добавление нового changelog (envers tables)`
### 367.`md5sum`
### 368.`Использование Liquibase в тестах`


# `15. Web Starter`

## `lesson 74. Web Starter. Введение`

### 369.`MVC и классические web-приложения`
### 370.`web-приложение на Spring Boot`
### 371.`Embedded Tomcat`
### 372.`Настройка spring-web приложения`
### 373.`Класс WebMvcAutoConfiguration`


## `lesson 75. Dispatcher Servlet`

### 374.`Жизненный цикл сервлетов`
### 375.`Псевдокод метода service в DispatcherServlet`
### 376.`Исходный код класса DispatcherServlet`


## `lesson 76. @Controller`

### 377.`Подключение зависимостей и настройка view resolver`
### 378.`Создание контроллера. @Controller`


## `lesson 77. @RequestMapping`

### 379.`Основные составляющие HTTP запроса и HTTP ответа`
### 380.`Основные составляющие URL`
### 381.`Аннотации @RequestMapping`


## `lesson 78. Parameters, Headers, Cookies`

### 382.`Parameters. @RequestParam annotation`
### 383.`Headers. @RequestHeader annotation`
### 384.`Cookies. @CookieValue annotation`
### 385.`Method params naming`
### 386.`DispatcherServlet sources`
### 387.`@PathVariable annotation`


## `lesson 79. Model`

### 388.`Attributes`
### 389.`Добавление Request атрибутов в Model`
### 390.`Добавление Session атрибутов в Model`
### 391.`DispatcherServlet sources`


## `lesson 80. @ModelAttribute`

### 392.`Упрощение работы с объектом ModelAndView`
### 393.`Динамическое создание атрибутов`
### 394.`Аннотация @ModelAttribute`
### 395.`HTML Form. LoginController`


## `lesson 81. Forward, Include, Redirect`

### 396.`3 вида перенаправления запросов`
### 397.`forward in Spring`
### 398.`redirect in Spring`

## `lesson 82. CRUD. API Design`

### 399.`API design best practices`
### 400.`CRUD. Method findAll`
### 401.`CRUD. Method findById`
### 402.`CRUD. Method create`
### 403.`CRUD. Method update`
### 404.`CRUD. Method delete`


## `lesson 83. CRUD. Service Layer`

### 405.`UserService. Method findAll`
### 406.`UserService. Method findById`
### 407.`UserService. Method create`
### 408.`@Transactional annotation`
### 409.`UserService. Method update`
### 410.`UserService. Method delete`
### 411.`Test UserService functionality`
### 412.`Tips. Method delete`

## `lesson 84. Spring MVC Testing`

### 413.`Аннотация @AutoConfigureMockMvc`
### 414.`Test findAll method`
### 415.`Transactions. spring.jpa.open-in-view property`
### 416.`Test create method`
### 417.`Problem with sending dates in params`

## `lesson 85. Type Converters`

### 418.`spring.mvc.format properties`
### 419.`Аннотация @DateTimeFormat`
### 420.`Интерфейс WebMvcConfigurer`


# `16. Thymeleaf`

## `lesson 86. Thymeleaf Starter. Введение`

### 421.`View Resolvers`
### 422.`Thymeleaf Template Engine Intro`
### 423.`Настройка Thymeleaf в проекте`
### 424.`Использование Thymeleaf`
### 425.`Тестирование функционала`

## `lesson 87. CRUD. View Layer. Часть 1`

### 426.`Создание users.html для метода findAll`
### 427.`Создание user.html для метода findById`
### 428.`Тестирование функционала`
### 429.`Добавление кнопки для метода delete`

## `lesson 88. CRUD. View Layer. Часть 2`

### 430.`Создание registration endpoint`
### 431.`Создание registration.html`
### 432.`Тестирование функционала registration`
### 433.`redirect с сохранением введенных параметров`

## `lesson 89. Filter Query`

### 434.`Add UserFilter - Controller & Service layers`
### 435.`Add UserFilter - users.html`
### 436.`Тестирование функционала`

## `lesson 90. Pagination. Best practices`

### 437.`HTTP endpoints best practices`
### 438.`2 options of pagination implementation`
### 439.`offset-based pagination`
### 440.`PageableArgumentResolver`
### 441.`Building PageResponse`
### 442.`Тестирование функционала`


# `17. Validation Starter`

## `lesson 91. Validation Starter. Введение`

### 443.`Подключение validation starter`
### 444.`Validation annotations`
### 445.`How to use annotations in practice`
### 446.`@Valid & @Validated`
### 447.`BindingResult object`
### 448.`Show validation errors on the page`
### 449.`Тестирование функционала`

## `lesson 92. Custom validator`

### 450.`Main parts in JSR 303 annotations`
### 451.`Custom annotation @UserInfo`
### 452.`Тестирование функционала`
### 453.`Configuration properties validation`
### 454.`Validation groups`

## `lesson 93. @ControllerAdvice & @ExceptionHandler`

### 455.`@ExceptionHandler annotation`
### 456.`Тестирование функционала`
### 457.`@ControllerAdvice annotation`
### 458.`Класс ResponseEntityExceptionHandler`


# `18. REST`

## `lesson 94. REST. Введение`

### 459.`Проблемы Controller API`
### 460.`REST API`
### 461.`REST API Usages`

## `lesson 95. REST. Практика`

### 462.`@ResponseBody & findAll method`
### 463.`findById method`
### 464.`@RequestBody & create method`
### 465.`update method`
### 466.`delete method`
### 467.`@RestController`
### 468.`@RestControllerAdvice`

## `lesson 96. Swagger. API docs`

### 469.`Rest clients`
### 470.`Подключение springdoc`
### 471.`Сгенерированная документация для Rest Controllers`
### 472.`Swagger ui`
### 473.`Swagger annotations`

## `lesson 97. Upload image`

### 474.`Добавление новой колонки image в таблице users`
### 475.`Создание ImageService`
### 476.`upload images from html pages. MultipartFile`
### 477.`Тестирование функционала`

## `lesson 98. Get image`

### 478.`Реализация функционала на уровне service`
### 479.`Отображение картинки на html странице`
### 480.`Реализация функционала на уровне rest controller`
### 481.`Тестирование функционала`
### 482.`Отображение отсутствующей картинки`
### 483.`Класс ResponseEntity`

# `19. Security Starter`

## `lesson 99. Security Starter. Введение`

### 484.`Понятия Аутентификация и Авторизация`
### 485.`Servlet Filters mechanism`
### 486.`Spring Servlet Filters mechanism`
### 487.`Подключение Spring Security Starter`

## `lesson 100. Authentication Architecture`

### 488.`Spring Security Model`
### 489.`Spring Security Authentication Logic`
### 490.`Debug Security filters (default behaviour)`

## `lesson 101. DaoAuthenticationProvider`

### 491.`DaoAuthenticationProvider source code`
### 492.`Add column password into users table`
### 493.`Update entity & enum`
### 494.`Implement UserDetailsService`
### 495.`Тестирование функциональности`

## `lesson 102. Form Login`

### 496.`Default login page source code`
### 497.`Custom login page`
### 498.`Customise SecurityFilterChain`
### 499.`Тестирование функицонала`
### 500.`Class UsernamePasswordAuthenticationFilter`

## `lesson 103. HTTP Basic Authentication`

### 501.`HTTP Basic Authentication principle`
### 502.`HTTP Basic encoder & decoder`
### 503.`Customise SecurityFilterChain to support HTTP Basic`
### 504.`BasicAuthenticationFilter source code`

## `lesson 104. PasswordEncoder`

### 505.`Зачем шифровать пароли`
### 506.`List of password encoders`
### 507.`Implement password encode/decode in the app`
### 508.`Тестирование функционала`

## `lesson 105. Logout`

### 509.`LogoutFilter source code`
### 510.`Customise logout in SecurityFilterChain`
### 511.`Add button Logout on pages`
### 512.`Тестирование функционала`

## `lesson 106. Authorization Architecture`

### 513.`AuthorizationFilter source code and logic`
### 514.`AuthorizationFilter implementations`
### 515.`Customise authorizeHttpRequests in SecurityFilterChain`
### 516.`Тестирование функционала`

## `lesson 107. Method Security`

### 517.`@PreAuthorize annotation`
### 518.`@PostAuthorize annotation`
### 519.`@EnableMethodSecurity annotation`
### 520.`@Secured annotation`
### 521.`Service layer authentication`
### 522.`@PreFilter & @PostFilter annotations`



## `lesson 108. Access to authenticated user`

### 523.`Get current user via SecurityContextHolder`
### 524.`@CurrentSecutiryContext annotation`
### 525.`@AuthenticationPrincipal annotation`
### 526.`Thymeleaf and Spring Security integration`

## `lesson 109. CSRF Filter`

### 527.`Cross-Site Request Forgery`
### 528.`How to solve CSRF problem`
### 529.`Synchronizer Token Pattern`
### 530.`When to use CSRF protection`
### 531.`CsrfFilter source code`
### 532.`How to work with CSRF token`
### 533.`Class CsrfRequestDataValueProcessor`
### 534.`Тестирование функционала`

## `lesson 110. Security Testing`

### 536.`Исправление существующих тестов`
### 537.`spring-security-test dependency`
### 538.`1. Manually define a user in tests`
### 539.`2. @WithMockUser annotation`
### 540.`3. SecurityMockMvcRequestPostProcessor`

## `lesson 111. OAuth 2.0. Теория`

### 541.`Текущий Authentication функционал в приложении`
### 542.`Что такое OAuth 2`
### 543.`Как внедрить OAuth 2 в приложении`
### 544.`OAuth 2 flow types`
### 545.`OAuth 2 Authorization Code Flow`
### 546.`OAuth 2 Implicit Flow`
### 547.`OpenID Connect (OIDC)`

## `lesson 112. OAuth 2.0. Практика`

### 548.`Create a new project in GCP`
### 549.`Configure OAuth 2 in the project`
### 550.`Configure Login Page`
### 551.`Тестирование функционала`

## `lesson 113. OAuth 2.0. Authentication Principle`

### 552.`Add UserInfoEndpoint config in SecurityFilterChain`
### 553.`Create oidcUserService`
### 554.`Тестирование функционала`

## `lesson 114. JWT. JSON Web Token`


### 555.`How to extract info from JWT`
### 556.`JWT header`
### 557.`JWT payload`
### 558.`JWT signature`
### 559.`Code Book`

## `lesson 115. Swagger Authorization`

### 560.`3 options to pass authorization in Swagger`
### 561.`springdoc properties to support OAuth 2`
### 562.`@SecurityScheme configuration`
### 563.`Тестирование функционала`



# `20. i18n & l10n`


## `lesson 116. i18n. MessageSource`

### 564.`spring.messages properties`
### 565.`IntelliJ IDEA UTF-8 settings`
### 566.`Creating MessageRestController`
### 567.`Тестирование функционала`

## `lesson 117. i18n. Thymeleaf`

### 568.`Login page i18n`
### 569.`How to change the language`
### 570.`LocalChangeInterceptor bean`
### 571.`LocaleResolver bean`
### 572.`Тестирование функционала`

# `21. AOP Starter`

## `lesson 118. AOP Starter. Введение`

### 573.`Усложнение кода второстепенной логикой`
### 574.`Crosscutting concerns`
### 575.`AOP terminology`
### 576.`AOP approaches`

## `lesson 119. AOP. Pointcut`

### 577.`spring-boot-starter-aop dependency`
### 578.`AspectJ annotations`
### 579.`@Pointcut`
### 580.`@within`
### 581.`within`
### 582.`this & target`
### 583.`@annotation`
### 584.`args`
### 585.`@args`
### 586.`bean`
### 587.`execution`

## `lesson 120. AOP. @Before Advice`

### 588.`@Before annotation`
### 589.`Тестирование функционала`
### 590.`CglibAopProxy`
### 591.`Proxy interceptors`
### 592.`Spring AOP diagram`
### 593.`AopAutoConfiguration`

## `lesson 121. AOP. JoinPoint. Params`

### 594.`JoinPoint object`
### 595.`Get access to proxy data from advice method params`
### 596.`Тестирование функционала`
### 597.`argNames`

## `lesson 122. AOP. @After Advices`

### 598.`All types of advice`
### 599.`@AfterReturning annotation`
### 600.`@AfterThrowing annotation`
### 601.`@After annotation`
### 602.`Тестирование функционала`

## `lesson 123. AOP. @Around Advice`

### 603.`TransactionInterceptor`
### 604.`@Around annotation`
### 605.`Тестирование функционала`

## `lesson 124. AOP. Best Practices`

### 606.`1. Combine different Pointcut types`
### 607.`2. Move common Pointcuts to separate Aspect`
### 608.`3. Don t use @Around advice everywhere`
### 609.`4. Separate Pointcuts by business logic`
### 610.`Aspects order`


# `22. Заключение`

## `lesson 125. Custom Spring Boot Starter`

### 611.`Create a new Gradle module`
### 612.`Define starter properties`
### 613.`Create Autoconfiguration`
### 614.`File META-INF/spring.factories`
### 615.`Move Aspects from the old to the new module`
### 616.`How to use newly created starter`
### 617.`spring-boot-configuration-processor`
### 618.`Тестирование функционала`

## `lesson 126. Заключение. Путь развития`

619.`Spring Framework Documentation`
620.`List of all main Spring Boot Starters`
621.`Java Road Map`