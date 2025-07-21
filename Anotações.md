# AWS-Practitioner
Estudos AWS Cloud


1 - Cloud Computing
Benefícios:

Velocidade: Permite a implantação e o desenvolvimento de soluções em questão de segundos.

Atualizações automáticas: A própria AWS realiza as atualizações de infraestrutura, sem interrupções nos serviços, e com possibilidade de integração com outras ferramentas.

Redução de custos: O custo com infraestrutura em nuvem é significativamente menor em comparação aos modelos tradicionais.

Segurança de dados: Possui recursos avançados de segurança e backup, garantindo a proteção das informações.

Escalabilidade: A infraestrutura se ajusta automaticamente — ou manualmente — conforme a demanda. É possível aumentar memória, disco ou CPU em poucos segundos, conforme necessário.



2 - Tipos de Cloud

IaaS (Infraestrutura como Serviço):
Você paga para utilizar a infraestrutura de uma provedora de Cloud. É o modelo mais básico, onde a provedora gerencia apenas a infraestrutura (servidores, armazenamento e rede), enquanto você é responsável pela instalação, configuração e gerenciamento do sistema operacional, aplicativos e dados.

PaaS (Plataforma como Serviço):
Você paga para utilizar uma plataforma completa fornecida pela provedora, que inclui tanto a infraestrutura quanto ferramentas de desenvolvimento e gerenciamento. A responsabilidade da provedora aumenta, cuidando da infraestrutura e da plataforma, enquanto você se concentra apenas no desenvolvimento e execução das aplicações.

SaaS (Software como Serviço):
Você utiliza um software pronto, acessado pela internet, sem se preocupar com a infraestrutura ou plataforma. A provedora gerencia tudo (infraestrutura, plataforma e software), e o usuário final apenas consome o serviço. É o modelo com o menor nível de responsabilidade do cliente.


Responsabilidades nos Modelos de Cloud Computing:

IaaS (Infrastructure as a Service)
Gerenciado pela provedora:
  ✅ Virtualização
  ✅ Servidores (Servers)
  ✅ Armazenamento (Storage)
  ✅ Rede (Network)

Gerenciado pelo cliente (você):
  ⚙️ Aplicações
  ⚙️ Dados (Data)
  ⚙️ Runtime
  ⚙️ Middleware
  ⚙️ Sistema Operacional (OS)

PaaS (Platform as a Service)
Gerenciado pela provedora:
  ✅ Rede (Network)
  ✅ Armazenamento (Storage)
  ✅ Servidores (Servers)
  ✅ Virtualização
  ✅ Sistema Operacional
  ✅ Middleware
  ✅ Runtime

Gerenciado pelo cliente (você):
  ⚙️ Dados (Data)
  ⚙️ Aplicações (Applications)

SaaS (Software as a Service)
Gerenciado pela provedora:
  ✅ Rede (Network)
  ✅ Armazenamento (Storage)
  ✅ Servidores (Servers)
  ✅ Virtualização
  ✅ Sistema Operacional
  ✅ Middleware
  ✅ Runtime
  ✅ Dados (Data)
  ✅ Aplicações (Applications)



Cloud Publica, Hybrida e  Privada

1. Nuvem Pública (Public Cloud)

Definição: Infraestrutura é disponibilizada ao público por um provedor terceirizado (ex: AWS, Azure, Google Cloud).

Acesso: Compartilhado entre vários clientes (multitenancy).

Vantagens: Escalabilidade, baixo custo inicial, manutenção feita pela provedora.

Exemplo: Usar o Amazon S3 para armazenar arquivos.

2. Nuvem Privada (Private Cloud)

Definição: Infraestrutura dedicada exclusivamente a uma única organização.

Acesso: Apenas pela própria organização (pode estar localmente ou em data centers de terceiros).

Vantagens: Maior controle, segurança e personalização.

Exemplo: Empresa que monta sua própria nuvem interna com OpenStack.

3. Nuvem Híbrida (Hybrid Cloud)

Definição: Combinação de nuvem pública e privada, funcionando de forma integrada para compartilhar dados e aplicações entre os ambientes.

Acesso: Parte interna (privada) e parte externa (pública), com integração segura entre elas.

Vantagens:

Flexibilidade: aproveita o melhor dos dois mundos.

Escalabilidade sob demanda usando recursos da nuvem pública.

Maior segurança para dados sensíveis mantidos na nuvem privada.

Exemplo: Uma empresa usa a nuvem privada para dados financeiros sensíveis e a pública para hospedar um site de e-commerce com alta demanda.



AWS Services 

Principais Serviços da AWS
1. Cálculo (Compute)
Amazon EC2 (Elastic Compute Cloud): Máquinas virtuais escaláveis na nuvem.

AWS Lambda: Executa seu código sob demanda, sem necessidade de servidores (serverless).

Elastic Beanstalk: Plataforma para implantar e escalar automaticamente aplicações web.

2. Armazenamento (Storage)
Amazon S3 (Simple Storage Service): Armazenamento de objetos, ideal para backups, imagens, vídeos etc.

Amazon EBS (Elastic Block Store): Armazenamento em bloco usado com EC2.

Amazon Glacier: Armazenamento de arquivos de longo prazo e baixo custo.

3. Banco de Dados (Databases)
Amazon RDS (Relational Database Service): Banco de dados relacional gerenciado (MySQL, PostgreSQL, SQL Server, Oracle).

