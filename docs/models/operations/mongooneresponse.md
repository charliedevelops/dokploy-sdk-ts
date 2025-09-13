# MongoOneResponse


## Supported Types

### `operations.MongoOneResponseBody`

```typescript
const value: operations.MongoOneResponseBody = {
  appName: "<value>",
  applicationStatus: "running",
  backups: [
    {
      appName: "<value>",
      backupId: "<id>",
      backupType: "compose",
      composeId: "<id>",
      database: "<value>",
      databaseType: "mariadb",
      destinationId: "<id>",
      enabled: true,
      keepLatestCount: 658.14,
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
  createdAt: "1718038727529",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: null,
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1725889942277",
    description: "intermix little ew",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1715567682812",
      description: "sticker uh-huh drag habit",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 5791.43,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mongoId: "<id>",
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: "/usr/local/src/ugh_minus.pkg",
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: "<id>",
      serviceType: "application",
      type: "file",
      volumeName: "<value>",
    },
  ],
  name: "<value>",
  networkSwarm: null,
  placementSwarm: {},
  replicaSets: true,
  replicas: 6169.68,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 8770.1,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1723566649209",
    description: "or ha jealous lucky what after gee yippee silver quadruple",
    enableDockerCleanup: true,
    ipAddress: "66.240.170.253",
    metricsConfig: {},
    name: "<value>",
    organizationId: "<id>",
    port: 6210.51,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Harley35",
  },
  serverId: null,
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 9809.39,
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

