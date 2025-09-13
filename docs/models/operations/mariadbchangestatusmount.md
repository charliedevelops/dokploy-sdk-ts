# MariadbChangeStatusMount

## Example Usage

```typescript
import { MariadbChangeStatusMount } from "dokploy-sdk/models/operations";

let value: MariadbChangeStatusMount = {
  mountId: "<id>",
  type: "volume",
  hostPath: "<value>",
  volumeName: "<value>",
  filePath: "/home/user/dir/stranger.exe",
  content: "<value>",
  serviceType: "application",
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

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `mountId`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `type`                                                                                                 | [operations.MariadbChangeStatusType](../../models/operations/mariadbchangestatustype.md)               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `hostPath`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `volumeName`                                                                                           | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `filePath`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `content`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `serviceType`                                                                                          | [operations.MariadbChangeStatusServiceType](../../models/operations/mariadbchangestatusservicetype.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `mountPath`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `applicationId`                                                                                        | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `postgresId`                                                                                           | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `mariadbId`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `mongoId`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `mysqlId`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `redisId`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `composeId`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |