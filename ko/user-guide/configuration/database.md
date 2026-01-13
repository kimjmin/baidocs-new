# Database Configuration

Configure database connections and settings.

## Supported Databases

- PostgreSQL 12+
- MySQL 8.0+
- SQLite 3

## Connection String

```yaml
database:
  type: postgres
  host: localhost
  port: 5432
  name: myapp
  user: admin
  password: secret
```

## Connection Pool

Configure connection pooling for better performance.
