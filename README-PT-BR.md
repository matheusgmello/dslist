# DSList
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/matheusgmello/dslist-backend/blob/main/LICENSE) 

# Sobre o projeto

DSList é uma API Rest construída durante o Intensivão Java Spring, evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A API é uma pesquisa de jogos que permite aos usuários encontrar informações sobre diferentes jogos.
Os usuários podem realizar buscas com base no gênero e na classificação dos jogos.
A API também possui um endpoint que permite ao usuário organizar a lista da maneira que preferir.

## Modelo de Domínio 

![App Screenshot](https://raw.githubusercontent.com/devsuperior/java-spring-dslist/main/resources/dslist-model.png)

## End Points
- `GET Games`: Busca a lista de jogos
- `GET Games by ID`: Busca um jogo por meio do ID
- `GET Lists`: Busca a categoria das listas de jogos
- `GET Lists by ID from Games`: Busca a lista categorizado pelo gênero (ID) do jogos
- `POST Lists Replacement`: Permite o usuário organizar a lista da maneira que preferir

## Retorno da API
![App Screenshot](https://github.com/matheusgmello/dslist-backend/blob/ea73c3a2f73d0ed3a3dc308fa81e5f8bfeee4179/assets/retorno%20api%20end%20point.png)

# Tecnologias utilizadas

## Back end
- Java
- Spring Boot
- PostgreSQL
  
# Como executar o projeto
### Pré-requisitos: Java 17

```bash
# Clonar repositório
git clone https://github.com/matheusgmello/dslist-api

# Entrar na pasta do projeto back end
cd dslist-backend

# Executar o projeto
./mvnw spring-boot:run
```

# Autor
[Matheus Gabriel Fleck de Mello](https://www.linkedin.com/in/matheus-gabriel-fleck-de-mello/)
