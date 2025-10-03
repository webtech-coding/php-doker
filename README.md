# Start everything
docker-compose up -d

# Check if containers running
docker-compose ps

# See logs if something wrong
docker-compose logs

# To go inside PHP container (useful for Composer etc)
docker-compose exec php bash