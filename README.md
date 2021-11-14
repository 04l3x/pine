# pine project

## a self hosted and open source alternative for existing git hosting services written in rust

- ###### this is a work in progress, and isn't ready to use it



<!--
[//]: <> # temporal space for requisites
[//]: <> 
[//]: <> the user deploy the server with a default user
[//]: <> 
[//]: <> the record represents list of all repositories allocated in the program instace
[//]: <> the filesystem persistence and database are independent phisycal components (are distributed)
[//]: <> 
[//]: <> the backend is connect to database and filesystem tought enviroment variables that define and identify the resources of app
[//]: <> 
[//]: <> the server mount the remote filesystem at start
[//]: <> 
[//]: <> 
[//]: <> the auth module generate sessions of 1 hour for new users and 12 hours sessions for login users
[//]: <> 
[//]: <> 
[//]: <> 
[//]: <> # How to deploy
[//]: <> 
[//]: <> ```sh
[//]: <> cd /path/of/project
[//]: <> cargo build --target release 
[//]: <> ```
[//]: <> 
[//]: <> ## Run Options
[//]: <> 
[//]: <> - ** Migrations
[//]: <> 	--None
[//]: <> 		not runs database migrations
[//]: <> 	--Drop
[//]: <> 		drop cascade current database schema and then run default script
[//]: <> 	--Default
[//]: <> 		run migrations, default script
[//]: <> 	--Custom
[//]: <> 		run custom script with path
[//]: <> 
[//]: <> - ** Example-data
[//]: <> 	--example-data
[//]: <> 		true or false default false
[//]: <> 
[//]: <> - ** Enviroment Vars File
[//]: <> 	--ENVIRONMENT=
[//]: <> 	--HOST=
[//]: <> 	--PORT=
[//]: <> 	--PSQL_HOST=
[//]: <> 	--PSQL_PORT=
[//]: <> 	--PSQL_USER=
[//]: <> 	--PSQL_PASSWORD=
[//]: <> 	--PSQL_DEFAULT_SCHEMA=
[//]: <> 	--PSQL_DEFAULT_DATABASE=
[//]: <> 	--GIT_ROOT_DIR=
[//]: <> 	--CLIENT_PATH=
[//]: <> 	--SECRET_KEY=
[//]: <> 	--LOGS_DIR=
[//]: <> 
[//]: <> 
[//]: <> * full start command example
[//]: <> ```sh
[//]: <> cd /path/of/binary/output
[//]: <> ./server  --migrations drop  --example-data true --environment test --vars ~/some/path/.somefile.env &
[//]: <> ```
[//]: <> 
[//]: <> ```sh
[//]: <> cd /path/of/binary/output
[//]: <> ./server &
[//]: <> ```
-->

data example
default user user
default password password
default email user@user.com


