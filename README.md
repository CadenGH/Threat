# Threat Hunting Simulator Using Graylog

<h2>Alright, I took on a project involving setting up a simulated hacking environment with VirtualBox, Windows 10, Ubuntu, Graylog, and executing the Follina exploit (CVE 2022-30190) to understand its impact and analyze the logs generated.</h2>

&nbsp;&nbsp;&nbsp;&nbsp; <h2> Here's a summary of the steps I took:</h2>

&nbsp;&nbsp;&nbsp;&nbsp; <h4>Setting up VMs:</h4> Installed Windows 10 and Ubuntu on VirtualBox, ensuring they are on the same NAT network for connectivity.

&nbsp;&nbsp;&nbsp;&nbsp; <h4>Installing Graylog:</h4> Configured Graylog on Ubuntu and set up Sidecar on Windows to collect logs.

&nbsp;&nbsp;&nbsp;&nbsp;<h4>Preparing Windows:</h4> Installed Microsoft Office, Sysmon for detailed system information.

&nbsp;&nbsp;&nbsp;&nbsp;<h4>Executing Follina Exploit:</h4> Cloned the Follina repository, crafted the malicious "follina.doc," set up a Python server, and executed the exploit to gain reverse shell access to the Windows machine.

&nbsp;&nbsp;&nbsp;&nbsp;<h4>Analyzing Logs in Graylog:</h4> Sifted through logs, set up search queries in Graylog to identify process creations, suspicious activities triggered by the exploit, and monitored for specific processes or behaviors.

<h3>Conclusions:</h3>
Successfully executed the Follina exploit to gain control of the Windows system, showcasing the severity of the vulnerability.
Leveraged Graylog effectively to analyze logs, identifying key indicators of compromise (IOCs) and suspicious activities triggered by the exploit.
Gained practical experience in setting up a hacking environment, executing an exploit, and using a SIEM for threat analysis and detection.
Highlighted the significance of thorough log analysis, understanding system behaviors, and the importance of threat research in cybersecurity defense strategies.

Overall, the project was a comprehensive journey from setting up the environment, executing an exploit, to analyzing logs—providing hands-on experience and insights into the world of cybersecurity, emphasizing the critical role of threat hunting and defense strategies.
