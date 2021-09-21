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

## Spring Cloud Overview

Spring как платформа построенная для разработки веб приложений на Java. Впервые представлена в 2004, в 2006 появились подпроекты, каждый подпроект фокусируется на разную индустрию. 

![image](https://user-images.githubusercontent.com/47852430/134102718-8cf68c71-a7c5-4f2d-b165-4f564fd4b7ad.png)

Spring IO (Spring Integration Objects) является названием для семьи подпроектов Spring. Она считается как зонт и подпроекты находятся под этим зонтом. Spring Cloud является подпроектов в зонте Spring IO и сам является зонтом

![image](https://user-images.githubusercontent.com/47852430/134102983-ee7f6c40-84d3-4e0a-b1bc-c3309b7cb839.png)

Spring Cloud стоит быть созданным с помощью Spring Boot

### Паттерны Spring Cloud 

![image](https://user-images.githubusercontent.com/47852430/134103035-cd0de4d8-2b72-4d7e-9e27-8d0eba4731ba.png)


## Spring Cloud Config Server 
## Spring Cloud Config Client
## Spring Cloud Eureka Server
## Spring Cloud Discovery Eurika Client
## Spring Cloud балансировка

