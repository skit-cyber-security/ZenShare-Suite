# ZenShare-Suite
The ZenShare Suite application is vulnerable by a Reflected Cross-Site Scripting (XSS) vulnerability, affecting web application login and recovery password functionalities.
An attacker can exploit this issue by crafting a malicious URL and tricking a victim into visiting it, leading to the execution of arbitrary JavaScript code in the victim’s browser in the context of the affected application.

# CVE ID
**CVE-XXXX-XXXXX - CVE-XXXX-XXXXX**

# Details
* **Vulnerability Type**: Reflected Cross-Site Scripting (XSS)
* **Affected Application**: ZenShare Suite
* **Affected Versions**: < 17.0
* **Impact**: Javascript Code Execution leading to session hijacking or credential theft in victim’s browser context.

# PoC / Attack Example

Within the application there are 2 parameters vulnerable to Cross-Site Scripting (XSS)
* [CVE-XXXX-XXXXX]
* [CVE-XXXX-XXXXX]


# References


# Credits
**Manuel Scala**, **Federico Mirra**, **Francesco Berti** <br></br>
<a href="https://sk-it.com/"><img src="img/skit_logo.png" width="300">
