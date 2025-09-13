# PostgresRemoveResponseBody

Successful response

## Example Usage

```typescript
import { PostgresRemoveResponseBody } from "dokploy-sdk/models/operations";

let value: PostgresRemoveResponseBody = {
  postgresId: "<id>",
  name: "<value>",
  appName: "<value>",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  description:
    "boohoo beneath boldly multicolored provided spice below muscat jealous down",
  dockerImage: "<value>",
  command: null,
  env: "<value>",
  memoryReservation: "<value>",
  externalPort: 6630.14,
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  applicationStatus: "done",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: null,
  updateConfigSwarm: {
    parallelism: 8763.1,
    order: "<value>",
  },
  rollbackConfigSwarm: null,
  modeSwarm: {},
  labelsSwarm: null,
  networkSwarm: [
    {},
  ],
  replicas: 3324.44,
  createdAt: "1728900974952",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description:
      "traditionalism once cinder behind primary doubtfully jeopardise along",
    createdAt: "1707054583750",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: null,
      createdAt: "1730231254737",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "lumbering if gah hippodrome",
    ipAddress: "222.91.173.60",
    port: 1306.56,
    username: "Monica_Walker",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1707205229902",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: 6688.76,
  },
  backups: [],
};
```

## Fields

| Field                                                                                                        | Type                                                                                                         | Required                                                                                                     | Description                                                                                                  |
| ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| `postgresId`                                                                                                 | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `name`                                                                                                       | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `appName`                                                                                                    | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `databaseName`                                                                                               | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `databaseUser`                                                                                               | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `databasePassword`                                                                                           | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `description`                                                                                                | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `dockerImage`                                                                                                | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `command`                                                                                                    | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `env`                                                                                                        | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `memoryReservation`                                                                                          | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `externalPort`                                                                                               | *number*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `memoryLimit`                                                                                                | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `cpuReservation`                                                                                             | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `cpuLimit`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `applicationStatus`                                                                                          | [operations.PostgresRemoveApplicationStatus](../../models/operations/postgresremoveapplicationstatus.md)     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `healthCheckSwarm`                                                                                           | [operations.PostgresRemoveHealthCheckSwarm](../../models/operations/postgresremovehealthcheckswarm.md)       | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `restartPolicySwarm`                                                                                         | [operations.PostgresRemoveRestartPolicySwarm](../../models/operations/postgresremoverestartpolicyswarm.md)   | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `placementSwarm`                                                                                             | [operations.PostgresRemovePlacementSwarm](../../models/operations/postgresremoveplacementswarm.md)           | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `updateConfigSwarm`                                                                                          | [operations.PostgresRemoveUpdateConfigSwarm](../../models/operations/postgresremoveupdateconfigswarm.md)     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `rollbackConfigSwarm`                                                                                        | [operations.PostgresRemoveRollbackConfigSwarm](../../models/operations/postgresremoverollbackconfigswarm.md) | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `modeSwarm`                                                                                                  | [operations.PostgresRemoveModeSwarm](../../models/operations/postgresremovemodeswarm.md)                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `labelsSwarm`                                                                                                | Record<string, *string*>                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `networkSwarm`                                                                                               | [operations.PostgresRemoveNetworkSwarm](../../models/operations/postgresremovenetworkswarm.md)[]             | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `replicas`                                                                                                   | *number*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `createdAt`                                                                                                  | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `environmentId`                                                                                              | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `serverId`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `environment`                                                                                                | [operations.PostgresRemoveEnvironment](../../models/operations/postgresremoveenvironment.md)                 | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `mounts`                                                                                                     | [operations.PostgresRemoveMount](../../models/operations/postgresremovemount.md)[]                           | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `server`                                                                                                     | [operations.PostgresRemoveServer](../../models/operations/postgresremoveserver.md)                           | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `backups`                                                                                                    | [operations.PostgresRemoveBackup](../../models/operations/postgresremovebackup.md)[]                         | :heavy_check_mark:                                                                                           | N/A                                                                                                          |