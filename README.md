# email_spam_detection
  
![image](https://github.com/ericleee0119/email_spam_detection/blob/main/img/1.PNG)  
  
  
1. We create the Amazon Sagenaker and train the spam email detection model  
2. We create a domain
3. When we send the email to the domain, the email will push in the S3
4. S3 will trigger Lambda
5. Lambda will detect whether the email is spam or not
6. The domain send back a email to the sender to tell them whether the email is spam or not
7. We create a CloudFormation for this flow
 
