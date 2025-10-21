# phishing-email-analysis
Analysis of a phishing email sample highlighting suspicious characteristics for internship task
# Phishing Email Analysis Report

## 1. Sender Information
- Email address: tate@cobratate.com 
- Likely spoofed domain

## 2. Email Headers
- SPF: Pass  
- DKIM: Fail  
- DMARC: Fail  
- Email originated from an unusual IP address not matching the official domain

## 4. Email Body
- Urgent message: "AWS had issues for a few hours and 90% of the internet went down with it."

## 5. Summary of Phishing Traits
- Sender spoofing  
- Authentication failures in DKIM/DMARC    
- Urgent/threatening language  
  

## Conclusion
This email exhibits classic phishing signs despite passing SPF. Failing DKIM and DMARC strongly indicates the message is not trustworthy.
