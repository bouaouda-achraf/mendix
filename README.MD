# Docker Mendix
docker run -p 8080:8080 -e DATABASE_ENDPOINT=postgres://DB_USER:DB_PASSWORD@DB_HOST:5432/mendix --network mendix bouaoudaachraf/mendix:mendix-app