## Облачные вычисления

### Что такое облачные вычисления?

Облачные вычисления - это предоставления компьютерных ресурсов для пользователя через internet подключение.

![image](https://user-images.githubusercontent.com/47852430/133871768-a05705c3-4fe5-475d-a708-db08ebd87b84.png)

Вместо того, что бы самому инвестрировать в оборудование, покупать нужное ПО, обслуживать и поддерживать это, на что уходят большие затраты, еще можно и потерять данные, для этого надо делать потсоянные бекапы и я для решения этих проблем появились облачные вычисления, оно помогает управлять вашему ПО. 
Нужны данные? Есть различные облачные сервисы, которые помогут и в случае проблемы, сами заменят жесткие диски, или, как пример, контактная книга, которая раньше копировалась вручную на каждый телефон - теперь синхронизирована через гугл, нужно только зайти в свой аккаунт.

### Обзор облачных сервисов

На данный момент облачный сервис делится на 3 вида:

- Ifrastructure as a Service (IaaS)
- Platform as a Service (PaaS)
- Software as a Service (SaaS)

![image](https://user-images.githubusercontent.com/47852430/133871878-f06cd3ad-ff39-44c5-844c-0235e68bfeb1.png)

![image](https://user-images.githubusercontent.com/47852430/133871932-85576826-ccc9-44da-86ab-73dad8dd8eee.png)

###  Infrastructure as a Service (IaaS)

IaaS означает "Инфраструктура как услуга". Обычно провайдер такого сервиса предоставит вам то, что связано с сетью, компьютером или место хранения данных. Вы можете арендовать сервер с нужными вам характеристиками, который будет обслуживаться провайдером в его датацентре, со всеми нужными для этого условиями.

IaaS используется не конечным пользователем, а тем, кто хочет развернуть свое программное обеспечение.

### Platform as a Service (PaaS) 

PaaS означает "Платформа как услуга". Это уровень уже выше, чем IaaS. В случае с IaaS вам предоставляется сервер, но что бы развернуть веб приложение вам нужно установить многие связанные вещи, например такие как Web Server, Database, данны установки зависят от вашего ПО и после завершения установок, вы можете развернуть ваше приложение.

Вам предоставляется необходимая платформа для развертывания вашего веб приложения. Есть многие провайдеры PaaS, которые не позволяют вам использовать свой сервер, а предоставляют вам платформу, что бы вы развернули ваше приложение и использовали общий сервер с другими людьми. Это уменьшает ваши затраты, но могут возникать риски неавторизированных доступов к вашим данным.

### Software as a Service (SaaS)

SaaS - програмое обеспечение как услуга, самый высокий уровень из всех видов облачных сервисов. Это продукт, который оперируется и управляется провайдером. Предоставляет ПО и приложение, работающие в internet и могут быть использованы конечными пользователями. 

Например WebEmail, такие как Mail, Gmail является совершенными продуктом, вы можете сразу им пользоваться без необходимости настраивать свой почтовый сервер. 
Или Google Docs, Microsoft Online предоставляет продукт, которым можно пользоваться сразу.

![image](https://user-images.githubusercontent.com/47852430/133871957-3e5148ee-af5b-42b3-b276-c98c26815595.png)

### Плюсы облачных вычисленияй

- Экономия затрат

Вместо оборудования и поддержки своей платформы, сервиса или сервера вы можете использовать уже готовый

- Удобство

Быстрое получение доступа, главное иметь internet и вы независимы от программного или аппаратного обеспечения в использовании.

- Безопасность и непрерывность

Если ваш жесткий диск сломается, утеряется, возможно вы потеряете все данные, если вы еще не делаете бекапы, а в случае с провайдером - он позаботиться о ваших данных. Если сервер упадет - провайдер оперативно его восстановит.

### Минусы облачных вычислений

- Конфиденциальность

Достаточно ли вы доверяете провайдеру, что бы хранить там самые-самые конфиденциальные данные? А вдруг он продаст их конкуренту?

- Беспокойство о downtme

Ни один провайдер не может гарантировать, что их сервер будет работать непрерывно 100% времени и никогда не остановиться.

## С чего начались облачные вычисления?

В 2007 году Netflix дистрибютировал свой миллиардный по счету DVD и в том же году Netflix провел реструктуризацию всех бизнес моделей, несмотря на большой успех в дистрибуцие DVD через почту, они понимают, что рано или поздно будут заменены видео по интернету, поэтому решили обновиться. А за год до этого, Amazon объявила о освем новом проекте, что не совсем связано с индустрией их бизнеса - "облачные высиления", потратили очень много денег на инвестиции в сервера, сервис котороый они открыли - облачные хранилище (Amazon S3), и Netflix решили стать партнером Amazon и использовать их сервера для своей стриминговой платформы.

Netflix стал пионером в технологиях программного обеспечения для облачных вычислений, делают то, что никто не делал до этого. Почти все у них на Amazon Web Service (AWS). На тот момент AWS не уделял внимание компонентам ПО, поэтому они должны были сами изобрести ПО, что бы их приложение работало в среде облаков. 

Архитектура Netflix
![image](https://user-images.githubusercontent.com/47852430/134100837-7fda233a-851b-42e7-ab04-096c7544b755.png)

Netflix решил, что их инновации могут оказаться полезными обществу и решили открыть их технологии для работы с облачными приложениями, после чего сразу получили внимание от группы разработчиков Spring. Сразу же изучили Netflix OSS (Netflix Open Source Software) чтобы оценить, нужно ли его реструктуризировать или нет и поняли, что оно очень хорошее. Но нужно сделать так, что бы его можно было использовать для целей пользователей, тк основная цель Netflix OS была для работы Netflix. Поэтому группа разработчиков Spring сфокусировались на то, чтобы программистам было легче использовать библиотеки Netflix.

![image](https://user-images.githubusercontent.com/47852430/134101141-55677c0f-ff99-4877-b4c2-0363083fcd7a.png)

------

## Spring Cloud Overview

Spring как платформа построенная для разработки веб приложений на Java. Впервые представлена в 2004, в 2006 появились подпроекты, каждый подпроект фокусируется на разную индустрию. 

![image](https://user-images.githubusercontent.com/47852430/134102718-8cf68c71-a7c5-4f2d-b165-4f564fd4b7ad.png)

Spring IO (Spring Integration Objects) является названием для семьи подпроектов Spring. Она считается как зонт и подпроекты находятся под этим зонтом. Spring Cloud является подпроектов в зонте Spring IO и сам является зонтом

![image](https://user-images.githubusercontent.com/47852430/134102983-ee7f6c40-84d3-4e0a-b1bc-c3309b7cb839.png)

Spring Cloud стоит быть созданным с помощью Spring Boot

### Паттерны Spring Cloud 

![image](https://user-images.githubusercontent.com/47852430/134103035-cd0de4d8-2b72-4d7e-9e27-8d0eba4731ba.png)

------

## Spring Cloud Config Server 

![image](https://user-images.githubusercontent.com/47852430/134276063-bc29e249-6b5e-4aac-9064-b3b0a68a7586.png)

Зачем нужен конфиг сервер в распределенном приложении? Что бы не хардкодить конфигурационные файлы в приложении, потому что тогда придется пересобирать и разворачивать заного всю среду, это является сложной задачей в среде распределенного приложения.

Идея разрешения проблемы - это нужно иметь приложение, управляющее конфигуряциями для другим приложений, которое работает независимо на сервере.

![image](https://user-images.githubusercontent.com/47852430/134276402-e3471cd2-5516-4e72-8b63-c24181ae389b.png)

Когда вы меняете конфиги на конфиг-сервере, вы хотите оповестить об этом клиентов и Spring Cloud Bus предоставляет механизм оповещения клиентов, что есть изменение и требует обновить новую информацию. 

![image](https://user-images.githubusercontent.com/47852430/134276529-d368a99a-e7f7-408b-aa8c-9f5c7271619f.png)

### Как сохраняет данные Config Server? 

Есть 2 способа
  - Сохранить на жестком диске сервера
  - Использовать Git или SVN

### Создание Config Server

Создаем Spring Boot приложение с зависимостью Spring Cloud Config Server

```java
@EnableConfigServer
@SpringBootApplication
public class SpringCloudConfigServerApplication {
  public static void main(String[] args) {
    SpringApplication.run(SpringCloudConfigServerApplication.class, args);
  }
}
```

В application.properties выставляем путь к конфигам.   
      
        server.port=8888
        spring.cloud.config.server.git.uri=https://github.com/firsss21/spring-cloud-config-git-repo-example.git

        #system file
        #spring.profiles.active=native
        #spring.cloud.config.server.native.searchLocations=C:/Users/firsss/Desktop/config

И перейдя по http://localhost:8888/spring-cloud-hello-service.properties получим наш конфиг

## Spring Cloud Config Client

Как приложение может получить свою информацию конфигурации, управляемое на Config-Server?

В нашем Spring Boot приложении с зависимостью Spring Cloud Config Server, в файле properties/bootstrap.properties выставляем адресс Config Server и application name.

      spring.application.name = app
      spring.cloud.config.uri=http://host-config-server:8888
      
Для такого названия приложения нам нужен файл app.properties среди хранимых нашим Config Server конфигах.

И теперь мы можем получать конфигурационные переменные как и обычно, через `@Value("${spring.datasource.url}")`, только для начала вешаем на наш Bean @RefreshScope (Аннотация @RefreshScope используется для загрузки значения свойств конфигурации с сервера конфигурации, любой Spring Bean аннотированный с помощью @RefreshScope будет обновлен во время запуска (runtime))

------

## Service Registration

При создании распределенной системы, которая сосотит из разных приложений, независимо работяющий на разных серверах, вам нужно что бы данные приложения могли разговаривать друг с другом, для этого они должны **найти** друг друга. Когда они найдут друг друга, они смогут взаимодействовать, поэтому нужен какой-то сервер, помогающий этим приложениям зарегистрировать свое существование. 

![image](https://user-images.githubusercontent.com/47852430/134442546-fd9926d5-2039-42ed-898b-04e6b2102824.png)

Все приложения в распределенной системе должны зарегистрироваться с **Service Registration**
![image](https://user-images.githubusercontent.com/47852430/134442642-935caf4b-96f5-46af-b902-cb67f06e2276.png)

Есть несколько технологий для **Service Registration**, Spring Cloud предоставляет следующие решения:
- Eureka
- Zookepeer
- Cloud Foundry
- Consul

### Spring Cloud Eureka Server
  
- Cоздадим **Service Registration** используя **Spring Cloud Eureka Server**
- Запустим и посмотрим **Eureka Monitor**
- Создание реплик приложения для демонстрации работы распределенной системы

- **Создаем Service Registration**

Запускаем Spring Boot приложение с зависимостью Eureka Server. Помечаем дополнительной аннотацией `@EnableEurekaServer`

```java
@EnableEurekaServer
@SpringBootApplication
public class EurekaserverApplication {
public static void main(String[] args) {
  SpringApplication.run(EurekaserverApplication.class, args);
}
}
```

```yml
spring:
  profiles: default
server:
  port: 9999
eureka:
  instance:
    hostname: eureka-server.ru
  client:
    registerWithEureka: false
    fetchRegistry: false
    serviceUrl:
      defaultZone: http://${eureka.instance.hostname}:${server.port}/eureka/
      ---
spring:
  profiles: one
  application:
    name: eureka-server-clustered
server:
  port: 9001  
eureka:
  instance:
    hostname: eureka-server-one.ru    
  client:
    registerWithEureka: true
    fetchRegistry: true        
    serviceUrl:
      defaultZone: http://eureka-server-two.ru:9002/eureka/,http://eureka-server-three.ru:9003/eureka/

---
spring:
  profiles: two
  application:
    name: eureka-server-clustered
server:
  port: 9002
eureka:
  instance:
    hostname: eureka-server-two.ru      
  client:
    registerWithEureka: true
    fetchRegistry: true        
    serviceUrl:
      defaultZone: http://eureka-server-one.ru:9001/eureka/,http://eureka-server-three.ru:9003/eureka/

---
spring:
  profiles: three
  application:
    name: eureka-server-clustered   
server:
  port: 9003
eureka:
  instance:
    hostname: eureka-server-three.ru    
  client:
    registerWithEureka: true
    fetchRegistry: true    
    serviceUrl:
      defaultZone: http://eureka-server-one.ru:9001/eureka/,http://eureka-server-two.ru:9002/eureka/   
       
```
- **Eureka Monitor**
Eureka Monitor (Eureka Монитор) позволяет вам видеть список приложений работающих и зарегистрированных с данным Eureka Server, одновременно позволяет вам видеть реплики данного приложения, которые работают на распределенной системе

Переходим по ссылке http://localhost:9999/

- **Создание реплик приложения**

Запускаем реплики приложения для демонстрации работы распределенной системы, конфиги которых описаны в **yml** конфиге,

```bash
java -jar -Dspring.profiles.active=one target/eurekaserver-0.0.1-SNAPSHOT.jar
java -jar -Dspring.profiles.active=two target/eurekaserver-0.0.1-SNAPSHOT.jar
java -jar -Dspring.profiles.active=three target/eurekaserver-0.0.1-SNAPSHOT.jar
```
Если выполняем локально и для примера, то дополнительно нужно обновить файл **hosts**

![image](https://user-images.githubusercontent.com/47852430/134612398-39609442-20e9-4196-b94f-2948a286ccfe.png)

Теперь перейдя по новым хостам мы можем увидеть созданные нами репликации и их статус.

![image](https://user-images.githubusercontent.com/47852430/134612620-232c2343-929b-4ffb-8eb9-0c426c181c5d.png)

## Spring Cloud Discovery Eureka Client

Создадим приложение, которое будет являться клиентом (**Eureka client**) нашего **Service Registration **(Eureka Server)**, после чего наш **Eureka Client** сможет получить других клиентов, подключенных к сервису и мы сможем взаимодействовать с ним через наше приложение.

Запускаем **Spring Boot** приложение с зависимостью **Eureka Discovery Client**. Помечаем дополнительной аннотацией `@EnableEurekaServer`

```java
@EnableEurekaClient
@SpringBootApplication
public class EurekaClientApplication {
    public static void main(String[] args) {
        SpringApplication.run(EurekaClientApplication.class, args);
    }
}

```

Создаем в конфиге yml несколько реплик одного приложения 
```yml

spring:
  application:
    name: TEST-SERVICE

---
eureka:
  instance:
    appname: TEST-SERVICE
  client:
    fetchRegistry: true
    serviceUrl:
      defaultZone: http://eureka-server-one.ru:9001/eureka
server:
  port: 7000

---
spring:
  profiles: test-replica1
eureka:
  instance:
    appname: TEST-SERVICE
  client:
    fetchRegistry: true
    serviceUrl:
      defaultZone: http://eureka-server-one.ru:9001/eureka
server:
  port: 8001

---
spring:
  profiles: test-replica2
eureka:
  instance:
    appname: TEST-SERVICE
  client:
    fetchRegistry: true
    serviceUrl:
      defaultZone: http://eureka-server-one.ru:9001/eureka
server:
  port: 8002

---
spring:
  profiles: test-replica3
eureka:
  instance:
    appname: TEST-SERVICE
  client:
    fetchRegistry: true
    serviceUrl:
      defaultZone: http://eureka-server-one.ru:9001/eureka
server:
  port: 8003

---
spring:
  profiles: test-replica4
eureka:
  instance:
    appname: TEST-SERVICE
  client:
    fetchRegistry: true
    serviceUrl:
      defaultZone: http://eureka-server-one.ru:9001/eureka
server:
  port: 8004

---
spring:
  profiles: test-replica5
eureka:
  instance:
    appname: TEST-SERVICE
  client:
    fetchRegistry: true
    serviceUrl:
      defaultZone: http://eureka-server-one.ru:9001/eureka
server:
  port: 8005
```

Собираем и запускаем все реплики

```bash
mvn package
java -jar -Dspring.profiles.active=test-replica1 target/eureka-client-0.0.1-SNAPSHOT.jar
java -jar -Dspring.profiles.active=test-replica2 target/eureka-client-0.0.1-SNAPSHOT.jar
java -jar -Dspring.profiles.active=test-replica3 target/eureka-client-0.0.1-SNAPSHOT.jar
java -jar -Dspring.profiles.active=test-replica4 target/eureka-client-0.0.1-SNAPSHOT.jar
java -jar -Dspring.profiles.active=test-replica5 target/eureka-client-0.0.1-SNAPSHOT.jar
```
Заходим на наш **Eureka Server** и видим все запущенные реплики.
![image](https://user-images.githubusercontent.com/47852430/134833726-4334f06e-7f87-4ca1-bb41-56564dc005a6.png)


## Spring Cloud балансировка

Что такое **Load Balancer**? Если у вашего распределенной системы множество приложений, работающих на разных компьютеах и количество пользователей большое - то приложение обычно создает разные реплики, которые работают на разных компьютерах. В это время появляется **Load Balancer** (Балансировка нагрузки), который помогает распределить входящий траффик поравну между репликами. 

![image](https://user-images.githubusercontent.com/47852430/134837029-98e38d27-6626-49a6-8a23-0be6fe7210bb.png)

### Балансировка на стороне сервера (Server Side Load Balancer)

Балансировка нагрузки расположена на стороне сервера, когда запросы поступают от клиента они приведут к балансировке и определит один сервер для этого запроса. Самый простой алгоритм используемый балансировщиком - случайное распределение. 
Почти все балансировки нагрузки являются аппаратным обеспечением, инегрирующим программным, которые контролируют балансировку нагрузки. 

![gif](https://s1.o7planning.com/ru/11739/images/15621620.gif)

Например: Nginx

### Балансировка на стороне клиента (Client Side Load Balancer)

Когда балансировка нагрузки находится на стороне **клиента**, она сама решает какому серверу отправить запрос, основываясь на некоторых критериях.

![image](https://user-images.githubusercontent.com/47852430/134837154-37dd6ab7-30fd-409e-a991-799dfdda4432.png)

Балансировка на клиентской стороне обычно отправляет запросы к серверам одной зоны (Zone), или имеет быстрый ответ.

Сервера отличаются по следующим критериям:

- Доступность (Avialability)
- Производительность (Performance)
- Месторасположение. Сервера могут быть в разных странах

### Netflix Ribbon

**Ribbon** это часть семьи Netflix Open Source Software, который является библиотекой, предоставляющей балансировку на клиентской стороне. 
Т.к он является частью **Netflix OSS** то он может автоматически взимодействовать с **Netflix Service Discovery (Eureka)**. 

**Spring Cloud** создал **API**, чтоб помочь легко использовать библиотеки **Ribbon**

Главные принципы, связанные с **Ribbon**:

- **Список серверов.**

Список серверов, которые могут предоставить определенную услугу для 1 **Client**.
Например: Client 1 нужна информация про погоду, то тогда будет список серверов, которые могут предоставить данную информацию. Данный список включает сервера напрямую конфигурированные в приложении Client и сервера, которые Client нашел.

- **Фильтрованный список серверов**

После получения списка серверов, этот фильтр отбросит медленные или недоступные сервера.

- **Балансировка нагрузки**

Ribbon - балансировка нагрузки, является компонентом, расположенном на стороне клиента, он решает как сервер будет вызван (из списка фильтрованных серверов).

Т.е. имеются некоторые стратегии для решения. Обычно основываются на **Rule Component** что бы создать настоящее решение.

По умолчанию **Spring Cloud Ribbon** использует стратегию **ZoneAwareLoadBalancer**, которая направляет на сервера в одной зоне с клиентом.

**Rule Component** - умный модуль, который создает решение **Вызывать или не вызывать**. По умлочанию Spring Cloud использует правило **ZoneAvoidanceRule**.

- **Ping**

**Ping** - способ, который использует **Client** для быстрой проверки работает ли на тот момент сервер или нет. Поведение по умолчанию у Spring Cloud это уполномочить **Eureka** автоматически проверять данную информацию, но Spring Cloud позволяет кастомизировать проверку по вашему.

## Создадим приложение

Создадим приложение, где **XYZ service** будет **Discovery Client (Eureka CLient)** и вызовет **ABC Service**. На приложении **XYZ Service** будем использовать **балансировку нагрузки**.

Для этого создадим 3 приложения:

- XYZ Service
- Service Registration (Eureka Server)
- ABC Service

Для демонстрации балансера, создадим 5 реплик ABC Service.

![image](https://user-images.githubusercontent.com/47852430/135018983-064781ae-c55c-4dc5-b6d8-de275194a791.png)

