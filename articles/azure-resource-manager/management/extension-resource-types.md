---
title: Extension resource types
description: Lists the Azure resource types are used to extend the capabilities of other resource types.
ms.topic: conceptual
ms.date: 10/20/2021
---

# Resource types that extend capabilities of other resources

An extension resource is a resource that adds to another resource's capabilities. For example, resource lock is an extension resource. You apply a resource lock to another resource to prevent it from being deleted or modified. It doesn't make sense to create a resource lock by itself. An extension resource is always applied to another resource.

## Microsoft.Advisor

- Microsoft.Advisor/configurations
- Microsoft.Advisor/recommendations
- Microsoft.Advisor/suppressions

## Microsoft.AlertsManagement

- Microsoft.AlertsManagement/alerts

## Microsoft.Authorization

- Microsoft.Authorization/batchResourceCheckAccess
- Microsoft.Authorization/denyAssignments
- Microsoft.Authorization/eligibleChildResources
- Microsoft.Authorization/locks
- Microsoft.Authorization/policyAssignments
- Microsoft.Authorization/policyDefinitions
- Microsoft.Authorization/policyExemptions
- Microsoft.Authorization/policySetDefinitions
- Microsoft.Authorization/privateLinkAssociations
- Microsoft.Authorization/roleAssignmentApprovals
- Microsoft.Authorization/roleAssignments
- Microsoft.Authorization/roleAssignmentScheduleInstances
- Microsoft.Authorization/roleAssignmentScheduleRequests
- Microsoft.Authorization/roleAssignmentSchedules
- Microsoft.Authorization/roleDefinitions
- Microsoft.Authorization/roleEligibilityScheduleInstances
- Microsoft.Authorization/roleEligibilityScheduleRequests
- Microsoft.Authorization/roleEligibilitySchedules
- Microsoft.Authorization/roleManagementPolicies
- Microsoft.Authorization/roleManagementPolicyAssignments

## Microsoft.Automanage

- Microsoft.Automanage/configurationProfileAssignmentIntents
- Microsoft.Automanage/configurationProfileAssignments

## Microsoft.Billing

- Microsoft.Billing/billingPeriods
- Microsoft.Billing/billingPermissions
- Microsoft.Billing/billingRoleAssignments
- Microsoft.Billing/billingRoleDefinitions
- Microsoft.Billing/createBillingRoleAssignment

## Microsoft.Blueprint

- Microsoft.Blueprint/blueprintAssignments
- Microsoft.Blueprint/blueprints

## Microsoft.Capacity

- Microsoft.Capacity/listSkus

## Microsoft.ChangeAnalysis

- Microsoft.ChangeAnalysis/changes
- Microsoft.ChangeAnalysis/changeSnapshots
- Microsoft.ChangeAnalysis/computeChanges

## Microsoft.Consumption

- Microsoft.Consumption/AggregatedCost
- Microsoft.Consumption/Balances
- Microsoft.Consumption/Budgets
- Microsoft.Consumption/Charges
- Microsoft.Consumption/CostTags
- Microsoft.Consumption/credits
- Microsoft.Consumption/events
- Microsoft.Consumption/Forecasts
- Microsoft.Consumption/lots
- Microsoft.Consumption/Marketplaces
- Microsoft.Consumption/Pricesheets
- Microsoft.Consumption/products
- Microsoft.Consumption/ReservationDetails
- Microsoft.Consumption/ReservationRecommendationDetails
- Microsoft.Consumption/ReservationRecommendations
- Microsoft.Consumption/ReservationSummaries
- Microsoft.Consumption/ReservationTransactions

## Microsoft.ContainerInstance

- Microsoft.ContainerInstance/serviceAssociationLinks

## Microsoft.CostManagement

- Microsoft.CostManagement/Alerts
- Microsoft.CostManagement/Budgets
- Microsoft.CostManagement/CheckNameAvailability
- Microsoft.CostManagement/Dimensions
- Microsoft.CostManagement/Exports
- Microsoft.CostManagement/ExternalSubscriptions
- Microsoft.CostManagement/Forecast
- Microsoft.CostManagement/GenerateDetailedCostReport
- Microsoft.CostManagement/Insights
- Microsoft.CostManagement/OperationResults
- Microsoft.CostManagement/OperationStatus
- Microsoft.CostManagement/Query
- Microsoft.CostManagement/Reportconfigs
- Microsoft.CostManagement/Reports
- Microsoft.CostManagement/ScheduledActions
- Microsoft.CostManagement/Views

## Microsoft.CustomProviders

- Microsoft.CustomProviders/associations

## Microsoft.DataMigration

- Microsoft.DataMigration/DatabaseMigrations

## Microsoft.Diagnostics

- Microsoft.Diagnostics/InsightDiagnostics
- Microsoft.Diagnostics/solutions

## Microsoft.EventGrid

- Microsoft.EventGrid/eventSubscriptions
- Microsoft.EventGrid/extensionTopics

## Microsoft.GuestConfiguration

- Microsoft.GuestConfiguration/configurationProfileAssignments
- Microsoft.GuestConfiguration/guestConfigurationAssignments
- Microsoft.GuestConfiguration/software

## Microsoft.HybridConnectivity

- Microsoft.HybridConnectivity/endpoints

## microsoft.insights

- microsoft.insights/baseline
- microsoft.insights/dataCollectionRuleAssociations
- microsoft.insights/diagnosticSettings
- microsoft.insights/diagnosticSettingsCategories
- microsoft.insights/eventtypes
- microsoft.insights/extendedDiagnosticSettings
- microsoft.insights/guestDiagnosticSettingsAssociation
- microsoft.insights/logDefinitions
- microsoft.insights/logs
- microsoft.insights/metricbaselines
- microsoft.insights/metricDefinitions
- microsoft.insights/metricNamespaces
- microsoft.insights/metrics
- microsoft.insights/myWorkbooks
- microsoft.insights/topology
- microsoft.insights/transactions

## Microsoft.IoTSecurity

- Microsoft.IoTSecurity/sensors
- Microsoft.IoTSecurity/sites

## Microsoft.KubernetesConfiguration

- Microsoft.KubernetesConfiguration/extensions
- Microsoft.KubernetesConfiguration/fluxConfigurations
- Microsoft.KubernetesConfiguration/sourceControlConfigurations

## Microsoft.Maintenance

- Microsoft.Maintenance/applyUpdates
- Microsoft.Maintenance/configurationAssignments
- Microsoft.Maintenance/updates

## Microsoft.ManagedIdentity

- Microsoft.ManagedIdentity/Identities

## Microsoft.ManagedServices

- Microsoft.ManagedServices/registrationAssignments
- Microsoft.ManagedServices/registrationDefinitions

## Microsoft.OperationalInsights

- Microsoft.OperationalInsights/storageInsightConfigs

## Microsoft.OperationsManagement

- Microsoft.OperationsManagement/managementassociations

## Microsoft.PolicyInsights

- Microsoft.PolicyInsights/attestations
- Microsoft.PolicyInsights/eventGridFilters
- Microsoft.PolicyInsights/policyEvents
- Microsoft.PolicyInsights/policyStates
- Microsoft.PolicyInsights/policyTrackedResources
- Microsoft.PolicyInsights/remediations

## Microsoft.Quota

- Microsoft.Quota/operationsStatus
- Microsoft.Quota/quotaRequests
- Microsoft.Quota/quotas
- Microsoft.Quota/usages

## Microsoft.RecoveryServices

- Microsoft.RecoveryServices/backupProtectedItems
- Microsoft.RecoveryServices/replicationEligibilityResults

## Microsoft.ResourceHealth

- Microsoft.ResourceHealth/childResources
- Microsoft.ResourceHealth/events
- Microsoft.ResourceHealth/impactedResources

## Microsoft.Resources

- Microsoft.Resources/links
- Microsoft.Resources/tags

## Microsoft.Security

- Microsoft.Security/adaptiveNetworkHardenings
- Microsoft.Security/advancedThreatProtectionSettings
- Microsoft.Security/antiMalwareSettings
- Microsoft.Security/assessmentMetadata
- Microsoft.Security/assessments
- Microsoft.Security/Compliances
- Microsoft.Security/dataCollectionAgents
- Microsoft.Security/deviceSecurityGroups
- Microsoft.Security/InformationProtectionPolicies
- Microsoft.Security/insights
- Microsoft.Security/jitPolicies
- Microsoft.Security/serverVulnerabilityAssessments
- Microsoft.Security/sqlVulnerabilityAssessments

## Microsoft.SecurityInsights

- Microsoft.SecurityInsights/aggregations
- Microsoft.SecurityInsights/alertRules
- Microsoft.SecurityInsights/alertRuleTemplates
- Microsoft.SecurityInsights/automationRules
- Microsoft.SecurityInsights/bookmarks
- Microsoft.SecurityInsights/cases
- Microsoft.SecurityInsights/dataConnectors
- Microsoft.SecurityInsights/dataConnectorsCheckRequirements
- Microsoft.SecurityInsights/enrichment
- Microsoft.SecurityInsights/entities
- Microsoft.SecurityInsights/entityQueryTemplates
- Microsoft.SecurityInsights/incidents
- Microsoft.SecurityInsights/listrepositories
- Microsoft.SecurityInsights/metadata
- Microsoft.SecurityInsights/onboardingStates
- Microsoft.SecurityInsights/settings
- Microsoft.SecurityInsights/sourceControls
- Microsoft.SecurityInsights/threatIntelligence
- Microsoft.SecurityInsights/watchlists

## Microsoft.SerialConsole

- Microsoft.SerialConsole/serialPorts

## Microsoft.ServiceLinker

- Microsoft.ServiceLinker/linkers

## Microsoft.SoftwarePlan

- Microsoft.SoftwarePlan/hybridUseBenefits

## Microsoft.Subscription

- Microsoft.Subscription/policies

## microsoft.support

- microsoft.support/supporttickets

## Microsoft.WorkloadMonitor

- Microsoft.WorkloadMonitor/monitors

## Next steps

- To get the resource ID for an extension resource in an Azure Resource Manager template, use the [extensionResourceId](../templates/template-functions-resource.md#extensionresourceid).
- For an example of creating an extension resource in a template, see [Event Grid Event Subscriptions](/azure/templates/microsoft.eventgrid/2019-06-01/eventsubscriptions).
