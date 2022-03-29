# Relatório de PaaS - Grupo 2
## Resumo

Ao longo deste trabalho optamos por fazer, em primeiro lugar, uma contextualização 
do que é o serviço de Platform-as-a-Service, a sua utilidade e especificações. Vamos explorar alguns dos diferentes serviços de PaaS da AWS, fazendo uma pequena contextualização do que consistem. Iremos ainda, analisar o serviço *Amazon Elastic Beanstalk*, desenvolver em maior detalhe o serviço e perceber as suas vantagens.  

## Introdução

Neste trabalho, através da aprendizagem feita ao longo das últimas aulas, complementada com uma pesquisa por vários websites, nomeadamente o website corporativo da Amazon Web Services (AWS) iremos analisar o serviço de nuvem PaaS e perceber quais são as suas vantagens e desvantagens, explorando também os diferentes serviços de PaaS oferecidos pela AWS e fazendo uma análise mais detalhada do serviço *Amazon Elastic Beanstalk*, de modo a perceber a sua aplicação e utilidade.


## O que é PaaS?

PaaS designa o serviço de _Platform-as-a-Service_ e refere-se ao serviço de nuvem que fornece a fundação para os desenvolvedores de _software_ desenharem, desenvolverem e executarem aplicações. Facilita a testagem das mesmas e permite implementar e distribuir essas aplicações sem que tenhamos de nos preocupar com a infraestrutura subjacente de _hardware_ mas também de todo o _software_ necessário para o desenvolvimento das mesmas e inclui serviços de rede, servidores, armazenamento, virtualização, sistemas operativos, middleware, desenvolvimento, monitorização e segurança.

<p align="center">
  <img src="https://blogs.bmc.com/wp-content/uploads/2017/09/saas-vs-paas-vs-iaas-720x675.png"/>
</p>


### Vantagens

O serviço PaaS oferece diversas vantagens, e é orientado para desenvolvedores de _software_. Algumas das suas vantagens são: 
* Menor investimento inicial, representando menor risco ao negócio, permitindo um maior número de “business ventures” com custos incrementais, não sendo necessário investimentos com infraestrutura, _softwares_ básicos como sistemas operativos e _softwares_ adicionais necessários para executar as aplicações necessárias ao ambiente de desenvolvimento;
* Custos de acordo com a utilização da capacidade e poder computacional utilizado;
* Atualizações e novas funcionalidades são disponibilizadas de forma imediata, não sendo necessário dedicar especialistas para estas funções;
* Suporte mais ágil com soluções implementadas rapidamente, onde os problemas encontrados são tratados e a solução é disponibilizada de forma transparente a todos os usuários sem a necessidade de um tratamento individual que retarda a disponibilização da correção;
* A empresa pode focar os seus esforços no seu negócio, sem despender energia com a escolha e manutenção de sistemas;
* Aumento da disponibilidade e segurança dos dados. Disponibilizando procedimentos de _backup_, restauração e planos de contingência para o caso da perda de informações ou falha de _hardware_.

### Desvantagens

Nem tudo são vantagens, e existem algumas limitações/desvantagens de optar pelo serviço de PaaS. Algumas das desvantagens são: 
* Dependência das capacidades do provedor de nuvem, a nível de rapidez, fiabilidade e funcionalidades. 
* Problemas de compatibilidade aquando a incorporação da infraestrutura no novo ambiente.
* Riscos de segurança derivados da disponibilização num ambiente público.

## AWS Beanstalk

<p align="justify">
  A Amazon Web Services abrange mais de cem serviços, cada um com a sua área específica de funcionalidade. Esta variedade, embora ofereça uma enorme flexibilidade na forma como pode ser gerida a infraestrutura AWS, pode tornar-se difícil e complicado perceber quais os serviços a utilizar e como os acomodar.
