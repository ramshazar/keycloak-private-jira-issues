# List of Keycloak CVEs

[nvd.nist.gov](https://nvd.nist.gov/vuln/search/results?form_type=Basic&results_type=overview&query=keycloak&search_type=all)

# Private JIRA Issues

## 14.0.0
[Changelog](https://github.com/keycloak/keycloak/compare/13.0.1...14.0.0)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |
| KEYCLOAK-18464 | [[KEYCLOAK-18464] - Failures when running without tls and remote](https://github.com/keycloak/keycloak/commit/6bb7a8894d6deb1ab46be59d99b3a124e582e733) | https://issues.redhat.com/browse/KEYCLOAK-18464 |
| KEYCLOAK-18102 | [KEYCLOAK-18102 - set specific jpa schema.](https://github.com/keycloak/keycloak/commit/b1f3e5554c2d3197b043404841cc26b8879d3664) | https://issues.redhat.com/browse/KEYCLOAK-18102 |
| KEYCLOAK-18406 | [KEYCLOAK-18406 SAMLServletAdapterTest failures](https://github.com/keycloak/keycloak/commit/333d279d7aeb39a3612af1bc7c778a2d1e1f8ffe) | https://issues.redhat.com/browse/KEYCLOAK-18406 |
| KEYCLOAK-18393 | [KEYCLOAK-18393 SAMLAdapterCrossDCTest failures](https://github.com/keycloak/keycloak/commit/6db1c8204ab4debecfa3950aae71d78db7183891) | https://issues.redhat.com/browse/KEYCLOAK-18393 |
| KEYCLOAK-18442 | [KEYCLOAK-18442 LifespanAdapterTest - duplicate resources](https://github.com/keycloak/keycloak/commit/78b676232677afd10b603d6f57a0d66488e5c6a9) | https://issues.redhat.com/browse/KEYCLOAK-18442 |
| KEYCLOAK-18391 | [KEYCLOAK-18391 CIBATest failure](https://github.com/keycloak/keycloak/commit/7ffa2835ef9159fbf6a6112c0783bb10a2260bb7) | https://issues.redhat.com/browse/KEYCLOAK-18391 |
| KEYCLOAK-18368 | [KEYCLOAK-18368 Invalidate client session after refresh token re-use](https://github.com/keycloak/keycloak/commit/91865fa93e3169cf31d03c8c37578c14a0ebff60) | https://issues.redhat.com/browse/KEYCLOAK-18368 |
| KEYCLOAK-18260 | [KEYCLOAK-18260 ClientSearchTest.testQuerySearch failure on MSSQL2019 - removed Central European characters from the test](https://github.com/keycloak/keycloak/commit/b071be779905bc2964a970f1f97c56fae067d0f8) | https://issues.redhat.com/browse/KEYCLOAK-18260 |
| KEYCLOAK-18249 | [KEYCLOAK-18249 WelcomePageTest fails on MSSQL 2019 - removed reference to `FK_P56CTINXXB9GSK57FO49F9TAC` from the `DropAllServlet`](https://github.com/keycloak/keycloak/commit/80eabcb7ebf44d11ee3ef304e7f9e453b49f8b59) | https://issues.redhat.com/browse/KEYCLOAK-18249 |
| KEYCLOAK-14540 | [KEYCLOAK-14540 Determine project/product name](https://github.com/keycloak/keycloak/commit/4b009ebf5e04f746608e115924c48c3d286485e1) | https://issues.redhat.com/browse/KEYCLOAK-14540 |
| KEYCLOAK-13757 | [KEYCLOAK-13757 fix for KEYCLOAK-18267_KEYCLOAK-17254](https://github.com/keycloak/keycloak/commit/1033b272e8dcb8bc0681ec3df8e1a02d32134b1f) | https://issues.redhat.com/browse/KEYCLOAK-13757 |
| KEYCLOAK-13757 | [KEYCLOAK-13757 update JDG version to 8.1 - testsuite updates](https://github.com/keycloak/keycloak/commit/28027401013b912450e01263ee467c511bc3c414) | https://issues.redhat.com/browse/KEYCLOAK-13757 |
| KEYCLOAK-17254 | [[KEYCLOAK-17254] Adaptively add the default modular JVM options to the "javaVmArguments" to start the cache server container with, if the JVM used to run the cache server is modular (JDK 9+)](https://github.com/keycloak/keycloak/commit/cbd42882053fa79b173934f809f1358c3eaca50a) | https://issues.redhat.com/browse/KEYCLOAK-17254 |
| KEYCLOAK-18267 | [[KEYCLOAK-18267] Fix 'java.lang.NoClassDefFoundError: Could not initialize class org.jboss.marshalling.river.RiverMarshaller' error for:](https://github.com/keycloak/keycloak/commit/de8dd59d66fa7f44a5353352b3f6bc4b38e36031) | https://issues.redhat.com/browse/KEYCLOAK-18267 |
| KEYCLOAK-18337 | [KEYCLOAK-18337 FAPI1Test fails in pipeline with auth-server-undertow-non-tls](https://github.com/keycloak/keycloak/commit/12c47150e776f02cda173908e1308443e3e1be8a) | https://issues.redhat.com/browse/KEYCLOAK-18337 |
| KEYCLOAK-14515 | [KEYCLOAK-14515 ModAuthMellonTest fails](https://github.com/keycloak/keycloak/commit/fc40e875b9545440ba297a546bb3df890960606d) | https://issues.redhat.com/browse/KEYCLOAK-14515 |
| KEYCLOAK-17796 | [KEYCLOAK-17796 Add options to http-builder to enable expect-continue, and to disable re-use of connections](https://github.com/keycloak/keycloak/commit/c3a15cb368eaa20d6af362926e1d77e7d96f7420) | https://issues.redhat.com/browse/KEYCLOAK-17796 |
| KEYCLOAK-18112 | [KEYCLOAK-18112 Token introspection of the revoked refresh token](https://github.com/keycloak/keycloak/commit/bc6a746780ab797519886c4448e12edebaac9cf5) | https://issues.redhat.com/browse/KEYCLOAK-18112 |
| KEYCLOAK-18250 | [[KEYCLOAK-18250] LDAPSyncTest.test09MembershipUsingDifferentAttributes fails on MySQL 8 and MariaDB 10.3](https://github.com/keycloak/keycloak/commit/38101d01c262b2f4585870017011da2c0d4fd012) | https://issues.redhat.com/browse/KEYCLOAK-18250 |
| KEYCLOAK-18264 | [KEYCLOAK-18264 Fix SamlLogoutTest with different consumer and provider url](https://github.com/keycloak/keycloak/commit/b216b9579c80954b8859bac76aee5d5a81ec1ea2) | https://issues.redhat.com/browse/KEYCLOAK-18264 |
| KEYCLOAK-16450 | [KEYCLOAK-16450 X509 Direct Grant Auth does not verify certificate timestamp validity](https://github.com/keycloak/keycloak/commit/478319348bdfdb9b6d39122f41edf2af79f679bb) | https://issues.redhat.com/browse/KEYCLOAK-16450 |
| KEYCLOAK-18056 | [KEYCLOAK-18056 exclude test for remote testsuite.](https://github.com/keycloak/keycloak/commit/afb8da7ff07e0b056a69c7d612e0280196029498) | https://issues.redhat.com/browse/KEYCLOAK-18056 |
| KEYCLOAK-17683 | [KEYCLOAK-17683 Use dedicated tmp directory even in unit tests](https://github.com/keycloak/keycloak/commit/2817cb4a19b0ea3f3425bbfc602b01b89a3c6c66) | https://issues.redhat.com/browse/KEYCLOAK-17683 |
| KEYCLOAK-17495 | [KEYCLOAK-17495 Do not include principal in the reference to broker sessionId](https://github.com/keycloak/keycloak/commit/3bb5bff8e0bf9de91dde9323ef8bc2b637b90e1d) | https://issues.redhat.com/browse/KEYCLOAK-17495 |
| KEYCLOAK-18030 | [[KEYCLOAK-18030] Upgrade Freemarker](https://github.com/keycloak/keycloak/commit/008fa8c2b1c47cf293e9bcd14520e0cc9610579c) | https://issues.redhat.com/browse/KEYCLOAK-18030 |
| KEYCLOAK-17322 | [KEYCLOAK-17322 Align tested databases with EAP 7.4 support matrix](https://github.com/keycloak/keycloak/commit/12921357292fc2d69982e944df0db3a20dfb6873) | https://issues.redhat.com/browse/KEYCLOAK-17322 |
| KEYCLOAK-18059 | [[KEYCLOAK-18059] Upgrade dev dependencies for the new Account Console (#8020)](https://github.com/keycloak/keycloak/commit/a6ab3119d63e136eb3ad86f4df572f41b7642449) | https://issues.redhat.com/browse/KEYCLOAK-18059 |
| KEYCLOAK-18060 | [[KEYCLOAK-18060] Upgrade commons-io](https://github.com/keycloak/keycloak/commit/87282ad18deafc9850c9222f1b033d84d9d8335c) | https://issues.redhat.com/browse/KEYCLOAK-18060 |
| KEYCLOAK-17997 | [[KEYCLOAK-17997] Upgrade Spring Security](https://github.com/keycloak/keycloak/commit/bbc8d83f64565224a29d325899985c023a36112c) | https://issues.redhat.com/browse/KEYCLOAK-17997 |
| KEYCLOAK-18001 | [[KEYCLOAK-18001] Upgrade Apache Ant dependency](https://github.com/keycloak/keycloak/commit/818dc40304bf9ae0a752dafe6963e71d8ba7847e) | https://issues.redhat.com/browse/KEYCLOAK-18001 |

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
| KEYCLOAK-15390 | [KEYCLOAK-15390 fix ClientMappersOIDCTest](https://github.com/keycloak/keycloak/commit/2ed8ed2543716e5d51acf2ef1c16c6ffd0f8d80b) | https://issues.redhat.com/browse/KEYCLOAK-15390 |

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
| KEYCLOAK-13259 | [KEYCLOAK-13259](https://github.com/keycloak/keycloak/commit/5ddd605ee96b8551c7eb00b609a0b97939925b77) | https://issues.redhat.com/browse/KEYCLOAK-13259 |
| KEYCLOAK-12986 | [KEYCLOAK-12986 BruteForceProtector does not log failures when login failure in PostBroker flow](https://github.com/keycloak/keycloak/commit/9474dd6208c01166b6144bea3ac2b6fe9f5c30f4) | https://issues.redhat.com/browse/KEYCLOAK-12986 |
| KEYCLOAK-12156 | [KEYCLOAK-12156 LogoutEndpoint does not verify token type of id_token_hint](https://github.com/keycloak/keycloak/commit/e6e0e6945dae13159216e5b06fe3342ec0bd4f1e) | https://issues.redhat.com/browse/KEYCLOAK-12156 |
| KEYCLOAK-13393 | [[KEYCLOAK-13393] Account2 marked as experimental](https://github.com/keycloak/keycloak/commit/5e101d20cae4be661d815737c34584b64aea5097) | https://issues.redhat.com/browse/KEYCLOAK-13393 |
| KEYCLOAK-13380 | [KEYCLOAK-13380 Validate alignment](https://github.com/keycloak/keycloak/commit/9336d598ba833ed92bf68ab923155926994e6c2d) | https://issues.redhat.com/browse/KEYCLOAK-13380 |
| KEYCLOAK-13390 | [KEYCLOAK-13390 license file update before 9.0.1 release](https://github.com/keycloak/keycloak/commit/2cccc97b2edb5960522cefbfae00866c872f9184) | https://issues.redhat.com/browse/KEYCLOAK-13390 |
| KEYCLOAK-13388 | [KEYCLOAK-13388 Trailing comma in tsconfig.json](https://github.com/keycloak/keycloak/commit/03bce36b4832f48ef9b9a6a25d90ef9e864e6301) | https://issues.redhat.com/browse/KEYCLOAK-13388 |
| KEYCLOAK-13386 | [[KEYCLOAK-13386] - SslRequired.EXTERNAL doesn't work for identity broker validations](https://github.com/keycloak/keycloak/commit/ec63245ac85ab850624e5101dd0159ff3336c71e) | https://issues.redhat.com/browse/KEYCLOAK-13386 |
| KEYCLOAK-13379 | [KEYCLOAK-13379 added now excluded project files](https://github.com/keycloak/keycloak/commit/4279f5b54f1f56128a30737edc03fae645354881) | https://issues.redhat.com/browse/KEYCLOAK-13379 |
| KEYCLOAK-13369 | [KEYCLOAK-13369 Not possible to move groups in admin console](https://github.com/keycloak/keycloak/commit/3e82473a9019f263a6b2824ad4eb7d1937a84a75) | https://issues.redhat.com/browse/KEYCLOAK-13369 |
| KEYCLOAK-13368 | [KEYCLOAK-13368 TestClassProvider undertow server not stopped after testsuite](https://github.com/keycloak/keycloak/commit/61fd66e10722b903379209b489a07291a4266220) | https://issues.redhat.com/browse/KEYCLOAK-13368 |
| KEYCLOAK-8372 | [KEYCLOAK-8372 - User Federation tests - fixing for different vendors (#6909)](https://github.com/keycloak/keycloak/commit/6cc897e3195aa3b1a2e441bd3a573b02f7d70b64) | https://issues.redhat.com/browse/KEYCLOAK-8372 |
| KEYCLOAK-12870 | [KEYCLOAK-12870 - Allow to pick arbitrary user for IdP linking (#6828)](https://github.com/keycloak/keycloak/commit/3b24465141b54ac88e73e35d580b46e009d1ff9a) | https://issues.redhat.com/browse/KEYCLOAK-12870 |
| KEYCLOAK-13273 | [[KEYCLOAK-13273] - Remove group policy when group is removed](https://github.com/keycloak/keycloak/commit/2eab44d3f391515e6383da223e98bb041b25b20b) | https://issues.redhat.com/browse/KEYCLOAK-13273 |
| KEYCLOAK-13356 | [KEYCLOAK-13356 Update licenses for kerby-asn1](https://github.com/keycloak/keycloak/commit/3d95637102eb029ae0da930d83bd9c8ba870e37e) | https://issues.redhat.com/browse/KEYCLOAK-13356 |
| KEYCLOAK-13348 | [KEYCLOAK-13348 license files updates - due to broken product build](https://github.com/keycloak/keycloak/commit/48e5e1a532d4bb86a84025aac19f40e31b93a05a) | https://issues.redhat.com/browse/KEYCLOAK-13348 |
| KEYCLOAK-4923 | [KEYCLOAK-4923: Client Service Account Roles are not exported](https://github.com/keycloak/keycloak/commit/a8e74196d1ca8a360bea52e9f76cb056d859f68f) | https://issues.redhat.com/browse/KEYCLOAK-4923 |
| KEYCLOAK-12696 | [KEYCLOAK-12696 license files updates](https://github.com/keycloak/keycloak/commit/82267c9647ff495e6bf38e114f69db5c10b86bf7) | https://issues.redhat.com/browse/KEYCLOAK-12696 |
| KEYCLOAK-13007 | [KEYCLOAK-13007 Add LDAPAccountTest](https://github.com/keycloak/keycloak/commit/f8dc7c0329891442486db0c8b436be2e083b1a6d) | https://issues.redhat.com/browse/KEYCLOAK-13007 |
| KEYCLOAK-12696 | [KEYCLOAK-12696 Upgrade to webauthn4j 0.10.2.RELEASE](https://github.com/keycloak/keycloak/commit/fc58af1365f596962b5c8e8c1202bea3ce325abe) | https://issues.redhat.com/browse/KEYCLOAK-12696 |
| KEYCLOAK-13249 | [KEYCLOAK-13249 jpa-changelog-8.0.0.xml contains whitespace character](https://github.com/keycloak/keycloak/commit/86089d40b869fd060de0ee0c022324b54152d277) | https://issues.redhat.com/browse/KEYCLOAK-13249 |
| KEYCLOAK-12768 | [KEYCLOAK-12768: Prevent reserved characters in URLs](https://github.com/keycloak/keycloak/commit/fff8571cfd7127799443398a5c7059d6d1b4f48d) | https://issues.redhat.com/browse/KEYCLOAK-12768 |
| KEYCLOAK-12844 | [KEYCLOAK-12844: keycloak.d.ts does not belong in new account console](https://github.com/keycloak/keycloak/commit/256bbff769d2837cc1b082aabc22eac76c92b630) | https://issues.redhat.com/browse/KEYCLOAK-12844 |
| KEYCLOAK-13257 | [KEYCLOAK-13257 Fix WelcomeScreenTest.accountSecurityTest](https://github.com/keycloak/keycloak/commit/89f483d578140dd510fa4a06ad3ae189ed135f6c) | https://issues.redhat.com/browse/KEYCLOAK-13257 |
| KEYCLOAK-13256 | [KEYCLOAK-13256 Fix WebAuthn in new Account Console tests](https://github.com/keycloak/keycloak/commit/e4f7eb78b5a205980107db19be2a63c8d7009856) | https://issues.redhat.com/browse/KEYCLOAK-13256 |
| KEYCLOAK-13036 | [[KEYCLOAK-13036] Fix KeycloakElytronCSVaultTest failures on IBM JDK  - credential store is generated on the fly for the test, avoiding incompatibilities between implementations of keystores](https://github.com/keycloak/keycloak/commit/8c627fdb20435b565e18c384a927d4d59254ddfe) | https://issues.redhat.com/browse/KEYCLOAK-13036 |
| KEYCLOAK-5162 | [KEYCLOAK-5162 Add index to even table](https://github.com/keycloak/keycloak/commit/aece5d1b4cb27bf7fa6a70c54f759d9f7e4fe709) | https://issues.redhat.com/browse/KEYCLOAK-5162 |
| KEYCLOAK-11282 | [[KEYCLOAK-11282] - Properly resolve config resolver](https://github.com/keycloak/keycloak/commit/84d099e48f95c4ab04abc6b5e215e270627083d0) | https://issues.redhat.com/browse/KEYCLOAK-11282 |
| KEYCLOAK-11412 | [KEYCLOAK-11412 Display more nice error message when creating top level group with same name](https://github.com/keycloak/keycloak/commit/56d1ab19a8449a64fdf6f9ccd8fe6f5b48bae683) | https://issues.redhat.com/browse/KEYCLOAK-11412 |
| KEYCLOAK-12869 | [KEYCLOAK-12869 REST sends credential type when no credential exists and credential disabled](https://github.com/keycloak/keycloak/commit/d7688f6b12df2fb9f3bbe85283dae9846341dc26) | https://issues.redhat.com/browse/KEYCLOAK-12869 |
| KEYCLOAK-9782 | [KEYCLOAK-9782: Do not allow duplicate group name when updating](https://github.com/keycloak/keycloak/commit/1f1ed36b71ff41ff0a19e3588e487ea332e66762) | https://issues.redhat.com/browse/KEYCLOAK-9782 |
| KEYCLOAK-12881 | [KEYCLOAK-12881 KEYCLOAK-13099 Update FederatedIdentities and Groups on POST](https://github.com/keycloak/keycloak/commit/8774a0f4baef7d6840768d617c24e39c6108e4aa) | https://issues.redhat.com/browse/KEYCLOAK-12881 |
| KEYCLOAK-12344 | [KEYCLOAK-12344 Update examples version](https://github.com/keycloak/keycloak/commit/ec1c21efe9d570fc86ac620e83ba8727a67ee4d6) | https://issues.redhat.com/browse/KEYCLOAK-12344 |
| KEYCLOAK-13174 | [KEYCLOAK-13174 Not possible to delegate creating or deleting OTP credential to userStorage](https://github.com/keycloak/keycloak/commit/72e4690248a28c8296c78e1fa95726877f894b8f) | https://issues.redhat.com/browse/KEYCLOAK-13174 |
| KEYCLOAK-12876 | [KEYCLOAK-12876 KEYCLOAK-13148 KEYCLOAK-13149 KEYCLOAK-13151 Re-introduce some changes to preserve UserStorage SPI backwards compatibility. Added test for backwards compatibility of user storage](https://github.com/keycloak/keycloak/commit/803f398dba025de20f3810bd557a39da360cab92) | https://issues.redhat.com/browse/KEYCLOAK-12876 |
| KEYCLOAK-13186 | [KEYCLOAK-13186 Remove role information from RefreshTokens](https://github.com/keycloak/keycloak/commit/cd51ff34749289a5ee27b3b9af330431d756132d) | https://issues.redhat.com/browse/KEYCLOAK-13186 |
| KEYCLOAK-12579 | [KEYCLOAK-12579: LDAP groups duplicated during UI listing of user groups](https://github.com/keycloak/keycloak/commit/ad3b9fc3898f31408c54ffd3bdf0e62a4be7bce2) | https://issues.redhat.com/browse/KEYCLOAK-12579 |
| KEYCLOAK-10029 | [KEYCLOAK-10029 Offline token migration fix. Always test offline-token migration when run MigrationTest](https://github.com/keycloak/keycloak/commit/bc1146ac2f0d3c6d96541908d315095f4757ab6a) | https://issues.redhat.com/browse/KEYCLOAK-10029 |
| KEYCLOAK-13237 | [KEYCLOAK-13237 Allow look ahead window set to 0 for otp policy](https://github.com/keycloak/keycloak/commit/db265200467114491ab6fbd525bff16fc1e65cee) | https://issues.redhat.com/browse/KEYCLOAK-13237 |
| KEYCLOAK-11345 | [[KEYCLOAK-11345] - Test basic features of Keycloak.X with current tetsuite](https://github.com/keycloak/keycloak/commit/b7a395a3efba785bae903975603f952d18564ffd) | https://issues.redhat.com/browse/KEYCLOAK-11345 |
| KEYCLOAK-13233 | [KEYCLOAK-13233 Fix missing text-security files](https://github.com/keycloak/keycloak/commit/097a9b6e2e2fd3687df76aab4483f362abb45686) | https://issues.redhat.com/browse/KEYCLOAK-13233 |
| KEYCLOAK-13253 | [KEYCLOAK-13253 read rpId from policy in WebAuthnAuthenticator](https://github.com/keycloak/keycloak/commit/2b35321b7c1a7e4de7ab268e3fd327f82970ecdf) | https://issues.redhat.com/browse/KEYCLOAK-13253 |
| KEYCLOAK-11808 | [KEYCLOAK-11808 update testsuite to use current jdbc driver version for migration testing](https://github.com/keycloak/keycloak/commit/83461d033b149de2964913091822b63363b29385) | https://issues.redhat.com/browse/KEYCLOAK-11808 |
| KEYCLOAK-13163 | [KEYCLOAK-13163 Fixed searching for user with fine-grained permissions](https://github.com/keycloak/keycloak/commit/99aba3398078d72535cb72817b787ebdc91671da) | https://issues.redhat.com/browse/KEYCLOAK-13163 |
| KEYCLOAK-13069 | [KEYCLOAK-13069 Fix failing RH-SSO base tests](https://github.com/keycloak/keycloak/commit/8cfd4d60e6dd5acfd8d35bdd0255c5ef7f7e15e5) | https://issues.redhat.com/browse/KEYCLOAK-13069 |
| KEYCLOAK-13260 | [KEYCLOAK-13260 Fix "Test authentication" button for LDAP User Federation](https://github.com/keycloak/keycloak/commit/a840d6ff9ad98afd068e466eec54233de361072a) | https://issues.redhat.com/browse/KEYCLOAK-13260 |
| KEYCLOAK-11424 | [KEYCLOAK-11424 DBAllocatorUnavailableException](https://github.com/keycloak/keycloak/commit/e4baef41d12ab760bfa2991cea1910d36990dba9) | https://issues.redhat.com/browse/KEYCLOAK-11424 |
| KEYCLOAK-13074 | [KEYCLOAK-13074 Don't return LDAP group members if under IMPORT mode](https://github.com/keycloak/keycloak/commit/8aa5019efec30172edd6398edeb70e458446b6a4) | https://issues.redhat.com/browse/KEYCLOAK-13074 |
| KEYCLOAK-9851 | [KEYCLOAK-9851 Removed properties from realm json attributes that are included as fields](https://github.com/keycloak/keycloak/commit/ed97d40939599e5b875024bf2a0f682133497271) | https://issues.redhat.com/browse/KEYCLOAK-9851 |
| KEYCLOAK-13026 | [KEYCLOAK-13026 Set path of OAuth_Token_Request_State cookie to /](https://github.com/keycloak/keycloak/commit/967ff939ecde897a2d4b621fa5ed8bcf85317027) | https://issues.redhat.com/browse/KEYCLOAK-13026 |
| KEYCLOAK-12799 | [KEYCLOAK-12799 Missing Cancel button on The WebAuthn setup screen when using AIA](https://github.com/keycloak/keycloak/commit/a1bbab9eb20e93d1963f4b0e7e7b7b372d4c055e) | https://issues.redhat.com/browse/KEYCLOAK-12799 |
| KEYCLOAK-10330 | [KEYCLOAK-10330 Force Jackson2 provider to be used by Keycloak admin client, to prevent json-b provider taking over](https://github.com/keycloak/keycloak/commit/fae333750a8d2ef8b0577f5770a75cead795f565) | https://issues.redhat.com/browse/KEYCLOAK-10330 |
| KEYCLOAK-12885 | [KEYCLOAK-12885 Make sure empty protocol in client scope doesn't result in NPE in well-known endpoint](https://github.com/keycloak/keycloak/commit/b84160786b525ec07b2d4bae1b602991d31849e2) | https://issues.redhat.com/browse/KEYCLOAK-12885 |
| KEYCLOAK-13056 | [[KEYCLOAK-13056] - Searching clients with reduced permissions results in 403](https://github.com/keycloak/keycloak/commit/23b4aee445a1d8785f55cbfd24c98cba12828f06) | https://issues.redhat.com/browse/KEYCLOAK-13056 |
| KEYCLOAK-13175 | [[KEYCLOAK-13175] - Setting the enforcement mode when fetching lazily fetching resources](https://github.com/keycloak/keycloak/commit/30b07a1ff56a4f5e15d8dedc77eeaf08b46d6d21) | https://issues.redhat.com/browse/KEYCLOAK-13175 |
| KEYCLOAK-10967 | [KEYCLOAK-10967 Add JSON body methods for test ldap and smtp connections. Deprecate old form based methods.](https://github.com/keycloak/keycloak/commit/75a772f52b66d9d7deaf3b0226226a3ea139d393) | https://issues.redhat.com/browse/KEYCLOAK-10967 |
| KEYCLOAK-13102 | [KEYCLOAK-13102 Remove error log message on invalid response_type](https://github.com/keycloak/keycloak/commit/b39b84c5dcd69d89e756bee1d042b7fef0ef4829) | https://issues.redhat.com/browse/KEYCLOAK-13102 |
| KEYCLOAK-12968 | [KEYCLOAK-12968 fix ClientTest.getAllClientsSearchAndPagination for postgresql](https://github.com/keycloak/keycloak/commit/701fb06de164e3df01cd7050e0b0e133a0205af8) | https://issues.redhat.com/browse/KEYCLOAK-12968 |
| KEYCLOAK-12192 | [[KEYCLOAK-12192] - Missing Input Validation in IDP Authorization URLs](https://github.com/keycloak/keycloak/commit/2f489a41ebd06eb14197f8a66afae86ac1397f42) | https://issues.redhat.com/browse/KEYCLOAK-12192 |
| KEYCLOAK-13181 | [KEYCLOAK-13181 Fix NPE in EAP 6 adapter](https://github.com/keycloak/keycloak/commit/0cf09553181ef7465a9fa0bd07cefabbbcaaec6c) | https://issues.redhat.com/browse/KEYCLOAK-13181 |
| KEYCLOAK-9346 | [KEYCLOAK-9346 Add new KeycloakPromise to support native promises](https://github.com/keycloak/keycloak/commit/c1bf183998d9b111dad73506a440d1b0b44edc40) | https://issues.redhat.com/browse/KEYCLOAK-9346 |
| KEYCLOAK-13116 | [KEYCLOAK-13116 Fix backwards compatilbity changes in LocaleSelectorSPI](https://github.com/keycloak/keycloak/commit/bcb542d9cc4f5e06356efc8e054a00d8ba290796) | https://issues.redhat.com/browse/KEYCLOAK-13116 |
| KEYCLOAK-12749 | [KEYCLOAK-12749 single worker/IO thread, use OAUTH2 constants](https://github.com/keycloak/keycloak/commit/8ed355a5fefb0d0b4097bc68ea81010e8aead8e2) | https://issues.redhat.com/browse/KEYCLOAK-12749 |
| KEYCLOAK-12749 | [KEYCLOAK-12749 fix "invalid state" error due to IE requesting favicon](https://github.com/keycloak/keycloak/commit/22555371d83e2dd683d9f9a871b1a1832215ab8c) | https://issues.redhat.com/browse/KEYCLOAK-12749 |
| KEYCLOAK-12285 | [KEYCLOAK-12285 Add support for RestEasy 4 to admin client](https://github.com/keycloak/keycloak/commit/6978806a7e42bb87064c1786eaee73cfa19ccb3a) | https://issues.redhat.com/browse/KEYCLOAK-12285 |
| KEYCLOAK-12980 | [[KEYCLOAK-12980] Username not updated when "Email as username" is enabled](https://github.com/keycloak/keycloak/commit/dfb67c3aa419674230bb8e345c3583e0282138d8) | https://issues.redhat.com/browse/KEYCLOAK-12980 |
| KEYCLOAK-13119 | [KEYCLOAK-13119 Fixing migration to Keycloak 2.2.0+ to correctly preserve default identity provider](https://github.com/keycloak/keycloak/commit/1e0fcc488342b9ac9e5ebf090d0424b7c9d0237a) | https://issues.redhat.com/browse/KEYCLOAK-13119 |
| KEYCLOAK-11804 | [[KEYCLOAK-11804] - Block service accounts to authenticate or manage credentials](https://github.com/keycloak/keycloak/commit/49b1dbba68af0b387d8d5101847d17321605a1cf) | https://issues.redhat.com/browse/KEYCLOAK-11804 |
| KEYCLOAK-12612 | [[KEYCLOAK-12612][KEYCLOAK-12944] Fix validation of SAML destination URLs  - no longer compare them to the server absolutePath; instead use the base URI to build the validation URL](https://github.com/keycloak/keycloak/commit/3fa8a5aa887a3ff85db405bce1d0a84d1a507955) | https://issues.redhat.com/browse/KEYCLOAK-12612 |
| KEYCLOAK-11903 | [KEYCLOAK-11903 Test for XSW attacks](https://github.com/keycloak/keycloak/commit/f45f882f0c9565e6fb05f8fac4237b8734e2a8cf) | https://issues.redhat.com/browse/KEYCLOAK-11903 |
| KEYCLOAK-13167 | [KEYCLOAK-13167 - JDBC resource leak in custom migrations](https://github.com/keycloak/keycloak/commit/08319db24253762491defe330ea33f9d6f1f0f71) | https://issues.redhat.com/browse/KEYCLOAK-13167 |
| KEYCLOAK-12695 | [KEYCLOAK-12695 Upgrade to openshift-restclient-java 8.0.0.Final](https://github.com/keycloak/keycloak/commit/cec04fecc730b561e3a668995b3d9192c23f12bf) | https://issues.redhat.com/browse/KEYCLOAK-12695 |
| KEYCLOAK-12606 | [KEYCLOAK-12606 Add test](https://github.com/keycloak/keycloak/commit/df11a8a864ec80d69171602510418c48845e34f5) | https://issues.redhat.com/browse/KEYCLOAK-12606 |
| KEYCLOAK-13085 | [KEYCLOAK-13085 minor fixes](https://github.com/keycloak/keycloak/commit/1ca417c2c0990bf156dae6d828b0a6fb064bcd48) | https://issues.redhat.com/browse/KEYCLOAK-13085 |
| KEYCLOAK-13085 | [KEYCLOAK-13085 pt_BR messages for login and email](https://github.com/keycloak/keycloak/commit/80a95eb520d2474ca95cefa8d306bd18722a2925) | https://issues.redhat.com/browse/KEYCLOAK-13085 |
| KEYCLOAK-12450 | [KEYCLOAK-12450 Revert em.clear() call](https://github.com/keycloak/keycloak/commit/93f05f92917980c0c0a1a167ed6ad398623d597a) | https://issues.redhat.com/browse/KEYCLOAK-12450 |
| KEYCLOAK-10898 | [KEYCLOAK-10898 WildFly Adapter CLI based installation scripts](https://github.com/keycloak/keycloak/commit/7c91e36e43599a25b008c9b09afd3145c3f4da4d) | https://issues.redhat.com/browse/KEYCLOAK-10898 |
| KEYCLOAK-13161 | [KEYCLOAK-13161 Use iterator instead of for-each loop in ClientCredentialsProviderUtils](https://github.com/keycloak/keycloak/commit/8061aa5217a92dffd2c643f4cb643b388d8076e6) | https://issues.redhat.com/browse/KEYCLOAK-13161 |
| KEYCLOAK-12884 | [KEYCLOAK-12884 Add more tests for SameSite](https://github.com/keycloak/keycloak/commit/d3bebb47460b51014ae0ba2270bc6011f8977aba) | https://issues.redhat.com/browse/KEYCLOAK-12884 |
| KEYCLOAK-13113 | [KEYCLOAK-13113 Exclude tests for Tomcat](https://github.com/keycloak/keycloak/commit/9b81c42525001ed5d04eb6ee574cf20b60af65ff) | https://issues.redhat.com/browse/KEYCLOAK-13113 |
| KEYCLOAK-12817 | [KEYCLOAK-12817: Password form is stretched if IdP is configured](https://github.com/keycloak/keycloak/commit/c78087c3edcec7c33bf06d9d0aca2361e763a2d8) | https://issues.redhat.com/browse/KEYCLOAK-12817 |
| KEYCLOAK-13070 | [KEYCLOAK-13070 UserConsentWithUserStorageModelTest failing with ModelDuplicateException](https://github.com/keycloak/keycloak/commit/695fb922419ab02bcc449980b7b75f85d574ca92) | https://issues.redhat.com/browse/KEYCLOAK-13070 |
| KEYCLOAK-12816 | [KEYCLOAK-12816 Fix representation to model conversion](https://github.com/keycloak/keycloak/commit/aecfe251e49d511b66a951171ad66ff505f1805e) | https://issues.redhat.com/browse/KEYCLOAK-12816 |
| KEYCLOAK-12640 | [[KEYCLOAK-12640] Client authorizationSettings.decisionStrategy value lost on realm import](https://github.com/keycloak/keycloak/commit/85d72162284766e85945abc8db0378e37638f236) | https://issues.redhat.com/browse/KEYCLOAK-12640 |
| KEYCLOAK-13111 | [KEYCLOAK-13111 Move execution of db-allocator-plugin to jpa profile](https://github.com/keycloak/keycloak/commit/f1e54455e7849fce02449740bce4fb5bb66fd91c) | https://issues.redhat.com/browse/KEYCLOAK-13111 |
| KEYCLOAK-13096 | [KEYCLOAK-13096 Add compile scope hamcrest dependency to springboot tests](https://github.com/keycloak/keycloak/commit/9f3a6de453cab43004102a750ed3e8d74fe2b238) | https://issues.redhat.com/browse/KEYCLOAK-13096 |
| KEYCLOAK-12979 | [KEYCLOAK-12979 Fix group-attribute parsing](https://github.com/keycloak/keycloak/commit/3db55727ca3ac79de2b88edd07e5b5e7691cbe22) | https://issues.redhat.com/browse/KEYCLOAK-12979 |
| KEYCLOAK-13097 | [KEYCLOAK-13097 fix UserStorageTest - add cleanup after test](https://github.com/keycloak/keycloak/commit/e2bd99e9e40b5de9b03db4edebcba956ae8ca4aa) | https://issues.redhat.com/browse/KEYCLOAK-13097 |
| KEYCLOAK-10673 | [KEYCLOAK-10673 updated text-security to 2.0](https://github.com/keycloak/keycloak/commit/b19355dd76be1c8aa857af40ad242d03a1b9d4ba) | https://issues.redhat.com/browse/KEYCLOAK-10673 |
| KEYCLOAK-13060 | [KEYCLOAK-13060 - Use CDI transaction manager](https://github.com/keycloak/keycloak/commit/8c6f926ccb7e5d3e8c41afc5f9d7bccad17a2e48) | https://issues.redhat.com/browse/KEYCLOAK-13060 |
| KEYCLOAK-11335 | [KEYCLOAK-11335 - Use Agroal DataSource](https://github.com/keycloak/keycloak/commit/5b86886eeb3436c386f21463ce21eaa728d30064) | https://issues.redhat.com/browse/KEYCLOAK-11335 |
| KEYCLOAK-12794 | [[KEYCLOAK-12794] - Missing id token checks in oidc broker](https://github.com/keycloak/keycloak/commit/a830818a8446ff9102a629666f14f13cdc4af289) | https://issues.redhat.com/browse/KEYCLOAK-12794 |
| KEYCLOAK-11155 | [KEYCLOAK-11155 split on first '=' instead of all](https://github.com/keycloak/keycloak/commit/8297c0c878946c1eaf47f5757a0c654a5182a196) | https://issues.redhat.com/browse/KEYCLOAK-11155 |
| KEYCLOAK-11129 | [KEYCLOAK-11129 coalesce possible null values](https://github.com/keycloak/keycloak/commit/93a1374558643ee31e717c1dfacecb8ab8d95f68) | https://issues.redhat.com/browse/KEYCLOAK-11129 |
| KEYCLOAK-10953 | [KEYCLOAK-10953 Avoid NPE when Updating Clients via Admin REST API](https://github.com/keycloak/keycloak/commit/469bca624bc9fca6c0eb8ac0c56a3f5491d0a0a7) | https://issues.redhat.com/browse/KEYCLOAK-10953 |
| KEYCLOAK-7961 | [KEYCLOAK-7961 Avoid sending back-channel logout requests to disabled clients](https://github.com/keycloak/keycloak/commit/f426ed6de63961b028d0da09f972cd98989d7628) | https://issues.redhat.com/browse/KEYCLOAK-7961 |
| KEYCLOAK-12689 | [KEYCLOAK-12689 - (tests)](https://github.com/keycloak/keycloak/commit/e134cae795e3143a9c740f966a3a61cf90d97b5c) | https://issues.redhat.com/browse/KEYCLOAK-12689 |
| KEYCLOAK-12689 | [KEYCLOAK-12689 - Improvements for camelCase config properties](https://github.com/keycloak/keycloak/commit/e6b4685659840b339366658415660edd3f5f4edf) | https://issues.redhat.com/browse/KEYCLOAK-12689 |
| KEYCLOAK-13068 | [KEYCLOAK-13068 - Upgrade to Quarkus 1.2.1.Final](https://github.com/keycloak/keycloak/commit/b7b78c87cab6975a137aab236db81b4b3f6c2a21) | https://issues.redhat.com/browse/KEYCLOAK-13068 |
| KEYCLOAK-11576 | [[KEYCLOAK-11576] - Properly handling redirect_uri parser errors](https://github.com/keycloak/keycloak/commit/1c71eb93db77f2f3fd7d5f8a5ce803b5250a93b1) | https://issues.redhat.com/browse/KEYCLOAK-11576 |
| KEYCLOAK-13054 | [KEYCLOAK-13054 Unblock temporarily disabled user on password reset, and remove invalid error message](https://github.com/keycloak/keycloak/commit/950eae090f3b8be8c284872f970ed44aad439b3f) | https://issues.redhat.com/browse/KEYCLOAK-13054 |
| KEYCLOAK-12635 | [KEYCLOAK-12635 KEYCLOAK-12935 KEYCLOAK-13023 UI test fixes](https://github.com/keycloak/keycloak/commit/de8ba75399209121f4238aef567795c1c4e7c938) | https://issues.redhat.com/browse/KEYCLOAK-12635 |
| KEYCLOAK-12958 | [KEYCLOAK-12958 Preview feature profile for WebAuthn (#6780)](https://github.com/keycloak/keycloak/commit/eaaff6e55578501256c8b55617213fafa2be3d3e) | https://issues.redhat.com/browse/KEYCLOAK-12958 |
| KEYCLOAK-12962 | [KEYCLOAK-12962 Enforce 3.6.0 maven version for deploy phase](https://github.com/keycloak/keycloak/commit/8436a880755a7166741d572b7a803e0417fdb909) | https://issues.redhat.com/browse/KEYCLOAK-12962 |
| KEYCLOAK-12899 | [KEYCLOAK-12899 Fix incorrect exception message in JWE](https://github.com/keycloak/keycloak/commit/6eef8b5dd41afcafc49bd07980b00312904067a3) | https://issues.redhat.com/browse/KEYCLOAK-12899 |
| KEYCLOAK-13041 | [KEYCLOAK-13041 Upgrade to EAP 7.3.0.CR4](https://github.com/keycloak/keycloak/commit/cae46d84435f3c1791418bd9d2ab3e789274803f) | https://issues.redhat.com/browse/KEYCLOAK-13041 |
| KEYCLOAK-12826 | [KEYCLOAK-12826 WebAuthn fails to login user when their security key supports "user handle"](https://github.com/keycloak/keycloak/commit/5db98a58d3714b009bfdaa51bba43f5186925439) | https://issues.redhat.com/browse/KEYCLOAK-12826 |
| KEYCLOAK-8044 | [KEYCLOAK-8044 Clear theme caches on hot-deploy](https://github.com/keycloak/keycloak/commit/9e4702211651c66187e0394fbaaa8eef7cca5f74) | https://issues.redhat.com/browse/KEYCLOAK-8044 |
| KEYCLOAK-12268 | [KEYCLOAK-12268 Show page not found for /account/log if events are disabled for the realm](https://github.com/keycloak/keycloak/commit/d8d81ee1626563b86e9ff1dea3e7a438457c2e11) | https://issues.redhat.com/browse/KEYCLOAK-12268 |
| KEYCLOAK-11700 | [KEYCLOAK-11700 Lower-case passwords before checking with password blacklist](https://github.com/keycloak/keycloak/commit/9a3a358b964e76b476bb1a1c4b94623fb574adc8) | https://issues.redhat.com/browse/KEYCLOAK-11700 |
| KEYCLOAK-13032 | [KEYCLOAK-13032 Add no cache headers to account form service](https://github.com/keycloak/keycloak/commit/06576a44c965e85214b4dbdbd6e488d2d1eb8feb) | https://issues.redhat.com/browse/KEYCLOAK-13032 |
| KEYCLOAK-12597 | [KEYCLOAK-12597 Fix admin console with base theme](https://github.com/keycloak/keycloak/commit/04903666d1921a185f7f316723390903dc63a16b) | https://issues.redhat.com/browse/KEYCLOAK-12597 |
| KEYCLOAK-12960 | [KEYCLOAK-12960 Use Long for time based values in JsonWebToken](https://github.com/keycloak/keycloak/commit/536824beb65bc36d7218870f6550d155fec11b18) | https://issues.redhat.com/browse/KEYCLOAK-12960 |
| KEYCLOAK-12969 | [KEYCLOAK-12969 Don't use GenericFilter in server-authz test application](https://github.com/keycloak/keycloak/commit/167f73f54e733beeeb052ee74f0d8fe8808f530a) | https://issues.redhat.com/browse/KEYCLOAK-12969 |
| KEYCLOAK-12612 | [[KEYCLOAK-12612][KEYCLOAK-12944] Fix validation of SAML destination URLs  - no longer compare them to the server absolutePath; instead use the base URI to build the validation URL](https://github.com/keycloak/keycloak/commit/7a3998870ca71ffdf94b491f7f105dfc7f24649b) | https://issues.redhat.com/browse/KEYCLOAK-12612 |
| KEYCLOAK-12858 | [KEYCLOAK-12858 Authenticator is sometimes required even when configured as alternative](https://github.com/keycloak/keycloak/commit/eeeaafb5e7c7ae253bd2481c4837d1eb59bdcfcf) | https://issues.redhat.com/browse/KEYCLOAK-12858 |
| KEYCLOAK-12926 | [KEYCLOAK-12926 Improve Locale based message lookup](https://github.com/keycloak/keycloak/commit/67ddd3b0ebdccedcb1006f1d9c06391e8b64e2e0) | https://issues.redhat.com/browse/KEYCLOAK-12926 |
| KEYCLOAK-13003 | [KEYCLOAK-13003 Remove a mention about providers directory](https://github.com/keycloak/keycloak/commit/21b12c39bd4508e9c69e7633b64a051fb95d9170) | https://issues.redhat.com/browse/KEYCLOAK-13003 |

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

## 8.0.2
[Changelog](https://github.com/keycloak/keycloak/compare/8.0.1...8.0.2)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |
| KEYCLOAK-12877 | [KEYCLOAK-12877 Fix ModelVersion for testing pipeline](https://github.com/keycloak/keycloak/commit/87c73c3ece7ba2ec427c4abbd8ebccccd0204e82) | https://issues.redhat.com/browse/KEYCLOAK-12877 |
| KEYCLOAK-12648 | [KEYCLOAK-12648 Introduce SameSite attribute in cookies](https://github.com/keycloak/keycloak/commit/6f5f76d7020cbb7db977159a6511872303fe376f) | https://issues.redhat.com/browse/KEYCLOAK-12648 |
| KEYCLOAK-12439 | [KEYCLOAK-12439 Update node_modules folder](https://github.com/keycloak/keycloak/commit/8e8fde37fdfabfbc9cebb91fb7d568dc6bbe5f09) | https://issues.redhat.com/browse/KEYCLOAK-12439 |
| KEYCLOAK-12439 | [[KEYCLOAK-12439] Update to Angular 1.7.9](https://github.com/keycloak/keycloak/commit/4c577a485d2a350bd51ce07cc155c485184bc06d) | https://issues.redhat.com/browse/KEYCLOAK-12439 |
| KEYCLOAK-12190 | [KEYCLOAK-12190 Add validation for client root and base URLs](https://github.com/keycloak/keycloak/commit/05cd4fb39464cb466abb16aecd2aa49a58d5ade5) | https://issues.redhat.com/browse/KEYCLOAK-12190 |
| KEYCLOAK-12278 | [KEYCLOAK-12278 Default first broker login flow is broken after migration (#252)](https://github.com/keycloak/keycloak/commit/49f9a2bfbc5df9f3b5d2a0e3d0e67d2b9b8b97c4) | https://issues.redhat.com/browse/KEYCLOAK-12278 |
| KEYCLOAK-9563 | [KEYCLOAK-9563 Improve access token checks for userinfo endpoint](https://github.com/keycloak/keycloak/commit/fe3211c871566098c6475c37aebf43a42388a024) | https://issues.redhat.com/browse/KEYCLOAK-9563 |
| KEYCLOAK-12571 | [KEYCLOAK-12571 upgrading xstream to newer version](https://github.com/keycloak/keycloak/commit/3aeb70357ace7164cfb14ba0c4ab8ea548ce2848) | https://issues.redhat.com/browse/KEYCLOAK-12571 |
| KEYCLOAK-12228 | [KEYCLOAK-12228 Sensitive Data Exposure from patch of hiba haddad haddadhiba0@gmail.com](https://github.com/keycloak/keycloak/commit/5c549575bdc91de6e6b8e7848f0ac8cb2f975e0b) | https://issues.redhat.com/browse/KEYCLOAK-12228 |
| KEYCLOAK-12193 | [KEYCLOAK-12193 Internal error message returned in error response](https://github.com/keycloak/keycloak/commit/514b5e10238fccbf613abb8fa3dff4d1c9ff809c) | https://issues.redhat.com/browse/KEYCLOAK-12193 |

## 8.0.1
[Changelog](https://github.com/keycloak/keycloak/compare/8.0.0...8.0.1)

| Ticket-ID | Commit | Issue-ID |
| --- | --- | --- |
| KEYCLOAK-12242 | [KEYCLOAK-12242 KEYCLOAK-12280](https://github.com/keycloak/keycloak/commit/6f47d7fc2ccab4f31e373774c983501e83dffa4b) | https://issues.redhat.com/browse/KEYCLOAK-12242 |
| KEYCLOAK-12239 | [KEYCLOAK-12239 [REL] Upgrade to WildFly 18.0.1](https://github.com/keycloak/keycloak/commit/b4dde095e2970c3ed024aa28c127f7fe82b02169) | https://issues.redhat.com/browse/KEYCLOAK-12239 |

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
