# Concept Note

## Summary of the action
To build an authentication system to authorise clients when connecting to a WiFi. Create a User Interface for the application and manage to develope an API for the application, Which can be later be deployed on docker for development purpose.


## Revelance
### Proposal
Wi-Fi networks, like any other technology, can be vulnerable to security risks if not properly configured and maintained. Two-factor authentication (2FA) is one way to improve the security of a Wi-Fi network by requiring users to provide two forms of identification before gaining access. This can help to prevent unauthorized access to the network and protect against common attack methods such as phishing and brute force attacks. However, it is important to note that 2FA is just one aspect of a comprehensive security strategy and it does not guarantee complete security. Other security measures such as regular software updates, encryption and firewalls should also be implemented.

### Problem
#### Integration
2FA usually depends on service or hardware provided by third parties. 

The use of a third-party service or hardware can create a dependency issue for an enterprise, as they have no control over the external service in the event of a malfunction.

This can potentially disrupt the ability of users to access the system and could lead to security vulnerabilities.

To mitigate this risk, it is important for enterprises to carefully evaluate the availability and reliability of third-party services and to have contingency plans in place to address potential disruptions.

### Solution
To build a personal strong encrypted 2FA system 

## Methodology
### Architecture
2FA architecture typically includes the following compenents:

1. Authentication server: This server is responsible for veriffying the users identity and providign access to the protected resource.
2. User Device: This is the device that the user uses to access the protected resource, such as a smartphone or computer.
3. Authentication methods: These are the methods used to verify the user's identity, such as a password, fingerprint, or biometric scan.
4. Commnication Channels: These are the channels used to transmit the authentication information between the user device and the authentication server, such as SMS, email, or push notifications.
5. Token generator: This is a hardware or software device that generates one-time passcodes that are used as a second form of authentication.
6. Secure storage: The place where the user's authentication information, such as their password or biometric data, is securely stored.

### Architectural Diagram 
[architecture diagram](Architectural_Diagram.png)
## Conclusion
The implementation of two-factor authentication (2FA) can have several benefits, including:

1. Improved security: By requiring two forms of identification, 2FA makes it much more difficult for unauthorized users to gain access to a system or service. This can help to prevent common attack methods such as phishing and brute force attacks.
2. Reduced risk of account takeover: With 2FA in place, even if an attacker manages to obtain a user's password, they will not be able to access the account without the second form of identification.
3. Compliance with regulations: Many industries have regulations that require the use of 2FA to protect sensitive information.
4. Increased user trust: By implementing 2FA, organizations can demonstrate to users that they take security seriously and are taking steps to protect their information.
It is worth to note that 2FA is not a silver bullet for security and it should be combined with other security measures such as encryption, firewalls, and regular software updates to have a comprehensive security strategy.
