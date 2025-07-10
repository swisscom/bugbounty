## Frequently Asked Questions (FAQ)

### What are the different issue states in Jira?

| State | Description |
| --- | --- |
| `OPEN` | The submission was received and is under initial review. |
| `ACKNOWLEDGED` | The bug bounty team has reviewed the submission and confirmed it is in scope and not a duplicate. This means the issue is now being handled. |
| `IN PROGRESS` | The report has been forwarded to the responsible team/supplier. Investigation and remediation are ongoing. |
| `VERIFICATION` | A fix has been implemented. We ask the reporter to test and confirm whether the issue is fully resolved. |
| `RESOLVED` | The vulnerability has been fixed. The reporter and/or the bug bounty team confirmed the remediation. |
| `IMPACT ASSESSMENT` | We are waiting for additional information before assigning a bounty (e.g. impact details). |
| `REQ. BANK DETAILS` | We are ready to issue a bounty but still need the reporter’s bank account information. |
| `SANCTIONS CHECK` | We are reviewing the reporter's identity and bank information against international sanctions and compliance lists. This is a required step before payment can proceed. |
| `PAYOUT INITIATED` | The bounty amount has been set and the payment process has been initiated. |
| `PAYOUT ISSUE` | There is an issue or a delay in processing the payment (e.g. failed sanctions check, rejected bank details, bounced payment). |
| `PAYOUT DISPUTE` | The reporter disagrees with the awarded bounty (e.g. amount too low). |
| `CLOSED` | If a bounty was awarded, the payout is initiated and will be processed by the bank within 2–3 days. The payment may take up to 21 days to arrive. Issues can be reopened if needed.  |
| `CNR` | The issue won't be fixed but has been paid out. Payment will be processed by the bank within 2–3 days and may take up to 21 days to arrive. Issues can be reopened if needed. |


### What's in scope, what's out of scope?
There are two lists which define the scope of the Swisscom bug bounty programme. You can think of them as a combination of an allow-list ([in-scope.txt](https://github.com/swisscom/bugbounty/blob/main/scope/inscope.txt)) and a block-list ([out-of-scope.txt](https://github.com/swisscom/bugbounty/blob/main/scope/outofscope.txt)).

 * The notation `*.domain.tld` means: _a domain and all of its subdomains_.
 * The entries in [out-of-scope.txt](https://github.com/swisscom/bugbounty/blob/main/scope/outofscope.txt) always take precedence over [in-scope.txt](https://github.com/swisscom/bugbounty/blob/main/scope/inscope.txt).

As an example, the more specific domains `*.cust.swisscom.ch` from [out-of-scope.txt](https://github.com/swisscom/bugbounty/blob/main/scope/outofscope.txt) are excluded from the scope, even if [in-scope.txt](https://github.com/swisscom/bugbounty/blob/main/scope/inscope.txt) contains all `*.swisscom.ch` subdomains in general.


### How far should I go to prove the possible exploitation of a vulnerability?
According to our [reporting guidelines](https://github.com/swisscom/bugbounty#55-reporting-guidelines), submissions are required to include a comprehensible description of the vulnerability along with step-by-step instructions to reproduce its exploitation. The fine balance lies within providing a working proof-of-concept, which clearly demonstrates the potential security impact of the vulnerability without actually inflicting any damage.

For example, say you found a SQL injection vulnerability in an application. Exploiting the vulnerability typically allows to retrieve the entire contents of the database. However, this isn't necessary to demonstrate the existence of the vulnerability and this would actually constitute a data breach. Rather, you can either provide us with metadata (e.g. schema/table names) or a behavioral analysis of the application (e.g. time measurements of responses for time-based SQL injections).


### How can I format my report?
You can apply text formatting when submitting your report in the bug bounty portal. For details about the markup, please refer to the [Jira Text Formatting Notation](https://jira.atlassian.com/secure/WikiRendererHelpAction.jspa?section=all). Note that other markup languages such as Markdown or HTML are not supported.


### May I run automated vulnerability scans on the scope?
The use of automated tools to perform active vulnerability scanning often causes collateral damage. According to the [programme rules](https://github.com/swisscom/bugbounty#542-impact-on-operations), _you must avoid tests that could impair, interrupt or otherwise damage Swisscom services_. Therefore running such tools on the scope without taking appropriate precautions is highly discouraged and could lead to exclusion of the programme.
