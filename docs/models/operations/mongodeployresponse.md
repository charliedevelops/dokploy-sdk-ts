# MongoDeployResponse


## Supported Types

### `operations.MongoDeployResponseBody`

```typescript
const value: operations.MongoDeployResponseBody = {
  mongoId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: null,
  databaseUser: "<value>",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: null,
  externalPort: 9501.22,
  applicationStatus: "idle",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 6332.49,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 6755.66,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
  },
  networkSwarm: [
    {},
  ],
  replicas: 2752.87,
  createdAt: "1729052788267",
  environmentId: "<id>",
  serverId: "<id>",
  replicaSets: false,
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description:
      "militate unique hope ravioli geez energetically innocently foolhardy whoever what",
    createdAt: "1705896617342",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "by whereas queasily redress ick almighty blissfully",
      createdAt: "1727445144010",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "kindly soulful shout ouch sleepily",
    ipAddress: "ecaa:e2f5:7faf:213d:1ddf:8388:4db0:b215",
    port: 3147.02,
    username: "Christopher.Wiegand",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1722223115991",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: null,
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
      keepLatestCount: 6304.17,
      backupType: "compose",
      databaseType: "mongo",
      composeId: "<id>",
      postgresId: "<id>",
      mariadbId: "<id>",
      mysqlId: null,
      mongoId: "<id>",
      userId: "<id>",
    },
  ],
};
```

### `models.ErrorT`

```typescript
const value: models.ErrorT = {
  message: "<value>",
  code: "<value>",
};
```

