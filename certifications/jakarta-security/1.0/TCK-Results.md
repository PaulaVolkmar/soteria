TCK Results
===========

As required by the
[Eclipse Foundation Technology Compatibility Kit License](https://www.eclipse.org/legal/tck.php),
following is a summary of the TCK results for releases of Jakarta Security.

# 1.0 Certification Request

- [x] Organization Name ("Organization") and, if applicable, URL\
  Eclipse Foundation
- [x] Product Name, Version and download URL (if applicable)\
  [Soteria 1.0.1](https://repo1.maven.org/maven2/org/glassfish/soteria/jakarta.security.enterprise/1.0.1/)
- [x] Specification Name, Version and download URL\
   [Jakarta Security 1.0](https://jakarta.ee/specifications/security/1.0/)
- [x] TCK Version, digital SHA-256 fingerprint and download URL\
  [Jakarta Security TCK 1.0.0](http://download.eclipse.org/ee4j/jakartaee-tck/jakartaee8-eftl/promoted/eclipse-security-tck-1.0.0.zip), SHA-256: 309111f000afb682f631a99d86a52bc8a8ab6f27dbed496387d5752e1a6647b4
- [x] Public URL of TCK Results Summary\
  [TCK results summary](https://eclipse-ee4j.github.io/soteria/certifications/jakarta-security/1.0/TCK-Results)
- [x] Any Additional Specification Certification Requirements\
  None
- [x] Java runtime used to run the implementation\
  Oracle JDK 1.8.0_202
- [x] Summary of the information for the certification environment, operating system, cloud, ...\
  Linux
- [x] By checking this box I acknowledge that the Organization I represent accepts the terms of the [EFTL](https://www.eclipse.org/legal/tck.php).
- [x] By checking this box I attest that all TCK requirements have been met, including any compatibility rules.



Test results:

```
[javatest.batch] Number of Tests Passed      = 85
[javatest.batch] Number of Tests Failed      = 0
[javatest.batch] Number of Tests with Errors = 0
[javatest.batch] ********************************************************************************
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/autoapplysession/Client.java#testAutoApplySession
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/basic/Client.java#testBasicHAMHasCorrectQualifier
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/basic/Client.java#testBasicHAMValidateRequest
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/basic/Client.java#testBasicHAMValidateRequest_wrongPassword
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/customform/base/Client.java#testCustomFormHAMHasCorrectQualifier
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/customform/base/Client.java#testCustomFormHAMValidateRequest
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/customform/base/Client.java#testCustomFormLoginToContinueErrorPage
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/customform/base/Client.java#testLoginToContinueuseRedirectToLogin
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/customform/expression/Client.java#testLoginToContinueuseForwardToLoginExpression
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/form/Client.java#testFormHAMHasCorrectQualifier
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/form/Client.java#testFormHAMValidateRequest
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/form/Client.java#testLoginToContinueerrorPage
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/form/Client.java#testLoginToContinueLoginPage
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/rememberme/test1/Client.java#testRememberMecookieHttpOnly
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/rememberme/test1/Client.java#testRememberMecookieMaxAgeSeconds
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/rememberme/test1/Client.java#testRememberMeCookieNameandisRememberMeExpression
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/rememberme/test2/Client.java#testRememberMecookieHttpOnlyFalse
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/rememberme/test2/Client.java#testRememberMecookieSecureOnly
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/rememberme/test3/Client.java#testRememberMecookieHttpOnlyExpression
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/rememberme/test3/Client.java#testRememberMecookieMaxAgeSecondsExpression
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/rememberme/test3/Client.java#testRememberMecookieSecureOnlyExpression
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/rememberme/test3/Client.java#testRememberMeisRememberMe
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/sam/obtainbean/Client.java#testSAMObtainBean
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/workflow/cleansubject/Client.java#testHAMCleanSubject
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/workflow/secureresponse/Client.java#testHAMSecureResponse
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/workflow/validaterequest/Client.java#testCallValidateRequestBeforeService
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/workflow/validaterequestduringauthen/Client.java#testCallValidateRequestDuringAuthenticate
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/ham/workflow/validaterequestwithfilter/Client.java#testCallValidateRequestBeforeFilter
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/basic/Client.java#testIdentityStoreInstall
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/customhandler/Client.java#testIdentityStore_customHandler
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/database/basic/Client.java#testAnnotationDBIDStore_Basic
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/database/hashalgorithm/Client.java#testAnnotationDBIDStore_HashAlgorithmDefault
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/database/hashalgorithmparam/Client.java#testAnnotationDBIDStore_HashAlgorithmParam
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/database/invalidcallerquery/Client.java#testAnnotationDBIDStore_Invalidcallerquery
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/database/invaliddatasource/Client.java#testAnnotationDBIDStore_Invaliddatasource
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/database/invalidgroupsquery/Client.java#testAnnotationDBIDStore_Invalidgroupsquery
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/database/invalidhashalgorithmparam/Client.java#testAnnotationDBIDStore_InvalidHashAlgorithmParam
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/database/invalidpriorityuseforexpr/Client.java#testAnnotationDBIDStore_invalidpriorityuseforexpr
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/database/multi/Client.java#testAnnotationDBIDStore_multi_withLdap
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/database/notvalidated/Client.java#testAnnotationDBIDStore_notValidated
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/database/priorityuseforexpr/Client.java#testAnnotationDBIDStore_priorityuseforexpr
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/database/priorityuseforexprbean/Client.java#testAnnotationDBIDStore_priorityuseforexprbean
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/database/useforgroup/Client.java#testAnnotationDBIDStore_useforgroup
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/database/useforvalidation/Client.java#testAnnotationDBIDStore_useforvalidation
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/idstorepermission/Client.java#testIdentityStore_customHandlerWithoutIDStorePermission
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/basic/Client.java#testAnnotationLdapIDStore_Basic
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/binddn/Client.java#testAnnotationLdapIDStore_Binddn
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/groupmemberof/Client.java#testAnnotationLdapIDStore_groupMemberOf
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/groupmemberofnotexist/Client.java#testAnnotationLdapIDStore_groupMemberOfNotExist
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/invalidbinddn/Client.java#testAnnotationLdapIDStore_invalidBinddn
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/invalidbinddnpassword/Client.java#testAnnotationLdapIDStore_invalidBinddnPassword
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/invalidcallerbasedn/Client.java#testAnnotationLdapIDStore_invalidCallerBasedn
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/invalidcallernameattr/Client.java#testAnnotationLdapIDStore_invalidCallerNameAttribute
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/invalidcallersearchbase/Client.java#testAnnotationLdapIDStore_invalidCallerSearchBase
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/invalidcallersearchfilter/Client.java#testAnnotationLdapIDStore_invalidCallerSearchFilter
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/invalidgroupmemberattr/Client.java#testAnnotationLdapIDStore_invalidGroupMemberAttribute
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/invalidgroupnameattr/Client.java#testAnnotationLdapIDStore_invalidGroupNameAttribute
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/invalidgroupsearchbase/Client.java#testAnnotationLdapIDStore_invalidGroupSearchBase
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/invalidgroupsearchfilter/Client.java#testAnnotationLdapIDStore_invalidGroupSearchFilter
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/invalidsearchscopeexpr/Client.java#testAnnotationLdapIDStore_invalidsearchScopeExpression
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/invalidurl/Client.java#testAnnotationLdapIDStore_invalidURL
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/notvalidated/Client.java#testAnnotationLdapIDStore_NotValidated
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/priorityuseforexpr/Client.java#testIdentityStore_ldap_priorityuseforexpr
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/searchscopebothonelevel/Client.java#testAnnotationLdapIDStore_searchScopeBothOneLevel
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/searchscopebothsubtree/Client.java#testAnnotationLdapIDStore_searchScopeBothSubTree
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/searchscopecalleronelevelgroupsubtree/Client.java#testAnnotationLdapIDStore_searchScopeCallerOneLevelGroupSubTree
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/searchscopecallersubtreegrouponelevel/Client.java#testAnnotationLdapIDStore_searchScopeCallerSubTreeGroupOneLevel
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/searchscopeexpr/Client.java#testAnnotationLdapIDStore_searchScopeExpression
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/useforgroup/Client.java#testIdentityStore_ldap_useforgroup
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/ldap/useforvalidation/Client.java#testIdentityStore_ldap_useforvalidation
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/multi/Client.java#testIdentityStoreValidate_multiIDStore
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/multi/Client.java#testIdentityStoreValidate_multiIDStore_INVALID
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/multi/Client.java#testIdentityStoreValidate_multiIDStore_INVALIDWithNOTVALIDATED
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/multi/Client.java#testIdentityStoreValidate_multiIDStore_NOTVALIDATED
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/multiauthz/Client.java#testIdentityStore_getGroups_multiGroupStore_highPriority_valid
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/multiauthz/Client.java#testIdentityStore_getGroups_multiGroupStore_lowerPriority_valid
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/useforgroup/Client.java#testIdentityStore_validationType_useforgroup
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/idstore/useforvalidation/Client.java#testIdentityStore_validationType_useforvalidation
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/securitycontext/authenticate/Client.java#testSecurityContextAuthenticate
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/securitycontext/authenticate/Client.java#testSecurityContextAuthenticate_wrongCredential
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/securitycontext/callerdata/Client.java#testSecurityContextHasAccessToWebResource
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/securitycontext/callerdata/Client.java#testSecurityContextIsCallerInRole
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/securitycontext/ejb/Client.java#testSecurityContextAvailableInEJB
[javatest.batch] PASSED........com/sun/ts/tests/securityapi/securitycontext/getprincipalsbytype/Client.java#testSecurityContextGetPrincipalsByType
[javatest.batch] PASSED........com/sun/ts/tests/signaturetest/securityapi/SecurityAPISigTest.java#signatureTest_from_standalone
[javatest.batch] 
[javatest.batch] Aug 2, 2019 10:01:55 PM Finished executing all tests, wait for cleanup...
[javatest.batch] Aug 2, 2019 10:01:55 PM Harness done with cleanup from test run.
[javatest.batch] Total time = 173s
[javatest.batch] Setup time = 0s
[javatest.batch] Cleanup time = 0s
[javatest.batch] Test results: passed: 85
```