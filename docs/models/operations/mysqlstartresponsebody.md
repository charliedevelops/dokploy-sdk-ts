# MysqlStartResponseBody

Successful response

## Example Usage

```typescript
import { MysqlStartResponseBody } from "dokploy-sdk/models/operations";

let value: MysqlStartResponseBody = {
  appName: "<value>",
  applicationStatus: "error",
  backups: [],
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1727187352540",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  databaseUser: "<value>",
  description: "a ick swiftly mature",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1707609077627",
    description: "technologist alongside membership fledgling mmm",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1712931505026",
      description: "pish mouser interestingly fond",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 7076.13,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: null,
  mounts: [],
  mysqlId: "<id>",
  name: "<value>",
  networkSwarm: [
    {},
  ],
  placementSwarm: {},
  replicas: 8000.77,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 3336.8,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1704906242413",
    description:
      "display upwardly negligible dividend yahoo inside quarrelsomely compassionate scratchy dearly",
    enableDockerCleanup: false,
    ipAddress: "4.63.118.171",
    metricsConfig: "<value>",
    name: "<value>",
    organizationId: "<id>",
    port: 8778.1,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Henriette.Abbott",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 1105.08,
  },
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `appName`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `applicationStatus`                                                                                  | [operations.MysqlStartApplicationStatus](../../models/operations/mysqlstartapplicationstatus.md)     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `backups`                                                                                            | [operations.MysqlStartBackup](../../models/operations/mysqlstartbackup.md)[]                         | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `command`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `cpuLimit`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `cpuReservation`                                                                                     | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `createdAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `databaseName`                                                                                       | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `databasePassword`                                                                                   | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `databaseRootPassword`                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `databaseUser`                                                                                       | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `description`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `dockerImage`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `env`                                                                                                | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `environment`                                                                                        | [operations.MysqlStartEnvironment](../../models/operations/mysqlstartenvironment.md)                 | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `environmentId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `externalPort`                                                                                       | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `healthCheckSwarm`                                                                                   | [operations.MysqlStartHealthCheckSwarm](../../models/operations/mysqlstarthealthcheckswarm.md)       | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `labelsSwarm`                                                                                        | Record<string, *string*>                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `memoryLimit`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `memoryReservation`                                                                                  | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `modeSwarm`                                                                                          | [operations.MysqlStartModeSwarm](../../models/operations/mysqlstartmodeswarm.md)                     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `mounts`                                                                                             | [operations.MysqlStartMount](../../models/operations/mysqlstartmount.md)[]                           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `mysqlId`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `name`                                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `networkSwarm`                                                                                       | [operations.MysqlStartNetworkSwarm](../../models/operations/mysqlstartnetworkswarm.md)[]             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `placementSwarm`                                                                                     | [operations.MysqlStartPlacementSwarm](../../models/operations/mysqlstartplacementswarm.md)           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `replicas`                                                                                           | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `restartPolicySwarm`                                                                                 | [operations.MysqlStartRestartPolicySwarm](../../models/operations/mysqlstartrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `rollbackConfigSwarm`                                                                                | [operations.MysqlStartRollbackConfigSwarm](../../models/operations/mysqlstartrollbackconfigswarm.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `server`                                                                                             | [operations.MysqlStartServer](../../models/operations/mysqlstartserver.md)                           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `serverId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `updateConfigSwarm`                                                                                  | [operations.MysqlStartUpdateConfigSwarm](../../models/operations/mysqlstartupdateconfigswarm.md)     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |