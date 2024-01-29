# transcendence htmx

HTMX version of the trancendance project made to learn htmx.
It will use htmx django redis and postgre.

## structure

  nginx -> redis1 -> django -> redis2 -> postgre

  * nginx: load balancer and static file dispatcher
  * redis1: caches http request
  * django: app api
  * redis2: caches postgre request
  * postgre: main database

Idealy would launch multiple django instances ```cubernetes``` to simulate load balancing.

## TODO

All:
> - [ ] finish setting up docker-compose

Eneko:

> - [ ] Frontend app mapping
> - [ ] Frontend app working
> - [ ] Djando container
> - [ ] Postgres container
> - [ ] Readme 




