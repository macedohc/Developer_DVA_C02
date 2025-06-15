# 🧠👩🏻‍🎓 Certificação AWS Certified Developer – Associate

-----

## Pesos 🏋️

- Domínio | % do exame \---------|----------|
- Domínio 1: Implantação | 24%
- Domínio 2: Segurança | 18%
- Domínio 3: Desenvolvimento em AWS | 30%
- Domínio 4: Refatoração | 10%
- Domínio 5: Monitoramento e Solução de Problemas | 18%
- TOTAL | 100%

**[REFERÊNCIA](https://www.google.com/search?q=https://d1.awsstatic.com/training-and-certification/docs-developer-associate/AWS-Certified-Developer-Associate_Exam-Guide.pdf)**

-----

## 1\. O que é a Computação em Nuvem? ☁️ ☁️ ☁️

"É a entrega sob demanda de recursos computacionais, através de uma plataforma de serviços via internet, sem o gerenciamento ativo do usuário."

**[REFERÊNCIA](https://aws.amazon.com/pt/what-is-cloud-computing/)**

-----

# 1.1 As 6 vantagens da Computação em Nuvem na visão da AWS. 🥇

# Save money

"Pare de gastar recursos financeiros na manutenção da infraestrutura e tenha mais foco nos clientes."

# Stop guessing capacity

"Elimina a adivinhação de quanta infraestrutura precisa. Com a computação em nuvem, você não precisa prever a capacidade de infraestrutura necessária antes de implantar um aplicativo."

# Variable expenses

"Ao adotar uma abordagem de computação em nuvem com o benefício de **despesas variáveis**, as empresas podem implementar soluções inovadoras enquanto economizam custos."

# Economies of scale

"O uso da computação em nuvem permite obter um custo variável inferior ao que você consegue por conta própria."

# Increase speed and agility

"Mais facilidade na hora de usar o serviço em poucos cliques."

# Go global

"Facilidade em disponibilizar o serviço em várias partes no globo."

**[REFERÊNCIA](https://docs.aws.amazon.com/pt_br/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html)**

-----

# 1.2 Tipos de Cloud

## Temos 3 tipos de Cloud\!

  * **IaaS: Infrastructure as a Service (Infraestrutura como Serviço).** \<br\> **Ex:** Utilizamos o serviço das máquinas EC2 para montar servidores virtuais, utilizando rede, armazenamento e processamento. A AWS oferece o hardware das máquinas e todo o maquinário por de trás do dashboard, enquanto o usuário configura o que deseja.

  * **PaaS: Platform as a Service (Plataforma como Serviço).** Não é preciso gerenciar a infraestrutura subjacente (geralmente hardware e sistemas operacionais), e você pode focar na implantação e no gerenciamento de suas aplicações.

  * **SaaS: Software as a Service (Software como Serviço).** Quando utilizamos o software: Amazon CloudFront, Amazon Detective, Amazon DocumentDB, etc.

**[REFERÊNCIA](https://aws.amazon.com/pt/types-of-cloud-computing/)**

-----

# 2\. SERVIÇOS ESSENCIAIS DE COMPUTAÇÃO 🖥 ☁️

## Amazon EC2 (Elastic Compute Cloud)

"O Amazon EC2 é um serviço que disponibiliza uma capacidade computacional segura, representado por uma instância redimensionável na Nuvem."

### CARACTERÍSTICAS

  * Modelo Infraestrutura como Serviço (IaaS)
  * Permite alugar máquinas virtuais (Instâncias EC2)
  * Possibilidade de armazenar dados em volumes virtuais (EBS)
  * Distribuir a carga de trabalho (ELB)
  * Escalar o serviço de acordo com a demanda (ASG)
  * Ambientes operacionais Windows, macOS e Linux
  * Cobrança por hora ou segundo (mínimo de 60 segundos)

**[REFERÊNCIA](https://aws.amazon.com/pt/ec2/)**

### 2.1 Tipos de Instâncias

FAMÍLIA | OTIMIZADO | IDEAL PARA
\---------|----------|---------|
`A, T, M, MAC` | Uso geral | Servidores web, desenvolvimento, homologação e repositórios de código
`C` | Computação | Modelagem científica, servidores de jogos, servidores de anúncios, machine learning
`R, X, Z` | Memória | Cargas de trabalho que processam grandes conjuntos de dados na memória
`I, D, H` | Armazenamento | Cargas de trabalho que requerem uso intensivo de disco (IOPS), grandes bancos de dados NoSQL, data warehouses

**[REFERÊNCIA](https://aws.amazon.com/pt/ec2/instance-types/)**

### 2.2 ✨ Opções de Compra de Instâncias EC2

Launch | Específico | Preço | Útil
\---------|----------|---------|---------
**SOB DEMANDA/On-Demand Instances** | Cobrança pelo uso (por hora OU por segundo). Sem compromisso de uso (anos). Sem pagamento adiantado. Pode aumentar ou diminuir a capacidade computacional. | Alto custo se usado por longo prazo | Cargas de trabalho de curto prazo, validar hipóteses, com pico de utilização previsível, testar e experimentar um ambiente.
**INSTÂNCIAS RESERVADAS (RIs)** | Aplicações que exigem capacidade reservada. Comprometimento de uso da instância por um período de 01 ou 03 anos. | Possui pagamento integral/parcial e adiantado. Até 75% de desconto em comparação com instâncias por demanda. | Ambiente de produção que foi testado e não será modificado, aplicação que precisa ter estado constante; Excelente para banco de dados.
**HOST DEDICADO** | Hardware dedicado. Servidor físico EC2 exclusivo para cumprir requisitos de conformidade. Visibilidade de soquetes, núcleos, IDs de host. Comprometimento por um período de 03 anos. Pode ser comprado sob demanda de horas. | Se optar por reservar, até 70% de desconto em comparação com instâncias por demanda. | Vincular licenças de software como Windows Server, AWS Server e SUSE Linux Enterprise Server.
**INSTÂNCIA DEDICADA** | Hardware dedicado. Pode compartilhar o hardware com outras instâncias na mesma conta. Não tem controle sobre o posicionamento da instância (você só pode movimentar hardware se interromper e reiniciar); Comprometimento por um período de 03 anos.
**INSTÂNCIAS SPOT** | São terminadas quando o preço do spot é maior do que o preço que você estabeleceu para pagar. Terminate = (preço spot da AWS \> seu preço) | Até 90% de desconto em comparação com instâncias por demanda. | Quando você tem urgência de grande capacidade computacional, workloads que podem parar e serem iniciados novamente, trabalhos em IoT, análise de dados, processamento de imagens.

**[REFERÊNCIA](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/instance-purchasing-options.html)**

### 2.3 Savings Plans do Amazon EC2

Permite reduzir os custos de computação ao haver o compromisso com uma quantidade consistente de uso de computação por um período de um ou três anos. Esse compromisso resulta em economias de até 72% em relação aos custos de instâncias sob demanda.

**[REFERÊNCIA](https://aws.amazon.com/pt/savingsplans/)**

-----

### 2.4 Amazon EC2 Auto Scaling

"O Amazon EC2 Auto Scaling permite que você adicione ou remova automaticamente instâncias do Amazon EC2 em resposta à alteração da demanda do aplicativo."

  - No Amazon EC2 Auto Scaling, há duas abordagens disponíveis: **scaling dinâmico** e **scaling preditivo**.
      * O scaling dinâmico responde às alterações na demanda.
      * O scaling preditivo programa automaticamente o número correto de instâncias do Amazon EC2 com base na demanda prevista.


**[REFERÊNCIA](https://aws.amazon.com/pt/ec2/autoscaling/)**

**Escalabilidade:** Aumentar os recursos computacionais como RAM, CPU, etc., de uma única instância.

**Elasticidade:** Aumentar ou diminuir o número de instâncias (máquinas) para atender à demanda.

**Serviços Elásticos:** Amazon EC2, Elastic Load Balancing, AWS Elastic Beanstalk, Amazon ElastiCache.

**OBS:**

  * Definir uma quantidade mínima, desejável e máxima de instâncias.
  * **Scale out** (aumentar com as demandas) e **Scale in** (diminuir quando a demanda deixa de ocorrer).
  * **Auto Scaling Group** é gratuito, você paga apenas pelas instâncias que estão sendo executadas.

-----

### 2.5 Elastic Load Balancing (ELB)

"O Elastic Load Balancing é o serviço AWS que distribui automaticamente o tráfego de entrada de aplicativos entre vários recursos, como instâncias do Amazon EC2, containers, endereços IP e Funções Lambda."

  - **TIPOS DE LOAD BALANCER**
      * Application Load Balancer (ALB)
      * Network Load Balancer (NLB)
      * Gateway Load Balancer (GLB)
      * Classic Load Balancer (CLB - em descontinuação)

| = | APPLICATION LOAD BALANCER | NETWORK LOAD BALANCER | GATEWAY LOAD BALANCER | CLASSIC LOAD BALANCER
|---|---|---|---|---|
| **Protocolos** | HTTP, HTTPS | TCP, UDP, TLS | IP (GENEVE) porta 6081 | HTTP, HTTPS, TCP, UDP, TLS
| **Plataforma** | Amazon VPC | Amazon VPC | Amazon VPC | Amazon VPC, Rede EC2-Classic
| **Camada OSI** | 7 (Aplicação) | 4 (Transporte) | 3 (Rede) | 7 OU 4
| **Recomendável** | Amazon EC2, Contêineres, Funções Lambda, Endereços IP | Amazon EC2, Microsserviços e Contêineres de alta performance | Gerenciar virtual appliances como firewalls e inspeção de pacotes no Amazon EC2 | Em breve será descontinuado (usar ALB ou NLB)

**[REFERÊNCIA](https://aws.amazon.com/pt/elasticloadbalancing/)**

-----

## Amazon Simple Notification Service (Amazon SNS)

"O Amazon Simple Notification Service (Amazon SNS) é um serviço de publicação/assinatura." É amplamente usado para desacoplamento de serviços e para enviar notificações push, SMS e e-mail.

**[REFERÊNCIA](https://aws.amazon.com/pt/sns/)**

## Amazon Simple Queue Service (Amazon SQS)

"O Amazon Simple Queue Service (Amazon SQS) é um serviço de enfileiramento de mensagens que permite o desacoplamento e a escalabilidade de microsserviços, sistemas distribuídos e aplicações sem servidor." Ajuda a criar aplicações distribuídas mais resilientes e escaláveis.

**[REFERÊNCIA](https://aws.amazon.com/pt/sqs/)**

## AWS Lambda

"O AWS Lambda é um serviço que permite a execução de códigos sem a necessidade de provisionar ou gerenciar servidores."

**OBS:**

  * **Serviço Serverless** gerenciado pela AWS.
  * AWS Lambda dimensiona suas aplicações automaticamente.
  * Você pode otimizar o tempo de execução e o tamanho de memória.
  * Cobrança por número de solicitações de suas funções e pela duração (por cada milissegundo que seu código for executado).

**[REFERÊNCIA](https://aws.amazon.com/pt/lambda/)**

## Amazon Elastic Container Service (Amazon ECS)

"É um sistema de gerenciamento de contêineres altamente dimensionável e de alto desempenho que permite executar e dimensionar aplicativos em contêineres na AWS." Suporta Docker.

**[REFERÊNCIA](https://aws.amazon.com/pt/ecs/)**

## Amazon Elastic Kubernetes Service (Amazon EKS)

"É um serviço totalmente gerenciado que você pode usar para executar o Kubernetes na AWS." Permite que você utilize orquestração de contêineres com Kubernetes sem precisar gerenciar o plano de controle.

**[REFERÊNCIA](https://aws.amazon.com/pt/eks/)**

## AWS Fargate

"O AWS Fargate é um mecanismo de computação sem servidor para contêineres. Ele funciona com o Amazon ECS e o Amazon EKS. Com o AWS Fargate, você não precisa provisionar ou gerenciar servidores." Ideal para desenvolvedores que querem focar apenas no código da aplicação em contêiner.

**[REFERÊNCIA](https://aws.amazon.com/pt/fargate/)**

-----


# 3\. INFRAESTRUTURA GLOBAL E CONFIABILIDADE 🛰 🏭

  * Uma **Região** é a disponibilização de uma coleção de recursos AWS em uma localização geográfica, sendo ela composta por um conjunto de Zonas de Disponibilidade.
  * **ZONA DE DISPONIBILIDADE (AZ):** Um conjunto de data centers que estão na mesma REGIÃO, porém separados por uma distância significativa, atuando de forma independente em caso de falha de uma zona. Isso garante alta disponibilidade e resiliência.
  * **Pontos de Presença (Edge Locations) ou Local de Borda:** Infraestrutura de servidores, localizada próximo a uma Zona de Disponibilidade, que armazena os dados mais solicitados em cache, para entregar com menor latência uma requisição de consulta. São utilizados como cache de dados para distribuição de conteúdo (ex: AWS CloudFront).

**[REFERÊNCIA](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/Concepts.RegionsAndAvailabilityZones.html)**

## AWS Elastic Beanstalk

"Você fornece definições de **código** e configuração, e o Elastic Beanstalk implanta os recursos necessários para executar as seguintes tarefas:"

  * Balancear carga
  * Dimensionar de forma automática (Auto Scaling Group - ASG)
  * Monitorar a integridade do aplicativo
  * Ajustar capacidade
  * Alta disponibilidade (Multi-AZ)
  * Suporta upload de código (arquivo \< 512MB ou via URL de Bucket S3)
  * É uma Plataforma como Serviço (PaaS)

**[REFERÊNCIA](https://aws.amazon.com/pt/elasticbeanstalk/)**

## AWS CloudFormation

"Você pode considerar sua infraestrutura como código. Crie frequentemente a infraestrutura e os aplicativos sem precisar executar ações manuais ou criar scripts personalizados." Permite modelar, provisionar e gerenciar recursos AWS usando templates.

**[REFERÊNCIA](https://aws.amazon.com/pt/cloudformation/)**

-----


# 4\. REDES 📡

## AMAZON VPC (Virtual Private Cloud)

"O Amazon VPC é uma sessão isolada logicamente na nuvem AWS, que permite customizar uma rede virtual e executar recursos em um ambiente com controle total." Permite definir sua própria rede virtual, incluindo faixas de IP, sub-redes, tabelas de rotas e gateways de rede.

**[REFERÊNCIA](https://aws.amazon.com/pt/vpc/)**

## AWS Direct Connect

"O AWS Direct Connect é um serviço que permite estabelecer uma conexão privada dedicada entre seu data center e uma VPC." Ajuda a reduzir custos de rede e aumentar a largura de banda para tráfego privado.


**[REFERÊNCIA](https://aws.amazon.com/pt/directconnect/)**

-----

## Gateway da Internet X Gateway Privado Virtual

Para permitir que o tráfego público da internet acesse sua VPC, é preciso anexar um **gateway da internet** à VPC.


**[REFERÊNCIA](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/VPC_Internet_Gateway.html)**

Para acessar recursos privados em uma VPC a partir de uma rede on-premises (via VPN ou Direct Connect), você pode usar um **gateway privado virtual**.



**[REFERÊNCIA](https://docs.aws.amazon.com/pt_br/directconnect/latest/UserGuide/virtualgateways.html)**

**OBS:** Uma sub-rede é uma seção de uma VPC na qual você pode agrupar recursos com base em necessidades operacionais ou de segurança. As sub-redes podem ser públicas (com acesso à internet) ou privadas (sem acesso direto à internet).

## Lista de Controle de Acesso (ACL) de Rede

"Uma lista de controle de acesso (ACL) de rede é um firewall virtual que controla o tráfego de entrada e saída no nível de sub-rede."

  * **Filtragem de pacotes stateless:** As ACLs de rede não se lembram de nada e verificam os pacotes que atravessam a fronteira da sub-rede em todos os sentidos: entrada e saída.

## Grupos de Segurança

Um grupo de segurança é um firewall virtual que controla o tráfego de entrada e saída de uma instância do Amazon EC2.

  * Por padrão, um grupo de segurança nega todo o tráfego de entrada e permite todo o tráfego de saída.
  * **Filtragem de pacotes stateful:** Os grupos de segurança se lembram de decisões anteriores tomadas para pacotes recebidos, permitindo o tráfego de retorno automaticamente.

**[REFERÊNCIA](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/ec2-security-groups.html)**

## Amazon Route 53

"É um serviço web de DNS altamente disponível e escalável. Oferece aos desenvolvedores e empresas uma maneira confiável de rotear os usuários finais para aplicativos da internet hospedados na AWS."


### REGISTROS COMUNS

URL | IP | REGISTRO/RECORD | TIPO
\---------|----------|---------|---------
www.google.com | 216.239.38.120 | A | IPv4 (Address Record)
www.google.com | 0:0:0:0:0:ffff:d8ef:2678 | AAAA | IPv6 (Quad-A Record)
search.google.com | www.google.com | CNAME | Hostname para Hostname (Canonical Name)
exemplo.com | Recurso AWS | ALIAS | ELB, CloudFront, S3, etc. (Aponta para recursos AWS de forma nativa)

**[REFERÊNCIA](https://aws.amazon.com/pt/route53/)**

-----


# 5\. Armazenamento e Bancos de Dados 📊 🗂 💻

## Amazon Elastic Block Store (Amazon EBS)

"É um serviço que fornece volumes de armazenamento persistentes a nível de bloco que você pode usar com instâncias do Amazon EC2. Se você interromper ou encerrar uma instância do Amazon EC2, todos os dados no volume do EBS anexo permanecerão disponíveis."

**[REFERÊNCIA](https://aws.amazon.com/pt/ebs/)**

## Snapshots do Amazon EBS

"Um snapshot do EBS é um backup incremental. Isso significa que o primeiro backup de um volume copia todos os dados."


**[REFERÊNCIA](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/EBSSnapshots.html)**

## Amazon Simple Storage Service (Amazon S3)

"É um serviço gerenciado de armazenamento e recuperação de objetos, respondendo com escalabilidade, disponibilidade, segurança e performance."

**OBS:**

  * Armazenamento virtualmente ilimitado.
  * Permite compartilhar arquivos ou criar websites estáticos.
  * Ideal para armazenar snapshots, backups, data lakes e para análise de big data.
  * Baixa latência e alta velocidade.
  * Durabilidade de 99,999999999% (onze noves).
  * O tamanho máximo de arquivo para um objeto no Amazon S3 é de 5 TB.
  * **ARMAZENAMENTO = BUCKETS | ARQUIVOS = OBJETOS | SUB-PASTAS = PREFIXOS**

### SOBRE OS OBJETOS

  * Tamanho máximo de objeto: 5 TB.
  * Para upload \> 5 GB, use multi-part upload.
  * Suporta metadata (chave e valor por sistema e usuário) e tags (chave e valor por usuário).
  * Suporta **Versionamento de objetos**, o que ajuda a proteger contra exclusões acidentais e permite restaurar versões anteriores de arquivos.

## Classes de Armazenamento do Amazon S3

| = | S3 Standard | S3 Intelligent-Tiering | S3 Standard-IA | S3 One Zone-IA | S3 Glacier | S3 Glacier Deep Archive
|---|---|---|---|---|---|---|
| **Bom para** | Uso geral, dados acessados frequentemente | Uso geral e movimentação automática de dados | Acesso pouco frequente, ideal para backup | Acesso pouco frequente, mas apenas uma AZ | Arquivar dados (recuperação em minutos/horas) | Retenção a longo prazo (\> 7 anos, recuperação em horas)
| **Ciclo Vida** | Zero | \<=30 dias (movimento automático) | \>=30 dias | \>=30 dias | \>=90 dias | \>=180 dias
| **Durabilidade** | 99,999999999% | 99,999999999% | 99,999999999% | 99,999999999% | 99,999999999% | 99,999999999%
| **Disponível** | (11 9's) | (11 9's) | (11 9's) | (11 9's) | (11 9's) | (11 9's)
| **Zonas Dispo** | \>=3 | \>=3 | \>=3 | 1 | \>=3 | \>=3
| **SLA** | 99,9% | 99% | 99% | 99% | 99,9% | 99,9%
| **Recuperação** | Imediata | Imediata | Imediata | Imediata | Minutos a Horas | Até 12 Horas

-----

  * **S3 Standard:** Projetado para dados acessados com frequência. Armazena dados em um mínimo de três Zonas de Disponibilidade. Alta durabilidade e disponibilidade.

-----

  * **S3 Standard-Infrequent Access (S3 Standard-IA):** Ideal para dados acessados com pouca frequência, mas que precisam ter alta disponibilidade quando necessário. Oferece o mesmo nível de durabilidade e disponibilidade do S3 Standard, mas com um preço de armazenamento mais baixo e um preço de recuperação mais alto.

-----

  * **One Zone-Infrequent Access (S3 One Zone-IA):** Armazena dados em uma única Zona de Disponibilidade. Tem um preço de armazenamento menor do que o S3 Standard-IA, mas com menor resiliência em caso de falha da AZ.

-----

  * **S3 Intelligent-Tiering:** O Amazon S3 monitora os padrões de acesso dos objetos. Se você não acessou um objeto por 30 dias consecutivos, o Amazon S3 o move automaticamente para o nível de acesso pouco frequente S3 Standard-IA. Se você acessar um objeto no nível de acesso pouco frequente, o Amazon S3 o move automaticamente para o nível de acesso frequente S3 Standard. Ideal para dados com padrões de acesso desconhecidos ou em alteração.

-----

  * **S3 Glacier:** Categoria de armazenamento de baixo custo, ideal para o arquivamento de dados. É possível recuperar objetos em poucos minutos a horas.

-----

  * **S3 Glacier Deep Archive:** Categoria de armazenamento de objetos com o menor custo, ideal para arquivamento de longo prazo (ex: retenção \> 7 anos). É possível recuperar objetos em até 12 horas.

-----

**[REFERÊNCIA](https://aws.amazon.com/pt/s3/)**

-----

## Amazon Elastic File System (Amazon EFS)

"É um sistema de arquivos escalável e elástico usado com os serviços de nuvem AWS e recursos locais. À medida que você adiciona e remove arquivos, o Amazon EFS expande e retrai automaticamente. Ele pode dimensionar sob demanda para petabytes sem interromper os aplicativos." Ideal para casos de uso em que um grande número de serviços e recursos precisam acessar os mesmos dados ao mesmo tempo (ex: cargas de trabalho de big data, contêineres).

**[REFERÊNCIA](https://aws.amazon.com/pt/efs/)**

## Amazon Relational Database Service (Amazon RDS)

"O Amazon Relational Database Service (Amazon RDS) é um serviço que permite executar bancos de dados relacionais gerenciados na nuvem AWS."

  * Oferece alta disponibilidade automática e recuperação.
  * O cliente é proprietário dos dados e do schema.
  * O cliente controla a rede.
  * Automatiza tarefas como provisionamento de hardware, configuração de banco de dados, aplicação de patches e backups.
  * Suporta vários motores de banco de dados, incluindo MySQL, PostgreSQL, MariaDB, Oracle, SQL Server e Amazon Aurora.

**[REFERÊNCIA](https://aws.amazon.com/pt/rds/)**

-----

## Amazon Aurora

"O Amazon Aurora é um banco de dados relacional de nível empresarial totalmente gerenciado."

  * Cinco vezes mais rápido do que o MySQL e três vezes mais rápido do que os bancos de dados PostgreSQL comuns.
  * Oferece alta disponibilidade.
  * Replicação de seis cópias dos dados em três Zonas de Disponibilidade.
  * Backup contínuo para o Amazon S3.
  * Considerado para cargas de trabalho que exigem alta disponibilidade e escalabilidade.

**[REFERÊNCIA](https://aws.amazon.com/pt/rds/aurora/)**

-----

## Amazon DynamoDB

  * Banco de dados **NoSQL** (não relacional) de chave-valor e documento.
  * O DynamoDB é **Serverless**, o que significa que você não precisa provisionar, aplicar patches ou gerenciar servidores.
  * Oferece Auto Scaling, alta performance e capacidade de produção massiva.
  * Potencial de tamanho de petabytes.
  * Acesso a API granular.

**[REFERÊNCIA](https://aws.amazon.com/pt/dynamodb/)**

## Amazon Redshift

"O Amazon Redshift é um serviço de **data warehouse** em escala de petabytes que você pode usar para análise de big data. Ele oferece a capacidade de coletar dados de muitas fontes, além de ajudar a entender relações e tendências em todos os seus dados."

**[REFERÊNCIA](https://aws.amazon.com/pt/redshift/)**

## AWS Database Migration Service (AWS DMS)

"O AWS Database Migration Service (AWS DMS) permite migrar bancos de dados relacionais e não relacionais e outros tipos de armazenamentos de dados."

  * O banco de dados de origem permanece totalmente operacional durante a migração, minimizando o tempo de inatividade das aplicações.
  * Os bancos de dados de origem e destino não precisam ser do mesmo tipo (migrações heterogêneas).

**[REFERÊNCIA](https://aws.amazon.com/pt/dms/)**

## Amazon DocumentDB (com compatibilidade com MongoDB)

"O Amazon DocumentDB é um serviço de banco de dados de documentos compatível com cargas de trabalho do MongoDB."

**[REFERÊNCIA](https://aws.amazon.com/pt/documentdb/)**

## Amazon Neptune

"O Amazon Neptune é um serviço de **banco de dados de grafo**."
Você pode usar o Amazon Neptune para criar e executar aplicativos que funcionam com conjuntos de dados altamente conectados, como mecanismos de recomendação, detecção de fraudes e gráficos de conhecimento.

**[REFERÊNCIA](https://aws.amazon.com/pt/neptune/)**

## Amazon Quantum Ledger Database (Amazon QLDB)

"O Amazon Quantum Ledger Database (Amazon QLDB) é um serviço de **banco de dados ledger**. Mantenha um log imutável e criptografável das mudanças de dados. Você pode usar o Amazon QLDB para revisar um histórico completo de todas as alterações feitas nos dados do aplicativo."

**[REFERÊNCIA](https://aws.amazon.com/pt/qldb/)**

## Amazon Managed Blockchain

"O Amazon Managed Blockchain é um serviço para criar e gerenciar redes de blockchain com estruturas de código aberto."
Blockchain é um sistema de registro distribuído que permite que várias partes executem transações e compartilhem dados sem uma autoridade central.

**[REFERÊNCIA](https://aws.amazon.com/pt/managed-blockchain/)**

## Amazon ElastiCache

"O Amazon ElastiCache é um serviço de cache em memória totalmente gerenciado que você pode usar para adicionar camadas de cache sobre seus bancos de dados e aplicações para ajudar a melhorar os tempos de leitura de solicitações comuns."
Ele é compatível com dois tipos de armazenamentos de dados: **Redis** e **Memcached**.

**[REFERÊNCIA](https://aws.amazon.com/pt/elasticache/)**

## Amazon DynamoDB Accelerator (DAX)

"O Amazon DynamoDB Accelerator (DAX) é um cache em memória para o DynamoDB." Ele ajuda a melhorar os tempos de resposta de milissegundos para microssegundos para leituras do DynamoDB.

**[REFERÊNCIA](https://aws.amazon.com/pt/dynamodb/dax/)**

-----


# 6\. SEGURANÇA 👮‍♀️ 👮

## 6.1 Modelo de Responsabilidade Compartilhada

A segurança na nuvem é uma **responsabilidade compartilhada** entre a AWS e o cliente.

  * **AWS (Segurança *DA* Nuvem):** Responsável pela segurança da infraestrutura que executa todos os serviços AWS. Inclui hardware, software, rede e instalações que executam os serviços da AWS.
  * **Cliente (Segurança *NA* Nuvem):** Responsável pela segurança de seus dados, controle de acesso, configuração da plataforma, aplicações, rede e sistema operacional convidados.

## AWS Identity and Access Management (IAM)

Permite que você gerencie o acesso aos serviços e recursos AWS com segurança.

**OBS:**

  * Usuários possuem credenciais permanentes e funções possuem credenciais temporárias.
  * Usuário **root** NÃO deve ser compartilhado e deve ser usado apenas para tarefas de gerenciamento de conta iniciais.
  * Use o **princípio do privilégio mínimo (least privilege principle)** nos usuários e funções.
  * Documentos JSON definem as permissões de acesso (Políticas do IAM).
  * Grupos contêm outros usuários, mas NÃO podem conter outros grupos.

### Usuários

Representam uma pessoa ou aplicação com credenciais de segurança permanentes.

### Grupos do IAM

Um grupo do IAM é um conjunto de usuários do IAM. Ao atribuir uma política do IAM a um grupo, todos os usuários do grupo recebem permissões especificadas pela política.

### Funções do IAM

Uma função do IAM é uma identidade que você pode assumir para obter acesso temporário a permissões. Ideal para conceder acesso a serviços AWS, outras contas AWS ou aplicações.

**[REFERÊNCIA](https://aws.amazon.com/pt/iam/)**

## AWS Organizations

"AWS Organizations permite que você gerencie e controle seu ambiente de maneira centralizada."

**OBS:**

  * AWS Organizations é um serviço Global.
  * Permite gerenciar múltiplas contas AWS.
  * Uma conta principal (Master Account).
  * API disponível para criação e gerenciamento de contas.
  * Restrição das contas usando **Service Control Policies (SCPs)**.
  * Permite consolidar e gerenciar múltiplas contas AWS em um local central.
  * Você pode agrupar contas em Unidades Organizacionais (UOs) para facilitar o gerenciamento.

**[REFERÊNCIA](https://aws.amazon.com/pt/organizations/)**

## Políticas de Controle de Serviço (SCPs)

As SCPs permitem que você coloque restrições nos serviços AWS, recursos e ações individuais de API que os usuários e funções em cada conta podem acessar dentro de uma organização.

**[REFERÊNCIA](https://docs.aws.amazon.com/pt_br/organizations/latest/userguide/orgs_manage_policies_scps.html)**

## AWS Artifact

O AWS Artifact é um serviço que fornece acesso sob demanda a relatórios de segurança e conformidade da AWS e a contratos on-line selecionados. O AWS Artifact tem duas seções principais: AWS Artifact Agreements e o AWS Artifact Reports.

  * **AWS Artifact Agreements:** Você pode revisar, aceitar e gerenciar contratos para uma conta individual e para todas as suas contas no AWS Organizations.
  * **AWS Artifact Reports:** Fornece relatórios de conformidade por auditores terceirizados, que verificaram se a AWS está em conformidade com diversas normas e regulamentações de segurança globais, regionais e específicas do setor.

**[REFERÊNCIA](https://aws.amazon.com/pt/artifact/)**

## Proteção contra Ataques de Negação de Serviço Distribuída (DDoS)

## AWS Shield

O AWS Shield é um serviço que protege aplicativos contra ataques DDoS. O AWS Shield oferece dois níveis de proteção: Standard e Advanced.

**OBS:**

  * AWS Shield é para mitigar ataques DDoS.
  * **Standard** é gratuito para todos os clientes AWS.
  * **Advanced** é pago, oferece suporte 24x7 e possui proteção extra em determinados serviços.

**[REFERÊNCIA](https://aws.amazon.com/pt/shield/)**

### AWS Shield Standard

"O AWS Shield Standard protege automaticamente todos os clientes AWS sem nenhum custo. Ele protege seus recursos AWS contra os tipos de ataques DDoS mais comuns e frequentes."

  * Gratuito para todos os clientes AWS.
  * Proteção contra SYN/UDP Floods, Reflection Attacks e outros ataques na camada 3 e camada 4.

### AWS Shield Advanced

"É um serviço pago que fornece diagnósticos detalhados de ataques e a capacidade de detectar e mitigar ataques elaborados de DDoS."

  * Serviço pago.
  * Suporte 24x7.
  * Proteção extra nos serviços: Amazon EC2, Elastic Load Balancing (ELB), Amazon CloudFront, AWS Global Accelerator e Route 53.

## AWS Key Management Service (AWS KMS)

"Permite que você execute operações de criptografia pelo uso de chaves de criptografia gerenciadas." Ajuda a criar e controlar chaves de criptografia para proteger seus dados em serviços AWS e em suas aplicações.

## AWS WAF (Web Application Firewall)

"É um firewall de aplicativo web que permite monitorar solicitações de rede que entram em seus aplicativos web." Ajuda a proteger aplicações web contra exploits comuns da web que podem afetar a disponibilidade da aplicação, comprometer a segurança ou consumir recursos excessivos.

  * **OBS:** Trabalha em conjunto com o Amazon CloudFront, Application Load Balancer e API Gateway.

## Amazon Inspector

"O Amazon Inspector **ajuda a melhorar a segurança e a conformidade** dos aplicativos executando avaliações de segurança automatizadas. Ele verifica os aplicativos quanto a vulnerabilidades de segurança e desvios das práticas recomendadas de segurança, como acesso aberto a instâncias do Amazon EC2 e instalações de versões de software vulneráveis."

**[REFERÊNCIA](https://aws.amazon.com/pt/inspector/)**

## Amazon GuardDuty

"O Amazon GuardDuty é um serviço que fornece **detecção inteligente de ameaças** para sua infraestrutura e seus recursos AWS. Ele identifica ameaças monitorando continuamente a atividade da rede e o comportamento da conta no seu ambiente AWS."

**[REFERÊNCIA](https://aws.amazon.com/pt/guardduty/)**

-----

# 7\. Monitoramento e Análise 👨‍💻 📟

-----
Entendido\! Vou continuar adaptando o seu texto, mantendo a estrutura e o foco na certificação AWS Certified Developer – Associate.

-----

## Amazon CloudWatch

"O Amazon CloudWatch é um serviço de monitoramento de desempenho dos recursos e dos aplicativos que você executa no seu ambiente AWS." É fundamental para desenvolvedores acompanharem a saúde e o desempenho de suas aplicações.

  * Visualizar aplicações e infraestrutura em um único local.
  * Acessar um Dashboard automático.
  * Criar seu próprio Dashboard personalizado com os serviços e métricas desejadas.
  * Configurar alarmes visuais do ambiente.

## **Coletar -\> Monitorar -\> Atuar -\> Analisar**

  * **Coletar:**
      * Coleta Métricas e Logs.
      * De recursos e serviços na nuvem e on-premises.
      * Métrica padrão a cada 5 minutos.
      * Métrica detalhada (paga) a cada minuto, para monitoramento mais granular.
  * **Monitorar:**
      * Visualize aplicações e sua infraestrutura em um único local.
      * Acesse um Dashboard automático.
      * Crie seu Dashboard personalizado com os serviços e métricas que deseja acompanhar.
      * Configure alarmes visuais para o ambiente.
  * **Atuar:**
      * Crie alarmes para atuar como gatilho, baseado nas métricas de uso e desempenho.
      * Opções do gatilho: amostra, porcentagem, valor máximo, mínimo, etc.
      * **ALARM ACTIONS:**
          * **Auto Scaling Group:** Aumentar ou diminuir o número de instâncias no Amazon EC2.
          * **Amazon SNS:** Enviar notificações para um SNS Topic, para que os assinantes (ex: desenvolvedores, operações) recebam um e-mail ou outra notificação.
          * **Lambda:** Invocar uma função Lambda para executar ações automatizadas em resposta a um alarme.
  * **Analisar:**
      * Analise em tempo real o seu ambiente (em segundos) ou posteriormente com até 15 meses de armazenamento dos logs e métricas.
      * A análise de alarmes possui três estados:
          * **OK:** Tudo bem, a métrica está dentro do limite.
          * **INSUFFICIENT\_DATA:** Coletando dados, não há dados suficientes para determinar o estado.
          * **ALARM:** Algo ruim aconteceu ou a sua métrica atingiu o limite configurado.

**[REFERÊNCIA](https://aws.amazon.com/pt/cloudwatch/)**

## AWS CloudTrail

"O AWS CloudTrail é um serviço que possibilita governança, conformidade, auditoria operacional e auditoria de riscos em sua conta AWS."

**OBS:**

  * Registra as chamadas de API (API calls) feitas por usuários, funções IAM e serviços AWS.
  * Permite visualizar um histórico completo de atividades do usuário e chamadas de API de seus aplicativos e recursos, essencial para depuração e segurança.

**[REFERÊNCIA](https://aws.amazon.com/pt/cloudtrail/)**

## CloudTrail Insights

Esse recurso opcional permite que o CloudTrail detecte automaticamente atividades de API incomuns ou anormais em sua conta AWS, como picos inesperados no uso de determinadas APIs.

**[REFERÊNCIA](https://docs.aws.amazon.com/pt_br/awscloudtrail/latest/userguide/logging-insights-events-with-cloudtrail.html)**

## AWS Config

"É um serviço que permite acessar, auditar e avaliar as configurações dos recursos da AWS." Ajuda a verificar a conformidade dos recursos com políticas internas e regulamentações externas.

  * **Funcionamento:**
      * "Há acesso irrestrito via SSH nos meus grupos de segurança?"
      * "Meus Buckets S3 estão com acesso aberto ao público?"
      * "Como minha configuração de Application Load Balancer (ALB) mudou ao longo do tempo?"

**[REFERÊNCIA](https://aws.amazon.com/pt/config/)**

**OBS:**

  * AWS Config é regional.
  * Auxilia na auditoria das alterações dos recursos para compliance.
  * Mantém histórico das alterações e armazena em um bucket S3 para posterior análise.
  * Notificações de alterações são enviadas com o Amazon SNS e disponibilizadas no Dashboard do AWS Config.

## AWS Trusted Advisor

"É um serviço web que inspeciona seu ambiente AWS e faz recomendações em tempo real de acordo com as práticas recomendadas da AWS."

  * Faz recomendações de práticas recomendadas em cinco categorias:
      * **Otimização de custos:** Identifica oportunidades para economizar dinheiro.
      * **Desempenho:** Sugere melhorias para aumentar a velocidade e eficiência.
      * **Segurança:** Alerta sobre vulnerabilidades e configurações inseguras.
      * **Tolerância a falhas:** Indica maneiras de construir sistemas mais resilientes.
      * **Limites de serviço:** Ajuda a monitorar e planejar o uso dos recursos para evitar limites.


**[REFERÊNCIA](https://aws.amazon.com/pt/premiumsupport/technology/trusted-advisor/)**

-----


# 8\. Definição de Preços e Suporte 💸 💵 ⏲

## Planos de Suporte AWS

## AWS Pricing Calculator

"Permite explorar os serviços AWS e gerar uma estimativa de custo de seus casos de uso na AWS. Você pode organizar as suas estimativas da AWS por grupos que definir." Ferramenta essencial para planejamento de custos de projetos.

**[REFERÊNCIA](https://calculator.aws/#/)**

## AWS Cost Explorer

"O AWS Cost Explorer é uma interface para visualizar, entender e gerenciar os custos e o uso da AWS ao longo do tempo."
**OBS:**

  * Ajuda a analisar tendências de gastos, identificar áreas de otimização e prever custos futuros.
  * Funciona em conjunto com o AWS Budgets.

**[REFERÊNCIA](https://aws.amazon.com/pt/aws-cost-management/aws-cost-explorer/)**

## AWS Marketplace

"O AWS Marketplace é um catálogo digital com milhares de ofertas de software de fornecedores independentes. Você pode usar o AWS Marketplace para encontrar, testar e comprar software que pode ser executado na AWS." Simplifica a implantação de softwares de terceiros.

### Categorias do AWS Marketplace


**[REFERÊNCIA](https://aws.amazon.com/marketplace)**

## AWS Budgets

"É um serviço para definir orçamentos personalizados e enviar alertas quando o uso ou os custos excederem o valor orçado." No AWS Budgets, você pode criar orçamentos para planejar o uso do serviço, os custos de serviço e as reservas de instâncias. Isso ajuda a controlar os gastos e evitar surpresas na fatura.

**[REFERÊNCIA](https://aws.amazon.com/pt/aws-cost-management/)**

-----


# 9\. Migração e Inovação

## Estratégias de Migração para a Nuvem (6 Rs da Migração)

  * **Redefinição de hospedagem (Rehost/Lift-and-shift):** Movimentação de aplicativos para a nuvem sem grandes alterações no código ou arquitetura. Geralmente é a estratégia mais rápida para começar.
  * **Redefinição de plataforma (Replatform/Lift, tinker, and shift):** Envolve realizar algumas otimizações na nuvem para obter um benefício tangível, sem refatorar o código principal. Ex: migrar de um banco de dados on-premises para o Amazon RDS.
  * **Refatoração/Re arquitetura (Refactor/Re-architect):** Reimaginar como um aplicativo é arquitetado e desenvolvido usando recursos nativos da nuvem para aproveitar ao máximo a elasticidade, escalabilidade e resiliência. Ex: migrar de monolito para microsserviços com Lambda e SQS.
  * **Recompra (Repurchase):** Mudar de uma licença tradicional para um modelo de software como serviço (SaaS) na nuvem. Ex: migrar de um CRM on-premises para o Salesforce.
  * **Retenção (Retain):** Consiste em manter os aplicativos essenciais para a empresa no ambiente de origem (on-premises) por questões de conformidade, legado ou custo.
  * **Inativação (Retire):** É o processo de remover aplicativos que não são mais necessários ou úteis, economizando recursos.

**[REFERÊNCIA](https://aws.amazon.com/pt/blogs/enterprise-strategy/6-strategies-for-migrating-applications-to-the-cloud/)**

## AWS Snow Family

"É uma coleção de dispositivos físicos para transporte físico de até exabytes de dados para dentro e para fora da AWS." Ideal para transferências de dados de grande volume onde a largura de banda de rede é limitada ou cara.

  * **AWS Snowcone:** Um dispositivo pequeno, robusto e seguro para transferência de dados e computação de borda.

      * Capacidade de 8 TB.
      * Portátil, adequado para lugares inóspitos ou remotos.
      * Poder computacional para edge computing.

  * **AWS Snowball Edge:** Dispositivos maiores e mais poderosos para migrações de dados em larga escala e cargas de trabalho de computação de borda.

      * **Snowball Edge otimizados para armazenamento:** Ideais para migrações de dados de grande escala e fluxos de trabalho de transferência recorrentes, além de computação local com necessidades maiores de capacidade.
          * Até 80 TB de disco rígido (HDD) utilizável para volumes de blocos, compatível com Amazon S3.
          * Unidade de estado sólido (SSD) de 1 TB para volumes de blocos.
          * Computação: 40 vCPUs e 80 GiB de memória para dar suporte a instâncias sbe1 do Amazon EC2 (equivalente a C5).
      * **Snowball Edge otimizado para computação:** Fornece recursos de computação poderosos para casos de uso como machine learning, análise de vídeo em movimento completo, análise e pilhas de computação locais.
          * HDD utilizável de 42 TB, compatível com Amazon S3.
          * Compatível com Amazon EBS.
          * 7,68 TB de capacidade de SSD NVMe.
          * Computação: 52 vCPUs, 208 GiB de memória e uma GPU NVIDIA Tesla V100 opcional. Os dispositivos executam as instâncias sbe-c e sbe-g do Amazon EC2, que são equivalentes às instâncias C5, M5a, G3 e P3.

  * **AWS Snowmobile:**
    "É um serviço de transferência de dados na escala de exabytes usado para mover grandes quantidades de dados para a nuvem AWS."

      * Você pode transferir até 100 petabytes por Snowmobile, um contêiner de transporte reforçado com 13,71 metros de comprimento puxado por um caminhão semirreboque.

-----


# 10\. AWS Well-Architected Framework

"Ajuda você a entender como projetar e operar sistemas confiáveis, seguros, eficientes e econômicos na nuvem AWS." É um conjunto de melhores práticas e diretrizes arquitetônicas.


  * O Well-Architected Framework se baseia em seis pilares (o seu texto ainda menciona 5, mas o atualizado tem 6):

      * **Excelência Operacional (Operational Excellence):** A capacidade de executar e monitorar sistemas para entregar valor comercial e melhorar continuamente os processos e procedimentos de apoio. Foca na automação, observabilidade e gerenciamento de mudanças.
      * **Segurança (Security):** Inclui a capacidade de proteger informações, sistemas e ativos, e, ao mesmo tempo, entregar valor comercial por meio de avaliações de risco e estratégias de mitigação. Foca em IAM, detecção, proteção, resposta e recuperação.
      * **Confiabilidade (Reliability):** A capacidade de um sistema de se recuperar de falhas de infraestrutura ou serviço, adquirir dinamicamente recursos de computação para atender à demanda e mitigar interrupções como configurações incorretas ou problemas de rede transitórios. Foca em alta disponibilidade, recuperação de desastres e resiliência.
      * **Eficiência de Desempenho (Performance Efficiency):** A capacidade de usar recursos computacionais com eficiência para cumprir requisitos do sistema e manter essa eficiência à medida que a demanda muda e as tecnologias evoluem. Foca na seleção de tipos de recursos corretos, dimensionamento e otimização.
      * **Otimização de Custos (Cost Optimization):** A capacidade de executar sistemas para entregar valor comercial com o menor preço. Foca em otimizar custos ao longo do tempo, adotando modelos de precificação adequados e gerenciamento de recursos.
      * **Sustentabilidade (Sustainability):** O pilar mais recente, foca em minimizar o impacto ambiental das cargas de trabalho na nuvem. Inclui otimização do uso de recursos, eficiência energética e seleção de regiões.

## AWS Cloud Adoption Framework (AWS CAF)

"O AWS Cloud Adoption Framework (AWS CAF) ajuda as organizações a desenvolver um plano abrangente para uma migração bem-sucedida para a nuvem. Ele organiza orientações em seis áreas de foco chamadas perspectivas." Cada perspectiva aborda responsabilidades distintas. O processo de planejamento ajuda as pessoas certas em toda a organização a se prepararem para as mudanças futuras.

  * Em geral, as perspectivas de **negócio**, **pessoas** e **governança** se concentram nas capacidades comerciais (estratégicas e organizacionais).
  * Enquanto as perspectivas de **plataforma**, **segurança** e **operações** se concentram em capacidades técnicas (implementação e gerenciamento).

**[REFERÊNCIA](https://d1.awsstatic.com/whitepapers/architecture/AWS_Well-Architected_Framework.pdf)**

-----
