# Log Queries

LogicMonitor log queries, provisioned with all new LogicMonitor accounts. Intended to be examples to get the creativity flowing! 

The Logs query language expands the standard search capabilities beyond keyword searches and filtering by resource, group, pipeline, and time range. The additional flexibility includes combining filters with logical operators, filtering events based on fields and values parsed from your logs, and matching patterns with glob expressions and regular expressions.

Use the features to, for example, narrow down information to quickly find relevant logs when troubleshooting. You can also summarize activity from log messages over a time range for reporting or alerting.

To visit the home for Logs query documentation start here: [LogicMonitor Query Language Overview](https://www.logicmonitor.com/support/lm-logs-query-language).


### Usage

Clone this git repo to your local machine using the URL from the green button above, or download the individual JSON files from the web page.

Utilze the import functionality in the UI to bring these JSON files into your portal. Click on the drop list arrow immediately to the right of the query bar on the Logs page.  *Note: Each individual user will need to import the files to be accessed from their login.*


## LogicMonitor Log Query Packs 

> The files are broken out into specific areas of interest. Choose one or all depending on your use case. Core is applicable to the widest use cases for all customers. There are some informational comments within the JSON files to clarify intended use.

**Core** 
- Anomaly 
- Error Conditions 
- Volume/Usage 
- Deviceless Logs 
- Logins

**Category**
- Network
- SNMP Trap
- Windows
- AWS

**Future releases**
- Application
- K8s - Kubernetes
- Azure / GCP