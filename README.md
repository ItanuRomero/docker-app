# docker-app
 Deploy of a next app with docker


# run it with:

docker-compose up --build --force-recreate

# If it does'nt work, try:

dockerd
docker-compose up --build --force-recreate

# When production:

docker-compose -f docker-compose.production.yml up --build --force-recreate