# MongoStartResponseBody

Successful response

## Example Usage

```typescript
import { MongoStartResponseBody } from "dokploy-sdk/models/operations";

let value: MongoStartResponseBody = {
  mongoId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "hmph surprisingly gosh powerfully",
  databaseUser: "<value>",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: null,
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 4280.58,
  applicationStatus: "running",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 5510.17,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 7044.77,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  networkSwarm: [
    {},
  ],
  replicas: 9188.7,
  createdAt: "1718251560372",
  environmentId: "<id>",
  serverId: "<id>",
  replicaSets: true,
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: null,
    createdAt: "1715955722785",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "whereas whirlwind vainly which turret probe whoever near hello",
      createdAt: "1706362761378",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [
    {
      mountId: "<id>",
      type: "file",
      hostPath: "<value>",
      volumeName: "<value>",
      filePath: "/tmp/wildly_jaggedly.doc",
      content: "<value>",
      serviceType: "compose",
      mountPath: "<value>",
      applicationId: "<id>",
      postgresId: "<id>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mysqlId: "<id>",
      redisId: null,
      composeId: "<id>",
    },
  ],
  server: null,
  backups: [],
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `mongoId`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `name`                                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `appName`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `description`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `databaseUser`                                                                                       | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `databasePassword`                                                                                   | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `dockerImage`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `command`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `env`                                                                                                | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `memoryReservation`                                                                                  | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `memoryLimit`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `cpuReservation`                                                                                     | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `cpuLimit`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `externalPort`                                                                                       | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `applicationStatus`                                                                                  | [operations.MongoStartApplicationStatus](../../models/operations/mongostartapplicationstatus.md)     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `healthCheckSwarm`                                                                                   | [operations.MongoStartHealthCheckSwarm](../../models/operations/mongostarthealthcheckswarm.md)       | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `restartPolicySwarm`                                                                                 | [operations.MongoStartRestartPolicySwarm](../../models/operations/mongostartrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `placementSwarm`                                                                                     | [operations.MongoStartPlacementSwarm](../../models/operations/mongostartplacementswarm.md)           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `updateConfigSwarm`                                                                                  | [operations.MongoStartUpdateConfigSwarm](../../models/operations/mongostartupdateconfigswarm.md)     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `rollbackConfigSwarm`                                                                                | [operations.MongoStartRollbackConfigSwarm](../../models/operations/mongostartrollbackconfigswarm.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `modeSwarm`                                                                                          | [operations.MongoStartModeSwarm](../../models/operations/mongostartmodeswarm.md)                     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `labelsSwarm`                                                                                        | Record<string, *string*>                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `networkSwarm`                                                                                       | [operations.MongoStartNetworkSwarm](../../models/operations/mongostartnetworkswarm.md)[]             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `replicas`                                                                                           | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `createdAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `environmentId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `serverId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `replicaSets`                                                                                        | *boolean*                                                                                            | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `environment`                                                                                        | [operations.MongoStartEnvironment](../../models/operations/mongostartenvironment.md)                 | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `mounts`                                                                                             | [operations.MongoStartMount](../../models/operations/mongostartmount.md)[]                           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `server`                                                                                             | [operations.MongoStartServer](../../models/operations/mongostartserver.md)                           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `backups`                                                                                            | [operations.MongoStartBackup](../../models/operations/mongostartbackup.md)[]                         | :heavy_check_mark:                                                                                   | N/A                                                                                                  |