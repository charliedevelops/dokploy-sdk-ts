# PostgresChangeStatusResponse


## Supported Types

### `operations.PostgresChangeStatusResponseBody`

```typescript
const value: operations.PostgresChangeStatusResponseBody = {
  appName: "<value>",
  applicationStatus: "done",
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
      keepLatestCount: 8061.76,
      mariadbId: "<id>",
      mongoId: null,
      mysqlId: "<id>",
      postgresId: "<id>",
      prefix: "<value>",
      schedule: "<value>",
      serviceName: "<value>",
      userId: "<id>",
    },
  ],
  command: null,
  cpuLimit: null,
  cpuReservation: "<value>",
  createdAt: "1720974373942",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: "seriously reschedule whereas",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1710471816361",
    description: "like puritan victoriously decide grubby bah but",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1725186984913",
      description: "gosh hexagon giggle carefully spear abaft meander",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 6192.25,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: null,
  postgresId: "<id>",
  replicas: 8082.57,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 2528.32,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1726949439085",
    description:
      "lest digit to rapidly smart sympathetically in progress hutch",
    enableDockerCleanup: false,
    ipAddress: "38.3.184.244",
    metricsConfig: "null",
    name: "<value>",
    organizationId: "<id>",
    port: 2782.73,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Luciano_Schumm",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 8370.89,
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

