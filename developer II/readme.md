# 📚  Glossário AWS Certified Developer - Associate (DVA-C02)

- Repositório com glossário organizado por domínio da prova DVA-C02, contendo nome dos serviços, descrição objetiva e palavras-chave que aparecem com frequência em questões. Ideal para revisões rápidas ou preparação direcionada.

---
## 📊 Distribuição por Domínios
- A prova DVA-C02 é dividida em quatro domínios principais, com as seguintes proporções:

- Domínio	Peso na Prova
1. Desenvolvimento com Serviços AWS	32%
2. Segurança	26%
3. Implantação	24%
4. Resolução de Problemas e Otimização	18%


## 🧠 Visão Geral dos Domínios
#### 1. Desenvolvimento com Serviços AWS (32%)
- Foco: Codificação com SDKs, CLI e APIs da AWS, criação de funções Lambda, manipulação de dados com S3 e DynamoDB, e arquitetura serverless.
- Serviços-Chave: Lambda, DynamoDB, S3, API Gateway, SQS, SNS, Kinesis, AWS SDK, AWS CLI.
#### 2. Segurança (26%)
- Foco: Autenticação e autorização, criptografia de dados, gestão de segredos e políticas de segurança.
- Serviços-Chave: IAM, Cognito, KMS, Secrets Manager, STS, SSM Parameter Store, ACM.
#### 3. Implantação (24%)
- Foco: Empacotamento, testes e deployment com ferramentas CI/CD e infraestrutura como código.
- Serviços-Chave: Elastic Beanstalk, CloudFormation, CodeCommit, CodeBuild, CodePipeline, CodeDeploy, Copilot, ECS, ECR, Fargate.

#### 4. Resolução de Problemas e Otimização (18%)
- Foco: Monitoramento, rastreamento, auditoria e melhoria de desempenho.
- Serviços-Chave: CloudWatch, X-Ray, CloudTrail.

---

### 🧭 Estratégia de Estudo por Prioridade
- Alta Prioridade (32%): Domine Lambda, APIs, DynamoDB, S3, mensageria e aplicações serverless.

- Segurança e Implantação (50%): Foque em IAM, Cognito, criptografia, deploy automático e IaC (infraestrutura como código).

- Atenção à Otimização (18%): Inclua práticas com CloudWatch, X-Ray, análise de logs e tracing.
---

#### 📖 Glossário Essencial para o DVA-C02
---

### 🧱 Parte 1: Fundamentos e Gerenciamento de Recursos
#### CAF (Cloud Adoption Framework)
* **Descrição:**Guias estratégicos da AWS para adoção da nuvem.
* **Palavras-chave:** transformação digital, migração, boas práticas, governança.

#### AWS Well-Architected Framework
* **Descrição:**Padrões para workloads seguros, eficientes e resilientes na nuvem.
* **Palavras-chave:**  pilares, boas práticas, segurança, performance.

#### IAM (Identity and Access Management)
* **Descrição:**Gerenciamento de identidades e permissões para recursos AWS.
* **Palavras-chave:** roles, policies, least privilege, usuários.

#### EC2 (Elastic Compute Cloud)
* **Descrição:**Máquinas virtuais sob demanda com controle total do ambiente.
* **Palavras-chave:** instâncias, AMI, auto scaling.

#### Elastic Load Balancer (ELB)
* **Descrição:**Distribuição de tráfego entre múltiplas instâncias.
* **Palavras-chave:**  balanceamento de carga, ALB, NLB.

#### Auto Scaling Group (ASG)
* **Descrição:**Escalonamento automático de instâncias EC2.
* **Palavras-chave:** políticas de scaling, alta disponibilidade.

#### EBS (Elastic Block Store)
* **Descrição:**Armazenamento persistente em blocos para EC2.
* **Palavras-chave:**  volumes, snapshots, IOPS.

#### Amazon Route 53
* **Descrição:**Serviço de DNS escalável e altamente disponível.
* **Palavras-chave:** DNS, failover, roteamento.

#### Amazon RDS
* **Descrição:**Banco de dados relacional gerenciado (MySQL, PostgreSQL etc).
* **Palavras-chave:**  multi-AZ, backups automáticos.

