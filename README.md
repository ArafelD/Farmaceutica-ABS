# 💊 Abstergo Industries 💊
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/devsuperior/sds1-wmazoni/blob/master/LICENSE) 

# Sobre o projeto 📋

Este relatório apresenta o processo de implementação de ferramentas na empresa [Abstergo Industries], realizado por [Rafael Dias]. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

### RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS :chart_with_upwards_trend: ###

Data: [20/02/2024] Empresa: Abstergo Industries

Responsável: [Rafael Dias]

# Descrição do Projeto :pushpin:
## Amazon cloud AWS
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:



## Etapa 1 - [Computação em AWS] - [Segurança, incorporada] 
  # [Descrição]
  
- Instâncias (máquinas virtuais)
- Capacidade computacional segura (servidores virtuais) e redimensionável na nuvem
- Amazon Elastic Compute Cloud (EC2)
- Execute cargas de trabalho tolerantes a falhas com desconto de até 90%
- Spot do Amazon EC2
- Adicione ou remova automaticamente a capacidade de computação para atender às mudanças na demanda
- Amazon EC2 Autoscaling
- Plataforma em nuvem fácil de usar que oferece tudo o que você precisa para criar um aplicativo ou site
- Amazon Lightsail Icon
- Processamento em lote totalmente gerenciado em qualquer escala
- AWS Batch
- Contêineres
- Maneira altamente segura, confiável e escalável de executar contêineres
- Amazon Elastic Container Service (ECS)
- Executa contêineres na infraestrutura gerenciada pelo cliente
- Amazon ECS Anywhere
- Armazene, gerencia e implante imagens de contêineres com facilidade
- Amazon Elastic Container Registry (ECR)
- Serviço totalmente gerenciado de Kubernetes
- Amazon Elastic Kubernetes Service (EKS)
- Crie e opere clusters do Kubernetes na sua própria infraestrutura
- Amazon EKS Anywhere
- Computação sem servidor para contêineres
- AWS Fargate
- Crie e execute aplicações em contêineres em um serviço totalmente gerenciado
- AWS App Runner
- Arquiteturas Sem servidor
- Execute códigos sem pensar sobre os servidores. Pague apenas pelo tempo de computação que você utilizar
- AWS Lambda
- Borda e híbrida
- Execute a infraestrutura e os serviços da AWS no local para ter uma experiência híbrida verdadeiramente consistente
- AWS Outposts
- Colete e processe dados em ambientes de borda robustos ou desconectados
- Snowball Edge
- Família AWS Snow
- Forneça aplicativos de latência ultrabaixa para dispositivos 5G
- AWS Wavelength
- Serviço preferido para todas as cargas de trabalho do vSphere para estender e migrar rapidamente para a nuvem
- VMware Cloud on AWS
- Execute aplicativos com requisitos rigorosos de latência mais perto dos usuários
- AWS Local Zones
- Gerenciamento de custo e capacidade
- Modelo de definição de preço flexível que oferece economia de até 72% no uso de computação da AWS
- AWS Savings Plan
- Recomenda recursos de computação ideais do AWS para suas workloads para reduzir custos e melhorar a performance
- AWS Compute Optimizer
- Serviço de fácil utilização para implementação e escalabilidade de aplicações web e serviços
- AWS Elastic Beanstalk
- Crie e mantenha imagens seguras do Linux ou Windows Server
- EC2 Image Builder
- Distribua automaticamente o tráfego de aplicativos recebidos por vários destinos
- Elastic Load Balancing (ELB)

## Etapa 2 - [Armazenamento na nuvem AWS] - [Segurança para dados, Escalabilidade] 
  # [Descrição]

  -  Acesse o armazenamento que precisa mais rapidamente
Disponibilize recursos em minutos, não em semanas. Acelere o tempo de chegada ao mercado, evite planejamentos complexos de capacidade e reduza o provisionamento excessivo com apenas alguns cliques.

-  Reduza os custos de armazenamento
Minimize seu custo total de propriedade (TCO) com serviços gerenciados que eliminam a manutenção da infraestrutura. Otimize seus custos de armazenamento com base na frequência e na rapidez necessárias para acessar seus dados.

- Assegure e proteja seus dados
Proteja seus dados com segurança e armazenamento incomparáveis, projetados para oferecer durabilidade de 99,999999999 (11 9s) e resiliência de várias zonas de disponibilidade. Mantenha os dados disponíveis para as aplicações com a resiliência de dados fornecida por meio de opções que vão da restauração granular à recuperação na AWS e em ambientes on-premises.

-  Estimule a inovação com novos insights
Escolha entre uma variedade de ferramentas para obter mais dos seus dados e acelerar a entrega de novos produtos e serviços. Execute análise de big data, inteligência artificial (IA), machine learning (ML), computação de alta performance (HPC) e aplicações de processamento de mídia em todos os seus dados da nuvem.


## Etapa 3: - [ Redes e entrega de conteúdo na AWS ] - [ Maior cobertura global , Performance consistentemente elevada  , Maior disponibilidade de rede  ]
 # [Descrição]
 
- O Amazon Virtual Private Cloud (Amazon VPC) oferece controle total sobre seu ambiente de redes virtual, incluindo posicionamento de recursos, conectividade e segurança. Comece a usar configurando sua VPC no console de serviço AWS. Em seguida, adicione recursos a ela, como instâncias do Amazon Elastic Compute Cloud (EC2) e Amazon Relational Database Service (RDS). Por fim, defina como suas VPCs se comunicam entre si, entre contas, zonas de disponibilidade (AZs) ou Regiões da AWS. No exemplo abaixo, o tráfego de rede está sendo compartilhado entre duas VPCs em cada região. 

- O AWS Transit Gateway conecta suas Amazon Virtual Private Clouds (VPCs) e redes on-premises por meio de um hub central. Essa conexão simplifica a rede e elimina os complexos relacionamentos de emparelhamento. O Transit Gateway atua como um roteador de nuvem altamente escalável — cada nova conexão é feita apenas uma vez.

- O AWS PrivateLink fornece conectividade privada entre nuvens privadas virtuais (VPCs), serviços compatíveis da AWS e suas redes on-premises sem expor seu tráfego à Internet pública. Os endpoints da VPC de interface, desenvolvidos com o PrivateLink, conectam você a serviços hospedados por parceiros da AWS e soluções compatíveis disponíveis no AWS Marketplace.

- O Amazon VPC Lattice é um serviço de camada de aplicação que conecta, monitora e protege consistentemente as comunicações entre seus serviços, ajudando a melhorar a produtividade para que seus desenvolvedores possam se concentrar na criação de recursos importantes para seus negócios. É possível definir políticas para acesso à rede, gerenciamento de tráfego e monitoramento para conectar serviços de computação de maneira simples e consistente em instâncias, contêineres e tecnologia sem servidor.

- O AWS App Mesh fornece rede em nível de aplicação para que seus serviços possam se comunicar em vários tipos de infraestrutura de computação.

- O Amazon API Gateway é um serviço gerenciado que permite que desenvolvedores criem, publiquem, mantenham, monitorem e protejam APIs em qualquer escala com facilidade. APIs agem como a “porta de entrada” para aplicativos acessarem dados, lógica de negócios ou funcionalidade de seus serviços de back-end. Usando o API Gateway, você pode criar APIs do RESTful e APIs do WebSocket que habilitam aplicativos de comunicação bidirecionais em tempo real. O API Gateway dá suporte a cargas de trabalho conteinerizadas e sem servidor, além de aplicativos da web. O API Gateway administra todas as tarefas envolvidas no recebimento e processamento de até centenas de milhares de chamadas de API simultâneas, inclusive gerenciamento de tráfego, suporte de CORS, controle de autorização e acesso, com fluxo controlado, monitoramento e gerenciamento de versões de API.
O API Gateway não tem taxas mínimas ou custos antecipados. Você paga apenas pelas chamadas de API recebidas e pela quantidade transferida de dados de saída. Além disso, com o modelo de definição de preço em camadas do API Gateway, você pode reduzir os custos à medida que seu uso da API é escalado.

- O AWS Cloud Map é um serviço de descoberta de recursos na nuvem. Com o Cloud Map, você pode definir nomes personalizados para os recursos do aplicativo, e ele manterá a localização atualizada desses recursos em constante mudança. Isso aumenta a disponibilidade do seu aplicativo, pois seu serviço da Web sempre descobre os locais mais atualizados de seus recursos. Os aplicativos modernos costumam ser compostos por vários serviços que são acessados por meio de uma API, executando uma função específica.
Cada serviço interage com uma variedade de outros recursos, como bancos de dados, filas, armazenamentos de objetos e microsserviços definidos pelo cliente, além de precisar encontrar a localização de todos os recursos de infraestrutura dos quais depende para funcionar. Na maioria dos casos, você gerencia todos esses nomes de recursos e seus locais manualmente dentro do código do aplicativo. No entanto, o gerenciamento manual de recursos se tornou algo demorado e propenso a erros com o aumento do número de recursos de infraestrutura dependentes ou com a alteração da escala vertical dos microsserviços de acordo com o tráfego. Você também pode usar produtos de descoberta de serviços de terceiros, mas isso exige a instalação e o gerenciamento de software e infraestrutura adicionais. Com o Cloud Map, você pode registrar qualquer recurso de aplicativo, como bancos de dados, filas, microsserviços e outros recursos de nuvem com nomes personalizados. O Cloud Map verifica constantemente a integridade dos recursos para verificar se a localização está atualizada. O aplicativo consulta o registo para obter a localização dos recursos necessários com base na versão do aplicativo e no ambiente de implantação.

# Anexos 

[Site da própria autora utilizado para toda pesquisa e citações https://aws.amazon.com/pt/cloud-map/ ]



# :confetti_ball: Conclusão :confetti_ball: 

A implementação de ferramentas na empresa [Abstergo Industries] tem como esperado [benefícios das ferramentas citadas], o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Este projeto, foi criado com objetivo de demonstrar os conhecimentos aprendidos no curso, fazendo uma demonstração de ferramentas AWS que podem ser implementadas em qualquer empresa que não utiliza o cloud AWS para redução de custos. :sunglasses: :sunglasses:





