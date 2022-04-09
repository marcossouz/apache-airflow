# Apache Airflow na Prática: Do ZERO ao DEPLOY, com Python!

Implemente pipelines de dados com exemplos práticos utilizando o Apache Airflow, Big Data, PostgreSQL e Linux.

# Conteúdo

- [x] 1 - CONHECENDO O APACHE AIRFLOW
  - [x] 1.1 - Introdução ao Apache AIRFLOW
  - [x] 1.2 - Principais Características do Apache AIRFLOW - Parte I
  - [x] 1.3 - Principais Características do Apache AIRFLOW - Parte II
  - [x] 1.4 - Vamos Imaginar Um Caso de Uso Bem Comum para o Apache AIRFLOW
  - [x] 1.5 - Porque usar o Apache AIRFLOW?
  - [x] 1.6 - Mais Motivos para Usar o Apache AIRFLOW
- [x] 2 - MERGULHANDO NO APACHE AIRFLOW
  - [x] 2.1 - Arquitetura do Apache Airflow
  - [x] 2.2 - Conhecendo os DAGs
  - [x] 2.3 - Airflow - Default Parameters, Context Manager e Operators
  - [x] 2.4 - Airflow - Hooks e Pools
  - [x] 2.5 - Airflow - Connections e Filas
  - [x] 2.6 - Airflow - XCOMS, Variáveis e Branching
  - [x] 2.7 - Airflow - SUB DAGs e SLA (Service Level Agreement)
  - [x] 2.8 - Airflow - Trigger Rules e Last Execution Only
  - [x] 2.9 - Airflow - Zombies/Undeads, Cluster Policies, Jinja Templating e Packaged DAGs
  - [x] 2.10 - Airflow - Conhecendo o Recurso "BACKFILL"
- [x] 3 - AIRFLOW OPERATORS
  - [x] 3.1 - Entendendo os OPERATORS no Apache AIRFLOW
  - [x] 3.2 - Principais OPERATORS do Apache AIRFLOW
- [x] 4 - ALTERNATIVAS AO APACHE AIRFLOW
  - [x] 4.1 - Conhecendo o Azkaban e o Apache OOZIE
- [ ] 5 - HANDS ON: INSTALANDO, CONFIGURANDO E INICIALIZANDO O APACHE AIRFLOW
  - [x] 5.1 - Instalação do Apache AIRFLOW
  - [x] 5.2 - Configurando o seu Ambiente para as Práticas (HANDS ON)
  - [x] 5.3 - Instalando o Apache AIRFLOW utilizando o PIP (Python)
    - `$ sudo bash`
    - `# whoami`
    - `# AIRFLOW_HOME=~/airflow`
    - `# echo $AIRFLOW_HOME`
    - `# apt install python3-pip`
    - `# pip3 install apache-airflow`
  - [x] 5.4 - Inicializando o MetaStore no Apache AIRFLOW
    - `# airflow db init`
  - [x] 5.5 - Conhecendo as Configurações do Apache AIRFLOW (airflow.cfg)
    - `# cd ~/airflow/`
    - `# pwd` -> /root/airflow
    - `# ls -lrth`
      - `-rw-r--r-- 1 root root  44K abr  9 00:00 airflow.cfg`
      - `-rw-r--r-- 1 root root 4,6K abr  9 00:00 webserver_config.py`
      - `drwxr-xr-x 3 root root 4,0K abr  9 00:00 logs`
      - `-rw-r--r-- 1 root root 604K abr  9 00:00 airflow.db`
    - `vim airflow.cfg`
  - [x] 5.6 - Criando um Usuário no Apache AIRFLOW
    - `airflow users create \
    - > --username admin \
    - > --firstname Silvester \
    - > --lastname Stalone \
    - > --role Admin \
    - > --email silvester@email.com`
  - [ ] 5.7 - Inicializando a Interface Web e o SCHEDULER do Apache AIRFLOW
  - [ ] 5.8 - Acessando e Conhecendo a Interface Web do Apache AIRFLOW
  - [ ] 5.9 - Executando uma INSTÂNCIA DE TAREFA e BACKFILLS no Apache AIRFLOW
  - [ ] 5.10 - Adicionando a Variável de Ambiente AIRFLOW_HOME no BASH PROFILE
- [ ] 6 - PREPARANDO O APACHE AIRFLOW PARA O AMBIENTE DE PRODUÇÃO
  - [ ] 6.1 - Migrando o BACKEND (Metastore DB) do SQLITE para o POSTGRESQL
  - [ ] 6.2 - Preparando o Ambiente para a Migração do Metastore DB (Backend)
  - [ ] 6.3 - Configurações para o Airflow em Produção (airflow.cfg)
  - [ ] 6.4 - Instalando o PostgreSQL
  - [ ] 6.5 - Configurando o PostgreSQL (pg_hba.conf e postgresql.conf)
  - [ ] 6.6 - Criando os Metadados no POSTGRESQL para Migrar o Metastore DB
  - [ ] 6.7 - Configurando e Inicializando o NOVO Metastore DB com o PostgreSQL
  - [ ] 6.8 - Conhecendo o Código PYTHON de um DAG (Workflow)
- [ ] 7 - IMPLEMENTANDO SEU PRIMEIRO DAG COM PYTHON NO APACHE AIRFLOW
  - [ ] 7.1 - Introdução aos DAGs no AIRFLOW
  - [ ] 7.2 - Explorando um Novo DAG no Apache AIRFLOW
  - [ ] 7.3 - Detalhes de Implementação: Parâmetros do DAG
  - [ ] 7.4 - Detalhes de Implementação: Operators e Tasks
  - [ ] 7.5 - Executando o DAG no Apache AIRFLOW

# Referências

- https://www.udemy.com/course/apache-airflow-bootcamp/
- https://www.virtualbox.org/wiki/Downloads
- https://drive.google.com/drive/folders/1QLEscCLopi8RdcL5JOEqE-5z3Rbyl9bH
