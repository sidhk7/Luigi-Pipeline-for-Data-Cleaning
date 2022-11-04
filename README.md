# Luigi-Pipeline-for-Data-Cleaning
Data Cleaning using Luigi ETL Pipeline. Based on Luigi tasks and creating a DAG flow, we can define the order of tasks. Along with this, if while running the whole pipeline, one task fails, the task which came before it and ran successfully wont have to run again. We can just fix our issue of that task and Luigi will resume from there.
The file here contains code which uses a Luigi ETL flow to clean the data of a csv file, and then load it into a MYSQL database.
