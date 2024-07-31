**Application Security**

1.	SAST(Static Application Security Testing) – Vulnerability Management
2.	SCA/SBOM (Software composition Analysis/Software bill of materials) – VM
3.	DAST(Dynamic Application Security Testing) – VM
4.	VAPT(Vulnerability Assessment & pentesting) – VM

Thhin applications, APIs, webservices, thick client apps(That install in machine- .exe, .dpkg, .sh)
Data in transit
1.	Sonarcode, Acunetx – Tools used in SAST
2.	SCA/SBOM : Downloading all versions /components in application and checking the vulnerability.
3.	DASt- Tool: Rapid7 indast. DAST is never done manually(Few subprocess can be done manually) 

**Burpsuit- Manual tool**

Insight Appsec Platform Walkthrough-
1.	_Dashboard_
2.	_Apps_: We can start scanning for an app
3.	_Scans_- Shows results of all scans
4.	_Vulnerabilities_
5.	_Targets_- First add application url in targets )Eg: www.fdr.in.com) and then we can go to apps to scan the app.
6.	_Tags_- We can add tags to the application. We can also create tags and then add them.
7.	_Schedules_- While setting configuration of the application, if we have set it up then only the details will be visible. We can also enable/disable those scan schedules.
8.	_Report_- Once scan is completed, we can generate report.
9.	_Settings_- Manage On Premises Engines(Set Scan engines)
a.	Create Attack Template(Scan OS Top 10 Vulnerabilities, a template to check all vulnerabilities)
b.	Archived targets
c.	Integrations
d.	Notifcations 