#### ElastiCache
* **Descrição:**Cache gerenciado com Redis e Memcached.
* **Palavras-chave:** baixa latência, in-memory, performance.

#### Amazon VPC
* **Descrição:**Rede virtual isolada com controle de subnets, IPs e ACLs.
* **Palavras-chave:**  NAT Gateway, security groups.

#### Amazon S3
* **Descrição:**Armazenamento de objetos com alta durabilidade e escalabilidade.
* **Palavras-chave:** buckets, objetos, políticas, versionamento.
---

### ⚙️ Parte 2: Desenvolvimento, CI/CD e Infraestrutura como Código
#### AWS CLI
* **Descrição:**Interface de linha de comando para gerenciar recursos AWS.
* **Palavras-chave:** automação, comandos aws, script.

#### AWS SDKs
* **Descrição:**Integração com AWS via código em várias linguagens.
* **Palavras-chave:** Python (Boto3), JavaScript, APIs.

#### IAM Policies
* **Descrição:**Permissões em JSON aplicadas a usuários, grupos e roles.
* **Palavras-chave:** actions, effect, resources.

#### Elastic Beanstalk
* **Descrição:**Plataforma gerenciada para aplicações web.
* **Palavras-chave:** deploy automático, ambiente.

#### AWS CodeCommit
* **Descrição:**Repositório Git gerenciado.
* **Palavras-chave:**  versionamento, push/pull, colaboração.

#### AWS CodePipeline
* **Descrição:**Pipeline de CI/CD com automação de build, test e deploy.
* **Palavras-chave:**  etapas, integração contínua.

#### AWS CodeBuild
* **Descrição:**Build automático com testes e geração de artefatos.
* **Palavras-chave:** buildspec, YAML, compilação.

#### AWS CodeDeploy
* **Descrição:**Automação de deploy para EC2, Lambda e ECS.
* **Palavras-chave:**  blue/green, in-place, atualização.

### AWS CloudFormation
* **Descrição:**IaC com arquivos YAML/JSON para provisionar recursos.
* **Palavras-chave:**Palavras-chave: template, stack, automatização.
---

### 🛡️ Parte 3: Monitoramento e Auditoria
#### Amazon CloudWatch
* **Descrição:**Métricas, logs e alarmes para recursos e aplicações.
* **Palavras-chave:**  dashboards, monitoramento, eventos.

#### AWS X-Ray
* **Descrição:**Tracing para identificar gargalos e latências.
* **Palavras-chave:**  microservices, performance.

#### AWS CloudTrail
* **Descrição:**Auditoria de chamadas de API.
* **Palavras-chave:** logs de API, compliance, rastreabilidade.
---
### 📩 Parte 4: Integração e Mensageria
#### Amazon SQS
* **Descrição:**Filas para comunicação assíncrona entre sistemas.
* **Palavras-chave:** Palavras-chave: polling, DLQ, mensagens.

#### Amazon SNS
* **Descrição:**Sistema pub/sub para notificações em tempo real.
* **Palavras-chave:** tópicos, fan-out, push.

#### Amazon Kinesis
* **Descrição:**Processamento de dados em tempo real via streams.
* **Palavras-chave:** shards, Data Streams, Firehose.
---
###⚡ Parte 5: Serverless
#### AWS Lambda
* **Descrição:**Execução de código sem servidores provisionados.
* **Palavras-chave:** funções, eventos, escalabilidade automática.

#### Amazon DynamoDB
* **Descrição:**Banco de dados NoSQL gerenciado.
* **Palavras-chave:** chave primária, provisionado/sob demanda.

#### Amazon API Gateway
* **Descrição:**Criação e gerenciamento de APIs REST/HTTP/WebSocket.
* **Palavras-chave:** proxy, endpoint, autenticação.

#### Amazon Cognito
* **Descrição:**Gerenciamento de usuários e autenticação para apps.
* **Palavras-chave:**  pool, tokens, login social.

#### AWS SAM
* **Descrição:**Framework para desenvolvimento e deploy serverless.
* **Palavras-chave:** sam deploy, sam build, YAML.
---

🐳 Parte 6: Containers e Orquestração
#### Amazon ECS
* **Descrição:**Orquestração de contêineres Docker.
* **Palavras-chave:** cluster, task, Fargate, EC2.

