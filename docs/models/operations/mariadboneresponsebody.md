# MariadbOneResponseBody

Successful response

## Example Usage

```typescript
import { MariadbOneResponseBody } from "dokploy-sdk/models/operations";

let value: MariadbOneResponseBody = {
  appName: "<value>",
  applicationStatus: "error",
  backups: [],
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1735497073509",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  databaseUser: "<value>",
  description: "insist once inquisitively",
  dockerImage: "<value>",
  env: null,
  environment: {
    createdAt: "1729371398270",
    description: "although er mainstream self-assured pro",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1712823222422",
      description:
        "phew oof willfully repentant promise than cleverly covenant repurpose",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 5131.34,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  mariadbId: "<id>",
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: null,
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: "/root/revere_fellow_among.mpeg",
      hostPath: "<value>",
      mariadbId: null,
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: "<id>",
      serviceType: "mysql",
      type: "bind",
      volumeName: "<value>",
    },
  ],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: {},
  replicas: 8063.52,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 5861.43,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1732329309074",
    description: null,
    enableDockerCleanup: false,
    ipAddress: "d962:a9fe:b887:aa0b:d4bd:fea4:1bdc:2db6",
    metricsConfig: [
      "<value 1>",
    ],
    name: "<value>",
    organizationId: "<id>",
    port: 3621.23,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Marge88",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 1371.99,
  },
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `appName`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `applicationStatus`                                                                                  | [operations.MariadbOneApplicationStatus](../../models/operations/mariadboneapplicationstatus.md)     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `backups`                                                                                            | [operations.MariadbOneBackup](../../models/operations/mariadbonebackup.md)[]                         | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
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
| `environment`                                                                                        | [operations.MariadbOneEnvironment](../../models/operations/mariadboneenvironment.md)                 | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `environmentId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `externalPort`                                                                                       | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `healthCheckSwarm`                                                                                   | [operations.MariadbOneHealthCheckSwarm](../../models/operations/mariadbonehealthcheckswarm.md)       | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `labelsSwarm`                                                                                        | Record<string, *string*>                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `mariadbId`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `memoryLimit`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `memoryReservation`                                                                                  | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `modeSwarm`                                                                                          | [operations.MariadbOneModeSwarm](../../models/operations/mariadbonemodeswarm.md)                     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `mounts`                                                                                             | [operations.MariadbOneMount](../../models/operations/mariadbonemount.md)[]                           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `name`                                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `networkSwarm`                                                                                       | [operations.MariadbOneNetworkSwarm](../../models/operations/mariadbonenetworkswarm.md)[]             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `placementSwarm`                                                                                     | [operations.MariadbOnePlacementSwarm](../../models/operations/mariadboneplacementswarm.md)           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `replicas`                                                                                           | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `restartPolicySwarm`                                                                                 | [operations.MariadbOneRestartPolicySwarm](../../models/operations/mariadbonerestartpolicyswarm.md)   | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `rollbackConfigSwarm`                                                                                | [operations.MariadbOneRollbackConfigSwarm](../../models/operations/mariadbonerollbackconfigswarm.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `server`                                                                                             | [operations.MariadbOneServer](../../models/operations/mariadboneserver.md)                           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `serverId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `updateConfigSwarm`                                                                                  | [operations.MariadbOneUpdateConfigSwarm](../../models/operations/mariadboneupdateconfigswarm.md)     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |