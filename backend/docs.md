# OpenAPI Doc Tools:


## Redoc 

- installed with cli (npm i -g @redocly/cli@latest)

- run with "redocly preview-docs swagger.yaml", starts up default redoc server

- run on local server

*No functionality for testing, basic rendering*


## Swagger

- installed with cli

- run with "node server.js"

- requires this code 
    const swaggerDocument = YAML.load("./swagger.yaml");
    app.use("/api-docs", swaggerUi.serve, swaggerUi.setup(swaggerDocument));

- run on local server

*Can test, poor rendering*

## Scalar

- https://docs.scalar.com/swagger-editor#/reference

*Can test, a bit too complex, nice rendering though*






## Examples:

- PHP lets you test code in docs https://www.php.net/manual/en/function.strlen.php