# Setting-Up-Trino-Iceberg-Rest-Minio

> The primary objective of this project is to create a Docker Compose environment that integrates multiple services including Minio, Iceberg-Rest catalog, and Trino. This setup will enable a seamless data management and analysis workflow. Additionally, we will demonstrate the usage of this setup through a Python notebook and Trino CLI commands, while performing tasks such as schema creation, data table creation, and data validation.

## The specific requirements of the project are as follows

- Set Up Minio Docker: Establish a Minio service using Docker, which will function as our S3 compatible storage system. This service will host a bucket named "rawdata".

- Set Up Iceberg-Rest Catalog: Deploy an Iceberg-Rest catalog service within the environment. The catalog implementation should be configured to use the Minio S3 storage created in the previous step.

- Set Up Trino Docker: Configure a Trino service using Docker. This service should be set up to communicate with the Iceberg-Rest catalog, allowing queries to be executed on the data stored in the Minio bucket.

- Create Python Notebook: Develop a Python Notebook that includes steps for creating a schema and a small sample table on the S3 Storage using the Trino CLI. This notebook will serve as a guide for users to interact with the data within the integrated environment.

- Validate the Creation of Schema and Tables: Verify the successful creation of the schema and tables within the Minio bucket. This validation will ensure the integrity of our data and the correct functioning of our services.

## Deliverables

- Docker Compose files for setting up Minio, Iceberg-Rest Catalog, and Trino services.

- Python Notebook with step-by-step instructions for creating a schema and sample table on S3 storage using the Trino CLI.

- Trino CLI commands used for creating the schema and tables.

- A detailed report validating the successful creation of the schema and tables on the Minio bucket.
