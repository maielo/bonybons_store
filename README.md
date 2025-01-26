# bonybons_store

## Dev local docker DB

```
docker run --name postgres -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=postgres -e POSTGRES_DB=postgres -p 127.0.0.1:5432:5432 -d postgres
```

## Production:

- vercel + railway

Followed these steps: https://docs.medusajs.com/resources/deployment/medusa-application/railway