# CS-305-Portfolio
Secure software development project including a full vulnerability assessment, HTTPS implementation, dependency analysis, and secure coding practices for a financial services application.

Portfolio Reflection – Artemis Financial

Artemis Financial is a financial services company that required improved security for its web-based application. The company needed to ensure that sensitive financial data was transmitted securely and that its software was protected against known vulnerabilities. The primary issue to address was identifying existing security weaknesses in the application and implementing secure coding practices to mitigate those risks. The goal was to strengthen data protection, improve encryption methods, and ensure the application followed industry best practices for secure software development.

During the vulnerability assessment, I did well in systematically identifying security weaknesses using both manual code review and automated dependency scanning tools. I analyzed the application for insecure communication protocols, outdated dependencies, and weak cryptographic implementations. Coding securely is critical because insecure software can expose sensitive data, damage an organization’s reputation, and lead to financial loss or regulatory penalties. Strong software security adds value by protecting customer trust, maintaining compliance, and reducing operational risk.

One challenging but helpful part of the assessment was interpreting the vulnerability scan results and determining which findings were most critical. Some vulnerabilities required deeper research to understand their impact and appropriate mitigation strategies. This process improved my ability to evaluate risk severity and prioritize remediation efforts effectively.

I increased layers of security by implementing HTTPS with SSL/TLS, generating a self-signed certificate, refactoring code to use secure hashing algorithms, and updating vulnerable dependencies. I also ensured proper input validation and secure configuration practices were applied. In the future, I would continue using tools such as OWASP Dependency-Check, static code analysis tools, and secure code review practices to assess vulnerabilities and determine appropriate mitigation techniques.

To ensure the application remained functional and secure, I tested the application after refactoring to verify that secure communication was properly established and that the checksum functionality operated correctly. After making changes, I re-ran vulnerability scans to confirm that no new vulnerabilities were introduced. This validation step ensured that security improvements did not negatively impact functionality.

Resources and tools that were especially helpful included Maven dependency scanning, SSL certificate generation using Java keytool, secure hashing with SHA-256, and structured vulnerability assessment workflows. These tools and practices will continue to support my work in future secure software development projects.

If presenting this work to a future employer, I would highlight the completed Vulnerability Assessment Report and the refactored secure application demonstrating HTTPS implementation and secure checksum generation. This project demonstrates my ability to identify vulnerabilities, implement secure coding practices, validate mitigation efforts, and document findings clearly — all of which are essential skills in secure software development and cybersecurity.
