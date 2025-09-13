# RedisSaveExternalPortMount

## Example Usage

```typescript
import { RedisSaveExternalPortMount } from "dokploy-sdk/models/operations";

let value: RedisSaveExternalPortMount = {
  applicationId: "<id>",
  composeId: "<id>",
  content: "<value>",
  filePath: null,
  hostPath: "<value>",
  mariadbId: "<id>",
  mongoId: "<id>",
  mountId: "<id>",
  mountPath: "<value>",
  mysqlId: "<id>",
  postgresId: null,
  redisId: "<id>",
  serviceType: "mongo",
  type: "file",
  volumeName: "<value>",
};
```

## Fields

| Field                                                                                                      | Type                                                                                                       | Required                                                                                                   | Description                                                                                                |
| ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| `applicationId`                                                                                            | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `composeId`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `content`                                                                                                  | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `filePath`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `hostPath`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `mariadbId`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `mongoId`                                                                                                  | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `mountId`                                                                                                  | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `mountPath`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `mysqlId`                                                                                                  | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `postgresId`                                                                                               | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `redisId`                                                                                                  | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `serviceType`                                                                                              | [operations.RedisSaveExternalPortServiceType](../../models/operations/redissaveexternalportservicetype.md) | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `type`                                                                                                     | [operations.RedisSaveExternalPortType](../../models/operations/redissaveexternalporttype.md)               | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `volumeName`                                                                                               | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |