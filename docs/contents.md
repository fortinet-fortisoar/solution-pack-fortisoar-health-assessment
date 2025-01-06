| [Home](../README.md) |
|----------------------|

# Contents

The **FortiSOAR Health Assessment** solution pack contains the following resources.

## Connectors

|**Name**|**Description**|
| :- | :- |
| FortiSOAR Health Assessment  | The Health Assessment Connector provides detailed insights into FortiSOAR VM configurations, including CPU, RAM, IOPs, and disk latency metrics. Additionally, it gathers playbook-related data, such as the most frequently executed playbooks and those with the highest failure rates. |


## Playbook Collection

|**Playbook Collection Name**|**Description**|
| :- | :- |
| 10 - SP - FortiSOAR Health Assessment | Playbooks designed to capture, evaluate, and generate reports and ymal files |

## Playbook

|**Playbook Name**|**Description**|
| :- | :- |
| Health Assessment | This playbook that creates Health Assessment Record |
| Health Assessment > Capture and Evaluate Data | This playbook captures and evaluates data to generate Health Assessment Record |
| Health Assessment > Get FortiSOAR Information | This playbook is used to gather information about your FortiSOAR system. |
| Configuration Recommendation | This playbook creates Configuration Recommendation Record |
| Configuration Recommendation > Capture and Evaluate Data | This playbook captures and evaluates data to generate Configuration Recommendation Recordd |
| > YAML File Generation | This playbook generates a YAML file with recommended configuration changes, stores it on a Linux system, and attaches it to the Health Assessment record as an attachment. |
| > Create MD for Description | This playbook generates a report that is displayed in the Health Assessment module. |
| > Report Generation | This playbook generates the report that is attached to Health Assessment Module |
| > Generate Configuration | This playbook generates configuration recommendations for your system based on its resources. |


>**Warning:** We recommend that you clone these playbooks before customizing to avoid loss of information while upgrading the solution pack.

| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) |
|-----------------------------------------|-------------------------------------------|---------------------|