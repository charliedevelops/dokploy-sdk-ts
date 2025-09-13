# MysqlDeployResponse


## Supported Types

### `operations.MysqlDeployResponseBody`

```typescript
const value: operations.MysqlDeployResponseBody = {
  appName: "<value>",
  applicationStatus: "error",
  backups: [],
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1728031262041",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  databaseUser: "<value>",
  description: null,
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1733715839242",
    description: "whoa since dissemble",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1716006885913",
      description: "rebuke who suddenly standard as gentle dusk",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 3405.58,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [
    {
      applicationId: null,
      composeId: "<id>",
      content: "<value>",
      filePath: null,
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: null,
      serviceType: "application",
      type: "bind",
      volumeName: "<value>",
    },
  ],
  mysqlId: "<id>",
  name: "<value>",
  networkSwarm: [
    {},
  ],
  placementSwarm: {},
  replicas: 819.87,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 1623.23,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1712204982423",
    description: "futon barring deplore scope via",
    enableDockerCleanup: false,
    ipAddress: "180.77.194.213",
    metricsConfig: {
      "key": "<value>",
      "key1": "<value>",
    },
    name: "<value>",
    organizationId: "<id>",
    port: 1582.79,
    serverId: "<id>",
    serverStatus: "active",
    sshKeyId: "<id>",
    username: "Trey.Luettgen-Gulgowski59",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 1251.35,
  },
};
```

### `models.ErrorT`

```typescript
const value: models.ErrorT = {
  code: "<value>",
  message: "<value>",
};
```

