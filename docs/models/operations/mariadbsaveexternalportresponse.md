# MariadbSaveExternalPortResponse


## Supported Types

### `operations.MariadbSaveExternalPortResponseBody`

```typescript
const value: operations.MariadbSaveExternalPortResponseBody = {
  mariadbId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "brr immediately stump hmph",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 5549.03,
  applicationStatus: "done",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 201.89,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 2378.06,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  networkSwarm: [],
  replicas: 8769.89,
  createdAt: "1724799748148",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "grandson until playfully gentle reschedule annually",
    createdAt: "1704180096982",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "assail although er",
      createdAt: "1723720328670",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "geez whine sneaky gee but till excluding reproachfully",
    ipAddress: "df4b:4b23:02da:6d87:3b66:a56f:e92b:adea",
    port: 9320.4,
    username: "Lia73",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1718959776780",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
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
      keepLatestCount: 9882.1,
      backupType: "database",
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

