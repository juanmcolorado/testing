Q1. If you are going to configure Mysql JDBC Database as Secondary User store Where should you place mysql driver?
    A) <IS-HOME>/repository/components/parches/patch<4_digit_number>

        correcto B) <IS-HOME>/repository/components/lib
        
        https://is.docs.wso2.com/en/6.0.0/deploy/change-to-mysql/#:~:text=Download%20the%20MySQL%20JDBC%20driver%20for%20the%20version%20you%20are%20using%20and%20copy%20it%20to%20the%20%3CIS_HOME%3E/repository/components/lib%20folder

    C) <IS-HOME>/repository/components/dropins
    D) <IS-HOME>/repository/components/plugins
Q2. What is a possible method to encrypt and decrypt user claim attributes when storing and retrieving in WSO2 Identity Server?
    A) Write a custom event listeners overriding POST and PRE operations of userstore.
    B) Write a custom authenticador
    C) Write a post authentication handler
    D) Write a custom password validator.
Q3. What is INCORRECT about internal and external roles of WSO2 Identity Server?
    A) External roles stores in a userstore itself and can be assigned only to user inside the userstore.
    B) Internal roles store in the Identity Server database and can be assigned to any user in any userstore
    C) Internal roles cannot be assigned to groups
    D) External roles store in a userstore itself and can be assigned to any user in other userstores.
Q4. When you create a new user what is the character NOT allowed for the username in the Identity server by default?
    A) Dot(i.e “.”)
    B) Dash(i.e “-”)
    C) Forward slash(i.e. “/”)
    D) Underscore(i.e.”_”)
Q5. Which of the following statements about the Password Recovery feature in WSO2 Identity Server is CORRECT?
    A) The REST API-based password recovery feature can be enable tenant-wise.
    B) Email templates for password recovery cannot be configured tenant-wise.
    C) The confirmation codes are stored in the registry during the REST API-based password recovery flows.
    D) The REST API-based password recovery feature can be enabled user stored-wise.
Q6. Which of the following statements about the ReCaptcha feature can be enabled tenant-wise.
    A) ReCaptcha can be configured to show up on the self user registration page.
    B) ReCaptcha can be configured to show up on the password recovery page.
    C) ReCaptcha can be configured to show up on the tenant creation page
    D) ReCaptcha can be configured to show up on the SSO(login)page.
Q7. Which of the following statement is CORRECT?
    A SCIM APIs can be used to lock a user account
    B SCIM APIs can be used to disable a user account
    C SCIM APIs can be used to initiate a forced password reset flow
        1. Only A
        2. Only A and B
        3. All of the above
        4. None of the above
Q8. Which of the following statement is TRUE about the password pattern configuration in WSO2 Identity Server?
    A) Privileged user can bypass the password pattern validation
    B) Password patterns can be configured user store-wise only.
    C) Password patterns can be configured both user store-wise and tenant-wise
    D) Password patterns can be configured tenant-wise only
Q9. Which of the following methods of forced password reset are used in WSO2 Identity Server?
    A) Password Reset via Recovery Email and OTP
    B) Password Reset via Recovery Email only
    C) Password Reset OTP only
    D) Password Reset via Recovery Email and OTP and Offline
Q10. Arrange the following OAuth tokens in the life time of Increasing order
    1 Authorization
    2 Access token
    3 Refresh token
        A) 1,2 and 3
        B) 1,3 and 2
        C) 3,1 and 2
        D) 3,2 and 1
Q11. What is the special parameter defined in the specification which can be used to limit the authorization grant?
    A) Scope
    B) Acr
    C) Permission
    D) Grant_limit
Q12. Which statement about grant types is FALSE?
    A) Authorization code, Implicit, Password, Client credential, and Refresh token grants are the initial grant types defined in the OAUHT core specification
    B) Grant types determine how a client application should obtain access tokens and what security credentials are used to gain access to resources.
    C) Grant types are picked based on the use care requirements, not the application type.
    D) Grant types such as SMAL2 bearer and JWT bearer are extended grant types in the OAuth 2.0 framework
Q13.  Which statement describes access delegation with respect to the IAM domain, more clearly?
    A) Provide the credentials that secure a resource owned by you to third party.
    B) Granting full access to a resource owned by you to a third party.
    C) Providing limited access to a secured resource owned by you to a third party to fulfill only a specific task on behalf of you.
    D) Change ownership of a secured resource owned by you to third party
Q14. What is the Callback URL?
    A) This is an endpoint in the client application
    B) This is the homepage of the client application, which initiates the authentication request
    C) This is the exact location in the client application in which the access token is sent
    D) This is the landing page of the client application user’s first access
Q15. Which of the following statements describes UMA 2.0?
    A) Enables controlled access of a user’s protected digital resources
    B) Enables auditing capabilities of user activity in the system
    C) Update username, mobile, and account number of the user
    D) All of the above
Q16. Which of the following can be done via UMA 2.0?
    A) Get the suspicious login alerts of the users
    B) Provide access to your resources for multiples users
    C) Block the user login based on the user role
    D) Configure account recovery mechanisms 
Q17. Which of the following best describes the “requesting party”?
    A) A user who requests access to a protected resource
    B) Another name for the authorization server
    C) The server that requests the resources
    D) Another name for the resource server
Q18. Which of the following best describes the “requesting owner”?
    A) A. A user who owns the resource
    B) B. An application that represents the user who owns the resource
    C) C. The server that hosts the resources
    D) A and B
Q19. Which of the following actions needs to be done at first to enable UMA 2.0?
    A) Configuring polices
    B) Send a request to the administrator
    C) Give a call to the requesting party
    D) Registering the resource
