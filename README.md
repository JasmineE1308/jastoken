Create and test your API in Postman:

POST /api/users/register: Register a new user with username, email, password

POST /api/users/login: Login with email and password and token is avaliable

GET /api/users/me: Get user information (requires a valid JWT in the Authorization header).

# JWT Authentication Example
## API Endpoints

- `POST /api/users/register`: Register a new user.
- `POST /api/users/login`: Login and get a JWT token.
- `GET /api/users/me`: Get user information (protected, requires token).
