# eCommerceSite
![CI](https://github.com/IonGondrea/eCommerceSite/actions/workflows/ci.yml/badge.svg)


**Spring Boot REST API for an e-commerce demo site.**

## Tech stack
- Java 21, Spring Boot 3
- Spring Data JPA (Hibernate) & PostgreSQL
- Spring Security 6 (JWT)
- Maven, Docker (soon)

## How to run locally
```bash
# clone repository
git clone https://github.com/IonGondrea/eCommerceSite.git
cd eCommerceSite

# start backend
./mvnw spring-boot:run
The API will be available at http://localhost:8080/api

## Roadmap
- [x] Project skeleton
- [ ] Categories CRUD
- [ ] Products & pagination
- [ ] JWT authentication
- [ ] Docker Compose for DB + app
- [ ] React front-end
