# nodejs-app
Simple  node-js application running in a docker image
# Build docker image
docker build --tag marvino1/nodejs-app .

# Run Docker image
docker container run --rm --name nodejs-app -p 3000:3000 marvino1/nodejs-app
