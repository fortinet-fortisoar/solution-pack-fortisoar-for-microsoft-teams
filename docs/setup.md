| [Home](../README.md) |
|----------------------|

# Installation

1. To install a solution pack, click **Content Hub** > **Discover**.
2. From the list of solution pack that appears, search for and select **FortiSOAR for Microsoft Teams**.
3. Click the **FortiSOAR for Microsoft Teams** solution pack card.
4. Click **Install** on the lower part of the screen to begin installation.

<table>
    <tr>
        <td><strong>NOTE</strong></td>
        <td>Microsoft Teams requires FortiSOAR&trade; setup to be accessible through cloud.</td>
    </tr>
</table>

## Prerequisites

The **FortiSOAR for Microsoft Teams** solution pack depends on the following solution packs that are installed automatically &ndash; if not already installed.

| Solution Pack Name | Version          | Purpose                                |
|:-------------------|:-----------------|:---------------------------------------|
| SOAR Framework     | v2.1.0 and later | Required for Incident Response modules |

# Configuration

- For setting up the bi-directional integration between FortiSOAR&trade; and Microsoft Teams application, refer to the following articles available on FortiSOAR&trade; product documentation:

    1. [Setup FortiSOAR&trade; for Microsoft Teams app on Azure](https://docs.fortinet.com/document/fortisoar/1.0.0/fortisoar-for-microsoft-teams-application/630/fortisoar-for-microsoft-teams-application-v1-0-0#setupFSROnAzure)

    2. [Enable the Microsoft Teams channel in Azure](https://docs.fortinet.com/document/fortisoar/1.0.0/fortisoar-for-microsoft-teams-application/630/fortisoar-for-microsoft-teams-application-v1-0-0#EnableMSTeams)

    3. [Configure the Microsoft Teams channel in Azure](https://docs.fortinet.com/document/fortisoar/1.0.0/fortisoar-for-microsoft-teams-application/630/fortisoar-for-microsoft-teams-application-v1-0-0#configureMSTeamsChannelInAzure)

    4. [Set up FortiSOAR for Microsoft Teams app on Microsoft Teams](https://docs.fortinet.com/document/fortisoar/1.0.0/fortisoar-for-microsoft-teams-application/630/fortisoar-for-microsoft-teams-application-v1-0-0#SetupFSRAppOnMsTeams)

    5. [Configuring the FortiSOAR For Microsoft Teams Application in your FortiSOAR instance](https://docs.fortinet.com/document/fortisoar/1.0.0/fortisoar-for-microsoft-teams-application/630/fortisoar-for-microsoft-teams-application-v1-0-0#configureFSRForMsTeamsAppinFSR)

    After completing the set up of FortiSOAR&trade; for Microsoft Teams app on Azure, configure the Microsoft Teams connector.

    - To configure and use Microsoft Teams connector, refer to [Configuring Microsoft Teams Connector](https://docs.fortinet.com/fortisoar/connectors/ms-teams)

    The bridge between FortiSOAR&trade; and Microsoft Teams is now ready for end-to-end communication between the two.

- For optimal performance of **FortiSOAR for Microsoft Teams** solution pack, install and configure threat intelligence connectors to enrich context of an indicator created through the Microsoft Teams application.

    - To configure and use the VirusTotal connector as a source of threat intelligence, refer to [Configuring Virus Total](https://docs.fortinet.com/fortisoar/connectors/virustotal).

    - To configure and use the IPStack connector as a source of geolocation for an IP address or a domain, refer to [Configuring IPStack](https://docs.fortinet.com/fortisoar/connectors/ipstack).

<table>
    <tr>
        <td><strong>NOTE</strong></td>
        <td>By default, <strong>FortiSOAR for Microsoft Teams</strong> is shipped with playbooks integrated with <em>VirusTotal</em> and <em>IPStack</em>. To use this solution pack with other threat intelligence connectors, edit the shipped playbooks accordingly.</td>
    </tr>
</table>


## Next Steps

| [Usage](./usage.md) | [Contents](./contents.md) |
|---------------------|---------------------------|
