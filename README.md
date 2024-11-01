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

