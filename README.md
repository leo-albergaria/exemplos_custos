# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
**Data:** 15 de abril de 2024  
**Empresa:** Abstergo Industries  
**Responsável:** José da Silva  

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por José da Silva. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1: Redução de custos de armazenamento
- **AWS S3 (Simple Storage Service)**
  - **Foco da ferramenta:** Armazenamento de objetos
  - **Descrição de caso de uso:** Migrar dados menos acessados para o armazenamento de objetos da AWS S3 para reduzir os custos de armazenamento.

### Etapa 2: Otimização de computação
- **AWS Lambda**
  - **Foco da ferramenta:** Computação sem servidor
  - **Descrição de caso de uso:** Implementar funções Lambda para processar eventos específicos, eliminando a necessidade de provisionamento e gerenciamento de servidores.

### Etapa 3: Aumento da eficiência operacional
- **AWS RDS (Relational Database Service)**
  - **Foco da ferramenta:** Banco de dados relacional gerenciado
  - **Descrição de caso de uso:** Migrar bancos de dados locais para o AWS RDS para aproveitar a escalabilidade e a automação do gerenciamento de banco de dados.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado reduzir os custos de armazenamento, otimizar a computação e aumentar a eficiência operacional. Isso resultará em uma melhoria significativa na eficiência e produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.


**Assinatura do Responsável pelo Projeto:**
José da Silva


## Anexos
- Documento de arquitetura da solução
- Planilha de custos estimados


# Documento de Arquitetura da Solução
## Visão Geral da Arquitetura
Este documento descreve a arquitetura técnica para a implementação de serviços AWS na Abstergo Industries. O projeto visa reduzir custos imediatos e aumentar a eficiência operacional por meio da utilização de serviços em nuvem.

## Diagrama de Arquitetura

## Componentes da Solução

### AWS S3 (Simple Storage Service)
- **Função**: Armazenamento de objetos.
- **Implementação**: Utilizado para armazenar dados menos acessados e arquivos estáticos.
- **Integração**: Integra-se com outros serviços para armazenamento e recuperação de dados.

### AWS Lambda
- **Função**: Computação sem servidor.
- **Implementação**: Utilizado para processamento de eventos específicos, como manipulação de arquivos no S3 e geração de relatórios.
- **Integração**: Dispara automaticamente em resposta a eventos definidos.

### AWS RDS (Relational Database Service)
- **Função**: Banco de dados relacional gerenciado.
- **Implementação**: Utilizado para armazenamento de dados transacionais e analíticos.
- **Integração**: Integra-se com aplicativos existentes por meio de conexões JDBC/ODBC.

## Escala e Desempenho
A arquitetura da solução foi projetada para escalar horizontalmente e garantir alto desempenho. O uso de serviços gerenciados da AWS permite dimensionamento automático e otimização de recursos de acordo com a demanda.

## Segurança
Os dados armazenados na AWS são protegidos por meio de políticas de controle de acesso, criptografia em repouso e em trânsito, e monitoramento contínuo de segurança. As permissões de acesso são concedidas com base no modelo de segurança de princípio do menor privilégio.

## Resiliência e Disponibilidade
A arquitetura da solução é altamente resiliente a falhas, com redundância de dados e serviços em várias zonas de disponibilidade. As instâncias EC2 e bancos de dados RDS são distribuídos em zonas de disponibilidade diferentes para garantir alta disponibilidade.

## Custos
O custo da solução é otimizado por meio da seleção cuidadosa dos serviços AWS e da implementação de práticas de otimização de custos, como dimensionamento automático e armazenamento de dados de acordo com a frequência de acesso.

## Considerações de Migração e Integração
A migração de dados existentes para a AWS foi realizada de forma gradual e planejada, minimizando o impacto nas operações comerciais. A integração com sistemas legados foi alcançada por meio de APIs e serviços de mensagens.

## Considerações de Manutenção e Suporte
A manutenção da solução é realizada por uma equipe dedicada de operações de nuvem, que monitora continuamente a integridade e o desempenho dos serviços AWS. As atualizações e correções de segurança são aplicadas regularmente para garantir a estabilidade e a segurança da infraestrutura.

## Plano de Implantação
O plano de implantação inclui uma série de etapas, desde a configuração inicial dos serviços AWS até a migração de dados e aplicativos. O cronograma de implantação é dividido em fases para facilitar o gerenciamento e minimizar o risco de interrupções nas operações comerciais.
