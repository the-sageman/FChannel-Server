Setup:

Have golang installed a correct GOPATH

Move config-init to config and change the values to reflect the instance

Create the database, username, and password for psql that is used in config file

run

psql -U (user) -d (database) -f databaseschema.psql

then start the client with

go run .