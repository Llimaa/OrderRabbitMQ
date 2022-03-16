# OrderRabbitMQ

**Mensageria com RabbitMQ e ASP.NET Core - Parte #1**

Integração com RabbitMQ. Nesse exemplo vamos construir uma API representando a funcionalidade de cadastro de pedido em um E-commerce.
Ao acessar o endpoint de cadastro de pedidos, vamos postar uma mensagem para fila do RabbitMQ;

Já para realizar o consumo do evento da fila, criamos um BackgroundService, esse BackgroundService vai ficar ouvindo nossa fila do RabbitMQ 
e consumindo os novos evento.

Acesse o artigo em: https://marcoslimadefatima.medium.com/
