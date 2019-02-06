# docker_demo
Eine einfache Docker Demo

Ohne docker-compose:
- docker build -t bommi2000 .
- docker run -dit --name bommi2000web -p 8080:80 bommi2000
- erreichbar unter  http://localhost:8080

Mit docker-compose:

- docker-compose up
- docker-compose up -d