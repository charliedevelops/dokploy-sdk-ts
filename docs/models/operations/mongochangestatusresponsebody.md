# MongoChangeStatusResponseBody

Successful response

## Example Usage

```typescript
import { MongoChangeStatusResponseBody } from "dokploy-sdk/models/operations";

let value: MongoChangeStatusResponseBody = {
  appName: "<value>",
  applicationStatus: "error",
  backups: [],
  command: "<value>",
  cpuLimit: null,
  cpuReservation: "<value>",
  createdAt: "1721604921202",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: "exploration carelessly guard after impassioned solace aw",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1705473620693",
    description:
      "um outsource underneath why mantua developmental while likable characterization",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1707082650676",
      description:
        "pish amongst considering astride gosh scorpion properly provided solicit sometimes",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 1786.65,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mongoId: "<id>",
  mounts: [],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: {},
  replicaSets: false,
  replicas: 6680.93,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 6097.55,
  },
  server: null,
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 7803.49,
  },
};
```

## Fields

| Field                                                                                                                          | Type                                                                                                                           | Required                                                                                                                       | Description                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ |
| `appName`                                                                                                                      | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `applicationStatus`                                                                                                            | [operations.MongoChangeStatusApplicationStatusResponse](../../models/operations/mongochangestatusapplicationstatusresponse.md) | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `backups`                                                                                                                      | [operations.MongoChangeStatusBackup](../../models/operations/mongochangestatusbackup.md)[]                                     | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `command`                                                                                                                      | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `cpuLimit`                                                                                                                     | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `cpuReservation`                                                                                                               | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `createdAt`                                                                                                                    | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `databasePassword`                                                                                                             | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `databaseUser`                                                                                                                 | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `description`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `dockerImage`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `env`                                                                                                                          | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `environment`                                                                                                                  | [operations.MongoChangeStatusEnvironment](../../models/operations/mongochangestatusenvironment.md)                             | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `environmentId`                                                                                                                | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `externalPort`                                                                                                                 | *number*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `healthCheckSwarm`                                                                                                             | [operations.MongoChangeStatusHealthCheckSwarm](../../models/operations/mongochangestatushealthcheckswarm.md)                   | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `labelsSwarm`                                                                                                                  | Record<string, *string*>                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `memoryLimit`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `memoryReservation`                                                                                                            | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `modeSwarm`                                                                                                                    | [operations.MongoChangeStatusModeSwarm](../../models/operations/mongochangestatusmodeswarm.md)                                 | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `mongoId`                                                                                                                      | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `mounts`                                                                                                                       | [operations.MongoChangeStatusMount](../../models/operations/mongochangestatusmount.md)[]                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `name`                                                                                                                         | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `networkSwarm`                                                                                                                 | [operations.MongoChangeStatusNetworkSwarm](../../models/operations/mongochangestatusnetworkswarm.md)[]                         | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `placementSwarm`                                                                                                               | [operations.MongoChangeStatusPlacementSwarm](../../models/operations/mongochangestatusplacementswarm.md)                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `replicaSets`                                                                                                                  | *boolean*                                                                                                                      | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `replicas`                                                                                                                     | *number*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `restartPolicySwarm`                                                                                                           | [operations.MongoChangeStatusRestartPolicySwarm](../../models/operations/mongochangestatusrestartpolicyswarm.md)               | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `rollbackConfigSwarm`                                                                                                          | [operations.MongoChangeStatusRollbackConfigSwarm](../../models/operations/mongochangestatusrollbackconfigswarm.md)             | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `server`                                                                                                                       | [operations.MongoChangeStatusServer](../../models/operations/mongochangestatusserver.md)                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `serverId`                                                                                                                     | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `updateConfigSwarm`                                                                                                            | [operations.MongoChangeStatusUpdateConfigSwarm](../../models/operations/mongochangestatusupdateconfigswarm.md)                 | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |