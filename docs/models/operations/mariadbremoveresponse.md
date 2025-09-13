# MariadbRemoveResponse


## Supported Types

### `operations.MariadbRemoveResponseBody`

```typescript
const value: operations.MariadbRemoveResponseBody = {
  appName: "<value>",
  applicationStatus: "error",
  backups: [
    {
      appName: "<value>",
      backupId: "<id>",
      backupType: "compose",
      composeId: "<id>",
      database: "<value>",
      databaseType: "mysql",
      destinationId: "<id>",
      enabled: false,
      keepLatestCount: 5485.5,
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
  createdAt: "1713153825006",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  databaseUser: "<value>",
  description:
    "magnificent deploy goodwill foodstuffs shakily certainly as fatally split showy",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1707769703708",
    description:
      "boo decide blank tightly abaft supposing smooth completion underneath till",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1728866695967",
      description: "sheathe lovingly freely",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 4214.67,
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
  mounts: [],
  name: "<value>",
  networkSwarm: [
    {},
  ],
  placementSwarm: {},
  replicas: 6249.32,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 7647.64,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1727218210474",
    description: null,
    enableDockerCleanup: true,
    ipAddress: "3cfc:bb15:9736:6eae:6b5f:baed:2dfe:7ab7",
    metricsConfig: {
      "key": "<value>",
    },
    name: "<value>",
    organizationId: "<id>",
    port: 2997.69,
    serverId: "<id>",
    serverStatus: "active",
    sshKeyId: "<id>",
    username: "Arlie.Parker1",
  },
  serverId: null,
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 6803.16,
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

