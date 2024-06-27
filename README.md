# etl_dev_env
Repository to setup a local dockerized developement environmnet - ETL Tools

# Step-by-Step Guide
1. Setup docker-compose.yml
	This file will define all the services: PostgreSQL, Apache Airflow, Apache Spark, and Jupyter Notebook.

	Docker Compose Services:

		PostgreSQL: Database service.
		Apache Spark: Standalone Spark cluster with a configurable number of workers.
		Apache Airflow: For orchestrating Spark jobs.
		Jupyter Notebook: For interacting with Spark and PostgreSQL.

