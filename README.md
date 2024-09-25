# Meltano Demo with CSV files and PostgreSql database

Using csv files and feed them to a PostgreSql Database.

## Installation and configuration

Add the extractor : 

    meltano add extractor tap-csv
Add the loader :

    meltano add loader target-postgres

### Prerequisites

Requirements for the software and other tools to build, test and push 
- [Python](https://www.python.org/downloads/)
- [Meltano](https://meltano.com/)
- [Postgresql](https://www.postgresql.org/download/)

### Test export to json

I tested also loading data from csv file to json file so we need the json loader configurated :

    meltano add loader target-jsonl
