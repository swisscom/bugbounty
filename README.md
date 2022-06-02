# Swisscom Vulnerability Disclosure Policy & Bug Bounty Programme 

## 1 Introduction
We, Swisscom Ltd and our affiliated companies (hereinafter "Swisscom") 
aim to design and operate our products and services according to the 
highest security standards to keep our customers safe. To this end, we 
are continually improving our security on multiple levels. We are aware 
that, despite all efforts, absolute security is impossible, and we 
cannot completely rule out the existence of security bugs. The purpose 
of the Swisscom Vulnerability Disclosure Policy and Bug Bounty Programme 
is to support the reporting of potential vulnerabilities in our systems 
by external parties. 

Customers, users, researchers, partners and any other parties who 
interact with Swisscom's products and services are encouraged to report 
identified vulnerabilities to our security team under observance of our 
[Responsible Disclosure Policy](#3-responsible-disclosure-policy).

Moreover, we invite both private individuals and legal entities to 
participate in our [Bug Bounty Programme](#5-bug-bounty-programme) 
(hereinafter the "Programme") in accordance with the [Programme 
Rules](#54-programme-rules). Bounties may be awarded for reporting 
[qualifying](#53-qualifying-vulnerabilities) and 
[in-scope](#52-programme-scope) vulnerabilities. 

Swisscom acknowledges the value of contributions from the security 
researcher community and highly appreciates the efforts made by the 
reporting party. We thank you in advance for your contribution! 


## 2 Contact Information
To take part in our Bug Bounty Programme, please register and submit 
your report directly on [our 
portal](https://issue.swisscom.ch/servicedesk/customer/portal/3). See 
[5.4.1 Registration](#541-registration). 

To report a security vulnerability to Swisscom without participation in 
the Bug Bounty Programme or for any other enquiries, please contact us 
by e-mail. 

<table>
  <tr>
    <td>E-mail</td>
	<td><a href="mailto:bug.bounty@swisscom.com">bug.bounty@swisscom.com</a></td>
  </tr>
  <tr>
    <td>PGP key ID</td>
    <td>350B4B73FA225C67</td>
  </tr>
  <tr>
    <td>PGP fingerprint</td>
    <td>28E7 E4D0 7ED7 9083 A93C 03B2 350B 4B73 FA22 5C67</td>
  </tr>
  <tr>
    <td>PGP public key</td>
	<td>
	 <a href="https://www.swisscom.ch/content/dam/swisscom/de/about/nachhaltigkeit/digitale-schweiz/sicherheit/bug-bounty/files/bug-bounty_04072020-04072022.asc">
	  Public key
	 </a>
	</td>
  </tr>
  <tr>
   <td>Portal link</td>
   <td>
    <a href="https://issue.swisscom.ch/servicedesk/customer/portal/3">
     Bug Bounty Portal
	</a>
   </td>
  </tr>
  <tr>
    <td>Postal address</td>
	<td>
	  Swisscom (Switzerland) Ltd<br>
	  GSE-CYD<br>
	  Bug Bounty Programme<br>
	  Förrlibuckstrasse 60/62<br>
	  CH-8005 Zürich<br>
	  Switzerland
	</td>
  </tr>
</table>


## 3 Responsible Disclosure Policy
To protect our customers, Swisscom does not publicly disclose or confirm 
security vulnerabilities until Swisscom has conducted an analysis of the 
reported vulnerability and issued fixes and/or mitigations in its 
Products or Services. 

By submitting a vulnerability report (hereinafter "Report") to Swisscom, 
you agree to not publicly disclose or share the reported vulnerability 
with any third party until Swisscom confirms that the vulnerability has 
been remediated. Swisscom will make every effort to remedy reported 
vulnerabilities within 90 days after notification of your Report to 
Swisscom. Swisscom must be informed in advance about your intended 
publications and their content. The publication must NOT include any 
customer, confidential or sensitive data, and must focus on the 
technical vulnerability discovered. 

In the event of publication, Swisscom and you shall mutually agree on a 
coordinated disclosure. 

If you submit a Report which affects a third-party service, we will 
limit the information that we share with any affected third party. We 
may share non-identifying content from your report with an affected 
third party. We will not share your identifying information with any 
affected third party without first obtaining your written permission. 


## 4 Safe Harbour Policy
The Swiss Penal Code qualifies any type of hacking as a major crime. 
This provision makes sure that you are safe from demands for a criminal 
sanction of Swisscom if you comply with the Programme Rules. If you 
violate these Rules, you may not only be prohibited from participating 
in the Programme in the future, but Swisscom also reserves the right to 
file criminal charges or take civil action against you. 

Please understand that Swisscom cannot and does not authorise security 
research that involves any customer assets (networks, systems, 
applications, products or services) managed by Swisscom in an 
outsourcing setting. If your security research involves assets that 
include data of a third party, such third party may take civil actions 
or file criminal charges against you. Swisscom cannot in any way offer 
to defend, indemnify or otherwise protect you from third-party claims or 
criminal charges against you. 

If you comply with the Programme Rules, Swisscom will honour its Safe 
Harbour Policy, as defined below: 

 * Swisscom interprets activities that comply with these Programme Rules 
as authorised access to our systems and will refrain from filing a 
complaint under Articles 
[143](https://www.fedlex.admin.ch/eli/cc/54/757_781_799/en#art_143),
[143<sup>bis</sup>](https://www.fedlex.admin.ch/eli/cc/54/757_781_799/en#art_143_bis)
and 
[144<sup>bis</sup>](https://www.fedlex.admin.ch/eli/cc/54/757_781_799/en#art_144_bis)
of the [Swiss Criminal Code](https://www.fedlex.admin.ch/eli/cc/54/757_781_799/en). 
 * If a criminal charge or legal action is initiated against you and you 
have complied fully with the [Programme Rules](#54-programme-rules), 
Swisscom will make every effort to inform the authorities that your 
actions were conducted in compliance with Swisscom’s Bug Bounty 
Programme. 


## 5 Bug Bounty Programme
Swisscom was the first company in Switzerland to introduce a Bug Bounty 
Programme (hereinafter "Programme"), which has been up and running since 
2015. The Programme continues to be distinguished for its openness 
today: 

 * Open participation for the global community of security researchers 
 * Open scope including all enterprise assets
 * Open-ended, unlimited duration

Participants are permitted to perform tests and investigations within 
the systems provided they act in good faith and respect the scope and 
rules described below. 


### 5.1 Eligibility
You are **eligible** to participate in the Programme if you meet **all** 
of the following criteria: 

 * You are of legal age and have the legal capacity to give your consent 
to the terms of these Programme Rules. 
 * If you are acting in the name of and on behalf of your employer, you 
must clearly state this during the Registration Process and confirm that 
you are authorised to give your consent to the terms of these Programme 
Rules in the name of and on behalf of your employer. You are responsible 
for reviewing your employer's rules for participating in this Programme. 
Swisscom disclaims any and all liability or responsibility for disputes 
arising between you and your employer related to this matter. 
 * Public Sector Employee: if you are a public sector employee, please 
contact our Bug Bounty team using the details above prior to any testing 
activities 

You are **not eligible** to participate in the Programme if you meet 
**any** of the following criteria: 

 * You do not fulfil all the above criteria
 * You are a resident or a national of any country subject to 
international or Swiss sanctions 
 * You are a resident or a national of any country that does not allow 
participation in this type of Programme 
 * You are currently an employee of Swisscom, or an immediate family or 
household member of such an employee 
 * Within the six months prior to providing us your Submission, you were 
an employee of Swisscom 
 * You currently (or within six months prior to providing us your 
Submission) perform services for Swisscom or a Swisscom subsidiary in an 
external staff capacity that requires access to the Swisscom Network, 
such as agency temporary worker, vendor employee, contractor 


### 5.2 Programme Scope
In principle, any Swisscom-owned assets are intended to be within the 
scope of the Programme. This includes almost all networks, systems, 
applications, products or services for which Swisscom is accountable. 

Likewise, assets from affiliated companies are also in scope if Swisscom 
Ltd owns more than 50% of the company shares. You can find a list of 
such participations in the current [annual 
report](https://reports.swisscom.ch/) under *Group Companies*. However, 
certain exceptions apply; for example, [Fastweb 
SpA](https://www.fastweb.it/) is explicitly out of scope. 

Swisscom's customer systems or customer systems outsourced to Swisscom 
are explicitly out of scope. 

A non-exhaustive list of assets is maintained here as an [authoritative 
source of the programme scope](scope). Participants must ensure to 
restrict their research and testing activities as defined in the 
*in-scope* and *out-of-scope* lists. Note that items in the 
*out-of-scope* list take precedence over the *in-scope* items. Testing 
on non-declared or *out-of-scope* assets will be viewed as a violation 
of the Programme Rules and any report on such will be disregarded. If a 
Swisscom asset is missing from the list, please contact the Bug Bounty 
team to validate and extend the scope accordingly. 


### 5.3 Qualifying Vulnerabilities
Any design, implementation or configuration issue that substantially 
affects confidentiality or integrity is likely to be eligible for a 
reward. Please refer to [vulnerabilities](vulnerabilities) for details. 


### 5.4 Programme Rules
The Rules of the Swisscom Bug Bounty Programme as defined in this 
document (hereinafter the "Programme Rules") govern the entire agreement 
between Swisscom and the participants (hereinafter "you") concerning the 
Swisscom Bug Bounty Programme. 

By participating in the Programme in any manner, you accept these 
Programme Rules. The Programme Rules may be changed unilaterally by 
Swisscom at any time. By participating in the Programme, you accept the 
Programme Rules applicable at that time. If you do not agree, you are 
not entitled to participate in the Programme. Swisscom reserves the 
right to terminate or discontinue the Programme at its discretion. 


#### 5.4.1 Registration
To participate in the Swisscom Bug Bounty Programme:
 1. You must register an account via our Bug Bounty Portal
 2. You must create a ticket of type "Register for Swisscom's Bug Bounty 
programme": 
   * You must provide your name and postal address as well as a copy of an 
identity document (e.g. passport or ID card) 
   * You are required to provide your bank details in order to receive 
Bounty payments (see below: [Payment 
modalities](#561-payment-modalities)) 
   * You must confirm that you have read these rules and will follow them 
 3. You must wait for confirmation of your registration from the Bug 
Bounty team before starting any research and testing 

You are required to register before starting any research and testing 
activity on our infrastructure. Reports originating from unknown 
participants will be disregarded and viewed as a violation of the 
Programme Rules. 


#### 5.4.2 Impact on operations
 1. You must avoid tests that could impair, interrupt or otherwise damage 
Swisscom services, services owned by Swisscom customers or other third 
parties. 
 2. You must avoid tests that could compromise, destroy or otherwise 
damage Swisscom data, data owned by Swisscom customers or other third 
parties. 
 3. You are expected to take all necessary technical and organisational 
measures to minimise the impact of your testing activity. For example, 
make sure you know what you are doing when using automated tools and 
limit your requests per second. 


#### 5.4.3 Confidentiality
 1. You must report any detected vulnerabilities exclusively to Swisscom 
through our portal. You must refrain from disclosing vulnerabilities to 
third parties, including customers of Swisscom that may be affected. 
 2. You must not publicly disclose any discovered credentials (e.g. 
passwords, tokens, API keys, etc). 
 3. Any obtained or downloaded data must not be disclosed to third 
parties and may not be used for any purpose other than reporting the 
vulnerability to Swisscom under this Programme. 
 4. Any obtained or downloaded data must be irrevocably erased from your 
systems immediately after reporting the vulnerability to Swisscom. 


#### 5.4.4 Interference with other parties
 1. You must refrain from interfering with other participants’ work 
when searching for vulnerabilities. 
 2. You must refrain from interfering with any devices or accounts from 
other Swisscom customers or third parties. 


#### 5.4.5 Data minimisation
 1. You must limit the amount of data accessed to a strict minimum. 
 2. You are expected to access the minimal amount of data necessary to 
prove the existence of a vulnerability. 


#### 5.4.6 Transgression of scope
If you happen to find yourself in a customer system managed by Swisscom, 
if you identify data that does not belong to Swisscom or if you have 
doubts about the type of system (Swisscom or customer) you are searching 
in, please stop further research in the system immediately and contact 
the Bug Bounty Team. 


#### 5.4.7 Social engineering
Any social engineering techniques such as phishing, smishing or vishing 
are forbidden. 


#### 5.4.8 Jurisdisction
You are expected to comply with all laws applicable to you.


#### 5.4.9 Abuse
 1. You must refrain from any misuse of Swisscom services, e.g. for 
sending unsolicited bulk email, postings, contact requests, SMS (text 
messages), instant messaging, etc. 
 2. You are not allowed to register duplicate accounts on the Bug Bounty 
portal. 


#### 5.4.10 Communication
Use only official communication channels as defined on the Swisscom Bug 
Bounty website. 


#### 5.4.11 Code of conduct
Swisscom expects you to comply with the following standards of behaviour 
when participating in the Programme. If you violate these standards, you 
may be prohibited from participating in the Programme in the future and 
any submissions you have provided may be deemed to be ineligible for 
Bounty payments. 

 1. No abusive language or harassment: we do not engage in and will not 
tolerate any form of threats, profanity and hateful speech, 
discrimination based on ethnicity, nationality, religion, sexual or 
gender identity or orientation, as well as age, level of experience or 
personal appearance. 
 2. Do not engage in any form of reputation-damaging behaviours or 
activities targeted at creating an unfair reputational advantage or 
rewards. 
 3. Do not engage in any activity that exploits people, harms people or 
risks harming people. 
 4. Do not share inappropriate content or material (involving, for 
example, nudity, bestiality, pornography, graphic violence or criminal 
activity). 
 5. Do not engage in any activity that is false or misleading.
 6. Do not engage in any activity that is harmful to you, the Programme 
or others (e.g., transmission of viruses, stalking, posting of terrorist 
content, communicating hate speech or advocating violence against 
others). 
 7. Do not infringe upon the rights of others (e.g., unauthorised sharing 
of copyrighted material) or engage in activity that violates the privacy 
of others. 
 8. Do not cause harm to Swisscom or to our customers, do not attempt to 
access our offices, data centres or any user accounts other than your 
own. 
 9. Do not help others to break these rules.


### 5.5 Reporting Guidelines
To support our triage process, please observe the following guidelines 
when submitting reports: 

 * The vulnerability must affect an in-scope asset (see [Programme 
Scope](#52-programme-scope) and must qualify for the Programme (see 
[Qualifying Vulnerabilities](#53-qualifying-vulnerabilities)). 
 2. You must send a clear, written description of the report along with 
step-by-step instructions to identify the affected asset and to 
reproduce the issue. Include attachments such as screenshots or 
proof-of-concept code, as necessary. 
 3. The written description of the report must contain a timestamp and 
source IP address for your attack attempt so we can identify your 
requests in the log files. In addition, you may also use distinctive 
identifiers in your requests, where applicable. For example: 
    * Set a distinctive reverse DNS entry for your IP address 
    * Append the string `-bugbounty-<username>` to the User-Agent 
header for HTTP requests 


### 5.6 Rewards
Monetary Rewards (hereinafter “Bounties”) for Reports may be awarded 
at Swisscom's full discretion. The Bounty amount depends on the business 
criticality of the reported vulnerability, the impacted system or data, 
and on the quality of the documentation provided to Swisscom. In 
general, rewards will be paid after remediation of the vulnerability, 
and you will be asked to validate the remediation measures. 

The following requirements for awarding a Bounty apply:
 * The vulnerability must affect an in-scope asset (see [Programme 
Scope](#52-programme-scope) and must qualify for the Programme (see 
[Qualifying Vulnerabilities](#53-qualifying-vulnerabilities)). 
 * You must be the first reporter of the vulnerability.
 * Reports on vulnerabilities having the same root cause (remediation in 
a single point), as well as enumeration of identical vulnerabilities may 
be merged into one report. In this case, the awarded Bounty would 
consist of a base reward + bonus for each additional finding. 


#### 5.6.1 Payment modalities
To ensure that you receive any Bounties to which you are entitled, 
please note the following prior to participation in the Programme: 

 * Rewards are paid out in Swiss francs (CHF) by bank transfer only. Any 
other payment channels are excluded. 
 * You must hold a bank account in your own or your company's name. 
Payments to entities other than the reporter are not allowed for legal 
reasons. 
 * It will only be possible to award Bounties if you meet the payment 
modality requirements 

Upon request, Swisscom may issue an invoice in your/your company's name.

Bounty Payments shall be due net within 30 days of confirmation of 
payment. The Bounty, if any, shall cover all services provided by you, 
including the costs for your Bug Bounty activities, documentation, any 
expenses and incidental costs, and licence fees. If, for any reason, you 
are unable or unwilling to receive your Bounty, we reserve the right to 
rescind it. 

You/your company will be responsible for your own taxes levied to the 
respective party as legal taxpayer in accordance with the applicable 
local law. Each party shall bear its own income, withholding, sales, 
service, value-added, use, excise, consumption and any other taxes and 
duties. 


### 5.7 Public Recognition
Swisscom may publicly recognise individuals who have reported 
considerable vulnerabilities under the Programme and been awarded 
Bounties.

Swisscom may, at its discretion, give you recognition on websites or 
other printed materials, unless you explicitly ask us not to include 
your name. 


### 5.8 Bug Bounty Agreement, Applicable Law and Jurisdiction
Upon your registration as reporter for the Program, you must agree to 
these Program Rules and enter into a Bug Bounty Agreement with the terms 
of these Program Rules with Swisscom. 

#### 5.8.1 Activity clause

##### 5.8.1.1 Activity of the reporter
The reporter provides independent advisory services with checking the 
digital security precautions and measures at Swisscom (advisory 
activities). In this connection, Swisscom has no authority to issue 
instructions or to monitor the reporter. 

The reporter organizes and provides his services in this context 
according to his own organizational considerations and on his own 
professional and entrepreneurial responsibility, in particular with 
reference to the determination of the place of performance and the hours 
of activity. The reporter decides freely and independently how the 
service is provided. 

The reporter uses his own working tools (computer, mobile phone, tablet, 
printer, etc.) to provide the services. The reporter is not entitled to 
any compensation in this regard. In any case, Swisscom is entitled to 
all (work) results including the technical database and processing 
methods in connection with and / or resulting from the advisory activity 
in accordance with this agreement. 

##### 5.8.1.2 Scope of the agreement
This agreement applies from the time the advisor agrees to it. 

Should the reporter or Swisscom no longer wish to cooperate based on 
this agreement at a future point in time, the corresponding cooperation 
can be terminated at any time, unless this occurs at an inopportune time 
(i.e. a point in time that would have significant negative consequences 
for one of the partners). 

##### 5.8.1.3 Other activities
By agreeing to this agreement, the reporter confirms that he is also 
working for other clients. 

##### 5.8.1.4 Consulting fee
The client can pay a success-related fee for the consulting activity, 
the amount of which is at the discretion of the client. Relevant 
criteria can be the topicality and the respective news content for the 
client. There is no legal entitlement to a fee. 

#### 5.8.2 Subcontractors
The use of subcontractors or other third parties by the reporter is not 
permitted. 

#### 5.8.3 Data privacy, data protection, data secrecy

##### 5.8.3.1 Data protection
The reporter is obliged to comply with all data protection provisions 
and applicable data protection regulations within the scope of his 
activity and applies the necessary care to protect data. 

Data protection violations detected by the reporter must be reported to 
the client immediately. 

In particular, the reporter must observe the data protection regulations 
and instructions of Swisscom. Deficits in the Swisscom security system 
discovered by the reporter must be reported to the client immediately. 

##### 5.8.3.2 Data secrecy
The reporter is also obliged to maintain data secrecy in all of his 
activities for the client. Specifically, this means that the reporter 
keeps all information, data and personal data known or entrusted to him 
secret and does not pass it on to third parties. 

In addition to maintaining data secrecy and secrecy, there are further 
confidentiality obligations (such as the maintenance of business and 
trade secrets, see point 5) that must be observed. 

The abstract naming of a system vulnerability found is expressly not 
covered by the data secrecy and the obligation to secrecy. However, the 
designation of the reporter may only be made after the removal by the 
client. 

#### 5.8.4	Reporting obligation
If the reporter has the opportunity to access personal data or 
particularly sensitive personal data, the reporter shall notify Swisscom 
immediately in writing by email (Contact: 
[bug.bounty@swisscom.com](mailto:bug.bounty@swisscom.com) or via our 
portal. 


#### 5.8.5	Confidentiality
The reporter is obliged to keep all data, personal data and information 
received in connection with his consulting activity confidential and not 
to pass them on to third parties. 

The abstract naming of a system vulnerability found is expressly not 
covered by the obligation of secrecy. However, the name may only be 
given after Swisscom has remedied the vulnerability. 

In addition, the reporter is obliged to treat business and manufacturing 
secrets known to him confidentially and not to pass them on to third 
parties. The duty of confidentiality remains in place even after the 
consultation contract has ended. 

The reporter undertakes under no circumstances to establish direct or 
indirect contact and communication with the customers and customers of 
the customer. 

After completing his consulting work, the reporter will return in full 
all physical and digital documents, documents and data that he received 
in the course of fulfilling this consulting contract. Copies of 
documents, data and documents may not be made. 

#### 5.8.6 Tax clause
The reporter is solely responsible for the correct taxation of fees 
received. In the event that the payments are subject to VAT, the client 
shows the VAT and the VAT is paid by the client. 

The reporter furthermore guarantees that he will independently pay all 
(social) insurance contributions as well as all taxes and duties 
required by the applicable legislation for the provision of the advisory 
activity. At the request of the client, the reporter will provide 
evidence of having met these obligations. 


#### 5.8.7 IP clause
Swisscom is not claiming any ownership rights to your report. However, 
by providing any report to Swisscom, you: 

 * grant Swisscom the following non-exclusive, irrevocable, perpetual, 
royalty free, worldwide, sub-licensable license to the intellectual 
property in your report(i) to use, review, assess, test, and otherwise 
analyze your report; (ii) to reproduce, modify, distribute, display and 
perform publicly, and commercialize and create derivative works of your 
report and all its content, in whole or in part; and (iii) to feature 
your report and all of its content in connection with the marketing, 
sale, or promotion of this Program or other programs (including internal 
and external sales meetings, conference presentations, tradeshows, and 
screen shots of the Report in press releases) in all media (now known or 
later developed); 
 * agree to sign any documentation that may be required for us or our 
designees to confirm the rights you granted above; 
 * understand and acknowledge that Swisscom may have developed or 
commissioned materials similar or identical to your Report, and you 
waive any claims you may have resulting from any similarities to your 
report; 
 * understand that you are not guaranteed any compensation or credit for 
use of your report; and 
 * represent and warrant that your report is your own work, that you 
haven't used information owned by another person or entity, and that you 
have the legal right to provide the report to Swisscom. 


#### 5.8.8	Bank account
The reporter has to name a bank account for the processing. It is 
essential that the reporter himself, as an individual, is the recipient 
of the payment. If the reporter names a company account, he/she must be 
named as recipient. The use of a company account for this private 
purpose is in the responsibility of the reporter. He/she must obtain the 
appropriate permission from the respective company. Swisscom is not 
obliged to do so. 

#### 5.8.9	General provisions
Changes and additions to this agreement, including this provision, are 
only possible by means of a written agreement signed by both parties. 

Should any provision of this consultancy agreement be invalid or 
unenforceable, this shall not affect the validity of the remaining 
provisions of this agreement. The invalid or unenforceable provision is 
to be replaced by a valid provision that comes as close as possible to 
the economic purpose of the invalid or unenforceable provision. 

This agreement is subject to Swiss substantive law. The exclusive place 
of jurisdiction for all disputes arising from or in connection with this 
consulting contract is the Swisscom headquarters. Mandatory places of 
jurisdiction are reserved. 
