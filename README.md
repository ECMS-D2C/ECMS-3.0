ECMS-3.0
========

ECMS tool for Documaker to CMOD migration

ECMS Migration tool has three main components
•	ECMS Controller
•	Documaker Extraction Adaptor
•	CMOD Ingestion  Adaptor
Documaker Extraction Adaptor will use IDS server to access contents from documaker server. CMOD ingestion Adaptor will use ODWEK JAVA API to ingest reports into CMOD. CMOD ingestion adaptor can also use ARSLOAD for report ingestion.
Controller is a web interface which facilitates migration configuration, monitoring and report generation.
All the three components can be deployed and configured in a distributed fashion and communication will be through Remote Method Invocation (RMI).
