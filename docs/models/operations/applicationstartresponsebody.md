# ApplicationStartResponseBody

Successful response

## Example Usage

```typescript
import { ApplicationStartResponseBody } from "dokploy-sdk/models/operations";

let value: ApplicationStartResponseBody = {
  name: "<value>",
  environmentId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "sleepy trial until sway maintainer until barring",
    createdAt: "1717643455195",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "tankful yahoo hence neck",
      createdAt: "1709110549258",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  domains: [],
  deployments: [
    {
      deploymentId: "<id>",
      title: "<value>",
      description: "venom youthfully critical other",
      status: null,
      logPath: "<value>",
      pid: "<id>",
      applicationId: null,
      composeId: "<id>",
      serverId: "<id>",
      isPreviewDeployment: true,
      previewDeploymentId: "<id>",
      createdAt: "1715560141517",
      startedAt: "<value>",
      finishedAt: "<value>",
      errorMessage: "<value>",
      scheduleId: "<id>",
      backupId: "<id>",
      rollbackId: "<id>",
      volumeBackupId: "<id>",
    },
  ],
  mounts: [
    {
      mountId: "<id>",
      type: "bind",
      hostPath: "<value>",
      volumeName: "<value>",
      filePath: "/etc/unaccountably.woff",
      content: "<value>",
      serviceType: "compose",
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
  redirects: [
    {
      redirectId: "<id>",
      regex: "<value>",
      replacement: "<value>",
      permanent: true,
      uniqueConfigKey: 5788.81,
      createdAt: "1707356094635",
      applicationId: "<id>",
    },
  ],
  security: [],
  ports: [
    {
      portId: "<id>",
      publishedPort: 153.4,
      publishMode: "ingress",
      targetPort: 824.02,
      protocol: "udp",
      applicationId: "<id>",
    },
  ],
  registry: {
    registryId: "<id>",
    registryName: "<value>",
    imagePrefix: "<value>",
    username: "Chyna_Kuvalis33",
    password: "fAF_RcxjvMV86g5",
    registryUrl: "https://unimportant-adviser.net",
    createdAt: "1729773724342",
    registryType: "selfHosted",
    organizationId: "<id>",
  },
  github: {
    githubId: "<id>",
    githubAppName: "<value>",
    githubAppId: 4821.58,
    githubClientId: "<id>",
    githubClientSecret: "<value>",
    githubInstallationId: "<id>",
    githubPrivateKey: "<value>",
    githubWebhookSecret: "<value>",
    gitProviderId: "<id>",
  },
  gitlab: {
    gitlabId: "<id>",
    gitlabUrl: "https://well-to-do-government.net/",
    applicationId: "<id>",
    redirectUri: "https://considerate-suitcase.name/",
    secret: "<value>",
    accessToken: "<value>",
    refreshToken: "<value>",
    groupName: "<value>",
    expiresAt: 2490.21,
    gitProviderId: "<id>",
  },
  bitbucket: {
    bitbucketId: "<id>",
    bitbucketUsername: "<value>",
    appPassword: "<value>",
    bitbucketWorkspaceName: "<value>",
    gitProviderId: "<id>",
  },
  gitea: {
    giteaId: "<id>",
    giteaUrl: "https://dim-mountain.biz/",
    redirectUri: "https://infinite-eternity.net",
    clientId: "<id>",
    clientSecret: "<value>",
    gitProviderId: "<id>",
    accessToken: "<value>",
    refreshToken: "<value>",
    expiresAt: 7320.27,
    scopes: "<value>",
    lastAuthenticatedAt: 7651.75,
  },
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "upon meh fatal lumpy even into task joyously",
    ipAddress: "4bac:8a45:0320:26b9:e84a:6dbd:a73f:d771",
    port: 4401.19,
    username: "Russell.Runte",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1717481954270",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: {
      "key": "<value>",
    },
  },
  previewDeployments: [
    {
      previewDeploymentId: "<id>",
      branch: "<value>",
      pullRequestId: "<id>",
      pullRequestNumber: "<value>",
      pullRequestURL: "https://magnificent-secret.net",
      pullRequestTitle: "<value>",
      pullRequestCommentId: "<id>",
      previewStatus: "done",
      appName: "<value>",
      applicationId: "<id>",
      domainId: "<id>",
      createdAt: "1704969568503",
      expiresAt: null,
    },
  ],
};
```

