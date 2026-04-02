# ZenShare Suite - Vulnerability Disclosure

This repository contains details regarding multiple Reflected Cross-Site Scripting (XSS) vulnerabilities discovered in the ZenShare Suite application.

## Vulnerability Overview

The ZenShare Suite application is vulnerable to Reflected Cross-Site Scripting (XSS) affecting the login and password recovery functionalities. An attacker can exploit these issues by crafting a malicious URL and tricking a victim into visiting it, leading to the execution of arbitrary JavaScript code in the victim’s browser.

---

## [CVE-2026-30251]

### Description
A reflected cross-site scripting (XSS) vulnerability in the **login_newpwd.php** endpoint of Interzen Consulting S.r.l ZenShare Suite v17.0 allows attackers to execute arbitrary Javascript in the context of the user's browser via a crafted URL injected into the **codice_azienda** parameter.

### Details
* **Vulnerability Type:** Cross Site Scripting (XSS)
* **Affected Component:** `login_newpwd.php`
* **Vulnerable Parameter:** `codice_azienda` (GET)
* **Attack Vector:** Remote
* **Impact:** Javascript Client-Side Code Execution

---

## [CVE-2026-30252]

### Description
Multiple reflected cross-site scripting (XSS) vulnerabilities in the **login.php** endpoint of Interzen Consulting S.r.l ZenShare Suite v17.0 allows attackers to execute arbitrary Javascript in the context of the user's browser via a crafted URL injected into the **codice_azienda** and **red_url** parameters.

### Details
* **Vulnerability Type:** Cross Site Scripting (XSS)
* **Affected Component:** `login.php`
* **Vulnerable Parameters:** `codice_azienda`, `red_url` (GET)
* **Attack Vector:** Remote
* **Impact:** Javascript Client-Side Code Execution

---

## Affected Versions
* **Product:** ZenShare Suite
* **Version:** < 17.0
* **Vendor:** Interzen Consulting S.r.l

## Credits
* **CVE-2026-30251:** Manuel Scala, Federico Mirra, Francesco Berti
* **CVE-2026-30252:** Manuel Scala, Federico Mirra


# Credits
**Manuel Scala**, **Federico Mirra**, **Francesco Berti** <br></br>
<a href="https://sk-it.com/"><img src="img/skit_logo.png" width="300">
