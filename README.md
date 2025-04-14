The following is a list of my collected CVE's

## IBM Content Navigator
* [CVE-2024-56341](https://www.ibm.com/support/pages/node/7229839) Cross-site scripting

## Uniguest Tripleplay
Tripleplay’s TripleSign Digital Signage is a fully integrated digital signage platform that allows users to dynamically control, update and deliver digital and video communications to a variety of end devices. During a pentest i've found multiple 0days that affacted the latest firmware:
* [CVE-2024-50707](https://uniguest.com/wp-content/uploads/2025/03/CVE-2024-50707-Vulnerability-Summary-1.pdf) remote code execution
* [CVE-2024-50706](https://uniguest.com/wp-content/uploads/2025/03/CVE-2024-50706-Vulnerability-Summary-1.pdf) SQL injetion
* [CVE-2024-50705](https://uniguest.com/wp-content/uploads/2025/02/CVE-2024-50705-Vulnerability-Summary.pdf) Reflexted cross-site scripting
* [CVE-2024-50704]([https://uniguest.com/cve-bulletins/](https://uniguest.com/wp-content/uploads/2025/03/CVE-2024-50707-Vulnerability-Summary-1.pdf) remote code execution

## Comfortkey
* [CVE-2024-27120](https://csirt.divd.nl/cves/CVE-2024-27120/) Path traversal

## FortiClient for Windows
* [CVE-2023-37939](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2023-37939]/README.md) Information disclosure

## Uniguest Tripleplay
Tripleplay’s TripleSign Digital Signage is a fully integrated digital signage platform that allows users to dynamically control, update and deliver digital and video communications to a variety of end devices. During a pentest i've found multiple 0days that affacted the latest firmware:
* [CVE-2023-25759](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2023-25759/README.md) OS command injection
* [CVE-2023-25760](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2023-25760/README.md) Privilege escalation
* [CVE-2023-26599](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2023-26599/README.md) Stored XSS

## Nagios XI
Nagios XI is an enterprise monitoring solution, see https://www.nagios.com/products/nagios-xi/ for more information. During an pentest i've found 4 0days:
* [CVE-2022-29270](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2022-29270/README.md) No password conformation during e-mail change leads to account takeover
* [CVE-2022-29272](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2022-29272/README.md) Open redirect in login form
* [CVE-2022-29269](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2022-29269/README.md) HTML injection in schedueld report mails
* [CVE-2022-29271](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2022-29271/README.md) Permissions issue where read-only users could schedule downtimes using downtime.php

## Glory Systems, RBW-100
The Glory RBW-100 banknote recycling system controls cash and removes the need for manual note handling. I've found two vulnerabilities in the Font Circle Controller management interface that can lead to a reverse root-shell:
* [CVE-2019-10479](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2019-10479/README.md) - Default hardcoded credentials
* [CVE-2019-10478](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2019-10478/README.md) - Arbitrary file upload
<img src="https://www.glory-global.com/-/media/GloryGlobal/Images/Product-and-Service/rbw100oem-hero-680x970-desktop.jpg?h=485&la=en-US&w=340&hash=47E7639F6120688E65216CDA6A1C6288BD86DD5F" width="150">

See a POC, combining these two vulnerabilities in action: https://youtu.be/MSKDfLpPOLw
