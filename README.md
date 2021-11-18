# moc-simple-runner
The absolute least amount you need to run this project

## Requirements
  * Git
  * Docker and Docker compose

## To install

* Clone this project into a directory

## To Launch core/admin/storefront
  * `docker compose up -d`

## To view logs from core
* `docker compose logs -f api`

The three sites serve locally on these ports:

 - Core GraphQL Server: 3000
 - Admin: 4080
 - Storefront: 4000

Your data should be saved between restarts in a local docker volume

Enjoy!
