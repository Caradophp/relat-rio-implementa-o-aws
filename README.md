# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 25 de Dezembro de 2025
Empresa: Abstergo Industries 
Responsável: Luciano Friebe Feigl

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Luciano Friebe Feigl**. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos, focando em otimização e eficiência operacional.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma focada em um serviço AWS que oferece potencial de redução de custos imediata. A seguir, serão descritas as etapas do projeto, detalhando o foco da ferramenta e um caso de uso prático para a Abstergo Industries.

### Etapa 1: AWS Cost Explorer
O **AWS Cost Explorer** é uma ferramenta nativa da AWS que permite visualizar, entender e gerenciar os custos e o uso da AWS ao longo do tempo.

- **Nome da ferramenta:** AWS Cost Explorer
- **Foco da ferramenta:** Visualização, análise e otimização de custos.
- **Descrição de caso de uso:** Utilizar o recurso de **Otimização de Recursos** do Cost Explorer para identificar instâncias Amazon EC2 que estão ociosas ou subutilizadas. A Abstergo Industries pode, com base nas recomendações, redimensionar (rightsizing) ou encerrar essas instâncias, gerando uma economia imediata ao eliminar o desperdício de recursos computacionais.

### Etapa 2: AWS Savings Plans
O **AWS Savings Plans** é um modelo de preços flexível que oferece descontos significativos em troca de um compromisso de uso por hora (em termos de USD/hora) por um período de 1 ou 3 anos.

- **Nome da ferramenta:** AWS Savings Plans (Plano de Economia de Computação)
- **Foco da ferramenta:** Redução de custos de computação com flexibilidade.
- **Descrição de caso de uso:** A Abstergo Industries pode analisar seu histórico de uso estável de recursos de computação (EC2, Fargate, Lambda) e se comprometer com um gasto por hora. Este compromisso se aplica automaticamente a qualquer uso de computação elegível, independentemente da região, família de instâncias ou sistema operacional. Isso permite uma economia de até **72%** em comparação com os preços sob demanda, garantindo uma redução de custos previsível e imediata para a carga de trabalho base.

### Etapa 3: Amazon EC2 Spot Instances
As **Amazon EC2 Spot Instances** permitem que os usuários solicitem capacidade de computação excedente da AWS com descontos de até **90%** em relação aos preços sob demanda.

- **Nome da ferramenta:** Amazon EC2 Spot Instances
- **Foco da ferramenta:** Utilização de capacidade excedente para cargas de trabalho flexíveis.
- **Descrição de caso de uso:** Implementar as Spot Instances para cargas de trabalho que são tolerantes a interrupções e não críticas, como ambientes de desenvolvimento e teste, processamento de Big Data em lote, ou tarefas de CI/CD (Integração Contínua/Entrega Contínua). Ao migrar essas cargas de trabalho para Spot Instances, a Abstergo Industries obtém uma redução drástica e imediata nos custos de infraestrutura para esses ambientes.

## Tabela de Resumo dos Serviços

| Serviço AWS | Foco Principal | Potencial de Economia | Ação Imediata para Abstergo Industries |
| :--- | :--- | :--- | :--- |
| **AWS Cost Explorer** | Análise e Otimização | Variável (Eliminação de Desperdício) | Identificar e Redimensionar/Encerrar Instâncias Ociosas |
| **AWS Savings Plans** | Compromisso de Uso | Até 72% | Comprometer-se com o uso base de computação por 1 ou 3 anos |
| **Amazon EC2 Spot Instances** | Capacidade Excedente | Até 90% | Migrar Cargas de Trabalho Tolerantes a Falhas (Dev/Test, CI/CD) |

## Conclusão
A implementação das ferramentas **AWS Cost Explorer**, **AWS Savings Plans** e **Amazon EC2 Spot Instances** na empresa **Abstergo Industries** tem como esperado a **otimização do orçamento de TI e a redução drástica dos gastos operacionais**, o que aumentará a eficiência e a produtividade da empresa. A economia gerada pode ser reinvestida em inovação e novos projetos tecnológicos. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

1. Guia de Início Rápido: Configuração e Uso do AWS Cost Explorer.
2. Planilha de Projeção de Custos: Comparativo On-Demand vs. Savings Plans.
3. Manual de Melhores Práticas para Implementação de EC2 Spot Instances.

Assinatura do Responsável pelo Projeto:

_________________________________________
**Luciano Friebe Feigl**
