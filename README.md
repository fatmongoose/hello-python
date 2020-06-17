# hello-python
Very simple hello world python Flask application.


docker
1. docker build -f docker/Dockerfile -t hello-python:latest .
1. docker image ls
1. docker run -p 5001:5000 hello-python


kubernetes
1. cd kubernetes
1. kubectl apply -f deployment.yaml
