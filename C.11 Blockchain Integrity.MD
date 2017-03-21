C.11 Blockchain Integrity
----------------

## (a) Blockchain integrity policy and procedures

1.	The organization develops, documents, and disseminates, to relevant personnel, a blockchain integrity policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance.

2.	The organization develops, documents, and disseminates, to relevant personnel, procedures to facilitate the implementation of the blockchain integrity policy and associated system and information integrity controls.

3.	The organization reviews and updates the current blockchain integrity policy and blockchain integrity procedures every 3 months.

## (b) Flaw remediation

1.	The organization identifies, reports, and corrects blockchain system flaws including those discovered during security assessments, continuous monitoring, incident response activities, and system error handling.

2.	The organization tests software and firmware updates related to flaw remediation for effectiveness and potential side effects before installation.

3.	The organization installs security-relevant software (e.g. patches, service packs, hot fixes, and anti-virus signatures) and firmware updates as soon as updates are released.

4.	The organization incorporates flaw remediation into the organizational configuration management process.

5.	The organization centrally manages the planning, implementing, assessing, authorizing, and monitoring the organization-defined, flaw remediation security controls.

6.	The organization employs automated mechanisms daily to determine the state of blockchain components with regard to flaw remediation.

7.	The organization measures the time between flaw identification and flaw remediation and establishes benchmarks for taking corrective actions.

8.	The organization installs relevant software and firmware updates automatically to blockchain components.

9.	The organization removes previous versions of software and/or firmware components after updated versions have been installed.

## (c) Malicious code protection

1.	The organization employs malicious code protection mechanisms at blockchain entry and exit points (e.g. firewalls, electronic mail servers, web servers, proxy servers, remote-access servers, workstations, notebook computers, and mobile devices) to detect and eradicate malicious code (e.g. viruses, worms, Trojan horses, and spyware; malicious code encoded in various formats such as UUENCODE, Unicode), contained within compressed or hidden files, or hidden in files using steganography).

2.	The organization updates malicious code protection mechanisms whenever new releases are available in accordance with organizational configuration management policy and procedures.

3.	The organization configures malicious code protection mechanisms to perform periodic and real-time scans of files from external sources as the files are downloaded, opened, or executed in accordance with organizational security policy. 

4.	The organization addresses the receipt of false positives during malicious code detection and eradication and the resulting potential impact on the availability of the blockchain.

5.	The organization centrally manages malicious code protection mechanisms.

6.	The organization tests malicious code protection mechanisms regularly by introducing a known benign, non-spreading test case into the blockchain and verifies that both detection of the test case and associated incident reporting occur.

7.	The blockchain implements non signature-based malicious code detection mechanisms (e.g. the use of heuristics to detect, analyze, and describe the characteristics or behavior of malicious code and to provide safeguards against malicious code for which signatures do not yet exist or for which existing signatures may not be effective) .

8.	The blockchain detects defined unauthorized operating system commands through the kernel application programming interface and (a) issues a warning; (b) audits the command execution; and (c) prevents the execution of the command.

9.	The organization analyzes the characteristics and behavior of malicious code; and incorporates the results from malicious code analysis into organizational incident response and flaw remediation processes.

## (d) Blockchain monitoring

1.	The organization monitors the blockchain to detect attacks and indicators of potential attacks in accordance and unauthorized local, network, and remote connections .

2.	The organization identifies unauthorized use of the blockchain.

3.	The organization deploys monitoring devices to collect organization-determined essential information and to track specific types of transactions of interest to the organization.

4.	The organization protects information obtained from intrusion-monitoring tools from unauthorized access, modification, and deletion.

5.	The organization heightens the level of blockchain monitoring activity whenever there is an indication of increased risk to organizational operations and assets.

6.	The organization obtains legal opinion with regard to monitoring activities in accordance with applicable laws.

7.	The organization provides monitoring information to relevant personnel as needed.

8.	The organization connects and configures individual intrusion detection tools into an information system-wide intrusion detection system.

9.	The organization employs automated tools (e.g. host-based, network-based, transport-based, or storage-based event monitoring tools or Security Information and Event Management (SIEM) technologies that provide real time analysis of alerts and/or notifications generated by blockchain) to support near real-time analysis of events.

