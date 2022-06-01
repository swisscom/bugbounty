# Qualifying Vulnerabilties
Any design, implementation or configuration issue that substantially 
affects confidentiality or integrity is likely to be eligible for a 
reward. Common examples include: 

 * Remote code execution (RCE)
 * Code injections (HTML, JS, SQL, PHP, etc)
 * Cross-site scripting (XSS)
 * Horizontal and vertical privilege escalation
 * Broken authentication and session management

The following issues are not considered relevant under the Programme:

 * The absence of a security feature alone without demonstrated impact 
 * Disclosure of non-sensitive information, even in bulk
 * Denial-of-Service attacks
 * "Self" XSS
 * Missing Cookie flags or missing security-related HTTP headers without a demonstrated security impact
 * Missing or incomplete SPF/DKIM/DMARC
 * Social engineering attacks 
 * *1-day vulnerabilities* are accepted four weeks after disclosure at the 
earliest (see exceptions below). Most non-critical patches are applied 
during standard maintenance windows.

Moreover, in cases where we generally accept the security impact, we 
also exclude certain classes of vulnerabilities.


## Excluded Vulnerabilities

| Date | Vulnerability | Comment |
| --- | --- | --- |
| Jan 2020 | Disclosure of unrestricted API keys | Disclosed API keys used for services like Google, Facebook, etc may lead to financial loss and/or denial of service if a quota is set and exhausted. These will no longer be considered as relevant for our Bug Bounty Programme. |
| Dec 2020 | CWE-613 Insufficient Session Expiration | The attack has a rather high pre-requisite in order to be exploitable namely, initial access to the current session. We agree that the behavior of an affected system should be implemented in a better way and this missing security feature would only bring improvement but consider it below the threshold to qualify for our Bug Bounty Programme. |

## Accepted 1-day Vulnerabilities

| Date | Vulnerability | Comment |
| --- | --- | --- |
| Dec 2021 | CVE-2021-44228 ([Log4Shell](https://www.lunasec.io/docs/blog/log4j-zero-day/)) | No RCE PoC required, detection via DNS logging e.g. using [Canary Tokens](https://canarytokens.org/) is sufficient |