## Fields

| Field                                                                                                                  | Type                                                                                                                   | Required                                                                                                               | Description                                                                                                            |
| ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| `applicationId`                                                                                                        | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `name`                                                                                                                 | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `appName`                                                                                                              | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `description`                                                                                                          | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `env`                                                                                                                  | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `previewEnv`                                                                                                           | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `watchPaths`                                                                                                           | *string*[]                                                                                                             | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `previewBuildArgs`                                                                                                     | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `previewLabels`                                                                                                        | *string*[]                                                                                                             | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `previewWildcard`                                                                                                      | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `previewPort`                                                                                                          | *number*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `previewHttps`                                                                                                         | *boolean*                                                                                                              | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `previewPath`                                                                                                          | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `previewCertificateType`                                                                                               | [operations.ApplicationStartPreviewCertificateType](../../models/operations/applicationstartpreviewcertificatetype.md) | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `previewCustomCertResolver`                                                                                            | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `previewLimit`                                                                                                         | *number*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `isPreviewDeploymentsActive`                                                                                           | *boolean*                                                                                                              | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `previewRequireCollaboratorPermissions`                                                                                | *boolean*                                                                                                              | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `rollbackActive`                                                                                                       | *boolean*                                                                                                              | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `buildArgs`                                                                                                            | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `memoryReservation`                                                                                                    | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `memoryLimit`                                                                                                          | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `cpuReservation`                                                                                                       | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `cpuLimit`                                                                                                             | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `title`                                                                                                                | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `enabled`                                                                                                              | *boolean*                                                                                                              | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `subtitle`                                                                                                             | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `command`                                                                                                              | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `refreshToken`                                                                                                         | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `sourceType`                                                                                                           | [operations.ApplicationStartSourceType](../../models/operations/applicationstartsourcetype.md)                         | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `cleanCache`                                                                                                           | *boolean*                                                                                                              | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `repository`                                                                                                           | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `owner`                                                                                                                | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `branch`                                                                                                               | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `buildPath`                                                                                                            | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `triggerType`                                                                                                          | [operations.ApplicationStartTriggerType](../../models/operations/applicationstarttriggertype.md)                       | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `autoDeploy`                                                                                                           | *boolean*                                                                                                              | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `gitlabProjectId`                                                                                                      | *number*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `gitlabRepository`                                                                                                     | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `gitlabOwner`                                                                                                          | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `gitlabBranch`                                                                                                         | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `gitlabBuildPath`                                                                                                      | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `gitlabPathNamespace`                                                                                                  | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `giteaRepository`                                                                                                      | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `giteaOwner`                                                                                                           | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `giteaBranch`                                                                                                          | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `giteaBuildPath`                                                                                                       | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `bitbucketRepository`                                                                                                  | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `bitbucketOwner`                                                                                                       | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `bitbucketBranch`                                                                                                      | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `bitbucketBuildPath`                                                                                                   | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `username`                                                                                                             | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `password`                                                                                                             | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `dockerImage`                                                                                                          | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `registryUrl`                                                                                                          | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `customGitUrl`                                                                                                         | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `customGitBranch`                                                                                                      | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `customGitBuildPath`                                                                                                   | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `customGitSSHKeyId`                                                                                                    | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `enableSubmodules`                                                                                                     | *boolean*                                                                                                              | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `dockerfile`                                                                                                           | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `dockerContextPath`                                                                                                    | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `dockerBuildStage`                                                                                                     | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `dropBuildPath`                                                                                                        | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `healthCheckSwarm`                                                                                                     | [operations.ApplicationStartHealthCheckSwarm](../../models/operations/applicationstarthealthcheckswarm.md)             | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `restartPolicySwarm`                                                                                                   | [operations.ApplicationStartRestartPolicySwarm](../../models/operations/applicationstartrestartpolicyswarm.md)         | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `placementSwarm`                                                                                                       | [operations.ApplicationStartPlacementSwarm](../../models/operations/applicationstartplacementswarm.md)                 | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `updateConfigSwarm`                                                                                                    | [operations.ApplicationStartUpdateConfigSwarm](../../models/operations/applicationstartupdateconfigswarm.md)           | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `rollbackConfigSwarm`                                                                                                  | [operations.ApplicationStartRollbackConfigSwarm](../../models/operations/applicationstartrollbackconfigswarm.md)       | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `modeSwarm`                                                                                                            | [operations.ApplicationStartModeSwarm](../../models/operations/applicationstartmodeswarm.md)                           | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `labelsSwarm`                                                                                                          | Record<string, *string*>                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `networkSwarm`                                                                                                         | [operations.ApplicationStartNetworkSwarm](../../models/operations/applicationstartnetworkswarm.md)[]                   | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `replicas`                                                                                                             | *number*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `applicationStatus`                                                                                                    | [operations.ApplicationStartApplicationStatus](../../models/operations/applicationstartapplicationstatus.md)           | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `buildType`                                                                                                            | [operations.ApplicationStartBuildType](../../models/operations/applicationstartbuildtype.md)                           | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `railpackVersion`                                                                                                      | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `herokuVersion`                                                                                                        | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `publishDirectory`                                                                                                     | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `isStaticSpa`                                                                                                          | *boolean*                                                                                                              | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `createdAt`                                                                                                            | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `registryId`                                                                                                           | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `environmentId`                                                                                                        | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `githubId`                                                                                                             | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `gitlabId`                                                                                                             | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `giteaId`                                                                                                              | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `bitbucketId`                                                                                                          | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `serverId`                                                                                                             | *string*                                                                                                               | :heavy_minus_sign:                                                                                                     | N/A                                                                                                                    |
| `environment`                                                                                                          | [operations.ApplicationStartEnvironment](../../models/operations/applicationstartenvironment.md)                       | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `domains`                                                                                                              | [operations.ApplicationStartDomain](../../models/operations/applicationstartdomain.md)[]                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `deployments`                                                                                                          | [operations.ApplicationStartDeployment](../../models/operations/applicationstartdeployment.md)[]                       | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `mounts`                                                                                                               | [operations.ApplicationStartMount](../../models/operations/applicationstartmount.md)[]                                 | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `redirects`                                                                                                            | [operations.ApplicationStartRedirect](../../models/operations/applicationstartredirect.md)[]                           | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `security`                                                                                                             | [operations.ApplicationStartSecurityResponse](../../models/operations/applicationstartsecurityresponse.md)[]           | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `ports`                                                                                                                | [operations.ApplicationStartPort](../../models/operations/applicationstartport.md)[]                                   | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `registry`                                                                                                             | [operations.ApplicationStartRegistry](../../models/operations/applicationstartregistry.md)                             | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `github`                                                                                                               | [operations.ApplicationStartGithub](../../models/operations/applicationstartgithub.md)                                 | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `gitlab`                                                                                                               | [operations.ApplicationStartGitlab](../../models/operations/applicationstartgitlab.md)                                 | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `bitbucket`                                                                                                            | [operations.ApplicationStartBitbucket](../../models/operations/applicationstartbitbucket.md)                           | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `gitea`                                                                                                                | [operations.ApplicationStartGitea](../../models/operations/applicationstartgitea.md)                                   | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `server`                                                                                                               | [operations.ApplicationStartServer](../../models/operations/applicationstartserver.md)                                 | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `previewDeployments`                                                                                                   | [operations.ApplicationStartPreviewDeployment](../../models/operations/applicationstartpreviewdeployment.md)[]         | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |