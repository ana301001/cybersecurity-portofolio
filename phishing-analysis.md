# Phishing Incident Analysis

## Scenario
A user reported receiving an email that appeared to be from a trusted service, requesting them to log in and verify their account details. The email created a sense of urgency, warning that the account could be suspended if no action was taken.

## Analysis
To determine whether the email was legitimate or malicious, I performed the following checks:

- **Sender verification:**  
  I examined the sender’s email address and domain. Although it looked similar to a legitimate domain at first glance, there was a slight variation (typo in the domain name), which is a common phishing technique.

- **Email content review:**  
  The message used urgent language and pressured the user to act quickly. It also contained generic greetings instead of addressing the user by name, which is often a red flag.
  
- **Link inspection:**  
  I analyzed the link included in the email without clicking on it directly. The URL redirected to a domain that did not match the official website and appeared suspicious.

- **General indicators:**  
  The email lacked proper formatting and consistency compared to official communications, reinforcing the suspicion that it was not legitimate.

## Conclusion
Based on the analysis, the email was identified as a phishing attempt designed to trick the user into revealing sensitive login credentials.

## Mitigation & Response
To address the incident, the following actions were taken:
- The user was informed about the phishing attempt and advised not to interact with the email.
- The malicious domain was noted and flagged for blocking.
- Awareness was reinforced by explaining how to identify similar phishing emails in the future.
- The incident was documented for future reference and learning purposes.

##  Key Takeaways
- Small differences in domain names can indicate phishing.
- Urgency and pressure are common social engineering tactics.
- Verifying links before clicking is essential for preventing compromise.
- User awareness is a critical layer of security.
