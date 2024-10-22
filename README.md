### How to build & run image

- Build `docker build -t pocketbase-image .`
- Run `docker run -p 8080:8080 -v ${PWD}/pb_data:/pb/pb_data pocketbase-image`

### How to run

- Start container: `docker-compose up`
- Start container (background mode):`docker-compose up -d`
- Stop container: `docker-compose down`

### Build from scratch before running

- Build: `docker-compose build --no-cache`
- Start: `docker-compose up`
- Stop: `docker-compose down`
