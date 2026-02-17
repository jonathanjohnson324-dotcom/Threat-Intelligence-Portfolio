REPORT: 00 <br/>
DATE: mm/dd/yy  <br/>
PRIORITY: Low  <br/>
SENSITIVITY: Standard  <br/><br/><br/>



# Executive Summary 
A brief summary of the report. It should explain the report’s significance, create a simple, easy-to-follow narrative of its key findings, and support a single decision. The reader should be able to make an informed decision based entirely on this summary.


## Key Takaways
<ul>
<li> Who is the report for? </li>
<li> Source of data collected </li>
<li> Attacker </li>
<li> Why does this report matter to the targeted audience? </li>
<li> Main takaway from report? </li>
</ul>


<table>
<tr> <td>Intelligence Requirements Addressed </td>	<td> Citation of the IR addressed by this report </td> </tr> 
<tr> <td> Data Sources  </td>                       <td></td>	</tr>                      
<tr> <td> Threat Actor </td>                        <td> Primary threat actor (and aliases) or N/A or Unknown </td> </tr> 
<tr> <td> Victim Location </td>	                  <td> Country of Victim </td> </tr> 
<tr> <td> Sectors </td>                            <td> Industry Targeted </td> </tr> 
<tr> <td> Actor Motivation </td>	                   <td> Cybercrime / Espionage / Hacktivism / Ransomware / ICS / Other / Unknown </td> </tr> 
</table>
<img width="900" height="537" alt="image" src="https://github.com/user-attachments/assets/ca963f39-a1de-4658-9277-d810194aaacf" />

Capabilities                          <MITRE technique, malware, hacking tool> <br/>
Adversary                             <Threat Actor, alias, email address, persona> <br/>
Infrastructure 	                      <IP address, domain name, URL, C2 server> <br/>
Victim                                <company, workstation/server name, email address, > <br/>
 	 	 	

### Intelligence Assessment
This section should include: 

<ul>
<li> A call to action, recommendation, or judgment: This threat (e.g., activity, threat actor, malware, etc.) demonstrates X and could potentially impact us. Therefore, we should do Y.  </li>
<li> Any new information: This threat has a new tool, capability, TTP, etc. </li>
<li> Key evidence: The threat has the following characteristics that uniquely distinguish it. </li>
<li> Estimative language (see Probability Matrix): “I assess with a <low/medium/high> level of certainty that < judgment> will impact us <impact>.”  </li>
<li> Background information: Any relevant background information about the threat actor, malware, TTP, etc., to give context to this new assessment. </li>
<li> Relations to your organization: How does this threat relate to your organization? Does it target your country or sector? Does it target vulnerabilities in the systems or technologies you use? Does it relate to any previous security incidents or detections? </li>
</ul>
<br/>
  
This section should include a kill chain analysis technique like Lockheed Martin’s Cyber Kill Chain. List the IOCs or TTPs found at each stage of the attack to create an attack narrative for the reader. The security operations team can then use this to identify possible mitigations or gaps.

<table> 
<th> Cyber Kill Chain </th> 
<tr> <td> S1: Reconnaissance  </td> <td></td>  	 </tr>
<tr> <td> S2: Weaponization </td> <td></td>  	 </tr>
<tr> <td> S3: Delivery </td> <td></td>  </tr>	 
<tr> <td> S4: Exploitation </td>  <td></td>  </tr>	 
<tr> <td> S5: Installation </td> <td></td>  </tr>	 
<tr> <td> S6: Command & Control (C2)</td> <td></td>   </tr>	 
<tr> <td> S7: Actions on Objectives </td> <td></td> 	</tr> 
</table>

### Key Intelligence Gaps

A bulleted list that summarizes additional information the CTI team needs to complete their analysis and raise the confidence of the assessment. You should highlight gaps affecting the assessment, such as if new information is discovered or existing information is proven wrong.  

These gaps should be tracked externally from the report using a project/task management system. 


### Indicators of Compromise (IOCs)

This section consists of IOCs found on endpoint devices (workstations, servers, mobile devices), in network logs, related malware, and any vulnerabilities relevant to the threat being discussed.  

