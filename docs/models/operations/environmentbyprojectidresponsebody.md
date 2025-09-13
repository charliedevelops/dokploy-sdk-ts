# EnvironmentByProjectIdResponseBody

## Example Usage

```typescript
import { EnvironmentByProjectIdResponseBody } from "dokploy-sdk/models/operations";

let value: EnvironmentByProjectIdResponseBody = {
  applications: [
    {
      appName: "<value>",
      applicationId: "<id>",
      applicationStatus: "idle",
      autoDeploy: true,
      bitbucketBranch: "<value>",
      bitbucketBuildPath: "<value>",
      bitbucketId: "<id>",
      bitbucketOwner: "<value>",
      bitbucketRepository: null,
      branch: "<value>",
      buildArgs: null,
      buildPath: "<value>",
      buildType: "paketo_buildpacks",
      cleanCache: true,
      command: "<value>",
      cpuLimit: "<value>",
      cpuReservation: "<value>",
      createdAt: "1706794563182",
      customGitBranch: "<value>",
      customGitBuildPath: "<value>",
      customGitSSHKeyId: "<id>",
      customGitUrl: "https://outstanding-bandwidth.info",
      description: "truly quietly phew what",
      dockerBuildStage: "<value>",
      dockerContextPath: "<value>",
      dockerImage: "<value>",
      dockerfile: "<value>",
      dropBuildPath: "<value>",
      enableSubmodules: true,
      enabled: true,
      env: "<value>",
      environmentId: "<id>",
      giteaBranch: "<value>",
      giteaBuildPath: "<value>",
      giteaId: "<id>",
      giteaOwner: "<value>",
      giteaRepository: null,
      githubId: "<id>",
      gitlabBranch: "<value>",
      gitlabBuildPath: null,
      gitlabId: null,
      gitlabOwner: "<value>",
      gitlabPathNamespace: "<value>",
      gitlabProjectId: 3196.85,
      gitlabRepository: "<value>",
      healthCheckSwarm: null,
      herokuVersion: "<value>",
      isPreviewDeploymentsActive: true,
      isStaticSpa: false,
      labelsSwarm: [
        "<value 1>",
        "<value 2>",
        "<value 3>",
      ],
      memoryLimit: "<value>",
      memoryReservation: "<value>",
      modeSwarm: {},
      name: "<value>",
      networkSwarm: {
        "key": "<value>",
        "key1": "<value>",
        "key2": "<value>",
      },
      owner: "<value>",
      password: "2MgwuIqRGE41Jxl",
      placementSwarm: {
        "key": "<value>",
        "key1": "<value>",
      },
      previewBuildArgs: "<value>",
      previewCertificateType: "letsencrypt",
      previewCustomCertResolver: null,
      previewEnv: "<value>",
      previewHttps: true,
      previewLabels: [
        "<value 1>",
        "<value 2>",
      ],
      previewLimit: 6824.23,
      previewPath: "<value>",
      previewPort: 677.58,
      previewRequireCollaboratorPermissions: false,
      previewWildcard: "<value>",
      publishDirectory: "<value>",
      railpackVersion: "<value>",
      refreshToken: "<value>",
      registryId: "<id>",
      registryUrl: "https://brilliant-bell.biz",
      replicas: 507.36,
      repository: "<value>",
      restartPolicySwarm: [
        "<value 1>",
        "<value 2>",
      ],
      rollbackActive: false,
      rollbackConfigSwarm: false,
      serverId: "<id>",
      sourceType: "docker",
      subtitle: null,
      title: "<value>",
      triggerType: "tag",
      updateConfigSwarm: [
        "<value 1>",
      ],
      username: "Johann_Moen",
      watchPaths: [
        "<value 1>",
      ],
    },
  ],
  compose: [],
  createdAt: "1717152313403",
  description:
    "furthermore unto finally gah modulo punctually whereas alienated basic",
  env: "<value>",
  environmentId: "<id>",
  mariadb: [],
  mongo: [],
  mysql: [
    {
      appName: "<value>",
      applicationStatus: "done",
      command: "<value>",
      cpuLimit: "<value>",
      cpuReservation: "<value>",
      createdAt: "1705779679419",
      databaseName: "<value>",
      databasePassword: "<value>",
      databaseRootPassword: "<value>",
      databaseUser: "<value>",
      description:
        "promise toward anaesthetise gee an unfurl wherever even absentmindedly innocently",
      dockerImage: "<value>",
      env: "<value>",
      environmentId: "<id>",
      externalPort: 432.5,
      healthCheckSwarm: [],
      labelsSwarm: [
        "<value 1>",
      ],
      memoryLimit: "<value>",
      memoryReservation: "<value>",
      modeSwarm: {},
      mysqlId: "<id>",
      name: "<value>",
      networkSwarm: null,
      placementSwarm: null,
      replicas: 7343.12,
      restartPolicySwarm: [
        "<value 1>",
        "<value 2>",
      ],
      rollbackConfigSwarm: true,
      serverId: "<id>",
      updateConfigSwarm: {
        "key": "<value>",
      },
    },
  ],
  name: "<value>",
  postgres: [
    {
      appName: "<value>",
      applicationStatus: "idle",
      command: "<value>",
      cpuLimit: "<value>",
      cpuReservation: "<value>",
      createdAt: "1718600927083",
      databaseName: "<value>",
      databasePassword: "<value>",
      databaseUser: "<value>",
      description: "uproot gah splay lost hurtful overproduce",
      dockerImage: "<value>",
      env: "<value>",
      environmentId: "<id>",
      externalPort: 9698.71,
      healthCheckSwarm: null,
      labelsSwarm: null,
      memoryLimit: "<value>",
      memoryReservation: "<value>",
      modeSwarm: [],
      name: "<value>",
      networkSwarm: {},
      placementSwarm: "null",
      postgresId: "<id>",
      replicas: 738.65,
      restartPolicySwarm: null,
      rollbackConfigSwarm: 2250.88,
      serverId: "<id>",
      updateConfigSwarm: "<value>",
    },
  ],
  project: {
    createdAt: "1706015984263",
    description: "inwardly hutch calmly",
    env: "<value>",
    name: "<value>",
    organizationId: "<id>",
    projectId: "<id>",
  },
  projectId: "<id>",
  redis: [
    {
      appName: "<value>",
      applicationStatus: "done",
      command: "<value>",
      cpuLimit: null,
      cpuReservation: "<value>",
      createdAt: "1734367809644",
      databasePassword: "<value>",
      description: "offset even conservation underneath and pish ornate",
      dockerImage: "<value>",
      env: "<value>",
      environmentId: "<id>",
      externalPort: 4143.62,
      healthCheckSwarm: null,
      labelsSwarm: "null",
      memoryLimit: "<value>",
      memoryReservation: "<value>",
      modeSwarm: "null",
      name: "<value>",
      networkSwarm: {
        "key": "<value>",
      },
      placementSwarm: [
        "<value 1>",
      ],
      redisId: "<id>",
      replicas: 1737.42,
      restartPolicySwarm: {
        "key": "<value>",
        "key1": "<value>",
      },
      rollbackConfigSwarm: "null",
      serverId: "<id>",
      updateConfigSwarm: true,
    },
  ],
};
```

