# PostgresStartResponse


## Supported Types

### `operations.PostgresStartResponseBody`

```typescript
const value: operations.PostgresStartResponseBody = {
  postgresId: "<id>",
  name: "<value>",
  appName: "<value>",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  description:
    "including incandescence all ouch hypothesise meh respectful who fisherman coal",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  externalPort: 2539.32,
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  applicationStatus: "running",
  healthCheckSwarm: null,
  restartPolicySwarm: null,
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 9272,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 1702.89,
    order: "<value>",
  },
  modeSwarm: null,
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  networkSwarm: [
    {},
  ],
  replicas: 2002.17,
  createdAt: "1722144452683",
  environmentId: "<id>",
  serverId: null,
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "publicize expert humiliating",
    createdAt: "1719805395931",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "general unless striking unless ick",
      createdAt: "1707999818079",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: null,
    ipAddress: "197.88.211.12",
    port: 3622.44,
    username: "Sanford86",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1718029108548",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: {
      "key": "<value>",
      "key1": "<value>",
    },
  },
  backups: [
    {
      backupId: "<id>",
      appName: "<value>",
      schedule: "<value>",
      enabled: null,
      database: "<value>",
      prefix: "<value>",
      serviceName: "<value>",
      destinationId: "<id>",
      keepLatestCount: 9773.94,
      backupType: "database",
      databaseType: "postgres",
      composeId: null,
      postgresId: "<id>",
      mariadbId: "<id>",
      mysqlId: "<id>",
      mongoId: null,
      userId: null,
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

