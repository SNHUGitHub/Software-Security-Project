# About
The client in this project is Artemis Financial. They are a consulting company that develops individualized financial plans for their customers. The financial plans include savings, retirement, investments, and insurance. The issue that they wanted to address is current and effective software security for their custom software. More specificially, they wanted to protect their clients' data and financial information in their public web interface by adding a file verification step to their web application. A data verification step in the form of a checksum is needed to transfer data and ensure secure communications.

# What did I do very well when I found my client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
What I did very well was laying out the details of the software security vulnerabilities that I found, in order to address the problem and solution of each one individually. It is important to code securely, because failing to do so can leave one's program vulnerable to security attacks that take advantage of breaking in to the program through code errors. The value that software security add to a company's overall wellbeing is huge. It protects the company's data to prevent losing a competitive edge to competitors, and personal data of the company's employees and customers. Moreover, it can also protect the data of any third-parties that are working with the company.  

# How did I increase layers of security?
I increased layers of security by identifying and addressing vulnerabilities through the use of the Vulnerability Assessment Process Flow. I plan to use this same process to address vulnerabilities and decide which mitigation techniques to use in the future.

# How did I make certain the code and software application were functional and secure? After refactoring the code, how did I check to see whether I introduced new vulnerabilities?
I made certain that the code and software application were functional and secured by testing the code often. More specifically, I initially assessed the program before adding any code of my own to it. One way that I did this was running the OWASP Dependency-Check Maven and making note of the vulnerabilities in the dependency-check report. Then, I continuously tested the code as I added layers of code to the program. This allowed me to easily track when code errors occured. I checked to see whether I introduced new vulnerabilities after refactoring the code by running the OWASP Dependency-Check Maven again, and then comparing the new dependency-check report with the old one that was created before the refactoring. 

# Resources, tools, and coding practices that I used and are helpful to the project:
1. Vulnerability Assessment Process Flow in order to assess a program's security vulnerabilities in layers.
2. Manually inspect the code.
3. Running the OWASP Dependency-Check Maven and making note of the vulnerabilities in the dependency-check report before refactoring the code
4. Understanding the differences between an encryption algorithm cipher and hash algorithm cipher, such as knowing when to use what. 
5. Generating self-signed certificates.
6. Implementing a SHA-256 cryptographic hash algorithm to avoid collisions and create a checksum verification. In general, understanding what it means to implement a hash algorithm that avoids collisions in order to figure out the best current cipher for the job. 
7. Refactoring the code in the "application.properties" file to convert HTTP to the HTTPS protocol, and then manually add in a previously created self-signed certificate to the computer in order to allow the browser(s) to trust the certificate.
