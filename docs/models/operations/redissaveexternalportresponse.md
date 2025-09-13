# RedisSaveExternalPortResponse


## Supported Types

### `operations.RedisSaveExternalPortResponseBody`

```typescript
const value: operations.RedisSaveExternalPortResponseBody = {
  appName: "<value>",
  applicationStatus: "idle",
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1715232661148",
  databasePassword: "<value>",
  description: null,
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1709861484506",
    description: "whose instead pendant hastily",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1708174808079",
      description: "agreeable scare violently why spew zowie than",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 3521.19,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: "/proc/till.xlsx",
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: "<id>",
      serviceType: "mariadb",
      type: "bind",
      volumeName: "<value>",
    },
  ],
  name: "<value>",
  networkSwarm: [
    {},
  ],
  placementSwarm: {},
  redisId: "<id>",
  replicas: 7162.01,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 8916.82,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1713211255890",
    description:
      "spirited boyfriend avaricious nor skateboard depend hmph above",
    enableDockerCleanup: true,
    ipAddress: "ba02:4aed:ff9b:242c:5519:5696:cc0d:331f",
    metricsConfig: "<value>",
    name: "<value>",
    organizationId: "<id>",
    port: 8316.2,
    serverId: "<id>",
    serverStatus: "active",
    sshKeyId: "<id>",
    username: "Melany.Dibbert",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 4544.09,
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

