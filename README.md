## What is MONICA?
---

MONICA was a research group of the Computer Networks Laboratory (CNL) at the Technical University of Kosice, Slovak Republic, that existed nearly 10 years. The research group was founded in 2006, formerly under the *BasicMeter* name. This name was given to the group based on the first major tool (BasicMeter) that was developed by its members.

The members of the group were composed of network and service management enthusiasts, in particular of undergraduate and graduate students studying for BSc., MSc., and PhD.  as well as university staff (assistant/associate professors and professors). The number of active MONICA contributors was around 10 members every academic year.

Over the years the research objectives of the group expanded. As such, to match better its activities, the name of the research group was changed to MONICA. MONICA stands for the **M**onitoring and **O**ptimization of **N**etwork **I**nfrastructures, **C**ommunications and **A**pplications. 

The main objective of MONICA was the development of network traffic flow measurement and monitoring tools and methods that are in conformity with the IPFIX protocol. MONICA was concluded in 2015 with the conclusion of the IPFIX working group.

**For a description of an IPFIX-based network traffic flow measurement and monitoring tool proceed to this [page](IPFIX.md).**

## Domains of Research and Development
---

The application domain specific tools and methods developed by MONICA include:

   * Adaptive flow measurement data volume reduction techniques.
   * Monitoring for Service Level Agreement (SLA) evaluation and fulfilment.
   * Anomaly-based intrusion detection system (IDS) built using fuzzy logic (subsystems).
   * Usage-based accounting of network services.

## Outcomes of MONICA
---

The tools, techniques and approaches developed by MONICA were presented on a number of conferences and published in various scientific journals. A selection of these works is as follows:

---

**An overview of major MONICA outcomes up to 2012 is provided in:**
   * A. Pekár, M. Révés, J. Giertl, and P. Feciľak, [“Overview and insight into the monica research group”](https://doi.org/10.2478/s13537-012-0013-9), Central European Journal of Computer Science, vol. 2, no. 3, pp. 331–343, Nov. 2012.

---

**Manuscripts related to the adaptive aggregation method that reduces the generated IPFIX flow records by 28% include:**
   * A. Pekár, M. Chovanec, L. Vokorokos, E. Chovancová, P. Feciľak, and M. Michalko, [“Adaptive aggregation of flow records”](https://doi.org/10.4149/cai_2018_1_142), Computing and Informatics, vol. 37, no. 1, pp. 142–164, 2018.
   * S. Tremko, A. Pekár, J. Juhár, and J. Janitor, [“Reduction of ip flow information in network traffic monitoring systems”](https://doi.org/10.1109/ICETA.2014.7107616), in Proceedings of the 2014 12th IEEE International Conference on Emerging eLearning Technologies and Applications, ser. ICETA ’14, Dec. 2014, pp. 385–390.
   * A. Pekár, E. Chovancová, P. Fanfara, and J. Trelová, [“Issues in the passive approach of network traffic monitoring”](https://doi.org/10.1109/INES.2013.6632836), in Proceedings of the 2013 IEEE 17th International Conference on Intelligent Engineering Systems, ser. INES ’13, Jun. 2013, pp. 327–332.

---

**SLAmeter related manuscripts include:**
   * A. Pekár, P. Feciľak, M. Michalko, J. Giertl, and M. Révés, [“Slameter - the evaluator of network traffic parameters”](https://doi.org/10.1109/ICETA.2012.6418318), in Proceedings of the 2012 IEEE 10th International Conference on Emerging eLearning Technologies Applications, ser. ICETA ’12, Nov. 2012, pp. 291–295.
   * L. Vokorokos, J. Juhár, A. Pekár, Peter Feciľak, [“The Web Application of the SLAmeter Tool”](https://doi.org/10.1109/ICETA.2014.7107587), in Proceedings of the 2014 12th IEEE International Conference on Emerging eLearning Technologies and Applications, ser. ICETA '14, Dec. 2014, pp. 215-220.

---

**A manuscript on our data warehouse technique for improving network monitoring efficacy is:**
   * L. Vokorokos, A. Pekár, and N. Ádám, [“Data preprocessing for efficient evaluation of network traffic parameters”](https://doi.org/10.1109/INES.2012.6249860), in Proceedings of the 2012 IEEE 16th International Conference on Intelligent Engineering Systems, ser. INES '12, Jun. 2012, pp. 363–367.

---

**The specification of our Analyser-Collector Protocol (ACP) for streamlined forwarding of measurement data between the collector and analyser is provided in:**
   * A. Pekár, J. Giertl, M. Révés , P. Feciľak, [“Simplification of the Real-Time Network Traffic Monitoring”](papers/acp.pdf), Electrical Engineering and Informatics II, Proceedings of the Faculty of Electrical Engineering and Informatics of the Technical University of Kosice, Mar. 2011, pp. 272-277.

---

## MONICA Repositories

The project repositories (including the WIKI pages, Trac, and SVN) of MONICA were originally maintained by the members of the group and hosted by [CNL](https://www.cnl.sk). Due to the high maintanence demands, these servers were shut down in 2016 and the core repositories moved to the [GitLab](https://git.kpi.fei.tuke.sk/monica) repository of the university department. **Note that these GitLab repositories are available only in Slovak language!**

**In 2018, the core repositories of MONICA were moved again to GitHub. The tranlation of the repositories into English language is in progress** (last updated in December 2018). The repositories are as follow:

   * IPFIX Exporter developed by MONICA: [MyBeem](https://github.com/cnl-monica/mybeem)
   * IPFIX Collector developed by MONICA: [JXColl](https://github.com/cnl-monica/jxcoll)
   * IPFIX Traffic Analysis application: [SLAmeter-Evaluator]() (backend), [SLAmeter-WebApp]() (frontend)
