# Wordpress ready for the CMS Cloud Manger project

I just used my known [wordpress-managed-app](https://git.cloudron.io/packages/wordpress-managed-app) and abridged the [docker-compose.yaml](./docker-compose.yaml) to set and use the variables that are necessary.

## TODO List

- Fix a race condition between `db` service starting up and `web` service at the same time resulting in `web` failing since `db` is not ready yet
