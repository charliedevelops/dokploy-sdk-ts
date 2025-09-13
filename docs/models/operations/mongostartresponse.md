# MongoStartResponse


## Supported Types

### `operations.MongoStartResponseBody`

```typescript
const value: operations.MongoStartResponseBody = {
  mongoId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "hmph surprisingly gosh powerfully",
  databaseUser: "<value>",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: null,
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 4280.58,
  applicationStatus: "running",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 5510.17,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 7044.77,
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
  replicas: 9188.7,
  createdAt: "1718251560372",
  environmentId: "<id>",
  serverId: "<id>",
  replicaSets: true,
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: null,
    createdAt: "1715955722785",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "whereas whirlwind vainly which turret probe whoever near hello",
      createdAt: "1706362761378",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [
    {
      mountId: "<id>",
      type: "file",
      hostPath: "<value>",
      volumeName: "<value>",
      filePath: "/tmp/wildly_jaggedly.doc",
      content: "<value>",
      serviceType: "compose",
      mountPath: "<value>",
      applicationId: "<id>",
      postgresId: "<id>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mysqlId: "<id>",
      redisId: null,
      composeId: "<id>",
    },
  ],
  server: null,
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

