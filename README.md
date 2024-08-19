SNHU CS_305

*Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?*

Artemis Financial is a global financial services provider looking to modernize its operations with a strong emphasis on security. Their primary concern was safeguarding financial transactions and customer data, which are crucial for maintaining client trust and meeting regulatory standards like GDPR, PCI-DSS, SOX, and GLBA. The key issue they needed to address was establishing and maintaining secure communications to defend against threats such as phishing, DDoS, MitM attacks, and injection attacks, while also ensuring the security of their RESTful API and supporting infrastructure.

*What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?*

I successfully identified over thirty security vulnerabilities within Artemis Financial's codebase, including critical issues in dependencies such as the Spring framework and Apache Tomcat. Through a meticulous manual review and static testing, I was able to pinpoint these vulnerabilities. Secure coding is essential as it prevents exploitation by nefarious actors, protects sensitive information, maintains customer trust, and ensures compliance with legal and regulatory standards. Software security significantly contributes to a company's overall health by minimizing the risk of costly data breaches, maintaining operational continuity, and protecting the company's reputation.

*Which part of the vulnerability assessment was challenging or helpful to you?**

The static testing phase was particularly challenging at first, but practice makes perfect. It required analyzing multiple dependencies and identifying critical vulnerabilities within them. This phase was crucial for understanding the depth of the security issues within the software and provided a clear direction for the necessary security enhancements. The detailed report generated from static testing offered a comprehensive view of which vulnerabilities required immediate attention and which could be addressed later.

*How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?*

I enhanced security layers by implementing thorough input validation and sanitization, securing application configurations, and adopting secure coding practices. Additionally, I recommended using automated tools for continuous vulnerability scanning and implementing secure communication protocols like TLS. In the future, I would continue utilizing static analysis tools like SonarQube, combined with dynamic security testing, to assess vulnerabilities and determine the most effective mitigation strategies.

*How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?*

After refactoring the code, I ensured the application's functionality and security by conducting comprehensive tests, including unit tests, integration tests, and security-specific tests. To verify that no new vulnerabilities were introduced, I used static analysis tools to re-scan the codebase and performed manual code reviews. Automated regression testing was also employed to confirm that existing functionality was not disrupted.

*What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?*

During this project, I utilized static analysis tools like SonarQube, dependency management tools to track vulnerable libraries, and secure coding practices such as input validation and secure configuration management. I also used OWASP's ESAPI for input sanitization and Spring Security for authentication and authorization. These resources and practices will be invaluable for future assignments.

*Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?*

From this assignment, I could present the detailed vulnerability assessment report, which highlights the identification of critical issues within the software and the corresponding mitigation strategies. Additionally, I could showcase the refactored code that demonstrates secure coding practices and the implementation of security measures like input validation and secure configurations. The use of static analysis tools and the overall security enhancement plan would also serve as valuable evidence of my ability to ensure the security and reliability of complex software systems.