Q20. What is NOT a part an id_token?
    A) Signature
    B) Payload
    C) Footer
    D) Header
Q21. Wich OAuth scope is used to engage the OIDC protocol?
    A) Id_token
    B) Openid
    C) No special scope is required
    D) Oidc
Q22. Which grant type CANNOT be used to retrieve an id_token?
    A) Resource Owner Password Grant
    B) Authorization Code Grant
    C) Implicit Grant
    D) Client Credentials Grant
Q23. In the id_token, when is the claim that denotes to whom the token is intended for?
    A) Int
    B) Aud
    C) Usr
    D) iat
Q24. What are scopes used for in OIDC?
    A) To denote permissions to APIs
    B) To request for user claims
    C) Both of the above
    D) None of the above
Q25. What is the CORRECT statement about the security aspects with SAML message exchange?
    A) Integrity of the authentication and logout requests cannot be verified
    B) Client has to solely rely on the transport level security of the underlying transport
    C) Clients can only enable response signing for integrity, and rely on the transport to encrypt the messages.
    D) Responses can be encrypted,and integrity of the authentication/ logout requests can be verified via request signing.
Q26. Which is TRUE about the <Issuer> element in the SAML assertion?
    A) At least one element must be present in an assertion
    B) There can be multiple elements for an assertion 
    C) This contains the unique identifier of the identity provider
    D) This contains the unique identifier of the service provider
Q27.which statement is INCORRECT about SAML?
    A) SAML can be used to write scripts for validating security assertions 
    B) SAML can be used for the authentication process.
    C) SAML can be used to enable Single Sign-on.
    D) SAML can be used to exchange user identity information.
Q28. What is TRUE about <AudienceRestriction>?
    A) Assertion containing a bearer subject confirmation may contain an<AudienceRestriction> element including the service provider’s unique identifier
    B) Current WSO2 implementation does not not allow adding multiple audience restrictions.
    C) Id assertion does not contain a <AudienceRestriction> element, SP needs to rely on the IdP signature.
    D) Multiple <AudienceRestriction> elements may be included in a single assertion.
Q29. Which of the following SAML 2.0 specifications describe how SAML Assertions are exchanged via existing protocols?
    A) SMAL 2.0 Metadata
    B) SMAL 2.0 Core
    C) SMAL 2.0 Profiles
    D) SMAL 2.0 Bindings
Q30. Select an open standard which is used for seamless integration between applications and identity providers.
    A) Work Flows
    B) OpenID Connect
    C) Active Directory
    D) Federation
Q31. What is a centralized access management system?
    A) Each application in the system manages its own user-base
    B) Shares the common user base for all the applications.
    C) Have identities distributed across multiple environments
    D) Allows users to sign in to one application and gain access to all the other applications sharing the same session.
Q32. Which of the following is an issue commonly found in centralized applications systems?
    A) Integration issues 
    B) Heavy weight
    C) Poor user experience
    D) Maintenance issues
Q33. Which of the following explains an advantage of SSO?
    A) Reduces risk caused by bad password habits
    B) Makes the system simple by having a userstore connects to each application
    C) Allows using a common message format when communicating.
    D) Allows plugging in multiple identity providers to the existing system.
Q34. Which of the following statements best describes what   is?
    a Identity federation is a method of sharing user credentials between multiple trust domains
    b Identity federation is a method of sharing a person’s digital identity across multiple trust domains.
        1) A only
        2) A and b
        3) B only
        4) None of the above
Q35. Which statement is TRUE about configuring identity providers to perform identity federation is WSO2 Identity Server?
   a. Any SMAL supporting IdP can be configured as a federated IdPB
    b Any SCIM supporting IdP can be Configured as a federated IdP
    c Any OpenID Connect supported IdP can be configured as a Federated idP
        • A,B and C
        • B only
        • A and C only
        • C only
Q36. Which of the following protocols supported by WSO2 identity Server CANNOT be used for Identity Federation?
    b.a SMAL 
    b.b XACML
    b.c WS- Federation(Passive)
        • A and C only
        • B and C only
        • b only
        • B,c only 
Q37. What are the benefits of identity federation?
    a Ability to enable MFA without requiring changes to service providers
    b Ability to share user credentials between identity providers and services providers
    c Ability to introduce social identity providers applications with minimun effort
        • A,b and c
        • A,c only
        • A,b only
        • B,c only
Q38. Which of the following is an INCORRECT statement about Multi-Factor Authentication?
    A) Enabling Multi-factor authentication is a step towards compliance.
    B) Password are a must for Multi-factor Authentication.
    C) Multi-Factor Authentication guarantees improved usability
    D) Multi-factor Authentication adds an extra barrier between your personal information and the attackers.
Q39. What is an INCORRECT statement on X509Authentication?
    A) X509Authentication uses a client certificate instead of username and password
    B) In X509Authentication the CN of the certificate should be equal to the username of the user who holds the certificate
    C) X509Authentication is used in back-channel authentications
    D) X509 is a standard defining format of public key certificates
Q40. Which statement is FALSE about two-factor authentication in WSO2 Identity Server?
    A) We can implement a second factor for authentication using a custom authenticator
    B) Two- factor authentication can be supported by WSO2 Identity Server by configuring multiple authentication steps
    C) WSO2 Identity Server supports FIDO as the second factor in two-factor authentication
    D) Two-factor authentication is supported in WSO2 Identity Server using XMPP
Q41.Which form of authentication is the easiest to deploy but the most vulnerable?
    A) Smart Cards
    B) Security token
    C) Passowords
    D) Biometrics
Q42. Analitys based adaptive authentication is used to 
    A) To prompt additional authentication steps
    B) Identity abnormal patterns
    C) Identity users with risk profile
    D) All of the above
Q43. Which of the following use case CANNOT be considered as Adaptive Authentication?
    A) User is prompted to login with TOTP authentication if he is logging in from a device for the first time
    B) User is denied to login when he is trying to login from USA, when he had already logged in from India 30 mins before.
    C) User is prompted for SMS OTP authentication after the basic	 authentication is successful 
    D) User is prompted for FIDO hardware key authentication if he is logging in outside the corporate network
Q44. Which of the following statements about JIT provisioning is INCORRECT?
    A) JIT provisioning is used to create users in a local userstore using the data extracted from a federated IdP within the federated authentication flow.
    B) JIT provisioned accounts cannot have a passoword
    C) JIT provisioning is creating user is WSO2 Identity Server by calling SCIM API endpoints.
    D) User accounts can be created in the external systems using JIT provisioning.
Q45.which of the following is NOT a benefit of using user provisioning?
    A) Improved security
    B) Seamless Integration
    C) Saves time and money
    D) Nome of the above
Q46. Choose the option with the CORRECT order of steps for user provisioning in the identity life cycle.
    A) Provisioning, Authorization, Permissions, Self-Service, De-Provisioning
    B) Provisioning, Self-Service, Authorization, Permissions, De-Provisioning
    C) Authorization, Permissions, Provisioning, Self-Service, De-Provisioning
    D) Authorization, Provisioning, Permissions, Self-Service, De-Provisioning
Q47. What is the outbound provisioning mechanism supported by WSO2 Identity Server?
    A) A. Role-based provisioning
    B) B. Rule-based provisioning
    C) Both A & B
    D) None of the Above
Q48. Wich of the following in NOT a provisioning mechanism available is WSO2 Identity Server?
    A) Self- Registration
    B) Administrative Portal
    C) Federated authenticators
    D) SCIM 2.0 API
Q49. Which of the following in NOT a main structural element of an XACML policy?
    A) PIP- Policy Information Point
    B) PAP- Policy Automation Point
    C) PEP- Policy Enforcement Point
    D) PDP- Policy Decision Point
Q50.  Which of the following is mandatory to include inside the <Result> element?
    A) <Obligations>
    B) <Attributes>
    C) <Decision>
    D) <Status>

*************************************************************************************************************************

1. A privileged user is someone who:
   a) Follows up on the latest and greatest technology.
   b) C-Level management.
   c) Can access the system database.
   d) Has more authority and access to an information system than a general user.

2. I you want to allow users to self register via User Portal what is the step you need to follow?
    a) Enable account recovery in the resident identity provider
    b). Enable self user registration in the resident identity provider
    https://is.docs.wso2.com/en/latest/learn/self-registration/
    To enable self-registration, select the Enable Self User Registration check box.
    c) Enable Account Disabling in the resident identity provider
    d) Enable Account locking in the resident identity provider

3. Suppose you have connected a read-write secondary user store. Which of the following functions related to roles, is NOT allowed for your user store?
    a) View permissions assigned
    b) Assign users from the same user store
    c. Assign users from the primary user store
    https://docs.wso2.com/display/IS530/Configuring+Roles+and+Permissions
    d) Rename the role
5. Which statement about the self user registration feature is INCORRECT?
    a) The self registration feature can be enabled user store-wise.monica.lizarraga@chakray.com
    d) The internal / selfsignup role is assigned to the self-registered users by default.
6. Which statement about the account disabled feature in WSO2 Identity Server is INCORRECT?
    a) Disabled users cannot use the password recovery flow to enable the account.
    b) Privileged users can disable a user account.
    c) If a user enters the wrong credentials multiple times, the account will be disabled.
    d) Disabled users cannot login to the Identity Server.
7. Which of the following is NOT a grant type of the OAuth 2.0 protocol?
    a) Basic Authentication Grant
    b) Authorization Code Grant
    c) Resource Owner Password Credentials Grant
    d) Implicit Grant
8. What are the client application types that can be supported by OAuth 2.0 ?
    a) Single-page applications (SPA)
    b) Mobile applications
    c) Web applications
    d) All of the above
9. What is the real-world example that can be used to describe an OAuth 2.0 access token?
    a) The main key to your car
    b) ATM card PIN number
    c) Valet key of your car
    d) None of the above
10. How does the resource server validate the access token?
    a) Resource server should send another authorization request to the authorization server with the client key
    b) Resource server should send another authorization request to the authorization server with the access token
    c) Resource server should send another introspection request to the authorization server with the access token
    d) Both b and c are correct answers
11. What makes UMA different from Oauth?
    a) UMA is a newer, more advanced version of the OAuth.
    b) UMA is an extension of the OAuth protocol so there is no difference.
    c) UMA can authorize devices where OAuth can authorize only users.
    d) UMA can be used to give access to a different user other than the resource owner whereas OAuth cannot.
13. What is the permission ticket used for?
    a) It is a token used by the client application to authenticate it against the resource server.
    b) The user’s username and password is encrypted in this format.
    c) It is an intermediate token given by the authorization server to represent the resource server.
    d) It is an access token provided from the authorization server to authorize the user.
14. What is NOT a standard authorization flow in OIDC?
    a) Authorization Code
    b) Decoupled
    c) Implicit
    d) Hybrid
15. In the id_token what does the iat claim denote?
    a) The issued time of the token.
    b) The user identifier.
    c) The intended audience of the token.
    d) The issuer of the id_token.
16. Which claim of the id_token helps the application to identify the issuer of the id_token?
    a) iss
    b) sub
    c) idp
    d) aud
18. What are the types of SAML Assertions?
    a) Authentication, Attribute and Authorization
    b) Authentication and Attribute
    c) Attribute and Authorization
    d) Authentication and Authorization
19. What is true about the validity period of the SAML assertion issued by WSO2 IS?
    a) In the default configuration, an assertion is valid for 3600 seconds.
    b) In the default configuration, an assertion is valid for 300 seconds.
    c) IdP and SP need to be in the same time zone to validate the assertion validity period.
    d) Admin users can update the assertion validity period under resident identity provider configuration.
21. Organization XYZ consumes two applications; an HR application and an accounts application. To improve the end user experience, the organization does not need to prompt a login page for the user when they log in to the HR application if there is already a valid session of the same user from an initial login to the accounts application. Which of the following is the best model for this organization?
    a) Applications having their own user base
    b) Applications having a common user base
    c) Combine both the applications and develop a single application system.
    d) An identity provider system which is connected to the organization's userstore
22. What is an issue commonly found in centralized application systems?
    a) Heavy weight
    b) Maintenance issues
    c) Poor user experience
    d) Difficult to scale
25. Which of the following is NOT an ‘Ownership Factor’?
    a) Identity card
    b) Finger print
    c) Mobile phone
    d) ATM card
26. Which of these is a ‘Knowledge Factor’?
    a) Security question
    b) A PIN number
    c) User password
    d) All of the above
27. What is an example of using MFA?
    a) Login to a website with username/password and then FIDO.
    b) Withdrawing money from an ATM using the ATM card and the pin number.
    c) Login to a website with username/password and then EMAIL OTP
    d) All of the above.
28. Which of the following use cases CANNOT be considered as Adaptive Authentication?
    a) User is denied to login when he is trying to login from USA, when he had already logged in from India 30 mins before
    b) User is prompted to login with TOTP authentication if he is logging in from a device for the first time.
    c) User is prompted for FIDO hardware key authentication if he is logging in outside the corporate network
    d) User is prompted for SMS OTP authentication after the basic authentication is successful
29. What is NOT a benefit of user provisioning?
    a) Saves time and money
    b) Improved security
    c) Seamless integration
    d) None of the above
30. WSO2 Identity Server uses SCIM APIs for provisioning. Which is the correct SCIM2.0 API endpoint used in default WSO2 IS?
    a)https://localhost:9443/scim2/User
    b)https://localhost:9443/scim2.0/Users
    c)https://localhost:9443/scim2/Users
    d)https://localhost:9443/scim/Users
1. Assume you have a Microsoft Windows Server where a web application is hosted. A Windows Active Directory is used as the user store, and WSO2 Identity Server is used as the authentication server. If you need your Microsoft Windows users to log in to the application, without exposing their passwords, which authentication mechanism could you use with WSO2 Identity Server? 
    a) WS-Federation
    b) SAML2 SSO
    c) IWA 
    d) OIDC
2. What is the INCORRECT statement about token revocation in WSO2 Identity Server?
    a) It is possible to revoke either refresh token or access token.
    b) There is only one REST endpoint to do the token revocation.
    c) You cannot remove all the access tokens for a given application at once.
    d) Revoke endpoint is /oauth2/revoke.
3. There are two web applications:
App1 supports SAML2 SSO web browser based authentication.
App2 supports OAuth/OpenID Connect.
A user will be automatically logged into App2 when the user has been already logged into App1. How is this supported by the WSO2 Identity Server?
    a) This can be supported because WSO2 Identity Server creates only a single session for the user agent.
    b) This can be supported by the authorization code grant type used in SAML2.
    c) This can be supported because SAML2 and OAuth2 use the same authentication protocol.
    d) This can be supported because the SAML2 token can be used as the OAuth2 bearer token
4. ABC Company needs to have their company logo in the Identity Server SSO login page. How can they achieve this?
    a) You cannot modify the SSO login page. The required logo must be added in the web application, which will have SSO with Identity Server.
    b) Edit the login.jsp in the SAML SSO web application.
    c) Edit the login.jsp in the authenticationendpoint web application.
    d) None of the above.
5. Which statement correctly explains the Request-Path Authenticator in WSO2 Identity Server?
    a) The request-path authenticators always require the user credentials to be present in the initial authentication request itself.
    b) There has to be only one request-path authenticator registered with the service provider corresponding to an authentication request.
    c) Request-path authenticator can be a federated authenticator.
    d) No more authentication can be done after the request-path authentication
6. Select the mandatory parameter in an IdP initiated SLO (Single Log-out) request
    a) slo
    b) spEntityID
    c) returnTo
    d) spIssuerID
7. When you configure inbound provisioning via the Management Console of WSO2 Identity Server, you can enable the dumb mode for inbound provisioning by selecting the relevant checkbox. Which of the following happens when you enable the dumb mode for inbound provisioning?
    a) Users/Groups are provisioned to WSO2 Identity Server, but not provisioned to external applications.
    b) Users/Groups are provisioned to both WSO2 Identity Server and external applications, but not persisted in WSO2 Identity Server.
    c) Users/Groups are not provisioned to either WSO2 Identity Server or external applications.
    d) Users/Groups are not persisted in WSO2 Identity Server, but are provisioned to external applications.
8. Which of the following is true about the user-mgt.xml file in WSO2 Identity Server?
    a) Hot deployment can be enabled for user-mgt.xml file.
    b) All secondary user store configurations in the <IS_HOME>/repository/deployment/server/userstores directory have a reference to the user-mgt.xml file to keep track of the primary user store.
    c) Primary user stores are configured in the user-mgt.xml file.
    d) The primary user store configuration file of a tenant is created in the <IS_HOME>/repository/tenants/<TenantId>/userstores directory.
9. What is Just-in-Time provisioning in WSO2 Identity Server?
    a) Provisioning a user to WSO2 Identity Server when the user is authenticated by a federated identity provider.
    b) Provisioning users/groups from WSO2 Identity Server to external applications via a provisioning request.
    c) Provisioning users/groups to WSO2 Identity Server user stores from an external application via a provisioning request.
    d) Provisioning a user to an external application when the user is authenticated by a federated identity provider.
10. Assume the following:
A customer is using WSO2 Identity Server as a federation hub.
End users can be authenticated using different IdPs.
The customer wants to persist the users in a secondary user store that is connected to WSO2 Identity Server.
Which of the following is the best approach to achieve this?
    a) Enable outbound provisioning for the federated identity provider by a conguring tenant and user store domains.
    b) Enable JIT provisioning for the federated identity provider.
    c) Implement a custom local authenticator and configure it as the last step for all federation ows.
    d) Customize the current authenticator to persist the user based on the tenant domain.
11. Which of the following is incorrect about user and role management in WSO2 Identity Server?
    a) Roles in a secondary user store can be assigned to users in the primary user store.
    b) A primary role that belongs to a tenant is not visible to another tenant.
    c) The set of permissions owned by a user is determined by the roles assigned to the user.
    d) It is possible to search users based on user attributes (claims).
12. Which of the following is correct about XACML-related congurations and deployment in WSO2 Identity Server?
    a) WSO2 Identity Server can act as an XACML PDP, PAP, and PEP in production deployment.
    b) Attribute cache and decision cache must be disabled when WSO2 Identity Server is clustered.
    c) Attribute cache and decision cache are not useful if the policy cache is disabled in the system.
    d) Attribute cache, decision cache, and policy cache can be cleared from the Management Console UI.
13. Assume you want to set up WSO2 Identity Server so that when an internal role is added, that role must be approved by an admin user before that user is permitted to perform any operation. Which of these statements about this functionality is true?
    a) Supported out-of-the-box, can be done by changing some configurations.
    b) Supported out-of-the-box, can be done without changing any configurations.
    c) Not supported out-of-the-box, but can be implemented as an extension.
    d) Cannot be implemented using WSO2 Identity Server.
14. In which order should these steps be performed when engaging the adduser operation to your WSO2 IS deployment with a workow using an external BPS server?
    |. Create a workow engine that points to the external BPS.
    II. Create a workow definition using the Add Workow Denition operation.
    III. Engage the adduser operation to workow using the Add Workow Engagement operation.
        a) I, II, III
        b) I, III, II
        c) III, I, II
        d) II, I, III
15. How do you disable prompting for consent in an authentication flow?
    a) It is not possible to disable prompting of consent in WSO2 Identity Server once it is enabled.
    b) In the identity.xml le, set the <EnableSSOConsentManagement> property to false.
    c) You can congure this in the service provider conguration of the management console.
    d) In the application-authentication.xml le, set the <EnableSSOConsentManagement> property to false.
1. Which of the following statements describe the purpose of inbound authenticators in WSO2 Identity Server?
    a) It is used to authenticate a user with locally available credent
    b) It is used to identify and process incoming protocol-specific authentication requests and build protocol-specific responses and send to service providers.
    c) It is used to identify protocol-specific responses that can be sent to identity providers.
    d) It is used to provision users to a user store.
2. What is the correct statement about the issuer of the id_token that is generated in OpenID Connect?
    a) Issuer is generated using the WSO2 Identity Server hostname.
    b) Issuer cannot be configured.
    c) It is set to /openid endpoint by default.
    d) None of the above.
3. What is not required from the client when dynamically registering a new client at the authorization server using the DCR specification in OpenIDConnect?
    a) Client sends an HTTP POST message to the client registration endpoint.
    b) Client discovers the client registration endpoint.
    c) The client generates a unique client ID and client secret.
    d) The HTTP POST message sent to the client registration endpoint contains client metadata parameters that the client chooses to specify for itself during the registration.
4. How can you get the tenant domain with the username as the subject identifier in tenant mode?
    a) Can be configured for each service provider in Local & Outbound Authentication Configuration.
    b) This can be configured globally in identity.xml file.
    c) It is enabled by default.
    d) This cannot be configured. The subject identifier will always have the tenant domain and user store domain.
6. Which statement is INCORRECT about service provider initiated SSO and identity provider initiated SSO in WSO2 Identity Server?
    a) WSO2 Identity Server supports service provider initiated SSO.
    b) WSO2 Identity Server supports service provider initiated SSO and identity provider initiated SSO.
    c) Identity provider initiated SSO uses the service provider’s issuer ID in its request.
    d) WSO2 Identity Server only supports identity provider initiated SSO.
7. Which of the following is correct about SCIM support in WSO2 Identity Server?
    a) WSO2 Identity Server only supports outbound provisioning via SCIM.
    b) WSO2 Identity Server only supports inbound provisioning via SCIM.
    c) WSO2 Identity Server supports both inbound and outbound provisioning via SCIM.
    d) WSO2 Identity Server does not support SCIM.
8. Which of the following is true about Just-in-Time (JIT) provisioning?
    a) Just-in-Time provisioning gets triggered when the Identity Server receives a successful authentication response from the external identity provider.
    b) JIT provisioning is configured against service providers.
    c) In JIT provisioning, a user is always provisioned to the primary user store.
    d) In JIT provisioning, the authentication flow is always blocked until the provisioning is completed.
