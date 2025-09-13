# RedisChangeStatusResponse


## Supported Types

### `operations.RedisChangeStatusResponseBody`

```typescript
const value: operations.RedisChangeStatusResponseBody = {
  redisId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "blah dimly about",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 6782.01,
  createdAt: "1735298939676",
  applicationStatus: "idle",
  healthCheckSwarm: {},
  restartPolicySwarm: null,
  placementSwarm: {},
  updateConfigSwarm: null,
  rollbackConfigSwarm: {
    parallelism: 2498.44,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  networkSwarm: [],
  replicas: 4886.37,
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "inwardly yahoo exploration anti likewise suckle",
    createdAt: "1706813093953",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "suspiciously whoever publicity",
      createdAt: "1722511417122",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description:
      "toward naturally about accidentally fall selfishly cantaloupe treble",
    ipAddress: "2c7d:9e55:eef9:fde8:2fcc:3dd2:f284:e48d",
    port: 4328.61,
    username: "Isai_Reinger",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1711252328552",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: "<value>",
  },
};
```

### `models.ErrorT`

```typescript
const value: models.ErrorT = {
  message: "<value>",
  code: "<value>",
};
```

