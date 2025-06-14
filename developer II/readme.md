📚 # Glossário AWS Certified Developer - Associate (DVA-C02)

Repositório com glossário organizado por domínio da prova DVA-C02, contendo nome dos serviços, descrição objetiva e palavras-chave que aparecem com frequência em questões. Ideal para revisões rápidas ou preparação direcionada.

---
📊 Distribuição por Domínios
A prova DVA-C02 é dividida em quatro domínios principais, com as seguintes proporções:

Domínio	Peso na Prova
1. Desenvolvimento com Serviços AWS	32%
2. Segurança	26%
3. Implantação	24%
4. Resolução de Problemas e Otimização	18%

Total: 100%
Fontes: GlobalDataNet, Whizlabs

🧠 Visão Geral dos Domínios
1. Desenvolvimento com Serviços AWS (32%)
Foco:
Codificação com SDKs, CLI e APIs da AWS, criação de funções Lambda, manipulação de dados com S3 e DynamoDB, e arquitetura serverless.

Serviços-Chave:
Lambda, DynamoDB, S3, API Gateway, SQS, SNS, Kinesis, AWS SDK, AWS CLI.

2. Segurança (26%)
Foco:
Autenticação e autorização, criptografia de dados, gestão de segredos e políticas de segurança.

Serviços-Chave:
IAM, Cognito, KMS, Secrets Manager, STS, SSM Parameter Store, ACM.

3. Implantação (24%)
Foco:
Empacotamento, testes e deployment com ferramentas CI/CD e infraestrutura como código.

Serviços-Chave:
Elastic Beanstalk, CloudFormation, CodeCommit, CodeBuild, CodePipeline, CodeDeploy, Copilot, ECS, ECR, Fargate.

4. Resolução de Problemas e Otimização (18%)
Foco:
Monitoramento, rastreamento, auditoria e melhoria de desempenho.

Serviços-Chave:
CloudWatch, X-Ray, CloudTrail.

🧭 Estratégia de Estudo por Prioridade
Alta Prioridade (32%): Domine Lambda, APIs, DynamoDB, S3, mensageria e aplicações serverless.

Segurança e Implantação (50%): Foque em IAM, Cognito, criptografia, deploy automático e IaC (infraestrutura como código).

Atenção à Otimização (18%): Inclua práticas com CloudWatch, X-Ray, análise de logs e tracing.

📖 Glossário Essencial para o DVA-C02
Este glossário contém 70 serviços e conceitos divididos por seções temáticas. Cada entrada inclui:

Nome do serviço

Descrição resumida

Palavras-chave relevantes para a prova

🧱 Parte 1: Fundamentos e Gerenciamento de Recursos
CAF (Cloud Adoption Framework)
Guias estratégicos da AWS para adoção da nuvem.
Palavras-chave: transformação digital, migração, boas práticas, governança.

AWS Well-Architected Framework
Padrões para workloads seguros, eficientes e resilientes na nuvem.
Palavras-chave: pilares, boas práticas, segurança, performance.

IAM (Identity and Access Management)
Gerenciamento de identidades e permissões para recursos AWS.
Palavras-chave: roles, policies, least privilege, usuários.

EC2 (Elastic Compute Cloud)
Máquinas virtuais sob demanda com controle total do ambiente.
Palavras-chave: instâncias, AMI, auto scaling.

Elastic Load Balancer (ELB)
Distribuição de tráfego entre múltiplas instâncias.
Palavras-chave: balanceamento de carga, ALB, NLB.

Auto Scaling Group (ASG)
Escalonamento automático de instâncias EC2.
Palavras-chave: políticas de scaling, alta disponibilidade.

EBS (Elastic Block Store)
Armazenamento persistente em blocos para EC2.
Palavras-chave: volumes, snapshots, IOPS.

Amazon Route 53
Serviço de DNS escalável e altamente disponível.
Palavras-chave: DNS, failover, roteamento.

Amazon RDS
Banco de dados relacional gerenciado (MySQL, PostgreSQL etc).
Palavras-chave: multi-AZ, backups automáticos.

ElastiCache
Cache gerenciado com Redis e Memcached.
Palavras-chave: baixa latência, in-memory, performance.

Amazon VPC
Rede virtual isolada com controle de subnets, IPs e ACLs.
Palavras-chave: NAT Gateway, security groups.

Amazon S3
Armazenamento de objetos com alta durabilidade e escalabilidade.
Palavras-chave: buckets, objetos, políticas, versionamento.

⚙️ Parte 2: Desenvolvimento, CI/CD e Infraestrutura como Código
AWS CLI
Interface de linha de comando para gerenciar recursos AWS.
Palavras-chave: automação, comandos aws, script.

AWS SDKs
Integração com AWS via código em várias linguagens.
Palavras-chave: Python (Boto3), JavaScript, APIs.

IAM Policies
Permissões em JSON aplicadas a usuários, grupos e roles.
Palavras-chave: actions, effect, resources.

Elastic Beanstalk
Plataforma gerenciada para aplicações web.
Palavras-chave: deploy automático, ambiente.

AWS CodeCommit
Repositório Git gerenciado.
Palavras-chave: versionamento, push/pull, colaboração.

AWS CodePipeline
Pipeline de CI/CD com automação de build, test e deploy.
Palavras-chave: etapas, integração contínua.

AWS CodeBuild
Build automático com testes e geração de artefatos.
Palavras-chave: buildspec, YAML, compilação.

AWS CodeDeploy
Automação de deploy para EC2, Lambda e ECS.
Palavras-chave: blue/green, in-place, atualização.

AWS CloudFormation
IaC com arquivos YAML/JSON para provisionar recursos.
Palavras-chave: template, stack, automatização.

🛡️ Parte 3: Monitoramento e Auditoria
Amazon CloudWatch
Métricas, logs e alarmes para recursos e aplicações.
Palavras-chave: dashboards, monitoramento, eventos.

AWS X-Ray
Tracing para identificar gargalos e latências.
Palavras-chave: microservices, performance.

AWS CloudTrail
Auditoria de chamadas de API.
Palavras-chave: logs de API, compliance, rastreabilidade.

📩 Parte 4: Integração e Mensageria
Amazon SQS
Filas para comunicação assíncrona entre sistemas.
Palavras-chave: polling, DLQ, mensagens.

Amazon SNS
Sistema pub/sub para notificações em tempo real.
Palavras-chave: tópicos, fan-out, push.

Amazon Kinesis
Processamento de dados em tempo real via streams.
Palavras-chave: shards, Data Streams, Firehose.

⚡ Parte 5: Serverless (Parte 1)
AWS Lambda
Execução de código sem servidores provisionados.
Palavras-chave: funções, eventos, escalabilidade automática.

Amazon DynamoDB
Banco de dados NoSQL gerenciado.
Palavras-chave: chave primária, provisionado/sob demanda.

Amazon API Gateway
Criação e gerenciamento de APIs REST/HTTP/WebSocket.
Palavras-chave: proxy, endpoint, autenticação.

Amazon Cognito
Gerenciamento de usuários e autenticação para apps.
Palavras-chave: pool, tokens, login social.

AWS SAM
Framework para desenvolvimento e deploy serverless.
Palavras-chave: sam deploy, sam build, YAML.

🐳 Parte 6: Containers e Orquestração
Amazon ECS
Orquestração de contêineres Docker.
Palavras-chave: cluster, task, Fargate, EC2.

Amazon ECR
Registro gerenciado de imagens Docker.
Palavras-chave: push/pull, repositório, integração.

AWS Fargate
Execução de contêineres sem gerenciar servidores.
Palavras-chave: serverless containers, custo sob demanda.


#### 36. **Amazon EKS (Elastic Kubernetes Service)**

* **Descrição:** Serviço gerenciado de Kubernetes para executar aplicações em contêiner.
* **Palavras-chave:** Kubernetes, pods, clusters, escalabilidade, gerenciamento automatizado.

#### 37. **AWS Copilot**

* **Descrição:** Ferramenta de linha de comando para implantar e gerenciar aplicações containerizadas com ECS/Fargate.
* **Palavras-chave:** CLI, pipeline, aplicações containerizadas, ECS simplificado.

---

### 🔐 Parte 7: Segurança, Acesso e Criptografia

#### 38. **AWS KMS (Key Management Service)**

* **Descrição:** Serviço gerenciado para criar, armazenar e gerenciar chaves de criptografia.
* **Palavras-chave:** criptografia, CMK, envelope, SSE, dados sensíveis.

#### 39. **IAM Roles / IAM Policies / IAM Users**

* **Descrição:** Conjunto de funcionalidades do IAM para controle de acesso.
* **Palavras-chave:** permissões, políticas, least privilege, acesso baseado em função.

#### 40. **AWS STS (Security Token Service)**

* **Descrição:** Gera credenciais temporárias para acesso seguro a recursos da AWS.
* **Palavras-chave:** credenciais temporárias, assumeRole, segurança, cross-account.

#### 41. **AWS Secrets Manager**

* **Descrição:** Armazena e gerencia segredos, como senhas e chaves de API.
* **Palavras-chave:** segredos, rotação automática, acesso seguro, criptografado.

#### 42. **AWS Systems Manager Parameter Store**

* **Descrição:** Armazena parâmetros de configuração e segredos.
* **Palavras-chave:** configurações, environment variables, secureString, automação.

#### 43. **AWS Certificate Manager (ACM)**

* **Descrição:** Gerencia certificados SSL/TLS para proteger aplicações e domínios.
* **Palavras-chave:** HTTPS, certificados, TLS, SSL, renovação automática.

#### 44. **AWS WAF (Web Application Firewall)**

* **Descrição:** Protege aplicações web contra ameaças comuns (ex: SQL injection, XSS).
* **Palavras-chave:** firewall, regras, proteção web, bloqueio.

#### 45. **AWS CloudHSM**

* **Descrição:** Hardware para gerenciamento seguro de chaves com controle exclusivo do cliente.
* **Palavras-chave:** HSM, segurança, FIPS 140-2, criptografia.

#### 46. **AWS Identity Center (antigo AWS SSO)**

* **Descrição:** Gerencia identidades e acesso de usuários centralizados entre contas e aplicações.
* **Palavras-chave:** single sign-on, IAM Identity Center, login único.

#### 47. **Amazon Macie**

* **Descrição:** Serviço de segurança que usa ML para descobrir e proteger dados sensíveis em S3.
* **Palavras-chave:** dados sensíveis, detecção automática, privacidade, S3.

#### 48. **AWS Resource Access Manager (RAM)**

* **Descrição:** Compartilha recursos entre contas AWS de forma segura.
* **Palavras-chave:** compartilhamento de recursos, cross-account, VPC, subnets.

---

### 💾 Parte 8: Armazenamento e Banco de Dados

#### 49. **Amazon Aurora**

* **Descrição:** Banco de dados relacional compatível com MySQL e PostgreSQL, com performance otimizada.
* **Palavras-chave:** RDS compatível, escalabilidade, alta performance, failover.

#### 50. **Amazon DynamoDB**

* **Descrição:** Banco NoSQL serverless com alta performance e escalabilidade automática.
* **Palavras-chave:** tabela, throughput, latência baixa, partition key, GSI, LSI.

#### 51. **Amazon RDS**

* **Descrição:** Serviço gerenciado de banco relacional compatível com vários mecanismos de banco.
* **Palavras-chave:** backups automáticos, Multi-AZ, instâncias de banco, failover.

#### 52. **Amazon ElastiCache**

* **Descrição:** Serviço de caching com Redis ou Memcached.
* **Palavras-chave:** cache, latência baixa, Redis, Memcached, session store.

#### 53. **Amazon MemoryDB for Redis**

* **Descrição:** Banco de dados Redis com durabilidade e alta disponibilidade.
* **Palavras-chave:** Redis, persistência, cache durável, multi-AZ.

#### 54. **Amazon EBS**

* **Descrição:** Armazenamento em blocos para EC2.
* **Palavras-chave:** volumes, snapshots, performance, disco.

#### 55. **Amazon EFS**

* **Descrição:** Sistema de arquivos compartilhado (NFS) acessível por várias instâncias.
* **Palavras-chave:** armazenamento em arquivos, escalável, compartilhado, NFS.

#### 56. **Amazon FSx**

* **Descrição:** Armazenamento de arquivos com suporte a sistemas como Windows File Server ou Lustre.
* **Palavras-chave:** arquivos, compatibilidade, desempenho, HPC.

#### 57. **Amazon S3 Glacier**

* **Descrição:** Armazenamento de longo prazo para arquivamento de dados com custo reduzido.
* **Palavras-chave:** arquivamento, baixo custo, cold storage, recuperação lenta.

---

### 🧰 Parte 9: Ferramentas DevOps e Developer

#### 58. **AWS Cloud Development Kit (CDK)**

* **Descrição:** Framework de infraestrutura como código usando linguagens de programação como Python, TypeScript, Java.
* **Palavras-chave:** infraestrutura como código (IaC), stacks, constructs, sintetizar para CloudFormation, programável.

#### 59. **AWS AppConfig**

* **Descrição:** Gerencia configurações de aplicativos de forma segura e controlada.
* **Palavras-chave:** feature flags, controle de configuração, rollback, mudanças seguras.

#### 60. **AWS CloudShell**

* **Descrição:** Terminal baseado em navegador com ferramentas pré-instaladas para gerenciar recursos AWS.
* **Palavras-chave:** CLI no navegador, ambiente shell, ferramenta rápida.

#### 61. **Amazon CodeGuru**

* **Descrição:** Ferramenta com IA para revisão de código e análise de performance.
* **Palavras-chave:** revisão de código, sugestões automatizadas, profiling, melhorias de performance.

#### 62. **AWS CodeArtifact**

* **Descrição:** Gerencia repositórios de pacotes de software (NPM, Maven, Python etc.).
* **Palavras-chave:** artefatos, pacotes, versionamento, repositório privado.

---

### 🔗 Parte 10: Integração, Eventos e Aplicações Web Modernas

#### 63. **Amazon EventBridge**

* **Descrição:** Barramento de eventos para conectar aplicações com base em eventos.
* **Palavras-chave:** eventos, integração, aplicações desacopladas, SaaS, regras, destino.

#### 64. **AWS Step Functions**

* **Descrição:** Orquestra workflows serverless com múltiplos serviços da AWS.
* **Palavras-chave:** workflows, máquina de estados, Lambda, orquestração, falhas controladas.

#### 65. **Amazon API Gateway**

* **Descrição:** Criação e gerenciamento de APIs REST, HTTP e WebSocket.
* **Palavras-chave:** APIs, RESTful, throttling, autenticação, integração com Lambda.

#### 66. **Amazon Cognito**

* **Descrição:** Serviço de autenticação, autorização e gerenciamento de usuários para apps web e mobile.
* **Palavras-chave:** login, SSO, federated identities, JWT, pools de usuários.

#### 67. **AWS AppSync**

* **Descrição:** Serviço gerenciado para APIs GraphQL, integrando fontes como DynamoDB e Lambda.
* **Palavras-chave:** GraphQL, dados em tempo real, sincronização, resolvers.

#### 68. **AWS Amplify**

* **Descrição:** Conjunto de ferramentas e serviços para desenvolver apps web/mobile com back-end na AWS.
* **Palavras-chave:** front-end, integração rápida, autenticação, armazenamento, GraphQL, CI/CD para frontend.

#### 69. **Amazon Simple Email Service (SES)**

* **Descrição:** Envio de e-mails em larga escala com autenticação e rastreamento.
* **Palavras-chave:** envio de e-mail, SMTP, marketing, transacional, reputação, DKIM.

#### 70. **Amazon CloudFront**

* **Descrição:** Rede de entrega de conteúdo (CDN) global para distribuição rápida de sites e APIs.
* **Palavras-chave:** CDN, baixa latência, cache, S3, API Gateway, HTTPS
