# Welcome to the GitHub Pages of the MONICA Research Group

## What is MONICA?
---

MONICA was a research group of the Computer Networks Laboratory (CNL) at the Technical University of Kosice, Slovak republic, between the years 2006 and 2015. The research group was founded in 2006, formerly under the *BasicMeter* name. This name was given to group based on the first major tool (BasicMeter) that has been developed by the MONICA members. 

The members of MONICA were composed of network and service management enthusiast, in particular, undergraduate and graduate students studying for BSc., MSc., and PhD., as well as university professionals (assistant/associate professors and professors). The number active MONICA contributors was up to 10 members every academic year.

Over the years, as the research objectives of MONICA expanded. As such, to match better its activites, the name of the group was renamed to MONICA. MONICA stands for the **M**onitoring and **O**ptimization of **N**etwork **I**nfrastructures, **C**ommunications and **A**pplications. 

The main objective of MONICA was the development of network traffic flow measurement and monitoring tools and methods that are in conformity with the IPFIX protocol. 

Application domain specific tools and methods developed by MONICA include:
   * Usage-based accounting which allows more flexible accounting for network services than flat-rate accounting and brings advantages for both the service providers and users. Our solution contains an accounting database and additional collector functions which create accounting records by aggregation of the flow records using specified criteria.
   * SLA evaluation for tracking the fulfillment of the specified conditions between the subscriber and the provider. Our solution provides web interface for both sides with specific information about the operation and traffic parameters of the last mile. It has a modular architecture, so it is simple to add new components upon the needs of such type of users.
   * Anomaly-based Intrusion Detection System (IDS) which builds information by characterizing the normal traffic, evaluates the current traffic, and alerts the administrator when violation occurs. Anomaly detection is implemented by fuzzy subsystems designated for the detection of specific types of network attacks, and also for the detection of general anomalies of the network traffic.
   * Adaptive Anomaly Driven Traffic Engineering (AADTE) using different dynamically applied configuration changes into the network devices, such as routing optimization, usage of QoS mechanisms or security policy enforcement. Specific optimizing changes are selected by a domain-specific decision maker module when traffic anomaly is detected.
   * Monitoring of information systems where the importance of solving security issues led us to design the monitoring tool's architecture inspired by the IPFIX. The proposed monitoring tool’s architecture involves the measurement of the operational parameters of an information system. It is easily scalable and powerful enough to handle a huge amount of monitored operations occuring in the case of DoS and DDoS attacks on a monitored information system.

MONICA was concluded in 2015 with the conclusion of the IPFIX working group.

## Outcomes of MONICA
---

The tools, techniques and approaches developed by MONICA were presented on a number of conferences and published in scientific journals. A selection of them is the following:

### BasicMeter

BasicMeter is the first tool developed by the group. BasicMeter is a network traffic flow metering tool that is in full conformity with the NetFlow and IPFIX protocols.

   * **Related publications:**
      * 
### SLAmeter

SLAmeter was the second major tool developed by MONICA. SLAmeter is based on BasicMeter. The main difference between the tools is that SLAmeter is aimed at 

### Analyser-Collector Protocol (ACP)

The Analyzer - Collector Protocol (ACP) is destined for the direct communication between the collector and analyzer. ACP is a supporting mechanism for real-time monitoring. In the BasicMeter architecture the analyzer is intended to visualize the data computed on the basis of the gathered traffic information and manage the other components of the tool. However, the analyser itself is not a subject of the IPFIX specifications and therefore we had to draft and implement our own network protocols for the data flow and communication between the analyzer and the other components of the metering tool. Along with the ACP we also developed an Application Programmable Interface (API), so it can be easily implemented in any analyzer-like application. 