### Endpoint Artifacts
A list of any unique artifacts associated with the threat that can be found on endpoint devices through intrusion analysis. This includes process names, filenames, DLLs, registry keys, scheduled tasks, command lines, services, etc. Use the MITRE ATT&CK tactic for the Tactic column. 

<table>
<tr> 
<th> Endpoint </th>   <th> Type </th>  <th> Description </th> <th> Tactics </th> 
</tr> 
<tr> <td></td> <td></td> <td></td> <td></td> </tr>
<tr> <td></td> <td></td> <td></td> <td></td> </tr>
<tr> <td></td> <td></td> <td></td> <td></td> </tr>
</table>


### Network Artifacts
A list of any unique artifacts associated with the threat that can be found in network logs. This includes IP addresses, domain names, email addresses, URLs, etc. Use Recon, Delivery, C2, AoO – Exfiltration, etc. for the Kill Chain Stage column. 

<table>
<tr> 
<th> Endpoint </th>   <th> Type </th>  <th> Description </th> <th> Kill Chain </th> 
</tr> 
<tr> <td></td> <td></td> <td></td> <td></td> </tr>
<tr> <td></td> <td></td> <td></td> <td></td> </tr>
<tr> <td></td> <td></td> <td></td> <td></td> </tr>
</table>

### Malware
A list of any malware or hacking tools associated with the threat.  The Malware Analysis Report could be a link to an internal report or an external hyperlink. The Kill Chain Stage includes Recon, Delivery, Exploitation, Installation, C2, AoO – Exfiltration, AoO – Ransomware, etc.  

<table>
<tr> 
<th> Malware </th>   <th> Hash Type </th>  <th> File Hash </th> <th> Description </th> <th> Malware Analysis Report </th> <th>Kill Chain Stage</th>
</tr> 
<tr> <td></td> <td></td> <td></td> <td></td> <td></td> <td></td> </tr>
<tr> <td></td> <td></td> <td></td> <td></td> <td></td> <td></td> </tr>
<tr> <td></td> <td></td> <td></td> <td></td> <td></td> <td></td> </tr>
</table>

### Common Vulnerabilities and Exposures (CVEs)
A list of CVEs associated with the threat. Completing this section may require help from other teams (e.g., vulnerability management). 

<table>
<tr> 
<th> CVE Number </th>  <th> CVSS Score </th>  <th> Patch Available (Y or N) </th> <th> Remediation </th> <th> Date Reported </th> <th>Patch Applied (Y or N or N/A) </th>
</tr> 
<tr> <td></td> <td></td> <td></td> <td></td> <td></td> <td></td> </tr>
<tr> <td></td> <td></td> <td></td> <td></td> <td></td> <td></td> </tr>
<tr> <td></td> <td></td> <td></td> <td></td> <td></td> <td></td> </tr>
</table>

### MITRE ATT&CK Techniques
This section lists the MITRE ATT&CK techniques relevant to the threat broken into tactics, techniques, and procedures (TTPs). It also contains the MITRE D3FEND countermeasure that can be used to defend against said technique and/or the security control used by the organization.  

<table>
<tr> 
<th> Tactics </th>  <th> Techniques </th>  <th> Procedures </th> <th> D3FEND </th> <th> Security Control </th>
</tr> 
<tr> <td></td> <td></td> <td></td> <td></td> <td></td>  </tr>
<tr> <td></td> <td></td> <td></td> <td></td> <td></td>  </tr>
<tr> <td></td> <td></td> <td></td> <td></td> <td></td>  </tr>
</table>

### Detection Opportunities
This section includes opportunities to detect using vendor-specific detection rules, threat hunting queries, Sigma rules, or YARA rules that correspond with the threat. Reference can be a link to an internal detection rule/query or an external hyperlink. 

<table>
<tr> 
<th> Rule/Query Name </th>  <th> Type </th>  <th> Description </th> <th> Reference </th>
</tr> 
<tr> <td></td> <td></td> <td></td> <td></td> <td></td>  </tr>
<tr> <td></td> <td></td> <td></td> <td></td> <td></td>  </tr>
<tr> <td></td> <td></td> <td></td> <td></td> <td></td>  </tr>
</table>



