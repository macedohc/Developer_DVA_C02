

### 🔢 **Domínio 1: Desenvolvimento com serviços AWS (32%)**

Foco em escrever, depurar e manter código com os serviços da AWS.

* **AWS Lambda**

  * *Descrição:* Serviço serverless para executar código em resposta a eventos.
  * *Palavras-chave:* trigger, handler, runtime, invocação, função.

* **Amazon S3**

  * *Descrição:* Armazenamento de objetos altamente escalável e durável.
  * *Palavras-chave:* bucket, objeto, evento, versionamento, ACL.

* **Amazon DynamoDB**

  * *Descrição:* Banco de dados NoSQL com baixa latência e alta escalabilidade.
  * *Palavras-chave:* tabela, chave primária, provisionado, leitura, TTL.

* **Amazon API Gateway**

  * *Descrição:* Serviço para criar, publicar e monitorar APIs RESTful e WebSocket.
  * *Palavras-chave:* endpoint, método, integração, proxy, REST API.

* **Amazon SNS**

  * *Descrição:* Serviço de mensagens pub/sub para notificações e comunicação entre sistemas.
  * *Palavras-chave:* tópico, assinatura, push, fan-out.

* **Amazon SQS**

  * *Descrição:* Serviço de filas para desacoplar e escalar microserviços.
  * *Palavras-chave:* fila, polling, delay, mensagens.

* **Amazon Kinesis**

  * *Descrição:* Processamento de streaming de dados em tempo real.
  * *Palavras-chave:* shard, stream, consumidor, produtor, Firehose.

* **AWS SDKs**

  * *Descrição:* Conjuntos de ferramentas para integrar aplicações com a AWS usando várias linguagens.
  * *Palavras-chave:* boto3, JavaScript, Java, Python, integração.

* **AWS CLI**

  * *Descrição:* Interface de linha de comando para gerenciar serviços AWS.
  * *Palavras-chave:* comando, script, perfil, autenticação.

* **Amazon EventBridge**

  * *Descrição:* Barramento de eventos para conectar serviços usando eventos customizados.
  * *Palavras-chave:* regra, destino, evento, bus, integração.

* **AWS AppSync**

  * *Descrição:* Serviço para construir APIs GraphQL seguras e escaláveis.
  * *Palavras-chave:* GraphQL, resolver, schema, dados em tempo real.

---

### 🔐 **Domínio 2: Segurança (26%)**

Foco em autenticação, autorização e criptografia de dados.

* **IAM (Identity and Access Management)**

  * *Descrição:* Controle de identidade e acesso a recursos da AWS.
  * *Palavras-chave:* política, role, usuário, grupo, least privilege.

* **IAM Identity Center (SSO)**

  * *Descrição:* Login centralizado e federado para múltiplas contas AWS.
  * *Palavras-chave:* SSO, login unificado, identidade, permissões.

* **Amazon Cognito**

  * *Descrição:* Gerenciamento de identidade de usuários para aplicações.
  * *Palavras-chave:* user pool, identity pool, token, OAuth, login federado.

* **AWS KMS**

  * *Descrição:* Serviço para criação e gerenciamento de chaves criptográficas.
  * *Palavras-chave:* chave gerenciada, criptografia, CMK, envelope encryption.

* **AWS Secrets Manager**

  * *Descrição:* Armazena e gerencia segredos como senhas e tokens.
  * *Palavras-chave:* segredo, rotação automática, acesso seguro.

* **SSM Parameter Store**

  * *Descrição:* Armazenamento seguro de parâmetros de configuração e segredos.
  * *Palavras-chave:* parâmetro, SecureString, versionamento, chave KMS.

* **AWS STS (Security Token Service)**

  * *Descrição:* Geração de credenciais temporárias para acessar recursos AWS.
  * *Palavras-chave:* AssumeRole, sessão, federado, temporário.

* **AWS Certificate Manager (ACM)**

  * *Descrição:* Gerencia certificados SSL/TLS para aplicações AWS.
  * *Palavras-chave:* certificado, HTTPS, domínio, validação.

* **AWS WAF**

  * *Descrição:* Firewall para aplicações web contra ataques comuns.
  * *Palavras-chave:* regras, SQL injection, XSS, ACL web.

* **AWS CloudHSM**

  * *Descrição:* Módulo de segurança de hardware gerenciado para chaves criptográficas.
  * *Palavras-chave:* HSM, FIPS 140-2, criptografia dedicada.

* **Amazon Macie**

  * *Descrição:* Detecta dados confidenciais (como PII) armazenados no S3.
  * *Palavras-chave:* PII, classificação, auditoria.

* **AWS RAM (Resource Access Manager)**

  * *Descrição:* Compartilhamento seguro de recursos entre contas da AWS.
  * *Palavras-chave:* compartilhamento, recurso, cross-account.

