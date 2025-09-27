# ApplicationStartMount

## Example Usage

```typescript
import { ApplicationStartMount } from "dokploy-sdk/models/operations";

let value: ApplicationStartMount = {
  applicationId: "<id>",
  composeId: "<id>",
  content: "<value>",
  filePath: "/mnt/cafe_illiterate_blah.htm",
  hostPath: "<value>",
  mariadbId: "<id>",
  mongoId: "<id>",
  mountId: "<id>",
  mountPath: "<value>",
  mysqlId: "<id>",
  postgresId: "<id>",
  redisId: "<id>",
  serviceType: "mysql",
  type: "volume",
  volumeName: "<value>",
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `applicationId`                                                                                  | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `composeId`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `content`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `filePath`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `hostPath`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `mariadbId`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `mongoId`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `mountId`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `mountPath`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `mysqlId`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `postgresId`                                                                                     | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `redisId`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `serviceType`                                                                                    | [operations.ApplicationStartServiceType](../../models/operations/applicationstartservicetype.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `type`                                                                                           | [operations.ApplicationStartType](../../models/operations/applicationstarttype.md)               | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `volumeName`                                                                                     | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |