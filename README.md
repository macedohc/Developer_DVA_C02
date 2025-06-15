# 🔝 **TÓPICOS MAIS COBRADOS NA CERTIFICAÇÃO DVA-C02**

### ✅ **1. AWS Lambda (Serverless)**

* Criação, execução e limites (timeout, memória)
* Integração com API Gateway, S3, DynamoDB, SNS, SQS
* Lambda Layers e Versions
* IAM Roles e políticas de execução
* Tempo de execução e cold start
* **⚠️Cai MUITO na prova**

---

### ✅ **2. Amazon API Gateway**

* Tipos de APIs (HTTP vs REST)
* Integração com Lambda
* Modelos de autorização (IAM, Lambda Authorizer, Cognito)
* Caching e throttling
* Deploy de stages
* **⚠️Muito comum junto com Lambda**

---

### ✅ **3. Amazon DynamoDB**

* Partições, chave primária (partition key, sort key)
* Operações: GetItem, PutItem, Query, Scan
* Indexes (GSI, LSI)
* Provisionamento vs On-Demand
* TTL, Streams e triggers com Lambda
* Transações e consistência de leitura
* **⚠️Cai bastante em questões práticas**

---

### ✅ **4. CI/CD com serviços Code\***

* **CodeCommit**: repositório Git
* **CodeBuild**: build automatizado, `buildspec.yml`
* **CodeDeploy**: estratégias de deploy (in-place, blue/green)
* **CodePipeline**: orquestração de etapas do pipeline
* **⚠️Muito comum em perguntas de automação de entrega**

---

### ✅ **5. IAM (Identity and Access Management)**

* Policies: inline, managed, permissões mínimas
* Roles: para Lambda, EC2, serviços interagirem
* IAM com SDK (STS, AssumeRole)
* Políticas baseadas em recurso e identidade
* **⚠️Essencial para quase todo o conteúdo**

---

### ✅ **6. Amazon S3**

* Buckets, versionamento, políticas de bucket
* Eventos (ex: disparar Lambda ao subir objeto)
* S3 Encryption (SSE-S3, SSE-KMS, SSE-C)
* Storage Classes: Standard, IA, Glacier
* **⚠️Muito comum, aparece com Lambda e Glue**

---

### ✅ **7. Amazon EventBridge / CloudWatch Events**

* Disparar eventos para Lambda, Step Functions, SNS
* Agendamentos (cron, rate)
* Filtros de eventos
* **⚠️Comum em fluxos de eventos automáticos**

---

### ✅ **8. Amazon SQS e SNS**

* **SQS**: filas padrão e FIFO, Dead Letter Queues (DLQ), visibilidade
* **SNS**: envio de mensagens para Lambda, email, SMS
* Diferenças entre pub/sub (SNS) e filas (SQS)
* **⚠️Muita questão sobre integração entre eles e Lambda**

---

### ✅ **9. AWS CloudFormation / SAM / CDK**

* Infraestrutura como código
* **SAM**: `template.yaml`, `sam deploy`
* CDK com TypeScript ou Python
* Dependências entre recursos e parâmetros
* **⚠️Alta chance de cair uma questão de deploy automático**

---

### ✅ **10. AWS CloudWatch, X-Ray, CloudTrail**

* Logs e métricas customizadas
* Alarmes e dashboards
* Distributed Tracing com X-Ray
* Auditoria com CloudTrail
* **⚠️Muito comum em questões de monitoramento**

---

## 🎯 OUTROS TÓPICOS QUE APARECEM:

* **Elastic Beanstalk**: deploy simplificado, configuração de ambiente
* **Step Functions**: orquestração de funções Lambda
* **Secrets Manager & Parameter Store**: armazenar variáveis sensíveis
* **RDS vs DynamoDB**: quando usar relacional ou NoSQL
* **ECS/Fargate**: container serverless (pouco, mas aparece)
* **KMS, STS, Cognito**: segurança e autenticação
* **AWS CLI e SDKs**: chamadas de API programáticas
* **API REST x SDK x CLI x Console**
* **Deploy seguro**: Blue/Green, canary, rollback

---

## 🧠 DICAS DE FOCO:

* Pratique **questões de Lambda + DynamoDB + API Gateway**
* Entenda **pipelines com CodePipeline** do início ao fim
* Domine **políticas IAM e roles de serviço**
* Saiba como **SQS e SNS interagem com Lambda**
* Revise **CloudFormation/SAM/CDK** e deploy automatizado
* Estude **monitoramento e logging com CloudWatch e X-Ray**

---