9. What is inbound provisioning in WSO2 Identity Server?
    a) Provisioning users/groups to the Identity Server from an external application via a provisioning request.
    b) Provisioning users/groups from WSO2 Identity Server to external applications via a provisioning request.
    c) Provisioning a user to WSO2 Identity Server when the user is authenticated by a federated IdP.
    d) Provisioning a user to an external application when the user is authenticated by a federated IdP.
10. In a customer environment, assume that the identity admin needs to provision all the employees to Google Apps at the time they join the company, and provision only the employees belonging to the sales-team to Salesforce. Which of the following procedures should you follow to achieve this?
    a) Configure Salesforce and Google Apps as provisioning identity providers in WSO2 Identity Server.
    b) In the Salesforce Provisioning Identity Provider Configuration, under the Role Configuration, set sales-team as the role for outbound provisioning.
    c) In the Resident Service Provider configuration, set both Salesforce and Google Apps as provisioning identity providers for outbound provisioning.
    d) All of the above.
11. Which of the following XACML specifications are currently supported in WSO2 Identity Server?
    I) XACML 3.0 core specification
    II) XACML Admin and Delegation Profile
    III) JSON Profile of XACML
    IV) XACML REST Profile
        a) I, III, IV
        b) I, II, III
        c) I, II, IV
        d) II, III, IV
12. You need to set up WSO2 Identity Server so that when a user is added to a given secondary user store, that user must be approved by an admin user before that user is permitted to perform any operation. Which of these statements about this functionality is true?
    a) Supported out-of-the-box and can be done by changing some file-based configurations.
    b) Supported out-of-the-box and can be done without changing any file-based configurations.
    c) Not supported out-of-the-box, but can be implemented as an extension.
    d) Cannot be implemented using Identity Server.
13. Which of the following is incorrect about user and role management in WSO2 Identity Server?
    a) A primary role that belongs to a tenant is not visible to another tenant.
    b) The set of permissions owned by a user is determined by the roles assigned to the user.
    c) Roles in a secondary user store can be assigned to users in the primary user store.
    d) It is possible to search users based on user attributes (claims).
14. Assume the following:
A customer is using WSO2 Identity Server as a federation hub.
End users can be authenticated using different IdPs.
The customer wants to persist the users in a secondary user store that is connected to WSO2 Identity Server.
Which of the following is the best approach to achieve this?
    a) Enable outbound provisioning for the federated identity provider by a conguring tenant and user store domains.
    b) Enable JIT provisioning for the federated identity provider.
    c) Implement a custom local authenticator and configure it as the last step for all federation ows.
    d) Customize the current authenticator to persist the user based on the tenant domain.
15. How do you disable prompting for consent in an authentication flow?
    a) It is not possible to disable prompting of consent in WSO2 Identity Server once it is enabled.
    b) In the identity.xml le, set the <EnableSSOConsentManagement> property to false.
    c) You can congure this in the service provider conguration of the management console.
    d) In the application-authentication.xml le, set the <EnableSSOConsentManagement> property to false.

IDENTITY ADVANCED
1. If you want a service provider to be accessible by all the tenants, which approach from the following would help to achieve it? 
    a) Update the permission of the role(which is created for the service provider) for /permission/admin.
    b) Creating a Service Provider in super tenant mode will allow by default to access by all the tenants.
    c) Configure a file-based service provider.
    d) Cannot achieve this using WSO2 Identity Server.
2. Assume that a user gets the No Access-Control-Allow-Origin header on a requested resource when invoking an endpoint in OAuth2 web application from a JavaScript of a webapp that is located in a different domain than the identity server domain. Which of the following is the best way to resolve this? 
    a) Enable the CORS (Cross-Origin Resource Sharing) filter for the OAuth webapp by adding the filter configuration to web.xml.
    b) Customize the OpenIDConnectUserEndpoint.java application so that it allows to invoke the userinfo endpoint from any domain.
    c) Disable CORS (Cross-Origin Resource Sharing) from the web browser.
    d) Pass * as a header with the request that is used to invoke the endpoint.
3. Consider a scenario where you need to pass a static parameter (param name "customparam" and value is "customvalue") to a third-party identity server, which is configured in the WSO2 identity Server as a federated identity provider (SAML2). The WSO2 Identity Server has a feature to add this type of static value in the SAML2 outbound connector as the additional query parameter. What is correct pattern required in the "additional query parameter"? 
    a) {customparam}=customvalue
    b) customparam={customvalue}
    c) customparam=${customvalue}
    d) customparam=customvalue
4. Consider a scenario where an internal web portal is used to monitor applications deployed in AWS. WSO2 Identity Server is used to login to this portal and now there is a requirement to configure SSO for this client portal with AWS admin console. What is the statement that does not belong to the solution?
    a) Add a new Identity Provider to the WSO2 Identity Server to connect AWS as a federated identity provider.
    b) Write a custom inbound authenticator to validate the request to check the redirection of AWS to WSO2 Identity Server.
    c) Configure the AWS application to make the WSO2 Identity Server as the identity provider.
    d) Point the internal user store to the AWS and make the application login from either the AWS login or the WSO2 Identity Server login.
5. Which statement is true about returnTo parameter in IdP initiated SLO request?
    a) This is a mandatory parameter.
    b) If this parameter is present in the request, then the spEntityID parameter must also be present.
    c) The value of returnTo that comes with the request may not match with one of the assertion consumer URLs or returnTo URLs of the service provider.
    d) This should be the endpoint URL that sends the logout request.