## Appendices
### Probability Matrix
You should use estimative language to describe your confidence in intelligence assessments or related judgments. The following table describes the certainty the language you use in the report conveys to the reader to provide additional context. 

<table>
<tr> 
<th> Almost Impossible </th>  <th> Highly Unlikely </th>  <th> Unlikely </th> <th> Possible </th> <th> Likely </th> <th> Highly Likely </th> <th> Almost Certain </th>
</tr> 
<tr> <td> 0 - 5% </td> <td>  5 - 25% </td> <td>  25 - 45% </td> <td>  45 - 55% </td> <td>  55 - 75% </td> <td>  75 - 95% </td> <td> 95 - 100% </td> </tr>
</table>

## Priority Matrix
You should assign each report a priority based on its impact on your organization. The following table describes four general priority levels you can assign to a report. 

<table> 
<tr>  <td> Low </td> <td> The threat requires regular monitoring and should be addressed when possible.    </td> </tr> 
<tr> <td> Moderate </td> <td> The threat needs to be monitored closely and addressed.   </td> </tr> 
<tr> <td> High </td> <td> The threat needs to be addressed quickly and monitored.   </td> </tr> 
<tr> <td> Critical </td> <td> Immediate action is required.   </td> </tr> 
</table>

## Source and Information Reliability
Each report should include an evaluation of source reliability. An industry standard is the Admiralty Scale, developed by NATO. This scale scores source reliability on a scale of A-F and information credibility on a scale of 1-6. Attaching an appendix that describes this to the reader provides clarity.  

## Source
<table> 
<tr>  <td> A (Completely reliable)  </td> <td> The source has a history of consistently providing accurate information.    </td> </tr> 
<tr> <td> B (Usually reliable)  </td> <td> Most of the time, the source provides accurate information.    </td> </tr> 
<tr> <td> C (Fairly reliable)  </td> <td> The source has provided accurate information on occasion.    </td> </tr> 
<tr> <td> D (Not usually reliable)  </td> <td> The source has provided accurate information infrequently.    </td> </tr>
<tr> <td> E (Unreliable)  </td> <td> The source has rarely or never provided accurate information.    </td> </tr> 
<tr> <td> F (Reliability cannot be judged)  </td> <td> The source’s reliability is unknown or untested.    </td> </tr> 
</table>

## Credibility
<table> 
<tr>  <td> 1 (Confirmed)   </td> <td> Other independent sources have confirmed the information.     </td> </tr> 
<tr> <td> 2 (Probably true)   </td> <td> The information is likely true but has not been confirmed.    </td> </tr> 
<tr> <td> 3 (Possibly true)  </td> <td> The information might be true, but it is unconfirmed.     </td> </tr> 
<tr> <td> 4 (Doubtful)   </td> <td> The information is unlikely to be true.    </td> </tr>
<tr> <td> 5 (Improbable)   </td> <td> The information is very unlikely to be true.     </td> </tr> 
<tr> <td> 6 (Cannot be judged)  </td> <td> The credibility of the information cannot be assessed.     </td> </tr> 
</table>

## Sensitivity Matrix
Each report should attach a sensitivity level as defined by your organization’s data protection policy. This ensures data is handled appropriately and only shared with appropriate personnel. Attaching an appendix that describes this to the reader provides clarity.  

<table>
<tr> 
<th> TLP:CLEAR  </th>  <th> TLP:GREEN  </th>  <th> TLP:AMBER  </th> <th> TLP:AMBER+STRICT </th> <th> 	TLP:RED </th> 
</tr> 
  
<tr> 
<td> There are no sharing restrictions. The information can be publicly shared.  </td> 
<td> Information can be shared within a community or sector to raise awareness of a threat.  </td> 
<td> Sensitive information that can be shared on a need-to-know basis within an organization or community  </td> 
<td>  The information is restricted to the organization and should not be shared with its clients or trusted partners.  </td> 
<td>  Highly sensitive information that should only be shared with a limited number of authorized people  </td> 
</tr>
</table>

## Feedback Contacts
Provide a point of contact where the intelligence consumer can direct their feedback once the intelligence report has been published. This will help the CTI team improve future reports, ensure intelligence requirements are being met, and maintain communication channels.  

