# MariadbChangeStatusResponse


## Supported Types

### `operations.MariadbChangeStatusResponseBody`

```typescript
const value: operations.MariadbChangeStatusResponseBody = {
  appName: "<value>",
  applicationStatus: "error",
  backups: [
    {
      appName: "<value>",
      backupId: "<id>",
      backupType: "database",
      composeId: "<id>",
      database: "<value>",
      databaseType: "web-server",
      destinationId: "<id>",
      enabled: false,
      keepLatestCount: 8624.52,
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
  command: null,
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1707141354984",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  databaseUser: "<value>",
  description:
    "peony boo orientate vol straw whose chromakey crackle unpleasant up",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1726236661044",
    description:
      "what incidentally cleverly brr but nicely intrepid frantically",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1723810700183",
      description: "stunt unnaturally whole gratefully indeed yuck",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 7773.67,
  healthCheckSwarm: null,
  labelsSwarm: {},
  mariadbId: "<id>",
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: {},
  replicas: 7836.98,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 822.63,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1725295121679",
    description: "aha ick reservation convince moral slimy apud yogurt",
    enableDockerCleanup: false,
    ipAddress: "72.86.199.124",
    metricsConfig: false,
    name: "<value>",
    organizationId: "<id>",
    port: 6527.49,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Ellsworth_Reinger",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 7092.58,
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

