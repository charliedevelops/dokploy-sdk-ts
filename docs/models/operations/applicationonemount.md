# ApplicationOneMount

## Example Usage

```typescript
import { ApplicationOneMount } from "dokploy-sdk/models/operations";

let value: ApplicationOneMount = {
  applicationId: "<id>",
  composeId: "<id>",
  content: "<value>",
  filePath: "/mnt/phew_hmph.mp3",
  hostPath: "<value>",
  mariadbId: "<id>",
  mongoId: "<id>",
  mountId: "<id>",
  mountPath: "<value>",
  mysqlId: "<id>",
  postgresId: "<id>",
  redisId: null,
  serviceType: "postgres",
  type: "bind",
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
| `serviceType`                                                                                | [operations.ApplicationOneServiceType](../../models/operations/applicationoneservicetype.md) | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `type`                                                                                       | [operations.ApplicationOneType](../../models/operations/applicationonetype.md)               | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `volumeName`                                                                                 | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |