# ☁️ Introdução ao Microsoft Azure (Resumos)

Abaixo um resumo sobre a introdução aos conceitos fundamentais da plataforma de nuvem Microsoft Azure, abordando alguns de seus principais serviços, os tipos de serviços em nuvem e os modelos de despesas. Ideal para iniciantes que buscam entender como a computação em nuvem pode otimizar operações e reduzir custos.

## 📚 Resumo do Conteúdo do Curso Introdução à Computação em Nuvem

### 💳 Modelo Baseado em Consumo

O Azure opera sob um modelo de pagamento por consumo, onde os usuários pagam apenas pelos recursos que realmente utilizam, tornando possível uma previsão de custos mais precisa e evitando gastos excessivos.

### 🔧 Serviços do Azure

O curso apresentou alguns dos serviços mais utilizados do Azure, incluindo:

- **Computação**: Serviços para criação e gestão de máquinas virtuais e aplicações.
- **Armazenamento**: Soluções para armazenamento seguro e escalável de dados.
- **Banco de Dados**: Serviços gerenciados de banco de dados para armazenamento e análise de dados.
- **Rede**: Ferramentas para conectar, proteger e otimizar redes na nuvem.
- **Segurança**: Recursos de segurança integrados para proteger dados e conformidade.

### 🔨 Modelos de Serviço em Nuvem

O curso abordou os principais modelos de serviço em nuvem:

- **Nuvem Privada**: Um ambiente de nuvem exclusivo de uma organização, controlado internamente e não acessível ao público. Oferece controle total sobre segurança e manutenção, ideal para empresas com requisitos rigorosos de conformidade.

- **Nuvem Pública**: Serviços de nuvem disponibilizados por um provedor de hosting, acessíveis via Internet. Reduz despesas de capital (CapEx) e é baseada no modelo de pagamento por uso, proporcionando flexibilidade e escalabilidade.

- **Nuvem Híbrida**: Combina elementos de nuvens privadas e públicas, permitindo que as organizações executem aplicativos no ambiente mais adequado, oferecendo flexibilidade e controle sobre segurança e conformidade.

### 💰 Modelos de Custo: CapEx e OpEx

- **CapEx (Despesas de Capital)**: Investimentos iniciais em infraestrutura física, cujos valores se depreciam com o tempo. Indicado para empresas que preferem controlar seus próprios recursos.

- **OpEx (Despesas Operacionais)**: Gastos baseados no consumo, em que a empresa paga conforme o uso dos serviços. Esse modelo permite flexibilidade financeira e melhor controle de custos ao longo do tempo.

---

## 🌐 Resumo do Conteúdo do Curso Benefícios da Nuvem: Escalabilidade e Elasticidade

A computação em nuvem oferece diversos benefícios para empresas e desenvolvedores ao permitir a criação de sistemas flexíveis, seguros e eficientes. Abaixo estão alguns dos principais aspectos que contribuem para esses benefícios.

### 🕒 Disponibilidade
A nuvem fornece alta disponibilidade, garantindo que os sistemas estejam acessíveis de forma contínua, mesmo em caso de falhas. Isso é possível graças a data centers redundantes e recursos de failover, que mantêm o sistema ativo em qualquer cenário. 

Os contratos de serviços em nuvem normalmente incluem um **Acordo de Nível de Serviço (SLA)**, que define o tempo mínimo de disponibilidade garantido pelo provedor. Este acordo assegura que o serviço manterá uma alta taxa de funcionamento e, caso o SLA não seja cumprido, a empresa pode ser compensada conforme estipulado no contrato.

### 📈 Escalabilidade
A escalabilidade permite aumentar ou reduzir os recursos conforme a necessidade do sistema cresce, seja verticalmente (adicionando capacidade ao mesmo servidor) ou horizontalmente (adicionando mais servidores). Isso é essencial para acomodar um número variável de usuários e cargas de trabalho sem comprometer o desempenho.

### 🔄 Elasticidade
A elasticidade refere-se à capacidade da nuvem de ajustar automaticamente os recursos conforme a demanda aumenta ou diminui, permitindo um uso mais eficiente e otimizado dos recursos e custos.

