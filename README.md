# Veebipood

OO2026 e-poe backend rakendus.

## Tech Stack

- **Java 21**
- **Spring Boot 4.0**
- **Spring Data JPA** - andmebaasi haldus
- **PostgreSQL** - andmebaas
- **H2** - arenduse andmebaas
- **Lombok** - boilerplate vähendamine
- **Springdoc OpenAPI** - API dokumentatsioon

## API

Rakendus sisaldab järgmisi mooduleid:

| Moodul | Kirjeldus |
|--------|-----------|
| Products | Toodete haldus |
| Categories | Kategooriate haldus |
| Orders | Tellimuste haldus |
| Persons | Kasutajate haldus |

## Käivitamine

```bash
./mvnw spring-boot:run
```

API dokumentatsioon on saadaval aadressil: `http://localhost:8080/swagger-ui.html`
