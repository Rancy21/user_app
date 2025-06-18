# Simple REST API

## Description
A basic user management API with endpoints to create users and fetch user details by ID.

## Programming Language and Framework used
- **Language:** Java 17
- **Framework:** SpringBoot


## How to Run
1. Clone or download the projectt
2. Navigate to the project directory
3. Run the application:
   ```bash
   mvn spring-boot:run
   ```
4. The API will be available at `http://localhost:8080`

## Example Usage

### Create a User
```bash
curl -X POST http://localhost:8080/users -H "Content-Type: application/json" -d '{"name":"larryck","email":"larr@gmail.com"}'
```
### Get a User
```bash
curl -X GET http://localhost:8080/users/733df520-3814-493d-a128-7f051b09b7d8
```
