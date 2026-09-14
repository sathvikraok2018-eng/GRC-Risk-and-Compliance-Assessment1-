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

##⚠️IDENTIFIED CYBERSECURITY RISKS (RISK=IMPACT SCORE * LIKELIHOOD SCORE)
RIsk ID      |   Risk Domain     |    Description               | Likelihood     |     Impact   |  Inherent score   |     Target control 
             |                   |                              |                |              |                   |
RSK-01       | web application   |   Unauthenticated portal     |                |              |                   |  Web app firewalls, Input 
               security             access/web upload             HIGH                HIGH          HIGH               Validation and Security patching
                                    vulnerabilities exposing
                                    client documents


