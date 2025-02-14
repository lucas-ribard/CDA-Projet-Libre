# Part 1 : Ideation
## Project: Simplified Network Monitoring Tool

### Project Overview  
An intuitive network monitoring tool designed to offer a **visually-driven** approach to packet analysis and network performance tracking.  
The application features:  

**Real-Time Packet Visualization**: Easily view and analyze network traffic through dynamic, graphical representations.   
**Hotspot Status Monitoring**: Keep track of Wi-Fi hotspot performance and connectivity at a glance.    
**Access Control Monitoring**: Simplify the supervision of restricted websites.    

This tool is built to **empower both novice and experienced** users to diagnose, analyze, and resolve network issues efficiently with an engaging and user-friendly interface.  
 
---
 
### Context and Problem Definition
In the field of computer security, **network monitoring is essential** to ensure the integrity and reliability of systems. However, existing tools (such as Wireshark) are often complex and require significant expertise to be used effectively. Therefore, there is a pressing need to simplify these tools to make them accessible to beginners while still providing advanced features such as the detection of suspicious activity and failure monitoring.

### Project Objectives :
- **Facilitate Network Monitoring:** Provide an intuitive tool that allows users, even those with little experience, to understand and analyze network traffic.
- **Proactive Anomaly Detection:** Integrate mechanisms to identify and alert users in the event of suspicious activity or network failures.
- **Simplification of Information:** Present network data in a clear and digestible manner to facilitate decision-making.

### Main Features :

#### Simplification of Information
- Simplified user interface.
- Visual and intuitive presentation of data.

#### Network Monitoring
- Continuous monitoring of network traffic.
- Real-time analysis of packets and network access.

#### Detection of Suspicious Activity
- Identification of abnormal behaviors.
- Implementation of rules and patterns recognized as dangerous.

#### Failure Monitoring
- Rapid detection of failures.
- Automatic notifications in the event of a failure or anomaly.

#### System Logging
- Logs of attacks and failures.
- This database can be used to record, analyze, and for machine learning purposes.

### Expected Results

#### Accessible Interface:
The final product is expected to offer an intuitive and user-friendly interface that clearly displays network monitoring data. The design will ensure that complex network information is presented in a comprehensible, visual format, making it accessible to users with limited technical expertise.

#### Effective Alert System:
The system should to feature a robust, real-time alert mechanism. This alert system will detect suspicious activity and operational failures immediately, providing notifications that enable users to respond swiftly and effectively to mitigate potential issues before they escalate.

#### Intelligent Database:
An intelligent database is expected to be integrated into the system, designed to store and analyze data on dangerous patterns and blocked sites. Over time, this continuously evolving database will enhance the overall security by learning from historical events and adapting to new threats.

### Constraints :
- **Project Duration:** 5 weeks.
- **Design Rules:** Adoption of clear coding standards, structured commits, and rigorous design methods to ensure the project's quality and maintainability.
- **Documentation:** Every step of the project must be thoroughly documented.

### Resources and Technologies

#### Tools and Libraries
- **Monitoring:** Use of proven tools such as Wireshark and libraries like Pyshark for packet capture and analysis.
- **Performance:** Compiling of the python source code in native C++ with the help of Cython for far greater performances.

#### Back-end
**Python:** Python was chosen for its simplicity and extensive library ecosystem, letting us develop powerful tool relatively quickly and spending more time on making the interface intuitive.

A server will run on the user computer, opening a website on the local network, this way the tool will be accesible on desktop and on smartphone.

#### Front-end
**[PWA](https://fr.wikipedia.org/wiki/Progressive_web_app)** : Cross-platform, simple, effective, easy maintenance.

**React :**

### Planning
- **Gantt Chart / Roadmap:** A detailed plan will be established to organize the various phases of the project (brainstorming, development, testing, etc.).
- **Database:** Provision for a dedicated table to store dangerous patterns and blocked sites to facilitate detection and alerts.

### Future Update Prospect
 - **Deep Learning for Threat Mitigation:**
Future iterations of the tool may integrate deep learning models to analyze network traffic patterns and predict emerging attack vectors. This AI-driven approach would allow the system to proactively counter threats by recognizing complex attack signatures and adapting its defenses in real time.

- **User Interface Enhancements:**
As the application evolves, additional focus on UI/UX improvements will further simplify complex data visualization. This might include customizable dashboards, advanced filtering options, and more intuitive navigation, ensuring that users can efficiently manage and monitor their networks regardless of expertise level.

- **Interoperability with Third-Party Security Tools:**
Future updates may offer enhanced compatibility with other network security and management systems. This would allow for seamless data sharing and correlation, fostering a more integrated and responsive security ecosystem.

### Conclusion
This project aims to democratize access to network monitoring tools by offering a simple, accessible, and effective solution. By combining an intuitive interface with robust technologies, we aspire to create a tool that meets current security needs while simplifying network management for less experienced users.
