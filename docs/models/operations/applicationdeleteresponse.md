# ApplicationDeleteResponse


## Supported Types

### `operations.ApplicationDeleteResponseBody`

```typescript
const value: operations.ApplicationDeleteResponseBody = {
  bitbucket: {
    appPassword: "<value>",
    bitbucketId: "<id>",
    bitbucketUsername: "<value>",
    bitbucketWorkspaceName: "<value>",
    gitProviderId: "<id>",
  },
  deployments: [
    {
      applicationId: "<id>",
      backupId: null,
      composeId: "<id>",
      createdAt: "1717110921239",
      deploymentId: "<id>",
      description: "blah ah blindly contradict schnitzel muffled",
      errorMessage: "<value>",
      finishedAt: "<value>",
      isPreviewDeployment: true,
      logPath: "<value>",
      pid: "<id>",
      previewDeploymentId: "<id>",
      rollbackId: "<id>",
      scheduleId: "<id>",
      serverId: "<id>",
      startedAt: "<value>",
      status: null,
      title: "<value>",
      volumeBackupId: "<id>",
    },
  ],
  domains: [],
  environment: {
    createdAt: "1705560402729",
    description: "fork furiously ignite synergy aw punctual",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1725371614083",
      description:
        "attribute brightly wetly but progress baseboard furthermore loyally",
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
    expiresAt: 3094.52,
    gitProviderId: "<id>",
    giteaId: "<id>",
    giteaUrl: "https://husky-cheese.biz",
    lastAuthenticatedAt: null,
    redirectUri: "https://webbed-stir-fry.com",
    refreshToken: "<value>",
    scopes: "<value>",
  },
  github: {
    gitProviderId: "<id>",
    githubAppId: 9371,
    githubAppName: "<value>",
    githubClientId: "<id>",
    githubClientSecret: null,
    githubId: "<id>",
    githubInstallationId: "<id>",
    githubPrivateKey: null,
    githubWebhookSecret: null,
  },
  gitlab: {
    accessToken: "<value>",
    applicationId: "<id>",
    expiresAt: 3909.93,
    gitProviderId: "<id>",
    gitlabId: "<id>",
    gitlabUrl: "https://heartfelt-help.biz/",
    groupName: "<value>",
    redirectUri: "https://warmhearted-vista.com",
    refreshToken: "<value>",
    secret: "<value>",
  },
  mounts: [],
  name: "<value>",
  ports: [
    {
      applicationId: "<id>",
      portId: "<id>",
      protocol: "udp",
      publishMode: "host",
      publishedPort: 692.6,
      targetPort: 109.31,
    },
  ],
  previewDeployments: [
    {
      appName: "<value>",
      applicationId: "<id>",
      branch: "<value>",
      createdAt: "1708177089962",
      domainId: "<id>",
      expiresAt: "1746824892196",
      previewDeploymentId: "<id>",
      previewStatus: "running",
      pullRequestCommentId: "<id>",
      pullRequestId: "<id>",
      pullRequestNumber: "<value>",
      pullRequestTitle: "<value>",
      pullRequestURL: "https://utilized-fog.name",
    },
  ],
  redirects: [],
  registry: {
    createdAt: "1723820196903",
    imagePrefix: "<value>",
    organizationId: "<id>",
    password: "quzRh44JpYvu0A5",
    registryId: "<id>",
    registryName: "<value>",
    registryType: "selfHosted",
    registryUrl: "https://silky-pension.biz",
    username: "Rebeka_DAmore23",
  },
  security: [
    {
      applicationId: "<id>",
      createdAt: "1731674527424",
      password: "G8EICSvbIc5PAmA",
      securityId: "<id>",
      username: "Gordon.Hudson77",
    },
  ],
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1716129912660",
    description: "rim phew powerless past barracks up goodwill",
    enableDockerCleanup: false,
    ipAddress: "d703:eea2:bfcf:45f7:e7da:1cdb:8fcc:1d0c",
    metricsConfig: {
      "key": "<value>",
      "key1": "<value>",
      "key2": "<value>",
    },
    name: "<value>",
    organizationId: "<id>",
    port: 6333.84,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Helene58",
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