---

### 🚀 **Domínio 3: Implantação (24%)**

Foco em empacotar, construir, testar e fazer deploy de aplicações na AWS.

* **AWS CodeCommit**

  * *Descrição:* Repositório Git privado hospedado pela AWS.
  * *Palavras-chave:* controle de versão, Git, branch, repositório.

* **AWS CodeBuild**

  * *Descrição:* Compila e testa código em ambiente gerenciado.
  * *Palavras-chave:* buildspec.yml, ambiente de build, CI.

* **AWS CodePipeline**

  * *Descrição:* Orquestração de pipelines de CI/CD.
  * *Palavras-chave:* estágio, ação, gatilho, pipeline.

* **AWS CodeDeploy**

  * *Descrição:* Deploy automatizado para instâncias EC2, ECS ou Lambda.
  * *Palavras-chave:* aplicação, grupo de destino, AppSpec, blue/green.

* **AWS Elastic Beanstalk**

  * *Descrição:* Serviço PaaS que gerencia o deploy de aplicações web.
  * *Palavras-chave:* ambiente, aplicação, plataforma, escalabilidade.

* **AWS CloudFormation**

  * *Descrição:* Infraestrutura como código para provisionamento automatizado.
  * *Palavras-chave:* template, stack, recurso, YAML.

* **AWS Copilot**

  * *Descrição:* CLI para desenvolver, lançar e operar aplicações em contêiner.
  * *Palavras-chave:* serviço, ambiente, deploy, contêiner.

* **Amazon ECS, ECR, Fargate**

  * *Descrição:* ECS orquestra contêineres, ECR armazena imagens, Fargate executa serverless.
  * *Palavras-chave:* cluster, task, container, imagem Docker.

* **Amazon EKS**

  * *Descrição:* Kubernetes gerenciado na AWS.
  * *Palavras-chave:* cluster, node, pod, kubectl.

* **AWS SAM**

  * *Descrição:* Framework para construir aplicações serverless com infraestrutura como código.
  * *Palavras-chave:* template.yaml, função Lambda, API Gateway, SAM CLI.

* **AWS Amplify**

  * *Descrição:* Desenvolvimento e deploy de aplicações web e mobile com backend.
  * *Palavras-chave:* hospedagem, CI/CD, autenticação, GraphQL.

* **AWS AppConfig**

  * *Descrição:* Gerenciamento de configuração de aplicações em tempo real.
  * *Palavras-chave:* rollout, configuração dinâmica, ambiente, aplicação.

---

### 🌍 **Domínio 4: Resolução de problemas e otimização (18%)**

Foco em monitoramento, rastreamento, logging e melhoria de performance.

* **Amazon CloudWatch**

  * *Descrição:* Coleta e monitora logs, métricas e alarmes.
  * *Palavras-chave:* métrica, log group, alarm, dashboard.

* **AWS X-Ray**

  * *Descrição:* Serviço de rastreamento de requisições em aplicações distribuídas.
  * *Palavras-chave:* trace, segment, latência, debugging.

* **AWS CloudTrail**

  * *Descrição:* Registra chamadas de API para auditoria e segurança.
  * *Palavras-chave:* eventos, logs de API, segurança, trilha.

* **AWS Config**

  * *Descrição:* Serviço de inventário e auditoria de configurações de recursos AWS.
  * *Palavras-chave:* conformidade, histórico, regra, alteração.

* **AWS Trusted Advisor**

  * *Descrição:* Análise de boas práticas e recomendações.
  * *Palavras-chave:* segurança, performance, economia.

* **Amazon OpenSearch**

  * *Descrição:* Análise e visualização de dados de log com Elasticsearch.
  * *Palavras-chave:* índice, busca, Kibana, logs.

* **Amazon SES**

  * *Descrição:* Serviço de envio de e-mails transacionais e marketing.
  * *Palavras-chave:* SMTP, verificação, domínio, bounce.

* **Amazon CloudFront**

  * *Descrição:* Rede de entrega de conteúdo (CDN) para reduzir latência.
  * *Palavras-chave:* distribuição, edge, cache, TTL.

* **Elastic Load Balancer (ELB)**

  * *Descrição:* Balanceamento de carga entre instâncias ou serviços.
  * *Palavras-chave:* listener, target group, health check.

* **Amazon RDS Performance Insights**

  * *Descrição:* Ferramenta para monitorar performance de bancos RDS.
  * *Palavras-chave:* workload, otimização, métrica.

* **Amazon EMR / AWS Glue**

  * *Descrição:* Processamento e transformação de dados em larga escala.
  * *Palavras-chave:* ETL, big data, Spark, PySpark, transformações.

---

