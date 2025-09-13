# MongoDeployResponse


## Supported Types

### `operations.MongoDeployResponseBody`

```typescript
const value: operations.MongoDeployResponseBody = {
  appName: "<value>",
  applicationStatus: "idle",
  backups: [
    {
      appName: "<value>",
      backupId: "<id>",
      backupType: "database",
      composeId: "<id>",
      database: "<value>",
      databaseType: "mongo",
      destinationId: "<id>",
      enabled: true,
      keepLatestCount: 9501.22,
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
  createdAt: "1710352257027",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: "midwife whoever terraform trick resource cluttered",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1724787539235",
    description: "advocate ick ack concerning",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1718805513776",
      description: "zowie gracefully nightlife by whereas queasily",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: null,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  memoryLimit: null,
  memoryReservation: "<value>",
  modeSwarm: {},
  mongoId: "<id>",
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: null,
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: null,
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: "<id>",
      serviceType: "mariadb",
      type: "file",
      volumeName: "<value>",
    },
  ],
  name: "<value>",
  networkSwarm: [
    {},
  ],
  placementSwarm: {},
  replicaSets: null,
  replicas: 2374.3,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 4478.82,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1714328443045",
    description: "accurate mid heavily usually aha butter",
    enableDockerCleanup: true,
    ipAddress: "80.47.206.243",
    metricsConfig: "null",
    name: "<value>",
    organizationId: "<id>",
    port: 3587.65,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Naomie.Mayert77",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 9215,
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

