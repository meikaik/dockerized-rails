# Instructions
- Ensure you have Docker 17.x installed
- `docker-compose up`, once all the dependencies are installed, an error may appear saying that you have no initialized your pg database
- `docker-compose run --user "$(id -u):$(id -g)" mobydock rake db:reset` to init the pg database
