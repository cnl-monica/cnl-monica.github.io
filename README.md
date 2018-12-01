# Welcome to the GitHub Pages of the MONICA Research Group

## What is MONICA?
---

MONICA was a research group of the Computer Networks Laboratory (CNL) at the Technical University of Kosice, Slovak republic, that existed nearly 10 years. The research group was founded in 2006, formerly under the *BasicMeter* name. This name was given to group based on the first major tool (BasicMeter) that was developed by its members. 

The members of the group were composed of network and service management enthusiast, in particular of undergraduate and graduate students studying for BSc., MSc., and PhD.  as well as university staff (assistant/associate professors and professors). The number active MONICA contributors was around 10 members every academic year.

Over the years the research objectives of the group expanded. As such, to match better its activites, the name of the reserach group was changed to MONICA. MONICA stands for the **M**onitoring and **O**ptimization of **N**etwork **I**nfrastructures, **C**ommunications and **A**pplications. 

The main objective of MONICA was the development of network traffic flow measurement and monitoring tools and methods that are in conformity with the IPFIX protocol. Application domain specific tools and methods developed by MONICA include:

   * Usage-based accounting which allows more flexible accounting for network services than flat-rate accounting and brings advantages for both the service providers and users. Our solution contains an accounting database and additional collector functions which create accounting records by aggregation of the flow records using specified criteria.
   * SLA evaluation for tracking the fulfillment of the specified conditions between the subscriber and the provider. Our solution provides web interface for both sides with specific information about the operation and traffic parameters of the last mile. It has a modular architecture, so it is simple to add new components upon the needs of such type of users.
   * Anomaly-based Intrusion Detection System (IDS) which builds information by characterizing the normal traffic, evaluates the current traffic, and alerts the administrator when violation occurs. Anomaly detection is implemented by fuzzy subsystems designated for the detection of specific types of network attacks, and also for the detection of general anomalies of the network traffic.
   * Adaptive Anomaly Driven Traffic Engineering (AADTE) using different dynamically applied configuration changes into the network devices, such as routing optimization, usage of QoS mechanisms or security policy enforcement. Specific optimizing changes are selected by a domain-specific decision maker module when traffic anomaly is detected.
   * Monitoring of information systems where the importance of solving security issues led us to design the monitoring tool's architecture inspired by the IPFIX. The proposed monitoring tool’s architecture involves the measurement of the operational parameters of an information system. It is easily scalable and powerful enough to handle a huge amount of monitored operations occuring in the case of DoS and DDoS attacks on a monitored information system.

MONICA was concluded in 2015 with the conclusion of the IPFIX working group.

## Outcomes of MONICA
---

The tools, techniques and approaches developed by MONICA were presented on a number of conferences and published in scientific journals. A selection of these works is as follows:

An overview of major MONICA outcomes up to 2012 is provided in:
   * A. Pekár, M. Révés, J. Giertl, and P. Feciľak, [“Overview and insight into the monica research group”](https://doi.org/10.2478/s13537-012-0013-9), Central European Journal of Computer Science, vol. 2, no. 3, pp. 331–343, Nov. 2012.

Manuscripts related to the adaptive aggregation method that reduces the generated IPFIX flow records by 28\% are the following:
   * A. Pekár, M. Chovanec, L. Vokorokos, E. Chovancová, P. Feciľak, and M. Michalko, [“Adaptive aggregation of flow records”](https://doi.org/10.4149/cai_2018_1_142), Computing and Informatics, vol. 37, no. 1, pp. 142–164, 2018.
   * S. Tremko, A. Pekár, J. Juhár, and J. Janitor, [“Reduction of ip flow information in network traffic monitoring systems”](https://doi.org/10.1109/ICETA.2014.7107616), in Proceedings of the 2014 12th IEEE International Conference on Emerging eLearning Technologies and Applications, ser. ICETA ’14, Dec. 2014, pp. 385–390.
   * A. Pekár, E. Chovancová, P. Fanfara, and J. Trelová, [“Issues in the passive approach of network traffic monitoring”](https://doi.org/10.1109/INES.2013.6632836), in Proceedings of the 2013 IEEE 17th International Conference on Intelligent Engineering Systems, ser. INES ’13, Jun. 2013, pp. 327–332.

Manuscripts related to the SLAmeter:
   * A. Pekár, P. Feciľak, M. Michalko, J. Giertl, and M. Révés, [“Slameter - the evaluator of network traffic parameters”](https://doi.org/10.1109/ICETA.2012.6418318), in Proceedings of the 2012 IEEE 10th International Conference on Emerging eLearning Technologies Applications, ser. ICETA ’12, Nov. 2012, pp. 291–295.
   * L. Vokorokos, J. Juhár, A. Pekár, Peter Feciľak, [“The Web Application of the SLAmeter Tool”](https://doi.org/10.1109/ICETA.2014.7107587), in Proceedings of the 2014 12th IEEE International Conference on Emerging eLearning Technologies and Applications, ser. ICETA '14, Dec. 2014, pp. 215-220.
   
Manuscript focusing on the data warehouse for network monitoring:
   * L. Vokorokos, A. Pekár, and N. Ádám, [“Data preprocessing for efficient evaluation of network traffic parameters”](https://doi.org/10.1109/INES.2012.6249860), in Proceedings of the 2012 IEEE 16th International Conference on Intelligent Engineering Systems, ser. INES '12, Jun. 2012, pp. 363–367.
   
Manuscript related to the ACP protocol is provided in:
   * A. Pekár, J. Giertl, M. Révés , P. Feciľak, “Simplification of the Real-Time Network Traffic Monitoring”, Electrical Engineering and Informatics II, Proceedings of the Faculty of Electrical Engineering and Informatics of the Technical University of Kosice, Mar. 2011, pp. 272-277.




