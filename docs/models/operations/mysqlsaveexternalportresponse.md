# MysqlSaveExternalPortResponse


## Supported Types

### `operations.MysqlSaveExternalPortResponseBody`

```typescript
const value: operations.MysqlSaveExternalPortResponseBody = {
  appName: "<value>",
  applicationStatus: "done",
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
      keepLatestCount: null,
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
  cpuReservation: null,
  createdAt: "1708541755324",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  databaseUser: "<value>",
  description: "whup next qua bowler afore meanwhile around",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1728684138006",
    description: "vaguely yum transom sport",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1721630569302",
      description: null,
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 9280.08,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [],
  mysqlId: "<id>",
  name: "<value>",
  networkSwarm: [],
  placementSwarm: {},
  replicas: 3343.41,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 880.51,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1713768035995",
    description: null,
    enableDockerCleanup: false,
    ipAddress: "2da9:a7be:fafc:8c8a:ad3e:9dbc:9a0d:ec29",
    metricsConfig: {},
    name: "<value>",
    organizationId: "<id>",
    port: 5989.83,
    serverId: "<id>",
    serverStatus: "active",
    sshKeyId: "<id>",
    username: "Elsa.Dibbert",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 1377,
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

