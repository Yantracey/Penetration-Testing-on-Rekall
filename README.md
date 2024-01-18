# Penetration-Testing-on-Rekall

**Day 1 - Web App Penetration Testing:**
On the first day of the engagement with Rekall Corporation, the focus was on identifying and exploiting vulnerabilities within the company's web application. The team successfully executed various techniques, including reflected cross-site scripting (XSS), local file inclusion (LFI), SQL injection, and command injection, to unveil multiple flags. These exploits targeted different sections of the web application, such as login pages, comment sections, and file upload functionalities. The penetration testing revealed a total of 15 flags, each associated with specific vulnerabilities within the web application.

**Day 2 - Linux Server Exploitation:**
The second day involved the exploration of Rekall's Linux servers. The team utilized tools like Domain Dossier, Zenmap, Nmap, and Nessus to identify hosts, open ports, and potential vulnerabilities. Successful exploits included gaining unauthorized access through vulnerabilities in Apache Struts, command injection, and exploiting weaknesses in Drupal. The team uncovered a total of 11 flags, each associated with different vulnerabilities on the Linux servers.

**Day 3 - Windows Machine Penetration:**
Transitioning to Rekall's Windows machines on the third day, the team initiated reconnaissance by searching for information on Google and discovered a GitHub repository containing hashed credentials. Using the cracked password, they gained access to the Windows machines. Exploits included anonymous FTP access, exploiting SLMAIL services, and lateral movement between machines using Metasploit. The Windows penetration testing revealed a total of 10 flags, each tied to distinct vulnerabilities and compromises on the Windows servers. The assessment concluded with obtaining NTLM hashes and cracking passwords to escalate privileges on the Windows domain.
