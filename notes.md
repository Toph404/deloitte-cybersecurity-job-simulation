# **Analysis Notes – Telstra Cyber Analyst Job Simulation**

## **Task Summary**
- Responded to a live malware alert affecting nbn services running the Spring Framework.  
- Triaged the incident and communicated findings to the relevant teams.  
- Analyzed firewall logs and identified consistent malicious request patterns tied to **Spring4Shell (CVE-2022-22965)**.  
- Implemented a Python-based firewall rule to detect and block exploit traffic.  
- Documented a full incident postmortem report outlining impact, mitigation, and lessons learned.  

---

## **Key Insights**
- Learned how to analyze structured firewall log data and identify exploit signatures.  
- Understood how distributed attacks require behavior-based filtering instead of IP blocking.  
- Gained hands-on experience building custom firewall logic using Python’s `http.server` module.  
- Practiced clear incident communication between SOC, Networks, and Application Security teams.  
- Strengthened post-incident documentation and reporting skills.  

---

## **Reflection**
During the **Telstra Cyber Analyst Job Simulation**, I worked through a realistic SOC scenario involving a **Spring4Shell malware attack** that caused downtime across nbn services. I began by triaging alerts, identifying the attack pattern in the logs, and drafting targeted communication to the appropriate response teams.  

The most challenging part was fine-tuning the **Python firewall rule** — making sure it caught all malicious payloads (e.g., `/tomcatwar.jsp`, `suffix=%>//`, `c1=Runtime`, `c2=<%`) — without blocking legitimate traffic. I also spent extra time understanding how the **Spring Framework vulnerability** was exploited, using resources from Spring.io and CISA to validate indicators.  

This exercise reinforced both the **technical** and **communication** sides of cybersecurity work — writing concise alerts, performing log-based threat analysis, implementing controls, and documenting outcomes for post-incident learning.  

---

## **Key Takeaways**
- Improved understanding of **zero-day exploit behavior** and mitigation strategy design.  
- Strengthened skills in **log analysis**, **pattern recognition**, and **Python-based automation**.  
- Gained practical insight into **SOC workflows**, from detection through to incident closure.  
- Recognized the importance of **clear communication** during high-severity incidents.  
