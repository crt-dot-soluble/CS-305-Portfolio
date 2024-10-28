### Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

The client, **Artemis Financial**, is a financial services provider that handles sensitive client data, including savings plans, retirement details, investments, and insurance. The company required a secure software application to protect client data from cyber threats. The primary issues Artemis Financial wanted to address included securing communications, protecting data integrity, and mitigating vulnerabilities in their software, such as outdated libraries and improper access control.

### What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I conducted a thorough **manual review** and **static testing** of the codebase, identifying critical vulnerabilities such as hardcoded credentials, unencrypted database connections, and input validation issues. Secure coding is vital because it prevents exploitation by attackers who could compromise sensitive data or disrupt operations. **Software security** adds tremendous value to a company’s well-being by protecting its **reputation**, ensuring **compliance with regulations**, and maintaining **client trust**. By addressing these vulnerabilities, I helped Artemis Financial safeguard its systems from potential security breaches.

### Which part of the vulnerability assessment was challenging or helpful to you?

The **static testing** using a dependency-check report was particularly helpful in identifying vulnerabilities in third-party libraries, such as **CVE-2019-17531** and **CVE-2020-11979**. One challenge was ensuring that all identified vulnerabilities were accurately mitigated without introducing new issues, especially when refactoring the code to remove hardcoded credentials and enforce secure communications.

### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased layers of security by:
- Implementing **HTTPS** to encrypt communications between the client and server.
- Using **SHA-256** for cryptographic hashing to ensure data integrity.
- Enforcing **input validation** to prevent injection attacks.
- Refactoring code to **remove hardcoded credentials** and secure database connections.

In the future, I would continue to use **manual code reviews**, **static analysis tools**, and **automated vulnerability scanners** to assess code security. I would then prioritize mitigation techniques based on the **severity of the vulnerabilities** and their **potential impact** on the system.

### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

To ensure the code was both functional and secure, I performed **functional testing** after refactoring the code, using secure communication protocols like HTTPS. I also conducted **secondary testing** to verify that the refactored code did not introduce new vulnerabilities. This included rerunning **static tests** and manually checking areas where changes were made, such as database connectivity and input validation functions.

### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

- **SHA-256** for cryptographic hashing to ensure data integrity.
- **Java Keytool** for generating and managing SSL/TLS certificates.
- **Spring Boot** configurations for enabling secure HTTPS connections.
- **Dependency-check tools** for identifying vulnerabilities in third-party libraries.
- **Input validation** and **secure coding practices** to prevent common vulnerabilities such as SQL injection and XSS.

These tools and practices will be invaluable in future tasks requiring secure software development and vulnerability assessment.

### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

From this assignment, I would show future employers:
- My ability to identify, assess, and mitigate software vulnerabilities.
- The implementation of **HTTPS** and **cryptographic hashing** to secure communications and ensure data integrity.
- My experience in **refactoring code** to improve security without sacrificing functionality.
- Examples of my work with **static testing tools** and **manual code reviews** to ensure software security compliance.
These examples demonstrate my strong understanding of secure coding practices and my ability to protect critical software systems from security threats.
