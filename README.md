# Boltium-toys-Scope-goals-and-risk-assessment-report.
Internal audit: Security recommendation for Botium toys focusing on Access control and Authentication policy
objective
To enhance the security of all users account and protect customer data (a requirement under GDPR and PCI DSS) by mandating stronger authentication methods and restricting unnecessary access.
Finding (Risk/Gap)
finding: The organization currently lacks a formal , enforced policy requiring strong passwords and multi-factor Authentication (MFA) for all employees accessing core systems and payment portals.
Risk;High. This leaves the comapny highly vulnerable to password -related attacks (e.g., brute force , credential stuffing) leading to a potential data breach , non- compliance fines , and reputational damage.
Recommended Action Items
Mandate multi-factor authentication (MFA) for all employees accessing company networks , cloud services and any system that handles customer data or financial information.
compliance justification -PCI DSS requirement 8: Requires MFA for all access into the Cardholder Data Environment (CDE) . GDPR Article 32: requires appropriate technical measures to ensure security.
Establish Strong Password policy - implement a policy that enforces : 12+ character minimum length , discourages password reuse, and recommends the use of a password manager tool.
Compliance justification -best practices for data protection and a fundamental security control
Enforce principle of least Privilege (PoLP) - Review user permissions across all systems (network, accounting , website backend). Revoke any access that is not strictly necessary for an employee to perform their job role.
Compliance Justification- Limits the damage an attacker or malicious insider can inflict if an account is compromised.
Disable default/ Unused Accounts - Immediately disable or delete all default vendor accounts (if applicable ) and any employee accounts that are no longer in use.
compliance Justification - Reduces the overall attack surface by eliminating unnecessary access points

