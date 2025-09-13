# MysqlStartResponseBody

Successful response

## Example Usage

```typescript
import { MysqlStartResponseBody } from "dokploy-sdk/models/operations";

let value: MysqlStartResponseBody = {
  mysqlId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "insert deceivingly prohibition hence helpless longboat",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: null,
  cpuLimit: "<value>",
  externalPort: 3468.37,
  applicationStatus: "done",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 7154.74,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 3399.93,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
  },
  networkSwarm: [
    {},
  ],
  replicas: 116.97,
  createdAt: "1733556026703",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "sedately chap incidentally roughly",
    createdAt: "1710222885044",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: null,
      createdAt: "1717966087532",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "what vain wonderfully",
    ipAddress: "13.5.91.241",
    port: 3803.19,
    username: "Luciano83",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1732348122504",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: "<value>",
  },
  backups: [],
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `mysqlId`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `name`                                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `appName`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `description`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `databaseName`                                                                                       | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `databaseUser`                                                                                       | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `databasePassword`                                                                                   | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `databaseRootPassword`                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `dockerImage`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `command`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `env`                                                                                                | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `memoryReservation`                                                                                  | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `memoryLimit`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `cpuReservation`                                                                                     | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `cpuLimit`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `externalPort`                                                                                       | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `applicationStatus`                                                                                  | [operations.MysqlStartApplicationStatus](../../models/operations/mysqlstartapplicationstatus.md)     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `healthCheckSwarm`                                                                                   | [operations.MysqlStartHealthCheckSwarm](../../models/operations/mysqlstarthealthcheckswarm.md)       | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `restartPolicySwarm`                                                                                 | [operations.MysqlStartRestartPolicySwarm](../../models/operations/mysqlstartrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `placementSwarm`                                                                                     | [operations.MysqlStartPlacementSwarm](../../models/operations/mysqlstartplacementswarm.md)           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `updateConfigSwarm`                                                                                  | [operations.MysqlStartUpdateConfigSwarm](../../models/operations/mysqlstartupdateconfigswarm.md)     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `rollbackConfigSwarm`                                                                                | [operations.MysqlStartRollbackConfigSwarm](../../models/operations/mysqlstartrollbackconfigswarm.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `modeSwarm`                                                                                          | [operations.MysqlStartModeSwarm](../../models/operations/mysqlstartmodeswarm.md)                     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `labelsSwarm`                                                                                        | Record<string, *string*>                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `networkSwarm`                                                                                       | [operations.MysqlStartNetworkSwarm](../../models/operations/mysqlstartnetworkswarm.md)[]             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `replicas`                                                                                           | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `createdAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `environmentId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `serverId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `environment`                                                                                        | [operations.MysqlStartEnvironment](../../models/operations/mysqlstartenvironment.md)                 | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `mounts`                                                                                             | [operations.MysqlStartMount](../../models/operations/mysqlstartmount.md)[]                           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `server`                                                                                             | [operations.MysqlStartServer](../../models/operations/mysqlstartserver.md)                           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `backups`                                                                                            | [operations.MysqlStartBackup](../../models/operations/mysqlstartbackup.md)[]                         | :heavy_check_mark:                                                                                   | N/A                                                                                                  |