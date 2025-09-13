# PostgresStartResponse


## Supported Types

### `operations.PostgresStartResponseBody`

```typescript
const value: operations.PostgresStartResponseBody = {
  appName: "<value>",
  applicationStatus: "error",
  backups: [
    {
      appName: "<value>",
      backupId: "<id>",
      backupType: "database",
      composeId: "<id>",
      database: "<value>",
      databaseType: "mariadb",
      destinationId: "<id>",
      enabled: true,
      keepLatestCount: 5110.29,
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
  createdAt: "1729019901897",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description:
    "foolishly during tightly ick supposing gadzooks book atop cram nearly",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1721275044880",
    description: "yowza but rotten phooey towards hunger strictly",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1713960768591",
      description: "worth showboat soliloquy proselytise",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 9773.94,
  healthCheckSwarm: {},
  labelsSwarm: null,
  memoryLimit: null,
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [
    {
      applicationId: null,
      composeId: null,
      content: "<value>",
      filePath: "/mnt/outside_incomparable.eot",
      hostPath: null,
      mariadbId: "<id>",
      mongoId: null,
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: null,
      serviceType: "redis",
      type: "volume",
      volumeName: "<value>",
    },
  ],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: {},
  postgresId: "<id>",
  replicas: 6774.66,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 2729.81,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1732386809506",
    description: "till ferret cleave although after um atomize supposing",
    enableDockerCleanup: true,
    ipAddress: "3b9b:daa0:a620:1fcf:dfa1:6ce5:9efa:dc4c",
    metricsConfig: [
      "<value 1>",
      "<value 2>",
    ],
    name: "<value>",
    organizationId: "<id>",
    port: 736.55,
    serverId: "<id>",
    serverStatus: "active",
    sshKeyId: "<id>",
    username: "Jarrell.Osinski",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 342.67,
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

