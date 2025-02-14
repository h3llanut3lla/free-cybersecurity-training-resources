---
icon: square-rss
description: >-
  This page provides practical guidance and resources on how to stay up-to-date
  with the ever-changing landscape of cyber threats.
---

# Staying Informed about Emerging Cyber Threats

## &#x20;**Threat Intelligence Sources**

* **CISA:** Subscribe to their email alerts (e.g., the CISA Insights and Alerts) and regularly check their website for advisories on newly discovered vulnerabilities and exploits. _Example:_ You see a CISA alert about a zero-day vulnerability in a popular web application framework. You immediately check if your organization uses that framework and prioritize patching if necessary.
* **Security Vendor Blog (CrowdStrike):** CrowdStrike's blog often details APT (Advanced Persistent Threat) activity. _Example:_ You read a post about a new APT group targeting the healthcare sector. You proactively review your network logs for indicators of compromise (IOCs) associated with that group.
* **Threat Intelligence Platform (Recorded Future):** You set up alerts in Recorded Future to notify you of any mentions of ransomware targeting your industry. _Example:_ You receive an alert about a new ransomware variant being used against similar organizations. You update your endpoint detection and response (EDR) rules to detect and prevent this variant.
* **OSINT (Twitter):** You follow security researchers who specialize in malware analysis. _Example:_ You see a tweet from a researcher about a new strain of malware being spread through phishing emails. You inform your security awareness training team to emphasize caution around suspicious emails.

## **Government and Public Sector**

* **CISA (Cybersecurity and Infrastructure Security Agency):** US-based, but their alerts and advisories are relevant globally. Excellent for vulnerability warnings and incident response guidance. (cisa.gov)  &#x20;
* **NIST (National Institute of Standards and Technology):** Provides frameworks, best practices, and vulnerability databases (NVD). A valuable resource for technical details. (nist.gov)  &#x20;
* **FBI (Federal Bureau of Investigation):** While focused on US threats, they often release information about significant cybercriminal activity. (fbi.gov)  &#x20;
* **NSA (National Security Agency):** (nsa.gov) Though less public-facing, they occasionally share threat information, especially related to nation-state actors.  &#x20;
* **International Counterparts:** Most countries have their own cyber defense agencies (e.g., NCSC in the UK, ACSC in Australia). These are crucial for region-specific threat intelligence.  &#x20;

## **Commercial Threat Intelligence Providers**

* **CrowdStrike:** Known for their in-depth research on APT groups and advanced malware.  &#x20;
* **Mandiant (now part of Google Cloud):** Highly regarded for their incident response expertise and threat research.  &#x20;
* **Recorded Future:** Aggregates and analyzes threat data from numerous sources, providing predictive threat intelligence.  &#x20;
* **ThreatConnect:** Offers a platform for collecting, analyzing, and sharing threat intelligence.  &#x20;
* **Palo Alto Networks Unit 42:** Provides threat research and analysis, particularly on advanced threats.  &#x20;
* **Proofpoint:** Strong in email security and phishing threat intelligence.  &#x20;
* **Rapid7:** Offers threat intelligence related to vulnerabilities and exploits, often tied to their vulnerability management tools.  &#x20;

## **Open-Source and Community-Driven**

* **MITRE ATT\&CK:** A knowledge base of adversary tactics, techniques, and procedures (TTPs). Invaluable for understanding attacker behavior. (attack.mitre.org)  &#x20;
* **OWASP (Open Web Application Security Project):** Focuses on web application security vulnerabilities and threats. (owasp.org)
* **SANS ISC SANS Internet Storm Center:** Provides timely alerts and analysis of internet-wide security events. (isc.sans.edu)  &#x20;
* **Threat Feeds:** Many organizations and individuals share threat data (IOCs, malware hashes, etc.) via threat feeds.These can be integrated into your security tools.  &#x20;

## Open-Source Threat Feeds

Open-source threat feeds are a valuable resource for cybersecurity professionals and enthusiasts.1 They provide a stream of data about potential threats, such as malicious IP addresses, domain names, file hashes, and other indicators of compromise (IOCs).2 Here are some commonly used and respected open-source threat feeds:

### **General Purpose Threat Feeds**

