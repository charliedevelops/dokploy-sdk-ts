# PostgresRemoveResponse


## Supported Types

### `operations.PostgresRemoveResponseBody`

```typescript
const value: operations.PostgresRemoveResponseBody = {
  appName: "<value>",
  applicationStatus: "running",
  backups: [
    {
      appName: "<value>",
      backupId: "<id>",
      backupType: "database",
      composeId: "<id>",
      database: "<value>",
      databaseType: "postgres",
      destinationId: "<id>",
      enabled: true,
      keepLatestCount: 1789.86,
      mariadbId: "<id>",
      mongoId: "<id>",
      mysqlId: "<id>",
      postgresId: "<id>",
      prefix: "<value>",
      schedule: "<value>",
      serviceName: null,
      userId: "<id>",
    },
  ],
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1734404093273",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: null,
  dockerImage: "<value>",
  env: null,
  environment: {
    createdAt: "1719202281066",
    description: null,
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1722918008081",
      description: "sanity beyond slink purse euphonium",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 7688.54,
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
      redisId: "<id>",
      serviceType: "mariadb",
      type: "file",
      volumeName: "<value>",
    },
  ],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: {},
  postgresId: "<id>",
  replicas: 4756.12,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 2467,
  },
  server: null,
  serverId: null,
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 6449.82,
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

