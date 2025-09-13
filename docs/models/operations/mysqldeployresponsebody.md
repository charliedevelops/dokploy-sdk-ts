# MysqlDeployResponseBody

Successful response

## Example Usage

```typescript
import { MysqlDeployResponseBody } from "dokploy-sdk/models/operations";

let value: MysqlDeployResponseBody = {
  mysqlId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "versus thoughtfully once peaceful",
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
  externalPort: 1103.26,
  applicationStatus: "running",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: null,
  updateConfigSwarm: {
    parallelism: 2253.22,
    order: "<value>",
  },
  rollbackConfigSwarm: null,
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
  },
  networkSwarm: [
    {},
  ],
  replicas: 686.28,
  createdAt: "1706911331440",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "drat and off outbid yowza wholly if judgementally",
    createdAt: "1733777181479",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: null,
      createdAt: "1729299618308",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [
    {
      mountId: "<id>",
      type: "volume",
      hostPath: "<value>",
      volumeName: "<value>",
      filePath: "/lib/bah_scarification_milky.dms",
      content: "<value>",
      serviceType: "application",
      mountPath: "<value>",
      applicationId: "<id>",
      postgresId: "<id>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mysqlId: "<id>",
      redisId: "<id>",
      composeId: "<id>",
    },
  ],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "excepting recompense cope capitalise",
    ipAddress: "adae:313e:dda2:02dd:c0aa:afef:f2dc:f6dc",
    port: 7755.27,
    username: "Hershel.Prohaska",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1725863675445",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: null,
    metricsConfig: [
      "<value 1>",
      "<value 2>",
      "<value 3>",
    ],
  },
  backups: [],
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `mysqlId`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `name`                                                                                                 | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `appName`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `description`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databaseName`                                                                                         | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databaseUser`                                                                                         | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databasePassword`                                                                                     | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databaseRootPassword`                                                                                 | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `dockerImage`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `command`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `env`                                                                                                  | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryReservation`                                                                                    | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryLimit`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuReservation`                                                                                       | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuLimit`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `externalPort`                                                                                         | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `applicationStatus`                                                                                    | [operations.MysqlDeployApplicationStatus](../../models/operations/mysqldeployapplicationstatus.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `healthCheckSwarm`                                                                                     | [operations.MysqlDeployHealthCheckSwarm](../../models/operations/mysqldeployhealthcheckswarm.md)       | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `restartPolicySwarm`                                                                                   | [operations.MysqlDeployRestartPolicySwarm](../../models/operations/mysqldeployrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `placementSwarm`                                                                                       | [operations.MysqlDeployPlacementSwarm](../../models/operations/mysqldeployplacementswarm.md)           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `updateConfigSwarm`                                                                                    | [operations.MysqlDeployUpdateConfigSwarm](../../models/operations/mysqldeployupdateconfigswarm.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `rollbackConfigSwarm`                                                                                  | [operations.MysqlDeployRollbackConfigSwarm](../../models/operations/mysqldeployrollbackconfigswarm.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `modeSwarm`                                                                                            | [operations.MysqlDeployModeSwarm](../../models/operations/mysqldeploymodeswarm.md)                     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `labelsSwarm`                                                                                          | Record<string, *string*>                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `networkSwarm`                                                                                         | [operations.MysqlDeployNetworkSwarm](../../models/operations/mysqldeploynetworkswarm.md)[]             | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `replicas`                                                                                             | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `createdAt`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environmentId`                                                                                        | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `serverId`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environment`                                                                                          | [operations.MysqlDeployEnvironment](../../models/operations/mysqldeployenvironment.md)                 | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `mounts`                                                                                               | [operations.MysqlDeployMount](../../models/operations/mysqldeploymount.md)[]                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `server`                                                                                               | [operations.MysqlDeployServer](../../models/operations/mysqldeployserver.md)                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `backups`                                                                                              | [operations.MysqlDeployBackup](../../models/operations/mysqldeploybackup.md)[]                         | :heavy_check_mark:                                                                                     | N/A                                                                                                    |