6. Consider a scenario where the user credentials are maintained in a single user store, while user attributes are maintained in multiple sources. When the user logs into the system via any SSO protocol, the response needs to be built using user attributes coming from multiple internal sources. How can this be done with WSO2 Identity Server?
    a) Create a custom user store manager as the user store manager corresponding to the primary user store. This custom user store manager must be aware of all the attribute stores in the system.
    b) This can be achieved by writing a custom authenticator.
    c) This can be achieved by writing a provisioning handler.
    d) This cannot be achieved in WSO2 Identity Server since there is no way to differentiate the attribute stores from the credentials store.
7. You have a read-only LDAP user store and need to do identity management operations (e.g., account locking). What is the most appropriate way to store your identity claims related to these operations?
    a) Implement a custom listener (UserOperationEventListener) to handle identity claims and store them in a custom place.
    b) Enable Identity.Managed.Internally property in the identity-mgt.properties file.
    c) Implement a custom user store manager to persist identity claims in a different store.
    d) Enable the JDBC-based identity data store in the identity-mgt.properties file.
8. Each service provider in WSO2 Identity Server should be able to specify from which user store it accepts users to get authenticated. How can it be achieved?
    a) Create a custom user operation listener to enforce the user store domain requirement when authenticating.
    b) Create a custom user store manager to enforce the user store domain requirement when authenticating.
    c) Build a XACML connector and create XACML policies for each service provider to enforce the user store domain requirement.
    d) Specify the user stores that are allowed in the service provider configurations of the WSO2 Identity Server.
9. Consider a scenario where all the user operations have to be approved by administrators in a hierarchical manner. For example, when an employee joins the company, it has to be approved by a set of administrators, while when the same employee is assigned to the marketing team, it must be approved by a different set of administrators. How can you achieve this multi-layer approval using WSO2 Identity Server?
    a) Create a workflow that has a defined criteria for its execution and with multiple steps, wherein each step it is specified who should provide the approval.
    b) Create a custom user operation event listener by implementing the UserOperationEventListener interface and handle the approval process when each user operation takes place.
    c) This feature is supported in the product by default and can be done by changing some filebased configurations.
    d) This cannot be achieved using WSO2 Identity Server.
10) When removing references to a deleted user's identity, what are the characters that a valid pseudonym can contain?
    a) Uppercase characters, lowercase characters, and numbers
    b) Uppercase characters, numbers, and special characters [! , @ , #]
    c) Only uppercase and lowercase characters from A-Z
    d) This depends on the configuration in the identity.xml file
1. What is correct statement about IDP-initiated SSO?
    a) Client application should build the SAML assertion and pass with the EntityID to the WSO2 Identity Server to initiate the IDP-initiated SSO.
    b) Client application should pass the EntityID only to the WSO2 Identity Server to initiate the IDP-initiated SSO.
    c) It is mandatory to build a SAML assertion in the client side for all the SAML SSO flows.
    d) It never generates SAML assertion in IDP initiated SSO flow.
2. Which statement is correct about the LDAP user store configuration?
    a) You can define multiple UserSearchBase properties in the configuration.
    b) The UserNameListFilter property in the configuration must contain the uid.
    c) The GroupSearchBase property is a mandatory property to be specified in the configuration.
    d) The PasswordHashMethod property must be configured as PLAIN_TEXT.
3. Which of the following is correct about entitlement service in WSO2 Identity Server?
    a) WSO2 Identity Server does not support decision caching as it cannot manage policy/attribute updates.
    b) WSO2 Identity Server does not support policy versioning.
    c) WSO2 Identity Server supports publishing multiple policies to external PDPs.
    d) WSO2 Identity Server supports REST API for policy publishing.
4. There are several service providers created in the WSO2 Identity Server by user A. The admin is asking user B to change some configurations in some service providers. However, user B is complaining that he cannot see any of these service providers under the service provider list. What could be the correct explanation for that?
    a) Only admin users can see the service provider list in the admin console.
    b) All of these service providers are disabled.
    c) User B is not assigned the application’s domain role permission corresponding to each service provider application.
    d) The admin user has not assigned user B to an internal role.
5. What is a possible method of bulk user update in WSO2 Identity Server?
    a)Through bulk CSV upload
    b)Through WSO2 Identity Server console app
    c)Through a patch SCIM2/Users Patch operation
    d)Through SCIM2 Bulk user Rest API
7. suppose you have connected a read-write secondary user store. Whats is the functionality NOT allowed for roles of your user store?
    a)Assign users from the same user store
    b)Assign users from the primary user store
    c)View permissions assgined
    d)Rename the role
8. Which of the following statements about the self user registration feature is INCORRECT?
    a)The self registration feature can be enabled user store-wise
    b)The interna{/ selfsignup role is assgined to the self-registered users by default
    c)The self registration feature can be enabled tenant-wise
    d)WSO2 identity Server supports REST APIs for self user registration
9. Which of th following statements is TRUE about the password pattern configuration in WSO2 Identity Server
    a)Password patterns can be configured both user store-wise and tenant-wise
    b)Password patterns can be configured tenant-wise only
    c)Password patterns can be configured user store-wise only
    d)Privilieged users can bypass the password pattern validation
Q8: Which of the following statements about the password history feature in WSO2 Identity Server is INCORRECT?
    A) The password history feature is enforced when updating the credentials of a user.
    B) The password history feature is enforced when adding a user.
    C) The password history feature can be enabled tenant-wise.
    D) The password history feature is not enforced for privileged users.
Q10: After you register an OAuth application, what is the simplest way to create a new client secret?
    A) Delete the current application and create a new application
    B) Use the revoke feature
    C) Use the "Regenerate Secret" feature OCreate a new application with the same application name
Q11: How does the resource server validate the access token?
    A. Resource server should send an authorization request to the authorization server with the client key
    B. Resource server should send an authorization request to the authorization server with the access token
    C. Resource server should send an introspection request to the authorization server with the access token OBoth B and C are correct answers
