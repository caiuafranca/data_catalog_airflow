# data_catalog_airflow

Teste Técnico

Infra:

- Banco mysql - Backoffice
    - docker compose build
    - docker compose up

- Banco postgresql - Airflow
- Airflow
    - Seguir a documentação
    - docker compose up airflow-init
    - docker compose up
- Amundsen
    -  docker-compose up dentro da pasta do amundsen

dentro das pastas tem o dockerfile e docker-compose das aplicações

o que fazer

1 - subir o ambiente em docker

2 - Construir Dags em Python 
2.1 - Dag para extrair os metadados do mysql e salvar no amundsen
2.2 - Dag para extrair os metadados do postgres e salvar no amundsen

3 (opcional) - Subir um banco NoSQL nessa Infra e efetuar a extração dos metadados
OBS. a tecnologia(mongo, redis...) e os collection e documentos(banco,tabelas) ficam a seu criterio

Entregavél

- ver os metadados na plataforma do amundsen
- par-programing com explanação do seu código

referencias:

https://airflow.apache.org/docs/apache-airflow/stable/howto/docker-compose/index.html
https://github.com/amundsen-io/amundsen

