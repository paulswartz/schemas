# MBTA Event Schemas

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Schema Validation

``` shell
# Check that the schemas in `schemas/` are valid
$ yarn test:schemas

# Check that the examples in `examples/` match the schemas in `schemas/`
$ yarn test:examples
```

### Testing

``` shell
$ yarn ci
# or 
$ yarn format --check
$ yarn typecheck
$ yarn test
```

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Deployment happens via [Github Actions](https://github.com/mbta/schemas/actions).
