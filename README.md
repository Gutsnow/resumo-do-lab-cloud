# Resumo do Lab Cloud

Este repositório contém um resumo das lições aprendidas sobre computação em nuvem utilizando a plataforma Microsoft Azure, durante o desenvolvimento do laboratório na DIO.

## Aprendizados

No primeiro módulo de computação em nuvem, aprendi sobre os diferentes tipos de nuvem: **pública**, **privada** e **híbrida**, além de entender em quais cenários cada modelo é mais adequado. Também explorei o conceito fundamental de computação em nuvem e as diferenças entre os modelos de despesas **CapEx (Capital Expenditure)** e **OpEx (Operational Expenditure)**, compreendendo como essas abordagens impactam os custos de TI.

### Elasticidade e Escalabilidade

- **Escalabilidade** refere-se à capacidade de um sistema de aumentar ou diminuir recursos de forma planejada. Pode ser:
  - **Vertical**: Aumentar a capacidade de um recurso específico (por exemplo, adicionar mais memória ou CPU a um servidor).
  - **Horizontal**: Adicionar mais instâncias ou servidores para distribuir a carga.
  
- **Elasticidade**, por outro lado, é a capacidade do sistema de ajustar automaticamente os recursos de acordo com a demanda, expandindo ou reduzindo rapidamente conforme necessário. Diferente da escalabilidade, a elasticidade não requer planejamento prévio, pois os recursos são ajustados automaticamente com base nas solicitações e uso do sistema.

### SLA (Service Level Agreement)

O **SLA** é um contrato oferecido pela Microsoft que define os níveis de disponibilidade e confiabilidade dos serviços da plataforma Azure. Ele especifica o tempo de atividade garantido e descreve as compensações (ou créditos) que o cliente pode receber caso o serviço não atinja esses níveis. 

Por exemplo, o SLA para máquinas virtuais pode garantir até **99,9%** ou até **99,99%** de disponibilidade, dependendo da configuração. O SLA define quanto tempo um serviço pode estar indisponível por mês e, com base na porcentagem escolhida, o cliente pode optar por um nível de serviço mais elevado para garantir maior confiabilidade.

# Arquiteturas de Nuvem

Este documento descreve os principais modelos de arquitetura em nuvem e suas características.

## Tipos de Arquiteturas

Existem três modelos principais de arquitetura em nuvem, cada um com um nível de responsabilidade para o administrador:

### 1. PaaS (Platform as a Service)
Funciona como uma plataforma onde podemos alocar recursos, utilizar e monitorar. Requer uma responsabilidade intermediária do administrador, como a gestão de segurança, mas grande parte da infraestrutura é gerenciada pelo provedor.

### 2. IaaS (Infrastructure as a Service)
Oferece a infraestrutura básica, como servidores, armazenamento e redes, de forma virtualizada. Nesse modelo, o administrador tem mais responsabilidades, incluindo a configuração, manutenção e segurança dos recursos.

### 3. SaaS (Software as a Service)
Fornece aplicativos prontos para uso, nos quais o administrador possui menos responsabilidades. Toda a manutenção e segurança do software são gerenciadas pelo provedor, permitindo ao usuário focar apenas no uso do aplicativo.

Cada modelo oferece diferentes níveis de controle e responsabilidade, proporcionando opções flexíveis para atender às necessidades específicas de cada organização.

