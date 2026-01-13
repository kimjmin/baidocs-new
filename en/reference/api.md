# API Reference

Complete API documentation.

## Authentication

All API requests require an API key:

```bash
curl -H "Authorization: Bearer YOUR_API_KEY" \
  https://api.example.com/v1/endpoint
```

## Endpoints

### Users

- `GET /api/users` - List users
- `POST /api/users` - Create user
- `GET /api/users/:id` - Get user
- `PUT /api/users/:id` - Update user
- `DELETE /api/users/:id` - Delete user

See individual endpoint documentation for details.
