# MysqlOneResponse


## Supported Types

### `operations.MysqlOneResponseBody`

```typescript
const value: operations.MysqlOneResponseBody = {
  mysqlId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: null,
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  dockerImage: "<value>",
  command: null,
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 3224.27,
  applicationStatus: "done",
  healthCheckSwarm: null,
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: null,
  rollbackConfigSwarm: {
    parallelism: 6573.9,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
  },
  networkSwarm: null,
  replicas: 9938.77,
  createdAt: "1712559561299",
  environmentId: "<id>",
  serverId: null,
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "oof valiantly mmm tired never truly tuxedo",
    createdAt: "1729355553936",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "hourly how lecture quixotic hole drive as scale what but",
      createdAt: "1732002276444",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: null,
    ipAddress: "156.130.205.219",
    port: 5651.27,
    username: "Genevieve_Jakubowski43",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1706323874487",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: true,
  },
  backups: [],
};
```

### `models.ErrorT`

```typescript
const value: models.ErrorT = {
  message: "<value>",
  code: "<value>",
};
```

