# Data Wayfinder's API Schema

## Schema Link

[https://data-wayfinder.github.io/Data-Wayfinder-Schema](https://data-wayfinder.github.io/Data-Wayfinder-Schema)

## Local Development

Run the local dev server to view the Swagger UI docs.

```sh
docker run -d -p 8080:8080 --name local-swagger-ui -v $(pwd):/app -e SWAGGER_JSON=/app/openapi.yaml swaggerapi/swagger-ui
```