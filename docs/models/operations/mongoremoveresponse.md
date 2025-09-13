# MongoRemoveResponse


## Supported Types

### `operations.MongoRemoveResponseBody`

```typescript
const value: operations.MongoRemoveResponseBody = {
  appName: "<value>",
  applicationStatus: "error",
  backups: [
    {
      appName: "<value>",
      backupId: "<id>",
      backupType: "compose",
      composeId: "<id>",
      database: "<value>",
      databaseType: "web-server",
      destinationId: "<id>",
      enabled: null,
      keepLatestCount: 3008.02,
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
  createdAt: "1720263241079",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: "tragic fooey phooey impressionable condense nudge",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1731845761406",
    description: "thyme inexperienced vainly service um phew",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1720183877882",
      description:
        "supposing from where release tabulate drat bob pish uselessly once",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 7742.91,
  healthCheckSwarm: {},
  labelsSwarm: {},
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mongoId: "<id>",
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: "/boot/defaults/birdbath_range_but.rar",
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: null,
      serviceType: "compose",
      type: "bind",
      volumeName: "<value>",
    },
  ],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: {},
  replicaSets: false,
  replicas: 5271.16,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 3035.55,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1730665355632",
    description: "deliberately oh meh gadzooks",
    enableDockerCleanup: false,
    ipAddress: "253.143.127.44",
    metricsConfig: 3094,
    name: "<value>",
    organizationId: "<id>",
    port: 5305.36,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Kristoffer_Larkin66",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 4544.66,
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

