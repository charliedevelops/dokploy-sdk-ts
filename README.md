# dokploy-sdk

Developer-friendly & type-safe Typescript SDK specifically catered to leverage *dokploy-sdk* API.

<div align="left">
    <a href="https://www.speakeasy.com/?utm_source=dokploy-sdk&utm_campaign=typescript"><img src="https://www.speakeasy.com/assets/badges/built-by-speakeasy.svg" /></a>
    <a href="https://opensource.org/licenses/MIT">
        <img src="https://img.shields.io/badge/License-MIT-blue.svg" style="width: 100px; height: 28px;" />
    </a>
</div>


<br /><br />
> [!IMPORTANT]
> This SDK is not yet ready for production use. To complete setup please follow the steps outlined in your [workspace](https://app.speakeasy.com/org/polariselabs/dokploy). Delete this section before > publishing to a package manager.

<!-- Start Summary [summary] -->
## Summary

Dokploy API: Endpoints for dokploy

More information about the API can be found at http://localhost:3000/api/settings.getOpenApiDocument
<!-- End Summary [summary] -->

<!-- Start Table of Contents [toc] -->
## Table of Contents
<!-- $toc-max-depth=2 -->
* [dokploy-sdk](#dokploy-sdk)
  * [SDK Installation](#sdk-installation)
  * [Requirements](#requirements)
  * [SDK Example Usage](#sdk-example-usage)
  * [Authentication](#authentication)
  * [Available Resources and Operations](#available-resources-and-operations)
  * [Standalone functions](#standalone-functions)
  * [Retries](#retries)
  * [Error Handling](#error-handling)
  * [Server Selection](#server-selection)
  * [Custom HTTP Client](#custom-http-client)
  * [Debugging](#debugging)
* [Development](#development)
  * [Maturity](#maturity)
  * [Contributions](#contributions)

<!-- End Table of Contents [toc] -->

<!-- Start SDK Installation [installation] -->
## SDK Installation

> [!TIP]
> To finish publishing your SDK to npm and others you must [run your first generation action](https://www.speakeasy.com/docs/github-setup#step-by-step-guide).


The SDK can be installed with either [npm](https://www.npmjs.com/), [pnpm](https://pnpm.io/), [bun](https://bun.sh/) or [yarn](https://classic.yarnpkg.com/en/) package managers.

### NPM

```bash
npm add <UNSET>
```

### PNPM

```bash
pnpm add <UNSET>
```

### Bun

```bash
bun add <UNSET>
```

### Yarn

```bash
yarn add <UNSET> zod

# Note that Yarn does not install peer dependencies automatically. You will need
# to install zod as shown above.
```

> [!NOTE]
> This package is published with CommonJS and ES Modules (ESM) support.
<!-- End SDK Installation [installation] -->

<!-- Start Requirements [requirements] -->
## Requirements

For supported JavaScript runtimes, please consult [RUNTIMES.md](RUNTIMES.md).
<!-- End Requirements [requirements] -->

<!-- Start SDK Example Usage [usage] -->
## SDK Example Usage

### Example

```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.admin.adminSetupMonitoring({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    metricsConfig: {
      server: {
        refreshRate: 4397.9,
        port: 8537.41,
        token: "<value>",
        urlCallback: "https://majestic-scratch.org",
        retentionDays: 6999.95,
        cronJob: "<value>",
        thresholds: {
          cpu: 5497.84,
          memory: 6419.22,
        },
      },
      containers: {
        refreshRate: 7401.48,
        services: {},
      },
    },
  });

  console.log(result);
}

run();

```
<!-- End SDK Example Usage [usage] -->

<!-- Start Authentication [security] -->
## Authentication

### Per-Client Security Schemes

This SDK supports the following security scheme globally:

| Name     | Type   | Scheme  | Environment Variable |
| -------- | ------ | ------- | -------------------- |
| `apiKey` | apiKey | API key | `DOKPLOY_API_KEY`    |

To authenticate with the API the `apiKey` parameter must be set when initializing the SDK client instance. For example:


### Per-Operation Security Schemes

Some operations in this SDK require the security scheme to be specified at the request level. For example:
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.admin.adminSetupMonitoring({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    metricsConfig: {
      server: {
        refreshRate: 4397.9,
        port: 8537.41,
        token: "<value>",
        urlCallback: "https://majestic-scratch.org",
        retentionDays: 6999.95,
        cronJob: "<value>",
        thresholds: {
          cpu: 5497.84,
          memory: 6419.22,
        },
      },
      containers: {
        refreshRate: 7401.48,
        services: {},
      },
    },
  });

  console.log(result);
}

run();

```
<!-- End Authentication [security] -->

<!-- Start Available Resources and Operations [operations] -->
## Available Resources and Operations

<details open>
<summary>Available methods</summary>

### [admin](docs/sdks/admin/README.md)

* [adminSetupMonitoring](docs/sdks/admin/README.md#adminsetupmonitoring)

### [ai](docs/sdks/ai/README.md)

* [aiOne](docs/sdks/ai/README.md#aione)
* [aiGetModels](docs/sdks/ai/README.md#aigetmodels)
* [aiCreate](docs/sdks/ai/README.md#aicreate)
* [aiUpdate](docs/sdks/ai/README.md#aiupdate)
* [aiGetAll](docs/sdks/ai/README.md#aigetall)
* [aiGet](docs/sdks/ai/README.md#aiget)
* [aiDelete](docs/sdks/ai/README.md#aidelete)
* [aiSuggest](docs/sdks/ai/README.md#aisuggest)
* [aiDeploy](docs/sdks/ai/README.md#aideploy)

### [application](docs/sdks/application/README.md)

* [applicationCreate](docs/sdks/application/README.md#applicationcreate)
* [applicationOne](docs/sdks/application/README.md#applicationone)
* [applicationReload](docs/sdks/application/README.md#applicationreload)
* [applicationDelete](docs/sdks/application/README.md#applicationdelete)
* [applicationStop](docs/sdks/application/README.md#applicationstop)
* [applicationStart](docs/sdks/application/README.md#applicationstart)
* [applicationRedeploy](docs/sdks/application/README.md#applicationredeploy)
* [applicationSaveEnvironment](docs/sdks/application/README.md#applicationsaveenvironment)
* [applicationSaveBuildType](docs/sdks/application/README.md#applicationsavebuildtype)
* [applicationSaveGithubProvider](docs/sdks/application/README.md#applicationsavegithubprovider)
* [applicationSaveGitlabProvider](docs/sdks/application/README.md#applicationsavegitlabprovider)
* [applicationSaveBitbucketProvider](docs/sdks/application/README.md#applicationsavebitbucketprovider)
* [applicationSaveGiteaProvider](docs/sdks/application/README.md#applicationsavegiteaprovider)
* [applicationSaveDockerProvider](docs/sdks/application/README.md#applicationsavedockerprovider)
* [applicationSaveGitProdiver](docs/sdks/application/README.md#applicationsavegitprodiver)
* [applicationDisconnectGitProvider](docs/sdks/application/README.md#applicationdisconnectgitprovider)
* [applicationMarkRunning](docs/sdks/application/README.md#applicationmarkrunning)
* [applicationUpdate](docs/sdks/application/README.md#applicationupdate)
* [applicationRefreshToken](docs/sdks/application/README.md#applicationrefreshtoken)
* [applicationDeploy](docs/sdks/application/README.md#applicationdeploy)
* [applicationCleanQueues](docs/sdks/application/README.md#applicationcleanqueues)
* [applicationReadTraefikConfig](docs/sdks/application/README.md#applicationreadtraefikconfig)
* [applicationUpdateTraefikConfig](docs/sdks/application/README.md#applicationupdatetraefikconfig)
* [applicationReadAppMonitoring](docs/sdks/application/README.md#applicationreadappmonitoring)
* [applicationMove](docs/sdks/application/README.md#applicationmove)
* [applicationCancelDeployment](docs/sdks/application/README.md#applicationcanceldeployment)

### [backup](docs/sdks/backup/README.md)

* [backupCreate](docs/sdks/backup/README.md#backupcreate)
* [backupOne](docs/sdks/backup/README.md#backupone)
* [backupUpdate](docs/sdks/backup/README.md#backupupdate)
* [backupRemove](docs/sdks/backup/README.md#backupremove)
* [backupManualBackupPostgres](docs/sdks/backup/README.md#backupmanualbackuppostgres)
* [backupManualBackupMySql](docs/sdks/backup/README.md#backupmanualbackupmysql)
* [backupManualBackupMariadb](docs/sdks/backup/README.md#backupmanualbackupmariadb)
* [backupManualBackupCompose](docs/sdks/backup/README.md#backupmanualbackupcompose)
* [backupManualBackupMongo](docs/sdks/backup/README.md#backupmanualbackupmongo)
* [backupManualBackupWebServer](docs/sdks/backup/README.md#backupmanualbackupwebserver)
* [backupListBackupFiles](docs/sdks/backup/README.md#backuplistbackupfiles)

### [bitbucket](docs/sdks/bitbucket/README.md)

* [bitbucketCreate](docs/sdks/bitbucket/README.md#bitbucketcreate)
* [bitbucketOne](docs/sdks/bitbucket/README.md#bitbucketone)
* [bitbucketBitbucketProviders](docs/sdks/bitbucket/README.md#bitbucketbitbucketproviders)
* [bitbucketGetBitbucketRepositories](docs/sdks/bitbucket/README.md#bitbucketgetbitbucketrepositories)
* [bitbucketGetBitbucketBranches](docs/sdks/bitbucket/README.md#bitbucketgetbitbucketbranches)
* [bitbucketTestConnection](docs/sdks/bitbucket/README.md#bitbuckettestconnection)
* [bitbucketUpdate](docs/sdks/bitbucket/README.md#bitbucketupdate)

### [certificates](docs/sdks/certificates/README.md)

* [certificatesCreate](docs/sdks/certificates/README.md#certificatescreate)
* [certificatesOne](docs/sdks/certificates/README.md#certificatesone)
* [certificatesRemove](docs/sdks/certificates/README.md#certificatesremove)
* [certificatesAll](docs/sdks/certificates/README.md#certificatesall)

### [cluster](docs/sdks/cluster/README.md)

* [clusterGetNodes](docs/sdks/cluster/README.md#clustergetnodes)
* [clusterRemoveWorker](docs/sdks/cluster/README.md#clusterremoveworker)
* [clusterAddWorker](docs/sdks/cluster/README.md#clusteraddworker)
* [clusterAddManager](docs/sdks/cluster/README.md#clusteraddmanager)

### [compose](docs/sdks/compose/README.md)

* [composeCreate](docs/sdks/compose/README.md#composecreate)
* [composeOne](docs/sdks/compose/README.md#composeone)
* [composeUpdate](docs/sdks/compose/README.md#composeupdate)
* [composeDelete](docs/sdks/compose/README.md#composedelete)
* [composeCleanQueues](docs/sdks/compose/README.md#composecleanqueues)
* [composeLoadMountsByService](docs/sdks/compose/README.md#composeloadmountsbyservice)
* [composeFetchSourceType](docs/sdks/compose/README.md#composefetchsourcetype)
* [composeRandomizeCompose](docs/sdks/compose/README.md#composerandomizecompose)
* [composeIsolatedDeployment](docs/sdks/compose/README.md#composeisolateddeployment)
* [composeGetConvertedCompose](docs/sdks/compose/README.md#composegetconvertedcompose)
* [composeDeploy](docs/sdks/compose/README.md#composedeploy)
* [composeRedeploy](docs/sdks/compose/README.md#composeredeploy)
* [composeStop](docs/sdks/compose/README.md#composestop)
* [composeStart](docs/sdks/compose/README.md#composestart)
* [composeGetDefaultCommand](docs/sdks/compose/README.md#composegetdefaultcommand)
* [composeRefreshToken](docs/sdks/compose/README.md#composerefreshtoken)
* [composeDeployTemplate](docs/sdks/compose/README.md#composedeploytemplate)
* [composeTemplates](docs/sdks/compose/README.md#composetemplates)
* [composeGetTags](docs/sdks/compose/README.md#composegettags)
* [composeDisconnectGitProvider](docs/sdks/compose/README.md#composedisconnectgitprovider)
* [composeMove](docs/sdks/compose/README.md#composemove)
* [composeProcessTemplate](docs/sdks/compose/README.md#composeprocesstemplate)
* [composeImport](docs/sdks/compose/README.md#composeimport)
* [composeCancelDeployment](docs/sdks/compose/README.md#composecanceldeployment)

### [deployment](docs/sdks/deployment/README.md)

* [deploymentAll](docs/sdks/deployment/README.md#deploymentall)
* [deploymentAllByCompose](docs/sdks/deployment/README.md#deploymentallbycompose)
* [deploymentAllByServer](docs/sdks/deployment/README.md#deploymentallbyserver)
* [deploymentAllByType](docs/sdks/deployment/README.md#deploymentallbytype)
* [deploymentKillProcess](docs/sdks/deployment/README.md#deploymentkillprocess)

### [destination](docs/sdks/destination/README.md)

* [destinationCreate](docs/sdks/destination/README.md#destinationcreate)
* [destinationTestConnection](docs/sdks/destination/README.md#destinationtestconnection)
* [destinationOne](docs/sdks/destination/README.md#destinationone)
* [destinationAll](docs/sdks/destination/README.md#destinationall)
* [destinationRemove](docs/sdks/destination/README.md#destinationremove)
* [destinationUpdate](docs/sdks/destination/README.md#destinationupdate)

### [docker](docs/sdks/docker/README.md)

* [dockerGetContainers](docs/sdks/docker/README.md#dockergetcontainers)
* [dockerRestartContainer](docs/sdks/docker/README.md#dockerrestartcontainer)
* [dockerGetConfig](docs/sdks/docker/README.md#dockergetconfig)
* [dockerGetContainersByAppNameMatch](docs/sdks/docker/README.md#dockergetcontainersbyappnamematch)
* [dockerGetContainersByAppLabel](docs/sdks/docker/README.md#dockergetcontainersbyapplabel)
* [dockerGetStackContainersByAppName](docs/sdks/docker/README.md#dockergetstackcontainersbyappname)
* [dockerGetServiceContainersByAppName](docs/sdks/docker/README.md#dockergetservicecontainersbyappname)


### [domain](docs/sdks/domain/README.md)

* [domainCreate](docs/sdks/domain/README.md#domaincreate)
* [domainByApplicationId](docs/sdks/domain/README.md#domainbyapplicationid)
* [domainByComposeId](docs/sdks/domain/README.md#domainbycomposeid)
* [domainGenerateDomain](docs/sdks/domain/README.md#domaingeneratedomain)
* [domainCanGenerateTraefikMeDomains](docs/sdks/domain/README.md#domaincangeneratetraefikmedomains)
* [domainUpdate](docs/sdks/domain/README.md#domainupdate)
* [domainOne](docs/sdks/domain/README.md#domainone)
* [domainDelete](docs/sdks/domain/README.md#domaindelete)
* [domainValidateDomain](docs/sdks/domain/README.md#domainvalidatedomain)

### [environment](docs/sdks/environment/README.md)

* [environmentCreate](docs/sdks/environment/README.md#environmentcreate)
* [environmentOne](docs/sdks/environment/README.md#environmentone)
* [environmentByProjectId](docs/sdks/environment/README.md#environmentbyprojectid)
* [environmentRemove](docs/sdks/environment/README.md#environmentremove)
* [environmentUpdate](docs/sdks/environment/README.md#environmentupdate)
* [environmentDuplicate](docs/sdks/environment/README.md#environmentduplicate)

### [gitea](docs/sdks/gitea/README.md)

* [giteaCreate](docs/sdks/gitea/README.md#giteacreate)
* [giteaOne](docs/sdks/gitea/README.md#giteaone)
* [giteaGiteaProviders](docs/sdks/gitea/README.md#giteagiteaproviders)
* [giteaGetGiteaRepositories](docs/sdks/gitea/README.md#giteagetgitearepositories)
* [giteaGetGiteaBranches](docs/sdks/gitea/README.md#giteagetgiteabranches)
* [giteaTestConnection](docs/sdks/gitea/README.md#giteatestconnection)
* [giteaUpdate](docs/sdks/gitea/README.md#giteaupdate)
* [giteaGetGiteaUrl](docs/sdks/gitea/README.md#giteagetgiteaurl)

### [github](docs/sdks/github/README.md)

* [githubOne](docs/sdks/github/README.md#githubone)
* [githubGetGithubRepositories](docs/sdks/github/README.md#githubgetgithubrepositories)
* [githubGetGithubBranches](docs/sdks/github/README.md#githubgetgithubbranches)
* [githubGithubProviders](docs/sdks/github/README.md#githubgithubproviders)
* [githubTestConnection](docs/sdks/github/README.md#githubtestconnection)
* [githubUpdate](docs/sdks/github/README.md#githubupdate)

### [gitlab](docs/sdks/gitlab/README.md)

* [gitlabCreate](docs/sdks/gitlab/README.md#gitlabcreate)
* [gitlabOne](docs/sdks/gitlab/README.md#gitlabone)
* [gitlabGitlabProviders](docs/sdks/gitlab/README.md#gitlabgitlabproviders)
* [gitlabGetGitlabRepositories](docs/sdks/gitlab/README.md#gitlabgetgitlabrepositories)
* [gitlabGetGitlabBranches](docs/sdks/gitlab/README.md#gitlabgetgitlabbranches)
* [gitlabTestConnection](docs/sdks/gitlab/README.md#gitlabtestconnection)
* [gitlabUpdate](docs/sdks/gitlab/README.md#gitlabupdate)

### [gitProvider](docs/sdks/gitprovider/README.md)

* [gitProviderGetAll](docs/sdks/gitprovider/README.md#gitprovidergetall)
* [gitProviderRemove](docs/sdks/gitprovider/README.md#gitproviderremove)

### [mariadb](docs/sdks/mariadb/README.md)

* [mariadbCreate](docs/sdks/mariadb/README.md#mariadbcreate)
* [mariadbOne](docs/sdks/mariadb/README.md#mariadbone)
* [mariadbStart](docs/sdks/mariadb/README.md#mariadbstart)
* [mariadbStop](docs/sdks/mariadb/README.md#mariadbstop)
* [mariadbSaveExternalPort](docs/sdks/mariadb/README.md#mariadbsaveexternalport)
* [mariadbDeploy](docs/sdks/mariadb/README.md#mariadbdeploy)
* [mariadbChangeStatus](docs/sdks/mariadb/README.md#mariadbchangestatus)
* [mariadbRemove](docs/sdks/mariadb/README.md#mariadbremove)
* [mariadbSaveEnvironment](docs/sdks/mariadb/README.md#mariadbsaveenvironment)
* [mariadbReload](docs/sdks/mariadb/README.md#mariadbreload)
* [mariadbUpdate](docs/sdks/mariadb/README.md#mariadbupdate)
* [mariadbMove](docs/sdks/mariadb/README.md#mariadbmove)
* [mariadbRebuild](docs/sdks/mariadb/README.md#mariadbrebuild)

### [mongo](docs/sdks/mongo/README.md)

* [mongoCreate](docs/sdks/mongo/README.md#mongocreate)
* [mongoOne](docs/sdks/mongo/README.md#mongoone)
* [mongoStart](docs/sdks/mongo/README.md#mongostart)
* [mongoStop](docs/sdks/mongo/README.md#mongostop)
* [mongoSaveExternalPort](docs/sdks/mongo/README.md#mongosaveexternalport)
* [mongoDeploy](docs/sdks/mongo/README.md#mongodeploy)
* [mongoChangeStatus](docs/sdks/mongo/README.md#mongochangestatus)
* [mongoReload](docs/sdks/mongo/README.md#mongoreload)
* [mongoRemove](docs/sdks/mongo/README.md#mongoremove)
* [mongoSaveEnvironment](docs/sdks/mongo/README.md#mongosaveenvironment)
* [mongoUpdate](docs/sdks/mongo/README.md#mongoupdate)
* [mongoMove](docs/sdks/mongo/README.md#mongomove)
* [mongoRebuild](docs/sdks/mongo/README.md#mongorebuild)

### [mounts](docs/sdks/mounts/README.md)

* [mountsCreate](docs/sdks/mounts/README.md#mountscreate)
* [mountsRemove](docs/sdks/mounts/README.md#mountsremove)
* [mountsOne](docs/sdks/mounts/README.md#mountsone)
* [mountsUpdate](docs/sdks/mounts/README.md#mountsupdate)
* [mountsAllNamedByApplicationId](docs/sdks/mounts/README.md#mountsallnamedbyapplicationid)

### [mysql](docs/sdks/mysql/README.md)

* [mysqlCreate](docs/sdks/mysql/README.md#mysqlcreate)
* [mysqlOne](docs/sdks/mysql/README.md#mysqlone)
* [mysqlStart](docs/sdks/mysql/README.md#mysqlstart)
* [mysqlStop](docs/sdks/mysql/README.md#mysqlstop)
* [mysqlSaveExternalPort](docs/sdks/mysql/README.md#mysqlsaveexternalport)
* [mysqlDeploy](docs/sdks/mysql/README.md#mysqldeploy)
* [mysqlChangeStatus](docs/sdks/mysql/README.md#mysqlchangestatus)
* [mysqlReload](docs/sdks/mysql/README.md#mysqlreload)
* [mysqlRemove](docs/sdks/mysql/README.md#mysqlremove)
* [mysqlSaveEnvironment](docs/sdks/mysql/README.md#mysqlsaveenvironment)
* [mysqlUpdate](docs/sdks/mysql/README.md#mysqlupdate)
* [mysqlMove](docs/sdks/mysql/README.md#mysqlmove)
* [mysqlRebuild](docs/sdks/mysql/README.md#mysqlrebuild)

### [notification](docs/sdks/notification/README.md)

* [notificationCreateSlack](docs/sdks/notification/README.md#notificationcreateslack)
* [notificationUpdateSlack](docs/sdks/notification/README.md#notificationupdateslack)
* [notificationTestSlackConnection](docs/sdks/notification/README.md#notificationtestslackconnection)
* [notificationCreateTelegram](docs/sdks/notification/README.md#notificationcreatetelegram)
* [notificationUpdateTelegram](docs/sdks/notification/README.md#notificationupdatetelegram)
* [notificationTestTelegramConnection](docs/sdks/notification/README.md#notificationtesttelegramconnection)
* [notificationCreateDiscord](docs/sdks/notification/README.md#notificationcreatediscord)
* [notificationUpdateDiscord](docs/sdks/notification/README.md#notificationupdatediscord)
* [notificationTestDiscordConnection](docs/sdks/notification/README.md#notificationtestdiscordconnection)
* [notificationCreateEmail](docs/sdks/notification/README.md#notificationcreateemail)
* [notificationUpdateEmail](docs/sdks/notification/README.md#notificationupdateemail)
* [notificationTestEmailConnection](docs/sdks/notification/README.md#notificationtestemailconnection)
* [notificationRemove](docs/sdks/notification/README.md#notificationremove)
* [notificationOne](docs/sdks/notification/README.md#notificationone)
* [notificationAll](docs/sdks/notification/README.md#notificationall)
* [notificationReceiveNotification](docs/sdks/notification/README.md#notificationreceivenotification)
* [notificationCreateGotify](docs/sdks/notification/README.md#notificationcreategotify)
* [notificationUpdateGotify](docs/sdks/notification/README.md#notificationupdategotify)
* [notificationTestGotifyConnection](docs/sdks/notification/README.md#notificationtestgotifyconnection)
* [notificationCreateNtfy](docs/sdks/notification/README.md#notificationcreatentfy)
* [notificationUpdateNtfy](docs/sdks/notification/README.md#notificationupdatentfy)
* [notificationTestNtfyConnection](docs/sdks/notification/README.md#notificationtestntfyconnection)
* [notificationGetEmailProviders](docs/sdks/notification/README.md#notificationgetemailproviders)

### [organization](docs/sdks/organization/README.md)

* [organizationCreate](docs/sdks/organization/README.md#organizationcreate)
* [organizationAll](docs/sdks/organization/README.md#organizationall)
* [organizationOne](docs/sdks/organization/README.md#organizationone)
* [organizationUpdate](docs/sdks/organization/README.md#organizationupdate)
* [organizationDelete](docs/sdks/organization/README.md#organizationdelete)
* [organizationAllInvitations](docs/sdks/organization/README.md#organizationallinvitations)
* [organizationRemoveInvitation](docs/sdks/organization/README.md#organizationremoveinvitation)

### [port](docs/sdks/port/README.md)

* [portCreate](docs/sdks/port/README.md#portcreate)
* [portOne](docs/sdks/port/README.md#portone)
* [portDelete](docs/sdks/port/README.md#portdelete)
* [portUpdate](docs/sdks/port/README.md#portupdate)

### [postgres](docs/sdks/postgres/README.md)

* [postgresCreate](docs/sdks/postgres/README.md#postgrescreate)
* [postgresOne](docs/sdks/postgres/README.md#postgresone)
* [postgresStart](docs/sdks/postgres/README.md#postgresstart)
* [postgresStop](docs/sdks/postgres/README.md#postgresstop)
* [postgresSaveExternalPort](docs/sdks/postgres/README.md#postgressaveexternalport)
* [postgresDeploy](docs/sdks/postgres/README.md#postgresdeploy)
* [postgresChangeStatus](docs/sdks/postgres/README.md#postgreschangestatus)
* [postgresRemove](docs/sdks/postgres/README.md#postgresremove)
* [postgresSaveEnvironment](docs/sdks/postgres/README.md#postgressaveenvironment)
* [postgresReload](docs/sdks/postgres/README.md#postgresreload)
* [postgresUpdate](docs/sdks/postgres/README.md#postgresupdate)
* [postgresMove](docs/sdks/postgres/README.md#postgresmove)
* [postgresRebuild](docs/sdks/postgres/README.md#postgresrebuild)

### [previewDeployment](docs/sdks/previewdeployment/README.md)

* [previewDeploymentAll](docs/sdks/previewdeployment/README.md#previewdeploymentall)
* [previewDeploymentDelete](docs/sdks/previewdeployment/README.md#previewdeploymentdelete)
* [previewDeploymentOne](docs/sdks/previewdeployment/README.md#previewdeploymentone)

### [project](docs/sdks/project/README.md)

* [projectCreate](docs/sdks/project/README.md#projectcreate)
* [projectOne](docs/sdks/project/README.md#projectone)
* [projectAll](docs/sdks/project/README.md#projectall)
* [projectRemove](docs/sdks/project/README.md#projectremove)
* [projectUpdate](docs/sdks/project/README.md#projectupdate)
* [projectDuplicate](docs/sdks/project/README.md#projectduplicate)

### [redirects](docs/sdks/redirects/README.md)

* [redirectsCreate](docs/sdks/redirects/README.md#redirectscreate)
* [redirectsOne](docs/sdks/redirects/README.md#redirectsone)
* [redirectsDelete](docs/sdks/redirects/README.md#redirectsdelete)
* [redirectsUpdate](docs/sdks/redirects/README.md#redirectsupdate)

### [redis](docs/sdks/redis/README.md)

* [redisCreate](docs/sdks/redis/README.md#rediscreate)
* [redisOne](docs/sdks/redis/README.md#redisone)
* [redisStart](docs/sdks/redis/README.md#redisstart)
* [redisReload](docs/sdks/redis/README.md#redisreload)
* [redisStop](docs/sdks/redis/README.md#redisstop)
* [redisSaveExternalPort](docs/sdks/redis/README.md#redissaveexternalport)
* [redisDeploy](docs/sdks/redis/README.md#redisdeploy)
* [redisChangeStatus](docs/sdks/redis/README.md#redischangestatus)
* [redisRemove](docs/sdks/redis/README.md#redisremove)
* [redisSaveEnvironment](docs/sdks/redis/README.md#redissaveenvironment)
* [redisUpdate](docs/sdks/redis/README.md#redisupdate)
* [redisMove](docs/sdks/redis/README.md#redismove)
* [redisRebuild](docs/sdks/redis/README.md#redisrebuild)

### [registry](docs/sdks/registry/README.md)

* [registryCreate](docs/sdks/registry/README.md#registrycreate)
* [registryRemove](docs/sdks/registry/README.md#registryremove)
* [registryUpdate](docs/sdks/registry/README.md#registryupdate)
* [registryAll](docs/sdks/registry/README.md#registryall)
* [registryOne](docs/sdks/registry/README.md#registryone)
* [registryTestRegistry](docs/sdks/registry/README.md#registrytestregistry)

### [rollback](docs/sdks/rollback/README.md)

* [rollbackDelete](docs/sdks/rollback/README.md#rollbackdelete)
* [rollbackRollback](docs/sdks/rollback/README.md#rollbackrollback)

### [schedule](docs/sdks/schedule/README.md)

* [scheduleCreate](docs/sdks/schedule/README.md#schedulecreate)
* [scheduleUpdate](docs/sdks/schedule/README.md#scheduleupdate)
* [scheduleDelete](docs/sdks/schedule/README.md#scheduledelete)
* [scheduleList](docs/sdks/schedule/README.md#schedulelist)
* [scheduleOne](docs/sdks/schedule/README.md#scheduleone)
* [scheduleRunManually](docs/sdks/schedule/README.md#schedulerunmanually)

### [security](docs/sdks/security/README.md)

* [securityCreate](docs/sdks/security/README.md#securitycreate)
* [securityOne](docs/sdks/security/README.md#securityone)
* [securityDelete](docs/sdks/security/README.md#securitydelete)
* [securityUpdate](docs/sdks/security/README.md#securityupdate)

### [server](docs/sdks/server/README.md)

* [serverCreate](docs/sdks/server/README.md#servercreate)
* [serverOne](docs/sdks/server/README.md#serverone)
* [serverGetDefaultCommand](docs/sdks/server/README.md#servergetdefaultcommand)
* [serverAll](docs/sdks/server/README.md#serverall)
* [serverCount](docs/sdks/server/README.md#servercount)
* [serverWithSSHKey](docs/sdks/server/README.md#serverwithsshkey)
* [serverSetup](docs/sdks/server/README.md#serversetup)
* [serverValidate](docs/sdks/server/README.md#servervalidate)
* [serverSecurity](docs/sdks/server/README.md#serversecurity)
* [serverSetupMonitoring](docs/sdks/server/README.md#serversetupmonitoring)
* [serverRemove](docs/sdks/server/README.md#serverremove)
* [serverUpdate](docs/sdks/server/README.md#serverupdate)
* [serverPublicIp](docs/sdks/server/README.md#serverpublicip)
* [serverGetServerMetrics](docs/sdks/server/README.md#servergetservermetrics)

### [settings](docs/sdks/settings/README.md)

* [settingsReloadServer](docs/sdks/settings/README.md#settingsreloadserver)
* [settingsCleanRedis](docs/sdks/settings/README.md#settingscleanredis)
* [settingsReloadRedis](docs/sdks/settings/README.md#settingsreloadredis)
* [settingsReloadTraefik](docs/sdks/settings/README.md#settingsreloadtraefik)
* [settingsToggleDashboard](docs/sdks/settings/README.md#settingstoggledashboard)
* [settingsCleanUnusedImages](docs/sdks/settings/README.md#settingscleanunusedimages)
* [settingsCleanUnusedVolumes](docs/sdks/settings/README.md#settingscleanunusedvolumes)
* [settingsCleanStoppedContainers](docs/sdks/settings/README.md#settingscleanstoppedcontainers)
* [settingsCleanDockerBuilder](docs/sdks/settings/README.md#settingscleandockerbuilder)
* [settingsCleanDockerPrune](docs/sdks/settings/README.md#settingscleandockerprune)
* [settingsCleanAll](docs/sdks/settings/README.md#settingscleanall)
* [settingsCleanMonitoring](docs/sdks/settings/README.md#settingscleanmonitoring)
* [settingsSaveSSHPrivateKey](docs/sdks/settings/README.md#settingssavesshprivatekey)
* [settingsAssignDomainServer](docs/sdks/settings/README.md#settingsassigndomainserver)
* [settingsCleanSSHPrivateKey](docs/sdks/settings/README.md#settingscleansshprivatekey)
* [settingsUpdateDockerCleanup](docs/sdks/settings/README.md#settingsupdatedockercleanup)
* [settingsReadTraefikConfig](docs/sdks/settings/README.md#settingsreadtraefikconfig)
* [settingsUpdateTraefikConfig](docs/sdks/settings/README.md#settingsupdatetraefikconfig)
* [settingsReadWebServerTraefikConfig](docs/sdks/settings/README.md#settingsreadwebservertraefikconfig)
* [settingsUpdateWebServerTraefikConfig](docs/sdks/settings/README.md#settingsupdatewebservertraefikconfig)
* [settingsReadMiddlewareTraefikConfig](docs/sdks/settings/README.md#settingsreadmiddlewaretraefikconfig)
* [settingsUpdateMiddlewareTraefikConfig](docs/sdks/settings/README.md#settingsupdatemiddlewaretraefikconfig)
* [settingsGetUpdateData](docs/sdks/settings/README.md#settingsgetupdatedata)
* [settingsUpdateServer](docs/sdks/settings/README.md#settingsupdateserver)
* [settingsGetDokployVersion](docs/sdks/settings/README.md#settingsgetdokployversion)
* [settingsGetReleaseTag](docs/sdks/settings/README.md#settingsgetreleasetag)
* [settingsReadDirectories](docs/sdks/settings/README.md#settingsreaddirectories)
* [settingsUpdateTraefikFile](docs/sdks/settings/README.md#settingsupdatetraefikfile)
* [settingsReadTraefikFile](docs/sdks/settings/README.md#settingsreadtraefikfile)
* [settingsGetIp](docs/sdks/settings/README.md#settingsgetip)
* [settingsGetOpenApiDocument](docs/sdks/settings/README.md#settingsgetopenapidocument)
* [settingsReadTraefikEnv](docs/sdks/settings/README.md#settingsreadtraefikenv)
* [settingsWriteTraefikEnv](docs/sdks/settings/README.md#settingswritetraefikenv)
* [settingsHaveTraefikDashboardPortEnabled](docs/sdks/settings/README.md#settingshavetraefikdashboardportenabled)
* [settingsHaveActivateRequests](docs/sdks/settings/README.md#settingshaveactivaterequests)
* [settingsToggleRequests](docs/sdks/settings/README.md#settingstogglerequests)
* [settingsIsCloud](docs/sdks/settings/README.md#settingsiscloud)
* [settingsIsUserSubscribed](docs/sdks/settings/README.md#settingsisusersubscribed)
* [settingsHealth](docs/sdks/settings/README.md#settingshealth)
* [settingsSetupGPU](docs/sdks/settings/README.md#settingssetupgpu)
* [settingsCheckGPUStatus](docs/sdks/settings/README.md#settingscheckgpustatus)
* [settingsUpdateTraefikPorts](docs/sdks/settings/README.md#settingsupdatetraefikports)
* [settingsGetTraefikPorts](docs/sdks/settings/README.md#settingsgettraefikports)
* [settingsUpdateLogCleanup](docs/sdks/settings/README.md#settingsupdatelogcleanup)
* [settingsGetLogCleanupStatus](docs/sdks/settings/README.md#settingsgetlogcleanupstatus)
* [settingsGetDokployCloudIps](docs/sdks/settings/README.md#settingsgetdokploycloudips)

### [sshKey](docs/sdks/sshkey/README.md)

* [sshKeyCreate](docs/sdks/sshkey/README.md#sshkeycreate)
* [sshKeyRemove](docs/sdks/sshkey/README.md#sshkeyremove)
* [sshKeyOne](docs/sdks/sshkey/README.md#sshkeyone)
* [sshKeyAll](docs/sdks/sshkey/README.md#sshkeyall)
* [sshKeyGenerate](docs/sdks/sshkey/README.md#sshkeygenerate)
* [sshKeyUpdate](docs/sdks/sshkey/README.md#sshkeyupdate)

### [stripe](docs/sdks/stripe/README.md)

* [stripeGetProducts](docs/sdks/stripe/README.md#stripegetproducts)
* [stripeCreateCheckoutSession](docs/sdks/stripe/README.md#stripecreatecheckoutsession)
* [stripeCreateCustomerPortalSession](docs/sdks/stripe/README.md#stripecreatecustomerportalsession)
* [stripeCanCreateMoreServers](docs/sdks/stripe/README.md#stripecancreatemoreservers)

### [swarm](docs/sdks/swarm/README.md)

* [swarmGetNodes](docs/sdks/swarm/README.md#swarmgetnodes)
* [swarmGetNodeInfo](docs/sdks/swarm/README.md#swarmgetnodeinfo)
* [swarmGetNodeApps](docs/sdks/swarm/README.md#swarmgetnodeapps)

### [user](docs/sdks/user/README.md)

* [userAll](docs/sdks/user/README.md#userall)
* [userOne](docs/sdks/user/README.md#userone)
* [userGet](docs/sdks/user/README.md#userget)
* [userHaveRootAccess](docs/sdks/user/README.md#userhaverootaccess)
* [userGetBackups](docs/sdks/user/README.md#usergetbackups)
* [userGetServerMetrics](docs/sdks/user/README.md#usergetservermetrics)
* [userUpdate](docs/sdks/user/README.md#userupdate)
* [userGetUserByToken](docs/sdks/user/README.md#usergetuserbytoken)
* [userGetMetricsToken](docs/sdks/user/README.md#usergetmetricstoken)
* [userRemove](docs/sdks/user/README.md#userremove)
* [userAssignPermissions](docs/sdks/user/README.md#userassignpermissions)
* [userGetInvitations](docs/sdks/user/README.md#usergetinvitations)
* [userGetContainerMetrics](docs/sdks/user/README.md#usergetcontainermetrics)
* [userGenerateToken](docs/sdks/user/README.md#usergeneratetoken)
* [userDeleteApiKey](docs/sdks/user/README.md#userdeleteapikey)
* [userCreateApiKey](docs/sdks/user/README.md#usercreateapikey)
* [userCheckUserOrganizations](docs/sdks/user/README.md#usercheckuserorganizations)
* [userSendInvitation](docs/sdks/user/README.md#usersendinvitation)

### [volumeBackups](docs/sdks/volumebackups/README.md)

* [volumeBackupsList](docs/sdks/volumebackups/README.md#volumebackupslist)
* [volumeBackupsCreate](docs/sdks/volumebackups/README.md#volumebackupscreate)
* [volumeBackupsOne](docs/sdks/volumebackups/README.md#volumebackupsone)
* [volumeBackupsDelete](docs/sdks/volumebackups/README.md#volumebackupsdelete)
* [volumeBackupsUpdate](docs/sdks/volumebackups/README.md#volumebackupsupdate)
* [volumeBackupsRunManually](docs/sdks/volumebackups/README.md#volumebackupsrunmanually)

</details>
<!-- End Available Resources and Operations [operations] -->

<!-- Start Standalone functions [standalone-funcs] -->
## Standalone functions

All the methods listed above are available as standalone functions. These
functions are ideal for use in applications running in the browser, serverless
runtimes or other environments where application bundle size is a primary
concern. When using a bundler to build your application, all unused
functionality will be either excluded from the final bundle or tree-shaken away.

To read more about standalone functions, check [FUNCTIONS.md](./FUNCTIONS.md).

<details>

<summary>Available standalone functions</summary>

- [`adminAdminSetupMonitoring`](docs/sdks/admin/README.md#adminsetupmonitoring)
- [`aiAiCreate`](docs/sdks/ai/README.md#aicreate)
- [`aiAiDelete`](docs/sdks/ai/README.md#aidelete)
- [`aiAiDeploy`](docs/sdks/ai/README.md#aideploy)
- [`aiAiGet`](docs/sdks/ai/README.md#aiget)
- [`aiAiGetAll`](docs/sdks/ai/README.md#aigetall)
- [`aiAiGetModels`](docs/sdks/ai/README.md#aigetmodels)
- [`aiAiOne`](docs/sdks/ai/README.md#aione)
- [`aiAiSuggest`](docs/sdks/ai/README.md#aisuggest)
- [`aiAiUpdate`](docs/sdks/ai/README.md#aiupdate)
- [`applicationApplicationCancelDeployment`](docs/sdks/application/README.md#applicationcanceldeployment)
- [`applicationApplicationCleanQueues`](docs/sdks/application/README.md#applicationcleanqueues)
- [`applicationApplicationCreate`](docs/sdks/application/README.md#applicationcreate)
- [`applicationApplicationDelete`](docs/sdks/application/README.md#applicationdelete)
- [`applicationApplicationDeploy`](docs/sdks/application/README.md#applicationdeploy)
- [`applicationApplicationDisconnectGitProvider`](docs/sdks/application/README.md#applicationdisconnectgitprovider)
- [`applicationApplicationMarkRunning`](docs/sdks/application/README.md#applicationmarkrunning)
- [`applicationApplicationMove`](docs/sdks/application/README.md#applicationmove)
- [`applicationApplicationOne`](docs/sdks/application/README.md#applicationone)
- [`applicationApplicationReadAppMonitoring`](docs/sdks/application/README.md#applicationreadappmonitoring)
- [`applicationApplicationReadTraefikConfig`](docs/sdks/application/README.md#applicationreadtraefikconfig)
- [`applicationApplicationRedeploy`](docs/sdks/application/README.md#applicationredeploy)
- [`applicationApplicationRefreshToken`](docs/sdks/application/README.md#applicationrefreshtoken)
- [`applicationApplicationReload`](docs/sdks/application/README.md#applicationreload)
- [`applicationApplicationSaveBitbucketProvider`](docs/sdks/application/README.md#applicationsavebitbucketprovider)
- [`applicationApplicationSaveBuildType`](docs/sdks/application/README.md#applicationsavebuildtype)
- [`applicationApplicationSaveDockerProvider`](docs/sdks/application/README.md#applicationsavedockerprovider)
- [`applicationApplicationSaveEnvironment`](docs/sdks/application/README.md#applicationsaveenvironment)
- [`applicationApplicationSaveGiteaProvider`](docs/sdks/application/README.md#applicationsavegiteaprovider)
- [`applicationApplicationSaveGithubProvider`](docs/sdks/application/README.md#applicationsavegithubprovider)
- [`applicationApplicationSaveGitlabProvider`](docs/sdks/application/README.md#applicationsavegitlabprovider)
- [`applicationApplicationSaveGitProdiver`](docs/sdks/application/README.md#applicationsavegitprodiver)
- [`applicationApplicationStart`](docs/sdks/application/README.md#applicationstart)
- [`applicationApplicationStop`](docs/sdks/application/README.md#applicationstop)
- [`applicationApplicationUpdate`](docs/sdks/application/README.md#applicationupdate)
- [`applicationApplicationUpdateTraefikConfig`](docs/sdks/application/README.md#applicationupdatetraefikconfig)
- [`backupBackupCreate`](docs/sdks/backup/README.md#backupcreate)
- [`backupBackupListBackupFiles`](docs/sdks/backup/README.md#backuplistbackupfiles)
- [`backupBackupManualBackupCompose`](docs/sdks/backup/README.md#backupmanualbackupcompose)
- [`backupBackupManualBackupMariadb`](docs/sdks/backup/README.md#backupmanualbackupmariadb)
- [`backupBackupManualBackupMongo`](docs/sdks/backup/README.md#backupmanualbackupmongo)
- [`backupBackupManualBackupMySql`](docs/sdks/backup/README.md#backupmanualbackupmysql)
- [`backupBackupManualBackupPostgres`](docs/sdks/backup/README.md#backupmanualbackuppostgres)
- [`backupBackupManualBackupWebServer`](docs/sdks/backup/README.md#backupmanualbackupwebserver)
- [`backupBackupOne`](docs/sdks/backup/README.md#backupone)
- [`backupBackupRemove`](docs/sdks/backup/README.md#backupremove)
- [`backupBackupUpdate`](docs/sdks/backup/README.md#backupupdate)
- [`bitbucketBitbucketBitbucketProviders`](docs/sdks/bitbucket/README.md#bitbucketbitbucketproviders)
- [`bitbucketBitbucketCreate`](docs/sdks/bitbucket/README.md#bitbucketcreate)
- [`bitbucketBitbucketGetBitbucketBranches`](docs/sdks/bitbucket/README.md#bitbucketgetbitbucketbranches)
- [`bitbucketBitbucketGetBitbucketRepositories`](docs/sdks/bitbucket/README.md#bitbucketgetbitbucketrepositories)
- [`bitbucketBitbucketOne`](docs/sdks/bitbucket/README.md#bitbucketone)
- [`bitbucketBitbucketTestConnection`](docs/sdks/bitbucket/README.md#bitbuckettestconnection)
- [`bitbucketBitbucketUpdate`](docs/sdks/bitbucket/README.md#bitbucketupdate)
- [`certificatesCertificatesAll`](docs/sdks/certificates/README.md#certificatesall)
- [`certificatesCertificatesCreate`](docs/sdks/certificates/README.md#certificatescreate)
- [`certificatesCertificatesOne`](docs/sdks/certificates/README.md#certificatesone)
- [`certificatesCertificatesRemove`](docs/sdks/certificates/README.md#certificatesremove)
- [`clusterClusterAddManager`](docs/sdks/cluster/README.md#clusteraddmanager)
- [`clusterClusterAddWorker`](docs/sdks/cluster/README.md#clusteraddworker)
- [`clusterClusterGetNodes`](docs/sdks/cluster/README.md#clustergetnodes)
- [`clusterClusterRemoveWorker`](docs/sdks/cluster/README.md#clusterremoveworker)
- [`composeComposeCancelDeployment`](docs/sdks/compose/README.md#composecanceldeployment)
- [`composeComposeCleanQueues`](docs/sdks/compose/README.md#composecleanqueues)
- [`composeComposeCreate`](docs/sdks/compose/README.md#composecreate)
- [`composeComposeDelete`](docs/sdks/compose/README.md#composedelete)
- [`composeComposeDeploy`](docs/sdks/compose/README.md#composedeploy)
- [`composeComposeDeployTemplate`](docs/sdks/compose/README.md#composedeploytemplate)
- [`composeComposeDisconnectGitProvider`](docs/sdks/compose/README.md#composedisconnectgitprovider)
- [`composeComposeFetchSourceType`](docs/sdks/compose/README.md#composefetchsourcetype)
- [`composeComposeGetConvertedCompose`](docs/sdks/compose/README.md#composegetconvertedcompose)
- [`composeComposeGetDefaultCommand`](docs/sdks/compose/README.md#composegetdefaultcommand)
- [`composeComposeGetTags`](docs/sdks/compose/README.md#composegettags)
- [`composeComposeImport`](docs/sdks/compose/README.md#composeimport)
- [`composeComposeIsolatedDeployment`](docs/sdks/compose/README.md#composeisolateddeployment)
- [`composeComposeLoadMountsByService`](docs/sdks/compose/README.md#composeloadmountsbyservice)
- [`composeComposeMove`](docs/sdks/compose/README.md#composemove)
- [`composeComposeOne`](docs/sdks/compose/README.md#composeone)
- [`composeComposeProcessTemplate`](docs/sdks/compose/README.md#composeprocesstemplate)
- [`composeComposeRandomizeCompose`](docs/sdks/compose/README.md#composerandomizecompose)
- [`composeComposeRedeploy`](docs/sdks/compose/README.md#composeredeploy)
- [`composeComposeRefreshToken`](docs/sdks/compose/README.md#composerefreshtoken)
- [`composeComposeStart`](docs/sdks/compose/README.md#composestart)
- [`composeComposeStop`](docs/sdks/compose/README.md#composestop)
- [`composeComposeTemplates`](docs/sdks/compose/README.md#composetemplates)
- [`composeComposeUpdate`](docs/sdks/compose/README.md#composeupdate)
- [`deploymentDeploymentAll`](docs/sdks/deployment/README.md#deploymentall)
- [`deploymentDeploymentAllByCompose`](docs/sdks/deployment/README.md#deploymentallbycompose)
- [`deploymentDeploymentAllByServer`](docs/sdks/deployment/README.md#deploymentallbyserver)
- [`deploymentDeploymentAllByType`](docs/sdks/deployment/README.md#deploymentallbytype)
- [`deploymentDeploymentKillProcess`](docs/sdks/deployment/README.md#deploymentkillprocess)
- [`destinationDestinationAll`](docs/sdks/destination/README.md#destinationall)
- [`destinationDestinationCreate`](docs/sdks/destination/README.md#destinationcreate)
- [`destinationDestinationOne`](docs/sdks/destination/README.md#destinationone)
- [`destinationDestinationRemove`](docs/sdks/destination/README.md#destinationremove)
- [`destinationDestinationTestConnection`](docs/sdks/destination/README.md#destinationtestconnection)
- [`destinationDestinationUpdate`](docs/sdks/destination/README.md#destinationupdate)
- [`dockerDockerGetConfig`](docs/sdks/docker/README.md#dockergetconfig)
- [`dockerDockerGetContainers`](docs/sdks/docker/README.md#dockergetcontainers)
- [`dockerDockerGetContainersByAppLabel`](docs/sdks/docker/README.md#dockergetcontainersbyapplabel)
- [`dockerDockerGetContainersByAppNameMatch`](docs/sdks/docker/README.md#dockergetcontainersbyappnamematch)
- [`dockerDockerGetServiceContainersByAppName`](docs/sdks/docker/README.md#dockergetservicecontainersbyappname)
- [`dockerDockerGetStackContainersByAppName`](docs/sdks/docker/README.md#dockergetstackcontainersbyappname)
- [`dockerDockerRestartContainer`](docs/sdks/docker/README.md#dockerrestartcontainer)
- [`domainDomainByApplicationId`](docs/sdks/domain/README.md#domainbyapplicationid)
- [`domainDomainByComposeId`](docs/sdks/domain/README.md#domainbycomposeid)
- [`domainDomainCanGenerateTraefikMeDomains`](docs/sdks/domain/README.md#domaincangeneratetraefikmedomains)
- [`domainDomainCreate`](docs/sdks/domain/README.md#domaincreate)
- [`domainDomainDelete`](docs/sdks/domain/README.md#domaindelete)
- [`domainDomainGenerateDomain`](docs/sdks/domain/README.md#domaingeneratedomain)
- [`domainDomainOne`](docs/sdks/domain/README.md#domainone)
- [`domainDomainUpdate`](docs/sdks/domain/README.md#domainupdate)
- [`domainDomainValidateDomain`](docs/sdks/domain/README.md#domainvalidatedomain)
- [`environmentEnvironmentByProjectId`](docs/sdks/environment/README.md#environmentbyprojectid)
- [`environmentEnvironmentCreate`](docs/sdks/environment/README.md#environmentcreate)
- [`environmentEnvironmentDuplicate`](docs/sdks/environment/README.md#environmentduplicate)
- [`environmentEnvironmentOne`](docs/sdks/environment/README.md#environmentone)
- [`environmentEnvironmentRemove`](docs/sdks/environment/README.md#environmentremove)
- [`environmentEnvironmentUpdate`](docs/sdks/environment/README.md#environmentupdate)
- [`giteaGiteaCreate`](docs/sdks/gitea/README.md#giteacreate)
- [`giteaGiteaGetGiteaBranches`](docs/sdks/gitea/README.md#giteagetgiteabranches)
- [`giteaGiteaGetGiteaRepositories`](docs/sdks/gitea/README.md#giteagetgitearepositories)
- [`giteaGiteaGetGiteaUrl`](docs/sdks/gitea/README.md#giteagetgiteaurl)
- [`giteaGiteaGiteaProviders`](docs/sdks/gitea/README.md#giteagiteaproviders)
- [`giteaGiteaOne`](docs/sdks/gitea/README.md#giteaone)
- [`giteaGiteaTestConnection`](docs/sdks/gitea/README.md#giteatestconnection)
- [`giteaGiteaUpdate`](docs/sdks/gitea/README.md#giteaupdate)
- [`githubGithubGetGithubBranches`](docs/sdks/github/README.md#githubgetgithubbranches)
- [`githubGithubGetGithubRepositories`](docs/sdks/github/README.md#githubgetgithubrepositories)
- [`githubGithubGithubProviders`](docs/sdks/github/README.md#githubgithubproviders)
- [`githubGithubOne`](docs/sdks/github/README.md#githubone)
- [`githubGithubTestConnection`](docs/sdks/github/README.md#githubtestconnection)
- [`githubGithubUpdate`](docs/sdks/github/README.md#githubupdate)
- [`gitlabGitlabCreate`](docs/sdks/gitlab/README.md#gitlabcreate)
- [`gitlabGitlabGetGitlabBranches`](docs/sdks/gitlab/README.md#gitlabgetgitlabbranches)
- [`gitlabGitlabGetGitlabRepositories`](docs/sdks/gitlab/README.md#gitlabgetgitlabrepositories)
- [`gitlabGitlabGitlabProviders`](docs/sdks/gitlab/README.md#gitlabgitlabproviders)
- [`gitlabGitlabOne`](docs/sdks/gitlab/README.md#gitlabone)
- [`gitlabGitlabTestConnection`](docs/sdks/gitlab/README.md#gitlabtestconnection)
- [`gitlabGitlabUpdate`](docs/sdks/gitlab/README.md#gitlabupdate)
- [`gitProviderGitProviderGetAll`](docs/sdks/gitprovider/README.md#gitprovidergetall)
- [`gitProviderGitProviderRemove`](docs/sdks/gitprovider/README.md#gitproviderremove)
- [`mariadbMariadbChangeStatus`](docs/sdks/mariadb/README.md#mariadbchangestatus)
- [`mariadbMariadbCreate`](docs/sdks/mariadb/README.md#mariadbcreate)
- [`mariadbMariadbDeploy`](docs/sdks/mariadb/README.md#mariadbdeploy)
- [`mariadbMariadbMove`](docs/sdks/mariadb/README.md#mariadbmove)
- [`mariadbMariadbOne`](docs/sdks/mariadb/README.md#mariadbone)
- [`mariadbMariadbRebuild`](docs/sdks/mariadb/README.md#mariadbrebuild)
- [`mariadbMariadbReload`](docs/sdks/mariadb/README.md#mariadbreload)
- [`mariadbMariadbRemove`](docs/sdks/mariadb/README.md#mariadbremove)
- [`mariadbMariadbSaveEnvironment`](docs/sdks/mariadb/README.md#mariadbsaveenvironment)
- [`mariadbMariadbSaveExternalPort`](docs/sdks/mariadb/README.md#mariadbsaveexternalport)
- [`mariadbMariadbStart`](docs/sdks/mariadb/README.md#mariadbstart)
- [`mariadbMariadbStop`](docs/sdks/mariadb/README.md#mariadbstop)
- [`mariadbMariadbUpdate`](docs/sdks/mariadb/README.md#mariadbupdate)
- [`mongoMongoChangeStatus`](docs/sdks/mongo/README.md#mongochangestatus)
- [`mongoMongoCreate`](docs/sdks/mongo/README.md#mongocreate)
- [`mongoMongoDeploy`](docs/sdks/mongo/README.md#mongodeploy)
- [`mongoMongoMove`](docs/sdks/mongo/README.md#mongomove)
- [`mongoMongoOne`](docs/sdks/mongo/README.md#mongoone)
- [`mongoMongoRebuild`](docs/sdks/mongo/README.md#mongorebuild)
- [`mongoMongoReload`](docs/sdks/mongo/README.md#mongoreload)
- [`mongoMongoRemove`](docs/sdks/mongo/README.md#mongoremove)
- [`mongoMongoSaveEnvironment`](docs/sdks/mongo/README.md#mongosaveenvironment)
- [`mongoMongoSaveExternalPort`](docs/sdks/mongo/README.md#mongosaveexternalport)
- [`mongoMongoStart`](docs/sdks/mongo/README.md#mongostart)
- [`mongoMongoStop`](docs/sdks/mongo/README.md#mongostop)
- [`mongoMongoUpdate`](docs/sdks/mongo/README.md#mongoupdate)
- [`mountsMountsAllNamedByApplicationId`](docs/sdks/mounts/README.md#mountsallnamedbyapplicationid)
- [`mountsMountsCreate`](docs/sdks/mounts/README.md#mountscreate)
- [`mountsMountsOne`](docs/sdks/mounts/README.md#mountsone)
- [`mountsMountsRemove`](docs/sdks/mounts/README.md#mountsremove)
- [`mountsMountsUpdate`](docs/sdks/mounts/README.md#mountsupdate)
- [`mysqlMysqlChangeStatus`](docs/sdks/mysql/README.md#mysqlchangestatus)
- [`mysqlMysqlCreate`](docs/sdks/mysql/README.md#mysqlcreate)
- [`mysqlMysqlDeploy`](docs/sdks/mysql/README.md#mysqldeploy)
- [`mysqlMysqlMove`](docs/sdks/mysql/README.md#mysqlmove)
- [`mysqlMysqlOne`](docs/sdks/mysql/README.md#mysqlone)
- [`mysqlMysqlRebuild`](docs/sdks/mysql/README.md#mysqlrebuild)
- [`mysqlMysqlReload`](docs/sdks/mysql/README.md#mysqlreload)
- [`mysqlMysqlRemove`](docs/sdks/mysql/README.md#mysqlremove)
- [`mysqlMysqlSaveEnvironment`](docs/sdks/mysql/README.md#mysqlsaveenvironment)
- [`mysqlMysqlSaveExternalPort`](docs/sdks/mysql/README.md#mysqlsaveexternalport)
- [`mysqlMysqlStart`](docs/sdks/mysql/README.md#mysqlstart)
- [`mysqlMysqlStop`](docs/sdks/mysql/README.md#mysqlstop)
- [`mysqlMysqlUpdate`](docs/sdks/mysql/README.md#mysqlupdate)
- [`notificationNotificationAll`](docs/sdks/notification/README.md#notificationall)
- [`notificationNotificationCreateDiscord`](docs/sdks/notification/README.md#notificationcreatediscord)
- [`notificationNotificationCreateEmail`](docs/sdks/notification/README.md#notificationcreateemail)
- [`notificationNotificationCreateGotify`](docs/sdks/notification/README.md#notificationcreategotify)
- [`notificationNotificationCreateNtfy`](docs/sdks/notification/README.md#notificationcreatentfy)
- [`notificationNotificationCreateSlack`](docs/sdks/notification/README.md#notificationcreateslack)
- [`notificationNotificationCreateTelegram`](docs/sdks/notification/README.md#notificationcreatetelegram)
- [`notificationNotificationGetEmailProviders`](docs/sdks/notification/README.md#notificationgetemailproviders)
- [`notificationNotificationOne`](docs/sdks/notification/README.md#notificationone)
- [`notificationNotificationReceiveNotification`](docs/sdks/notification/README.md#notificationreceivenotification)
- [`notificationNotificationRemove`](docs/sdks/notification/README.md#notificationremove)
- [`notificationNotificationTestDiscordConnection`](docs/sdks/notification/README.md#notificationtestdiscordconnection)
- [`notificationNotificationTestEmailConnection`](docs/sdks/notification/README.md#notificationtestemailconnection)
- [`notificationNotificationTestGotifyConnection`](docs/sdks/notification/README.md#notificationtestgotifyconnection)
- [`notificationNotificationTestNtfyConnection`](docs/sdks/notification/README.md#notificationtestntfyconnection)
- [`notificationNotificationTestSlackConnection`](docs/sdks/notification/README.md#notificationtestslackconnection)
- [`notificationNotificationTestTelegramConnection`](docs/sdks/notification/README.md#notificationtesttelegramconnection)
- [`notificationNotificationUpdateDiscord`](docs/sdks/notification/README.md#notificationupdatediscord)
- [`notificationNotificationUpdateEmail`](docs/sdks/notification/README.md#notificationupdateemail)
- [`notificationNotificationUpdateGotify`](docs/sdks/notification/README.md#notificationupdategotify)
- [`notificationNotificationUpdateNtfy`](docs/sdks/notification/README.md#notificationupdatentfy)
- [`notificationNotificationUpdateSlack`](docs/sdks/notification/README.md#notificationupdateslack)
- [`notificationNotificationUpdateTelegram`](docs/sdks/notification/README.md#notificationupdatetelegram)
- [`organizationOrganizationAll`](docs/sdks/organization/README.md#organizationall)
- [`organizationOrganizationAllInvitations`](docs/sdks/organization/README.md#organizationallinvitations)
- [`organizationOrganizationCreate`](docs/sdks/organization/README.md#organizationcreate)
- [`organizationOrganizationDelete`](docs/sdks/organization/README.md#organizationdelete)
- [`organizationOrganizationOne`](docs/sdks/organization/README.md#organizationone)
- [`organizationOrganizationRemoveInvitation`](docs/sdks/organization/README.md#organizationremoveinvitation)
- [`organizationOrganizationUpdate`](docs/sdks/organization/README.md#organizationupdate)
- [`portPortCreate`](docs/sdks/port/README.md#portcreate)
- [`portPortDelete`](docs/sdks/port/README.md#portdelete)
- [`portPortOne`](docs/sdks/port/README.md#portone)
- [`portPortUpdate`](docs/sdks/port/README.md#portupdate)
- [`postgresPostgresChangeStatus`](docs/sdks/postgres/README.md#postgreschangestatus)
- [`postgresPostgresCreate`](docs/sdks/postgres/README.md#postgrescreate)
- [`postgresPostgresDeploy`](docs/sdks/postgres/README.md#postgresdeploy)
- [`postgresPostgresMove`](docs/sdks/postgres/README.md#postgresmove)
- [`postgresPostgresOne`](docs/sdks/postgres/README.md#postgresone)
- [`postgresPostgresRebuild`](docs/sdks/postgres/README.md#postgresrebuild)
- [`postgresPostgresReload`](docs/sdks/postgres/README.md#postgresreload)
- [`postgresPostgresRemove`](docs/sdks/postgres/README.md#postgresremove)
- [`postgresPostgresSaveEnvironment`](docs/sdks/postgres/README.md#postgressaveenvironment)
- [`postgresPostgresSaveExternalPort`](docs/sdks/postgres/README.md#postgressaveexternalport)
- [`postgresPostgresStart`](docs/sdks/postgres/README.md#postgresstart)
- [`postgresPostgresStop`](docs/sdks/postgres/README.md#postgresstop)
- [`postgresPostgresUpdate`](docs/sdks/postgres/README.md#postgresupdate)
- [`previewDeploymentPreviewDeploymentAll`](docs/sdks/previewdeployment/README.md#previewdeploymentall)
- [`previewDeploymentPreviewDeploymentDelete`](docs/sdks/previewdeployment/README.md#previewdeploymentdelete)
- [`previewDeploymentPreviewDeploymentOne`](docs/sdks/previewdeployment/README.md#previewdeploymentone)
- [`projectProjectAll`](docs/sdks/project/README.md#projectall)
- [`projectProjectCreate`](docs/sdks/project/README.md#projectcreate)
- [`projectProjectDuplicate`](docs/sdks/project/README.md#projectduplicate)
- [`projectProjectOne`](docs/sdks/project/README.md#projectone)
- [`projectProjectRemove`](docs/sdks/project/README.md#projectremove)
- [`projectProjectUpdate`](docs/sdks/project/README.md#projectupdate)
- [`redirectsRedirectsCreate`](docs/sdks/redirects/README.md#redirectscreate)
- [`redirectsRedirectsDelete`](docs/sdks/redirects/README.md#redirectsdelete)
- [`redirectsRedirectsOne`](docs/sdks/redirects/README.md#redirectsone)
- [`redirectsRedirectsUpdate`](docs/sdks/redirects/README.md#redirectsupdate)
- [`redisRedisChangeStatus`](docs/sdks/redis/README.md#redischangestatus)
- [`redisRedisCreate`](docs/sdks/redis/README.md#rediscreate)
- [`redisRedisDeploy`](docs/sdks/redis/README.md#redisdeploy)
- [`redisRedisMove`](docs/sdks/redis/README.md#redismove)
- [`redisRedisOne`](docs/sdks/redis/README.md#redisone)
- [`redisRedisRebuild`](docs/sdks/redis/README.md#redisrebuild)
- [`redisRedisReload`](docs/sdks/redis/README.md#redisreload)
- [`redisRedisRemove`](docs/sdks/redis/README.md#redisremove)
- [`redisRedisSaveEnvironment`](docs/sdks/redis/README.md#redissaveenvironment)
- [`redisRedisSaveExternalPort`](docs/sdks/redis/README.md#redissaveexternalport)
- [`redisRedisStart`](docs/sdks/redis/README.md#redisstart)
- [`redisRedisStop`](docs/sdks/redis/README.md#redisstop)
- [`redisRedisUpdate`](docs/sdks/redis/README.md#redisupdate)
- [`registryRegistryAll`](docs/sdks/registry/README.md#registryall)
- [`registryRegistryCreate`](docs/sdks/registry/README.md#registrycreate)
- [`registryRegistryOne`](docs/sdks/registry/README.md#registryone)
- [`registryRegistryRemove`](docs/sdks/registry/README.md#registryremove)
- [`registryRegistryTestRegistry`](docs/sdks/registry/README.md#registrytestregistry)
- [`registryRegistryUpdate`](docs/sdks/registry/README.md#registryupdate)
- [`rollbackRollbackDelete`](docs/sdks/rollback/README.md#rollbackdelete)
- [`rollbackRollbackRollback`](docs/sdks/rollback/README.md#rollbackrollback)
- [`scheduleScheduleCreate`](docs/sdks/schedule/README.md#schedulecreate)
- [`scheduleScheduleDelete`](docs/sdks/schedule/README.md#scheduledelete)
- [`scheduleScheduleList`](docs/sdks/schedule/README.md#schedulelist)
- [`scheduleScheduleOne`](docs/sdks/schedule/README.md#scheduleone)
- [`scheduleScheduleRunManually`](docs/sdks/schedule/README.md#schedulerunmanually)
- [`scheduleScheduleUpdate`](docs/sdks/schedule/README.md#scheduleupdate)
- [`securitySecurityCreate`](docs/sdks/security/README.md#securitycreate)
- [`securitySecurityDelete`](docs/sdks/security/README.md#securitydelete)
- [`securitySecurityOne`](docs/sdks/security/README.md#securityone)
- [`securitySecurityUpdate`](docs/sdks/security/README.md#securityupdate)
- [`serverServerAll`](docs/sdks/server/README.md#serverall)
- [`serverServerCount`](docs/sdks/server/README.md#servercount)
- [`serverServerCreate`](docs/sdks/server/README.md#servercreate)
- [`serverServerGetDefaultCommand`](docs/sdks/server/README.md#servergetdefaultcommand)
- [`serverServerGetServerMetrics`](docs/sdks/server/README.md#servergetservermetrics)
- [`serverServerOne`](docs/sdks/server/README.md#serverone)
- [`serverServerPublicIp`](docs/sdks/server/README.md#serverpublicip)
- [`serverServerRemove`](docs/sdks/server/README.md#serverremove)
- [`serverServerSecurity`](docs/sdks/server/README.md#serversecurity)
- [`serverServerSetup`](docs/sdks/server/README.md#serversetup)
- [`serverServerSetupMonitoring`](docs/sdks/server/README.md#serversetupmonitoring)
- [`serverServerUpdate`](docs/sdks/server/README.md#serverupdate)
- [`serverServerValidate`](docs/sdks/server/README.md#servervalidate)
- [`serverServerWithSSHKey`](docs/sdks/server/README.md#serverwithsshkey)
- [`settingsSettingsAssignDomainServer`](docs/sdks/settings/README.md#settingsassigndomainserver)
- [`settingsSettingsCheckGPUStatus`](docs/sdks/settings/README.md#settingscheckgpustatus)
- [`settingsSettingsCleanAll`](docs/sdks/settings/README.md#settingscleanall)
- [`settingsSettingsCleanDockerBuilder`](docs/sdks/settings/README.md#settingscleandockerbuilder)
- [`settingsSettingsCleanDockerPrune`](docs/sdks/settings/README.md#settingscleandockerprune)
- [`settingsSettingsCleanMonitoring`](docs/sdks/settings/README.md#settingscleanmonitoring)
- [`settingsSettingsCleanRedis`](docs/sdks/settings/README.md#settingscleanredis)
- [`settingsSettingsCleanSSHPrivateKey`](docs/sdks/settings/README.md#settingscleansshprivatekey)
- [`settingsSettingsCleanStoppedContainers`](docs/sdks/settings/README.md#settingscleanstoppedcontainers)
- [`settingsSettingsCleanUnusedImages`](docs/sdks/settings/README.md#settingscleanunusedimages)
- [`settingsSettingsCleanUnusedVolumes`](docs/sdks/settings/README.md#settingscleanunusedvolumes)
- [`settingsSettingsGetDokployCloudIps`](docs/sdks/settings/README.md#settingsgetdokploycloudips)
- [`settingsSettingsGetDokployVersion`](docs/sdks/settings/README.md#settingsgetdokployversion)
- [`settingsSettingsGetIp`](docs/sdks/settings/README.md#settingsgetip)
- [`settingsSettingsGetLogCleanupStatus`](docs/sdks/settings/README.md#settingsgetlogcleanupstatus)
- [`settingsSettingsGetOpenApiDocument`](docs/sdks/settings/README.md#settingsgetopenapidocument)
- [`settingsSettingsGetReleaseTag`](docs/sdks/settings/README.md#settingsgetreleasetag)
- [`settingsSettingsGetTraefikPorts`](docs/sdks/settings/README.md#settingsgettraefikports)
- [`settingsSettingsGetUpdateData`](docs/sdks/settings/README.md#settingsgetupdatedata)
- [`settingsSettingsHaveActivateRequests`](docs/sdks/settings/README.md#settingshaveactivaterequests)
- [`settingsSettingsHaveTraefikDashboardPortEnabled`](docs/sdks/settings/README.md#settingshavetraefikdashboardportenabled)
- [`settingsSettingsHealth`](docs/sdks/settings/README.md#settingshealth)
- [`settingsSettingsIsCloud`](docs/sdks/settings/README.md#settingsiscloud)
- [`settingsSettingsIsUserSubscribed`](docs/sdks/settings/README.md#settingsisusersubscribed)
- [`settingsSettingsReadDirectories`](docs/sdks/settings/README.md#settingsreaddirectories)
- [`settingsSettingsReadMiddlewareTraefikConfig`](docs/sdks/settings/README.md#settingsreadmiddlewaretraefikconfig)
- [`settingsSettingsReadTraefikConfig`](docs/sdks/settings/README.md#settingsreadtraefikconfig)
- [`settingsSettingsReadTraefikEnv`](docs/sdks/settings/README.md#settingsreadtraefikenv)
- [`settingsSettingsReadTraefikFile`](docs/sdks/settings/README.md#settingsreadtraefikfile)
- [`settingsSettingsReadWebServerTraefikConfig`](docs/sdks/settings/README.md#settingsreadwebservertraefikconfig)
- [`settingsSettingsReloadRedis`](docs/sdks/settings/README.md#settingsreloadredis)
- [`settingsSettingsReloadServer`](docs/sdks/settings/README.md#settingsreloadserver)
- [`settingsSettingsReloadTraefik`](docs/sdks/settings/README.md#settingsreloadtraefik)
- [`settingsSettingsSaveSSHPrivateKey`](docs/sdks/settings/README.md#settingssavesshprivatekey)
- [`settingsSettingsSetupGPU`](docs/sdks/settings/README.md#settingssetupgpu)
- [`settingsSettingsToggleDashboard`](docs/sdks/settings/README.md#settingstoggledashboard)
- [`settingsSettingsToggleRequests`](docs/sdks/settings/README.md#settingstogglerequests)
- [`settingsSettingsUpdateDockerCleanup`](docs/sdks/settings/README.md#settingsupdatedockercleanup)
- [`settingsSettingsUpdateLogCleanup`](docs/sdks/settings/README.md#settingsupdatelogcleanup)
- [`settingsSettingsUpdateMiddlewareTraefikConfig`](docs/sdks/settings/README.md#settingsupdatemiddlewaretraefikconfig)
- [`settingsSettingsUpdateServer`](docs/sdks/settings/README.md#settingsupdateserver)
- [`settingsSettingsUpdateTraefikConfig`](docs/sdks/settings/README.md#settingsupdatetraefikconfig)
- [`settingsSettingsUpdateTraefikFile`](docs/sdks/settings/README.md#settingsupdatetraefikfile)
- [`settingsSettingsUpdateTraefikPorts`](docs/sdks/settings/README.md#settingsupdatetraefikports)
- [`settingsSettingsUpdateWebServerTraefikConfig`](docs/sdks/settings/README.md#settingsupdatewebservertraefikconfig)
- [`settingsSettingsWriteTraefikEnv`](docs/sdks/settings/README.md#settingswritetraefikenv)
- [`sshKeySshKeyAll`](docs/sdks/sshkey/README.md#sshkeyall)
- [`sshKeySshKeyCreate`](docs/sdks/sshkey/README.md#sshkeycreate)
- [`sshKeySshKeyGenerate`](docs/sdks/sshkey/README.md#sshkeygenerate)
- [`sshKeySshKeyOne`](docs/sdks/sshkey/README.md#sshkeyone)
- [`sshKeySshKeyRemove`](docs/sdks/sshkey/README.md#sshkeyremove)
- [`sshKeySshKeyUpdate`](docs/sdks/sshkey/README.md#sshkeyupdate)
- [`stripeStripeCanCreateMoreServers`](docs/sdks/stripe/README.md#stripecancreatemoreservers)
- [`stripeStripeCreateCheckoutSession`](docs/sdks/stripe/README.md#stripecreatecheckoutsession)
- [`stripeStripeCreateCustomerPortalSession`](docs/sdks/stripe/README.md#stripecreatecustomerportalsession)
- [`stripeStripeGetProducts`](docs/sdks/stripe/README.md#stripegetproducts)
- [`swarmSwarmGetNodeApps`](docs/sdks/swarm/README.md#swarmgetnodeapps)
- [`swarmSwarmGetNodeInfo`](docs/sdks/swarm/README.md#swarmgetnodeinfo)
- [`swarmSwarmGetNodes`](docs/sdks/swarm/README.md#swarmgetnodes)
- [`userUserAll`](docs/sdks/user/README.md#userall)
- [`userUserAssignPermissions`](docs/sdks/user/README.md#userassignpermissions)
- [`userUserCheckUserOrganizations`](docs/sdks/user/README.md#usercheckuserorganizations)
- [`userUserCreateApiKey`](docs/sdks/user/README.md#usercreateapikey)
- [`userUserDeleteApiKey`](docs/sdks/user/README.md#userdeleteapikey)
- [`userUserGenerateToken`](docs/sdks/user/README.md#usergeneratetoken)
- [`userUserGet`](docs/sdks/user/README.md#userget)
- [`userUserGetBackups`](docs/sdks/user/README.md#usergetbackups)
- [`userUserGetContainerMetrics`](docs/sdks/user/README.md#usergetcontainermetrics)
- [`userUserGetInvitations`](docs/sdks/user/README.md#usergetinvitations)
- [`userUserGetMetricsToken`](docs/sdks/user/README.md#usergetmetricstoken)
- [`userUserGetServerMetrics`](docs/sdks/user/README.md#usergetservermetrics)
- [`userUserGetUserByToken`](docs/sdks/user/README.md#usergetuserbytoken)
- [`userUserHaveRootAccess`](docs/sdks/user/README.md#userhaverootaccess)
- [`userUserOne`](docs/sdks/user/README.md#userone)
- [`userUserRemove`](docs/sdks/user/README.md#userremove)
- [`userUserSendInvitation`](docs/sdks/user/README.md#usersendinvitation)
- [`userUserUpdate`](docs/sdks/user/README.md#userupdate)
- [`volumeBackupsVolumeBackupsCreate`](docs/sdks/volumebackups/README.md#volumebackupscreate)
- [`volumeBackupsVolumeBackupsDelete`](docs/sdks/volumebackups/README.md#volumebackupsdelete)
- [`volumeBackupsVolumeBackupsList`](docs/sdks/volumebackups/README.md#volumebackupslist)
- [`volumeBackupsVolumeBackupsOne`](docs/sdks/volumebackups/README.md#volumebackupsone)
- [`volumeBackupsVolumeBackupsRunManually`](docs/sdks/volumebackups/README.md#volumebackupsrunmanually)
- [`volumeBackupsVolumeBackupsUpdate`](docs/sdks/volumebackups/README.md#volumebackupsupdate)

</details>
<!-- End Standalone functions [standalone-funcs] -->

<!-- Start Retries [retries] -->
## Retries

Some of the endpoints in this SDK support retries.  If you use the SDK without any configuration, it will fall back to the default retry strategy provided by the API.  However, the default retry strategy can be overridden on a per-operation basis, or across the entire SDK.

To change the default retry strategy for a single API call, simply provide a retryConfig object to the call:
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.admin.adminSetupMonitoring({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    metricsConfig: {
      server: {
        refreshRate: 4397.9,
        port: 8537.41,
        token: "<value>",
        urlCallback: "https://majestic-scratch.org",
        retentionDays: 6999.95,
        cronJob: "<value>",
        thresholds: {
          cpu: 5497.84,
          memory: 6419.22,
        },
      },
      containers: {
        refreshRate: 7401.48,
        services: {},
      },
    },
  }, {
    retries: {
      strategy: "backoff",
      backoff: {
        initialInterval: 1,
        maxInterval: 50,
        exponent: 1.1,
        maxElapsedTime: 100,
      },
      retryConnectionErrors: false,
    },
  });

  console.log(result);
}

run();

```

If you'd like to override the default retry strategy for all operations that support retries, you can provide a retryConfig at SDK initialization:
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy({
  retryConfig: {
    strategy: "backoff",
    backoff: {
      initialInterval: 1,
      maxInterval: 50,
      exponent: 1.1,
      maxElapsedTime: 100,
    },
    retryConnectionErrors: false,
  },
});

async function run() {
  const result = await dokploy.admin.adminSetupMonitoring({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    metricsConfig: {
      server: {
        refreshRate: 4397.9,
        port: 8537.41,
        token: "<value>",
        urlCallback: "https://majestic-scratch.org",
        retentionDays: 6999.95,
        cronJob: "<value>",
        thresholds: {
          cpu: 5497.84,
          memory: 6419.22,
        },
      },
      containers: {
        refreshRate: 7401.48,
        services: {},
      },
    },
  });

  console.log(result);
}

run();

```
<!-- End Retries [retries] -->

<!-- Start Error Handling [errors] -->
## Error Handling

[`DokployError`](./src/models/errors/dokployerror.ts) is the base class for all HTTP error responses. It has the following properties:

| Property            | Type       | Description                                            |
| ------------------- | ---------- | ------------------------------------------------------ |
| `error.message`     | `string`   | Error message                                          |
| `error.statusCode`  | `number`   | HTTP response status code eg `404`                     |
| `error.headers`     | `Headers`  | HTTP response headers                                  |
| `error.body`        | `string`   | HTTP body. Can be empty string if no body is returned. |
| `error.rawResponse` | `Response` | Raw HTTP response                                      |

### Example
```typescript
import { Dokploy } from "dokploy-sdk";
import * as errors from "dokploy-sdk/models/errors";

const dokploy = new Dokploy();

async function run() {
  try {
    const result = await dokploy.admin.adminSetupMonitoring({
      authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
    }, {
      metricsConfig: {
        server: {
          refreshRate: 4397.9,
          port: 8537.41,
          token: "<value>",
          urlCallback: "https://majestic-scratch.org",
          retentionDays: 6999.95,
          cronJob: "<value>",
          thresholds: {
            cpu: 5497.84,
            memory: 6419.22,
          },
        },
        containers: {
          refreshRate: 7401.48,
          services: {},
        },
      },
    });

    console.log(result);
  } catch (error) {
    if (error instanceof errors.DokployError) {
      console.log(error.message);
      console.log(error.statusCode);
      console.log(error.body);
      console.log(error.headers);
    }
  }
}

run();

```

### Error Classes
**Primary error:**
* [`DokployError`](./src/models/errors/dokployerror.ts): The base class for HTTP error responses.

<details><summary>Less common errors (6)</summary>

<br />

**Network errors:**
* [`ConnectionError`](./src/models/errors/httpclienterrors.ts): HTTP client was unable to make a request to a server.
* [`RequestTimeoutError`](./src/models/errors/httpclienterrors.ts): HTTP request timed out due to an AbortSignal signal.
* [`RequestAbortedError`](./src/models/errors/httpclienterrors.ts): HTTP request was aborted by the client.
* [`InvalidRequestError`](./src/models/errors/httpclienterrors.ts): Any input used to create a request is invalid.
* [`UnexpectedClientError`](./src/models/errors/httpclienterrors.ts): Unrecognised or unexpected error.


**Inherit from [`DokployError`](./src/models/errors/dokployerror.ts)**:
* [`ResponseValidationError`](./src/models/errors/responsevalidationerror.ts): Type mismatch between the data returned from the server and the structure expected by the SDK. See `error.rawValue` for the raw value and `error.pretty()` for a nicely formatted multi-line string.

</details>
<!-- End Error Handling [errors] -->

<!-- Start Server Selection [server] -->
## Server Selection

### Override Server URL Per-Client

The default server can be overridden globally by passing a URL to the `serverURL: string` optional parameter when initializing the SDK client instance. For example:
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy({
  serverURL: "http://localhost:3000/api",
});

async function run() {
  const result = await dokploy.admin.adminSetupMonitoring({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    metricsConfig: {
      server: {
        refreshRate: 4397.9,
        port: 8537.41,
        token: "<value>",
        urlCallback: "https://majestic-scratch.org",
        retentionDays: 6999.95,
        cronJob: "<value>",
        thresholds: {
          cpu: 5497.84,
          memory: 6419.22,
        },
      },
      containers: {
        refreshRate: 7401.48,
        services: {},
      },
    },
  });

  console.log(result);
}

run();

```
<!-- End Server Selection [server] -->

<!-- Start Custom HTTP Client [http-client] -->
## Custom HTTP Client

The TypeScript SDK makes API calls using an `HTTPClient` that wraps the native
[Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API). This
client is a thin wrapper around `fetch` and provides the ability to attach hooks
around the request lifecycle that can be used to modify the request or handle
errors and response.

The `HTTPClient` constructor takes an optional `fetcher` argument that can be
used to integrate a third-party HTTP client or when writing tests to mock out
the HTTP client and feed in fixtures.

The following example shows how to use the `"beforeRequest"` hook to to add a
custom header and a timeout to requests and how to use the `"requestError"` hook
to log errors:

```typescript
import { Dokploy } from "dokploy-sdk";
import { HTTPClient } from "dokploy-sdk/lib/http";

const httpClient = new HTTPClient({
  // fetcher takes a function that has the same signature as native `fetch`.
  fetcher: (request) => {
    return fetch(request);
  }
});

httpClient.addHook("beforeRequest", (request) => {
  const nextRequest = new Request(request, {
    signal: request.signal || AbortSignal.timeout(5000)
  });

  nextRequest.headers.set("x-custom-header", "custom value");

  return nextRequest;
});

httpClient.addHook("requestError", (error, request) => {
  console.group("Request Error");
  console.log("Reason:", `${error}`);
  console.log("Endpoint:", `${request.method} ${request.url}`);
  console.groupEnd();
});

const sdk = new Dokploy({ httpClient });
```
<!-- End Custom HTTP Client [http-client] -->

<!-- Start Debugging [debug] -->
## Debugging

You can setup your SDK to emit debug logs for SDK requests and responses.

You can pass a logger that matches `console`'s interface as an SDK option.

> [!WARNING]
> Beware that debug logging will reveal secrets, like API tokens in headers, in log messages printed to a console or files. It's recommended to use this feature only during local development and not in production.

```typescript
import { Dokploy } from "dokploy-sdk";

const sdk = new Dokploy({ debugLogger: console });
```

You can also enable a default debug logger by setting an environment variable `DOKPLOY_DEBUG` to true.
<!-- End Debugging [debug] -->

<!-- Placeholder for Future Speakeasy SDK Sections -->

# Development

## Maturity

This SDK is in beta, and there may be breaking changes between versions without a major version update. Therefore, we recommend pinning usage
to a specific package version. This way, you can install the same version each time without breaking changes unless you are intentionally
looking for the latest version.

## Contributions

While we value open-source contributions to this SDK, this library is generated programmatically. Any manual changes added to internal files will be overwritten on the next generation. 
We look forward to hearing your feedback. Feel free to open a PR or an issue with a proof of concept and we'll do our best to include it in a future release. 

### SDK Created by [Speakeasy](https://www.speakeasy.com/?utm_source=dokploy-sdk&utm_campaign=typescript)
