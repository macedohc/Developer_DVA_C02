# 🧠🌸 Conteúdo da certificação **AWS Certified Developer – Associate (DVA-C02)** 

---

### ✅ **MAIS COMUNS NA PROVA (PRIORIDADE MÁXIMA)**

---

#### **AWS Lambda**

**Serve para:** executar código sem gerenciar servidores
**Funciona assim:** você envia uma função (em Python, Node.js etc.) e define triggers como API Gateway, S3, DynamoDB ou eventos do EventBridge
**Palavras-chave:** serverless, execution role, cold start, concurrency, timeout, memory size

---

#### **Amazon API Gateway**

**Serve para:** criar e gerenciar APIs REST, HTTP ou WebSocket
**Funciona assim:** atua como porta de entrada para funções Lambda ou outros serviços
**Palavras-chave:** throttle, stage, endpoint type, integration, authorization (IAM, Cognito, Lambda authorizer)

---

#### **Amazon DynamoDB**

**Serve para:** banco de dados NoSQL gerenciado
**Funciona assim:** você define tabelas com chave primária, secundária e usa leitura/gravação provisionada ou on-demand
**Palavras-chave:** partition key, sort key, GSIs, LSIs, eventually consistent, provisioned, on-demand, DynamoDB Streams

---

#### **Amazon S3**

**Serve para:** armazenar objetos (arquivos, imagens, backups etc.)
**Funciona assim:** você cria buckets, define políticas, e pode ativar versionamento ou eventos
**Palavras-chave:** object key, versioning, lifecycle, encryption (SSE-S3, SSE-KMS), presigned URL, event notification

---

#### **Amazon CloudWatch**

**Serve para:** monitoramento e logs
**Funciona assim:** coleta métricas, logs e alarmes para serviços como Lambda, EC2 e RDS
**Palavras-chave:** metrics, logs, alarms, dashboards, custom metrics

---

#### **Amazon EventBridge**

**Serve para:** orquestrar eventos entre serviços
**Funciona assim:** você define regras que escutam eventos e direcionam ações (ex: invocar Lambda)
**Palavras-chave:** rule, pattern, target, event bus, schema

---

#### **AWS IAM (Identity and Access Management)**

**Serve para:** controlar permissões de acesso
**Funciona assim:** você cria usuários, grupos, roles e políticas baseadas em JSON
**Palavras-chave:** principal, action, resource, condition, trust policy, role, STS

---

#### **AWS CodePipeline**

**Serve para:** orquestrar pipelines CI/CD
**Funciona assim:** conecta repositórios (CodeCommit/GitHub), compila (CodeBuild), testa e faz deploy (CodeDeploy)
**Palavras-chave:** stages, actions, artifact, source, build, deploy

---

#### **AWS CodeBuild**

**Serve para:** construir e testar código automaticamente
**Funciona assim:** executa comandos definidos no `buildspec.yml`
**Palavras-chave:** build environment, buildspec, compute type, logs

---

#### **AWS CodeDeploy**

**Serve para:** fazer deploy automático de código
**Funciona assim:** define estratégias de deployment (rolling, blue/green, canary)
**Palavras-chave:** deployment group, AppSpec.yml, lifecycle hooks, rollback

---

#### **Amazon RDS**

**Serve para:** banco de dados relacional gerenciado
**Funciona assim:** suporta MySQL, PostgreSQL, MariaDB, SQL Server etc., com backups automáticos e alta disponibilidade
**Palavras-chave:** Multi-AZ, Read Replica, snapshots, endpoint, security group

---

#### **Amazon Cognito**

**Serve para:** autenticação e autorização de usuários
**Funciona assim:** cria pools de usuários e de identidade, integra com API Gateway e IAM
**Palavras-chave:** user pool, identity pool, OAuth, tokens, federation

---

#### **AWS CloudFormation**

**Serve para:** infraestrutura como código (IaC)
**Funciona assim:** define recursos da AWS com arquivos YAML ou JSON
**Palavras-chave:** stack, template, parameters, outputs, resources, update, rollback

---

#### **AWS SAM (Serverless Application Model)**

