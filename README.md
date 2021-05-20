# FIAP - Microservices (Hands-On) | LAB 1

---

## Build imagem do contêiner
> docker build -t imagem_clientes_microservice .

## Executa contêiner da aplicação
> docker run --name clientes-microservice -it -p 5050:5000 -d imagem_clientes_microservice

## Acessar no navegador
> http://ip:5050/

## Executa conteiner do DB
> docker run -d -p 27017:27017 --name mongodb mongo
