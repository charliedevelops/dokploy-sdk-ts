# ApplicationStopResponseBody

Successful response

## Example Usage

```typescript
import { ApplicationStopResponseBody } from "dokploy-sdk/models/operations";

let value: ApplicationStopResponseBody = {
  bitbucket: {
    appPassword: "<value>",
    bitbucketId: "<id>",
    bitbucketUsername: "<value>",
    bitbucketWorkspaceName: "<value>",
    gitProviderId: "<id>",
  },
  deployments: [
    {
      applicationId: null,
      backupId: "<id>",
      composeId: "<id>",
      createdAt: "1723878221457",
      deploymentId: "<id>",
      description: "gosh gadzooks than nor hmph whoever whose as a unless",
      errorMessage: "<value>",
      finishedAt: "<value>",
      isPreviewDeployment: false,
      logPath: "<value>",
      pid: "<id>",
      previewDeploymentId: "<id>",
      rollbackId: "<id>",
      scheduleId: "<id>",
      serverId: "<id>",
      startedAt: "<value>",
      status: "running",
      title: "<value>",
      volumeBackupId: "<id>",
    },
  ],
  domains: [],
  environment: {
    createdAt: "1719984209438",
    description: "long but amount acidly oof empty underneath beep round aha",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1730454078929",
      description: "fuss nervously rich uh-huh",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  gitea: {
    accessToken: "<value>",
    clientId: "<id>",
    clientSecret: "<value>",
    expiresAt: 5032.98,
    gitProviderId: "<id>",
    giteaId: "<id>",
    giteaUrl: "https://smug-gray.net",
    lastAuthenticatedAt: 1508.36,
    redirectUri: "https://hefty-breastplate.org",
    refreshToken: "<value>",
    scopes: "<value>",
  },
  github: null,
  gitlab: {
    accessToken: "<value>",
    applicationId: "<id>",
    expiresAt: 8539.48,
    gitProviderId: "<id>",
    gitlabId: "<id>",
    gitlabUrl: "https://negligible-electronics.net",
    groupName: "<value>",
    redirectUri: "https://fearless-corporation.name",
    refreshToken: null,
    secret: "<value>",
  },
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: "/selinux/fray_that_comparison.list",
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: "<id>",
      serviceType: "redis",
      type: "file",
      volumeName: null,
    },
  ],
  name: "<value>",
  ports: [
    {
      applicationId: "<id>",
      portId: "<id>",
      protocol: "udp",
      publishMode: "ingress",
      publishedPort: 2013.96,
      targetPort: 5916.58,
    },
  ],
  previewDeployments: [
    {
      appName: "<value>",
      applicationId: "<id>",
      branch: "<value>",
      createdAt: "1708636404915",
      domainId: "<id>",
      expiresAt: "1749323109681",
      previewDeploymentId: "<id>",
      previewStatus: "error",
      pullRequestCommentId: "<id>",
      pullRequestId: "<id>",
      pullRequestNumber: "<value>",
      pullRequestTitle: "<value>",
      pullRequestURL: "https://deserted-obesity.name",
    },
  ],
  redirects: [],
  registry: {
    createdAt: "1708673929172",
    imagePrefix: "<value>",
    organizationId: "<id>",
    password: "lGhpZnJpaZgbIUA",
    registryId: "<id>",
    registryName: "<value>",
    registryType: "cloud",
    registryUrl: "https://intent-doing.info",
    username: "Warren.Bashirian87",
  },
  security: [
    {
      applicationId: "<id>",
      createdAt: "1731674517472",
      password: "e1RS730cZJjdWa7",
      securityId: "<id>",
      username: "Cleta_Klocko",
    },
  ],
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1728417310124",
    description: "meh kick fragrant elver acidic hard-to-find impanel subsidy",
    enableDockerCleanup: true,
    ipAddress: "17.13.40.81",
    metricsConfig: {},
    name: "<value>",
    organizationId: "<id>",
    port: 2089.9,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Wilma63",
  },
};
```

## Fields

| Field                                                                                                                | Type                                                                                                                 | Required                                                                                                             | Description                                                                                                          |
| -------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| `appName`                                                                                                            | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `applicationId`                                                                                                      | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `applicationStatus`                                                                                                  | [operations.ApplicationStopApplicationStatus](../../models/operations/applicationstopapplicationstatus.md)           | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `autoDeploy`                                                                                                         | *boolean*                                                                                                            | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `bitbucket`                                                                                                          | [operations.ApplicationStopBitbucket](../../models/operations/applicationstopbitbucket.md)                           | :heavy_check_mark:                                                                                                   | N/A                                                                                                                  |
| `bitbucketBranch`                                                                                                    | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `bitbucketBuildPath`                                                                                                 | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `bitbucketId`                                                                                                        | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `bitbucketOwner`                                                                                                     | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `bitbucketRepository`                                                                                                | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `branch`                                                                                                             | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `buildArgs`                                                                                                          | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `buildPath`                                                                                                          | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `buildType`                                                                                                          | [operations.ApplicationStopBuildType](../../models/operations/applicationstopbuildtype.md)                           | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `cleanCache`                                                                                                         | *boolean*                                                                                                            | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `command`                                                                                                            | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `cpuLimit`                                                                                                           | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `cpuReservation`                                                                                                     | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `createdAt`                                                                                                          | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `customGitBranch`                                                                                                    | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `customGitBuildPath`                                                                                                 | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `customGitSSHKeyId`                                                                                                  | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `customGitUrl`                                                                                                       | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `deployments`                                                                                                        | [operations.ApplicationStopDeployment](../../models/operations/applicationstopdeployment.md)[]                       | :heavy_check_mark:                                                                                                   | N/A                                                                                                                  |
| `description`                                                                                                        | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `dockerBuildStage`                                                                                                   | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `dockerContextPath`                                                                                                  | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `dockerImage`                                                                                                        | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `dockerfile`                                                                                                         | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `domains`                                                                                                            | [operations.ApplicationStopDomain](../../models/operations/applicationstopdomain.md)[]                               | :heavy_check_mark:                                                                                                   | N/A                                                                                                                  |
| `dropBuildPath`                                                                                                      | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `enableSubmodules`                                                                                                   | *boolean*                                                                                                            | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `enabled`                                                                                                            | *boolean*                                                                                                            | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `env`                                                                                                                | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `environment`                                                                                                        | [operations.ApplicationStopEnvironment](../../models/operations/applicationstopenvironment.md)                       | :heavy_check_mark:                                                                                                   | N/A                                                                                                                  |
| `environmentId`                                                                                                      | *string*                                                                                                             | :heavy_check_mark:                                                                                                   | N/A                                                                                                                  |
| `gitea`                                                                                                              | [operations.ApplicationStopGitea](../../models/operations/applicationstopgitea.md)                                   | :heavy_check_mark:                                                                                                   | N/A                                                                                                                  |
| `giteaBranch`                                                                                                        | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `giteaBuildPath`                                                                                                     | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `giteaId`                                                                                                            | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `giteaOwner`                                                                                                         | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `giteaRepository`                                                                                                    | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `github`                                                                                                             | [operations.ApplicationStopGithub](../../models/operations/applicationstopgithub.md)                                 | :heavy_check_mark:                                                                                                   | N/A                                                                                                                  |
| `githubId`                                                                                                           | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `gitlab`                                                                                                             | [operations.ApplicationStopGitlab](../../models/operations/applicationstopgitlab.md)                                 | :heavy_check_mark:                                                                                                   | N/A                                                                                                                  |
| `gitlabBranch`                                                                                                       | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `gitlabBuildPath`                                                                                                    | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `gitlabId`                                                                                                           | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `gitlabOwner`                                                                                                        | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `gitlabPathNamespace`                                                                                                | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `gitlabProjectId`                                                                                                    | *number*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `gitlabRepository`                                                                                                   | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `healthCheckSwarm`                                                                                                   | [operations.ApplicationStopHealthCheckSwarm](../../models/operations/applicationstophealthcheckswarm.md)             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `herokuVersion`                                                                                                      | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `isPreviewDeploymentsActive`                                                                                         | *boolean*                                                                                                            | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `isStaticSpa`                                                                                                        | *boolean*                                                                                                            | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `labelsSwarm`                                                                                                        | Record<string, *string*>                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `memoryLimit`                                                                                                        | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `memoryReservation`                                                                                                  | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `modeSwarm`                                                                                                          | [operations.ApplicationStopModeSwarm](../../models/operations/applicationstopmodeswarm.md)                           | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `mounts`                                                                                                             | [operations.ApplicationStopMount](../../models/operations/applicationstopmount.md)[]                                 | :heavy_check_mark:                                                                                                   | N/A                                                                                                                  |
| `name`                                                                                                               | *string*                                                                                                             | :heavy_check_mark:                                                                                                   | N/A                                                                                                                  |
| `networkSwarm`                                                                                                       | [operations.ApplicationStopNetworkSwarm](../../models/operations/applicationstopnetworkswarm.md)[]                   | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `owner`                                                                                                              | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `password`                                                                                                           | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `placementSwarm`                                                                                                     | [operations.ApplicationStopPlacementSwarm](../../models/operations/applicationstopplacementswarm.md)                 | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `ports`                                                                                                              | [operations.ApplicationStopPort](../../models/operations/applicationstopport.md)[]                                   | :heavy_check_mark:                                                                                                   | N/A                                                                                                                  |
| `previewBuildArgs`                                                                                                   | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `previewCertificateType`                                                                                             | [operations.ApplicationStopPreviewCertificateType](../../models/operations/applicationstoppreviewcertificatetype.md) | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `previewCustomCertResolver`                                                                                          | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `previewDeployments`                                                                                                 | [operations.ApplicationStopPreviewDeployment](../../models/operations/applicationstoppreviewdeployment.md)[]         | :heavy_check_mark:                                                                                                   | N/A                                                                                                                  |
| `previewEnv`                                                                                                         | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `previewHttps`                                                                                                       | *boolean*                                                                                                            | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `previewLabels`                                                                                                      | *string*[]                                                                                                           | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `previewLimit`                                                                                                       | *number*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `previewPath`                                                                                                        | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `previewPort`                                                                                                        | *number*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `previewRequireCollaboratorPermissions`                                                                              | *boolean*                                                                                                            | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `previewWildcard`                                                                                                    | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `publishDirectory`                                                                                                   | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `railpackVersion`                                                                                                    | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `redirects`                                                                                                          | [operations.ApplicationStopRedirect](../../models/operations/applicationstopredirect.md)[]                           | :heavy_check_mark:                                                                                                   | N/A                                                                                                                  |
| `refreshToken`                                                                                                       | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `registry`                                                                                                           | [operations.ApplicationStopRegistry](../../models/operations/applicationstopregistry.md)                             | :heavy_check_mark:                                                                                                   | N/A                                                                                                                  |
| `registryId`                                                                                                         | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `registryUrl`                                                                                                        | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `replicas`                                                                                                           | *number*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `repository`                                                                                                         | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `restartPolicySwarm`                                                                                                 | [operations.ApplicationStopRestartPolicySwarm](../../models/operations/applicationstoprestartpolicyswarm.md)         | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `rollbackActive`                                                                                                     | *boolean*                                                                                                            | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `rollbackConfigSwarm`                                                                                                | [operations.ApplicationStopRollbackConfigSwarm](../../models/operations/applicationstoprollbackconfigswarm.md)       | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `security`                                                                                                           | [operations.ApplicationStopSecurityResponse](../../models/operations/applicationstopsecurityresponse.md)[]           | :heavy_check_mark:                                                                                                   | N/A                                                                                                                  |
| `server`                                                                                                             | [operations.ApplicationStopServer](../../models/operations/applicationstopserver.md)                                 | :heavy_check_mark:                                                                                                   | N/A                                                                                                                  |
| `serverId`                                                                                                           | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `sourceType`                                                                                                         | [operations.ApplicationStopSourceType](../../models/operations/applicationstopsourcetype.md)                         | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `subtitle`                                                                                                           | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `title`                                                                                                              | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `triggerType`                                                                                                        | [operations.ApplicationStopTriggerType](../../models/operations/applicationstoptriggertype.md)                       | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `updateConfigSwarm`                                                                                                  | [operations.ApplicationStopUpdateConfigSwarm](../../models/operations/applicationstopupdateconfigswarm.md)           | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `username`                                                                                                           | *string*                                                                                                             | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |
| `watchPaths`                                                                                                         | *string*[]                                                                                                           | :heavy_minus_sign:                                                                                                   | N/A                                                                                                                  |