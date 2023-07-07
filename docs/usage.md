| [Home](../README.md) |
|--------------------------------------------|

# Usage

This section gives a brief description on some of the commands used in FortiSOAR for Microsoft Teams application:

## `@fortiSOAR createAlert`

This commands performs the following actions:

1. Displays a new alert form.
2. Uses the details from the form to create a new alert in FortiSOAR.

You can create placeholder alerts on the fly for further investigation by the Security Operations Center (SOC) team.

## `@fortiSOAR createIndicator`

This commands performs the following actions:

1. Displays a new indicator form.
2. Uses the details from the form to create a new indicator in FortiSOAR.
3. Takes an indicator value in the command to create the indicator with the specified value.

    `@fortiSOAR createIndicator <indicator_value>` adds an indicator in FortiSOAR and gets the latest enrichment details back to Microsoft Teams within seconds.

    For example, `@fortiSOAR createIndicator gumblar.cn` creates an indicator of value `gumblar.cn`.

You can create indicators on the fly for enrichment and further investigation by the Security Operations Center (SOC) team.

## `@fortiSOAR invokePlaybook`

This command takes another argument `<tag_name>` to trigger the playbook containing the tag `<<tag_name>>`.

For example, the command `invokePlaybook getIPRep` invokes playbooks with the tag `getIPRep`.

This powerful action opens the automation capabilities for FortiSOAR where you can create and invoke playbooks in FortiSOAR.

>**NOTE**: The playbook you are trying to invoked must have an existing `bot_enabled` tag. 

## `@fortiSOAR help`

This command brings up the available commands and their usage details.
