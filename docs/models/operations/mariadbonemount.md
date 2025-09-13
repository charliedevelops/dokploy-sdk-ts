# MariadbOneMount

## Example Usage

```typescript
import { MariadbOneMount } from "dokploy-sdk/models/operations";

let value: MariadbOneMount = {
  mountId: "<id>",
  type: "bind",
  hostPath: null,
  volumeName: "<value>",
  filePath: "/var/log/times.war",
  content: "<value>",
  serviceType: "mongo",
  mountPath: "<value>",
  applicationId: "<id>",
  postgresId: "<id>",
  mariadbId: "<id>",
  mongoId: "<id>",
  mysqlId: "<id>",
  redisId: "<id>",
  composeId: "<id>",
};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `mountId`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `type`                                                                               | [operations.MariadbOneType](../../models/operations/mariadbonetype.md)               | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `hostPath`                                                                           | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `volumeName`                                                                         | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `filePath`                                                                           | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `content`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `serviceType`                                                                        | [operations.MariadbOneServiceType](../../models/operations/mariadboneservicetype.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `mountPath`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `applicationId`                                                                      | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `postgresId`                                                                         | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `mariadbId`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `mongoId`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `mysqlId`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `redisId`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `composeId`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |