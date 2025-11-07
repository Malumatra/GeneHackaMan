---

## 3. Detailed Domain Breakdown

### 📂 `00_Foundational_Concepts`
This section covers the core principles that underpin all of cybersecurity.

*   **Core Principles:**
    *   `cia_triad.md` (Confidentiality, Integrity, Availability)
    *   `aaa_model.md` (Authentication, Authorization, Accounting)
    *   `non_repudiation.md`
    *   `principle_of_least_privilege.md`
    *   `defense_in_depth.md`
*   **Risk Management:**
    *   `threat_vs_vulnerability_vs_risk.md`
    *   `risk_assessment_basics.md`
*   **Security Models:**
    *   `zero_trust_model.md`
    *   `bell-lapadula_model.md`

### 📂 `01_Networking_and_Protocols`
A deep understanding of networking is essential for cybersecurity.

*   **Core Models:**
    *   `osi_model.md`
    *   `tcp_ip_model.md`
*   **Key Protocols & Services:**
    *   `http_https.md`
    *   `dns.md`
    *   `ssh_scp_sftp.md`
    *   `ftp_ftps.md`
    *   `smb.md`
    *   `dhcp.md`
    *   `icmp.md`
*   **Network Infrastructure:**
    *   `firewalls.md`
    *   `routers_and_switches.md`
    *   `proxies_and_reverse_proxies.md`
    *   `virtual_private_networks_vpn.md`
    *   `network_address_translation_nat.md`

### 📂 `02_Cryptography`
This section details the science of secure communication.

*   **Concepts:**
    *   `encryption_vs_hashing.md`
    *   `symmetric_cryptography.md`
    *   `asymmetric_cryptography.md` (Public-Key Cryptography)
    *   `hashing_algorithms.md`
    *   `digital_signatures.md`
    *   `public_key_infrastructure_pki.md`
*   **Common Algorithms:**
    *   `aes.md` (Advanced Encryption Standard)
    *   `rsa.md` (Rivest–Shamir–Adleman)
    *   `sha-256.md` (Secure Hash Algorithm)
    *   `tls_ssl.md` (Transport Layer Security)

### 📂 `03_Offensive_Security`
This section covers the methodologies, tactics, and techniques used by ethical hackers and malicious actors to compromise systems.

*   **Penetration Testing Methodologies:**
    *   `penetration_testing_execution_standard_ptes.md`
    *   `osstmm.md` (Open Source Security Testing Methodology Manual)
    *   `kill_chain_methodology.md`
*   **Phases of Hacking:**
    *   **Reconnaissance:**
        *   `passive_reconnaissance_osint.md`
        *   `active_reconnaissance.md`
    *   **Scanning_and_Enumeration:**
        *   `port_scanning.md`
        *   `vulnerability_scanning.md`
        *   `network_mapping.md`
        *   `service_and_os_enumeration.md`
    *   **Gaining_Access_Exploitation:**
        *   `social_engineering.md` (Phishing, Vishing, Pretexting)
        *   `password_attacks.md` (Brute Force, Dictionary, Credential Stuffing, Password Spraying)
        *   `malware.md` (Viruses, Worms, Trojans, Ransomware, Spyware)
        *   `web_application_attacks.md` (SQL Injection, Cross-Site Scripting (XSS), CSRF, Directory Traversal)
        *   `network_attacks.md` (Man-in-the-Middle, DoS/DDoS, ARP Poisoning)
        *   `buffer_overflows.md`
    *   **Maintaining_Access:**
        *   `persistence_mechanisms.md`
        *   `privilege_escalation.md`
        *   `backdoors_and_rootkits.md`
    *   **Covering_Tracks:**
        *   `log_manipulation.md`
        *   `steganography.md`

### 📂 `04_Defensive_Security`
This section focuses on the tools, strategies, and procedures for protecting systems.

*   **Threat Detection & Monitoring:**
    *   `siem_systems.md` (Security Information and Event Management)
    *   `ids_and_ips.md` (Intrusion Detection/Prevention Systems)
    *   `log_analysis.md`
    *   `endpoint_detection_and_response_edr.md`
*   **Incident Response:**
    *   `incident_response_lifecycle.md` (Preparation, Identification, Containment, Eradication, Recovery, Lessons Learned)
*   **System & Network Hardening:**
    *   `os_hardening.md` (Windows, Linux)
    *   `secure_configuration.md`
    *   `patch_management.md`
*   **Digital Forensics:**
    *   `forensics_process.md`
    *   `chain_of_custody.md`
    *   `memory_forensics.md`
    *   `disk_forensics.md`

### 📂 `05_Cyber_Threats_and_Actors`
This section categorizes and describes the landscape of cyber threats.

*   **Threat Actors:**
    *   `script_kiddies.md`
    *   `hacktivists.md`
    *   `organized_cybercrime.md`
    *   `advanced_persistent_threats_apts.md`
*   **Threat Intelligence:**
    *   `indicators_of_compromise_iocs.md`
    *   `ttps_and_mitre_attck_framework.md`

### 📂 `06_Tools_and_Technologies`
A repository of knowledge about the specific software and scripts used in the field.

*   **Offensive Tools:**
    *   `nmap.md`
    *   `metasploit_framework.md`
    *   `wireshark.md`
    *   `burp_suite.md`
    *   `john_the_ripper.md`
    *   `hashcat.md`
*   **Defensive Tools:**
    *   `snort.md`
    *   `security_onion.md`
    *   `splunk.md`
    *   `autopsy.md`
*   **Programming & Scripting:**
    *   `python_for_cybersecurity.md` (Scapy, Requests, Sockets)
    *   `bash_scripting_for_automation.md`
    *   `powershell_for_security.md`

### 📂 `07_Governance_Risk_and_Compliance`
This covers the business and regulatory side of cybersecurity.

*   **Frameworks & Standards:**
    *   `nist_cybersecurity_framework.md`
    *   `iso_27001-27002.md`
    *   `pci_dss.md` (Payment Card Industry Data Security Standard)
    *   `gdpr_and_data_privacy.md` (General Data Protection Regulation)
    *   `soc_2.md` (Service Organization Control 2)

### 📂 `08_Specialized_Domains`
Advanced or niche topics in cybersecurity.

*   `cloud_security.md` (AWS, Azure, GCP Security Models)
*   `mobile_security.md` (Android & iOS)
*   `iot_security.md` (Internet of Things)
*   `ics_scada_security.md` (Industrial Control Systems)
*   `ai_in_cybersecurity.md` (Using AI for defense and the threat of AI in attacks)

## 4. Interconnectivity and Contribution

Contributors should actively link between related topics to build a rich, web-like knowledge graph. For example, the `nmap.md` file should link to `port_scanning.md` and `active_reconnaissance.md`. This contextual linking is vital for the AI's ability to form connections and reason about the domain. All entries must adhere to the `CONTRIBUTING.md` guidelines and use the standard data entry template.
