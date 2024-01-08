| [Home](../README.md) |
|--------------------------------------------|

# Usage

Refer to [Simulate Scenario documentation](https://github.com/fortinet-fortisoar/solution-pack-soc-simulator/blob/develop/docs/usage.md) to understand how to simulate and reset scenarios.

To generate report with self analyzing system details, we have included a scenario &mdash; **System Configuration Recommendation** with this solution pack. 

This solution pack includes a playbook that you can launch manually from the scenario page. This playbook performs the following tasks:

- Get system details either from user or analyze itself
- Generate Recommendation for UWSGI, PGSQL, etc 
- Converts Recommendation to HTML report and create an attachment of report

Refer to the sections *System Configuration Recommendation Scenario* and *Manual Email Upload* to understand how this solution pack's automation addresses your needs.

## System Configuration Recommendation Scenario
This scenario generates a report by analyzing system details automatically and creates a task for tracking purposes

Navigate to the Task and note the following:

- The task contains comments to know at what phase is being executed in plybook
- After Playbook execution is successfully you will get an atttachment created for system configuration report

>**NOTE**: If any error occurs please check the comments it self and if no error is present in comments then check playbook execution log


## Manual Trigger > System Configuration Recommendation

This Playbook can be executed on Scenario module. **Execute** button to display the playbook &ndash; **Manual Trigger > System Configuration Recommendation** &ndash; from the playbook collection **10 - SP - System Configuration Recommendation**.

When executed, this playbook prompts you to enter data related to your system like Number of CPU, RAM in GB, etc. as soon as you enter data and click execute an attchament will be created containing system configuration report

# Note 
* For HA setups apply the recommended configuration to all the system and then restart the services starting with Primary
* For HA setups allocate swap memory for PostgreSQL with size equal to shared memory
* Steps to apply recommended configuration is mentioned in report itself

| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Contents](./contents.md) |
|-----------------------------------------|-------------------------------------------|---------------------------|