Q13: Arrange the following OAuth tokens in the lifetime of increasing order.
    1. Authorization code
    2. Access token
    3. Refresh token
        A) 3,1 and 2
        B) 1,3 and 2
        C) 1,2 and 3
        D) 3,2 and 1
Q14: In the tutorial, when you access the application, what was the authorization header type used to send the access token?
    A) Mutual
    B) earer
    C) Digest
    D) Basic
Q16: What makes UMA different from OAuth?
    A) UMA is an extension of the OAuth protocol so there is no difference.
    B) UMA is a newer, more advanced version of the OAuth. OUMA can authorize devices where OAuth can authorize only users.
    C) UMA can be used to give access to a different user other than the resource owner whereas OAuth cannot.
Q18:Which of the following roles is a UMA 2.0 role?
    A) Resource Owner
    B) Authorization Server
    C) Requesting Party
    D) All of the above
Q19:Which of the following best describes the "resource owner"?
    A) A user who owns the resource.
    B) An application that represents the user who owns the resource.
    C) The server that hosts the resources.
    D) A and B.
Q20:What is NOT a part of an id_token?
    A) header
    B) payload
    C) signature
    D) footer
Q22:In the id_token what does the iat claim denote?
    A) The issuer of the id_token
    B) The intended audience of the token
    C) The user identifier
    D) The issued time of the token
Q23: Which part of the id_token contains the information required to validate the signature of the token?
    A) sig claim in the payload
    B) lt can be found by decoding the base64 encoded signature
    C) Header part of the token
    D) iss claim in the payload
Q24:Which claim of the id_token helps the application to identify the issuer of the id_token?
    A) sub
    B) idp
    C) Caud
    D) iss
Q25:What are the types of SAML Assertions?
    A) Authentication, Attribute and Authorization
    B) Authentication and Authorization.
    C) Authentication and Attribute
    D) Attribute and Authorization
Q31: Organization XYZ consumes two applications; an HR application and an accounts application. To improve the end user experience, the organization does not need to prompt a login page for the user when they log in to the HR application if there is already a valid session of the same user from an initial login to the accounts application. Which of the following is the best model for this organization?
    A) An identity provider system which is connected to the organization's userstore. 
    B) Combine both the applications and develop a single application system.
    C) Applications having their own user base
    D) CApplications having a common user base
Q33: Which of the following is NOT an advantage of using an open standard for SSO?
    A) Pre-defined message formats between the identity provider and service provider communications 
    B) Minimizes development overhead
    C) Applications implementing proprietary communication protocols can be easily integrated with an identity provider
    D) Reduces complexity in integrating new applications with an identity provider
Q35: Which of the following statements are CORRECT regarding identity federation?
    A. Identity federation increases risk of credential leakage as user credentials are shared between identity providers and service providers
    B. Identity federation enables single sign-on for applications
    C. Identity federation allows integration of third party identity providers through standard protocols
        1. A, B and C
        2. B only
        3. B and C only
        4. A and B only
Q42:What is the CORRECT statement about adaptive authentication?
    A) lt's just a marketing term for the traditional authentication
    B) lt's the same as multi factor authentication
    C) lt gives an extra level of security
    D) lt enforces to use a knowledge factor
Q43: Which scenario explains LOA (Level of Assurance) based adaptive authentication accurately?
    A) When a user inquires about the account balance from a banking application it prompts a single factor to authenticate, but when doing a money transaction it prompts multiple factors to prove identity
    B) When a user tries to login to two different applications the system prompts the same type of authentication mechanism to prove the user's identity. 
    C) When login to an enterprise application user A with a higher permission level will get a single factor to authenticate while a user with lower permission level will get multiple factors 
    D) None of the above explains LOA properly
Q44:What is inbound provisioning?
    A) Provisioning a user from an external application when the user is authenticated by a federated IdP.
    B) Provisioning users and groups from external applications
    C) Provisioning users and groups into external applications.
    D) Provisioning a user to an external application when the user is authenticated by a federated IdP
Q45:Which of the following is NOT a provisioning mechanism available in WSO2 Identity Server?
    A) Self-Registration
    B) Administrative Portal
    C) SCIM 2.0 API
    D) Federated authenticators
Q46: Consider the following scenario. You are building an online grocery delivery system. You need consumers to come and register themselves in the system in order to purchase goods. You want to enable customers to login using their Google accounts. In order to contact the customer later when delivering the purchased goods, you need to save his/her details in WSO2 Identity Server. How can you achieve this using WSO2 Identity Server?
    A) Configure Google as a federated identity provider in WSO2 Identity Server and enable JIT provisioning, so that sign-up with google is enabled.
    B) set-up a help desk/call center to collect users email addresses and other information and create an account for him/her. 
    C) Enable self-registration and ask users to provide the email address as the username when registering themselves. 
    D) None of the above
Q48: Which of the following statements defines user provisioning?
    A) The process of creating and maintaining digital identities in a system and assigning appropriate privileges to them.
    B) The process of verifying the identity of a user. 
    C) Process of allowing members of a system to use their credentials to access a resource in another system.
    D) None of the above
Q49: Which of the following is NOT a possible output to receive after evaluating a XACML policy?
    A) lndeterminate
    B) Intermittent
    C) NotApplicable
    D) Deny
Q50: What is the extension that needs to be written to evalute a XACML policy from the permissions retrieved by calling an API?
    A) Implement a custom userstore
    B) Implement a custiom PEP
    C) Implement a custom PDP
    D) Implement a custom PIP

    Prueba Luis