# CSE412-GroupProject-DB

This repo contains a database dump of the Group 20's CSE 412 Group Project.

The database dump was created on the production server (Raspberry Pi) using the command the following command:

`pg_dump --dbname="dbname=cse412groupproject user=pi password=[REDACTED] host=localhost port=5433" > ~/database_dump`

To restore the database using the database dump file, run the command:

`psql ~/cse412groupproject < database_dump`

To create a minimal version of the database, see the `setup.sh` script located in the API project.
