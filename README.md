# Start Postgresql

docker run --name postgres -v /path/to/data/dir:/var/lib/postgresql/data -d optionfactory/postgresql:9.6

# Connect to Postgresql instance with psql

docker exec -ti postgres psql -U postgres