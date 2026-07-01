# POC Portfolio

A collection of infrastructure automation scripts, security simulation tools, and virtual lab configurations targeting Windows Server 2022 and enterprise Linux environments.

## Projects

### 1. Offensive Security & Adversary Simulation Engineering

* **Drac's Eye | Custom C2 Research Framework**
  An offensive Command and Control (C2) simulation framework built from the ground up to research adversary techniques, validate defensive posture, and demonstrate how advanced threats maintain persistence and execute post-exploitation activities in controlled environments.
  * **Centralized Session Orchestration:** A custom control plane interface designed to monitor, track, and manage persistent agent beacons across simulated target environments.
  * **Defensive Evasion Research:** Implements conceptual runtime memory patching mechanics—including AMSI (Antimalware Scan Interface) and ETW (Event Tracing for Windows) bypasses—to analyze how modern endpoints detect evasion techniques.
  * **Post-Exploitation Triage Modules:** Features modular capability testing for security assessment, including local credential auditing (browser, credential manager, and Wi-Fi data), keystroke capture simulation, and hardware telemetry gathering (webcam/microphone validation).
  * **Lateral Reconnaissance Engine:** Embedded network assessment utilities, such as automated ARP scanning, allowing security operators to map out adjacent live hosts from a compromised node during internal assessments.

[![Drac's Eye Showcase](https://img.youtube.com/vi/tzHiZBDCOCE/0.jpg)](https://www.youtube.com/watch?v=tzHiZBDCOCE)

---

### 2. Security & Threat Intelligence Engineering

* **Dracs-GEO | Geolocation & Threat Intelligence Tool**
  A real-time threat intelligence application designed to aggregate, visualize, and analyze malicious network traffic. Users can ingest bulk IP address data to assess global risk vectors.
  * **Interactive Visualization:** Dynamic mapping interface tracking geographic traffic origins.
  * **Intelligence Reporting:** Instant metadata extraction for ISPs, Autonomous System Numbers (ASNs), geographic regions, and hosting providers.
  * **Data Export:** Generates structured threat intelligence reports into local text files for forensic analysis.
  
  [![Dracs GEO Showcase](https://img.youtube.com/vi/8aEjsWjwrtI/0.jpg)](https://www.youtube.com/watch?v=8aEjsWjwrtI)

* **Dracs-IDS | Network Intrusion Detection System**
  A custom-developed network intrusion detection suite built for live traffic analysis and protocol monitoring.
  * **Real-Time Telemetry:** Live visualization of packet flow and network activity.
  * **Signature & Behavioral Detection:** Automated identification of malicious patterns (e.g., SYN floods, ARP spoofing, and port scanning) with categorized severity alerts (Low to Critical).
  * **Network Reconnaissance Interface:** Integrated Nmap support for managed asset scanning, customizable port thresholds, and IP blacklisting capabilities.
  
  [![Dracs IDS Showcase](https://img.youtube.com/vi/05C5EWmmYpI/0.jpg)](https://www.youtube.com/watch?v=05C5EWmmYpI)

* **Dracs-VmMt | Virtual Machine Management & Orchestration**
  A centralized control plane and orchestration tool for managing virtual sandboxes across Type-2 hypervisors (VirtualBox and VMware).
  * **Batch Lifecycle Operations:** Automated mass startup, teardown, and individual execution control for target VMs.
  * **Network Mapping Lookup:** Integrated dashboard tracking NAT port forwarding rules, enabling rapid SSH access without manual hypervisor inspection.
  
  [![Dracs VmMt Showcase](https://img.youtube.com/vi/xXHvN6mT1cM/0.jpg)](https://www.youtube.com/watch?v=xXHvN6mT1cM)

### 3. Identity & Access Management (IAM) Automation
* **ActiveDirectory-Mass-Provisioning-Script:** PowerShell script automating the generation of 1,000+ user objects, directory structures, and OU management.
![AD Mass Provisioning Screenshot](./ActiveDirectory-Mass-Provisioning-Script.jpeg)

* **CSV-to-AD-Bulk-Importer:** Identity migration tool utilizing structured `try/catch` exception handling to manage pre-existing directory accounts and formatting anomalies.
![CSV to AD Importer Screenshot](./CSV-to-AD-Bulk-Importer.jpeg)

### 4. Advanced Networking & Lab Infrastructure
* **Multi-Distro-VirtualBox-Lab:** Configured and maintained virtualized test networks running heterogeneous Linux distributions (Arch, Kali, Debian, Ubuntu, Fedora Server).
![VirtualBox Environment](./virtualbox-labs.jpeg)

* **Edge NAT Port Forwarding:** Implementation of custom NAT routing schemas (e.g., mapping Host Port `2224` to Guest Port `22`) to provide secure external access to isolated host segments.
![Port Forwarding Config](./port-forwarding-config.jpeg)

* **Inventory Tracking Script:** A companion script mapping current host/guest socket connections to simplify lab inventory tracking.
![Lab Management Tool Screenshot](./Lab%20Management%20Tool.jpeg)

## Proof of Concept
This portfolio includes a collection of video demonstrations and verified screenshots showcasing my custom offensive research simulation frameworks, geolocation threat intelligence tools, real-time network intrusion detection, virtual machine orchestration, type 2 hypervisor configurations, network routing rules, and Active Directory scripting environments.
