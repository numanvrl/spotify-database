# spotify-database
A 3NF Spotify database using dataset from Spotify API which weekly-top-200-songs.

## instructions:
* clone the repository
* create the database as instructed in create_database.sql
* install requirements with python3 -m pip install -r requirements.txt
* go to scripts directory and execute python3 insert_all.py with desired parameters


## parameters for scripts 
python3 insert_all.py --host localhost --database spotify --user root --password /empty/ --path ../datasets/spotify-top-200-dataset.csv

* --host for the host of the mysql server (optional, localhost by default)
* --port for the port of the mysql server (optional, 3306 by default)
* --database for the database name from mysql server (optional, spotify by default)
* --user for the user of the mysql server (optional, admin by default)
* --password for the password of the user (optional, empty by default)
* --path for the file path of the csv dataset (optional, ../datasets/spotify-top-200-dataset.csv by default)
