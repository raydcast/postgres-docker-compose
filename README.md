# PostgreSQL Docker Compose
The simple postgres service, with docker compose. With username and password default `postgres`, and service running on default port: `5432`
## Usage
### Install
```bash
git clone https://github.com/raydcast/postgres-docker-compose.git
cd postgres-docker-compose
```
### Start PostgreSQL container
```bash
docker-compose up
# or, if necessary superuser privileges
sudo docker-compose up
```
### Show status
```bash
docker-compose ps
# or, if necessary superuser privileges
sudo docker-compose ps
```
### Stop PostgreSQL container
```bash
docker-compose down
# or, if necessary superuser privileges
sudo docker-compose down
```