<table>
<tr> <th> ROLE  </th>  <th> NAME  </th>  <th> TITLE  </th> <th> PHONE </th> <th> EMAIL </th> </tr>
<tr> <td> Head of CTI </td> <td></td> <td></td> <td></td> <td></td> </tr>
<tr> <td> CTI Manager </td> <td></td> <td></td> <td></td> <td></td> </tr>
<tr> <td> CTI Lead </td> <td></td> <td></td> <td></td> <td></td> </tr>
<tr> <td> CTI Analyst (author) </td> <td></td> <td></td> <td></td> <td></td> </tr>
</table>

## Definitions and Acronyms
A list of key terms and acronyms used throughout the report. This lets the reader understand how the CTI team defines a particular technical term.  

<table>
<tr> <th> Key Terms </th> <th> Definition </th></tr>
<tr><td> Actions on Objections (AoO)  </td> <td> The final stage of a cyber attack is where a threat actor achieves their goals. This may include exfiltrating sensitive data, deploying ransomware, or performing espionage. </td></tr>
<tr><td> Admiralty Scale  </td> <td> A method used to evaluate the reliability of sources and the credibility of information in intelligence gathering. Reliability is scored from A to F, and credibility from 1 to 6. </td></tr>
<tr><td> Command and Control (C2) </td> <td> The communication channel attackers aim to establish between compromised systems and their command infrastructure. </td></tr>
<tr><td> Common Vulnerabilities and Exposures (CVE) </td> <td> A system and standardized naming convention used to identify and catalog publicly known cybersecurity vulnerabilities and exposures.  </td></tr>
<tr><td> Cyber Kill Chain </td> <td> A structured framework for understanding the different stages a cyber attack must complete to be successful. </td></tr>
<tr><td> Cyber Threat Intelligence (CTI) </td> <td> The process of gathering, analyzing, and disseminating information about current or potential threats to an organization’s digital infrastructure </td></tr>
<tr><td> Diamond Model </td> <td> A simple framework for analyzing and understanding cyber threats. Defenders use it to organize and structure their intrusion analysis. </td></tr>
<tr><td> Estimative Language</td> <td> Carefully chosen words that convey the confidence, certainty, or likelihood of an intelligence assessment’s conclusion or judgment. </td></tr>
<tr><td> Indicator of Compromise (IOC)  </td> <td> A piece of data or evidence that indicates a malicious activity has occurred within a network or on a computer system. </td></tr>
<tr><td> Intelligence Requirement (IR) </td> <td> Specific information needs to guide the collection, analysis, and dissemination of cyber threat intelligence within an organization. </td></tr>
<tr><td> Malware </td> <td> A term used to define any malicious software designed to harm, exploit, or otherwise compromise a computer system, network, or device (e.g., ransomware). </td></tr>
<tr><td> MITRE ATT&CK </td> <td> A framework that provides a detailed and organized catalog of common tactics, techniques, and procedures (TTPs) threat actors use. </td></tr>
<tr><td> MITRE D3FEND </td> <td> A framework that provides a detailed catalog of defensive security controls and mitigations against attack techniques. </td></tr>
<tr><td> Sigma Rules </td> <td> A standardized format for writing and sharing detection rules for identifying suspicious or malicious activity within log data. </td></tr>
<tr><td> Tactic, Technique, Procedure (TTP) </td> <td> A way to describe and categorize the behavior of adversaries to help organizations anticipate, detect, and respond to cyber threats. </td></tr>
<tr><td> Traffic Light Protocol (TLP) </td> <td> A classification framework for securely sharing and handling sensitive information in the cyber security community. </td></tr>
<tr><td> YARA Rules </td> <td> A standardized format for identifying and classifying malware, detecting threats, and analyzing files based on patterns and signatures. </td></tr>
</table>

### Conclusion
It is vital that you and your team have a cyber threat intelligence report template that you can use to effectively share intelligence within your organization and with the wider community. This template should empower you to streamline your CTI processes and speed up the dissemination of threat intelligence. 




About this portfolio
Template inspired by Kraven Security at https://kravensecurity.com/cyber-threat-intelligence-report-template/