**Serve para:** facilitar a criação de aplicações serverless
**Funciona assim:** extensão do CloudFormation com foco em Lambda, API Gateway e DynamoDB
**Palavras-chave:** `template.yaml`, `sam deploy`, `sam build`, `sam local`, transform

---

#### **Amazon SQS (Simple Queue Service)**

**Serve para:** fila de mensagens entre sistemas
**Funciona assim:** mensagens são colocadas na fila e processadas por consumidores
**Palavras-chave:** visibility timeout, delay, standard vs FIFO, DLQ (dead letter queue)

---

#### **Amazon SNS (Simple Notification Service)**

**Serve para:** envio de notificações em massa
**Funciona assim:** tópicos publicam mensagens para múltiplos assinantes (Lambda, SQS, e-mail)
**Palavras-chave:** publish/subscribe, topic, subscription, fan-out

---

#### **AWS X-Ray**

**Serve para:** rastrear requisições em aplicações distribuídas
**Funciona assim:** coleta traces detalhados entre serviços como Lambda e API Gateway
**Palavras-chave:** segment, trace, annotations, service map

---

#### **AWS SDK e AWS CLI**

**Serve para:** interagir com os serviços via código ou terminal
**Funciona assim:** SDKs em várias linguagens (Python, JavaScript, Java) e CLI para automações
**Palavras-chave:** boto3, credentials, `aws configure`, access key, region, profile

---

### 🔵 **INTERMEDIÁRIOS (MÉDIA FREQUÊNCIA NA PROVA)**

---

#### **Amazon EC2 + Auto Scaling**

**Serve para:** instâncias de máquinas virtuais
**Funciona assim:** define tipos de instância, AMI, grupos de segurança e escalabilidade automática
**Palavras-chave:** AMI, instance type, scaling policy, launch template

#### **Amazon Elastic Beanstalk**

**Serve para:** implantar aplicações web rapidamente
**Funciona assim:** empacota código, escolhe ambiente (Node.js, Python etc.) e faz deploy
**Palavras-chave:** environment, deployment strategy, configuration, managed updates

#### **AWS Systems Manager (SSM)**

**Serve para:** gerenciar instâncias e configurações
**Funciona assim:** usa documentos para executar comandos remotamente ou armazenar parâmetros
**Palavras-chave:** parameter store, automation, run command

#### **Amazon CloudFront**

**Serve para:** distribuir conteúdo globalmente com baixa latência
**Funciona assim:** entrega objetos S3 ou APIs com cache em edge locations
**Palavras-chave:** CDN, origin, TTL, signed URL

#### **AWS AppConfig**

**Serve para:** gerenciar e lançar configurações de aplicação de forma segura
**Funciona assim:** define configurações, monitora e implementa em fases
**Palavras-chave:** deployment strategy, validators, hosted configuration

#### **Amazon ElastiCache**

**Serve para:** cache em memória (Redis ou Memcached)
**Funciona assim:** reduz latência acessando dados rapidamente
**Palavras-chave:** Redis, TTL, replication, cluster mode

---

### 🟡 **MENOS FREQUENTES MAS POSSÍVEIS NA PROVA**

---

* **Amazon Aurora**: banco relacional compatível com MySQL e PostgreSQL com melhor performance
* **Amazon Athena**: consulta arquivos no S3 com SQL
* **Amazon EMR**: cluster gerenciado para big data
* **Amazon OpenSearch**: busca e análise em tempo real
* **AWS Copilot**: deploy simplificado de apps containerizadas
* **AWS CloudShell**: terminal na web para comandos CLI
* **Amazon FSx / EFS / EBS**: opções de armazenamento para EC2
* **Amazon Macie**: detecta dados sensíveis (ex: CPF, cartão)
* **AWS Amplify**: frontend + backend rápido para apps web/mobile
* **AWS WAF**: firewall para proteger contra ataques em camada 7
* **AWS Step Functions**: coordena fluxos de trabalho serverless
* **AWS Key Management Service (KMS)**: gerenciamento de chaves criptográficas
* **AWS Certificate Manager (ACM)**: gerenciamento de certificados SSL
* **AWS Secrets Manager**: armazena segredos com rotação automática
* **Amazon EKS / ECS / Fargate / ECR**: serviços de contêineres

---
