# champ-devops-assignment

1. clone the repository
2. run `docker-compose up -d`
3. Send requests to the reverse proxy using `localhost` followed by the desired endpoint.

## Endpoints

### Product service

- `GET /product/:id`
- `POST /product`
- `GET /healthcheck`

### User service

- `GET /user/:id`
- `GET /user/:id/product`
- `POST /user/:id/product`
- `POST /user`
- `GET /healthcheck`
