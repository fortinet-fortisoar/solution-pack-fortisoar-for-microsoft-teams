| [Home](../README.md) |
|--------------------------------------------|

# Installation

1. To install a solution pack, click **Content Hub** > **Discover**.
2. From the list of solution pack that appears, search for and select **FortiSoar for Microsoft Teams**.
3. Click the **FortiSOAR for Microsoft Teams** solution pack card.
4. Click **Install** on the bottom to begin installation.

## Prerequisites

The **FortiSoar for Microsoft Teams** solution pack depends on the following solution packs that are installed automatically &ndash; if not already installed.

| Solution Pack Name | Purpose                                |
|:-------------------|:---------------------------------------|
| SOAR Framework     | Required for Incident Response modules |

# Configuration

For optimal performance of **FortiSoar for Microsoft Teams** solution pack, you can install and configure the following connectors:

- Microsft Teams connector for creating alerts and incidents using commands in the Microsoft Teams's chat interface.
    - To configure and use refer to [Configuring Microsft Teams Connector](https://docs.fortinet.com/document/fortisoar/2.0.0/microsoft-teams/529/microsoft-teams-v2-0-0)
- Threat intelligence connectors to enrich context of an indicator created through the Microsoft Teams app.
    - To configure and use the VirusTotal connector as a source of threat intelligence, refer to [Configuring Virus Total](https://docs.fortinet.com/document/fortisoar/3.0.2/virustotal/374/virustotal-v3-0-2#Configuration_parameters).
    - To configure and use the IPStack connector as a source of geolocation for an IP address or a domain, refer to [Configuring Virus Total](https://docs.fortinet.com/document/fortisoar/1.0.1/ipstack/368/ipstack-v1-0-1#Configuration_parameters).