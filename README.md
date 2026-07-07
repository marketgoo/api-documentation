# marketgoo API Documentation

This repository contains the API documentation for the **marketgoo** API — the **Provisioning** and **Data API** used to integrate with the marketgoo platform.

The **marketgoo** API is based on REST principles and follows the recommendations from the [json:api specification](http://jsonapi.org).

## Repository structure

- `reference/` — OpenAPI specification (`openapi.yaml`) and endpoint reference documentation.
- `docs/` — Guides and getting-started documentation.

## Documentation source

This content is authored for and synced with [ReadMe](https://readme.com). To validate the OpenAPI specification locally:

```bash
npx rdme openapi validate reference/openapi.yaml
```

