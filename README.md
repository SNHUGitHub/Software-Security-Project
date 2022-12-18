# CS305-Software-Security

# Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
The client was Artemis Financial. They are a consulting company that develops individualized financial plans for their customers. The financial plans include savings, retirement, investments, and insurance. The issue that they wanted to address was current and effective software security for their custom software. More specificially, they wanted to protect their clients' data and financial information in their public web interface by adding a file verification step to their web application. A data verification step in the form of a checksum is needed to transfer data and ensure secure communications.

# What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
What I did very well was laying out the details of the software security vulnerabilities that I found, in order to address the problem and solution of each one individually. It is important to code securely, because failing to do so can leave one's program vulnerable to security attacks that take advantage of breaking in to the program through code errors. The value that software security add to a company's overall wellbeing is huge. It protects the company's data to prevent losing a competitive edge to competitors, and personal data of the company's employees and customers. Moreover, it can also protect the data of any third-parties that are working with the company.  

# What part of the vulnerability assessment was challenging or helpful to you?
Input validation and encapsulation were the most challenging, because we did not go in-depth and practice the different ways that we can create security around these vulnerabilities. APIs, Cryptography, and Client/Server were the most helpful, because we were able to go in-depth and practice writing secured code to address these vulnerabilities. 

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased layers of security by identifying and addressing vulnerabilities through the use of the Vulnerability Assessment Process Flow. I plan to use this same process to address vulnerabilities and decide which mitigation techniques to use in the future. 

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I made certain that the code and software application were functional and secured by testing the code often. More specifically, I initially assessed the program before adding any code of my own to it. One way that I did this was running the OWASP Dependency-Check Maven and making note of the vulnerabilities in the dependency-check report. Then, I continuously tested the code as I added layers of code to the program. This allowed me to easily track when code errors occur. I checked to see whether I introduced new vulnerabilities after refactoring the code by running the OWASP Dependency-Check Maven again, and then comparing the new dependency-check report with the old one that was created before the refactoring. 

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
1. Vulnerability Assessment Process Flow in order to assess a program's security vulnerabilities in layers.
2. Manually inspect the code.
3. Running the OWASP Dependency-Check Maven and making note of the vulnerabilities in the dependency-check report before refactoring the code
4. Understanding the differences between an encryption algorithm cipher and hash algorithm cipher, such as knowing when to use what. 
5. Generating self-signed certificates.
6. Implementing a SHA-256 cryptographic hash algorithm to avoid collisions and create a checksum verification. In general, understanding what it means to implement a hash algorithm that avoids collisions in order to figure out the best current cipher for the job. 
7. Refactoring the code in the "application.properties" file to convert HTTP to the HTTPS protocol, and then manually add in a previously created self-signed certificate to the computer in order to allow the browser(s) to trust the certificate. 

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
How I can assess a program's security vulnerabilities, manually inspect a code for security vulnerabilities, run a OWASP Dependency-Check Maven and understand the dependency-check report, understand when to implement an encryption versus hash algorithm cipher, generate a self-signed certificate and manually allow the computer to trust it, create a checksum verification, and refactor the code in order to convert HTTP to the HTTPS protocol.
