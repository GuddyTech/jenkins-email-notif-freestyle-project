# jenkins-email-notif-freestyle-project

This is a Jenkins Frees Style Project to send email notification and attach files from directories and sunbdirectories to the email notification sent
The SMTP SERVER has to be working. So when you test the email connection, it has to connect.

## SMTP SERVER FOR EMAIL NOTIFICATION IN JENKINS
1. To create an SMTP Server for Jenkins: https://www.youtube.com/watch?v=diagLJuF2eI&t=303s
2. Manage jenkins
3. Plugins
4. Download the EXTENDED E-MAIL NOTIFICATION
5. Manage jenkins
6. System configuration
7. Extended E-mail Notification
8. SMTP server = smtp.gmail.com
9. SMTP Port = 465 for SSL
10. Click on Advanced and add credential = Username: guddytechs@gmail.com Password: google APP PASSWORDS
11. To get google APP PASSWORDS go to Google account
12. Security
13. App passwords
14. Input email and copy  password
15. Use the password in the jenkins credential
16. Select Use SSL
17. Default Content Type = HTML
18. E-MAIL NOTIFICATION
19. SMTP server = smtp.gmail.com
20. Advanced
21. User Name = guddytechs@gmail.com
22. Password = App Password
23. Use SSL
24. SMTP Port 465 for SSL
25. Charset UTF-8
26. Test configuration by sending test e-mail
27. You will receive the email if well connected
28. Go to the Freestyle Pipeline Project
29. Configure
30. Post - build Actions
31. Project Recipient List = guddytechs@gmail.com
32. Content type = HTML
33. Attachments = *.txt, **/*jar
34. Attach Build Log (optional)
35. Advanced setting
36. Triggers
37. Always
38. Send to RECIPIENT LIST
39. Advanced 
40. Recipient list = guddytechs@gmail.com

