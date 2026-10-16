# IAM Architecture and Practices

## 1. Introduction

IAM Architecture refers to the structure and components used to manage identities and control access to cloud resources.

IAM practices are the methods followed to ensure that only authorized users can access the required resources.

## 2. Components of IAM Architecture

### 2.1 Identity Repository

Stores information about users, groups, and service accounts.

### 2.2 Authentication System

Verifies the identity of users through passwords, OTPs, biometrics, or multi-factor authentication.

### 2.3 Authorization System

Determines which resources an authenticated user can access and what actions they can perform.

### 2.4 Policy Engine

Evaluates access policies and determines whether an access request should be allowed or denied.

### 2.5 Auditing and Monitoring

Records user activities and helps administrators identify suspicious access and security violations.

## 3. Important IAM Practices

- **Least Privilege:** Give users only the permissions they need.
    
- **Multi-Factor Authentication:** Use more than one verification method.
    
- **Role-Based Access Control:** Assign permissions according to job roles.
    
- **Regular Access Reviews:** Check permissions periodically.
    
- **Account Management:** Disable unused accounts and remove access when it is no longer required.
    
- **Monitoring:** Review access logs and investigate suspicious activity.
    

## 4. Working of IAM

1. A user requests access to a cloud resource.
    
2. The authentication system verifies the user's identity.
    
3. The authorization system checks the user's permissions.
    
4. Access is granted or denied according to the applicable policy.
    
5. The activity may be recorded in audit logs.
    

## 5. Real-Time Example

In a college cloud system, students can view their marks, faculty members can update marks, and administrators can manage user accounts. IAM assigns appropriate permissions to each role.

## 6. Conclusion

IAM architecture combines identity management, authentication, authorization, policies, and monitoring. Good IAM practices help protect cloud resources from unauthorized access.

[[07 - Cloud Security Policies and Protocols]]

