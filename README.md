# airflow-kubernetes
Repo del taller Airflow en Kubernetes para el taller "Airflow en Kubernetes" @ PyConAr 2020

## Setup

Para setupear el virtual environment para este taller les recomiendo ejecutar:

```bash
pip install "apache-airflow[async,celery,crypto,jdbc,kubernetes,password,postgres,redis,slack]==1.10.12" --constraint ./requirements.txt
```