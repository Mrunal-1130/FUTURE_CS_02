### Phishing Detection & Awareness

### Project Overview

This project demonstrates the process of identifying and analyzing phishing emails through email header analysis, sender domain verification, and phishing indicator identification. Four email samples were analyzed, including three simulated phishing emails and one legitimate business email. The objective is to understand common phishing techniques and improve email security awareness.


### Project Objectives

* Analyze phishing and legitimate email samples.
* Perform email header analysis.
* Inspect sender domains and embedded links.
* Identify common phishing indicators.
* Classify the risk level of each email.
* Document findings in a structured report.
* Develop phishing prevention and awareness guidelines.


### Email Samples

| Sample                                  | Type       |
| --------------------------------------- | ---------- |
| Fake Cloud Storage Account Verification | Phishing   |
| Fake Payroll Update                     | Phishing   |
| Fake Package Delivery Notification      | Phishing   |
| Project Status Meeting Scheduled        | Legitimate |


### Tools Used

The following tools were used during this project:

| Tool                               | Purpose                                                                                                             |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Gmail                              | Sending and receiving sample emails between test accounts.                                                          |
| Gmail – Show Original              | Extracting complete email headers and authentication results.                                                       |
| Google Admin Toolbox Messageheader | Analyzing email headers, SPF, DKIM, DMARC, and routing information.                                                 |


### Analysis Methodology

The following methodology was used to analyze each email:

### 1. Email Sample Collection

Three phishing emails and one legitimate email were created and exchanged between two personal test email accounts.

### 2. Email Header Analysis

The complete email headers were extracted using Gmail's **Show Original** feature. The following header fields were examined:

* From
* Return-Path
* Reply-To
* SPF
* DKIM
* DMARC
* Received Chain

### 3. Sender Domain & Link Inspection

The sender's email domain was compared with the official domain of the organization it claimed to represent. Embedded hyperlinks were also inspected to determine whether they pointed to legitimate or suspicious websites.

### 4. Phishing Indicator Identification

Each email was examined for common phishing characteristics such as:

* Unofficial sender domains
* Generic greetings
* Urgent or threatening language
* Suspicious hyperlinks
* Requests for sensitive information
* Unexpected attachments
* Social engineering techniques

### 5. Risk Classification

Each email was assigned a risk level based on its content and potential impact:

* Legitimate
* Medium Risk
* High Risk

### 6. Documentation

The findings were documented with screenshots, header analysis, phishing indicators, observations, and risk assessments.

### 7. Awareness Recommendations

Security recommendations were prepared to help users recognize and avoid phishing attacks.



### Key Findings

* The three phishing emails impersonated trusted organizations using unofficial sender domains.
* The phishing emails used urgency and social engineering techniques to manipulate recipients into revealing sensitive information.
* Suspicious hyperlinks redirected users to unofficial websites that could be used for credential theft.
* The legitimate email originated from the organization's official domain and contained normal business communication without phishing indicators.


### Conclusion

This project demonstrates a practical approach to phishing email detection by combining email header analysis, sender domain verification, phishing indicator identification, and risk assessment. It highlights the importance of user awareness and proper email verification techniques in reducing the risk of phishing attacks and protecting sensitive information.
