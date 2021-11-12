## Phone CRUD Rest API with Nest

### Requirements
- Docker
- docker-compose

### Technologies
- NestJS
- JWT
- Postgres
- Nginx
- Docker
- Swagger

### Designs
- Service pattern
- Repository pattern
- TDD
- Dependency injection
- Git flow
- Semantic versioning
- Conventional commits

### Mounting dev environment
1. On first time, to download images and build containers:
```shell
docker-compose up --build
```
**for detached build or initialization use `-d` flag**
```shell
docker-compose up --build -d
```
```shell
docker-compose up -d
```
2. To stop containers use:
```shell
docker-compose down
```
3. To stop containers and remove volumes use:
```shell
docker-compose down -v
```
