# ApplicationOneResponseBody

Successful response

## Example Usage

```typescript
import { ApplicationOneResponseBody } from "dokploy-sdk/models/operations";

let value: ApplicationOneResponseBody = {
  bitbucket: {
    appPassword: "<value>",
    bitbucketId: "<id>",
    bitbucketUsername: "<value>",
    bitbucketWorkspaceName: "<value>",
    gitProviderId: "<id>",
  },
  deployments: [],
  domains: [
    {
      applicationId: "<id>",
      certificateType: "letsencrypt",
      composeId: "<id>",
      createdAt: "1726431900283",
      customCertResolver: "<value>",
      domainId: "<id>",
      domainType: "compose",
      host: "miserly-density.name",
      https: false,
      internalPath: null,
      path: "/rescue",
      port: null,
      previewDeploymentId: "<id>",
      serviceName: "<value>",
      stripPath: false,
      uniqueConfigKey: 1416.09,
    },
  ],
  environment: {
    createdAt: "1704974983120",
    description: "upwardly unbearably daintily below tenderly aha",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1712173287320",
      description:
        "regular spotless abaft considering however cautiously vicinity atop suddenly",
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
    clientId: null,
    clientSecret: "<value>",
    expiresAt: 3782.15,
    gitProviderId: "<id>",
    giteaId: "<id>",
    giteaUrl: "https://sneaky-dusk.info",
    lastAuthenticatedAt: null,
    redirectUri: "https://immense-story.biz",
    refreshToken: "<value>",
    scopes: "<value>",
  },
  github: {
    gitProviderId: "<id>",
    githubAppId: 6380.22,
    githubAppName: "<value>",
    githubClientId: "<id>",
    githubClientSecret: "<value>",
    githubId: "<id>",
    githubInstallationId: "<id>",
    githubPrivateKey: "<value>",
    githubWebhookSecret: "<value>",
  },
  gitlab: {
    accessToken: "<value>",
    applicationId: "<id>",
    expiresAt: null,
    gitProviderId: "<id>",
    gitlabId: "<id>",
    gitlabUrl: "https://valuable-boyfriend.info",
    groupName: "<value>",
    redirectUri: null,
    refreshToken: "<value>",
    secret: "<value>",
  },
  hasGitProviderAccess: true,
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: "/selinux/hole_tidy.war",
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: null,
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: null,
      serviceType: "mongo",
      type: "file",
      volumeName: "<value>",
    },
  ],
  name: "<value>",
  ports: [],
  previewDeployments: [
    {
      appName: "<value>",
      applicationId: "<id>",
      branch: "<value>",
      createdAt: "1718836537470",
      domainId: "<id>",
      expiresAt: null,
      previewDeploymentId: "<id>",
      previewStatus: "running",
      pullRequestCommentId: "<id>",
      pullRequestId: "<id>",
      pullRequestNumber: "<value>",
      pullRequestTitle: "<value>",
      pullRequestURL: "https://splendid-request.info/",
    },
  ],
  redirects: [],
  registry: {
    createdAt: "1732623398669",
    imagePrefix: "<value>",
    organizationId: "<id>",
    password: "0a71GFQeTD2WCvn",
    registryId: "<id>",
    registryName: "<value>",
    registryType: "selfHosted",
    registryUrl: "https://ample-knuckle.biz/",
    username: "Mathias0",
  },
  security: [],
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1714144966856",
    description: "decent apropos properly entrench very impact",
    enableDockerCleanup: true,
    ipAddress: "f91b:0f3e:0b04:4a6a:771c:3e2e:3d5f:d440",
    metricsConfig: "<value>",
    name: "<value>",
    organizationId: "<id>",
    port: 6058.75,
    serverId: "<id>",
    serverStatus: "active",
    sshKeyId: "<id>",
    username: "Shemar_Lindgren",
  },
  unauthorizedProvider: "gitea",
};
```

## Fields

| Field                                                                                                              | Type                                                                                                               | Required                                                                                                           | Description                                                                                                        |
| ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ |
| `appName`                                                                                                          | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `applicationId`                                                                                                    | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `applicationStatus`                                                                                                | [operations.ApplicationOneApplicationStatus](../../models/operations/applicationoneapplicationstatus.md)           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `autoDeploy`                                                                                                       | *boolean*                                                                                                          | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `bitbucket`                                                                                                        | [operations.ApplicationOneBitbucket](../../models/operations/applicationonebitbucket.md)                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `bitbucketBranch`                                                                                                  | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `bitbucketBuildPath`                                                                                               | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `bitbucketId`                                                                                                      | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `bitbucketOwner`                                                                                                   | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `bitbucketRepository`                                                                                              | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `branch`                                                                                                           | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `buildArgs`                                                                                                        | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `buildPath`                                                                                                        | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `buildType`                                                                                                        | [operations.ApplicationOneBuildType](../../models/operations/applicationonebuildtype.md)                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `cleanCache`                                                                                                       | *boolean*                                                                                                          | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `command`                                                                                                          | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `cpuLimit`                                                                                                         | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `cpuReservation`                                                                                                   | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `createdAt`                                                                                                        | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `customGitBranch`                                                                                                  | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `customGitBuildPath`                                                                                               | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `customGitSSHKeyId`                                                                                                | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `customGitUrl`                                                                                                     | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `deployments`                                                                                                      | [operations.ApplicationOneDeployment](../../models/operations/applicationonedeployment.md)[]                       | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `description`                                                                                                      | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `dockerBuildStage`                                                                                                 | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `dockerContextPath`                                                                                                | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `dockerImage`                                                                                                      | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `dockerfile`                                                                                                       | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `domains`                                                                                                          | [operations.ApplicationOneDomain](../../models/operations/applicationonedomain.md)[]                               | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `dropBuildPath`                                                                                                    | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `enableSubmodules`                                                                                                 | *boolean*                                                                                                          | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `enabled`                                                                                                          | *boolean*                                                                                                          | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `env`                                                                                                              | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `environment`                                                                                                      | [operations.ApplicationOneEnvironment](../../models/operations/applicationoneenvironment.md)                       | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `environmentId`                                                                                                    | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `gitea`                                                                                                            | [operations.ApplicationOneGitea](../../models/operations/applicationonegitea.md)                                   | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `giteaBranch`                                                                                                      | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `giteaBuildPath`                                                                                                   | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `giteaId`                                                                                                          | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `giteaOwner`                                                                                                       | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `giteaRepository`                                                                                                  | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `github`                                                                                                           | [operations.ApplicationOneGithub](../../models/operations/applicationonegithub.md)                                 | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `githubId`                                                                                                         | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `gitlab`                                                                                                           | [operations.ApplicationOneGitlab](../../models/operations/applicationonegitlab.md)                                 | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `gitlabBranch`                                                                                                     | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `gitlabBuildPath`                                                                                                  | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `gitlabId`                                                                                                         | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `gitlabOwner`                                                                                                      | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `gitlabPathNamespace`                                                                                              | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `gitlabProjectId`                                                                                                  | *number*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `gitlabRepository`                                                                                                 | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `hasGitProviderAccess`                                                                                             | *boolean*                                                                                                          | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `healthCheckSwarm`                                                                                                 | [operations.ApplicationOneHealthCheckSwarm](../../models/operations/applicationonehealthcheckswarm.md)             | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `herokuVersion`                                                                                                    | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `isPreviewDeploymentsActive`                                                                                       | *boolean*                                                                                                          | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `isStaticSpa`                                                                                                      | *boolean*                                                                                                          | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `labelsSwarm`                                                                                                      | Record<string, *string*>                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `memoryLimit`                                                                                                      | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `memoryReservation`                                                                                                | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `modeSwarm`                                                                                                        | [operations.ApplicationOneModeSwarm](../../models/operations/applicationonemodeswarm.md)                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `mounts`                                                                                                           | [operations.ApplicationOneMount](../../models/operations/applicationonemount.md)[]                                 | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `name`                                                                                                             | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `networkSwarm`                                                                                                     | [operations.ApplicationOneNetworkSwarm](../../models/operations/applicationonenetworkswarm.md)[]                   | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `owner`                                                                                                            | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `password`                                                                                                         | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `placementSwarm`                                                                                                   | [operations.ApplicationOnePlacementSwarm](../../models/operations/applicationoneplacementswarm.md)                 | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `ports`                                                                                                            | [operations.ApplicationOnePort](../../models/operations/applicationoneport.md)[]                                   | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `previewBuildArgs`                                                                                                 | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `previewCertificateType`                                                                                           | [operations.ApplicationOnePreviewCertificateType](../../models/operations/applicationonepreviewcertificatetype.md) | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `previewCustomCertResolver`                                                                                        | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `previewDeployments`                                                                                               | [operations.ApplicationOnePreviewDeployment](../../models/operations/applicationonepreviewdeployment.md)[]         | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `previewEnv`                                                                                                       | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `previewHttps`                                                                                                     | *boolean*                                                                                                          | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `previewLabels`                                                                                                    | *string*[]                                                                                                         | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `previewLimit`                                                                                                     | *number*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `previewPath`                                                                                                      | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `previewPort`                                                                                                      | *number*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `previewRequireCollaboratorPermissions`                                                                            | *boolean*                                                                                                          | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `previewWildcard`                                                                                                  | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `publishDirectory`                                                                                                 | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `railpackVersion`                                                                                                  | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `redirects`                                                                                                        | [operations.ApplicationOneRedirect](../../models/operations/applicationoneredirect.md)[]                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `refreshToken`                                                                                                     | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `registry`                                                                                                         | [operations.ApplicationOneRegistry](../../models/operations/applicationoneregistry.md)                             | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `registryId`                                                                                                       | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `registryUrl`                                                                                                      | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `replicas`                                                                                                         | *number*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `repository`                                                                                                       | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `restartPolicySwarm`                                                                                               | [operations.ApplicationOneRestartPolicySwarm](../../models/operations/applicationonerestartpolicyswarm.md)         | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `rollbackActive`                                                                                                   | *boolean*                                                                                                          | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `rollbackConfigSwarm`                                                                                              | [operations.ApplicationOneRollbackConfigSwarm](../../models/operations/applicationonerollbackconfigswarm.md)       | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `security`                                                                                                         | [operations.ApplicationOneSecurity](../../models/operations/applicationonesecurity.md)[]                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `server`                                                                                                           | [operations.ApplicationOneServer](../../models/operations/applicationoneserver.md)                                 | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `serverId`                                                                                                         | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `sourceType`                                                                                                       | [operations.ApplicationOneSourceType](../../models/operations/applicationonesourcetype.md)                         | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `subtitle`                                                                                                         | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `title`                                                                                                            | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `triggerType`                                                                                                      | [operations.ApplicationOneTriggerType](../../models/operations/applicationonetriggertype.md)                       | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `unauthorizedProvider`                                                                                             | [operations.UnauthorizedProvider](../../models/operations/unauthorizedprovider.md)                                 | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `updateConfigSwarm`                                                                                                | [operations.ApplicationOneUpdateConfigSwarm](../../models/operations/applicationoneupdateconfigswarm.md)           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `username`                                                                                                         | *string*                                                                                                           | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |
| `watchPaths`                                                                                                       | *string*[]                                                                                                         | :heavy_minus_sign:                                                                                                 | N/A                                                                                                                |