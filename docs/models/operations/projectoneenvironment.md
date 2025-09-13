# ProjectOneEnvironment

## Example Usage

```typescript
import { ProjectOneEnvironment } from "dokploy-sdk/models/operations";

let value: ProjectOneEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "abaft brown ham natural eek than factorise who underpants",
  createdAt: "1718071541233",
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