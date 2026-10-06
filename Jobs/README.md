## Google Chronicle Alerts Creator Job
This job will sync new SOAR alerts with Chronicle SIEM.
Note: This job is only supported from Chronicle SOAR version 6.2.30 and higher.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment|String|True|Default Environment|
|API Root|String|True|https://eu-chronicle.googleapis.com/v1alpha/projects/251657645427/locations/eu/instances/ab6f2f36-8b9d-4f06-9429-e4eeb73b0c7b|
|User's Service Account|Password|False|*****|
|Workload Identity Email|Password|False|*****|
|Verify SSL|Boolean|False|true|


test 22222## stageupjob
This job synchronizes Google SecOps Alerts and Palo Alto XDR Incidents. It ensures that comments and status are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the "Palo Alto XDR Incident" tag. If the alert didn’t originate from "Palo Alto Cortex XDR Connector",  you will need to add an "Incident_ID" context value to the case for the job to be able to find the correct information.


**Run Interval In Seconds:** 600

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|Api Root|String|False|https://api-gcptesting.xdr.us.paloaltonetworks.com|
|Api Key|Password|True|*****|
|Api Key ID|String|True|56|
|Max Hours Backwards|Integer|True|24|
|User Mapping JSON|String|False|{"Google SecOps Display Name": "XDR Username"}|
|Verify SSL|Boolean|False|true|


readme addon text 