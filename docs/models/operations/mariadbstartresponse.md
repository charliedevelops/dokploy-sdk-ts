# MariadbStartResponse


## Supported Types

### `operations.MariadbStartResponseBody`

```typescript
const value: operations.MariadbStartResponseBody = {
  appName: "<value>",
  applicationStatus: "error",
  backups: [],
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1720536947069",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  databaseUser: "<value>",
  description: "woefully despite strategy ah duh stealthily for",
  dockerImage: "<value>",
  env: null,
  environment: {
    createdAt: "1728590061063",
    description: "wherever astride vivid sensitize concerning",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1723904933546",
      description: "punctually gosh perfectly likewise pupil",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 9579.93,
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
  mounts: [
    {
      applicationId: "<id>",
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
      redisId: "<id>",
      serviceType: "application",
      type: "bind",
      volumeName: "<value>",
    },
  ],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: {},
  replicas: 5957.01,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 9463.63,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1729727548045",
    description: "famously square before opposite less innovate",
    enableDockerCleanup: true,
    ipAddress: "2c80:acfe:dccf:f58a:ccf0:0f36:c1dc:b34b",
    metricsConfig: [
      "<value 1>",
    ],
    name: "<value>",
    organizationId: "<id>",
    port: 4777.32,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Darrick61",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 5118.23,
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

