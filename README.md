# Orders Microservice

## Dev

1. Clone repository
2. Install dependencies
3. Create a `.env` file based on `env.template`
4. Make sure the Postgres server is running

```
docker compose up -d
```

5. Execute prisma migration with command `npx prisma migrate dev`
6. Make sure the NATS server is running

```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```

7. Run `npm run start:dev`
