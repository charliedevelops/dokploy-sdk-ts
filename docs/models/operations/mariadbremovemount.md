# MariadbRemoveMount

## Example Usage

```typescript
import { MariadbRemoveMount } from "dokploy-sdk/models/operations";

let value: MariadbRemoveMount = {
  applicationId: "<id>",
  composeId: "<id>",
  content: "<value>",
  filePath: "/usr/X11R6/fleck_cram_pish.eot",
  hostPath: "<value>",
  mariadbId: "<id>",
  mongoId: "<id>",
  mountId: "<id>",
  mountPath: "<value>",
  mysqlId: "<id>",
  postgresId: null,
  redisId: "<id>",
  serviceType: "redis",
  type: "file",
  volumeName: null,
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `applicationId`                                                                            | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `composeId`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `content`                                                                                  | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `filePath`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `hostPath`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `mariadbId`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `mongoId`                                                                                  | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `mountId`                                                                                  | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `mountPath`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `mysqlId`                                                                                  | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `postgresId`                                                                               | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `redisId`                                                                                  | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `serviceType`                                                                              | [operations.MariadbRemoveServiceType](../../models/operations/mariadbremoveservicetype.md) | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `type`                                                                                     | [operations.MariadbRemoveType](../../models/operations/mariadbremovetype.md)               | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `volumeName`                                                                               | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |