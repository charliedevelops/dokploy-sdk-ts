# MysqlOneMount

## Example Usage

```typescript
import { MysqlOneMount } from "dokploy-sdk/models/operations";

let value: MysqlOneMount = {
  mountId: "<id>",
  type: "file",
  hostPath: "<value>",
  volumeName: "<value>",
  filePath: "/usr/local/bin/overconfidently.dump",
  content: "<value>",
  serviceType: "mysql",
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

| Field                                                                            | Type                                                                             | Required                                                                         | Description                                                                      |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| `mountId`                                                                        | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `type`                                                                           | [operations.MysqlOneType](../../models/operations/mysqlonetype.md)               | :heavy_check_mark:                                                               | N/A                                                                              |
| `hostPath`                                                                       | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `volumeName`                                                                     | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `filePath`                                                                       | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `content`                                                                        | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `serviceType`                                                                    | [operations.MysqlOneServiceType](../../models/operations/mysqloneservicetype.md) | :heavy_check_mark:                                                               | N/A                                                                              |
| `mountPath`                                                                      | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `applicationId`                                                                  | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `postgresId`                                                                     | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `mariadbId`                                                                      | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `mongoId`                                                                        | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `mysqlId`                                                                        | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `redisId`                                                                        | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `composeId`                                                                      | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |