

### How to build image
docker run -p 8080:8080 -v ${PWD}/pb_data:/pb/pb_data pocketbase-image

### How to run
- Start container: `docker-compose up`
- Start container (background mode):`docker-compose up -d`
- Stop container: `docker-compose down`