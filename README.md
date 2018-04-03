# ICTDBS603 Major Unit Assignment Helper Files

To set up a Docker container:

    docker run \
      -p 0.0.0.0:30000:3306 \
      --name ictdbs603-db \
      -e MYSQL_ROOT_PASSWORD=password \
      -e MYSQL_USER=ictdbs603-dev \
      -e MYSQL_PASSWORD=password \
      -e MYSQL_DATABASE=ictdbs603 \
      -d mysql:5.7.20
      
The migration file in this directory `ictdbs603-migration.sql` represents the database state.