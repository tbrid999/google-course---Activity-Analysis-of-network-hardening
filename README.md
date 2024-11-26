# google-course---Activity-Analysis-of-network-hardening
Part One: Analysis of Vulnerabilities
After a comprehensive review of the organization’s network, the following vulnerabilities were identified as the root cause of the recent data breach:

Shared Passwords Among Employees: Sharing passwords increases the risk of unauthorized access and weakens individual accountability, making it difficult to determine who accessed sensitive systems or data.

Default Admin Password for the Database: A default password is an easy target for brute force attacks and malicious actors, as these passwords are widely known and documented.

No Firewall Rules in Place: Without traffic filtering, the network is exposed to unauthorized access and malicious activity. It is easier for attackers to infiltrate or exfiltrate data.

No Multifactor Authentication (MFA): The absence of MFA means that compromised passwords are sufficient for attackers to gain access to critical systems and sensitive data.

If these vulnerabilities remain unaddressed, the organization is at high risk of future data breaches or other attacks, potentially resulting in customer trust loss, regulatory penalties, and significant financial damage.

Part Two: Recommended Security Hardening Practices
To address these vulnerabilities and prevent future incidents, the following hardening techniques are recommended:

1. Implement Strong Password Policies
Details: Establish a strict password policy that prohibits password sharing and enforces the use of strong, unique passwords for all accounts. Strong passwords should include a combination of upper- and lowercase letters, numbers, and special characters.
Why Effective:
Minimizes the risk of brute force attacks by increasing password complexity.
Ensures accountability by assigning unique credentials to each user.
Frequency: Passwords should be updated regularly, ideally every 60–90 days. Implementing tools like password managers can help employees securely store and manage unique passwords.
2. Enforce Multifactor Authentication (MFA)
Details: Enable MFA across all employee and administrative accounts. This adds an additional layer of security by requiring a second verification factor (e.g., a one-time password sent to a mobile device or email).
Why Effective:
Prevents unauthorized access even if a password is compromised.
Reduces the likelihood of successful phishing or brute force attacks.
Frequency: MFA should be a permanent security feature, configured and maintained as part of the organization’s authentication policy.
3. Configure and Monitor Firewall Rules
Details: Set up firewall rules to filter incoming and outgoing network traffic based on defined criteria, such as IP addresses, protocols, and ports.
Why Effective:
Protects the network perimeter by blocking unauthorized access and malicious traffic.
Reduces the risk of data exfiltration and lateral movement within the network.
Frequency: Firewall configurations should be reviewed quarterly and updated as needed. Monitoring should be continuous with automated alerts for suspicious activity.
4. Remove Default Admin Passwords
Details: Change all default passwords on critical systems and databases to strong, unique passwords immediately.
Why Effective:
Eliminates one of the most common attack vectors used by malicious actors.
Enhances overall system security by reducing the risk of unauthorized access.
Frequency: Default passwords should be changed during initial system setup. Regular audits should verify that no default credentials remain in use.
Conclusion
By implementing these network hardening practices, the organization can significantly reduce the risk of future data breaches. Strong password policies, MFA, configured firewall rules, and the elimination of default passwords will create a more secure environment, protect customer data, and restore trust in the organization’s commitment to security. Regular reviews and updates to these practices will ensure continued protection against evolving threats.
