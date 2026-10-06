# GitSync

## Integrations
|Name|Description|
|----|-----------|
|CA Service Desk Manager|CA Service Desk Manager is designed to help IT service desk analysts make every moment count through a dynamic experience so they can deliver great customer service without the fear of overbearing processes or metrics. With the solution, teams can embrace teamwork rather than working from siloed knowledge stashes and disjointed communications.|
|CrowdStrike Falcon|CrowdStrike Falcon is the leader in next-generation endpoint protection, threat intelligence and incident response through cloud-based endpoint protection.|


## Connectors
|Name|Description|Has Mappings|
|----|-----------|------------|
|stageupconnector|Pull information about Rule based alerts from Google Chronicle. Note: dynamic list is used for filtering purposes. For all of the details please visit the documentation portal.|False|


## Playbooks
|Name|Description|
|----|-----------|
|stageupPlaybook|test description|
|stageupblock|An embedded workflow that can receive inputs and return an output.|


## Visual Families
|Name|Description|
|----|-----------|
|stageupvisualfamilies|stageupvisualfamilies|


## Jobs
|Name|Description|
|----|-----------|
|Google Chronicle Alerts Creator Job|This job will sync new SOAR alerts with Chronicle SIEM.Note: This job is only supported from Chronicle SOAR version 6.2.30 and higher.|
|stageupjob|This job synchronizes Google SecOps Alerts and Palo Alto XDR Incidents. It ensures that comments and status are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the "Palo Alto XDR Incident" tag. If the alert didn’t originate from "Palo Alto Cortex XDR Connector",  you will need to add an "Incident_ID" context value to the case for the job to be able to find the correct information.|

