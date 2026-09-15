# CS305-Portfolio
Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
  
  Artemis Financial is a financial services company specializing in client data management and secure financial transactions. Artemis Financial wanted to increase its security that included encryption for sensative data and 
  ensured integrity through cheksum while enforcing secure communication channels via HTTPS. The main issue was the risk of data breaches and unauthorized access.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
 
  I used a systematic approach witrh static and dynamic analysis. Assesment revealed multiple weaknesses in data handling and storage practices. Secure coding is vital for preventing security breaches, 
  data leaks, and compliance violations. It builds trust with clients and stakeholders by ensuring that their sensitive information is protected. Furthermore, investing in software security reduces the 
  potential financial and reputational damage associated with data breaches. Software security adds immense value to a company’s overall well-being by protecting its assets and reputation. Secure software 
  leads to increased customer trust, better compliance with regulations, and reduced costs associated with data breaches.

Which part of the vulnerability assessment was challenging or helpful to you?
  
  What had challenged me the most was creating a comprehensive analysis of the existing code to find hidden vulnerabilities. There are many different forms attacks may come in and this project deepened my understanding
  of common vulnerabilities such as injection attacks, cross site scripting, and poor data storage practices. Learning to identify these attacks improved my coding making it much more secure.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
  
  To increase the layers of security I implimented encryption through AES, checksum validation using SHA-256, and enforced HTTPS to secure data in transit. In the future I could impliment OWASP ZAP automated vulenrability scanning.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
  
  To ensure functionality I utilized unit testing along with static code analysis. After refactoring, I conducted regression testing to confirm that existing functionalities were preserved and that no new vulnerabilities were introduced.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
  
  I utilized SpringBoot, BouncyCastle, SHA-256, AES, and OWASP's database to ensure the data would be protected.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
  
  From this assignment I would showcase the comprehensive reporting and vulnerability assesment process. As well, my refactored code with secure preacticing and the implimentation of encryption and cheksum validation. I would also showcase 
  the unit testing performed showing how the vulnerabilities were identified and addressed.
