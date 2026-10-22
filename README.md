<div align="center">

# Assem Merzoug

**Web and API pentester.** I test the whole application — recon, authentication,
injection, access control, business logic, and the server underneath it — then
write it up the way a client reads it.

<sub>MSc Automation &amp; Systems Engineering · BSc Electrical Engineering → offensive security</sub>

[Portfolio](https://assemmerzoug.github.io/Portfolio/) ·
[Writeups](https://github.com/ASSEMMERZOUG/ctf-writeups) ·
[HackerOne](https://hackerone.com/4ss3m) ·
[LinkedIn](https://linkedin.com/in/assemmerzoug)

</div>

---

I start from a login page and a scope, map what is actually reachable, and look
for the place where the code trusts the client. Each finding gets a request that
proves it and an honest severity — not a paragraph of "could potentially".
Then the report: reproduction steps, impact, and the fix.

Most of what I learn is public here: the machines I have taken apart, and the
tool I write the reports with.

<br>

<div align="center">

![BSCP](https://img.shields.io/badge/BSCP-in%20progress-d97757?style=flat-square&logo=burpsuite&logoColor=white)
![CWES](https://img.shields.io/badge/CWES-in%20progress-9f7aea?style=flat-square&logo=hackthebox&logoColor=white)
![OSCP](https://img.shields.io/badge/OSCP-long%20term-6b7280?style=flat-square&logo=offensive-security&logoColor=white)

</div>

<br>

## Selected work

| | |
|---|---|
| **[pdfsmith](https://github.com/ASSEMMERZOUG/pdfsmith)** | A PDF report engine with no dependencies — no LaTeX, no browser, no reportlab. JSON or Python in, a client-ready report out: cover, contents, findings with severity, evidence, remediation. I write my own reports with it. |
| **[ctf-writeups](https://github.com/ASSEMMERZOUG/ctf-writeups)** | Hack The Box machines written up as full pentest reports: recon, the exact request or command that proved the finding, privilege escalation, and how to fix it. Flags redacted. |
| **[web-pentest-field-manual](https://github.com/ASSEMMERZOUG/web-pentest-field-manual)** | Methodology on one page per topic — attack surface, technique, tool, worked example. The notes I keep while hunting. |
| **[web-pentester-roadmap](https://github.com/ASSEMMERZOUG/web-pentester-roadmap)** | A reference library for the path from first box to paid work: tools, protocols, attack vectors, Active Directory basics. |

## Recent reports

- **[Principal](https://github.com/ASSEMMERZOUG/ctf-writeups/tree/master/hackthebox/principal)** — an unsigned JWT accepted inside a valid JWE, and an SSH certificate authority that signed a certificate for `root`.
- **[Fireflow](https://github.com/ASSEMMERZOUG/ctf-writeups/tree/master/hackthebox/fireflow)** — Langflow CVE-2026-33017 to root on the Kubernetes node underneath.
- **[Reactor](https://github.com/ASSEMMERZOUG/ctf-writeups/tree/master/hackthebox/reactor)** — one crafted request into a Node.js application, then everything it kept in its own database.
- **[Support](https://github.com/ASSEMMERZOUG/ctf-writeups/tree/master/hackthebox/support)** — anonymous SMB, a password in an LDAP attribute, Resource-Based Constrained Delegation to Domain Admin.

## Toolbox

`Burp Suite` · `nmap` · `ffuf` · `sqlmap` · `Wireshark` · `Python` ·
`JavaScript` · `Bash` · `Linux` · `Active Directory`

<br>

<div align="center">
<sub>Bug reports and writeups: <a href="https://hackerone.com/4ss3m">HackerOne</a> · CTFs and lab work: <a href="https://github.com/ASSEMMERZOUG/ctf-writeups">ctf-writeups</a></sub>
</div>
