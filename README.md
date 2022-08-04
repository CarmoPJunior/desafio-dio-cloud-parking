# Desafio  DIO Cloud Parking


Este projeto faz parte do treinamento do curso da Digital Innovation, para o bootcamp Spring Framework Experience.

<h2>🎯 Objetivo do Projeto</h2>
<p>O objetivo deste projeto foi aplicar os conhecimentos aprendidos durante o bootcamp Spring Framework Experience.
Para isso foi criado uma api que simula a operação de um estacionamento utilizando o framework Spring.
</p>


<h2>Comandos do docker</h2>
### Criar a base de dados:
> docker run --name parking-db -p 5432:5432 -e POSTGRES_DB=parking -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=123 -d postgres:10-alpine

### Para a base de dados:
> docker stop parking-db

### Iniciar a base de dados:
> docker start parking-db
