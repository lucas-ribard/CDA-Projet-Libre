# Part 1 : Ideation
## Project: Simplified Network Monitoring Tool

### Context and Problem Definition
In the field of computer security, network monitoring is essential to ensure the integrity and reliability of systems. However, existing tools (such as Wireshark) are often complex and require significant expertise to be used effectively. Therefore, there is a pressing need to simplify these tools to make them accessible to beginners while still providing advanced features such as the detection of suspicious activity and failure monitoring.

### Project Objectives :
- **Facilitate Network Monitoring:** Provide an intuitive tool that allows users, even those with little experience, to understand and analyze network traffic.
- **Proactive Anomaly Detection:** Integrate mechanisms to identify and alert users in the event of suspicious activity or network failures.
- **Simplification of Information:** Present network data in a clear and digestible manner to facilitate decision-making.

### Main Features :

#### Network Monitoring
- Continuous monitoring of network traffic.
- Real-time analysis of packets and network access.

#### Simplification of Information
- Simplified user interface.
- Visual and intuitive presentation of data.

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
- **Accessible Interface:** A program capable of monitoring the network and presenting information in a way that is understandable, even for novices.
- **Effective Alert System:** Real-time detection of suspicious activity and failures, with notifications enabling a rapid response.
- **Intelligent Database:** A storage system for dangerous patterns or blocked sites to continuously enhance security.

### Constraints :
- **Project Duration:** 5 weeks.
- **Design Rules:** Adoption of clear coding standards, structured commits, and rigorous design methods to ensure the project's quality and maintainability.
- **Documentation:** Every step of the project must be thoroughly documented.

### Resources and Technologies

#### Tools and Libraries
- **Monitoring:** Use of proven tools such as Wireshark and libraries like Pyshark for packet capture and analysis.
- **Performance:** Compiling of the python source code in native C++ with the help of Cython for far greater performances.

#### Back-end
- **Python:** Chosen for its simplicity and extensive library ecosystem.

#### Front-end
- **React Native:** For the development of a modern and responsive user interface.

### Planning
- **Gantt Chart / Roadmap:** A detailed plan will be established to organize the various phases of the project (brainstorming, development, testing, etc.).
- **Database:** Provision for a dedicated table to store dangerous patterns and blocked sites to facilitate detection and alerts.

### Conclusion
This project aims to democratize access to network monitoring tools by offering a simple, accessible, and effective solution. By combining an intuitive interface with robust technologies, we aspire to create a tool that meets current security needs while simplifying network management for less experienced users.
