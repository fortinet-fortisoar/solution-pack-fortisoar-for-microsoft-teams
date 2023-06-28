| [Home](../README.md) |
|----------------------|

# Contents

The **FortiSOAR for Microsoft Teams** solution pack contains the following resources.

## Connectors

| Name       | Description                                                                                                                                                                       |
|:-----------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Microsoft Teams      | Microsoft Teams is a chat-based workspace in Office 365 that provides global, remote, and dispersed teams with the ability to work together and share information using a common space. This connector facilitates automated operation related to teams. |
| VirusTotal | Scans and analyzes suspicious files, URLs, IP addresses and retrieves reports from VirusTotal about them                                                                          |
| IPStack    | IPStack provides geolocation facility for IP Address or Domain.                                                                                                                   |

## Notification Channel

| Name               | Description                                         |
|:-------------------|:----------------------------------------------------|
| Microsoft Teams Link | To send a message to Microsoft Teams when certain rule is met. |
| Microsoft Team      | It Sends a Manual Input Form to the Microsoft Teams application.|

## Rules

Rules provide a framework to define a condition that generates notifications.

| Name                                     | Description                                                                                                                                                          |
|:-----------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Microsoft Teams > Notify on External Manual Input Form | It Sends a Manual Input Form to the Microsoft Teams application. when the manual input step for Microsoft Teams is triggered. |
| Microsoft Teams > Notify on Playbook failure | Sends an error when a playbook which has `bot_enabled` tag fails. Error: `PlaybookName` Playbook has failed. Please check the *Executed Playbook Logs* in FortiSOAR. |
| Microsoft Teams > Send Manual Input link  | Sends a link to Microsoft Teams that can be clicked to get the manual input.                                      |

When creating notification rules, selecting **Manual Input** as a notification trigger, makes following conditions available:
- **External Channels (Inline)** - The manual input form appears inline with other FortiSOAR messages in Microsoft Teams.

    ![](./res/inline-form.png)

- **External Channels (Link)** - The manual input form appears as a link with other FortiSOAR messages in Microsoft Teams.

    ![](./res/form-as-link.png)

## Playbook Collection

| 02 - Use Case - FortiSOAR for Microsoft Teams |
|:------------------------------------|

| Playbook Name        | Description                                                                                                |
|:---------------------|:-----------------------------------------------------------------------------------------------------------|
| Create Indicator     | Extract Indicators from the text provided as Input                                                         |
| Create Alert         | Creates an alert based on the values provided in the form                                                  |
| Enrich IP From Microsoft Teams | Reference playbook that gets triggered from Microsoft Teams based and provides latest reputation formatted for Microsoft Teams |