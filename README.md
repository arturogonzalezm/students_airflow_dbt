# Students Apache Airflow and DBT
Build pipeline that ingests students csv files using Apache Airflow and build a data model using dbt

## Installations

- You are going to use Snowflake free trial (https://signup.snowflake.com/?utm_source=google&utm_medium=paidsearch&utm_campaign=ap-au-en-brand-trial-exact&utm_content=go-eta-evg-ss-free-trial&utm_term=c-g-snowflake%20trial-e&_bt=562090225080&_bk=snowflake%20trial&_bm=e&_bn=g&_bg=125204643262&gclsrc=aw.ds&gad=1&gclid=Cj0KCQjwnMWkBhDLARIsAHBOftpYZMakmW-CpisFoUJEyD1Pq6fketS9HLWbk_gjoLYXsu-CqX5dvyMaAtU4EALw_wcB)
- Download and Install Docker (https://docs.docker.com/desktop/install/windows-install/)
- Install DBT CLI so you can use the command line
- Install Python 3.7, 3.8, 3.9 or 3.10

## Instructions

- Pull from master branch
- Create a branch called feature/snowflake-yourname
- Load the CSV files using DBT seeds (https://www.youtube.com/watch?v=CWetaAaEdKw)
- Automate the DBT seeds by creating and triggering Apache Airflow DAGs in order to load the CSV data into Snowflake. 
- Make sure you name each DAG the way each CSV is named.
- Make sure Apache Airflow is running on Docker Production Image.
- Make sure each Snowflake table is named the same as every CSV file adding as a prefix stg_. Ie. stg_class_list
- Once the CSV data is loaded into Snowflake join the stg tables using star schema approach with DBT (https://docs.getdbt.com/quickstarts).
- Once the data is joined and the new joined tables are in Snowflake create a dashboard using Streamlit (https://streamlit.io/) and another dashboard using https://powerbi.microsoft.com/en-au/landing/free-account/?ef_id=_k_Cj0KCQjwnMWkBhDLARIsAHBOftrKfrChnRO5iSIwux9SBFWE3lf8Jua6SCye-m1Okj8qB34M8TnFSNYaAkqEEALw_wcB_k_&OCID=AIDcmmet0q7mo5_SEM__k_Cj0KCQjwnMWkBhDLARIsAHBOftrKfrChnRO5iSIwux9SBFWE3lf8Jua6SCye-m1Okj8qB34M8TnFSNYaAkqEEALw_wcB_k_&gclid=Cj0KCQjwnMWkBhDLARIsAHBOftrKfrChnRO5iSIwux9SBFWE3lf8Jua6SCye-m1Okj8qB34M8TnFSNYaAkqEEALw_wcB
- Create a Pull Request on Github for me to review your project.

Reference links:
- DBT: https://docs.getdbt.com/quickstarts and https://www.youtube.com/watch?v=5rNquRnNb4E
- Apache Airflow and DBT: https://www.youtube.com/watch?v=MhCuxTDlVkE
- Apache Airflow: https://airflow.apache.org/docs/apache-airflow/stable/installation/index.html
- DBT and Snowflake: https://www.youtube.com/watch?v=5rNquRnNb4E


