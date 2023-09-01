# beto
Projeto principal BETO

## Docker

Para rodar o projeto com docker, é necessário ter instalado o Docker em ambiente local.

### Docker Compose

Comando para construir as imagens e rodar os containers.

```
docker compose up --build
```

### Estrutura Docker Compose

O docker compose está configurado para rodar FRONT, BACK e BANCO DE DADOS (MongoDB) na raiz e cada projeto (front e back) deve possuir seu respectivdo docker file dentro de seu respectivo diretório.

./docker-compose
./laboracao-back
    |_ dockerfile
./laboracao-front
    |_ dockerfile

Essa estrutura deve ser respeitada para o docker compose rodar corretamente.

### Dockerfile

Cada parte do projeto possui seu respectivo docker file em seu diretório raiz.
