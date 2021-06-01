# List of Keycloak CVEs

[nvd.nist.gov](https://nvd.nist.gov/vuln/search/results?form_type=Basic&results_type=overview&query=keycloak&search_type=all)

# Private JIRA Issues

## 13.0.1
[Changelog](https://github.com/keycloak/keycloak/compare/13.0.0...13.0.1)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |
| KEYCLOAK-17495 | [KEYCLOAK-17495 Do not include principal in the reference to broker sessionId](https://github.com/keycloak/keycloak/commit/f014299e7c781dff2b492b81bc81adcf717bd530) | https://issues.redhat.com/browse/KEYCLOAK-17495 |

## 13.0.0
[Changelog](https://github.com/keycloak/keycloak/compare/12.0.4...13.0.0)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |
| KEYCLOAK-17998 | [[KEYCLOAK-17998] Upgrade PostgreSQL JDBC Driver](https://github.com/keycloak/keycloak/commit/f1bdfaa642fce03deebd1da3b5e5b42ac9653da0) | https://issues.redhat.com/browse/KEYCLOAK-17998 |
| KEYCLOAK-15170 | [KEYCLOAK-15170 Reset password link is not invalidated if email address is changed](https://github.com/keycloak/keycloak/commit/57fca2a34f6feb61292538c4fa3ee0bb69b51263) | https://issues.redhat.com/browse/KEYCLOAK-15170 |
| KEYCLOAK-17989 | [[KEYCLOAK-17989] Update Jetty to the latest version](https://github.com/keycloak/keycloak/commit/4f089120715990532731ee617ce55ee36eba5a5f) | https://issues.redhat.com/browse/KEYCLOAK-17989 |
| KEYCLOAK-17734 | [KEYCLOAK-17734 LifespanAdapterTest fails due to header check](https://github.com/keycloak/keycloak/commit/c2c1b482eab192c65223ba147c4fc2cab2d42c60) | https://issues.redhat.com/browse/KEYCLOAK-17734 |
| KEYCLOAK-17835 | [KEYCLOAK-17835 Account Permanent Lockout and login error messages](https://github.com/keycloak/keycloak/commit/315b9e3c2970145e03dfaaddc364d588c9ebf060) | https://issues.redhat.com/browse/KEYCLOAK-17835 |
| KEYCLOAK-17873 | [KEYCLOAK-17873 FuseUtils - No bundles found for Fuse 7.x](https://github.com/keycloak/keycloak/commit/5c4753ef2030d50eca96a59a08273adc1d1a5d02) | https://issues.redhat.com/browse/KEYCLOAK-17873 |
| KEYCLOAK-17457 | [KEYCLOAK-17457 Failed OfflineServletsAdapterTest](https://github.com/keycloak/keycloak/commit/ca019c36e88a01eff31f11ffc54e828467236f2a) | https://issues.redhat.com/browse/KEYCLOAK-17457 |
| KEYCLOAK-16913 | [KEYCLOAK-16913 Fix failed FuseAdapterTest](https://github.com/keycloak/keycloak/commit/b237c503ba744ac2caf2f7e40879af2948d9c554) | https://issues.redhat.com/browse/KEYCLOAK-16913 |
| KEYCLOAK-17311 | [KEYCLOAK-17311 - exclude for Remote testsuite](https://github.com/keycloak/keycloak/commit/e0d660d81568dea4716c9700494f70191ac3416d) | https://issues.redhat.com/browse/KEYCLOAK-17311 |
| KEYCLOAK-17302 | [KEYCLOAK-17302 - exclude for Remote testsuite](https://github.com/keycloak/keycloak/commit/17b19b2e3612d36fbf2d5a30112c400a982a5cb7) | https://issues.redhat.com/browse/KEYCLOAK-17302 |
| KEYCLOAK-17310. | [KEYCLOAK-17310. Disabled test in remote environment. (#7898)](https://github.com/keycloak/keycloak/commit/5f551e018d672b93f2570b8e5f32cf04448cca8d) | https://issues.redhat.com/browse/KEYCLOAK-17310. |
| KEYCLOAK-17215 | [KEYCLOAK-17215 Slowness issue while hitting /auth/admin/realms/$REALM/clients?viewableOnly=true after DELETE a role](https://github.com/keycloak/keycloak/commit/0a0caa07d6b22b1a67d7eb7607e1587f75db9578) | https://issues.redhat.com/browse/KEYCLOAK-17215 |
| KEYCLOAK-17100 | [[KEYCLOAK-17100] Testsuite Wildfly initialization error on Windows [KEYCLOAK-17392] Java CLASSPATH is wrongly parsed on Windows](https://github.com/keycloak/keycloak/commit/5fac80b05e7d930b686083c9f53aa49f892bbbfe) | https://issues.redhat.com/browse/KEYCLOAK-17100 |
| KEYCLOAK-16890 | [KEYCLOAK-16890: Stored XSS attack on new acct console (#7867)](https://github.com/keycloak/keycloak/commit/717d9515fa131e3d8c8936e41b2e52270fdec976) | https://issues.redhat.com/browse/KEYCLOAK-16890 |
| KEYCLOAK-17033 | [KEYCLOAK-17033: Reflected XSS attack with referrer in new account console](https://github.com/keycloak/keycloak/commit/3b80eee5bfdf2b80c47465c0f2eaf70074808741) | https://issues.redhat.com/browse/KEYCLOAK-17033 |
| KEYCLOAK-16356 | [KEYCLOAK-16356 update JUnit to the latest version](https://github.com/keycloak/keycloak/commit/cd44b99eb90bc0d64f299d04bcbf1bb7c5fe9db0) | https://issues.redhat.com/browse/KEYCLOAK-16356 |
| KEYCLOAK-16212 | [KEYCLOAK-16212 - Exclude Remote execution for the LDAPVaultCredentialsTest, fixed broken exclude Remote execution for the LDAPUserLoginTest.](https://github.com/keycloak/keycloak/commit/b3ea6f74beb2bb0fa625e0cd438ce72bb97ff465) | https://issues.redhat.com/browse/KEYCLOAK-16212 |
| KEYCLOAK-17301 | [KEYCLOAK-17301 - fix -> added org.infinispan.commons module into jboss-deployment-structure.xml](https://github.com/keycloak/keycloak/commit/ef57714eaa1e2b275962ed3e9a2244d963a38497) | https://issues.redhat.com/browse/KEYCLOAK-17301 |
| KEYCLOAK-14913 | [[KEYCLOAK-14913] GitLab Identity Provider shouldn't request for 'api' scope](https://github.com/keycloak/keycloak/commit/852593310f8933e5765225001f8b7414efdb097b) | https://issues.redhat.com/browse/KEYCLOAK-14913 |
| KEYCLOAK-14766 | [KEYCLOAK-14766 - Removed setting default password for LDAPRule configuration](https://github.com/keycloak/keycloak/commit/8203c4451effd67b48af691e40c3df16829ac700) | https://issues.redhat.com/browse/KEYCLOAK-14766 |
| KEYCLOAK-14483 | [KEYCLOAK-14483 Broker state param fix](https://github.com/keycloak/keycloak/commit/41dc94fead4c20560e0dd96c3efbd7bd10a484b6) | https://issues.redhat.com/browse/KEYCLOAK-14483 |
| KEYCLOAK-17125 | [KEYCLOAK-17125 Update Arquillian drone version to 2.5.2](https://github.com/keycloak/keycloak/commit/52a939f61a70b40751b058f125828a99e6096223) | https://issues.redhat.com/browse/KEYCLOAK-17125 |
| KEYCLOAK-15239 | [KEYCLOAK-15239 Reset Password Success Message not shown when Kerberos is Enabled](https://github.com/keycloak/keycloak/commit/6f409d088a97095fd78f38eff7dc01ed29072cdc) | https://issues.redhat.com/browse/KEYCLOAK-15239 |
| KEYCLOAK-16517 | [KEYCLOAK-16517 Make sure that just real clients with standardFlow or implicitFlow enabled are considered for redirectUri during logout](https://github.com/keycloak/keycloak/commit/ed8d5a257f98b1f0275909b7dc1b97e79b288bcb) | https://issues.redhat.com/browse/KEYCLOAK-16517 |
| KEYCLOAK-15849 | [KEYCLOAK-15849 : auth-remote-server exclude -> removed duplicated annotation, fixed @Test(timeout) bug -> replaced by lambda expression.](https://github.com/keycloak/keycloak/commit/4a2830bc2e90240695b78618dd570beccaa808ce) | https://issues.redhat.com/browse/KEYCLOAK-15849 |
| KEYCLOAK-16521 | [[KEYCLOAK-16521] - Fixing secret for non-confidential clients](https://github.com/keycloak/keycloak/commit/9356843c6c3d7097d010b3bb6f91e25fcaba378c) | https://issues.redhat.com/browse/KEYCLOAK-16521 |
| KEYCLOAK-16329 | [KEYCLOAK-16329 CVE-2020-1695 resteasy: Improper validation of response header](https://github.com/keycloak/keycloak/commit/bfaab76b5f36c403ab5106a028379128b0b0d022) | https://issues.redhat.com/browse/KEYCLOAK-16329 |
| KEYCLOAK-14366 | [[KEYCLOAK-14366] - Missing check for iss claim in JWT validation on Client Authentication (Token Endpoint)](https://github.com/keycloak/keycloak/commit/f6c3ec5d9ef9b01e1c40d6f5f25ad017f2f0d877) | https://issues.redhat.com/browse/KEYCLOAK-14366 |
| KEYCLOAK-16939 | [KEYCLOAK-16939 : Performance testsuite -> new gc charts, sar profiles, new datasets, crossdc profile](https://github.com/keycloak/keycloak/commit/54c5b1514f0611056f38053081d094cf5e5fd08a) | https://issues.redhat.com/browse/KEYCLOAK-16939 |
| KEYCLOAK-16468 | [KEYCLOAK-16468 Support for deny list of metadata attributes not updateable by account REST and admin REST](https://github.com/keycloak/keycloak/commit/dae4a3eaf26590b8d441b8e4bec3b700ee303b72) | https://issues.redhat.com/browse/KEYCLOAK-16468 |
| KEYCLOAK-14019 | [KEYCLOAK-14019 Improvements for request_uri parameter](https://github.com/keycloak/keycloak/commit/eac3329d225a58b43b0bc97300423596063b33c1) | https://issues.redhat.com/browse/KEYCLOAK-14019 |
| KEYCLOAK-14856 | [KEYCLOAK-14856 fix migration, add ssl for migration server](https://github.com/keycloak/keycloak/commit/dfa27b9f0f980f7a5753e1a3cfd259462704e802) | https://issues.redhat.com/browse/KEYCLOAK-14856 |
| KEYCLOAK-15390 | [KEYCLOAK-15390 fix ClientMappersOIDCTest](https://github.com/keycloak/keycloak/commit/2ed8ed2543716e5d51acf2ef1c16c6ffd0f8d80b | https://issues.redhat.com/browse/KEYCLOAK-15390 |

## 12.0.4
[Changelog](https://github.com/keycloak/keycloak/compare/12.0.3...12.0.4)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |

## 12.0.3
[Changelog](https://github.com/keycloak/keycloak/compare/12.0.2...12.0.3)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |
| KEYCLOAK-16890 | [KEYCLOAK-16890: Stored XSS attack on new acct console](https://github.com/keycloak/keycloak/commit/87422b77aee787c6c55ca22fde31c60bcfe4c7f7) | https://issues.redhat.com/browse/KEYCLOAK-16890 |
| KEYCLOAK-17033 | [KEYCLOAK-17033: Reflected XSS attack with referrer in new account console](https://github.com/keycloak/keycloak/commit/010d7eb0ce9e3b5ee8131a7a0d7400b21deeae50) | https://issues.redhat.com/browse/KEYCLOAK-17033 |

## 12.0.2
[Changelog](https://github.com/keycloak/keycloak/compare/12.0.1...12.0.2)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |
| KEYCLOAK-16468 | [KEYCLOAK-16468 Support for deny list of metadata attributes not updateable by account REST and admin REST](https://github.com/keycloak/keycloak/commit/a602a80ada921a0a795211c1539b59ce55477c05) | https://issues.redhat.com/browse/KEYCLOAK-16468 |
| KEYCLOAK-14019 | [KEYCLOAK-14019 Improvements for request_uri parameter](https://github.com/keycloak/keycloak/commit/55a064a978b0b7e0f0b93c33931f7dabe7d0d5e2) | https://issues.redhat.com/browse/KEYCLOAK-14019 |

## 12.0.1
[Changelog](https://github.com/keycloak/keycloak/compare/12.0.0...12.0.1)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |

## 12.0.0
[Changelog](https://github.com/keycloak/keycloak/compare/11.0.3...12.0.0)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |
| KEYCLOAK-16354 | [KEYCLOAK-16354: Update serialize-javascript dependency](https://github.com/keycloak/keycloak/commit/36fa3d555ab61ec93919dacf683883fbf4f404bb) | https://issues.redhat.com/browse/KEYCLOAK-16354 |
| KEYCLOAK-14352 | [[KEYCLOAK-14352] JavaScript injection vulnerability of Realm registration REST API](https://github.com/keycloak/keycloak/commit/43e075afa51d40cf65ead3d8797c877762a35c55) | https://issues.redhat.com/browse/KEYCLOAK-14352 |
| KEYCLOAK-14306 | [KEYCLOAK-14306 OIDC redirect_uri allows dangerous schemes resulting in potential XSS](https://github.com/keycloak/keycloak/commit/01be601dbdd77822827de173e34180d9322db85c) | https://issues.redhat.com/browse/KEYCLOAK-14306 |
| KEYCLOAK-15012 | [KEYCLOAK-15012 Fix issue with folder theme provider](https://github.com/keycloak/keycloak/commit/1281f28bb8d9968cce443324b81319fa25d70d65) | https://issues.redhat.com/browse/KEYCLOAK-15012 |
| KEYCLOAK-15295 | [KEYCLOAK-15295 User can manage resources with just "view-profile" role using new Account Console](https://github.com/keycloak/keycloak/commit/2df62369c3d9b2f6a7fc55b99c9412bff63c2632) | https://issues.redhat.com/browse/KEYCLOAK-15295 |
| KEYCLOAK-15735 | [KEYCLOAK-15735 Fix LDAPSamlIdPInitiatedVaryingLetterCaseTest failures on few DBs](https://github.com/keycloak/keycloak/commit/267f1797d4777e8ea9f3fe27a46629cad0884611) | https://issues.redhat.com/browse/KEYCLOAK-15735 |
| KEYCLOAK-15921 | [KEYCLOAK-15921 Fix auth server URL](https://github.com/keycloak/keycloak/commit/e80538c60c9b292dd7693a8319f44f7f0b0febe9) | https://issues.redhat.com/browse/KEYCLOAK-15921 |
| KEYCLOAK-15892 | [KEYCLOAK-15892 Can not install 7.4.3.CR1 Fuse adapter](https://github.com/keycloak/keycloak/commit/c8d0f2c59cddd3a719a6c03c8d1b267eeddd50c6) | https://issues.redhat.com/browse/KEYCLOAK-15892 |
| KEYCLOAK-15830 | [KEYCLOAK-15830 Remove authentication session after failed directGrant authentication](https://github.com/keycloak/keycloak/commit/d269af1b70960a2f7dfc2fb71002da2b209e37a8) | https://issues.redhat.com/browse/KEYCLOAK-15830 |
| KEYCLOAK-15734 | [KEYCLOAK-15734 Exclude tests with testingClient in remote environment](https://github.com/keycloak/keycloak/commit/540516c6a9a7850ecdb9ed59292d613c7ba2598a) | https://issues.redhat.com/browse/KEYCLOAK-15734 |
| KEYCLOAK-14828 | [KEYCLOAK-14828 Disable DTD for SAML XML parser](https://github.com/keycloak/keycloak/commit/e4078933f854c72a65d3d5619163da0ece874f2d) | https://issues.redhat.com/browse/KEYCLOAK-14828 |
| KEYCLOAK-14232 | [KEYCLOAK-14232 Add Referrer-Policy: no-referrer to each response from Keycloak](https://github.com/keycloak/keycloak/commit/f7e0af438d5a2d24b76bd3f34f71693c109738d5) | https://issues.redhat.com/browse/KEYCLOAK-14232 |
| KEYCLOAK-15270 | [KEYCLOAK-15270 Account REST API doesn't verify audience](https://github.com/keycloak/keycloak/commit/a9a719b88c67bb8575dca3b980582f9610b12257) | https://issues.redhat.com/browse/KEYCLOAK-15270 |
| KEYCLOAK-15395. | [KEYCLOAK-15395. Removed totp/remove (DELETE) and credentials/password (GET, POST) endpoints.](https://github.com/keycloak/keycloak/commit/2572b1464b5627905c9e857b22bfa9e34ddf1509) | https://issues.redhat.com/browse/KEYCLOAK-15395. |
| KEYCLOAK-14510 | [KEYCLOAK-14510 Properly close Response object](https://github.com/keycloak/keycloak/commit/1c4a2db8e1d0cb8f48edd2ac8d115decccf0bfb4) | https://issues.redhat.com/browse/KEYCLOAK-14510 |
| KEYCLOAK-14826 | [KEYCLOAK-14826 Fix non-ssl auth-server tests failures](https://github.com/keycloak/keycloak/commit/74988a3f21c26764e01956ff8c9ef5cea865cb2d) | https://issues.redhat.com/browse/KEYCLOAK-14826 |

## 11.0.3
[Changelog](https://github.com/keycloak/keycloak/compare/11.0.2...11.0.3)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |
| KEYCLOAK-15585 | [KEYCLOAK-15585 OIDC redirect_uri allows dangerous schemes resulting in potential XSS](https://github.com/keycloak/keycloak/commit/f660adc9f820c28de7dce42b6fff2c3bf39684fb) | https://issues.redhat.com/browse/KEYCLOAK-15585 |
| KEYCLOAK-14969 | [KEYCLOAK-14969 Whitelist RefreshableKeycloakSecurityContext for KeycloakPrincipal serialization](https://github.com/keycloak/keycloak/commit/e40234d9a02af5baa118fa071bb350fad542548a) | https://issues.redhat.com/browse/KEYCLOAK-14969 |
| KEYCLOAK-15590 | [KEYCLOAK-15590 Javascript adapter init() is throwing a promise error after upgrade to 11](https://github.com/keycloak/keycloak/commit/b5d90130350b6ad15c30041bf783fccb5a3fe6dd) | https://issues.redhat.com/browse/KEYCLOAK-15590 |
| KEYCLOAK-15722 | [KEYCLOAK-15722 KeycloakPromise sometimes doesn't work](https://github.com/keycloak/keycloak/commit/6a3945c9eb5560c6a83d68ba1637a2ffe41fd011) | https://issues.redhat.com/browse/KEYCLOAK-15722 |
| KEYCLOAK-15584 | [KEYCLOAK-15584 User can manage resources with just "view-profile" role using new Account Console](https://github.com/keycloak/keycloak/commit/d962340561601570db630eee4d3b207be7c220fe) | https://issues.redhat.com/browse/KEYCLOAK-15584 |
| KEYCLOAK-15012 | [KEYCLOAK-15012 Fix issue with folder theme provider](https://github.com/keycloak/keycloak/commit/0a4bccadf02487e66e0c7459e289121409640af7) | https://issues.redhat.com/browse/KEYCLOAK-15012 |

## 11.0.2
[Changelog](https://github.com/keycloak/keycloak/compare/11.0.1...11.0.2)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |

## 11.0.1
[Changelog](https://github.com/keycloak/keycloak/compare/11.0.0...11.0.1)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |
| KEYCLOAK-14872 | [KEYCLOAK-14872 CL DoS - read-timetout of the HTTP listener set to 30000 ms - read-timetout of the HTTPS listener set to 30000 ms - max-pool-size of the KeycloakDS datasource set to 100 connections](https://github.com/keycloak/keycloak/commit/bee4ca89897766c4b68856eafe14f1a3dad34251) | https://issues.redhat.com/browse/KEYCLOAK-14872 |
| KEYCLOAK-15217 | [KEYCLOAK-15217 Revert accidentally removed changes from KEYCLOAK-14107](https://github.com/keycloak/keycloak/commit/ebec28e4c7cc17c944f3737217aa5bfabe24e586) | https://issues.redhat.com/browse/KEYCLOAK-15217 |
| KEYCLOAK-14352 | [[KEYCLOAK-14352] JavaScript injection vulnerability of Realm registration REST API](https://github.com/keycloak/keycloak/commit/c1bbd7c508e467fc1faaf3709ffe803bbc3e11af) | https://issues.redhat.com/browse/KEYCLOAK-14352 |
| KEYCLOAK-14232 | [KEYCLOAK-14232 Add Referrer-Policy: no-referrer to each response from Keycloak](https://github.com/keycloak/keycloak/commit/3ba95662df8abe74c9248e879faa8bf4022ede67) | https://issues.redhat.com/browse/KEYCLOAK-14232 |
| KEYCLOAK-14828 | [KEYCLOAK-14828 Disable DTD for SAML XML parser](https://github.com/keycloak/keycloak/commit/0f6dc45fadbc1f8d2f4a90e8df550ae2f1322510) | https://issues.redhat.com/browse/KEYCLOAK-14828 |

## 11.0.0
[Changelog](https://github.com/keycloak/keycloak/compare/10.0.2...11.0.0)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |
| KEYCLOAK-14778 | [KEYCLOAK-14778 Springboot tests fails with compilation error](https://github.com/keycloak/keycloak/commit/08023239165f5b4784cb5dde9cfc0fd121b8298e) | https://issues.redhat.com/browse/KEYCLOAK-14778 |
| KEYCLOAK-14508 | [KEYCLOAK-14508 - Exclude SessionNotOnOrAfterTest from remote tests](https://github.com/keycloak/keycloak/commit/48e4432e9dff0bf0fbe593e72b849e21961e1e1f) | https://issues.redhat.com/browse/KEYCLOAK-14508 |
| KEYCLOAK-14474 | [KEYCLOAK-14474 ConsentsTest fails intermittently on auth-server-undertow](https://github.com/keycloak/keycloak/commit/71dca9e1b99c05aa2b7c7d38f46b769df509ec04) | https://issues.redhat.com/browse/KEYCLOAK-14474 |
| KEYCLOAK-14574 | [KEYCLOAK-14574: Update angularjs to 1.8.0](https://github.com/keycloak/keycloak/commit/556c61160c6d2e7dfb61ece344574e38306646ab) | https://issues.redhat.com/browse/KEYCLOAK-14574 |
| KEYCLOAK-14546 | [KEYCLOAK-14546 Springboot tests fails with compilation error](https://github.com/keycloak/keycloak/commit/c163fce46e13af928f097281e51e41afc35870b4) | https://issues.redhat.com/browse/KEYCLOAK-14546 |
| KEYCLOAK-14516 | [KEYCLOAK-14516 app-server-eap6 tests fails due to compilation error](https://github.com/keycloak/keycloak/commit/1b988cc12e7d7bab6375646a40e1e4e1a810b330) | https://issues.redhat.com/browse/KEYCLOAK-14516 |
| KEYCLOAK-14087 | [KEYCLOAK-14087 migration from 9.0.3](https://github.com/keycloak/keycloak/commit/c403aa49f724fec793e3babc3de4bf4e9753bf24) | https://issues.redhat.com/browse/KEYCLOAK-14087 |
| KEYCLOAK-10162 | [KEYCLOAK-10162 Usage of ObjectInputStream without checking the object types](https://github.com/keycloak/keycloak/commit/33863ba16117844930a38ebde57a25258f5b80fd) | https://issues.redhat.com/browse/KEYCLOAK-10162 |
| KEYCLOAK-12305 | [[KEYCLOAK-12305] [Testsuite] Check LDAP federated user (in)valid login(s) using various authentication methods, bind credential types, and connection encryption mechanisms](https://github.com/keycloak/keycloak/commit/a121f77ea468d07275212668e85a2be7601b6ea0) | https://issues.redhat.com/browse/KEYCLOAK-12305 |
| KEYCLOAK-13748 | [KEYCLOAK-13748 Create automated test for scenario with alternative subflow for credential reset](https://github.com/keycloak/keycloak/commit/8c7b69fc9ec35f9d51654db311651fb5c6f1c0ba) | https://issues.redhat.com/browse/KEYCLOAK-13748 |
| KEYCLOAK-13047 | [KEYCLOAK-13047 LDAP no-import fixes. Avoid lost updates - dont allow update attributes, which are not mapped to LDAP](https://github.com/keycloak/keycloak/commit/12d965abf37fb4f594c61b05d48374de5a3eb899) | https://issues.redhat.com/browse/KEYCLOAK-13047 |
| KEYCLOAK-14062 | [KEYCLOAK-14062 Add postgres10](https://github.com/keycloak/keycloak/commit/37e23cb0a2bb66ef371a6f3fb0618844a34f6e00) | https://issues.redhat.com/browse/KEYCLOAK-14062 |
| KEYCLOAK-14086 | [KEYCLOAK-14086 Outdated wildfly deprecated version](https://github.com/keycloak/keycloak/commit/4a70494285054239999257dc7087a5e788c50f3d) | https://issues.redhat.com/browse/KEYCLOAK-14086 |

## 10.0.2
[Changelog](https://github.com/keycloak/keycloak/compare/10.0.1...10.0.2)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |

## 10.0.1
[Changelog](https://github.com/keycloak/keycloak/compare/10.0.0...10.0.1)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |

## 10.0.0
[Changelog](https://github.com/keycloak/keycloak/compare/9.0.3...10.0.0)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |
| KEYCLOAK-13636 | [KEYCLOAK-13636 Missing wildfly-dist in EAP 7.4.0.CD19 build](https://github.com/keycloak/keycloak/commit/be28bfee1dc22d19c637b0bde70be3665338585f) | https://issues.redhat.com/browse/KEYCLOAK-13636 |
| KEYCLOAK-13656 | [[KEYCLOAK-13656] - Deny request if requested scope is not associated to resource or any typed resources](https://github.com/keycloak/keycloak/commit/44b489b57198200688396ca7111e049d124e0f72) | https://issues.redhat.com/browse/KEYCLOAK-13656 |
| KEYCLOAK-13852 | [KEYCLOAK-13852 reset time at the end of testTokenConcurrentRefresh test](https://github.com/keycloak/keycloak/commit/1db87acc98edbf616f9af7deb992a32176940ded) | https://issues.redhat.com/browse/KEYCLOAK-13852 |
| KEYCLOAK-13306 | [KEYCLOAK-13306 Model fixes for check realm when lookup by ID](https://github.com/keycloak/keycloak/commit/b29810c92328be014023e87f73325095df221c2a) | https://issues.redhat.com/browse/KEYCLOAK-13306 |
| KEYCLOAK-13285 | [KEYCLOAK-13285 Enable check identity for email](https://github.com/keycloak/keycloak/commit/97b565469058cacac6d2559b2cff37effcca2cfd) | https://issues.redhat.com/browse/KEYCLOAK-13285 |
| KEYCLOAK-7450 | [[KEYCLOAK-7450] - Match subject when validating id_token returned from external OP](https://github.com/keycloak/keycloak/commit/b60b85ab65a6197f6f1bce84880fcf447e6afbd6) | https://issues.redhat.com/browse/KEYCLOAK-7450 |
| KEYCLOAK-13660 | [KEYCLOAK-13660 Patch installation is not performed with -Dauth.server.patch.zips](https://github.com/keycloak/keycloak/commit/52b67f61725ce70b127d37486cc75e53df93323c) | https://issues.redhat.com/browse/KEYCLOAK-13660 |
| KEYCLOAK-13383 | [KEYCLOAK-13383 WebAuthnRegisterAndLoginTest fails with -Dproduct with auth-server-eap](https://github.com/keycloak/keycloak/commit/bf92bd16b05ca333b9cffd1600b307fbdfc943bd) | https://issues.redhat.com/browse/KEYCLOAK-13383 |
| KEYCLOAK-13384 | [KEYCLOAK-13384 exclude IdentityProviderTest.failCreateInvalidUrl from remote-tests](https://github.com/keycloak/keycloak/commit/330d5b2c253143f6a93d760aee768b1332460cb1) | https://issues.redhat.com/browse/KEYCLOAK-13384 |
| KEYCLOAK-13571 | [KEYCLOAK-13571 KcinitTest fails with -Dproduct due to skipped maven plugin exacution](https://github.com/keycloak/keycloak/commit/780d11e790f460d7307e1e112b7b7a7fc658fdea) | https://issues.redhat.com/browse/KEYCLOAK-13571 |
| KEYCLOAK-12972 | [KEYCLOAK-12972 Fix fuse tests](https://github.com/keycloak/keycloak/commit/8b96882a1c990faf1ec0a4bf44c49bd83929f2eb) | https://issues.redhat.com/browse/KEYCLOAK-12972 |

## 9.0.3
[Changelog](https://github.com/keycloak/keycloak/compare/9.0.2...9.0.3)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |
| KEYCLOAK-13383 | [KEYCLOAK-13383 WebAuthnRegisterAndLoginTest fails with -Dproduct with auth-server-eap](https://github.com/keycloak/keycloak/commit/dcd9f3dfd1a7f560320b53e4150f7890736db530) | https://issues.redhat.com/browse/KEYCLOAK-13383 |
| KEYCLOAK-13384 | [KEYCLOAK-13384 exclude IdentityProviderTest.failCreateInvalidUrl from remote-tests](https://github.com/keycloak/keycloak/commit/a6c9b35650fd82d8546808f703cd4311ff51fcd5) | https://issues.redhat.com/browse/KEYCLOAK-13384 |
| KEYCLOAK-13571 | [KEYCLOAK-13571 KcinitTest fails with -Dproduct due to skipped maven plugin exacution](https://github.com/keycloak/keycloak/commit/cb4bf825cb335874a9ad9132420462fd3354fa81) | https://issues.redhat.com/browse/KEYCLOAK-13571 |
| KEYCLOAK-12972 | [KEYCLOAK-12972 Fix fuse tests](https://github.com/keycloak/keycloak/commit/50fc8cdb985a8993037ece4651846aa9d7202b91) | https://issues.redhat.com/browse/KEYCLOAK-12972 |
| KEYCLOAK-13285 | [KEYCLOAK-13285 Enable check identity for email](https://github.com/keycloak/keycloak/commit/531dc51ab7237e826147b2073f8a737544d5f265) | https://issues.redhat.com/browse/KEYCLOAK-13285 |

## 9.0.2
[Changelog](https://github.com/keycloak/keycloak/compare/9.0.0...9.0.2)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |

## 9.0.1

There is no 9.0.1 tag (anymore).

## 9.0.0
[Changelog](https://github.com/keycloak/keycloak/compare/8.0.2...9.0.0)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |
| KEYCLOAK-10420 | [KEYCLOAK-10420 Broker tests don't work with RH-SSO](https://github.com/keycloak/keycloak/commit/90b35cc13d5ac9c8e785ecba1e7e94f50536cce8) | https://issues.redhat.com/browse/KEYCLOAK-10420 |
| KEYCLOAK-12065 | [KEYCLOAK-12065 UserSessionInitializerTest is failing](https://github.com/keycloak/keycloak/commit/1bdf77f40936611e963cd775f581fe2ed0aae8cf) | https://issues.redhat.com/browse/KEYCLOAK-12065 |
| KEYCLOAK-12964 | [KEYCLOAK-12964 Fix adapter remote tests execution deciding](https://github.com/keycloak/keycloak/commit/c3f0b342bfbeece5b19d9cca33831a3af2947922) | https://issues.redhat.com/browse/KEYCLOAK-12964 |
| KEYCLOAK-12963 | [KEYCLOAK-12963 Exclude testNoPortInDestination test for remote container](https://github.com/keycloak/keycloak/commit/f28ca30e6df92f85fb9037729c710d5728dffed5) | https://issues.redhat.com/browse/KEYCLOAK-12963 |
| KEYCLOAK-12237 | [KEYCLOAK-12237 Fix WelcomePageTest on Postgresql](https://github.com/keycloak/keycloak/commit/3d22644bbe0e95638059ff077c83c119b6f00f72) | https://issues.redhat.com/browse/KEYCLOAK-12237 |
| KEYCLOAK-11930 | [KEYCLOAK-11930 removal of xstream license references as this dependency has been removed](https://github.com/keycloak/keycloak/commit/96c2fffd1e5f1a64cef4251f338ed2695926f696) | https://issues.redhat.com/browse/KEYCLOAK-11930 |
| KEYCLOAK-12228 | [KEYCLOAK-12228 Sensitive Data Exposure from patch of hiba haddad haddadhiba0@gmail.com](https://github.com/keycloak/keycloak/commit/622a97bd1c3044760b2166301864da9941cae131) | https://issues.redhat.com/browse/KEYCLOAK-12228 |
| KEYCLOAK-12821 | [KEYCLOAK-12821 Check if action is disabled in realm before executing](https://github.com/keycloak/keycloak/commit/3c0cf8463aea85f4658ff764f53f24853dcd7296) | https://issues.redhat.com/browse/KEYCLOAK-12821 |
| KEYCLOAK-9563 | [KEYCLOAK-9563 Improve access token checks for userinfo endpoint](https://github.com/keycloak/keycloak/commit/1d54f2ade391f397956fdcb66f75daf0182d8c1e) | https://issues.redhat.com/browse/KEYCLOAK-9563 |
| KEYCLOAK-12638 | [KEYCLOAK-12638 Remove Request parameters from exception message](https://github.com/keycloak/keycloak/commit/62c9e1577618470832ede22dcedd46cba15b1836) | https://issues.redhat.com/browse/KEYCLOAK-12638 |
| KEYCLOAK-12764 | [KEYCLOAK-12764 Fix shrinkwrap issue by updating arquillian bom version](https://github.com/keycloak/keycloak/commit/e5935d8069154db2bc9ee83ae85c7e1ff6822324) | https://issues.redhat.com/browse/KEYCLOAK-12764 |
| KEYCLOAK-12193 | [KEYCLOAK-12193 Internal error message returned in error response](https://github.com/keycloak/keycloak/commit/ecec20ad597ae360a964b4c039827bab8e27a2fe) | https://issues.redhat.com/browse/KEYCLOAK-12193 |
| KEYCLOAK-12190 | [KEYCLOAK-12190 Fix PartialImportTest for client validation](https://github.com/keycloak/keycloak/commit/5d1fa8719e12c7013c2016621efe1cf8bdeb0a00) | https://issues.redhat.com/browse/KEYCLOAK-12190 |
| KEYCLOAK-12190 | [KEYCLOAK-12190 Add validation for client root and base URLs](https://github.com/keycloak/keycloak/commit/75457496325c4ae8963199a318d834d6a5eaad16) | https://issues.redhat.com/browse/KEYCLOAK-12190 |
| KEYCLOAK-12792 | [[KEYCLOAK-12792] - Invalid nonce handling in OIDC identity brokering](https://github.com/keycloak/keycloak/commit/fc514aa2567ca353b8c3dc380ff80b9af88c9295) | https://issues.redhat.com/browse/KEYCLOAK-12792 |
| KEYCLOAK-12240 | [KEYCLOAK-12240 MigrationModelTest fails in pipeline](https://github.com/keycloak/keycloak/commit/337e8f8fad5404bc5a27ea1340956861b1515747) | https://issues.redhat.com/browse/KEYCLOAK-12240 |
| KEYCLOAK-12744 | [[KEYCLOAK-12744] rh-sso-preview theme for product build](https://github.com/keycloak/keycloak/commit/6ac5a2a17ed00bfd36ad103f56f3797547157fcf) | https://issues.redhat.com/browse/KEYCLOAK-12744 |
| KEYCLOAK-12236 | [KEYCLOAK-12236 NumberFormatException when starting container (#6689)](https://github.com/keycloak/keycloak/commit/d6c5f79f2cd7d388780ea29c5ef39707ecdd2f5f) | https://issues.redhat.com/browse/KEYCLOAK-12236 |
| KEYCLOAK-12724 | [KEYCLOAK-12724 - workaround hibernate bug - set explicitly dialect for oracle version greater than 12](https://github.com/keycloak/keycloak/commit/47d6d65bbb18a5f23a5b67c2282e2090fab9e4a3) | https://issues.redhat.com/browse/KEYCLOAK-12724 |
| KEYCLOAK-12462 | [KEYCLOAK-12462 Align to EAP 7.3.0.CR3](https://github.com/keycloak/keycloak/commit/89fc0e1fcc3df43e4a8e89c817b897f8aa9a5d60) | https://issues.redhat.com/browse/KEYCLOAK-12462 |
| KEYCLOAK-12462 | [KEYCLOAK-12462 Align to EAP 7.3.0.GA](https://github.com/keycloak/keycloak/commit/e1f8e5d08cd377bcc8f8c19e417f54f43e0ae420) | https://issues.redhat.com/browse/KEYCLOAK-12462 |
| KEYCLOAK-12242 | [KEYCLOAK-12242 KEYCLOAK-12280](https://github.com/keycloak/keycloak/commit/1ac76fde5986d78f34f6a73cd157487bc26d8b36) | https://issues.redhat.com/browse/KEYCLOAK-12242 |
| KEYCLOAK-11863 | [KEYCLOAK-11863 ConfigMigrationTest wrong assertion for Standalone configuration](https://github.com/keycloak/keycloak/commit/13b546315325750230ea4762fbfa5adc362cea68) | https://issues.redhat.com/browse/KEYCLOAK-11863 |
| KEYCLOAK-12062 | [KEYCLOAK-12062 AccountLinkSpringBootTest is failing](https://github.com/keycloak/keycloak/commit/3c3667d81e60cda096ab6073672d7ed252e280f6) | https://issues.redhat.com/browse/KEYCLOAK-12062 |
| KEYCLOAK-12117 | [KEYCLOAK-12117 X509BrowserLoginTest failing in pipeline](https://github.com/keycloak/keycloak/commit/50ec24557e16741e1ac2d97ed9280432b5add631) | https://issues.redhat.com/browse/KEYCLOAK-12117 |
| KEYCLOAK-12072 | [KEYCLOAK-12072 Missing version for spring-boot-legacy-container-bundle in product](https://github.com/keycloak/keycloak/commit/ebb1883427dd210967510fa23f31bd9a3732d0f2) | https://issues.redhat.com/browse/KEYCLOAK-12072 |
| KEYCLOAK-12070 | [KEYCLOAK-12070 Split properties for sun.xml.ws and sun.xml.bind](https://github.com/keycloak/keycloak/commit/ee72cab41547b95dc19b2dac50f98b2315dbbeeb) | https://issues.redhat.com/browse/KEYCLOAK-12070 |
| KEYCLOAK-12070 | [KEYCLOAK-12070 Alignment clash for sun.jaxb.version](https://github.com/keycloak/keycloak/commit/1fd3d8525bf4c29425c3a570246e67fa8c66f339) | https://issues.redhat.com/browse/KEYCLOAK-12070 |

# Misq

## Why?
The Keycloak maintainers do not announce security fixes (Like for every rule there are [exceptions](https://www.keycloak.org/docs/latest/release_notes/index.html#ldap-issue)).
So to identify the criticality of an update you have to check all the changes in the git repository and try to find out which of them a security fixes. But the Keycloak team makes their JIRA issues private, if they are about security issues. That allows us to correlate git commits with JIRA issues that are private.
I miss this list on every Keycloak update. So I decided to do this myself.
My goal is to enable others to better decide if they need to update their Keycloak instances.

## Is every private issue a security issue?
I do not think so. There could also be other reasons to make an issue private.
But I do not know. I am not able to check that. I expect that there will be private issues that are not security issues.

## Are there security issues that are public?
I think so. One could argue that for example every Wildfly update is a security fix in some way. There also might other issues that fixes vulnerabilities, but that are public.

## So which updates should I apply?
All of them.
But test them properly. The .0 releases are huge sometimes and the .1 releases often contain fixes for the previous ones.

## This is irresponsible!
As so often there is a problem with the dual-use security dilemma.
But I do not publish new research or exploits.
In the end I only gather some public information. This can be done by anyone with beginner level bash, git and curl skills.
As someone responsible for Keycloak instances I rate the value for me higher than for attackers. 

## Are there any further informations about security and Keycloak?
First there is the [Threat Model Mitigation](https://www.keycloak.org/docs/latest/server_admin/#threat-model-mitigation) part of the official Keycloak docs. This is their "Hardening Guide".
Then there is the [Keycloak - CNCF Security SIG - Self Assessment](https://docs.google.com/document/d/14IIGliP3BWjdS-0wfOk3l_1AU8kyoSiLUzpPImsz4R0/). While the submissin process is stuck for a while now the document definitely is worth a read.
Third there is the [report of a security assessment of Keycloak version 8.0.0](https://cure53.de/pentest-report_keycloak.pdf) executed by [Cure53](https://cure53.de/) funded by [REWE digital](https://www.rewe-digital.com/inside-rewe-digital/show/rewe-digital-loves-open-source.html) (Disclaimer: I have been involved in the assessment).
