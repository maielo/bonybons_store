# bonybons_store

## Medusa CLI for creating DB & user:

```
npx medusa user --email maielo.mv@gmail.com -p <pass>
```

```
npx medusa db:setup --db medusa-bonybons
```


## Dev local docker DB

```
docker-compose up -d
```

- will run dev for admin
```
pnpm dev
```

## Production:


- railway - cli to create admin
- vercel + railway

Followed these steps: https://docs.medusajs.com/resources/deployment/medusa-application/railway