</p>
<p align="justify">
Com o Elastic Beanstalk, os desenvolvedores de <i>software</i> podem implementar e gerir as suas aplicações na nuvem AWS, sem ter de se preocupar com administração de servidores e sistemas. Desta forma, permite reduzir a complexidade de gestão sem restringir possibilidades de escolha ou controlo. Simplesmente, faz-se o <i>upload</i> da aplicação, e o Elastic Beanstalk, automaticamente,  trata dos detalhes dos servidores e da sua capacidade, equilíbrio de carga, escalonamento e monitorização do estado da aplicação.
</p>
<p align="justify">
O Elastic Beanstalk suporta aplicações desenvolvidas em Go, Java, .NET, Node.js, PHP, Python e Ruby. Sendo esta uma ferramenta para implementação de aplicações em computação em nuvem da AWS, tem acesso a outras tecnologias/serviços. Nas configurações de uma implementação de uma aplicação no Elastic Beanstalk, o programador tem acesso ao AWS EC2, Amazon S3, Amazon RDS, AutoScaling e Elastic Load Balancing, entre outros.
</p>
<p align="justify">
De um forma simplificada, o programador cria um ficheiro .zip utilizando o Elastic Beanstalk, este cria toda a infraestrutura necessária para implementar a aplicação, desde os servidores a bases de dados, até utilizando AutoScaling e Elastic Load Balancing, dependendo das nossas preferências.
</p>
<p align="justify">
A título de exemplo, algumas das funções de gestão fornecidas pelo serviço são: implementação de uma versão nova de uma aplicação (ou até mesmo reverter para uma versão anterior); acesso a resultados reportados pelo serviço de monitorização <i>CloudWatch</i>; notificações de email quando o estado da aplicação implementada muda ou servidores são adicionados ou removidos; e acesso aos ficheiros de login sem que seja necessário entrar nos servidores da aplicação. 
</p>

<p align="justify">
No que toca ao preço deste serviço, este é 100% gratuito. No entanto, o utilizador terá de pagar pelo uso dos servidores EC2, tal como o armazenamento e tudo o resto, como se estivesse a utilizar qualquer outro serviço de computação em nuvem da AWS.
</p>

Sintetizando, o Elastic Beanstalk oferece:

* Uma forma rápida e simples de implementar aplicações

* Possibilidade de maior investimento de tempo no desenvolvimento de aplicações

* Acesso a todos os serviços de computação em nuvem da AWS.

* Controlo sobre os recursos utilizados

* Modelo de pagamento simplificado



## Outros serviços oferecidos

A Amazon disponibiliza vários serviços PaaS no seu catálogo dos quais se destacam os seguintes:

*	**AWS Lambda:** serviço de computação que permite executar código para praticamente qualquer tipo de aplicação ou serviço de _backend_ sem se preocupar com servidores. Pode ser accionado a partir de mais de 200 serviços da AWS e aplicações SaaS e só se paga pelo que se usar;
*	**Amazon RDS (Amazon Relational Database Service):** coleção de serviços gerenciados que facilita a configuração, operação e escalabilidade de bancos de dados na nuvem;
*	**AWS Cloud9:** IDE que permite escrever, executar e depurar código usando apenas um _browser_ e inclui um editor de código, um depurador e um terminal. O Cloud9 possui ferramentas essenciais para linguagens de programação comuns, tais como JavaScript, Python e PHP, entre outras, para que não seja necessário instalar arquivos ou configurar a máquina de desenvolvimento para iniciar novos projetos;
*	**Amazon Lightsail:**  oferece instâncias de servidor privado virtual fáceis de usar, _containers_, armazenamento e bases de dados;
*	**AWS Robomaker:** serviço de simulação baseado em nuvem que permite que os desenvolvedores de robótica executem, escalem e automatizem a simulação sem gerenciar nenhuma infraestrutura;
*	**Amazon API Gateway:** permite que desenvolvedores criem, publiquem, mantenham, monitorem e protejam APIs em qualquer escala com facilidade. Administra todas as tarefas envolvidas na receção e processamento de centenas de milhares de chamadas de API em simultâneo, inclusive gerenciamento de tráfego, controlo de autorização e acesso, monitorização e gerenciamento de versões;
*	**AWS Amplify:** conjunto de ferramentas e recursos especialmente desenvolvidos para que desenvolvedores _frontend_ de plataformas móveis e Web criem aplicações completas de forma rápida e fácil na AWS;
*	**AWS Codestar:** disponibiliza uma interface que viabiliza uma fácil gestão de atividades de desenvolvimento de _software_ num só lugar, permitindo o desenvolvimento, compilação e rápida implementação de aplicações na AWS.
