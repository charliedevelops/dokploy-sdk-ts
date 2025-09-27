# MariadbSaveExternalPortResponseBody

Successful response

## Example Usage

```typescript
import { MariadbSaveExternalPortResponseBody } from "dokploy-sdk/models/operations";

let value: MariadbSaveExternalPortResponseBody = {
  appName: "<value>",
  applicationStatus: "done",
  backups: [],
  command: null,
  cpuLimit: null,
  cpuReservation: "<value>",
  createdAt: "1712284784177",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  databaseUser: "<value>",
  description: "apropos uh-huh so",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1711048859426",
    description: "rue label um but including apud",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1733180289037",
      description: "uh-huh reasoning beside even duh er per huzzah",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 5832.89,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  mariadbId: "<id>",
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [],
  name: "<value>",
  networkSwarm: [
    {},
  ],
  placementSwarm: {},
  replicas: 493.99,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 7268.99,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1708402517607",
    description: null,
    enableDockerCleanup: true,
    ipAddress: "81.8.0.37",
    metricsConfig: {},
    name: "<value>",
    organizationId: "<id>",
    port: 6661.24,
    serverId: "<id>",
    serverStatus: "active",
    sshKeyId: "<id>",
    username: "Sid.Wyman23",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 9919.51,
  },
};
```

## Fields

| Field                                                                                                                          | Type                                                                                                                           | Required                                                                                                                       | Description                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ |
| `appName`                                                                                                                      | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `applicationStatus`                                                                                                            | [operations.MariadbSaveExternalPortApplicationStatus](../../models/operations/mariadbsaveexternalportapplicationstatus.md)     | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `backups`                                                                                                                      | [operations.MariadbSaveExternalPortBackup](../../models/operations/mariadbsaveexternalportbackup.md)[]                         | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `command`                                                                                                                      | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `cpuLimit`                                                                                                                     | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `cpuReservation`                                                                                                               | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `createdAt`                                                                                                                    | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `databaseName`                                                                                                                 | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `databasePassword`                                                                                                             | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `databaseRootPassword`                                                                                                         | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `databaseUser`                                                                                                                 | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `description`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `dockerImage`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `env`                                                                                                                          | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `environment`                                                                                                                  | [operations.MariadbSaveExternalPortEnvironment](../../models/operations/mariadbsaveexternalportenvironment.md)                 | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `environmentId`                                                                                                                | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `externalPort`                                                                                                                 | *number*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `healthCheckSwarm`                                                                                                             | [operations.MariadbSaveExternalPortHealthCheckSwarm](../../models/operations/mariadbsaveexternalporthealthcheckswarm.md)       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `labelsSwarm`                                                                                                                  | Record<string, *string*>                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `mariadbId`                                                                                                                    | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `memoryLimit`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `memoryReservation`                                                                                                            | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `modeSwarm`                                                                                                                    | [operations.MariadbSaveExternalPortModeSwarm](../../models/operations/mariadbsaveexternalportmodeswarm.md)                     | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `mounts`                                                                                                                       | [operations.MariadbSaveExternalPortMount](../../models/operations/mariadbsaveexternalportmount.md)[]                           | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `name`                                                                                                                         | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `networkSwarm`                                                                                                                 | [operations.MariadbSaveExternalPortNetworkSwarm](../../models/operations/mariadbsaveexternalportnetworkswarm.md)[]             | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `placementSwarm`                                                                                                               | [operations.MariadbSaveExternalPortPlacementSwarm](../../models/operations/mariadbsaveexternalportplacementswarm.md)           | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `replicas`                                                                                                                     | *number*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `restartPolicySwarm`                                                                                                           | [operations.MariadbSaveExternalPortRestartPolicySwarm](../../models/operations/mariadbsaveexternalportrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `rollbackConfigSwarm`                                                                                                          | [operations.MariadbSaveExternalPortRollbackConfigSwarm](../../models/operations/mariadbsaveexternalportrollbackconfigswarm.md) | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `server`                                                                                                                       | [operations.MariadbSaveExternalPortServer](../../models/operations/mariadbsaveexternalportserver.md)                           | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `serverId`                                                                                                                     | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `updateConfigSwarm`                                                                                                            | [operations.MariadbSaveExternalPortUpdateConfigSwarm](../../models/operations/mariadbsaveexternalportupdateconfigswarm.md)     | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |