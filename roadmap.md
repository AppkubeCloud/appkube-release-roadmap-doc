- [Introduction](#introduction)
- [Key-Modules](#key-modules)
- [Key-Modules-and-UseCases](#key-modules-and-usecases)
# Introduction
This document will detail about Appkube roadmap and releases.

Synectiks Appkube is a SRE platform that primarily focuses on following :

- Manage distributed microservices Cost & Quality (container & server less) in multicloud hybrid environment
- Deliver reusable common App Blocks to write enterprise products with reduced coding effort
- Deliver DevSecOps tooling to write cloud native products

It helps customer who is devoloping products in cloudnative environment as follows:

- Reduced Operation Management time & Effort @50%
- Imporves product SLE's by 30%
- Reduce Cloud Capex by 25%
- Reduce Development Effort by 50%

## Key-Modules

![AppkubeModules](./images/appkube-modules.png)

## Key-Modules-and-UseCases



<table><tr><th colspan="1" valign="top">Module</td><th colspan="1" valign="top">Use Cases</td><th colspan="1" valign="top">Description</td><th colspan="1" valign="top">Release</td><th colspan="1" valign="top">Testing Criterion</td></tr>
<tr><td colspan="1" valign="top"><b>Cloud CMDB</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" rowspan="24" valign="top"></td><td colspan="1" valign="top">Cloud Asset Discovery</td><td colspan="1" valign="top"><p>Given an account, discover its elements.</p><p></p></td><td colspan="1" valign="top">0\.0.0.1</td><td colspan="1" valign="top"><p>Find and verify the list of Cloud Elements in product.</p><p></p></td></tr>
<tr></td><td colspan="1" valign="top">Environment Wise Infra View</td><td colspan="1" valign="top"><p>List all elements Account / VPC wise - Do Further Navigation on elements.</p><p></p></td><td colspan="1" valign="top">0\.0.0.1</td><td colspan="1" valign="top"><p>Find and verify the elements and configs.</p><p></p></td></tr>
<tr></td><td colspan="1" valign="top">Filters in Asset Home Page</td><td colspan="1" valign="top">Filter with Departments / Products / Env / Accounts/ Zone</td><td colspan="1" valign="top">0\.0.0.1</td><td colspan="1" valign="top">Verify all the filters in home page are working.</td></tr>
<tr></td><td colspan="1" valign="top">Add department / product / Env Manually</td><td colspan="1" valign="top">From the Assets Page, add the business entities.</td><td colspan="1" valign="top">0\.0.0.2</td><td colspan="1" valign="top"><p>Find and verify the added element in UI.</p><p></p></td></tr>
<tr></td><td colspan="1" valign="top">Tag cloud element with business entities</td><td colspan="1" valign="top">In Assets, wherever non-tagged cloud element is there, we should be able to associate with Business.</td><td colspan="1" valign="top">0\.0.0.2</td><td colspan="1" valign="top">We should see the services view in Account and the Application view.</td></tr>
<tr></td><td colspan="1" valign="top">Segregate Unused Assets / Manually Associated Assets/ Auto discovered Assets</td><td colspan="1" valign="top">In assets page, we should be having this view.</td><td colspan="1" valign="top">0\.0.0.2</td><td colspan="1" valign="top">Verify the segregated assets.</td></tr>
<tr></td><td colspan="1" valign="top">Set logs for Element</td><td colspan="1" valign="top">In assets list, we should see the warning and should see the options to set log location – this may require cloud watch log’s group discovery.</td><td colspan="1" valign="top">0\.0.0.2</td><td colspan="1" valign="top">Logs are Available and logs stream can be shown once we set the log location.</td></tr>
<tr></td><td colspan="1" valign="top">Set Trace for Element</td><td colspan="1" valign="top">In assets list, we should see the warning and should see the options to set log location – this may require AWS X-RAY g discovery.</td><td colspan="1" valign="top">0\.0.0.2</td><td colspan="1" valign="top">Traces are Available and trace stream can be shown once we set the trace location.</td></tr>
<tr></td><td colspan="1" valign="top">Filter Orphaned Elements - No logs / No Trace/ No monitoring</td><td colspan="1" valign="top"></td><td colspan="1" valign="top">0\.0.0.2</td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Filter Non-productive Assets / Productive Assets</td><td colspan="1" valign="top"></td><td colspan="1" valign="top">0\.0.0.2</td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Environment Wise Services View</td><td colspan="1" valign="top"></td><td colspan="1" valign="top">0\.0.0.3</td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Environment Wise Application View</td><td colspan="1" valign="top"></td><td colspan="1" valign="top">0\.0.0.3</td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Environment Wise Billing View</td><td colspan="1" valign="top"></td><td colspan="1" valign="top">0\.0.0.3</td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Product wise Cost Explorer</td><td colspan="1" valign="top"></td><td colspan="1" valign="top">0\.0.0.3</td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Product wise Services SLA Explorer</td><td colspan="1" valign="top"></td><td colspan="1" valign="top">0\.0.0.3</td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Enable Monitoring for Cloud Elements</td><td colspan="1" valign="top"></td><td colspan="1" valign="top">0\.0.0.4</td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Service Topology and Its drilldown</td><td colspan="1" valign="top"></td><td colspan="1" valign="top">0\.0.0.4</td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Enable Alerts for Cloud Elements</td><td colspan="1" valign="top"></td><td colspan="1" valign="top">0\.0.0.4</td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Add product deployment JSON in GitHub from automation central and the corresponding details are imported in CMDB.</td><td colspan="1" valign="top"></td><td colspan="1" valign="top">0\.0.0.4</td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Environment Wise Alerts View</td><td colspan="1" valign="top"></td><td colspan="1" valign="top">0\.0.0.5</td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Environment Wise Threats/Compliance View</td><td colspan="1" valign="top"></td><td colspan="1" valign="top">0\.0.0.5</td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Filter Non-Secure / Non-Compliant Assets</td><td colspan="1" valign="top"></td><td colspan="1" valign="top">0\.0.0.5</td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Cloud Services Mesh</td><td colspan="1" valign="top"></td><td colspan="1" valign="top">0\.0.0.6</td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Data Mesh Support</td><td colspan="1" valign="top"></td><td colspan="1" valign="top">0\.0.0.6</td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Automation Central</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" rowspan="13" valign="top"></td><td colspan="1" valign="top">Add landing Zone</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Add product enclave</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Add cluster</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Add Gateway</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Add LB in product</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Add product in product enclave</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Add Business Service in a product</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Add Common Service in a product</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Run Audits on Product</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Run Audits on Landing Zone</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Run Audits on Product Enclave</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Run Audits on Cluster</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Self Service Provisioning – Org / Business </td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Security/RBAC</b> </td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top"><p>Add/Update/Delete</p><p>Users / Groups / Role / Transactions</p></td><td colspan="1" valign="top">The basic functionality of the Security module that allows to Add Admin / Leaders / DevSecOps Users and their Roles.</td><td colspan="1" valign="top">0\.0.0.1</td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Add Configurable Authentication methods for users</td><td colspan="1" valign="top"></td><td colspan="1" valign="top">0\.0.0.2</td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Define RBAC for User/ Group / Roles </td><td colspan="1" valign="top"></td><td colspan="1" valign="top">0\.0.0.2</td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Integrate Vault for storing Authentication Details.</td><td colspan="1" valign="top"></td><td colspan="1" valign="top">0\.0.0.3</td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Catalogue Management</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" rowspan="3" valign="top"></td><td colspan="1" valign="top">View / Search Global Catalogue</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Manage artifact libraries</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Import Artifacts</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Preference Management</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" rowspan="5" valign="top"></td><td colspan="1" valign="top">User / Group / Role Management</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Vault Integration</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Environment Specific Watcher / Jobs on /off</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">SLA / Cost Update Periodicity</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Manage Metric / Log / Trace Databases</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Vault</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Store/ Retrieve Cloud Env Details in Vault</td><td colspan="1" valign="top">Store the credentials in vault, use them in discovery.</td><td colspan="1" valign="top">0\.0.0.1</td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Metric Central</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Get Metrics of Cloud Element directly with Vault</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Get Metric of Cloud Element from Prometheus & Vault</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Add Metric Database in K8 cluster</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Provision Dynamic Prometheus Agents for Account / Cloud Elements</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Manage Prometheus Pool of Agents (Add / update / Delete)</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Log Central</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Search Logs of Cloud Element directly with Vault</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Search Logs of Cloud Element from Promtail / logdb & Vault</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Add Logdb Database in K8 cluster</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Provision Dynamic Prom tail log Agents for Account / Cloud Elements</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Manage Prometheus Pool of Log Agents (Add / update / Delete)</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Trace Central</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Search Traces of Cloud Element directly with Vault & AWS XRAY</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Search Logs of Cloud Element from TraceDb & Vault</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Add Trace Db Database in K8 cluster</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Set/ Configure Cloud Elements to pass its trace data</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Cost Central</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Evaluate Services and Cloud Elements costs periodically and store them in Metric DB – create watcher</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Can start / stop watcher for cloud elements dynamically</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Add metric DB in k8 cluster for Cost</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Evaluate Services and Cloud Elements costs trends periodically and store them in Metric DB – create watcher</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Add Cost oriented Alerting rules and evaluate them periodically</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>SLA Central</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Evaluate Services and Cloud Elements SLA’s periodically and store them in Metric DB – create watcher</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Can start / stop watcher for cloud elements dynamically</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Add metric DB in k8 cluster for SLA’s</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Evaluate Services and Cloud Elements SLA’s trends periodically and store them in Metric DB – create watcher</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Add SLA oriented Alerting rules and evaluate them periodically</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Search Queries and API’s on SLA’s</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Transfer SLA tuples to Drill Down Analytics for doing SLA analysis</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Compliance Central</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Create / Update / Delete Compliance Rules & Policies</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Run compliances on Cloud Element against set of rules and policies</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Store compliance result sets in github and do the change analysis</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Artifact Editor</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" rowspan="7" valign="top"></td><td colspan="1" valign="top"><p>A generic DS where we can fire metric / logs / trace /Api’s request and</p><p>Can develop application in speedy way</p></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Modify standalone UI to consume Artifact Json Easily</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Create/ Publish Dashboard in Global Catalogue</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Create/ Publish Workflows in Global Catalogue</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Create/ Publish Automation in Global Catalogue</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">List Artifacts in Global Catalogue</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr></td><td colspan="1" valign="top">Search Artifacts in Global Catalogue</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Appkube Operator</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Individual Services Operator</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">whole Appkube Service Operator</td><td colspan="1" valign="top"><p>Deploy CMDB/VAULT/SECURITY service with Istio gateway and LB in EKS</p><p></p></td><td colspan="1" valign="top">0\.0.0.1</td><td colspan="1" valign="top"><p>UI can access the API's with LB url-api.synectiks.net</p><p></p></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Procurement App Operator</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">EMS App Operator</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Cluster Explorer</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Cluster Home Page</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Services Page</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Individual App Service Explorer</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Individual Data Service Explorer</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Cluster Reliability Dashboards</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Cloud Element Explorer</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">S3 Explorer</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Lambda Explorer</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">NLB Explorer</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Cluster Explorer</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Api Gateway Explorer</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">CDN Explorer</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Waf Explorer</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Data lake Services Explorer</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Alert Manager</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Alert Home Page and Filters</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Integration of Notification Channels</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Alert rules discovery and provision in Prometheus</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Add alert streaming with kafka & alert DB – (same logdb)</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Dashboard to alert manager integration </td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Alert Manager to Service Desk Integrations</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Alert filters on products / env / service /layers</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">All dashboard and Prometheus Alert Rules Discovery</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Silence / Dedup / Process alerts</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Alert integration with Cost and SLA central</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Service Desk</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Manage Agents / Op -Leads / Customer</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">SLA reports</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Ticket to Run jobs integration</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Analytics</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Reporting</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Dev Central</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Generators</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Delivery Central</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Quality Central</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Test Central</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Workflow Editor</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Workflow Engine</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Static Site Generator</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">CI/CD</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">SDK/ Libraries</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">GitOps</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Operators</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Code Quality</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Code Vulnerability</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Container Management</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">FAAS Tooling</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Ops Central</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">ChatOps</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">AI-OPS</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Optimizer</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Tool Chain</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Self Service Provisioning</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Tools/ Diagnostics</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Change Central</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Script Central</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Sec Central</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Infra Security</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">App Security</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Data Security</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Container Security</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Code Security (SAST/DAST)</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">RBAC</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Vault Management</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Certificate Management</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Analytics</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Drill Down Analytics</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Views Management</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"><b>Report Central</b></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Daily/ Weekly / Monthly / Quarterly Cost & SLA reports</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">PROD/ Non-Prod </td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Top 10 reports</td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
</table>


# **RoadMap & Releases**

## **Release 0.0.0.1**

**Date of Release** ---**26th May 2023**
### **Features**
- Cloud Asset Discovery -- This rease will focus on cloud element discovery and display of different cloud accounts. For any AWS account , 
given the crossAccountRoleArn and ID , the product should diplay every VPC's and corresponding hardwares elements in a comprehensive format.

#### **Included Use Cases**

|Module| Use-Cases| Description | Acceptance Tests|
|:---|:---|:---|:---|
|CMDB| Cloud Asset Discovery | Given an account , discover its elements |Find and verify the list of Cloud Elements in product |
|CMDB| Environment Wise Infra View | List all elements Account / VPC wise - Do Further Navigatios on elements |Find and verify the elements and configs|
|CMDB| Filters in Asset Home Page| Filter with Departments / Products / Env / Accounts/ Zone |Verify all the filters in home page are working.|
|Security/RBAC| Add/Update/Delete Users / Groups / Role / Transactions| Basic functions of security module |Check CRUD of user/ group/roles|
|VAULT| Store/ Retrieve Cloud Env Details in Vault| List all elements Account / VPC wise - Do Further Navigatios on elements |Find and verify the elements and configs|
|Appkube Operator|Write Appkube Operator| Deploy CMDB/VAULT/SECURITY service with istio gateway and LB in EKS |UI can access the API's with LB url-api.synectiks.net|

## **Release 0.0.0.2**

**Date of Release** ---**9th June 2023**
### **Features**
- Cloud Asset to Business – Manual Association -- This rease will focus on associating the discovered cloud elements with business entities 
  (Department - Product - Env - Microservices - (firewall/Gw/LB/App&Data layer)
#### **Included Use Cases**

|Module| Use-Cases| Description | Acceptance Tests|
|:---|:---|:---|:---|
|CMDB| Add department / product / Env Manually | In organization , we can add dpeartment/product/env/service/app layer/data layer manually |Find and verify the added element in UI |
|CMDB| Environment Wise Infra View | List all elements Account / VPC wise - Do Further Navigatios on elements |Find and verify the elements and configs|
|CMDB| Environment Wise Infra View | List all elements Account / VPC wise - Do Further Navigatios on elements |Find and verify the elements and configs|
|Security/RBAC| Add/Update/Delete Users / Groups / Role / Transactions| Basic functions of security module |Check CRUD of user/ group/roles|
|VAULT| Store/ Retrieve Cloud Env Details in Vault| List all elements Account / VPC wise - Do Further Navigatios on elements |Find and verify the elements and configs|
|Appkube Operator|Write Appkube Operator| Deploy CMDB/VAULT/SECURITY service with istio gateway and LB in EKS |UI can access the API's with LB url-api.synectiks.net|


Asset Discovery  /// 0.0.1
Dashboard Catalogue /// 0.0.2
Cloud Asset to Business – Manual Association /// 0.0.3
Alert & Service Desk Integration /// 0.0.4
Few explorer (Lambdas / LB…) 5  Rel 1.0 /// 0.0.5
Compliance Checks
Automation
Catalogue Publish



### phase2- architecture


Asset Discovery  /// 0.0.1
Dashboard Catalogue /// 0.0.2
Cloud Asset to Business – Manual Association /// 0.0.3
Alert & Service Desk Integration /// 0.0.4
Few explorer (Lambdas / LB…) 5  Rel 1.0 /// 0.0.5
