# PostgresDeployMount

## Example Usage

```typescript
import { PostgresDeployMount } from "dokploy-sdk/models/operations";

let value: PostgresDeployMount = {
  applicationId: "<id>",
  composeId: "<id>",
  content: "<value>",
  filePath: "/root/duh_furthermore.bmp",
  hostPath: "<value>",
  mariadbId: null,
  mongoId: "<id>",
  mountId: "<id>",
  mountPath: "<value>",
  mysqlId: "<id>",
  postgresId: "<id>",
  redisId: "<id>",
  serviceType: "mariadb",
  type: "volume",
  volumeName: "<value>",
};
```

## Fields

| Field                                                                                        | Type                                                                                         | Required                                                                                     | Description                                                                                  |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `applicationId`                                                                              | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `composeId`                                                                                  | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `content`                                                                                    | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `filePath`                                                                                   | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `hostPath`                                                                                   | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `mariadbId`                                                                                  | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `mongoId`                                                                                    | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `mountId`                                                                                    | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `mountPath`                                                                                  | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `mysqlId`                                                                                    | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `postgresId`                                                                                 | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `redisId`                                                                                    | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `serviceType`                                                                                | [operations.PostgresDeployServiceType](../../models/operations/postgresdeployservicetype.md) | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `type`                                                                                       | [operations.PostgresDeployType](../../models/operations/postgresdeploytype.md)               | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `volumeName`                                                                                 | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |