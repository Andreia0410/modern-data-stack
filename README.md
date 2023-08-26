# Modern Data Stack
airbyte-dbt-airflow-snowflake-metabase



Tarefas:

Infraestrutura:

- Setup do ambiente de desenvolvimento (Hardware, Software - Linux, Python, Docker, Curl, Pip, Git, Npm, etc...) X
- Setar as Permissoes do Gitpod ao Repositorio no Github X
- Subir o Airbyte via docker X
- Subir o Airflow via docker X
- Subir o Metabase via docker X
- Criar o script de execução ?
- Testar a Execução ?
- Snowflake Data Warehouse:
- Criar a Conta no SnowFlake X
    Verificar a existência das tabelas X
    Obter os links de conexão e nome da conta X

Extração:

No Airbyte:

1. Conectar com as origens baseadas nos Csvs X
2. Criar as entidades no snowflake através do script base da documentação X
3. Conectar o destino no snowflake X
4. Criar as conexões do airbyte associando as origens ao destino X
5. Testar as conexões X

Preparação:

No Airbyte (Destination Loading Method):

1. Local Staging (Ambiente de Desenvolvimento) X
2. Cloud Staging (Ambiente de Produção) X

Transformação:

No Dbt:

1. Criação da Conta X
2. Conexão com o Github X
3. Criação do Dbt Project X
4. Criação do Profile de conexão com o snowflake X
5. Criação do Schema X
6. Criação dos Modelos Base X
7. Criação do Modelo Relacionado X
8. Visualização gráfica do modelo X
9. Teste de execução X
10. Commits, Branches, Pull Requests, Merges no Github X
11. Obtenção do link de conexão com o Airbyte X

Visualização:

No Metabase:

1. Conectar Metabase com o Snowflake
2. Criar uma Question
3. Criar um Dashboard
4. Adicionar uma Question
5. Visualizar o Resultado

Orquestração:

No Airflow:

1. Criar a dag
2. Criar a Docker network
3. Incluir nos composes a network criada
4. Setup Up no serviço
5. Testar a conexao entre os containers do airflow e do airbyte
6. Criar as conexões com o Airbyte através do script
7. Testar a execução do pipeline
