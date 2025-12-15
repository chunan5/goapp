
## About This Project
 A simple Blog management Api written in Go. Uses Go + Gin for application, Postgres for Database, Air for live reloads.
 
## How To Run/Install
1. Download the ZIP file or clone the repository.
2. Set up your database and JWT secrets in .env file.
3. Navigate to your project root and run "docker compose up".
4. Create a database according to yout env.
5. Migarte database by going into the docker container by using the command "docker compose exec app bash" and then run th command "go run migrate/migrate.go" to migrate database.
6. Confirm Api is located on localhost:6969 port.
