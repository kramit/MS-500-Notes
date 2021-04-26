## Module 06: Threat management

### Talking points

Azure Sentinal test incidents

https://azsec.azurewebsites.net/2020/01/06/create-a-fully-customized-azure-sentinel-incident/

https://github.com/azsec/azure-sentinel-tools/blob/master/scripts/New-AzSentinelIncident.ps1

https://azurecloudai.blog/2021/02/25/how-to-generate-azure-sentinel-incidents-for-testing/



### Lesson 1: Security dashboard

Demonstration:  Office 365 Security Dashboard
https://www.microsoft.com/en-us/videoplayer/embed/RE1VV3o

Microsoft Security Community
https://youtu.be/kHUEVUKXbBM

### Lesson 2: Threat investigation and response

Demonstration: Threat Dashboard and Explorer
https://youtu.be/krFAjIkD66M

Attack Simulator in Office 365
https://youtu.be/5jWGU2VM3SI

Microsoft Graph Security API
https://youtu.be/oYXPGwH9Ho0

Using the Microsoft Intelligent Security Graph
https://youtu.be/-Q_G3yF9ZL4

### Lesson 3: Azure Sentinel

That’s why we re-imagined the SIEM + SOAR tool to introduce a new cloud-native solution called Microsoft Azure Sentinel - providing intelligent security analytics at cloud scale for your entire enterprise.
 Azure Sentinel makes it easy to collect security data across your entire hybrid organization from devices, users, apps, servers and any cloud, it uses the power of artificial intelligence to ensure you are identifying real threats quickly, and unleashes you from the burden of traditional SIEMs by eliminating the need to spend time on setting up, maintaining and scaling infrastructure. 

Since it is built on Azure, it offers limitless cloud scale and speed, scaling automatically to address your needs. 
Traditional SIEMs have also proven to be expensive to own and operate, often requiring you to commit upfront and incur high cost for infrastructure maintenance and data ingestion. With Azure Sentinel there will be no upfront costs, you will only pay for what you use, and we are offering free Office 365 activity data import to help you reduce security costs significantly

Key Takeaway: Azure Sentinel is a Cloud-native SIEM solution that includes Security Orchestration, Automation and Response (SOAR), Machine Learning, and Behavior Analytics

Like legacy SIEMs, Azure Sentinel can collect, store, and analyze security data of nearly any format and source. Because it is built on native cloud services, Azure Sentinel can store and analyze immense amounts of logs without requiring on-premises infrastructure like servers, storage and networking. Additionally, the cloud architecture allows Azure Sentinel to reason over millions of records within seconds. 

Azure Sentinel leverages Microsoft’s threat intelligence system (called the Graph Security API) that processes 6.5 trillion signals per day from a diverse set of sources (endpoint, web, network, malware, and more).  Azure sentinel integrates the resulting geo location and IP reputation feeds to enrich your alerts and investigations. 

Analyze and Detect Threats - Azure Sentinel simplifies the use of advanced analytics technology like machine learning and behavior analytics to enable analysts to rapidly identify and investigate anomalies. 
As an example, the machine learning in azure sentinel can quickly identify a spike in events on a particular Saturday (relative to other Saturdays) and then automatically generate a query to return the logs during that timeframe so the analyst can begin investigating whether it is an active attack or a benign event. 

Investigate and Hunt Suspicious activities - Azure sentinel includes an interactive visualization of attacks so you can quickly and intuitively navigate the related elements of an attack to understand its scope, dive deep, and pivot without typing a query. 

Azure Sentinel also supports Jupyter notebooks via Azure notebooks to enable your team to consume operations playbooks and methodology from the community as well as create and update your own. 

Additionally, Azure Sentinel automates and orchestrates response across tools in your enterprise like ServiceNow, Slack/Teams/Email, and Security tools like Palo Alto Firewalls. 

Azure Sentinel is built with a connection to the community on GitHub and allows you to leverage resources from the community including detections, dashboards, functions, notebooks, playbooks, hunting queries and more. You can also contribute your own learnings to the community for other teams to use. 

Our goal is to make it easy for you to collect data across all sources in your organization.  Azure Sentinel has built-in connectors that help you do just that-
One-click integration with Microsoft solutions
Data connectors for growing list of other technologies – on-premises and cross-cloud
Support for standard log formats (CEF/Syslog and WEF) 
Specialized TAXII and Graph connectors for threat intelligence data
REST API for connecting to cloud solutions
Proven log analytics platform with more than 10Pb of daily data ingestion

After you connect data sources to Azure Sentinel, the next step is to identify suspicious activities and threats. Azure Sentinel provides built-in templates to enable you to do this and get notified of such threats. These templates were designed by Microsoft’s team of security experts and analysts based on known threats, common attack vectors, and suspicious activity escalation chains. After you enable these templates, they will automatically search for suspicious activity across your environment. Many of them can be customized to search for, or filter out, activities according to your needs. 

More than 100 built-in alert rules were developed by Microsoft and community security experts
A wizard enables you to create your own analytics rules using KQL queries 
Thresholds can be set to alert when activity levels exceed normal patterns
Correlation events with your threat intelligence and now with Microsoft intel about malicious URLs.
Microsoft has unparalleled view of evolving threat landscape
Customers can now match Microsoft URL TI with network logs
Matched MS indicators are added to the TI table for use like any other indicator
Retrospective lookbacks that match TI against historical event data and more TI types will be coming soon.
Alerts can be used to trigger automated playbooks


Interactive Guide: Modernize your security operations with Microsoft Azure Sentinel
https://aka.ms/AzureSentinel_SOC_InteractiveGuide

Analysts need to proactively look for threats that may not have been discovered by security apps. Azure Sentinel includes built-in hunting queries that guide you to ask the right questions to find previously undiscovered threats.

With Azure Sentinel hunting, you can take advantage of the following capabilities:
• Built-in queries: A starting page provides preloaded query examples designed to get you started quickly and familiarize you with the tables and the query language. These built-in hunting queries are developed and fine-tuned by Microsoft security researchers and the GitHub community on a continuous basis to provide you with an entry point and help you start hunting for the beginnings of new attacks.
• Powerful query language with IntelliSense: Built on top of a query language, this gives you the flexibility you need to take hunting to the  next level.
.• Use notebooks to automate investigation: Notebooks encapsulate all the hunting steps in a reusable playbook that can be shared with others in your organization.
• Query the stored data: The data is accessible in tables for you to query. For example, you can query process creation, DNS events, and many other event types.
• Links to community: Leverage the power of the greater community to find additional queries and data sources

### Lesson 4: Advanced Threat Analytics

Overview of ATA Deployment
https://youtu.be/UvhozhWq25I
