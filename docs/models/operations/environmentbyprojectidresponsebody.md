# EnvironmentByProjectIdResponseBody

## Example Usage

```typescript
import { EnvironmentByProjectIdResponseBody } from "dokploy-sdk/models/operations";

let value: EnvironmentByProjectIdResponseBody = {
  environmentId: "<id>",
  name: "<value>",
  description: "abaft yahoo postbox mask",
  createdAt: "1724120254645",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: null,
    createdAt: "1706596586723",
    organizationId: "<id>",
    env: "<value>",
  },
  applications: [],
  mariadb: [],
  mongo: [
    {
      mongoId: "<id>",
      name: "<value>",
      appName: "<value>",
      description:
        "indeed of overconfidently heartbeat ultimately unaccountably oof",
      databaseUser: "<value>",
      databasePassword: "<value>",
      dockerImage: "<value>",
      command: "<value>",
      env: "<value>",
      memoryReservation: "<value>",
      memoryLimit: "<value>",
      cpuReservation: "<value>",
      cpuLimit: "<value>",
      externalPort: 4847.77,
      applicationStatus: "error",
      healthCheckSwarm: [],
      restartPolicySwarm: "<value>",
      placementSwarm: true,
      updateConfigSwarm: "null",
      rollbackConfigSwarm: {
        "key": "<value>",
      },
      modeSwarm: "null",
      labelsSwarm: [],
      networkSwarm: [],
      replicas: 6448.72,
      createdAt: "1705269329790",
      environmentId: "<id>",
      serverId: "<id>",
      replicaSets: true,
    },
  ],
  mysql: [],
  postgres: [
    {
      postgresId: "<id>",
      name: "<value>",
      appName: "<value>",
      databaseName: "<value>",
      databaseUser: "<value>",
      databasePassword: "<value>",
      description: "inasmuch bind fill well back inasmuch whose",
      dockerImage: "<value>",
      command: "<value>",
      env: "<value>",
      memoryReservation: "<value>",
      externalPort: 3912.61,
      memoryLimit: "<value>",
      cpuReservation: "<value>",
      cpuLimit: "<value>",
      applicationStatus: "error",
      healthCheckSwarm: true,
      restartPolicySwarm: null,
      placementSwarm: null,
      updateConfigSwarm: 1537.72,
      rollbackConfigSwarm: [
        "<value 1>",
        "<value 2>",
        "<value 3>",
      ],
      modeSwarm: {
        "key": "<value>",
        "key1": "<value>",
        "key2": "<value>",
      },
      labelsSwarm: {},
      networkSwarm: "<value>",
      replicas: 9925.46,
      createdAt: "1733957273335",
      environmentId: "<id>",
      serverId: "<id>",
    },
  ],
  redis: [
    {
      redisId: "<id>",
      name: "<value>",
      appName: "<value>",
      description: "restaurant determined gah",
      databasePassword: "<value>",
      dockerImage: "<value>",
      command: "<value>",
      env: "<value>",
      memoryReservation: "<value>",
      memoryLimit: "<value>",
      cpuReservation: "<value>",
      cpuLimit: "<value>",
      externalPort: 230.57,
      createdAt: "1723787027031",
      applicationStatus: "running",
      healthCheckSwarm: [
        "<value 1>",
        "<value 2>",
        "<value 3>",
      ],
      restartPolicySwarm: 850.31,
      placementSwarm: [
        "<value 1>",
        "<value 2>",
        "<value 3>",
      ],
      updateConfigSwarm: "<value>",
      rollbackConfigSwarm: {
        "key": "<value>",
        "key1": "<value>",
        "key2": "<value>",
      },
      modeSwarm: 7757.1,
      labelsSwarm: {
        "key": "<value>",
      },
      networkSwarm: {
        "key": "<value>",
        "key1": "<value>",
      },
      replicas: 7204.78,
      environmentId: "<id>",
      serverId: "<id>",
    },
  ],
  compose: [
    {
      composeId: "<id>",
      name: "<value>",
      appName: "<value>",
      description: "consequently past hence oddly",
      env: "<value>",
      composeFile: "<value>",
      refreshToken: null,
      sourceType: "gitlab",
      composeType: "docker-compose",
      repository: "<value>",
      owner: "<value>",
      branch: "<value>",
      autoDeploy: false,
      gitlabProjectId: null,
      gitlabRepository: "<value>",
      gitlabOwner: "<value>",
      gitlabBranch: "<value>",
      gitlabPathNamespace: "<value>",
      bitbucketRepository: "<value>",
      bitbucketOwner: "<value>",
      bitbucketBranch: "<value>",
      giteaRepository: "<value>",
      giteaOwner: null,
      giteaBranch: "<value>",
      customGitUrl: "https://wide-pneumonia.info/",
      customGitBranch: "<value>",
      customGitSSHKeyId: "<id>",
      command: "<value>",
      enableSubmodules: false,
      composePath: "<value>",
      suffix: "<value>",
      randomize: true,
      isolatedDeployment: true,
      isolatedDeploymentsVolume: true,
      triggerType: null,
      composeStatus: "error",
      environmentId: "<id>",
      createdAt: "1717457453884",
      watchPaths: [
        "<value 1>",
      ],
      githubId: "<id>",
      gitlabId: "<id>",
      bitbucketId: "<id>",
      giteaId: null,
      serverId: null,
    },
  ],
};
```

## Fields

| Field                                                                                                          | Type                                                                                                           | Required                                                                                                       | Description                                                                                                    |
| -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| `environmentId`                                                                                                | *string*                                                                                                       | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `name`                                                                                                         | *string*                                                                                                       | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `description`                                                                                                  | *string*                                                                                                       | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `createdAt`                                                                                                    | *string*                                                                                                       | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `env`                                                                                                          | *string*                                                                                                       | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `projectId`                                                                                                    | *string*                                                                                                       | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `project`                                                                                                      | [operations.EnvironmentByProjectIdProject](../../models/operations/environmentbyprojectidproject.md)           | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `applications`                                                                                                 | [operations.EnvironmentByProjectIdApplication](../../models/operations/environmentbyprojectidapplication.md)[] | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `mariadb`                                                                                                      | [operations.EnvironmentByProjectIdMariadb](../../models/operations/environmentbyprojectidmariadb.md)[]         | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `mongo`                                                                                                        | [operations.EnvironmentByProjectIdMongo](../../models/operations/environmentbyprojectidmongo.md)[]             | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `mysql`                                                                                                        | [operations.EnvironmentByProjectIdMysql](../../models/operations/environmentbyprojectidmysql.md)[]             | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `postgres`                                                                                                     | [operations.EnvironmentByProjectIdPostgre](../../models/operations/environmentbyprojectidpostgre.md)[]         | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `redis`                                                                                                        | [operations.EnvironmentByProjectIdRedi](../../models/operations/environmentbyprojectidredi.md)[]               | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `compose`                                                                                                      | [operations.EnvironmentByProjectIdCompose](../../models/operations/environmentbyprojectidcompose.md)[]         | :heavy_check_mark:                                                                                             | N/A                                                                                                            |