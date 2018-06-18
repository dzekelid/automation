---
name: Azure Automation
x-slug: azure-automation
description: Automate all of those frequent, time-consuming, and error-prone cloud
  management tasks. Azure Automation helps you focus on work that adds business value.
  By reducing errors and boosting efficiency, it also helps to lower your operational
  costs.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Automation
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Automation API Automation Account Update
  x-api-slug: azure-automation-api
  description: Update an automation account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}
  tags: Automation, Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountname-patch-openapi.md
- name: Azure Automation API Automation Account Create Or Update
  x-api-slug: azure-automation-api
  description: Create or update automation account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}
  tags: Automation, Account, Or
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountname-put-openapi.md
- name: Azure Automation API Automation Account Delete
  x-api-slug: azure-automation-api
  description: Delete an automation account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}
  tags: Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountname-delete-openapi.md
- name: Azure Automation API Automation Account Get
  x-api-slug: azure-automation-api
  description: Get information about an Automation Account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}
  tags: Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountname-get-openapi.md
- name: Azure Automation API Automation Account List By Resource Group
  x-api-slug: azure-automation-api
  description: Retrieve a list of accounts within a given resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts
  tags: Automation, Account, List, Resource, Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccounts-get-openapi.md
- name: Azure Automation API Lists the Automation Accounts
  x-api-slug: azure-automation-api
  description: Retrieve a list of accounts within a given subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Automation/automationAccounts
  tags: Lists, Automation, Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidprovidersmicrosoft-automationautomationaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidprovidersmicrosoft-automationautomationaccounts-get-openapi.md
- name: Azure Automation API Statistics List By Automation Account
  x-api-slug: azure-automation-api
  description: Retrieve the statistics for the account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/statistics
  tags: Statistics, List, Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamestatistics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamestatistics-get-openapi.md
- name: Azure Automation API Usages List By Automation Account
  x-api-slug: azure-automation-api
  description: Retrieve the usage for the account id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/usages
  tags: Usages, List, Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnameusages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnameusages-get-openapi.md
- name: Azure Automation API Certificate List By Automation Account
  x-api-slug: azure-automation-api
  description: Retrieve a list of certificates.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/certificates
  tags: Certificate, List, Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamecertificates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamecertificates-get-openapi.md
- name: Azure Automation API Connection List By Automation Account
  x-api-slug: azure-automation-api
  description: Retrieve a list of connections.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/connections
  tags: Connection, List, Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnameconnections-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnameconnections-get-openapi.md
- name: Azure Automation API Connection Type List By Automation Account
  x-api-slug: azure-automation-api
  description: Retrieve a list of connectiontypes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/connectionTypes
  tags: Connection, Type, List, Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnameconnectiontypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnameconnectiontypes-get-openapi.md
- name: Azure Automation API Credential List By Automation Account
  x-api-slug: azure-automation-api
  description: Retrieve a list of credentials.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/credentials
  tags: Credential, List, Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamecredentials-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamecredentials-get-openapi.md
- name: Azure Automation API Dsc Compilation Job List By Automation Account
  x-api-slug: azure-automation-api
  description: Retrieve a list of dsc compilation jobs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/compilationjobs
  tags: Dsc, Compilation, Job, List, Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamecompilationjobs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamecompilationjobs-get-openapi.md
- name: Azure Automation API Dsc Configuration List By Automation Account
  x-api-slug: azure-automation-api
  description: Retrieve a list of configurations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/configurations
  tags: Dsc, Configuration, List, Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnameconfigurations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnameconfigurations-get-openapi.md
- name: Azure Automation API Dsc Node List By Automation Account
  x-api-slug: azure-automation-api
  description: Retrieve a list of dsc nodes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/nodes
  tags: Dsc, Node, List, Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamenodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamenodes-get-openapi.md
- name: Azure Automation API Dsc Node Configuration List By Automation Account
  x-api-slug: azure-automation-api
  description: Retrieve a list of dsc node configurations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/nodeConfigurations
  tags: Dsc, Node, Configuration, List, Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamenodeconfigurations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamenodeconfigurations-get-openapi.md
- name: Azure Automation API Hybrid Runbook Worker Group List By Automation Account
  x-api-slug: azure-automation-api
  description: Retrieve a list of hybrid runbook worker groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/hybridRunbookWorkerGroups
  tags: Hybrid, Runbook, Worker, Group, List, Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamehybridrunbookworkergroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamehybridrunbookworkergroups-get-openapi.md
- name: Azure Automation API Job List By Automation Account
  x-api-slug: azure-automation-api
  description: Retrieve a list of jobs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/jobs
  tags: Job, List, Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamejobs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamejobs-get-openapi.md
- name: Azure Automation API Job Schedule List By Automation Account
  x-api-slug: azure-automation-api
  description: Retrieve a list of job schedules.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/jobSchedules
  tags: Job, Schedule, List, Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamejobschedules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamejobschedules-get-openapi.md
- name: Azure Automation API Module List By Automation Account
  x-api-slug: azure-automation-api
  description: Retrieve a list of modules.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/modules
  tags: Module, List, Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamemodules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamemodules-get-openapi.md
- name: Azure Automation API Runbook List By Automation Account
  x-api-slug: azure-automation-api
  description: Retrieve a list of runbooks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/runbooks
  tags: Runbook, List, Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooks-get-openapi.md
- name: Azure Automation API Schedule List By Automation Account
  x-api-slug: azure-automation-api
  description: Retrieve a list of schedules.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/schedules
  tags: Schedule, List, Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnameschedules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnameschedules-get-openapi.md
- name: Azure Automation API Variable List By Automation Account
  x-api-slug: azure-automation-api
  description: Retrieve a list of variables.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/variables
  tags: Variable, List, Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamevariables-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamevariables-get-openapi.md
- name: Azure Automation API Webhook List By Automation Account
  x-api-slug: azure-automation-api
  description: Retrieve a list of webhooks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/webhooks
  tags: Webhook, List, Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamewebhooks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamewebhooks-get-openapi.md
- name: Azure Automation API
  x-api-slug: azure-automation-api
  description: Automate all of those frequent, time-consuming, and error-prone cloud
    management tasks. Azure Automation helps you focus on work that adds business
    value. By reducing errors and boosting efficiency, it also helps to lower your
    operational costs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com//
  tags: Automation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/automation/master/_listings/azure-automation/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/automation/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/automation/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/automation/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/automation/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---