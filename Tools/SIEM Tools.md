To better understand security analysts tools, it's necessary to remember some concepts. One core component of this study is a **Log**, which can be defined as a record of events that occur within an organization's system's and networks.

Logs can be categorized, not only by this, as it follows:

* **Firewall Log**: A record of established connections for incoming traffic from the internet. It also includes outbound requests to the internet from within the network.
* **Network Log**: A record of all computers and devices that enter and leave the network. It also records connections between devices and services on the network.
* **Server Log**: A record of events related to services, such as websites, emails or files shares. It includes actions such as login, password, and username requests.

# Security Information and Event Management(SIEM)

That's an application that collects and analyzes log data to monitor critical activities in an organization. It also stores the log data in a centralized location, making it more easy to visualize and filter the events, per specified parameters.

Many SIEM tools use dashboards to visualize data that is being monitored. It's job of the cybersecurity analyst to look into those data and check if there's something unusual. For example, looking at the log events, an analyst can see that there are multiple login attempts to an employee account, outside of their regular work hours and from a distant geolocation.

Also, SIEM tools can be useful to have data that can be used as **Metrics** for the IT department as a whole. These **Metrics** are key technical attributes, such as response time, availability, and failure rate, which are used to asses the perfomance of a software application.

## Types of SIEM tools

1. **Self-hosted**: These kind of tools require that an organization install, operate and maintain the tool using their own physical environment. These are ideal when an organization is required to maintain physical control over confidential data.
2. **Cloud-hosted**: The SIEM tools are maintained and and managed by the SIEM providers, make them accessible trough the internet. These are ideal to places that don't want to invest in creating and maintaining their own infrastructure.
3. **Hybrid**: Gets the benefits of the cloud, but use the physical control over confidential data.

## List of SIEM tools

* [SplunkEnterprise](https://www.splunk.com/en_us/products/splunk-enterprise.html): **Self-hosted** tool used to retain, analyze and search an organization's log data to provide security information and alerts in real time.
* [SplunkCloud](https://www.splunk.com/en_us/products/splunk-cloud-platform.html): A **cloud-hosted** solution that allows an analyst to collect, search and monitor log data.
* [Google's Chronicle](https://cloud.google.com/chronicle/docs/overview?hl=pt-br): A **cloud-native** tool designed to retain, analyze and search data.

### Dashboards

Among the SIEM tools mentioned above, there are many features that help the cyber security analysts. Within these tools, the dashboards are very important to review organization's data.

Inside **Splunk** tools, such as Enterprise and Cloud, there are the following options of dashboards:

#### Security Posture

This posture dashboard is designed for security operations centers (SOCs). It displays the last 24 hours of an organization's notable security related events and trends allows security professionals to determine if security infrastructure and policies are performing as designed.

Security analysts can use this dashboard to monitor and investigate potential threats in real time, such as suspicious network activity originating from a specific IP address.

#### Executive Summary dashboard

The executive summary dashboard analyses the overall health of the organization over time. This helps security teams improve security measures that reduce risk. Security analysts might use this dashboard to provide high-level insights to stakeholders, such as generating a summary of security incidents and trends over a specific period of time.

#### Incident review dashboard

The incident review dashboard allows analysts to identify suspicious patterns that can occur in the event of an incident. It assists by highlighting higher risk items that need  immediate review by an analyst. This dashboard can be very helpful because it provides a visual timeline of the events leading up to an incident.

#### Risk analysis dashboard

The risk analysis dashboard helps analysts identify risk for each risk object. It shows changes in risk-related activity or behavior, such as a user logging in outside of normal working hours or unusually high network traffic from a specific computer. A security analyst might use this dashboard to analyse the potential impact of vulnerabilities in critical assets, which helps analysts prioritize their risk mitigation efforts.

The **Chronicle** SIEM tool allows to collect and analyze log data according to:

* A specific asset
* A domain name
* A user
* An IP address

**Chronicle** provides multiple dashboards that help analysts monitor an organization's logs, create filters and alerts, and track suspicious domain names. The application's dashboards can be listed as:

#### Enterprise insights dashboard

This dashboard highlights recent alert. It identifies suspicious domain names in logs, known as indicators of compromise (IOCs). Each result is labeled with a confidence score to indicate the likelihood of a threat. It also provides a severity level that indicates the significance of each threat to the organization. A security analyst might use this dashboard to monitor login or data access attempts related to a critical asset - like and application or system - from unusual locations or devices.

#### Data ingestion and health dashboard

The data ingestion and health dashboard shows the number of event logs, log sources, and success rates of data being processed into Chronicle. An analyst might use this dashboard to ensure that log sources are correctly configured and that logs are received without error.

#### IOC matches dashboard

This dashboard indicates top threats, risk and vulnerabilities to the organization. Security professionals use this dashboard to observe domain names, IP addresses, and device IOCs over time in order to identify trends. This information is then used to direct the security team's focus to the highest priority threats.

#### Main dashboard

The main dashboard displays a high-level summary of information related to the organization's data ingestion, alerting, and event activity over time. Security professionals can use this dashboard to access a timeline of security events - such as spike in failed login attempts - to identify threat trends across log sources, devices, IP addresses and physical locations.

#### Rule Detection Dashboard

This dashboard provides statistics related to incidents with the highest occurrences, severities, and detections overtime. Also, an analyst can use this to access a list of all the alerts triggered by a specific detection rule, such as a rule designed to alert whenever a user opens a known malicious attachment an email.

#### User sign in overview dashboard

This dashboard provides information about user access behavior across the organization. It can give data about unusual activity, such as user signing in from multiple locations at the same time.