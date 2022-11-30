# docker-app
 Deploy of a next app with docker


# run it with:

docker-compose up --build --force-recreate

# If it does'nt work, try:

dockerd
docker-compose up --build --force-recreate

# When production:

docker-compose -f docker-compose.production.yml up --build --force-recreate

# Step Guide:
Clone the repo with:
- git clone https://github.com/ItanuRomero/docker-app.git
Then enter the folder:
- cd docker-app/next-app/
Then run the docker-compose build:
- docker-compose -f docker-compose.production.yml up --build --force-recreate