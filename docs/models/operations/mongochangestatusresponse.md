# MongoChangeStatusResponse


## Supported Types

### `operations.MongoChangeStatusResponseBody`

```typescript
const value: operations.MongoChangeStatusResponseBody = {
  mongoId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "times section case overstay",
  databaseUser: "<value>",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: null,
  externalPort: 5166.96,
  applicationStatus: "done",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 5650.49,
    order: "<value>",
  },
  rollbackConfigSwarm: null,
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  networkSwarm: null,
  replicas: 8402.87,
  createdAt: "1708104569587",
  environmentId: "<id>",
  serverId: "<id>",
  replicaSets: true,
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "ring aha as openly to dispose shinny",
    createdAt: "1711226127339",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "furthermore drat hmph boulevard shear loudly relieve unlike",
      createdAt: "1721693165698",
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
      filePath: "/usr/sbin/far_off.so",
      content: null,
      serviceType: "application",
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
    description: "at consequently before regarding bran rebel",
    ipAddress: "200.119.145.223",
    port: 5704.33,
    username: "Jaime_Mohr",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1727917310222",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: "<value>",
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
      keepLatestCount: 9227.88,
      backupType: "database",
      databaseType: "mariadb",
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