## Fields

| Field                                                                                                          | Type                                                                                                           | Required                                                                                                       | Description                                                                                                    |
| -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| `applications`                                                                                                 | [operations.EnvironmentByProjectIdApplication](../../models/operations/environmentbyprojectidapplication.md)[] | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `compose`                                                                                                      | [operations.EnvironmentByProjectIdCompose](../../models/operations/environmentbyprojectidcompose.md)[]         | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `createdAt`                                                                                                    | *string*                                                                                                       | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `description`                                                                                                  | *string*                                                                                                       | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `env`                                                                                                          | *string*                                                                                                       | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `environmentId`                                                                                                | *string*                                                                                                       | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `mariadb`                                                                                                      | [operations.EnvironmentByProjectIdMariadb](../../models/operations/environmentbyprojectidmariadb.md)[]         | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `mongo`                                                                                                        | [operations.EnvironmentByProjectIdMongo](../../models/operations/environmentbyprojectidmongo.md)[]             | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `mysql`                                                                                                        | [operations.EnvironmentByProjectIdMysql](../../models/operations/environmentbyprojectidmysql.md)[]             | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `name`                                                                                                         | *string*                                                                                                       | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `postgres`                                                                                                     | [operations.EnvironmentByProjectIdPostgre](../../models/operations/environmentbyprojectidpostgre.md)[]         | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `project`                                                                                                      | [operations.EnvironmentByProjectIdProject](../../models/operations/environmentbyprojectidproject.md)           | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `projectId`                                                                                                    | *string*                                                                                                       | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `redis`                                                                                                        | [operations.EnvironmentByProjectIdRedi](../../models/operations/environmentbyprojectidredi.md)[]               | :heavy_check_mark:                                                                                             | N/A                                                                                                            |