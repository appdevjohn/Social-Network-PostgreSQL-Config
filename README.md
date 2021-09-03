# Social Network PostgreSQL Config
The `setup.sql` file contains all of the instructions to set up the PostgreSQL database. If you want to `docker run` this in a container, all you need to set these three environment variables. Make sure to expose port `5432` or place it on a docker network.
```
POSTGRES_USER=user
POSTGRES_PASSWORD=password1
POSTGRES_DB=social_network
```