#### Amazon ECR
* **Descrição:**Registro gerenciado de imagens Docker.
* **Palavras-chave:** push/pull, repositório, integração.

#### AWS Fargate
* **Descrição:**Execução de contêineres sem gerenciar servidores.
* **Palavras-chave:** serverless containers, custo sob demanda.


#### Amazon EKS (Elastic Kubernetes Service)

* **Descrição:** Serviço gerenciado de Kubernetes para executar aplicações em contêiner.
* **Palavras-chave:** Kubernetes, pods, clusters, escalabilidade, gerenciamento automatizado.

#### AWS Copilot

* **Descrição:** Ferramenta de linha de comando para implantar e gerenciar aplicações containerizadas com ECS/Fargate.
* **Palavras-chave:** CLI, pipeline, aplicações containerizadas, ECS simplificado.

---

### 🔐 Parte 7: Segurança, Acesso e Criptografia

#### AWS KMS (Key Management Service)

* **Descrição:** Serviço gerenciado para criar, armazenar e gerenciar chaves de criptografia.
* **Palavras-chave:** criptografia, CMK, envelope, SSE, dados sensíveis.

#### IAM Roles / IAM Policies / IAM Users

* **Descrição:** Conjunto de funcionalidades do IAM para controle de acesso.
* **Palavras-chave:** permissões, políticas, least privilege, acesso baseado em função.

#### AWS STS (Security Token Service)

* **Descrição:** Gera credenciais temporárias para acesso seguro a recursos da AWS.
* **Palavras-chave:** credenciais temporárias, assumeRole, segurança, cross-account.

#### AWS Secrets Manager

* **Descrição:** Armazena e gerencia segredos, como senhas e chaves de API.
* **Palavras-chave:** segredos, rotação automática, acesso seguro, criptografado.

#### AWS Systems Manager Parameter Store

* **Descrição:** Armazena parâmetros de configuração e segredos.
* **Palavras-chave:** configurações, environment variables, secureString, automação.

#### AWS Certificate Manager (ACM)

* **Descrição:** Gerencia certificados SSL/TLS para proteger aplicações e domínios.
* **Palavras-chave:** HTTPS, certificados, TLS, SSL, renovação automática.

#### AWS WAF (Web Application Firewall)

* **Descrição:** Protege aplicações web contra ameaças comuns (ex: SQL injection, XSS).
* **Palavras-chave:** firewall, regras, proteção web, bloqueio.

#### AWS CloudHSM

* **Descrição:** Hardware para gerenciamento seguro de chaves com controle exclusivo do cliente.
* **Palavras-chave:** HSM, segurança, FIPS 140-2, criptografia.

#### AWS Identity Center (antigo AWS SSO)

* **Descrição:** Gerencia identidades e acesso de usuários centralizados entre contas e aplicações.
* **Palavras-chave:** single sign-on, IAM Identity Center, login único.

#### Amazon Macie

* **Descrição:** Serviço de segurança que usa ML para descobrir e proteger dados sensíveis em S3.
* **Palavras-chave:** dados sensíveis, detecção automática, privacidade, S3.

#### AWS Resource Access Manager (RAM)

* **Descrição:** Compartilha recursos entre contas AWS de forma segura.
* **Palavras-chave:** compartilhamento de recursos, cross-account, VPC, subnets.

---

### 💾 Parte 8: Armazenamento e Banco de Dados

#### Amazon Aurora

* **Descrição:** Banco de dados relacional compatível com MySQL e PostgreSQL, com performance otimizada.
* **Palavras-chave:** RDS compatível, escalabilidade, alta performance, failover.

#### Amazon DynamoDB

* **Descrição:** Banco NoSQL serverless com alta performance e escalabilidade automática.
* **Palavras-chave:** tabela, throughput, latência baixa, partition key, GSI, LSI.

#### Amazon RDS

* **Descrição:** Serviço gerenciado de banco relacional compatível com vários mecanismos de banco.
* **Palavras-chave:** backups automáticos, Multi-AZ, instâncias de banco, failover.

#### Amazon ElastiCache

* **Descrição:** Serviço de caching com Redis ou Memcached.
* **Palavras-chave:** cache, latência baixa, Redis, Memcached, session store.

