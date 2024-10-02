# **Treinamento de Stack Moderna de Dados**

# **Introdução**

- Objetivo do treinamento: apresentar Airbyte, DBT, Snowflake e Airflow na prática
- Foco principal: transformação de dados (DBT)
- Outras ferramentas serão abordadas de forma mais superficial

# **Airbyte**

- Ferramenta de ingestão de dados (EL do ELT)
- Extrai dados de diferentes fontes e carrega em um destino (ex: Snowflake)
- Arquitetura simples, com Web App Server, Scheduler e Workers
- Ampla variedade de conectores pré-construídos

# **Snowflake**

- Data Warehouse moderno, multi-cloud
- Desacoplamento entre armazenamento e computação
- Carregamento de dados extremamente rápido (ex: de 30 min para 21 seg)
- Pricing baseado em créditos, com opções de armazenamento e computação separadas

# **DBT (Data Build Tool)**

- Framework para transformação de dados
- Foco em simplicidade e produtividade
- Utiliza SQL para transformações
- Suporte a materialização de modelos (tabelas, views, incrementais, efêmeros)
- Integração com Git para controle de versão
- Testes embutidos para validação dos modelos

# **Airflow**

- Orquestrador de workflows de dados
- Arquitetura com Web Server, Scheduler e Workers
- Execução de DAGs (Directed Acyclic Graphs) para orquestrar os jobs
- Integração com o DBT para execução de pipelines

# **Motivação para a Stack Moderna de Dados**

- Complexidade de manter uma infraestrutura tradicional de dados
- Necessidade de simplificar a entrega de dados para os usuários finais
- Conceito de "data mesh" e descentralização dos dados
- Ferramentas modernas permitem agilidade e produtividade

# **Exemplo Prático**

- Ingestão de dados de banco SQL Server e MongoDB usando Airbyte
- Carregamento dos dados no Snowflake
- Transformação dos dados usando DBT
- Orquestração do pipeline usando Airflow

# **Conclusão**

- Importância da adoção da Stack Moderna de Dados
- Disponibilização da gravação do treinamento
- Feedback e melhorias para os próximos workshops
- Novidades da comunidade para 2023
