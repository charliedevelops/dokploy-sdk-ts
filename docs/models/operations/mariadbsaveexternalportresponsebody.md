# MariadbSaveExternalPortResponseBody

Successful response

## Example Usage

```typescript
import { MariadbSaveExternalPortResponseBody } from "dokploy-sdk/models/operations";

let value: MariadbSaveExternalPortResponseBody = {
  mariadbId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "brr immediately stump hmph",
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
  externalPort: 5549.03,
  applicationStatus: "done",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 201.89,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 2378.06,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  networkSwarm: [],
  replicas: 8769.89,
  createdAt: "1724799748148",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "grandson until playfully gentle reschedule annually",
    createdAt: "1704180096982",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "assail although er",
      createdAt: "1723720328670",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "geez whine sneaky gee but till excluding reproachfully",
    ipAddress: "df4b:4b23:02da:6d87:3b66:a56f:e92b:adea",
    port: 9320.4,
    username: "Lia73",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1718959776780",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: [
      "<value 1>",
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
      keepLatestCount: 9882.1,
      backupType: "database",
      databaseType: "mysql",
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

| Field                                                                                                                          | Type                                                                                                                           | Required                                                                                                                       | Description                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ |
| `mariadbId`                                                                                                                    | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `name`                                                                                                                         | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `appName`                                                                                                                      | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `description`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `databaseName`                                                                                                                 | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `databaseUser`                                                                                                                 | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `databasePassword`                                                                                                             | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `databaseRootPassword`                                                                                                         | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `dockerImage`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `command`                                                                                                                      | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `env`                                                                                                                          | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `memoryReservation`                                                                                                            | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `memoryLimit`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `cpuReservation`                                                                                                               | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `cpuLimit`                                                                                                                     | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `externalPort`                                                                                                                 | *number*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `applicationStatus`                                                                                                            | [operations.MariadbSaveExternalPortApplicationStatus](../../models/operations/mariadbsaveexternalportapplicationstatus.md)     | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `healthCheckSwarm`                                                                                                             | [operations.MariadbSaveExternalPortHealthCheckSwarm](../../models/operations/mariadbsaveexternalporthealthcheckswarm.md)       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `restartPolicySwarm`                                                                                                           | [operations.MariadbSaveExternalPortRestartPolicySwarm](../../models/operations/mariadbsaveexternalportrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `placementSwarm`                                                                                                               | [operations.MariadbSaveExternalPortPlacementSwarm](../../models/operations/mariadbsaveexternalportplacementswarm.md)           | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `updateConfigSwarm`                                                                                                            | [operations.MariadbSaveExternalPortUpdateConfigSwarm](../../models/operations/mariadbsaveexternalportupdateconfigswarm.md)     | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `rollbackConfigSwarm`                                                                                                          | [operations.MariadbSaveExternalPortRollbackConfigSwarm](../../models/operations/mariadbsaveexternalportrollbackconfigswarm.md) | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `modeSwarm`                                                                                                                    | [operations.MariadbSaveExternalPortModeSwarm](../../models/operations/mariadbsaveexternalportmodeswarm.md)                     | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `labelsSwarm`                                                                                                                  | Record<string, *string*>                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `networkSwarm`                                                                                                                 | [operations.MariadbSaveExternalPortNetworkSwarm](../../models/operations/mariadbsaveexternalportnetworkswarm.md)[]             | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `replicas`                                                                                                                     | *number*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `createdAt`                                                                                                                    | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `environmentId`                                                                                                                | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `serverId`                                                                                                                     | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `environment`                                                                                                                  | [operations.MariadbSaveExternalPortEnvironment](../../models/operations/mariadbsaveexternalportenvironment.md)                 | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `mounts`                                                                                                                       | [operations.MariadbSaveExternalPortMount](../../models/operations/mariadbsaveexternalportmount.md)[]                           | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `server`                                                                                                                       | [operations.MariadbSaveExternalPortServer](../../models/operations/mariadbsaveexternalportserver.md)                           | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `backups`                                                                                                                      | [operations.MariadbSaveExternalPortBackup](../../models/operations/mariadbsaveexternalportbackup.md)[]                         | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |