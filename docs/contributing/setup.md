# Setup Guide

{{ remrg:task Write a guide to setup your project & dependencies }}

## Docker

### Database Configuration

If you don't have a `.env` file already, run `cp .env.example .env`.

Set the following in your `.env`:

- `POSTGRES_DB`: initial database name.
- `POSTGRES_USER`: initial administrative user.
- `POSTGRES_PASSWORD`: a unique, non-empty password. No default is provided.

### Startup

Run docker compose to start:

```
docker compose up --build -d
```
