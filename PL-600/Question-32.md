## MetaData
Question Type : Multiple Choice
Max Answers : 4

## Question
You are the architect for a new Power Platform solution. You are documenting the mechanisms through which Microsoft ensures the high availability of Power Platform based solutions to project stakeholders. Which of the statements below are factually correct? 

## Options
Option 1 : Microsoft deploys a Microsoft Power Platform environment within an Azure region.
Option 2 : Within an Azure region, services and data are replicated redundantly across the datacenter(s) to increase availability.
Option 3 : Each Azure region has a paired region where Microsoft Power Platform resources are replicated automatically. 
Option 4 : Microsoft monitors Microsoft Power Platform on your behalf as part of the service.
Option 5 : If an issue occurs with the primary datacenter, Power Platform customers will initiate the failover from the primary location to the regional pair.

## Answers
Option 1 : 3
Option 2 : 3
Option 3 : 3
Option 4 : 3

## Reference Links
https://learn.microsoft.com/en-us/training/modules/power-platform-architecture/7-availability

## Explanation
Microsoft Power Platform components handle internal integrations; solution architects should focus on external integrations and custom code.<br>If an issue occurs with the primary datacenter, Microsoft will initiate the failover automatically, if necessary, from the primary location to the regional pair. Microsoft also handles required service recovery.<br>Users should not notice interruptions in service. At worst, they will have a transient error when saving data. For example, model-driven apps will handle such errors.<br>However, custom code could have issues. For example, the endpoint for the environment might change. Integrations should use the global discovery service for endpoint discovery to get the latest environment endpoint. Custom code should have transient error handling with automatic retries. 

## Products 


## Modules SubModules CTA 

