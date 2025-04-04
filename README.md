# ds-openapi-spec

OpenAPI specification for DataSpace services:
1) [Catalog Service](https://hiro-microdatacenters-bv.github.io/ds-catalog/docs/index.html)
2) [Search Service](https://hiro-microdatacenters-bv.github.io/ds-openapi-spec/search-service.html)

## Installation

To install `redoc-cli`, use the following command:

```bash
npm install -g redoc-cli
```

## Generating Documentation

You can generate HTML documentation from the OpenAPI specification using `redoc-cli`:

```bash
redoc-cli bundle services/catalog-service/openapi.yaml -o docs/catalog-service.html
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
