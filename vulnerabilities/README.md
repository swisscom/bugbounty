# Vulnerabilities

## Qualifying Vulnerabilities
Any design, implementation or configuration issue that substantially 
affects confidentiality or integrity is likely to be eligible for a 
reward. Common examples include: 

 * Remote code execution (RCE)
 * Code injections (HTML, JS, SQL, PHP, etc)
 * Cross-site scripting (XSS)
 * Horizontal and vertical privilege escalation
 * Broken authentication and session management
 * Sensitive data exposure

## Non-Qualifying Vulnerabilities
The following issues are not considered relevant under the Programme:

 * The absence of a security feature alone without demonstrated impact 
 * Disclosure of non-sensitive information, even in bulk
 * Denial-of-Service attacks
 * "Self" XSS
 * Missing Cookie flags or missing security-related HTTP headers without 
a demonstrated security impact 
 * Open redirects
 * Clickjacking
 * Missing or incomplete SPF/DKIM/DMARC
 * Social engineering attacks
 * Reports from automated tools or scans without explanatory documentation
 * Missing Rate limiting without further security impact

Moreover, in cases where we generally accept the security impact, we 
also exclude certain classes of vulnerabilities.

### Excluded Vulnerabilities

| Date | Vulnerability | Comment |
| --- | --- | --- |
| Jan 2020 | Disclosure of unrestricted API keys | Disclosed API keys used for services like Google, Facebook, etc may lead to financial loss and/or denial of service if a quota is set and exhausted. These will no longer be considered as relevant for our Bug Bounty Programme. |
| Jun 2022 | XSS in legacy Browsers | Cross-site scripting (XSS) in legacy browsers such as Microsoft Internet Explorer will no longer be considered for our Bug Bounty Programme |
| Jul 2022 | CVE-2019-12616, CSRF in phpMyAdmin < 4.9.0 | Proof-of-concept requires user interaction, which violates our [policy on social engineering](https://github.com/swisscom/bugbounty#547-social-engineering). After weighing out the risk it was decided that this attack will no longer be considered as relevant for our Bug Bounty Programme. |
| Jul 2022 | CWE-489 Active Debug Code | Unless sensitive data is exposed, applications running with debug mode turned on do not constitute a security issue considered as relevant for our Bug Bounty Programme. |
| May 2023 | Takeover of expired second-level domains listed in [https://github.com/swisscom/bugbounty/blob/main/scope/inscope.txt](inscope.txt). |

## 1-Day Vulnerabilities
Most non-critical patches are applied during standard maintenance 
windows. Therefore, *1-day vulnerabilities* are accepted four weeks 
after disclosure at the earliest (see exceptions below). 

### Accepted 1-day Vulnerabilities
Special cases where information on 1-day vulnerabilities is explicitly 
desired are listed below. For any clarifications regarding this list, 
please contact the Bug Bounty team. 

| Date | Vulnerability | Comment |
| --- | --- | --- |
| Dec 2021 | CVE-2021-44228 ([Log4Shell](https://www.lunasec.io/docs/blog/log4j-zero-day/)) | ~~No RCE PoC required, detection via DNS logging e.g. using [Canary Tokens](https://canarytokens.org/) is sufficient~~ Update Mar 2023: please provide a RCE PoC if possible. |
