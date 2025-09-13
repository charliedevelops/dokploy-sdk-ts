# MongoStopMount

## Example Usage

```typescript
import { MongoStopMount } from "dokploy-sdk/models/operations";

let value: MongoStopMount = {
  mountId: "<id>",
  type: "bind",
  hostPath: "<value>",
  volumeName: "<value>",
  filePath: "/etc/namedb/gadzooks.dot",
  content: "<value>",
  serviceType: "mysql",
  mountPath: "<value>",
  applicationId: "<id>",
  postgresId: "<id>",
  mariadbId: null,
  mongoId: "<id>",
  mysqlId: "<id>",
  redisId: null,
  composeId: "<id>",
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `mountId`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `type`                                                                             | [operations.MongoStopType](../../models/operations/mongostoptype.md)               | :heavy_check_mark:                                                                 | N/A                                                                                |
| `hostPath`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `volumeName`                                                                       | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `filePath`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `content`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `serviceType`                                                                      | [operations.MongoStopServiceType](../../models/operations/mongostopservicetype.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `mountPath`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `applicationId`                                                                    | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `postgresId`                                                                       | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `mariadbId`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `mongoId`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `mysqlId`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `redisId`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `composeId`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |