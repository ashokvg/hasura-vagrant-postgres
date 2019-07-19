# hasura-vagrant-demo
A repo which provides Vagrant support to stand up an instance of Postgres, Hasura, and PGAdmin

1. Clone the repo
2. Edit the .env file to provide your desired credentials
3. Assuming you have Vagrant already installed, 'vagrant up' to start
4. The Hasura console is available at http://localhost:9842/console
5. PGAdmin is available at http://localhost:9852
6. Postgres is available on port 9832

If you want to connect to the database from PGAdmin, create a new server connection.  On the General tab, provide a name.  On the Connection tab, for the hostname use 'postgres'.  Use the username and password and database used in the .env file.

Helpful links:
https://hasura.io/
https://github.com/hasura/graphql-engine
https://github.com/hasura/graphql-engine/tree/master/install-manifests/docker-compose-pgadmin





