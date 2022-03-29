# Trabalho-de-PaaS
## Resumo

Ao longo deste trabalho optamos por fazer, em primeiro lugar, uma contextualização 
do que é o serviço de Platform-as-a-Service, a sua utilidade e especificações. Vamos explorar alguns dos diferentes serviços de PaaS da AWS, fazendo uma pequena contextualização do que consistem. Iremos ainda, analisar o serviço da *Amazon Elastic Beanstalk*, desenvolver em maior detalhe o serviço e perceber as suas vantagens.  

## Introdução

Neste trabalho, através da aprendizagem feita ao longo das últimas aulas, complementada com uma pesquisa por vários websites, nomeadamente o website corporativo da AWS  iremos analisar o serviço de nuvem PaaS, percebendo quais são as suas vantagens e desvantagens. Explorando, também, os diferentes serviços de PaaS oferecidos pela Amazon Web Services (AWS), e fazendo uma análise mais detalhada do serviço *Amazon Elastic Beanstalk*, de modo a perceber a sua utilidade e aplicação.


## O que é PaaS?

PaaS designa o serviço de Platform-as-a-Service, refere-se ao serviço de nuvem que fornece a fundação para os desenvolvedores de software desenharem, desenvolverem e executarem aplicações. Facilita a testagem das mesmas e permite implementar e distribuir essas aplicações sem que tenhamos de nos preocupar com a infraestrutura subjacente de hardware, mas também de todo o software necessário para o desenvolvimento das mesmas, inclui serviços de rede, servidores, armazenamento, virtualização, sistemas operativos, middleware, desenvolvimento, monitorização, segurança.

![img](https://blogs.bmc.com/wp-content/uploads/2017/09/saas-vs-paas-vs-iaas-1024x953.png)

### Vantagens

O serviço PaaS oferece diversas  vantagens, e é orientado para desenvolvedores de software. Algumas das suas vantagens são: 
* Menor investimento inicial, representando menor risco ao negócio, permitindo um maior número de “business ventures” com custos incrementais, não sendo necessário investimentos com infra-estrutura, softwares básicos como sistemas operacionais e softwares adicionais necessários para executar as aplicações necessárias ao ambiente de desenvolvimento. 
* Custos de acordo com a utilização da capacidade e poder computacional utilizado. 
* Atualizações e novas funcionalidades são disponibilizadas de forma imediata, não sendo necessário dedicar especialistas para estas funções.
* Suporte mais ágil com soluções implementadas rapidamente, onde os problemas encontrados são tratados e a solução é disponibilizada de forma transparente a todos os usuários sem a necessidade de um tratamento individual que retarda a disponibilização da correção.
* A empresa pode focar seus esforços no seu negócio, sem despender energia com a escolha e manutenção de sistemas.
* Aumento da disponibilidade e segurança dos dados. Disponibilizando procedimentos de backup, restauração e planos de contingência para o caso da perda de informações ou falha de hardware.

### Desvantagens

Nem tudo são vantagens, e existem algumas limitações/desvantagens de optar pelo serviço de PaaS. Algumas das desvantagens são: 
* Dependência das capacidades do provedor de nuvem, a nível de rapidez, fiabilidade e funcionalidades. 
* Problemas de compatibilidade aquando a incorporação da infraestrutura no novo ambiente.
* Riscos de segurança derivados da disponibilização num ambiente público.

## Serviços oferecidos

A Amazon disponibiliza imensos serviços no seu catálogo dos quais se destacam os seguintes referentes a PaaS:

*	**AWS Lambda:** serviço de computação que permite executar código para praticamente qualquer tipo de aplicação ou serviço de backend sem se preocupar com servidores. Pode ser accionado a partir de mais de 200 serviços da AWS e aplicações SaaS e só se paga pelo que se usar;
*	**Amazon RDS (Amazon Relational Database Service):** coleção de serviços gerenciados que facilita a configuração, operação e escalabilidade de bancos de dados na nuvem;
*	**AWS Cloud9:** IDE que permite escrever, executar e depurar código usando apenas um browser e inclui um editor de código, um depurador e um terminal. O Cloud9 possui ferramentas essenciais para linguagens de programação comuns, tais como JavaScript, Python e PHP, entre outras, para que não seja necessário instalar arquivos ou configurar a máquina de desenvolvimento para iniciar novos projetos;
*	**Amazon Lightsail:**  oferece instâncias de servidor privado virtual fáceis de usar, containers, armazenamento e bancos de dados;
*	**AWS Robomaker:** serviço de simulação baseado em nuvem que permite que os desenvolvedores de robótica executem, escalem e automatizem a simulação sem gerenciar nenhuma infraestrutura;
*	**Amazon API Gateway:** permite que desenvolvedores criem, publiquem, mantenham, monitorem e protejam APIs em qualquer escala com facilidade. Administra todas as tarefas envolvidas na receção e processamento de centenas de milhares de chamadas de API em simultâneo, inclusive gerenciamento de tráfego, controlo de autorização e acesso, monitorização e gerenciamento de versões;
*	**AWS Amplify:** conjunto de ferramentas e recursos especialmente desenvolvidos para que desenvolvedores frontend de plataformas móveis e Web criem aplicações completas de forma rápida e fácil na AWS;
*	**AWS Codestar:** disponibiliza uma interface que viabiliza uma fácil gestão de atividades de desenvolvimento de software num só lugar, permitindo o desenvolvimento, compilação e rápida implementação de aplicações na AWS.