10.	The organization employs automated tools to integrate intrusion detection tools into access control and flow control mechanisms for rapid response to attacks by enabling reconfiguration of these mechanisms in support of attack isolation and elimination.

11.	The blockchain monitors inbound and outbound communications traffic for unusual or unauthorized activities or conditions.

12.	The organization tests intrusion-monitoring tools every day.

13.	The organization analyzes outbound communications traffic at the external boundary of the blockchain to discover anomalies (e.g. large file transfers, long-time persistent connections, unusual protocols and ports in use, and attempted communications with suspected malicious external addresses).

14.	The organization employs automated mechanisms to alert security personnel of inappropriate or unusual activities with security implications.

15.	The organization analyzes communications traffic/event patterns for the blockchain; develops profiles representing common traffic patterns and/or events; and uses the traffic/event profiles in tuning system-monitoring devices to reduce the number of false positives and the number of false negatives.

16.	The organization employs a wireless intrusion detection system to identify rogue wireless devices and to detect attack attempts and potential compromises/breaches to the blockchain.

17.	The organization employs an intrusion detection system to monitor wireless communications traffic as the traffic passes from wireless to wired networks.

18.	The organization correlates information from monitoring tools (e.g., host monitoring, network monitoring, anti-virus software) employed throughout the components of the blockchain.

19.	The organization correlates information from monitoring physical, cyber, and supply chain activities to achieve integrated, organization-wide situational awareness.

20.	The organization analyzes outbound communications traffic at the external boundary of the blockchain to detect covert exfiltration of information.

21.	The organization implements additional monitoring of individuals who have been identified by relevant sources (such as human resource records, intelligence agencies, law enforcement organizations, and/or other credible sources) as posing an increased level of risk.

22.	The organization implements additional monitoring of privileged users and individuals during probationary period.

23.	The organization implements host-based monitoring mechanisms at defined blockchain components.

24.	The blockchain discovers, collects, distributes, and uses indicators of compromise .

## (e) Security alerts, advisories, and directives

1.	The organization receives security alerts, advisories, and directives from relevant external organizations on an ongoing basis.

2.	The organization generates internal security alerts, advisories, and directives as deemed necessary.

3.	The organization disseminates security alerts, advisories, and directives to relevant personnel and external organizations.

4.	The organization employs automated mechanisms to make security alert and advisory information available throughout the organization.

## (f) Security function verification

1.	The organization verifies the correct operations of defined security functions at blockchain transitional states (e.g. system startup, restart, shutdown, and abort) upon command by user with appropriate privilege.

2.	The organization notifies relevant personnel of failed security verification tests.

3.	The information system implements automated mechanisms to support the management of distributed security testing.

4.	The organization reports the results of security function verification to relevant personnel.

## (g) Software, firmware, and information integrity

1.	The organization employs integrity verification tools to detect unauthorized changes to software, firmware, and information  using state-of-the-practice integrity-checking mechanisms (e.g., parity checks, cyclical redundancy checks, cryptographic hashes) and associated tools. 

2.	The organization employs automated tools that provide notification to relevant personnel upon discovering discrepancies during integrity verification.

3.	The organization employs centrally managed integrity verification tools.

4.	The blockchain implements cryptographic mechanisms (e.g. digital signatures and the computation and application of signed hashes using asymmetric cryptography, protecting the confidentiality of the key used to generate the hash, and using the public key to verify the hash information).

5.	The organization incorporates the detection of unauthorized security-relevant changes to the blockchain into the organizational incident response capability.

6.	The blockchain verifies the integrity of the boot process of defined devices.

7.	The organization implements defined security safeguards to protect the integrity of boot firmware in defined devices.

8.	The organization requires that defined user-installed software execute in a confined physical or virtual machine environment with limited privileges.  

9.	The organization requires that the integrity of user-installed software be verified prior to execution.

10.	The organization allows execution of binary or machine-executable code obtained from sources with limited or no warranty and without the provision of source code only in confined physical or virtual machine environments and with the explicit approval of relevant personnel.

11.	The organization implements cryptographic mechanisms to authenticate software or firmware components prior to installation.