Amazon DynamoDB: Banco de dados NoSQL altamente escalável e gerenciado.

Amazon Aurora: Banco de dados relacional compatível com MySQL e PostgreSQL, com alto desempenho.

4. Redes e Entrega de Conteúdo (Networking & CDN)
Amazon VPC (Virtual Private Cloud): Rede virtual isolada na nuvem.

Amazon Route 53: Serviço de DNS e roteamento.

Amazon CloudFront: CDN (Content Delivery Network) para entrega rápida de conteúdo globalmente.

5. Segurança, Identidade e Conformidade
AWS IAM (Identity and Access Management): Controle de usuários e permissões.

AWS KMS (Key Management Service): Gerenciamento de chaves de criptografia.

AWS Shield: Proteção contra ataques DDoS.

6. Monitoramento e Gerenciamento
Amazon CloudWatch: Coleta de logs e monitoramento de recursos AWS.

AWS CloudFormation: Infraestrutura como código (IaC).

AWS Config: Auditoria e conformidade da configuração de recursos.



Modelo de Responsabilidade Compartilhada na AWS

A AWS adota um modelo de responsabilidade compartilhada, no qual tanto a AWS quanto o cliente têm responsabilidades específicas relacionadas à segurança e operação dos serviços em nuvem.

1. Responsabilidade da AWS ("Segurança da Nuvem")

A AWS é responsável por proteger a infraestrutura que executa todos os serviços oferecidos na Nuvem AWS:

Hardware (servidores, discos, roteadores, etc.)

Software de virtualização

Instalações físicas (datacenters)

Redes e infraestrutura global

Exemplos:

Manutenção dos data centers

Proteção contra ameaças físicas

Atualizações de hardware e infraestrutura

2. Responsabilidade do Cliente ("Segurança na Nuvem")

O cliente é responsável por tudo o que ele cria, carrega, configura e gerencia dentro da nuvem.

Gerenciamento de dados e criptografia

Configuração de segurança nos serviços (firewalls, grupos de segurança)

Gerenciamento de identidade e acesso (IAM)

Atualização de sistemas operacionais e aplicações (em EC2, por exemplo)

Exemplos:

Definir quem pode acessar o quê (via IAM)

Garantir que os dados armazenados estão criptografados

Monitorar logs e atividades com CloudTrail e CloudWatch

Resumo Visual (exemplo EC2):

AWS gerencia: Infraestrutura física, rede, virtualização

Cliente gerencia: Sistema operacional, atualizações, dados, permissões, aplicações

Esse modelo é essencial para entender até onde vai a segurança da AWS e onde começa a sua. Entender isso é fundamental para tirar a certificação AWS Cloud Practitioner.



🔷 1. Conceitos Principais da Infraestrutura Global
🟩 1.1. Região (Region)
Uma Região é uma área geográfica distinta que contém múltiplas Zonas de Disponibilidade (AZs).

Cada região é fisicamente isolada das outras para oferecer tolerância a falhas regionais.

Nomeadas como us-east-1 (Virgínia), sa-east-1 (São Paulo), etc.

📌 Exemplo:
A região São Paulo (sa-east-1) tem 3 Zonas de Disponibilidade.

🟩 1.2. Zona de Disponibilidade (Availability Zone - AZ)
Uma AZ é composta por um ou mais data centers físicos com energia, refrigeração e redes independentes.

As AZs de uma mesma região estão interconectadas por links redundantes e de baixa latência.

Você pode implantar seus recursos em múltiplas AZs para garantir alta disponibilidade e tolerância a falhas.

📌 Exemplo:
Na região us-east-1 (Norte da Virgínia), há 6 zonas de disponibilidade: us-east-1a, us-east-1b, ..., us-east-1f.

🟩 1.3. Localizações Locais (Local Zones)
Local Zones são extensões de uma região da AWS, localizadas próximas a grandes centros urbanos para oferecer latência ultra baixa.

Ideal para workloads como jogos, edição de vídeo e renderização.

🟩 1.4. Pontos de Presença (Edge Locations)
Usados principalmente pelos serviços de entrega de conteúdo como o Amazon CloudFront.

Servem como cache de conteúdo estático, reduzindo a latência para usuários finais.

🟩 1.5. Outposts, Wavelength, e AWS Snow Family
Esses são recursos especializados da infraestrutura global:

Outposts: extensão da infraestrutura da AWS para seu datacenter local (nuvem híbrida).

Wavelength: para aplicativos 5G de baixa latência, integrando AWS com redes móveis.

Snow: dispositivos físicos para migração ou computação em ambientes desconectados/extremos.

🌍 Resumo da Estrutura Hierárquica
scss
Copiar
Editar
Infraestrutura Global
├── Regiões (Regions)
│   ├── Zonas de Disponibilidade (AZs)
│   │   └── Data Centers
│   └── Local Zones
└── Edge Locations (CloudFront, Route 53, etc)
📊 Números Atualizados (2025 – estimativa)
+33 Regiões ativas.

+100 Zonas de Disponibilidade.

+450 Pontos de Presença (Edge Locations) em mais de 90 cidades.

Regiões futuras planejadas em países como México, Tailândia, Grécia e Malásia.

✅ Benefícios dessa Infraestrutura
Alta disponibilidade (você pode replicar entre AZs).

Redundância geográfica (entre regiões).

Redução de latência com Edge Locations.

Maior resiliência a falhas de energia, hardware e rede






