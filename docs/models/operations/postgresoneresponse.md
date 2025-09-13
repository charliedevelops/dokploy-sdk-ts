# PostgresOneResponse


## Supported Types

### `operations.PostgresOneResponseBody`

```typescript
const value: operations.PostgresOneResponseBody = {
  postgresId: "<id>",
  name: "<value>",
  appName: "<value>",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  description:
    "liberalize neat if settle as misappropriate round young iridescence",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  externalPort: 6900.12,
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  applicationStatus: "running",
  healthCheckSwarm: null,
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 6267.78,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 3788.88,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  networkSwarm: [],
  replicas: 5973.1,
  createdAt: "1707162415224",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "after drat supposing hence management",
    createdAt: "1731917924351",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "fully yearly fooey usefully oh phew above",
      createdAt: "1729177506214",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [
    {
      mountId: "<id>",
      type: "volume",
      hostPath: null,
      volumeName: "<value>",
      filePath: "/opt/sbin/playfully_haircut_how.png",
      content: "<value>",
      serviceType: "postgres",
      mountPath: "<value>",
      applicationId: "<id>",
      postgresId: null,
      mariadbId: "<id>",
      mongoId: null,
      mysqlId: "<id>",
      redisId: "<id>",
      composeId: "<id>",
    },
  ],
  server: null,
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
      keepLatestCount: 2579.45,
      backupType: "compose",
      databaseType: "mysql",
      composeId: "<id>",
      postgresId: "<id>",
      mariadbId: "<id>",
      mysqlId: "<id>",
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

