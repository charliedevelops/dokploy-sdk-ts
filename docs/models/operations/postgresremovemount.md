# PostgresRemoveMount

## Example Usage

```typescript
import { PostgresRemoveMount } from "dokploy-sdk/models/operations";

let value: PostgresRemoveMount = {
  mountId: "<id>",
  type: "bind",
  hostPath: "<value>",
  volumeName: "<value>",
  filePath: "/Applications/ugh_substitution_personal.xhtml",
  content: "<value>",
  serviceType: "mariadb",
  mountPath: "<value>",
  applicationId: "<id>",
  postgresId: "<id>",
  mariadbId: "<id>",
  mongoId: "<id>",
  mysqlId: null,
  redisId: "<id>",
  composeId: null,
};
```

## Fields

| Field                                                                                        | Type                                                                                         | Required                                                                                     | Description                                                                                  |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `mountId`                                                                                    | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `type`                                                                                       | [operations.PostgresRemoveType](../../models/operations/postgresremovetype.md)               | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `hostPath`                                                                                   | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `volumeName`                                                                                 | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `filePath`                                                                                   | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `content`                                                                                    | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `serviceType`                                                                                | [operations.PostgresRemoveServiceType](../../models/operations/postgresremoveservicetype.md) | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `mountPath`                                                                                  | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `applicationId`                                                                              | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `postgresId`                                                                                 | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `mariadbId`                                                                                  | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `mongoId`                                                                                    | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `mysqlId`                                                                                    | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `redisId`                                                                                    | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `composeId`                                                                                  | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |