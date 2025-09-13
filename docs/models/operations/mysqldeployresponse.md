# MysqlDeployResponse


## Supported Types

### `operations.MysqlDeployResponseBody`

```typescript
const value: operations.MysqlDeployResponseBody = {
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

### `models.ErrorT`

```typescript
const value: models.ErrorT = {
  message: "<value>",
  code: "<value>",
};
```

