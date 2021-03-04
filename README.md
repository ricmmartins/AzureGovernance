# AzureGovernance
A guide to start from scratch with Azure Governance


## Azure Fundamentals
1. [How does Azure Works](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/get-started/what-is-azure?WT.mc_id=devops_userstory_service_sprg-inproduct-devopsportal)
2. [Terminologies](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/considerations/fundamental-concepts#azure-terminology)
3. [Portfolio Hierarchy](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/reference/fundamental-concepts/hosting-hierarchy)
4. [Subscription purposes](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/considerations/fundamental-concepts#azure-subscription-purposes)
5. [Subscription decision guides](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/decision-guides/subscriptions/)
6. [Azure adminsitrative roles](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/considerations/fundamental-concepts#azure-administrative-roles)
7. [Azure Monitor Overview](https://docs.microsoft.com/en-us/azure/azure-monitor/overview)<br>
8. [Azure Security Center Intro](https://docs.microsoft.com/en-us/azure/security-center/security-center-intro)
9. [Microsoft Learn: Azure Fundamentals Learning Path](https://docs.microsoft.com/en-us/learn/paths/azure-fundamentals/)

## Azure Active Directory Basics
1. [What is AAD](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-whatis)
2. [Compare AD with AAD](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-compare-azure-ad-to-ad)
3. [AAD Deployment Guide](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-deployment-checklist-p2)
4. [Tutorial Create a new tenant in AAD](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-access-create-new-tenant)
5. [Tutorial: View your organization’s groups and members in AAD](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-access-create-new-tenant)
6. [Enable MFA](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/concept-fundamentals-mfa-get-started)
7. [Tutorial: Secure user sign-in events with Azure Multi-Factor Authentication](https://docs.microsoft.com/en-us/azure/active-directory/authentication/tutorial-enable-azure-mfa)
8. [Using security defaults](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/concept-fundamentals-security-defaults)


## Resources Organization
1. [Initial subscriptions](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/initial-subscriptions)
2. [Scale subscriptions](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/scale-subscriptions)
3. [Tutorial: Create an additional Azure subscription](https://docs.microsoft.com/en-us/azure/cost-management-billing/manage/create-subscription)
4. [Associate or add an Azure subscription to you AAD Tenant](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-how-subscriptions-associated-directory)
5. Organize subscriptions and resources<br/>
5.1. **Management Groups**<br/>
5.1.1. [Organize subscriptions](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/organize-subscriptions)<br/>
5.1.2. [Organize your Azure Resources (CAF)](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-setup-guide/organize-resources?tabs=AzureManagementGroupsAndHierarchy)<br/>
5.1.3. [Management Groups](https://docs.microsoft.com/en-us/azure/governance/management-groups/overview)<br/>
5.1.4. [Tutorial: Create management groups for resource organization and management](https://docs.microsoft.com/en-us/azure/governance/management-groups/create-management-group-portal)<br/>
5.2. **Naming Conventions**<br/>
5.2.1. [Recommended naming and tagging conventions](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/naming-and-tagging)<br/>
5.2.2. [Resource naming and tagging decision guide](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/decision-guides/resource-tagging/)<br/>
5.3. **Resource Groups**<br/>
5.3.1. [Principles of resource groups](https://docs.microsoft.com/en-us/learn/modules/control-and-organize-with-azure-resource-manager/2-principles-of-resource-groups)<br/>
5.3.2. [Tutorial: Creating Resource Groups](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resource-groups-portal#create-resource-groups)<br/>
5.4. **Tags**<br/>
5.4.1. [Use tags to organize your Azure resources ](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/tag-resources#portal)<br/>
5.4.2. [Use tagging to organize resources (MS Learn)](https://docs.microsoft.com/en-us/learn/modules/control-and-organize-with-azure-resource-manager/3-use-tagging-to-organize-resources)<br/>

## Role Based Access Control
1. [What is RBAC](https://docs.microsoft.com/en-us/azure/role-based-access-control/overview)
2. [Manage access to your Azure environment with role-based access controls](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-setup-guide/manage-access)
3. [Role-based access control](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/considerations/roles)
4. [Secure resources with RBAC](https://docs.microsoft.com/en-us/learn/modules/control-and-organize-with-azure-resource-manager/5-role-based-access)
5. [Tutorial: Add or remove role assignments using Azure RBAC and the Azure portal](https://docs.microsoft.com/en-us/azure/role-based-access-control/role-assignments-portal)
6. [Differences on RBAC Roles and Azure AD Roles](https://docs.microsoft.com/en-us/azure/role-based-access-control/rbac-and-directory-admin-roles)

## Azure Policy
1. [What is Azure Policy](https://docs.microsoft.com/en-us/azure/governance/policy/overview)
2. [Governance, security and compliance in Azure](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-setup-guide/govern-org-compliance?tabs=AzurePolicy)
3. [Define IT compliance with Azure Policy (MS Learn)](https://docs.microsoft.com/en-us/learn/modules/intro-to-governance/2-azure-policy)
4. [Organize policy with initiatives (MS Learn)](https://docs.microsoft.com/en-us/learn/modules/intro-to-governance/3-initiatives)
5. [Use policies to enforce standards (MS Learn)](https://docs.microsoft.com/en-us/learn/modules/control-and-organize-with-azure-resource-manager/4-use-policies-to-enforce-standards)
6. [Tutorial: Create a policy assignment to identify non-compliant resources](https://docs.microsoft.com/en-us/azure/governance/policy/assign-policy-portal)

## Resource Locks
1. [Lock resources to prevent unexpected changes](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/lock-resources)
2. [Use resource locks to protect resources (MS Learn)](https://docs.microsoft.com/en-us/learn/modules/control-and-organize-with-azure-resource-manager/6-use-resource-locks-to-protect-resources)
3. [Tutorial: Create a lock from Azure Portal](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/lock-resources#portal)

## Azure Blueprints
1. [What is Azure Blueprints?](https://docs.microsoft.com/en-us/azure/governance/blueprints/overview)
2. [Blueprint definitions](https://docs.microsoft.com/en-us/azure/governance/blueprints/overview#blueprint-definition)
3. [Define standard resources with Azure Blueprints (MS Learn)](https://docs.microsoft.com/en-us/learn/modules/intro-to-governance/5-azure-blueprints)
4. [Tutorial: Define and assign a blueprint in the portal](https://docs.microsoft.com/en-us/azure/governance/blueprints/create-blueprint-portal)

## Azure Service Health
1. [What is Azure Service Health?](https://docs.microsoft.com/en-us/azure/service-health/overview)
2. [View service health notifications by using the Azure portal](https://docs.microsoft.com/en-us/azure/service-health/service-notifications)
3. [Tutorial: Create activity log alerts on service notifications](https://docs.microsoft.com/en-us/azure/service-health/alerts-activity-log-service-notifications-portal)

## Azure Advisor
1. [Monitoring and reporting in Azure (CAF)](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-setup-guide/monitoring-reporting)
2. [Introduction to Azure Advisor](https://docs.microsoft.com/en-us/azure/advisor/advisor-overview)
3. [Get started with Azure Advisor](https://docs.microsoft.com/en-us/azure/advisor/advisor-get-started)
4. [Tutorial: Create Azure Advisor alerts on new recommendations](https://docs.microsoft.com/en-us/azure/advisor/advisor-alerts-portal)

## Azure Cost Management
1. [Manage costs and billing for your Azure resources](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-setup-guide/manage-costs)
2. [What is Azure Cost Management and Billing?](https://docs.microsoft.com/en-us/azure/cost-management-billing/cost-management-billing-overview)
3. [How to optimize your cloud investment with Azure Cost Management](https://docs.microsoft.com/en-us/azure/cost-management-billing/costs/cost-mgt-best-practices)
4. [Quickstart: Explore and analyze costs with cost analysis](https://docs.microsoft.com/en-us/azure/cost-management-billing/costs/quick-acm-cost-analysis)
5. [Tutorial: Create and manage Azure budgets](https://docs.microsoft.com/en-us/azure/cost-management-billing/costs/tutorial-acm-create-budgets)
6. [Tutorial: Create and manage exported data](https://docs.microsoft.com/en-us/azure/cost-management-billing/costs/tutorial-export-acm-data)
7. [Tutorial: Optimize costs from recommendations](https://docs.microsoft.com/en-us/azure/cost-management-billing/costs/tutorial-acm-opt-recommendations)
8. [Predict costs and optimize spending for Azure (MS Learn)](https://docs.microsoft.com/en-us/learn/modules/predict-costs-and-optimize-spending/)

## Azure Resource Graph
1. [What is Azure Resource Graph?](https://docs.microsoft.com/en-us/azure/governance/resource-graph/overview)
2. [Azure Resource Graph Explorer](https://docs.microsoft.com/en-us/azure/governance/resource-graph/first-query-portal)
3. [Tutorial: Create and share an Azure Resource Graph query in the Azure portal](https://docs.microsoft.com/en-us/azure/governance/resource-graph/tutorials/create-share-query)
4. [Starter Resource Graph query samples](https://docs.microsoft.com/en-us/azure/governance/resource-graph/samples/starter?tabs=azure-cli)
5. [Advanced Resource Graph query samples](https://docs.microsoft.com/en-us/azure/governance/resource-graph/samples/advanced?tabs=azure-cli)
6. [Understanding the Azure Resource Graph query language](https://docs.microsoft.com/en-us/azure/governance/resource-graph/concepts/query-language)
7. [Explore your Azure resources with Resource Graph](https://docs.microsoft.com/en-us/azure/governance/resource-graph/concepts/explore-resources)
8. [Azure Resource Graph security baseline for Azure Security Benchmark](https://docs.microsoft.com/en-us/azure/governance/resource-graph/concepts/azure-security-benchmark-baseline)
9. [Get resource changes](https://docs.microsoft.com/en-us/azure/governance/resource-graph/how-to/get-resource-changes)

### Outcomes
One you finish a learning over those topics, you will be ready to deploy Azure Governance with confidence. So after this, I strongly recommend you take a look into AzGovViz, a tool created by Julian Hayward to give to you a visualization from environment governance. See more at: [https://github.com/julianhayward/azure-mg-sub-governance-reporting](https://github.com/julianhayward/azure-mg-sub-governance-reporting)







