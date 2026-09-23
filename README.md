## Rizky Darmawan

Cyber Security student with hands-on experience in network and mobile penetration testing, as well as reverse engineering. Interested in exploring system security, identifying potential vulnerabilities, and understanding how security can be considered when developing digital solutions. Always eager to learn, take on new challenges, and continuously improve technical skills and cybersecurity knowledge. Currently focused on developing skills in secure programming and reverse engineering.

## Technical Skills

Penetration Testing : Reconnaissance, Scanning, Enumeration, Vulnerability Assessment, Exploitation, Privilege Escalation, Post-Exploitation, Reporting.

Mobile Security : Mobile Penetration Testing, APK Analysis, Static Analysis, Dynamic Analysis.

Reverse Engineering : APK Reverse Engineering.

Programming Language : C/C++, Python, SQL (MariaDB/MySQL).

## Featured Project

Mobile Application Penetration Testing

Performed static analysis on an Android APK using JADX GUI to identify security vulnerabilities in the application’s manifest, DEX bytecode, and resources.

Performed APK reverse engineering using MT Manager to analyze client-side application logic.

Validate vulnerabilities related to in-game data and advertisement mechanisms.

• Hill Climb Racing version 1.67.0

Analyzed the APK using JADX GUI.

Identified potential security vulnerabilities.

Analyzed the application’s DEX bytecode using MT Manager.

Validated the identified weaknesses through controlled modifications.

Successfully modified Coins, Gems, and Paints, and bypassed in-game advertisements.

Full Write-Up: https://docs.google.com/document/d/1yn1Targ-Dk6yQF37FIEjGdPVRtqAJp_OmJ8ShKHhyAw/edit?usp=sharing


HackTheBox (HTB)

• Expressway

Performed network scanning and enumeration using Nmap and ike-scan to identify exposed services and potential entry points.

Analyzed IKE-PSK authentication data and recovered credentials using Hashcat to gain initial access through SSH.

Identified and exploited a vulnerable sudo version (CVE-2025-32463) to escalate privileges and gain Root access.

Flow:

Scanned the target using Nmap to identify open ports and running services.

Discovered and enumerated the IKE/ISAKMP service using ike-scan.

Identified a valid username and captured IKE-PSK authentication data.

Recovered the password using Hashcat and gained initial access through SSH.

Identified a vulnerable sudo version during privilege escalation analysis.

Exploited CVE-2025-32463 to escalate privileges and gain Root access.

Full Write-Up : https://docs.google.com/document/d/1jXPrSI-boRDCgJsS07p5tF0F5tLj7wXfynPjGZlh2Ms/edit?tab=t.0

• Guardian

Performed web application enumeration to identify exposed account information, default credentials, and insecure application functionality.

Analyzed application components and identified vulnerabilities that could be exploited to gain higher-level access.

Chained multiple vulnerabilities to escalate access from a Student account to Lecturer and Admin access.

Flow:

Scanned the target using Nmap to identify open ports and running services.

Enumerated the web application and discovered exposed student account information.

Gained access to the student portal using exposed default credentials.

Enumerated chat parameters and discovered additional credentials.

Identified a vulnerable PhpSpreadsheet version through application files.

Exploited the file upload vulnerability to obtain a lecturer session.

Analyzed lecturer functionality and chained the discovered weaknesses to gain Admin access.

Full Write-Up : https://docs.google.com/document/d/1jXPrSI-boRDCgJsS07p5tF0F5tLj7wXfynPjGZlh2Ms/edit?tab=t.0
