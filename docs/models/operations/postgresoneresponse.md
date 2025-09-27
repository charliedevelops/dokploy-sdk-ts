# PostgresOneResponse


## Supported Types

### `operations.PostgresOneResponseBody`

```typescript
const value: operations.PostgresOneResponseBody = {
  appName: "<value>",
  applicationStatus: "idle",
  backups: [
    {
      appName: "<value>",
      backupId: "<id>",
      backupType: "compose",
      composeId: null,
      database: "<value>",
      databaseType: "mysql",
      destinationId: "<id>",
      enabled: false,
      keepLatestCount: 4781.95,
      mariadbId: "<id>",
      mongoId: "<id>",
      mysqlId: "<id>",
      postgresId: "<id>",
      prefix: "<value>",
      schedule: "<value>",
      serviceName: "<value>",
      userId: "<id>",
    },
  ],
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1733806182342",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: "knitting along co-producer atop possible boohoo pomelo",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1721666022691",
    description: "instead burly nor knavishly upbeat elver",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1705027263361",
      description: "softly for than who aw",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 8384.93,
  healthCheckSwarm: {},
  labelsSwarm: {},
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: null,
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: "/bin/sure_footed_soft_archaeology.m2a",
      hostPath: null,
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: "<id>",
      serviceType: "application",
      type: "bind",
      volumeName: null,
    },
  ],
  name: "<value>",
  networkSwarm: [
    {},
  ],
  placementSwarm: {},
  postgresId: "<id>",
  replicas: 375.64,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 7805.99,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1731901264634",
    description: "stratify yowza eek urgently impact gee crushing ick",
    enableDockerCleanup: false,
    ipAddress: "195.108.223.13",
    metricsConfig: [
      "<value 1>",
      "<value 2>",
    ],
    name: "<value>",
    organizationId: "<id>",
    port: 8305.37,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Earnestine_Larkin",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 9205.54,
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

