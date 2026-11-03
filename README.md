This repository contains the docker-compose file `universitychallenge.yml`. It runs the images
- mwdf/universitychallengeweb
- mwdf/universitychallengedb.

The former contains an installation of the web application UniversityChallenge. The latter contains a
database with data the web application runs against.

The web application runs on the 8082 port internally. This gets forwarded to the 8081 port on the local machine.
The database runs on the 5432 port internally and gets forwarded to the 5433 port on the local machine.

Example run command:

`docker-compose -f .\universitychallenge.yml up`

Check the application on

`http://localhost:8081`
