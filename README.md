# CS-305
Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
The client was a consulting company that develops individualized financial plans for its customers. The financial plans include savings, retirement, investments, and insurance.  Artemis Financial has a RESTful web application programming interface (API). The company is seeking Global Rain’s expertise about how to protect the organization from external threats.

What did you do well when you found your client’s software security vulnerabilities? 
I used the vulnerability assesment diagram and began to look for the weaknesses in the software. Assessing the INPUT VALIDATION, APIS, CRYPTOGRAPHY, CLIENT/SERVER, CODE ERROR, CODE QUALITY, and ENCAPSULATION I was able to verify the any deficiancies.

Why is it important to code securely? What value does software security add to a company’s overall well-being?
Secure coding is crucial for software development because it increases trust in the company, enhances reliability, and reduces the risk of data leaks. By following secure coding standards, developers can remove commonly exploited vulnerabilities and prevent future cyberattacks.

Which part of the vulnerability assessment was challenging or helpful to you?
The part of the vulnerability assessment that was most challenging for me was the identifying false postives in the OWASP dependency check. It took a lot of time and research to go through such a large document of vulnerabilities.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased layers of security by ensuring I had to latest verison of anything used in development. Specically, I used the most updated OWASP check for my maven build to run my vulnerability assessment. This was the lastest informaation could be obtained. Moving forward I would continue to use OWASP as well as manual code reviews and functional testing.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
To ensure the code was functional and secure I implemented a test application. This made sure the hash was properly implemented and secure. After refacting the code I ran a maven configuration using the OWASP check to view any additional vulnerabilities added. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
OWASP, Java Security Standard Algorithm Names, and the Iron-Clad Java textbook were the resources I used most and will likely return to for future assisnments.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
Implementing an alogorithm, building a POM.xl, keystore, application properties to access the keystore, test application for my alogorithm, and several other techniques that enhance my ability to perform cyber security.
