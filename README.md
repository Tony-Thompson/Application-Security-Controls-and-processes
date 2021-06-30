# Application Security Control (ASC)

An ASC is one of the base concepts of ISO 27034. An ASC is simply a control to prevent a security weakness within an application. For example, “binding variables in SQL statements” is an application security control to prevent SQL injection  —  a common application security weakness. ASCs are actions that we take as a matter of process, procedure or automation to reduce security risks. They may be identified by security audits or as a part of projects and continuous improvement. 

Even though ASCs use contexts to derive when they apply to a particular product, not every product we build has the same need for security controls. For example, an internal-facing application with no sensitive data (e.g. ScanStation) has a very different risk profile than a web-facing application with customers’ personally identifiable information (e.g. BetterOff). For this reason, ISO 27034 introduces the concept of Levels of Trust. Each ASC we create will have one or more levels of trust.

The following items are illustrative examples of ASCs which we follow. Subsequent pages will address each one in more detail and record our approach and/or actions to each. By virtue of being a library, more will be added over time and some may be removed. 

## Authentication

Employees are required to pass multi factor authentication before gaining access to Looking Local resources. Multi-factor authentication is a process of verifying identity using at least two independent factors including what a person knows, possesses and physical attributes of a person such as their voice. The following are common factors that are used in multi-factor authentication processes.

#### Passcode ~ A numeric password such as a personal identification number (pin).
#### Password ~ A user created string of characters.
#### Challenge / Response ~ Answers to challenge questions that may include obscure personal information.
#### Magnetic Stripe Cards ~ Cards that contain data such as identification numbers written on magnetic storage media. May include other security features such as an employee id card with a photo on the front.


## Audit Trail
A web server records IP addresses and URLs for each access and retains such information for a period of time as an audit trail. An audit trail is information that is recorded by an information technology for the purposes of aiding a future audit or investigation. It is common for technologies such as websites, business applications, communication tools, databases and operating systems to create logs that can be used to recreate past activities for purposes such as security investigations. In many cases, these logs are maintained for a time and eventually deleted. 
Beyond information that is automatically recorded by technology, it is common for us to implement an audit trail for risk management, compliance, legal, human resources, health and safety information that are specifically designed to capture and retain anything that might help future investigations in these areas.

## Training

Employees are trained in defensing computing on an annual basis.

## Peer Review

Design changes to a critical system require a secure code review.

## Communication

Employees are prohibited from attaching documents to internal emails as they can easily be misaddressed. Instead, employees send a link to a document management system that offers authentication and authorization.

## Incident Management

Any employee who loses an electronic device that has been used for work is required to report an incident immediately.

## Cryptography

Data in storage is encrypted on all devices. Encryption is the conversion of data into a format known as ciphertext that can't be understood without a key. It depends on the strength of its algorithms and keys but properly implemented it is difficult or infeasible to break. Encryption is a cornerstone of information security that enables privacy, secure communication and ecommerce. The following are basic encryption concepts and techniques.
Cleartext
Cryptography
Format-preserving Encryption
Hashcode
Key Stretching
Keys
Nonce
Pepper
Plaintext
Private Key
Pseudorandom
Public Key
Public Key Encryption
Random Seed
Salt
Strong Password
Symmetric Encryption

## Passwords

Systems perform validation to ensure employees choose strong passwords.

## Processes

An IT governance process reviews security incidents on a monthly basis.

## Automation

A website places a three hour freeze on a customer's account if they get their password wrong five times. This dramatically reduces the potential for brute force attacks.

## Configuration Management

Changes to firewall rules require an approved change request.

## Security Testing

Major system software releases are required to undergo security testing.


The Council on CyberSecurity Critical Security Controls list some high level measures that we implement as part of our  implement in software. Among the 20 critical controls listed above there is also the concept of  “Application Software Security” with 11 recommended implementation measures:

1.) Patching
2.) Implement a Web Application Firewall (WAF)
3.) Error checking all input
4.) Use an automated scanner to look for security weaknesses
5.) Output sanitization of error messages
6.) Segregation development and production environments
7.) Secure code analysis, manual and automated
8.) Verify vendor security processes
9.) Database configuration hardening
10.) Train developers on writing secure code
11.) Remove development artifacts from production code

Of these 11, it is interesting to note that two relate to infrastructure architecture, four are operational, two are part of testing processes, and only three are things that are done as part of coding.

While many controls are definitely of a technical nature, it is important to distinguish the way in which controls differ from coding techniques. Many things we might think of as controls, should more properly be put into coding standards or guidelines. As an example, NIST SP800-53 suggests five controls related to session management




| ID      | Title | How-Tos |
| ----------- | ----------- | ----------- |
| Active Attack | Title       |Title       |
| Advanced Persistent Threat | Title       |Title       |
| AI Box | Title       |Title       |
| Antifragile | Title       |Title       |
| Audit Trail | Title       |Title       |
| Backdoor | Title       |Title       |
| Canary Trap | Title       |Title       |
| Critical Infrastructure | Title       |Title       |
| Cryptographic Keys | Title       |Title       |
| Cryptographic Salt | Title       |Title       |
| Cryptography | Title       |Title       |
| Cybersecurity | Title       |Title       |
| Data Breach | Title       |Title       |
| Data Remanence | Title       |Title       |
| Data Room | Title       |Title       |
| Data Security | Title       |Title       |
| Data Sovereignty | Title       |Title       |
| Data Wipe | Title       |Title       |
| Deep Magic | Title       |Title       |
| Defense In Depth | Title       |Title       |
| Defense In Depth | Title       |Title       |
| Defensive Computing | Title       |Title       |
| Degaussing | Title       |Title       |
| Digital Identity | Title       |Title       |
| Document Control | Title       |Title       |
| Failure Of Imagination | Title       |Title       |
| Format-preserving Encryption | Title       |Title       |
| Geofencing | Title       |Title       |
| Hardening | Title       |Title       |
| Hashcode | Title       |Title       |
| Honeypot | Title       |Title       |
| Human Error | Title       |Title       |
| Information Security Testing | Title       |Title       |
| Input Validation | Title       |Title       |
| IoT Security | Title       |Title       |
| Key Stretching | Title       |Title       |
| Multi-Factor Authentication | Title       |Title       |
| Mutual Authentication | Title       |Title       |
| Need To Know | Title       |Title       |
| Network Security | Title       |Title       |
| Non-repudiation | Title       |Title       |
| Nonce | Title       |Title       |
| Operations Security | Title       |Title       |
| Overlay Network | Title       |Title       |
| Passive Attack | Title       |Title       |
| Password Entropy | Title       |Title       |
| Password Fatigue | Title       |Title       |
| Patch Management | Title       |Title       |
| Penetration Test | Title       |Title       |
| Principle Of Least Privilege | Title       |Title       |
| Privacy | Title       |Title       |
| Proof Of Work | Title       |Title       |
| Proxy Server | Title       |Title       |
| Pseudorandom | Title       |Title       |
| Sandbox | Title       |Title       |
| Secure Code Review | Title       |Title       |
| Security As A Service | Title       |Title       |
| Security Controls | Title       |Title       |
| Security Event | Title       |Title       |
| Security Through Obscurity | Title       |Title       |
| Strong Authentication | Title       |Title       |
| Tarpit | Title       |Title       |
| Tokens | Title       |Title       |
| Zero-day | Title       |Title       |
