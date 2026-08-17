# VARIO Cloud OpenAPI Specification

This repository contains the public OpenAPI specification for the VARIO Cloud REST API.

Use the specification to explore available resources and schemas or to generate clients and development tooling compatible with OpenAPI.

## Documentation

- [Get started with the VARIO Cloud REST API](https://developer.vario-software.de/documentation/rest-api/introduction)
- [Learn about REST API authentication](https://developer.vario-software.de/documentation/rest-api/authentication)
- [Explore the complete REST API Reference](https://developer.vario-software.de/api-reference)
- [Browse all VARIO Cloud Developer Docs](https://developer.vario-software.de/)

## Base URL

The API is reached per tenant:

```
https://{subdomain}.vario.cloud/api/vario
```

Replace `{subdomain}` with your own tenant subdomain. Do not use the server address contained in this specification — build the base URL from your own subdomain instead.

Your ERP can also provide a tenant-specific version of this specification, whose `servers` entry already holds the correct address. See [Get started with the VARIO Cloud REST API](https://developer.vario-software.de/documentation/rest-api/introduction).

## TypeScript definitions

If you work in TypeScript or JavaScript, you do not need to generate types from this specification yourself — [`@vario-software/types`](https://www.npmjs.com/package/@vario-software/types) publishes them ready to use.
