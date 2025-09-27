# ApplicationOneResponse


## Supported Types

### `operations.ApplicationOneResponseBody`

```typescript
const value: operations.ApplicationOneResponseBody = {
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

### `models.ErrorT`

```typescript
const value: models.ErrorT = {
  code: "<value>",
  message: "<value>",
};
```

