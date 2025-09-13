# MariadbChangeStatusResponse


## Supported Types

### `operations.MariadbChangeStatusResponseBody`

```typescript
const value: operations.MariadbChangeStatusResponseBody = {
  mariadbId: "<id>",
  name: "<value>",
  appName: "<value>",
  description:
    "tough agitated parody typify nor for except petticoat delightfully duh",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: null,
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 8913.22,
  applicationStatus: "running",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 8083.44,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 1437.34,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  networkSwarm: [
    {},
  ],
  replicas: 8309.19,
  createdAt: "1725775864468",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "polished platter pish prance",
    createdAt: "1725269878288",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "councilman language frightfully pish aha perfectly fearless whether",
      createdAt: "1719623363118",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [
    {
      mountId: "<id>",
      type: "volume",
      hostPath: "<value>",
      volumeName: "<value>",
      filePath: "/var/mail/save.m3a",
      content: "<value>",
      serviceType: "mariadb",
      mountPath: "<value>",
      applicationId: "<id>",
      postgresId: "<id>",
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
    description: "powerfully stratify inculcate",
    ipAddress: "46.103.73.34",
    port: 233.23,
    username: "Hayden.Denesik-Welch",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1719862083759",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: true,
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
      keepLatestCount: 3921.61,
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