### 🔒 Confiabilidade
A nuvem oferece alta confiabilidade ao armazenar dados e aplicações com redundância, garantindo que o sistema funcione corretamente mesmo em caso de falhas. Essa confiabilidade reduz o tempo de inatividade e melhora a experiência do usuário final.

### 📊 Previsibilidade
Com a nuvem, empresas têm previsibilidade de custos e desempenho. O modelo de pagamento por uso permite um controle mais preciso dos gastos, enquanto o desempenho previsível garante que o sistema opere conforme as necessidades do negócio.

### 🔐 Segurança
A segurança na nuvem é garantida por um modelo de responsabilidade compartilhada, onde tanto o provedor quanto o cliente têm responsabilidades específicas. O provedor de nuvem é responsável pela segurança física e infraestrutura de hardware, enquanto o cliente é responsável pelas configurações de segurança dos dados e das aplicações que utiliza. Cabe ao cliente ou técnico configurar permissões, criptografia e backups adequadamente, além de seguir as normas legais e regulatórias para proteger dados sensíveis.

### 🛡️ Governança
A governança é facilitada com ferramentas de monitoramento, controle de acesso e políticas automatizadas. Isso permite que as empresas mantenham o controle sobre quem acessa os recursos, como eles são usados e que normas devem ser seguidas.

### ⚙️ Gerenciabilidade
A nuvem oferece uma gerenciabilidade simplificada com ferramentas de automação e monitoramento em tempo real. Isso permite que as equipes de TI administrem a infraestrutura de forma centralizada, gerenciando configurações, atualizações e recursos com facilidade.

### 📄 SLA (Acordo de Nível de Serviço)
O **Acordo de Nível de Serviço (SLA)** especifica o tempo mínimo de disponibilidade garantido pelo provedor de nuvem, influenciando diretamente os custos. Quando uma aplicação precisa de alta disponibilidade (como sistemas de pagamento), é necessário contratar um SLA mais elevado, o que implica em custos maiores mas garante um funcionamento mais contínuo e confiável. Para aplicações com menor criticidade, como sistemas de teste, pode-se optar por SLAs com menor disponibilidade e custos reduzidos.

**Exemplo**: Um serviço financeiro que processa transações 24/7 precisará de um SLA de 99.99% para garantir disponibilidade máxima. Já um ambiente de desenvolvimento pode ter um SLA de 95%, reduzindo custos.

Esses benefícios fazem da nuvem uma escolha cada vez mais vantajosa para empresas que buscam flexibilidade, segurança e otimização de custos para suas operações.

---

## 🌥️ Resumo do Conteúdo do Curso Tipos de Serviço na Nuvem

Existem diferentes tipos de serviços na nuvem, cada um com um nível específico de controle, flexibilidade e responsabilidade. Estes modelos permitem que as empresas escolham o tipo de serviço mais adequado às suas necessidades e orçamento.

### 🖥️ IaaS (Infrastructure as a Service)

**Infraestrutura como Serviço** oferece recursos de infraestrutura básica, como máquinas virtuais, armazenamento e redes, permitindo que as empresas gerenciem seu próprio sistema operacional e aplicações.

- **Exemplo**: Usar o **Microsoft Azure Virtual Machines** para configurar e gerenciar máquinas virtuais com diferentes sistemas operacionais, sem a necessidade de adquirir ou manter hardware físico.

### 🚀 PaaS (Platform as a Service)

**Plataforma como Serviço** fornece uma plataforma completa para desenvolver, gerenciar e hospedar aplicativos. Este modelo permite que os desenvolvedores se concentrem no código e na lógica do aplicativo, sem se preocupar com a infraestrutura subjacente.

- **Exemplo**: O **Azure App Service** permite que você implemente e escale aplicativos web e APIs sem a necessidade de configurar o servidor e as redes, oferecendo ferramentas integradas de monitoramento e escalabilidade.

### 🌐 SaaS (Software as a Service)

**Software como Serviço** entrega aplicativos prontos para uso diretamente para o usuário final, com todo o gerenciamento de infraestrutura, armazenamento e dados sendo responsabilidade do provedor de nuvem. Os usuários acessam o software através da Internet, geralmente por meio de uma assinatura.

