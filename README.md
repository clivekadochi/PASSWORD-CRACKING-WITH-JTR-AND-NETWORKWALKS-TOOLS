<div align="center">

# 🔐 PASSWORD-CRACKING-WITH-JTR-AND-NETWORKWALKS-TOOLS
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ver-KaliLinux%20v7.2-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Ver-Virtualbox%20v7.1.4-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2026.2-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Linux-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Zenmap Scanning%2F-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali%20Linux-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks Intern-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Clive%20Kadochi%20IT Tech-C00000?style=flat-square" />
</p>

---

<p align="center"> ## 🔐PENETRATION-TESTING-REPORT-
  

## W3-PM-FINAL REPORT PASSWORD CRACKING WITH JTR & NETWORKWALKS TOOLS | CYBERSECURITY |  NETWORKWALKS

Pentester Name
(Cybersecurity Professional)	Clive Kadochi
Program/Batch	B083-Networkwalks
Date	 20th September 2026
Modules completed	W3-PM1: Password Cracking with JTR 
W3-PM2: Password Cracking with NW Tools
Client/Target	1. Networkwalks (secured written permission already)
2. Locked PDF 1, 2 and 3.
Permission secured from client?	Yes
Phases covered	Phase 1: Password Cracking with JTR 
Phase 2: Password Cracking with NW Tools
Phase 3-5: In Progress




1. Liability Disclaimer
I have performed these activities only on the systems & devices where I had secured written permission or the devices/systems that I own myself. All these materials are for education and research purpose only. Do not use anything from here to break the law. The instructor, the authors and Networkwalks are not responsible for what you do with this knowledge. Every action you take is your own responsibility. Misuse can lead to criminal charges, heavy fines, loss of your job and a permanent record. In most countries unauthorised access is a crime even when nothing is damaged.
 
2. Introduction
Password cracking is the process of recovering a password from stored data or a protected file. Security professionals use it to test how strong a password is and to show why weak passwords are risky. If a password is short or common, it can be found quickly, which proves the need for strong passwords. Many files like PDF, ZIP, and Office documents can be locked with a password. When a file is locked, its password is stored in the form of a hash. A hash is a scrambled value that represents the password. To recover the password, we first take out this hash from the file, and then run it through a cracking tool that tries different words until it finds a match. 

John the Ripper (JTR) is a popular password cracking tool used by security professionals to test how strong passwords are. It started as a tool for Unix systems but now works on Windows, Linux, and Mac. It can check many types of password hashes and also unlock password protected files like PDF, ZIP, and Office documents. Johnny is the graphical version of John the Ripper. It gives a simple point and click screen, so beginners can use JTR without typing long commands. Both tools are widely used in security testing and learning labs to understand password safety. In this lab task you will use JTR John and JTR Johnny to recover the password of a protected PDF file. This exercise helps you learn how password cracking works and why it is important to use strong passwords for protection.
In this lab you will use two free online tools made by Networkwalks. First you will use the Hash Calculator to take the hash out of a locked PDF file. Then you will use the Password Cracker to find the real password from that hash. Both tools run in your web browser, so you do not need to install anything. This lab helps you understand how password cracking works step by step and why strong passwords are important for protection.


3. Tools Used
The table below lists each tool used in this report and its purpose.
Tool	Purpose
 (JTR) password cracking tool	John the Ripper (JTR) is a popular password cracking tool used by security professionals
Networkwalks Hash Calculator tools	Hash Calculator  take the hash out of a locked PDF file
Networkwalks Password Cracker tools	Then the Password Cracker finds the real password from that hash
4.1 (JTR) password cracking tool

Crack the password of attached PDF file (My Locked PDF1.pdf) using JTR JOHN and JTR JOHNNY tools on your Windows PC. 
First, I opened the hash website & upload your pdf file to find its hash: 
Browse the PDF file & click on Upload:
Then Select & copy the hash value:  *Note: If your hash contains extra characters like b' in the start then make sure to remove those when saving in txt file (hash value should be in the format shown in above screenshot i.e. starting with $pdf$....)
Open notepad and Save the file with name hash1.txt:
Open Johnny again: Click on ‘Open password file’:
Browse to the hash1.txt file that you have just saved & click on Open:
Click on ‘Start new attack’: then PDF file password will be cracked (it might take some time depending on your computer speed & password complexity):
Now you i used the password to open PDF file. Open the encrypted PDF:
I Entered password1 (which i have just cracked):
Finally, my PDF file was opened. 


4.2 Networkwalks Hash Calculator & Password Cracker tools
For the second activity, I used Networkwalks Hash Calculator & Password Cracker tools  to Crack the password of the attached PDF file (My Locked PDF1.pdf) using the Networkwalks Hash Calculator and Password Cracker tools on my Windows laptop

I first opened the Networkwalks Hash Calculator in my web browser: 
Then Upload the locked PDF file to the Hash Calculator. The tool will read the file and give you the hash value that starts with $pdf$...
Copy the full hash value. Note: Copy the complete hash starting from $pdf$. Do not miss any part of it. 
Open the Networkwalks Password Cracker in your web browser:
Then Paste the hash value into the Password Cracker and start the attack. The tool will try different passwords until it finds a match.
Wait for the tool to finish. The cracked password will be shown on the screen. Note: The time taken depends on how simple or complex the password is. 
After completing the scan, I opened the locked PDF file and enter the cracked password. Enter password1 (which i have just cracked): 
My PDF file was opened. 
.

 
5. Risk Analysis / Impact
Based on the information collected during the password cracking activities, I identified the following potential risks.
#	Risk / Finding	Evidence / Observation	Potential Impact	Risk Level
1	Offline risk by exposing weak, reused credentials	Offline vulnerability Exploitation	The tool processes exported  password hash files (such as / etc./ shadow) locally on an attackers hardware 	● Medium
2	Attack vectors supported 	Dictionary/wordlist attacks	Compares hashes against millions of common passwords	● Low
3	Algorithmic weakness	Unsalted or Legacy hashing algorithms 	MD5 or Short DES  are cracked almost instantly	● Low
4	Impact of successful Cracking	Unauthorized privilege Escalation	Breaking a standard user hash can lead to horizontal movement 	● Low
5	Mitigation and Defense strategies 	Upgrade Hash standards	Migrate away from weak or unsalted legacy formats 	● Medium
6	Enforce Multi-Factor Authentication	MFA Authentication was not performed	Render static password theft insufficient by requiring a second authentication factor for all critical network entry points.	● Medium

Risk level key:  ● Critical ● Medium ● Low
The risks above are observations from the password cracking exercises, not confirmed vulnerabilities.
The practical exercises primarily involved password cracking and information protection. No exploitation or vulnerability validation was performed as part of these two modules.
Therefore, the presence of  information such as a John the Ripper (JTR), Networkwalks Hash Calculator tools does not by itself mean that the secured files is vulnerable. Further authorized password cracker tool would be required to confirm any actual vulnerability.

6. Recommendations
Based on the observations from these activities, I recommend the following security improvements:
1.	Review publicly exposed technology information
Organizations should set strong passwords in order to protect publicly visible information.
2.	Keep software updated
CMS platforms, plugins and other web technologies should be regularly updated and reviewed against current security advisories.
3.	Review Security records regularly
Security records should be checked periodically to ensure that only required information and services are publicly exposed.
4.	Properly configure and monitor the John the Ripper (JTR) 
Crack the password of attached PDF file (My Locked PDF1.pdf) using JTR JOHN and JTR JOHNNY tools on your Windows PC. .
5.	Maintain network documentation
Network topology and device information should be documented and updated regularly.
6.	Perform password cracking with authorization
Password Cracking should only be performed against systems and networks where appropriate authorization has been provided.

7. Conclusion
During Week 3 of my Cybersecurity & Ethical Hacking internship, I completed practical activities covering John the Ripper (JTR), Networkwalks Hash Calculator tools and Networkwalks Password Cracker tools.
In the password cracking activity, I used (JTR), Networkwalks Hash Calculator and Password Cracker tools to collect information about the target Locked PDF files. I learned how John the Ripper is used to crack PDF files, Networkwalks Hash Calculator and Password Cracker tools technologies can identify password.
The exercises showed me that information gathering is an important part of cybersecurity. Even before attempting to exploit a system, a security professional can learn a significant amount about an environment by carefully analysing publicly available information and network responses.
I also learned that technical findings should be documented clearly. A good cybersecurity report should explain what was performed, what was discovered, what the observation means, what risk it may create, and what can be done to reduce that risk.
Finally, I learned that password cracking must always be performed within an authorized scope. These activities were completed as part of the assigned educational cybersecurity lab.

8. Evidences Collected
 
 
 
 
 

 
 

-End-


👤 Author
Clive Kadochi
Cybersecurity Professional B083
LinkedIn: www.linkedin.com/in/clive-kadochi-1st-924492261 
________________________________________
📌 Project Information
Program Name: Cybersecurity program at Networkwalks | Week: 03 | Repository GitHub:  https://github.com/clivekadochi/PENETRATION-TESTING-REPORT-.git


