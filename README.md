# spring-cloud-stream-rabbit-functional
  # RabbitMQ Setup
  - docker pull rabbitmq
  - docker run -d --hostname my-rabbit --name myrabbit -e RABBITMQ_DEFAULT_USER=admin -e RABBITMQ_DEFAULT_PASS=123456 -p 5672:5672 -p 15672:15672 rabbitmq:3-management

![ppc](https://ichi.pro/assets/images/max/724/1*Y7e_0n81_Mev69sunSDxBg.png)
