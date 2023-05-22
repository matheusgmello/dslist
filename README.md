# DSList
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/matheusgmello/dslist-backend/blob/main/LICENSE) 

# Sobre o projeto

DSList é uma aplicação Back-end construída durante o Intensivão Java Spring, evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação é uma pesquisa de games que permite aos usuários encontrar informações sobre diferentes jogos.
Os usuários podem realizar buscas com base no gênero e na classificação dos jogos. A aplicação também possui um endpoint especial que permite a ordenação personalizada da lista de jogos.

## Modelo conceitual

![App Screenshot](https://github.com/matheusgmello/dslist-backend/blob/325eae32ad551b242e20b4623c32aff71a73b3c1/assets/retorno%20api%20end%20point.png)

## End Points
- `GET games`: Busca a lista de jogos
- `GET games by id`: Busca um jogo por meio de ID
- `GET games lists`: Busca a categoria das listas de jogos
- `GET games by lists`: Busca uma lista por meio de seu ID mostrando quais jogos estão dentro desta categoria
- `POST list replacement`: Organiza a lista como o usuário preferir

## Retorno da API
![App Screenshot](https://github.com/matheusgmello/readme-example/blob/8512d78af3dd3631db8cbb40d3d6f83330a3a5d8/assets/retorno%20api%20end%20point.png)

# Tecnologias utilizadas

## Back end
- Java
- Spring Boot
- H2 Console
- JPA / Hibernate
- Maven

## Implantação em produção
- Banco de dados: Postgresql

# Como executar o projeto

Pré-requisitos: Java 17


```bash
# clonar repositório
git clone https://github.com/matheusgmello/dslist-backend

# entrar na pasta do projeto back end
cd dslist-backend

# executar o projeto
./mvnw spring-boot:run
```


# Autor

Matheus Gabriel Fleck de Mello
