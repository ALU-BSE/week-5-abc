## Team Members
- Beverly Mugwadi - beverlymugwadi
- Quentin Rurangirwa - MaxKrypton
- Ketia Mukakalisa - mketia
- Junior Rwaka - jrwaka

## What We Built
JWT authentication system
User registration endpoint
User login endpoint
Protected user profile endpoint
API documentation
Postman test suite

## API Endpoints

### Public Endpoints
- `POST /api/users/register/` - User registration
- `POST /api/users/login/` - User login
- `POST /api/users/token/refresh/` - Refresh access token

### Protected Endpoints (Requires Authentication)
- `GET /api/users/profile/` - Get user profile
- `PUT /api/users/profile/` - Update user profile

### Documentation
- Swagger UI: http://127.0.0.1:8000/api/docs/

## Testing
Import Postman collection from `/postman/SafeBoda_API.postman_collection.json`

## Key Learnings
1. We learned how to implement JWT authentication in Django REST Framework, using access and refresh tokens to secure endpoints.
2. We gained experience in applying permissions and protecting user-specific data through authenticated requests.
3. We practiced collaborative development and testing as a team using GitHub and Postman.