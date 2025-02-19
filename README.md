# Humanloop Fern Configuration

This repository contains your Fern Configuration:

- [OpenAPI spec](./openapi.yml)
<!-- - [Generators config](./fern/generators.yml) -->

## Setup

```sh
npm install -g fern-api # only required once
```

## Validating your API Definition

To validate your API, run:

```sh
fern check
```

## Changing docs

To see a preview of your docs as you write them, run:

```sh
fern docs dev
```

To see a exact preview fully rendered, run:

```sh
fern generate --docs --preview
```

and you'll get a preview URL.

## Deploying your Docs

```sh
npm install -g fern-api # only required once
fern docs
```
