Sample project demonstrating how to integrate Sidekiq and Redis into an existing Rails project, as described in [How To Add Sidekiq and Redis to a Ruby on Rails Application](https://www.digitalocean.com/community/tutorials/how-to-add-sidekiq-and-redis-to-a-ruby-on-rails-application)

# Development

## create containers
`docker-compose up -d`

## start containers (if not already started via `up`)
`docker-compose start`

## view logs
`docker-compose logs -f`

view logs filtered by service
`docker-compose logs -f | grep {{service_name}}`

## stop container
`docker compose stop`

## remove containers (keeps data volumes)
`docker-compose down`
