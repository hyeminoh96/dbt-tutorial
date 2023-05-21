# dbt-airflow-orchestration-demo

DBT and Airflow Orchestration Demo

## Overview

This repository is intended for my personal study of DBT (Data Build Tool) and testing the orchestration between DBT and Airflow. 


## Contents

The repository contains the following files and directories:

- `dbt_project.yml`: The configuration file for DBT projects.
- `models/`: Directory for housing DBT models and associated SQL scripts.
- `dags/`: Directory for storing Airflow DAGs (Directed Acyclic Graphs).
- `plugins/`: Directory for any custom Airflow plugins required.
- `tests/`: Directory for tests related to DBT and Airflow integration.
- `README.md`: The current file you are reading.

## Prerequisites

Before using this repository, ensure that you have the following prerequisites installed and configured:

1. **DBT**: Install DBT by following the official DBT installation guide (link to the guide).
2. **Airflow**: Install and set up Airflow by referring to the Airflow documentation (link to the documentation).

## Usage

To use this repository, follow the steps below:

1. Clone the repository to your local machine using the command: `git clone https://github.com/your-username/dbt-airflow-demo.git`.
2. Configure your DBT project by modifying the `dbt_project.yml` file to match your specific project requirements.
3. Create your DBT models in the `models/` directory, along with any necessary SQL scripts.
4. Define your Airflow DAGs in the `dags/` directory, specifying the dependencies and execution order.
5. (Optional) Add any required custom plugins in the `plugins/` directory.
6. Run tests in the `tests/` directory to validate the integration between DBT and Airflow.
7. Execute the Airflow DAGs to trigger the DBT jobs and automate your data pipelines.

## Contributing

Contributions to this repository are welcome! If you find any issues or have suggestions for improvements, please submit a pull request or open an issue.

## License

This repository is licensed under the [MIT License](https://opensource.org/licenses/MIT). See the [LICENSE](LICENSE) file for more details.
