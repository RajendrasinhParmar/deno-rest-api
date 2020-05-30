# deno-rest-api
This is the demo repository for basic REST API example using Deno

## Installation

We just need to install deno. Follow the link for installation.

[Install Deno](https://deno.land/#installation)

Once the installation is done execute following command to start Deno Rest API server

```shell
deno run --allow-net server.ts
```

Make sure to pass --allow-net argument as we are using network for the rest API requests.

The command will start server on port 8000.

Hit one of the API end points to get API response

1. GET - http://localhost:8000/api/v1/products (Get all Products)
2. GET - http://localhost:8000/api/v1/products/:id (Get Product by id)
3. POST - http://localhost:8000/api/v1/products (Add new Product)
4. PUT - http://localhost:8000/api/v1/products/:id (Update Product by id)
5. DELETE - http://localhost:8000/api/v1/products/:id (Delete Product by id)
