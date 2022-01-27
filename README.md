# @himenon/atlassian-jira-typescript-openapi

```bash
yarn add -D @himenon/atlassian-jira-typescript-openapi
```

## Usage

```ts
import * as fs from "fs";
import type { Schemas, Client } from "@himenon/atlassian-jira-typescript-openapi/v3";
```

## Build

```ts
yarn run build
```

## Update Schemas

```bash
# Fetch and Build
yarn run build:all

# Fetch schemas
yarn run fetch:schemas

# Generate source code
yarn run generate:code
```

## OpenAPI Source for ArgoCD

- <https://developer.atlassian.com/cloud/jira/platform/swagger-v3.v3.json>

## OpenAPI TypeScript Code Generator

- [@himenon/openapi-typescript-code-generator](https://github.com/Himenon/openapi-typescript-code-generator)

You can also just use the type definition

## Use Another Version

Edit [config.ts](./scripts/config.ts)

## LICENCE

[@Himenon/atlassian-jira-typescript-openapi](https://github.com/Himenon/atlassian-jira-typescript-openapi)・MIT
