# Security Assessment

## Findings

### Weak Password Risk

Initial test accounts used simple passwords for laboratory purposes.

Risk:

* Password guessing attacks
* Credential compromise

Mitigation:

* Enforced password policy through GPO
* Minimum length set to 12 characters

### Centralized Authentication

All users authenticate through Active Directory.

Benefits:

* Centralized identity management
* Easier auditing
* Better access control

### DNS Integration

DNS integrated with Active Directory for domain services.

Benefits:

* Reliable name resolution
* Simplified administration