* **AlienVault Open Threat Exchange (OTX):** A large and well-established threat intelligence platform with a wide range of threat feeds contributed by the community.3 ([otx.alienvault.com](https://www.google.com/search?q=otx.alienvault.com))
* **Feodo Tracker:** Tracks various botnets and malware families, providing information on command-and-control servers and associated IOCs.4 (feodotracker.eu)5
* **Abuse.ch:** Offers a variety of threat feeds, including lists of malicious IP addresses, domain names, and URLs.6 (abuse.ch)
* **ThreatFox:** A free and open platform for sharing threat intelligence.7 It aggregates data from multiple sources. (threatfox.abuse.ch)

### **Malware-Focused Feeds**

* **Malware Bazaar:** A project from abuse.ch that shares malware samples and associated metadata, including file hashes and detection information.8 (bazaar.abuse.ch)
* **VirusTotal:** While not strictly a threat feed, VirusTotal provides a wealth of information about files, URLs, and domains, including antivirus scan results and community feedback.9 This can be very useful for malware analysis. ([virustotal.com](https://www.google.com/search?q=virustotal.com))

### **IP Address and Network-Focused Feeds**

* **Blocklist.de:** Provides various blocklists of IP addresses known to be involved in malicious activity.10 (blocklist.de)
* **Emerging Threats:** Offers a variety of threat feeds, including lists of malicious IP addresses and network traffic signatures.11 (rules.emergingthreats.net)

### **Domain and URL Feeds**

* **PhishTank:** A collaborative platform for sharing phishing URLs.12 ([phishtank.com](https://www.google.com/search?q=phishtank.com))
* **URLVoid:** Provides information about the reputation of URLs and domains. (urlvoid.com)

### **Other Useful Feeds**

* **Tor Exit Node List:** A list of Tor exit nodes, which can be useful for identifying potentially suspicious traffic.13 (torproject.org)

### **Key Considerations When Using Open-Source Threat Feeds**

* **Reliability:** The quality and accuracy of open-source threat feeds can vary.14 It's important to evaluate the reputation of the source and the data it provides.
* **Attribution:** Understand the source of the data and how it was collected.
* **Format:** Threat feeds are typically provided in various formats, such as text files, CSV files, or STIX. Make sure you can integrate the data into your security tools.
* **Integration:** Use threat intelligence platforms or security tools to automate the process of collecting, processing, and using threat feed data.15
* **False Positives:** Be prepared for false positives, as some threat feeds may contain inaccurate or outdated information.
* **Combining Feeds:** Using multiple threat feeds can provide a more comprehensive view of the threat landscape.16

### **Best Practices**

* **Verify Data:** Always verify threat feed data before taking action based on it.
* **Use Multiple Feeds:** Combine multiple reputable feeds to improve accuracy and coverage.17
* **Integrate with Security Tools:** Integrate threat feeds with your SIEM, firewalls, and other security tools to automate threat detection and response.18
* **Regularly Update:** Threat feed data changes rapidly, so make sure you update your feeds regularly.19

Open-source threat feeds can be a valuable addition to your threat intelligence strategy, providing real-time information about potential threats. By carefully selecting and integrating these feeds, you can enhance your ability to detect and respond to cyberattacks.

## **Security News and Publications**

* **Threatpost:** You read an article on Threatpost about a rise in phishing attacks targeting small businesses. _Example:_ You review your organization's email filtering rules and consider implementing additional anti-phishing measures.
* **Krebs on Security:** Brian Krebs often reports on major data breaches. _Example:_ After reading about a breach caused by weak passwords, you remind your employees about the importance of u
* **The Hacker News:** Delivers daily cybersecurity news, vulnerability reports, and information on new attack techniques. (thehackernews.com)
* **BleepingComputer:** Covers security news, malware analysis, and vulnerability disclosures. (bleepingcomputer.com)
* **Dark Reading:** Provides insights and analysis on enterprise security topics, with a focus on strategy and management. (darkreading.com)
* **CSO Online:** Offers news, analysis, and opinion pieces on cybersecurity, with a focus on business and enterprise security. (csoonline.com)
* **SearchSecurity (TechTarget):** Covers a broad range of security topics, including data breaches, compliance, and risk management. (searchsecurity.techtarget.com)

<details>

<summary>Using <a href="https://feedly.com">Feedly</a></summary>

Feedly is a great tool for keeping up with cybersecurity news.&#x20;

First, create a free account at feedly.com.&#x20;

Then, find sources by searching keywords like "cybersecurity news" or the names of publications (e.g., "Threatpost").&#x20;

You can also browse categories or import a list of feeds. Subscribe to the sources you like by clicking "+ Follow."&#x20;

Organize these into collections (like folders) such as "General News," "Threat Intel," or "Vulnerability Management."&#x20;

</details>

## **Community Engagement and Networking**

* **Black Hat Conference:** You attend a Black Hat talk on new attack techniques targeting cloud environments. _Example:_ You learn about a new attack vector and discuss with your cloud security team how to mitigate this risk in your organization's cloud infrastructure.
* **Reddit (r/netsec):** You see a discussion on Reddit about a new vulnerability in a popular open-source library. _Example:_ You check if your organization uses that library and prioritize patching if needed.

## **Continuous Learning**

* **Coursera Course:** You take a Coursera course on incident response to improve your ability to handle security incidents related to emerging threats.
* **CTF Competition:** You participate in a CTF competition that includes challenges related to malware analysis, helping you better understand how malware works and how to detect it.

## **Tools and Technologies**

* **SIEM System:** You configure your SIEM system to alert you on suspicious network traffic patterns that might indicate a botnet or other malicious activity.
* **Vulnerability Scanner:** You run regular vulnerability scans on your systems to identify and address any newly discovered vulnerabilities.

## **Tailoring Your Approach - Examples:**

* **Industry Focus:** If you work in the financial industry, you pay close attention to threats targeting financial institutions, such as banking Trojans and credit card skimming.
* **Threat Intelligence Process:** Your organization develops a process for sharing threat intelligence with relevant teams, so that security operations, incident response, and vulnerability management teams are all aware of emerging threats and can take appropriate action.

By applying these examples to your own situation, you can develop a comprehensive strategy for staying informed about emerging cyber threats and protecting your organization.



