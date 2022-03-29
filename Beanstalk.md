## AWS Beanstalk

<p align="justify">
A Amazon Web Services abrange mais de cem serviços, cada um com a sua área específica de funcionalidade. Esta variedade, embora ofereça uma enorme flexibilidade na forma como pode ser gerida a infraestrutura AWS, pode-se tornar difícil e complicado, perceber quais os serviços a utilizar e como os acomodar.
</p>
<p align="justify">
Com o Elastic Beanstalk, os desenvolvedores de software podem implementar e gerir as suas aplicações na nuvem AWS, sem ter de se preocupar com administração de servidores e sistemas. Desta forma, permite reduzir a complexidade de gestão sem restringir possibilidades de escolha ou controlo. Simplesmente, faz-se o upload da aplicação, e o Elastic Beanstalk, automaticamente,  trata dos detalhes dos servidores e da sua capacidade, equilíbrio de carga, escalonamento e monitorização do estado da aplicação.
</p>
<p align="justify">
O Elastic Beanstalk suporta aplicações desenvolvidas em Go, Java, .NET, Node.js, PHP, Python e Ruby. Sendo esta uma ferramenta para implementação de aplicações em computação em nuvem da AWS, tem acesso a outras tecnologias/serviços. Nas configurações de uma implementação de uma aplicação no Elastic Beanstalk, o programador tem acesso ao AWS EC2, Amazon S3, Amazon RDS, Auto Scaling e Elastic Load Balancing, entre outros.
</p>
<p align="justify">
De um forma simplificada, o programador cria um ficheiro *.zip*, utilizando o Elastic Beanstalk, este cria toda a infraestrutura necessária para implementar a aplicação, desde os servidores, a bases de dados, até utilizando AutoScaling e Elastic Load Balancing, dependendo das nossas preferências.
</p>
<p align="justify">
A título de exemplo, algumas das funções de gestão fornecidas pelo serviço são: implementação de uma versão nova de uma aplicação (ou até mesmo reverter para uma versão anterior); acesso a resultados reportados pelo serviço de monitorização CloudWatch; notificações de email quando o estado da aplicação implementada muda ou servidores são adicionados ou removidos; e acesso aos ficheiros de login sem que seja necessário entrar nos servidores da aplicação. 
</p>

<p align="justify">
No que toca ao preço deste serviço, este é 100% gratuito. No entanto, o utilizador terá de pagar pelo uso dos servidores EC2, tal como o armazenamento e tudo o resto, como se estivesse a utilizar qualquer outro serviço de computação em nuvem da AWS.
</p>

**Sintetizando o Elastic Beanstalk oferece:**

* Uma forma rápida e simples de implementar aplicações

* Possibilidade de maior investimento de tempo no desenvolvimento de aplicações

* Acesso a todos os serviços de computação em nuvem da AWS.

* Controlo sobre os recursos utilizados

* Modelo de pagamento simplificado
