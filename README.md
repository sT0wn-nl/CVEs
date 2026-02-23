# CVE Disclosures

A collection of vulnerabilities I have responsibly disclosed over the years.

---

## Clever Display BlueOne

- [CVE-2025-36755](https://csirt.divd.nl/cves/CVE-2025-36755/) — BIOS access through physical USB keyboard

## IBM Content Navigator

- [CVE-2024-56341](https://www.ibm.com/support/pages/node/7229839) — Cross-site scripting (XSS)

## Uniguest Tripleplay (2024)

Tripleplay's TripleSign Digital Signage is a fully integrated platform that allows users to dynamically control, update, and deliver digital and video communications to a variety of end devices. During a penetration test, I discovered multiple zero-day vulnerabilities affecting the latest firmware:

- [CVE-2024-50707](https://uniguest.com/wp-content/uploads/2025/03/CVE-2024-50707-Vulnerability-Summary-1.pdf) — Remote code execution
- [CVE-2024-50706](https://uniguest.com/wp-content/uploads/2025/03/CVE-2024-50706-Vulnerability-Summary-1.pdf) — SQL injection
- [CVE-2024-50705](https://uniguest.com/wp-content/uploads/2025/02/CVE-2024-50705-Vulnerability-Summary.pdf) — Reflected cross-site scripting (XSS)
- [CVE-2024-50704](https://uniguest.com/wp-content/uploads/2025/03/CVE-2024-50707-Vulnerability-Summary-1.pdf) — Remote code execution

## Comfortkey

- [CVE-2024-27120](https://csirt.divd.nl/cves/CVE-2024-27120/) — Path traversal

## Wago PLC

- [CVE-2023-4089](https://certvde.com/de/advisories/VDE-2023-046/) — Local file inclusion (LFI)

## FortiClient for Windows

- [CVE-2023-37939](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2023-37939/README.md) — Information disclosure

## Uniguest Tripleplay (2023)

Tripleplay's TripleSign Digital Signage is a fully integrated platform that allows users to dynamically control, update, and deliver digital and video communications to a variety of end devices. During a penetration test, I discovered multiple zero-day vulnerabilities affecting the latest firmware:

- [CVE-2023-25759](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2023-25759/README.md) — OS command injection
- [CVE-2023-25760](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2023-25760/README.md) — Privilege escalation
- [CVE-2023-26599](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2023-26599/README.md) — Stored cross-site scripting (XSS)

## Nagios XI

[Nagios XI](https://www.nagios.com/products/nagios-xi/) is an enterprise monitoring solution. During a penetration test, I discovered four zero-day vulnerabilities:

- [CVE-2022-29270](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2022-29270/README.md) — Missing password confirmation during email change, leading to account takeover
- [CVE-2022-29272](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2022-29272/README.md) — Open redirect in login form
- [CVE-2022-29269](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2022-29269/README.md) — HTML injection in scheduled report emails
- [CVE-2022-29271](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2022-29271/README.md) — Permissions issue allowing read-only users to schedule downtimes via `downtime.php`

## Glory Systems RBW-100

The Glory RBW-100 banknote recycling system automates cash handling and removes the need for manual note processing. I discovered two vulnerabilities in the Font Circle Controller management interface that, when chained, lead to a reverse root shell:

- [CVE-2019-10479](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2019-10479/README.md) — Default hardcoded credentials
- [CVE-2019-10478](https://github.com/sT0wn-nl/CVEs/tree/master/CVE-2019-10478/README.md) — Arbitrary file upload

See a [proof of concept](https://youtu.be/MSKDfLpPOLw) combining both vulnerabilities in action.
