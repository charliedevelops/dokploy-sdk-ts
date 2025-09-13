# ProjectAllEnvironment

## Example Usage

```typescript
import { ProjectAllEnvironment } from "dokploy-sdk/models/operations";

let value: ProjectAllEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "as fathom tune opposite",
  createdAt: "1732484648520",
  env: "<value>",
  projectId: "<id>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `environmentId`    | *string*           | :heavy_check_mark: | N/A                |
| `name`             | *string*           | :heavy_check_mark: | N/A                |
| `description`      | *string*           | :heavy_check_mark: | N/A                |
| `createdAt`        | *string*           | :heavy_check_mark: | N/A                |
| `env`              | *string*           | :heavy_check_mark: | N/A                |
| `projectId`        | *string*           | :heavy_check_mark: | N/A                |
| `applications`     | *any*[]            | :heavy_minus_sign: | N/A                |
| `compose`          | *any*[]            | :heavy_minus_sign: | N/A                |
| `mariadb`          | *any*[]            | :heavy_minus_sign: | N/A                |
| `mongo`            | *any*[]            | :heavy_minus_sign: | N/A                |
| `mysql`            | *any*[]            | :heavy_minus_sign: | N/A                |
| `postgres`         | *any*[]            | :heavy_minus_sign: | N/A                |
| `redis`            | *any*[]            | :heavy_minus_sign: | N/A                |