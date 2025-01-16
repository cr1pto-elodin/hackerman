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