# ec2-remediation-system-enhancement

## System Overview

### The EC2 remediation system was put in place to help notify and provide action steps to the DevOps team when the AWS Server goes down. Previously this incident response did not exist in which case when it went down there was depredated service for a period of time to customers without IT’s knowledge, potentially costing the company valuable customers. 

### By implementing this remediation system, there is an integration between the AWS Server and ServiceNow and when the server goes offline it is logged into tables in ServiceNow which will then trigger a workflow to notify DevOps and provide the appropriate remediation steps. 

### The enhancement includes the use of an AI agent to help optimize the proces of the DevOps completing the remediation steps. They can use the agent by inputting the incident or intance number to the have the AI agent remediate by performing the action of the UI Action to turn the instance back on. 

## Implementation Steps

### When implementing the AI agent there was some difficulty with only utilizing one tool when attempting to look up the incident. Thus after ample testing it was determined that an additional skill was needed to look up incident table records to be able to successfully pass both testing scenarios. 
####1. Look up by incident records 
####2. Remediating intance 

![Diagram]()

![Diagram]()


## Architecture Diagram

![Diagram](Diagram.png)


![Diagram]()


## Optimization

### 

![Diagram]()

## DevOps AI Process Instructions 

#### 1. Log into the ServiceNow-company.com system 
#### 2. 
#### 3. 

## DevOps Manual Process Instructions
