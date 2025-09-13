# MysqlChangeStatusResponse


## Supported Types

### `operations.MysqlChangeStatusResponseBody`

```typescript
const value: operations.MysqlChangeStatusResponseBody = {
  mysqlId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "impressive likewise upright hubris pish",
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
  externalPort: null,
  applicationStatus: "idle",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 9001.33,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 8863.81,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {},
  networkSwarm: null,
  replicas: 1406.5,
  createdAt: "1725057734996",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "emergent loaf immediately",
    createdAt: "1719638568650",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "but refine dampen violently casement for quarrel unlucky refine highly",
      createdAt: "1727451506644",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [
    {
      mountId: "<id>",
      type: "bind",
      hostPath: "<value>",
      volumeName: "<value>",
      filePath: null,
      content: "<value>",
      serviceType: "mariadb",
      mountPath: "<value>",
      applicationId: "<id>",
      postgresId: null,
      mariadbId: "<id>",
      mongoId: "<id>",
      mysqlId: "<id>",
      redisId: "<id>",
      composeId: "<id>",
    },
  ],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "psst noon sans wildly astride",
    ipAddress: "c18b:2e06:3605:b2ac:eb95:cb89:2dbe:20ad",
    port: 3999.4,
    username: "Oral_Jakubowski",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1723653149901",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: false,
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
      keepLatestCount: 9899.08,
      backupType: "compose",
      databaseType: "mariadb",
      composeId: null,
      postgresId: "<id>",
      mariadbId: "<id>",
      mysqlId: null,
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

