# Cplusplus-program-CS305

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial was a financial services company that needed stronger security for its web application. The company wanted to protect sensitive financial data and make sure users could communicate with the application securely. The main issue addressed was the lack of secure encrypted communication and the need for better data integrity checks.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I did well identifying secure coding improvements and adding security features to the application. I configured HTTPS on port 8443 using an SSL certificate and added a SHA-256 checksum endpoint to help verify data integrity. Secure coding is important because it protects customer information, reduces the chance of attacks, and helps prevent costly security problems. Software security adds value by improving customer trust, protecting the company’s reputation, and reducing business risk.

Which part of the vulnerability assessment was challenging or helpful to you?

The most helpful part of the vulnerability assessment was seeing how dependency checks and secure communication settings work together. It showed me that application security is not just about writing code, but also about checking libraries, certificates, and configuration settings. The challenging part was making sure the security changes worked correctly while still keeping the application functional.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased layers of security by using HTTPS, creating a keystore and SSL certificate, and implementing SHA-256 hashing for checksum verification. In the future, I would use dependency scanning, code review, certificate validation, secure coding standards, and vulnerability assessment tools to identify risks. I would choose mitigation techniques based on the severity of the vulnerability, the type of data being protected, and the possible impact to the organization.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I made sure the application was functional and secure by running the refactored code, testing the HTTPS configuration, and checking the hash endpoint in the browser. After refactoring, I would run another dependency check, review the code, and complete functional testing to make sure the application still worked correctly and that no new vulnerabilities or errors were introduced.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

The resources and tools I used included Java keytool, HTTPS/TLS configuration, SHA-256 hashing, Maven dependency checks, and secure coding practices. These will be useful in future assignments because they help verify secure communication, protect data integrity, and identify vulnerable dependencies before an application is released.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

For future employers, I could show the completed Artemis Financial secure software report, the working SSL server project, the configured HTTPS application, and the checksum feature. These examples show that I understand secure communication, certificate generation, checksum verification, dependency scanning, and secure coding best practices.
