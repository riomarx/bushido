
Quick node.js app demonstrating how to dockerize a simple app.

Exposes web server on port 8080.

See Dockerfile for more details.

How to run:
$ git clone https://github.com/mariosevic/SimpleNodeApp.git
$cd SimpleNodeApp
$ docker image build -t test:latest .
$ docker container run -d \
--name App1 \
-p 8080:8080 \
app:latest
