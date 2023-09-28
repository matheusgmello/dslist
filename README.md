# DSList
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/matheusgmello/dslist-backend/blob/main/LICENSE) 

## Readme em [PT-BR](https://github.com/matheusgmello/dslist-api/blob/main/README-PT-BR.md) 📜
# About the project

DSList is a Rest API built during the Intensivão Java Spring, an event organized by [DevSuperior](https://devsuperior.com "Site da DevSuperior").

The API is a game search engine that allows users to find information about different games. Users can perform searches based on the genre and rating of the games. The API also features an endpoint that allows the user to organize the list in their preferred way.

## Domain Model

![App Screenshot](https://raw.githubusercontent.com/devsuperior/java-spring-dslist/main/resources/dslist-model.png)

## End Points
- `GET Games`: Search for the list of games
- `GET Games by ID`: Search for a game by its ID
- `GET Lists`: Search for the category of the game lists
- `GET Lists by ID from Games`: Search the list categorized by the genre (ID) of the games
- `POST Lists Replacement`: Allows the user to organize the list in their preferred way

## The API's response
![App Screenshot](https://github.com/matheusgmello/dslist-backend/blob/ea73c3a2f73d0ed3a3dc308fa81e5f8bfeee4179/assets/retorno%20api%20end%20point.png)

# Technologies

## Back end
- Java
- Spring Boot
- PostgreSQL
  
# How to Run
### Prerequisites: Java 17

```bash
# Clone repository
git clone https://github.com/matheusgmello/dslist-api

# Enter the backend folder
cd dslist-backend

# Run the project
./mvnw spring-boot:run
```

# Author
[Matheus Gabriel Fleck de Mello](https://www.linkedin.com/in/matheus-gabriel-fleck-de-mello/)