- **Exemplo**: O **Microsoft 365** (antigo Office 365) é uma suíte de produtividade que inclui Word, Excel, PowerPoint, entre outros. Ele está disponível na nuvem e acessível de qualquer dispositivo, sem necessidade de instalação local.

### 🔐 Modelo de Responsabilidade Compartilhada

No modelo de responsabilidade compartilhada, tanto o provedor de nuvem quanto o cliente têm responsabilidades de segurança distintas:

- O **provedor de nuvem** é responsável por proteger a infraestrutura física, os serviços e a rede subjacente.
- O **cliente** é responsável pela segurança de seus dados, aplicativos e configurações, além de controlar o acesso e a configuração dos serviços que utiliza.

Para mais informações sobre responsabilidade compartilhada, consulte a [documentação oficial da Microsoft](https://learn.microsoft.com/training/modules/describe-cloud-service-types/1-introduction).

Esses modelos de serviço oferecem uma ampla gama de opções e benefícios, permitindo que as empresas escolham a abordagem de nuvem que melhor se adapta aos seus objetivos e necessidades.

---

## ☁️ Resumo do Curso: Componentes de Arquitetura do Azure

### 🌍 Regiões Globais em Cloud

- 🧭 **Criação de recursos em regiões estratégicas:**  
  Permite criar recursos na região mais próxima do cliente final para melhorar a performance.  
  _Exemplo: Uma empresa com sede no Brasil e operação na Europa pode criar recursos em West Europe para atender usuários locais._

- 💰 **Atenção aos custos por região:**  
  Preços variam entre regiões.  
  _Exemplo: Uma VM em "East US" pode ter custo diferente da mesma VM em "Brazil South"._

- 🏙️ **Zonas de Disponibilidade:**  
  São datacenters separados fisicamente dentro de uma mesma região para garantir alta disponibilidade.  
  _Exemplo: Criar VMs replicadas em diferentes zonas de "Brazil South"._

- 🌐 **Backbone global da Microsoft:**  
  Infraestrutura própria que conecta regiões e garante desempenho e segurança.

- 🔒 **Verificação de restrições legais:**  
  Algumas legislações, como a LGPD, proíbem que dados de cidadãos saiam do país.  
  _Exemplo: Aplicações com dados sensíveis devem ser hospedadas em regiões do Brasil._

- 📍 **Pares de Regiões:**  
  Azure emparelha regiões com no mínimo 300 milhas de separação para fins de replicação e recuperação.  
  _Exemplo: "Brazil South" pode ter um par de recuperação em outra região._

- 🔁 **Replicação automática:**  
  Alguns serviços replicam dados automaticamente para uma região secundária.  
  _Exemplo: Azure Storage com geo-redundância._

- 🏛️ **Regiões Soberanas:**  
  Regiões exclusivas para uso governamental, com instâncias isoladas.  
  _Exemplo: A Microsoft opera na China via a empresa 21Vianet._

### 📦 Grupos de Recursos no Azure

- 🧱 **Agrupamento de recursos relacionados:**  
  VMs, storages, bancos de dados e redes podem ser agrupados em um mesmo grupo de recurso.  
  _Exemplo: Todos os recursos de um sistema de RH podem estar no grupo "Recursos-RH"._

- 🗂️ **Organização por contexto:**  
  Facilita o controle por ambiente, aplicação ou projeto.  
  _Exemplo: Criar um grupo de recurso separado para "Homologação" e outro para "Produção"._

- ✏️ **Nomes de grupos não são editáveis:**  
  Uma vez criado, o nome do grupo não pode ser alterado.  
  _Exemplo: Criou como "producao2024", não poderá renomear para "producao-main" depois._

- 🔄 **Movimentação de recursos entre grupos é possível.**

### 🧾 Assinaturas e Grupos de Gerenciamento

- 👥 **Várias assinaturas por conta:**  
  Uma conta pode possuir múltiplas assinaturas para dividir projetos, departamentos ou clientes.  
  _Exemplo: Uma empresa pode ter uma assinatura para o setor de TI e outra para o setor Financeiro._

- 📊 **Otimização de custos:**  
  Permite separar cobranças e analisar gastos por assinatura.

- 🏷️ **Grupos de gerenciamento:**  
  Aplicam políticas, permissões e limites em diversas assinaturas ao mesmo tempo.  
  _Exemplo: Criar um grupo de gerenciamento para aplicar uma política de segurança em todas as assinaturas de um departamento._

---

## 🖥️ Resumo do Curso: Computação e Rede na Azure

### ⚙️ Serviços de Computação

- 🧠 **Recursos sob demanda:**  
  Oferece CPU, memória, disco, rede e sistema operacional conforme necessidade do usuário.  
  _Exemplo: Criar uma VM com Windows Server para testes de software._

- 🖥️ **Máquinas Virtuais (VMs):**  
  Emulações de computadores físicos com total controle do SO. Modelo de responsabilidade compartilhada (IaaS).  
  _Exemplo: Migrar um servidor legado para o Azure com modelo lift-and-shift._

- 📈 **Conjuntos de Dimensionamento:**  
  Permitem escalar VMs automaticamente com base na demanda, com balanceamento de carga incluso.  
  _Exemplo: Aumentar automaticamente o número de VMs durante uma campanha de marketing._

- 🛡️ **Conjuntos de Disponibilidade:**  
  Dividem as VMs em domínios de falha (vertical) e de atualização (horizontal), garantindo resiliência.  
  _Exemplo: Distribuir três VMs entre racks distintos e horários diferentes de atualização._

- 💻 **Área de Trabalho Virtual do Azure (AVD):**  
  Virtualização de desktops e aplicativos baseada em nuvem.  
  _Exemplo: Fornecer acesso remoto a colaboradores sem comprar novos computadores._

### 📦 Serviços de Contêineres

- 📦 **Contêineres no Azure:**  
  Executam aplicativos de forma leve, sem a sobrecarga de um SO completo. Suporte a Docker e Kubernetes.  
  _Exemplo: Subir uma API em um contêiner com tempo de resposta otimizado._

- 🚢 **Kubernetes e Orquestração:**  
  Gerencia e automatiza a implantação de contêineres em escala.  
  _Exemplo: Orquestrar múltiplas instâncias de microserviços para balancear carga._

### ⚡ Computação Serverless

- ⚡ **Azure Functions:**  
  Executa código sob demanda com base em eventos, sem necessidade de provisionar infraestrutura.  
  _Exemplo: Criar uma função que processa uploads em um blob storage._

- 🌐 **Serviços de Aplicativos (App Services):**  
  PaaS gerenciado para criar e escalar aplicações web e APIs com suporte a várias linguagens.  
  _Exemplo: Hospedar uma API REST em Node.js com escalabilidade automática._

### 🌐 Rede no Azure

- 🌐 **Rede Virtual (VNet):**  
  Conecta recursos do Azure entre si, com a internet e com redes locais.  
  _Exemplo: Criar uma VNet com sub-redes separadas para banco de dados e aplicação._

- 🔐 **VPN Gateway:**  
  Estabelece comunicação criptografada entre uma rede local e a rede do Azure via internet.  
  _Exemplo: Conectar a infraestrutura da empresa ao Azure com segurança._

- ⚡ **ExpressRoute:**  
  Conexão de alta velocidade e privada entre o ambiente local e a nuvem, sem passar pela internet pública.  
  _Exemplo: Usar ExpressRoute para replicação de banco de dados com latência mínima._

- 🧭 **DNS do Azure:**  
  Gerencia nomes de domínio com suporte a RBAC (controle de acesso baseado em função) e monitoramento.  
  _Exemplo: Usar Azure DNS para gerenciar zonas DNS de aplicações web corporativas._

- ✏️ **Documentação Microsoft sobre o laboratório de Computação e Rede:**

  [VM Linux pelo Portal](https://learn.microsoft.com/pt-br/azure/virtual-machines/linux/quick-create-portal?tabs=ubuntu)
  
  [VM Windows pelo Portal](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)

  [Área de Trabalho Virtual do Azure](https://learn.microsoft.com/pt-br/azure/virtual-desktop/)

  [Aplicativo de Funções](https://learn.microsoft.com/pt-br/azure/azure-functions/functions-create-function-app-portal?tabs=core-tools&pivots=flex-consumption-plan)

  [Criação de Rede pelo Portal](https://learn.microsoft.com/pt-br/azure/virtual-network/quickstart-create-virtual-network?tabs=portal)

---

## 🗄️ Resumo do Curso: Armazenamento no Azure

### 🧾 Conceitos Gerais

- 🆔 **Nome único da conta de armazenamento:**  
  Deve ser **globalmente exclusivo**, com 3 a 24 caracteres.  
  _Exemplo: uma conta chamada `minhaempresa123` será acessada via `minhaempresa123.blob.core.windows.net`._

### 🧬 Tipos de Redundância

- 📍 **LRS (Local Redundant Storage):**  
  Replicação dentro de um único datacenter.  
  _Mais econômica, menor tolerância a falhas físicas._

- 🏢 **ZRS (Zone Redundant Storage):**  
  Replicação em zonas diferentes dentro da mesma região.  
  _Maior disponibilidade e resiliência regional._

- 🌎 **GRS (Geo-Redundant Storage):**  
  Replicação em regiões geograficamente distintas.  
  _Alta durabilidade com recuperação de desastre._

- 🛰️ **GZRS (Geo-Zone Redundant Storage):**  
  Combina redundância geográfica e de zonas.  
  _Máximo nível de durabilidade e disponibilidade._

### 📦 Serviços de Armazenamento

- 🧊 **Blob:**  
  Armazenamento massivo de dados não estruturados (texto, imagens, vídeos).  
  _Exemplo: armazenar backups ou uploads de usuários._

- 💽 **Disco:**  
  Usado por VMs, aplicativos e outros serviços como armazenamento de blocos.  
  _Exemplo: disco de sistema operacional de uma máquina virtual._

- 📬 **Fila (Queue):**  
  Gerenciamento de mensagens assíncronas entre componentes.  
  _Exemplo: fila de pedidos em um e-commerce._

- 📁 **Arquivos (Files):**  
  Compartilhamento de arquivos baseado em SMB.  
  _Exemplo: uso por múltiplos usuários em rede corporativa._

- 🗃️ **Tabelas (Tables):**  
  Armazenamento NoSQL de chave/atributo para dados estruturados.  
  _Exemplo: tabela de logs ou registros rápidos._

### 🌍 Pontos de Extremidade

- 🌐 **Formato de endpoint dos serviços:**  
  `{nomedaconta}.{tipodeserviço}.core.windows.net`  
  _Exemplo: `minhaempresa.blob.core.windows.net`_

### 🧊 Camadas de Acesso

- 🔁 **Frequente:**  
  Otimizada para armazenamento de dados acessados com frequência.

- 💤 **Esporádico:**  
  Otimizada para armazenamento de dados acessados com pouca frequência  
  e armazenados por pelo menos **30 dias**.

- 🧊 **Frio:**  
  Otimizado para o armazenamento de dados acessados com pouca frequência  
  e armazenados por pelo menos **90 dias**.

- 🪦 **Arquivo Morto:**  
  Otimizada para armazenamento de dados acessados raramente  
  e armazenados por pelo menos **180 dias**, com requisitos de **latência flexíveis**.

### 🚚 Migração e Ferramentas

- 📦 **Azure Data Box:**  
  Serviço físico para transferir grandes volumes de dados (até 80 TB).  
  _Exemplo: migração de datacenter para nuvem._

- 🔧 **AzCopy:**  
  Utilitário de linha de comando para **cópia unidirecional** de arquivos/blobs.  
  _Exemplo: copiar arquivos locais para Blob Storage._

- 🧑‍💻 **Gerenciador de Armazenamento do Azure:**  
  Interface gráfica multiplataforma (Windows, macOS, Linux).  
  _Internamente utiliza o AzCopy._

- 🔄 **Sincronização de Arquivos do Azure:**  
  Sincronização **bidirecional** entre nuvem e arquivos locais.  
  _Mantém localmente os arquivos mais acessados e libera espaço automaticamente._
