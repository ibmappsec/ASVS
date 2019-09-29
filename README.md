# Application Security Verification Standard (ASVS) Intro
The Application Security Verification Standard (ASVS) Project provides a basis for testing web application technical security controls and also provides developers with a list of requirements for secure development.
https://www.owasp.org/index.php/Category:OWASP_Application_Security_Verification_Standard_Project

# How to implement this standard
The Application Security Verification Standard defines three security verification levels, with each level increasing
in depth.
* ASVS Level 1 is for low assurance levels, and is completely penetration testable
* ASVS Level 2 is for applications that contain sensitive data, which requires protection and is the
recommended level for most apps
* ASVS Level 3 is for the most critical applications - applications that perform high value transactions, contain
sensitive medical data, or any application that requires the highest level of trust.
Each ASVS level contains a list of security requirements. Each of these requirements can also be mapped to
security-specific features and capabilities that must be built into software by developers

![ASVL Levels](asvs_levels.png)

# The Aim Of ASVS?
The primary aim of the Application Security Verification Standard (ASVS) Project is to normalize the range in the coverage and level of rigor available in the market when it comes to performing Web application security verification using a commercially-workable open standard. The standard provides a basis for testing application technical security controls, as well as any technical security controls in the environment, that are relied on to protect against vulnerabilities such as Cross-Site Scripting (XSS) and SQL injection. This standard can be used to establish a level of confidence in the security of Web applications. The requirements were developed with the following objectives in mind:

* Use as a metric - Provide application developers and application owners with a yardstick with which to assess the degree of trust that can be placed in their Web applications,
* Use as guidance - Provide guidance to security control developers as to what to build into security controls in order to satisfy application security requirements, and
Use during procurement - Provide a basis for specifying application security verification requirements in contracts.

# ASVS Table of Contents

### [V1: Architecture, Design and Threat Modeling Requirements](V1/README.md)
### [V2: Authentication Verification Requirements](V1/V1.1.md)
### [V3: Session Management Verification Requirements](V1/V1.1.md)
### [V4: Access Control Verification Requirements](V1/V1.1.md)
### [V5: Validation, Sanitization and Encoding Verification Requirements](V1/V1.1.md)
### [V6: Stored Cryptography Verification Requirements](V1/V1.1.md)
### [V7: Error Handling and Logging Verification Requirements](Security%20Playbook/1.%20Identify%20teams.md)
### [V8: Data Protection Verification Requirements](Security%20Playbook/2.%20Define%20the%20role.md)
### [V9: Communications Verification Requirements](Security%20Playbook/3.%20Nominate%20Champions.md)
### [V10: Malicious Code Verification Requirements](Security%20Playbook/4.%20Set%20up%20communication%20channels.md)
### [V11: Business Logic Verification Requirements](Security%20Playbook/5.%20Build%20solid%20knowledge%20base.md)
### [V12: File and Resources Verification Requirements](Security%20Playbook/6.%20Maintain%20interest.md)
### [V13: API and Web Service Verification Requirements](Security%20Playbook/5.%20Build%20solid%20knowledge%20base.md)
### [V14: Configuration Verification Requirements](Security%20Playbook/6.%20Maintain%20interest.md)

---
# Simplified diagram