#### Amazon MemoryDB for Redis

* **Descrição:** Banco de dados Redis com durabilidade e alta disponibilidade.
* **Palavras-chave:** Redis, persistência, cache durável, multi-AZ.

#### Amazon EBS

* **Descrição:** Armazenamento em blocos para EC2.
* **Palavras-chave:** volumes, snapshots, performance, disco.

#### Amazon EFS

* **Descrição:** Sistema de arquivos compartilhado (NFS) acessível por várias instâncias.
* **Palavras-chave:** armazenamento em arquivos, escalável, compartilhado, NFS.

#### Amazon FSx

* **Descrição:** Armazenamento de arquivos com suporte a sistemas como Windows File Server ou Lustre.
* **Palavras-chave:** arquivos, compatibilidade, desempenho, HPC.

#### Amazon S3 Glacier

* **Descrição:** Armazenamento de longo prazo para arquivamento de dados com custo reduzido.
* **Palavras-chave:** arquivamento, baixo custo, cold storage, recuperação lenta.

---

### 🧰 Parte 9: Ferramentas DevOps e Developer

#### AWS Cloud Development Kit (CDK)

* **Descrição:** Framework de infraestrutura como código usando linguagens de programação como Python, TypeScript, Java.
* **Palavras-chave:** infraestrutura como código (IaC), stacks, constructs, sintetizar para CloudFormation, programável.

#### AWS AppConfig

* **Descrição:** Gerencia configurações de aplicativos de forma segura e controlada.
* **Palavras-chave:** feature flags, controle de configuração, rollback, mudanças seguras.

#### AWS CloudShell

* **Descrição:** Terminal baseado em navegador com ferramentas pré-instaladas para gerenciar recursos AWS.
* **Palavras-chave:** CLI no navegador, ambiente shell, ferramenta rápida.

#### Amazon CodeGuru

* **Descrição:** Ferramenta com IA para revisão de código e análise de performance.
* **Palavras-chave:** revisão de código, sugestões automatizadas, profiling, melhorias de performance.

#### AWS CodeArtifact

* **Descrição:** Gerencia repositórios de pacotes de software (NPM, Maven, Python etc.).
* **Palavras-chave:** artefatos, pacotes, versionamento, repositório privado.

---

### 🔗 Parte 10: Integração, Eventos e Aplicações Web Modernas

#### Amazon EventBridge

* **Descrição:** Barramento de eventos para conectar aplicações com base em eventos.
* **Palavras-chave:** eventos, integração, aplicações desacopladas, SaaS, regras, destino.

#### AWS Step Functions

* **Descrição:** Orquestra workflows serverless com múltiplos serviços da AWS.
* **Palavras-chave:** workflows, máquina de estados, Lambda, orquestração, falhas controladas.

#### Amazon API Gateway

* **Descrição:** Criação e gerenciamento de APIs REST, HTTP e WebSocket.
* **Palavras-chave:** APIs, RESTful, throttling, autenticação, integração com Lambda.

#### Amazon Cognito

* **Descrição:** Serviço de autenticação, autorização e gerenciamento de usuários para apps web e mobile.
* **Palavras-chave:** login, SSO, federated identities, JWT, pools de usuários.

#### AWS AppSync

* **Descrição:** Serviço gerenciado para APIs GraphQL, integrando fontes como DynamoDB e Lambda.
* **Palavras-chave:** GraphQL, dados em tempo real, sincronização, resolvers.

#### AWS Amplify

* **Descrição:** Conjunto de ferramentas e serviços para desenvolver apps web/mobile com back-end na AWS.
* **Palavras-chave:** front-end, integração rápida, autenticação, armazenamento, GraphQL, CI/CD para frontend.

#### Amazon Simple Email Service (SES)

* **Descrição:** Envio de e-mails em larga escala com autenticação e rastreamento.
* **Palavras-chave:** envio de e-mail, SMTP, marketing, transacional, reputação, DKIM.

#### Amazon CloudFront

* **Descrição:** Rede de entrega de conteúdo (CDN) global para distribuição rápida de sites e APIs.
* **Palavras-chave:** CDN, baixa latência, cache, S3, API Gateway, HTTPS
