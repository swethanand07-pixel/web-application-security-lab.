OWASP TOP 10 – 2025 ANALYSIS

1. Introduction

OWASP stands for Open Worldwide Application Security Project. It is an organization that helps improve software and web application security.

The OWASP Top 10 is a list of the most critical security risks affecting web applications. It helps developers understand vulnerabilities and implement security measures.

2. Objectives

- Understand common web application vulnerabilities.
- Identify security risks.
- Study the OWASP Top 10 categories.
- Understand preventive security measures.
- Learn secure coding practices.
- Improve application security awareness.

3. OWASP TOP 10 – 2025

A01 – Broken Access Control

Description:
Broken Access Control occurs when users can access resources or perform actions beyond their authorized permissions.

Example:
A normal user accessing an administrator-only page.

Impact:

- Unauthorized access.
- Data exposure.
- Modification of restricted information.

Prevention:

- Implement role-based access control.
- Verify permissions on the server.
- Apply the principle of least privilege.

A02 – Security Misconfiguration

Description:
Security Misconfiguration occurs when applications, servers or databases are not configured securely.

Example:
Using default passwords or displaying detailed error messages.

Impact:

- Information disclosure.
- Unauthorized access.
- Increased security risks.

Prevention:

- Disable unnecessary services.
- Change default credentials.
- Apply security updates.
- Use secure configuration settings.

A03 – Software Supply Chain Failures

Description:
Software Supply Chain Failures occur when vulnerabilities or compromises affect software dependencies, development tools, build systems or distribution processes.

Example:
An application using an outdated or compromised third-party library.

Impact:

- Software compromise.
- Data leakage.
- Unauthorized code changes.

Prevention:

- Use trusted software dependencies.
- Regularly update libraries.
- Verify software integrity.
- Review third-party components.

A04 – Cryptographic Failures

Description:
Cryptographic Failures happen when sensitive information is not properly protected using encryption.

Example:
Transmitting confidential information without HTTPS.

Impact:

- Exposure of sensitive data.
- Privacy violations.
- Unauthorized information access.

Prevention:

- Use strong encryption.
- Implement HTTPS.
- Protect encryption keys.
- Avoid storing sensitive data unnecessarily.

A05 – Injection

Description:
Injection vulnerabilities occur when untrusted input is interpreted as commands or queries by an application.

Example:
An application accepting unsafe database input without proper validation.

Impact:

- Unauthorized database access.
- Information disclosure.
- Data modification.

Prevention:

- Use parameterized queries.
- Validate user input.
- Apply safe input handling.
- Avoid unsafe command construction.

A06 – Insecure Design

Description:
Insecure Design occurs when security is not properly considered during the application design process.

Example:
A banking application designed without proper transaction verification.

Impact:

- Security weaknesses.
- Unauthorized operations.
- Business logic abuse.

Prevention:

- Follow secure design principles.
- Perform threat modelling.
- Include security requirements.
- Review application architecture.

A07 – Authentication Failures

Description:
Authentication Failures occur when an application does not properly verify the identity of users.

Example:
An application using weak authentication controls.

Impact:

- Unauthorized account access.
- Account compromise.
- Privacy risks.

Prevention:

- Use strong password policies.
- Implement multi-factor authentication.
- Apply secure session management.
- Use secure password storage.

A08 – Software or Data Integrity Failures

Description:
These failures occur when an application does not properly verify the integrity of software, updates or important data.

Example:
Installing software updates without verifying their authenticity.

Impact:

- Unauthorized modifications.
- Compromised application functionality.
- Data integrity problems.

Prevention:

- Verify digital signatures.
- Use trusted update sources.
- Validate important data.
- Protect software development pipelines.

A09 – Security Logging and Alerting Failures

Description:
This category occurs when security events are not properly recorded, monitored or reported through alerts.

Example:
Repeated failed login attempts occurring without generating a security alert.

Impact:

- Delayed incident detection.
- Difficulty investigating attacks.
- Reduced security visibility.

Prevention:

- Maintain security logs.
- Monitor suspicious activities.
- Configure appropriate alerts.
- Protect log information.

A10 – Mishandling of Exceptional Conditions

Description:
This occurs when applications do not properly handle unexpected situations, errors or abnormal conditions.

Example:
An application exposing confidential information through detailed error messages.

Impact:

- Information leakage.
- Application instability.
- Unexpected security weaknesses.

Prevention:

- Implement proper exception handling.
- Display safe error messages.
- Validate application states.
- Perform error-handling tests.

4. Secure Coding Practices

1. Validate all user inputs.
2. Use secure authentication methods.
3. Apply access control.
4. Encrypt sensitive information.
5. Keep software dependencies updated.
6. Handle errors securely.
7. Maintain security logs.
8. Perform regular security reviews.

5. Security Testing Methodology

The following methodology is used in the controlled security lab:

1. Identify: Understand the application and its security requirements.
2. Analyze: Study possible security weaknesses.
3. Test: Perform authorized tests in a safe sandbox.
4. Fix: Apply appropriate security improvements.
5. Document: Record findings and recommendations.

6. Tools Used

- GitHub – Project documentation and version control.
- OWASP ZAP – Authorized web application security testing.
- Browser Developer Tools – Inspecting application behaviour.
- HTML, CSS and JavaScript – Understanding web technologies.

7. Expected Outcomes

- Better understanding of web application security.
- Knowledge of OWASP Top 10 vulnerabilities.
- Improved secure coding awareness.
- Ability to document security findings.
- Understanding of vulnerability remediation.

8. Conclusion

The OWASP Top 10 provides important knowledge about common web application security risks. Understanding these vulnerabilities helps developers build safer and more reliable applications.

This analysis improves security awareness and provides a foundation for practical web application security testing.

9. References

- OWASP Official Website: https://owasp.org/
- OWASP Top 10:2025: https://owasp.org/Top10/2025/
- OWASP Foundation: https://owasp.org/projects/top-ten/

---

Prepared by: Swetha A
Module: 03 – Web Application Security
Duration: Day 11 – Day 15
