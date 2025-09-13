# MariadbOneResponseBody

Successful response

## Example Usage

```typescript
import { MariadbOneResponseBody } from "dokploy-sdk/models/operations";

let value: MariadbOneResponseBody = {
  mariadbId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "shyly repossess who",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: null,
  applicationStatus: "error",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 6910.11,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 2171.56,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: null,
  networkSwarm: null,
  replicas: 4463.62,
  createdAt: "1711952973984",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "furthermore questionable rout whirlwind",
    createdAt: "1708965231542",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "boohoo meh so round lumpy nor unimportant",
      createdAt: "1725568589968",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "deceivingly by barring after swat modulo harp through",
    ipAddress: "93.88.120.190",
    port: 313.14,
    username: "Kamren63",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1727830605032",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: null,
    metricsConfig: [
      "<value 1>",
      "<value 2>",
      "<value 3>",
    ],
  },
  backups: [
    {
      backupId: "<id>",
      appName: "<value>",
      schedule: "<value>",
      enabled: false,
      database: "<value>",
      prefix: "<value>",
      serviceName: "<value>",
      destinationId: "<id>",
      keepLatestCount: 6533.64,
      backupType: "database",
      databaseType: "mariadb",
      composeId: "<id>",
      postgresId: "<id>",
      mariadbId: "<id>",
      mysqlId: "<id>",
      mongoId: "<id>",
      userId: "<id>",
    },
  ],
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `mariadbId`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
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
| `applicationStatus`                                                                                  | [operations.MariadbOneApplicationStatus](../../models/operations/mariadboneapplicationstatus.md)     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `healthCheckSwarm`                                                                                   | [operations.MariadbOneHealthCheckSwarm](../../models/operations/mariadbonehealthcheckswarm.md)       | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `restartPolicySwarm`                                                                                 | [operations.MariadbOneRestartPolicySwarm](../../models/operations/mariadbonerestartpolicyswarm.md)   | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `placementSwarm`                                                                                     | [operations.MariadbOnePlacementSwarm](../../models/operations/mariadboneplacementswarm.md)           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `updateConfigSwarm`                                                                                  | [operations.MariadbOneUpdateConfigSwarm](../../models/operations/mariadboneupdateconfigswarm.md)     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `rollbackConfigSwarm`                                                                                | [operations.MariadbOneRollbackConfigSwarm](../../models/operations/mariadbonerollbackconfigswarm.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `modeSwarm`                                                                                          | [operations.MariadbOneModeSwarm](../../models/operations/mariadbonemodeswarm.md)                     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `labelsSwarm`                                                                                        | Record<string, *string*>                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `networkSwarm`                                                                                       | [operations.MariadbOneNetworkSwarm](../../models/operations/mariadbonenetworkswarm.md)[]             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `replicas`                                                                                           | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `createdAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `environmentId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `serverId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `environment`                                                                                        | [operations.MariadbOneEnvironment](../../models/operations/mariadboneenvironment.md)                 | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `mounts`                                                                                             | [operations.MariadbOneMount](../../models/operations/mariadbonemount.md)[]                           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `server`                                                                                             | [operations.MariadbOneServer](../../models/operations/mariadboneserver.md)                           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `backups`                                                                                            | [operations.MariadbOneBackup](../../models/operations/mariadbonebackup.md)[]                         | :heavy_check_mark:                                                                                   | N/A                                                                                                  |