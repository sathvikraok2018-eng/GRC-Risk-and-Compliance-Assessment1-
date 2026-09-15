# GRC-Risk-and-Compliance-Assessment1- Small business TAX portal 

##📌Executive summary:

Small accounting and tax portal business handles high volume data of the customers or client which nedds high security.Data such as

##Sensitive Personally Identifialble Information(SPII)  ---  PAN/SSN Numbers ---  Aadhar card information  ---  Bank statements(Income statement)  ---  Banking records.

##In addition to these information the business has the web portal for uploading the sensitive and confidential information through the web portal which widens the gap for information leaks and cyber attacks on the information.

This project delivers a practical end-to-end Governance, Risk and Compliance (GRC) assessment for the small scale tax business firm.It establishes the baseline thteat model, quantifies cybersecurity risk across client lifecycle, defines core governance policies and maps security controls in accordance with the International Standards Framework (NIST CSF 2.0 Framework, ISO 27001:, SOC2)

-------

##🏢 FIRM CONTEXT AND DATA SCOPE 

**Business model: Tax services integrated with web portal uploads for documents uploads, in-person consultation and service appointment.

**Primary attack assests: Client SPII, Financial ledgers, web portal database and staff endpoints.

**Key data handled:
   
   *Government ID Numbers (PAN,Aadhar,SSN)

   *Income statemts and salary slips
 
   *Bank statemets and Investemts reciepts
   
   *Client portal login credential 



## ⚠️ IDENTIFIED CYBERSECURITY RISKS (RISK=LIKELIHOOD SCORE * IMPACT SCORE)

| Risk ID | Risk Domain | Description | Likelihood | Impact | Inherent Score | Target Control |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| RSK-01 | Web application security | Unauthenticated portal access/web upload vulnerabilities exposing client documents  | High | High | high | web application firewalls, input validation and security patching. |
| RSK-02 | Data governance | Local workstation download of SPII leading to unencrypted data sprawl | High | Critical | Critical | Endpoint encryption and Data retention |
| RSK-03 | Endpoint and Remote access | Unenforced MFA and BYOD(Bring Your Own Device) by seasonal employee leading to credential exposure | High | High | High | Uing of secure VPN (Virtual Private Network), Enforcing MultiFactor Authentication (MFA) |
| RSK-04 | Operational continuity | Phishing led Ransomware causing operational halt during business season | Medium | Critical | Critical | Establishing Endpoint Detection Response (EDR), Implementing immutable backups and anti phishing training |
| RSK-05 | Supply chain | Intercepted filings via third party tax software and weak APIs | Low | High | Medium | Third Party Risk Management (TPRM) and OAuth scoping |



