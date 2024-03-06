# MITRE

## Task 1:

*No answer needed*.

## Task 2:

*No answer needed*.

## Task 3:

> Besides Blue teamers, who else will use the ATT&CK Matrix? (Red Teamers, Purpe Teamers, SOC Managers?)

**Red Teamers**

> What is the ID for this technique?

Go to the phishing page, the ID is -> **T1566**.

> Based on this technique, what mitigation covers identifying social engineering techniques?

**User Training**.

> What are the data sources for Detection? (format: source1,source2,source3 with no spaces after commas)

Scroll down the phishing page info and find : **Application Log,File,network traffic**.

> What groups have used spear-phishing in their campaigns? (format: group1,group2)

Scroll up the phishing page info and find : **Axiom,Gold SOUTHFIELD**.

> Based on the information for the first group, what are their associated groups?

Hover over the little 8 on the Axiom line and read the URL you will find: **Group 72**

> What software is associated with this group that lists phishing as a technique?

After clicking on Axiom just Ctrl+F "Phishing" you gonna find : **Hikit**.

> What is the description for this software?

Just click on Hikit and the description pop on your screen, just copy paste it : **Hikit is malware that has been used by Axiom for late-stage persistence and exfiltration after the initial compromise.**

> This group overlaps (slightly) with which other group?

In the information paragraph concerning the Axiom company, we find the name of **winnti group**.

> How many techniques are attributed to this group?

Just count the techniques used table : **15**.

## Task 4:

> What tactic has an ID of TA0003?

**Persistence**.

> What is the name of the library that is a collection of Zeek (BRO) scripts?

**BZAR**.

> What is the name of the technique for running executables with the same hash and different names?

**Masquerading**.

> Examine CAR-2013-05-004, besides Implementations, what additional information is provided to analysts to ensure coverage for this technique?

**Unit Tests**.

## Task 5:

> Under Prepare, what is ID SAC0002?

**persona creation**.

> What is the name of the resource to aid you with the engagement activity from the previous question?

Go in tool and -> All tool then find : **PERSONA PROFILE WORKSHEET**.

> Which engagement activity baits a specific response from the adversary?

**Lures**.

> What is the definition of Threat Model?

Go in Understand Category and then click on Threat Model and on "Full definitions" and then copy/paste : **A risk assessment that models organizational strengths and weaknesses**.

## Task 6:

> What is the first MITRE ATT&CK technique listed in the ATT&CK Lookup dropdown?

Click on Att&ck Lookup and look to the first attack mentionned : **Data Obfuscation**.

> In D3FEND Inferred Relationships, what does the ATT&CK technique from the previous question produce?

Click on Data obfuscation and look the finality of the technique : **Outbound Internet Network Traffic**.

## Task 7:

> In Phase 1 for the APT3 Emulation Plan, what is listed first?

**C2 Setup**.

> Under Persistence, what binary was replaced with cmd.exe?

**sethc.exe**

> Examining APT29, what  C2 frameworks are listed in Scenario 1 Infrastructure? (format: tool1,tool2)

**pupy,metasploit framework**.

> What C2 framework is listed in Scenario 2 Infrastructure?

**PoshC2**.

> Examine the emulation plan for Sandworm. What webshell is used for Scenario 1? Check MITRE ATT&CK for the Software ID for the webshell. What is the id? (format: webshell,id)

**P.A.S.,S0598**.

## Task 8:

> What is a group that targets your sector who has been in operation since at least 2013?

Just CTRL+F the page with "Aviation" and the first you see is : **APT33** which is the answer.

> As your organization is migrating to the cloud, is there anything attributed to this APT group that you should focus on? If so, what is it?

Do the same thing, CTRL+F "cloud" and the first thing you see is the answer : **Cloud Accounts**.

> What tool is associated with the technique from the previous question?

**Ruler**.

> Referring to the technique from question 2, what mitigation method suggests using SMS messages as an alternative for its implementation?

Click on Cloud Accounts then CTRL+F "sms" and copy/paste the first word : **Multi-factor Authentication**.

> What platforms does the technique from question #2 affect?

Do the same thing but with "Platform" : **Azure AD, Google Workspace, IaaS, Office 365, SaaS**.

## Task 9:

*No answer needed*.
