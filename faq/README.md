## Frequently Asked Questions (FAQ)

### What are the different issue states in Jira?

| State | Description |
| --- | --- |
| `OPEN` | New submission |
| `ACKNOWLEDGED` | Submission acknowledged by the bug bounty team |
| `IN PROGRESS` | Submission was handed over to the responsible team |
| `PENDING INTERNAL` | Issue requires in-depth analysis, e.g. when further parties (vendors, suppliers, etc) are involved. |
| `PENDING REPORTER` | Additional information about the vulnerability required from the reporter |
| `VERIFICATION` | Request confirmation of the fix by the reporter |
| `RESOLVED` | Vulnerability was remediated |
| `GATHER METADATA` | Bug bounty team collects all information required to assess the impact of the reported vulnerability |
| `REQ. BANK DETAILS` | Bank account information required from the reporter |
| `PAYOUT INITIATED` | Bounty was assigned and payment process initiated |
| `CLOSED` | Payout succeeded and issue is closed |

### What's in scope, what's out of scope?
There are two lists which define the scope of the Swisscom bug bounty programme. You can think of them as a combination of an allow-list ([in-scope.txt](https://github.com/swisscom/bugbounty/blob/main/scope/inscope.txt)) and a block-list ([out-of-scope.txt](https://github.com/swisscom/bugbounty/blob/main/scope/outofscope.txt)).

 * The notation `*.domain.tld` means: _a domain and all of its subdomains_.
 * The entries in [out-of-scope.txt](https://github.com/swisscom/bugbounty/blob/main/scope/outofscope.txt) always take precedence over [in-scope.txt](https://github.com/swisscom/bugbounty/blob/main/scope/inscope.txt)).

As an example, the more specific domains `*.cust.swisscom.ch` from [out-of-scope.txt](https://github.com/swisscom/bugbounty/blob/main/scope/outofscope.txt) are excluded from the scope, even if [in-scope.txt](https://github.com/swisscom/bugbounty/blob/main/scope/inscope.txt) contains all `*.swisscom.ch` subdomains in general.