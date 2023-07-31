- [x] Organization Name ("Organization") and, if applicable, URL:<br/>
     AsiaInfo
- [x] Product Name, Version and download URL (if applicable):<br/>
  [flyingserver-mp-v3.5.0](http://www.antdb.net/flyingserver)
- [x] Specification Name, Version and download URL:<br/>
  [microprofile-jwt-auth-1.2](https://download.eclipse.org/microprofile/microprofile-jwt-auth-1.2/microprofile-jwt-auth-spec-1.2.html)
- [x] Public URL of TCK Results Summary:<br/>
  [flyingserver microprofile-jwt-auth-1.2 TCK Result](https://github.com/AsiainfoAnhui/aisware_flyingserver_v2_ee8/blob/master/MicroProfile/TCK_result/mp4.1/microprofile-jwt-auth-1.2/TCK_Result.MD)
- [x] Any Additional Specification Certification Requirements:<br/>
  Not Applicable
- [x] Java runtime used to run the implementation:<br/>
   java8 (OpenJDK Runtime Environment (build 1.8.0_372-b07))
- [x] Summary of the information for the certification environment, operating system, cloud, ...:<br/>
   ubuntu-20.04.4
- [x] By checking this box I acknowledge that the Organization I represent accepts the terms of the [EFTL](https://www.eclipse.org/legal/tck.php).
- [x] By checking this box I attest that all TCK requirements have been met, including any compatibility rules.


Test results:
```xml
<?xml version="1.0" encoding="UTF-8"?>
<testsuites>
    <testsuite hostname="node1"  name="base-tests" tests="190" failures="0" timestamp="2023-07-17T11:26:22 CST" time="883.666" errors="0">
        <testcase name="testExpGrace" time="0.192" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsTest"/>
        <testcase name="testExpGraceDeprecated" time="0.013" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsTest"/>
        <testcase name="testFailAlgorithm" time="0.005" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsTest"/>
        <testcase name="testFailAlgorithmDeprecated" time="0.003" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsTest"/>
        <testcase name="testFailExpired" time="0.021" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsTest"/>
        <testcase name="testFailExpiredDeprecated" time="0.008" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsTest"/>
        <testcase name="testFailIssuer" time="0.009" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsTest"/>
        <testcase name="testFailIssuerDeprecated" time="0.006" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsTest"/>
        <testcase name="testFailJustExpired" time="0.006" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsTest"/>
        <testcase name="testFailJustExpiredDeprecated" time="0.007" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsTest"/>
        <testcase name="testFailSignature" time="0.251" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsTest"/>
        <testcase name="testFailSignatureDeprecated" time="0.172" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsTest"/>
        <testcase name="testSignedByECKeyVerifiedByRSKey" time="0.033" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsTest"/>
        <testcase name="testSignedByRSKeyVerifiedByECKey" time="0.008" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsTest"/>
        <testcase name="testValidToken" time="0.004" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsTest"/>
        <testcase name="testValidToken1024BitKeyLength" time="0.011" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsTest"/>
        <testcase name="testValidTokenDeprecated" time="0.005" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsTest"/>
        <testcase name="testValidTokenEC256" time="0.011" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsTest"/>
        <testcase name="testExpGrace" time="0.008" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsEncryptTest"/>
        <testcase name="testFailAlgorithm" time="0.004" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsEncryptTest"/>
        <testcase name="testFailEncryption" time="0.071" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsEncryptTest"/>
        <testcase name="testFailExpired" time="0.003" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsEncryptTest"/>
        <testcase name="testFailIssuer" time="0.004" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsEncryptTest"/>
        <testcase name="testFailJustExpired" time="0.004" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsEncryptTest"/>
        <testcase name="testValidToken" time="0.004" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsEncryptTest"/>
        <testcase name="testValidateSignedToken" time="0.003" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsEncryptTest"/>
        <testcase name="testEncryptECSignedClaims" time="0.01" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsSignEncryptTest"/>
        <testcase name="testEncryptSignedClaims" time="0.006" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsSignEncryptTest"/>
        <testcase name="testEncryptSignedClaimsWithoutCty" time="0.005" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsSignEncryptTest"/>
        <testcase name="testNestedSignedByECKeyVerifiedByRSKey" time="0.007" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsSignEncryptTest"/>
        <testcase name="testNestedSignedByRSKeyVerifiedByECKey" time="0.008" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsSignEncryptTest"/>
        <testcase name="testValidateEncryptedOnlyToken" time="0.005" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsSignEncryptTest"/>
        <testcase name="testValidateSignedToken" time="0.002" classname="org.eclipse.microprofile.jwt.tck.util.TokenUtilsSignEncryptTest"/>
        <testcase name="callEchoNoAuth" time="0.817" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.UnsecuredPingTest"/>
        <testcase name="verifyAudience" time="0.398" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RequiredClaimsTest"/>
        <testcase name="verifyExpiration" time="0.056" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RequiredClaimsTest"/>
        <testcase name="verifyIssuedAt" time="0.04" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RequiredClaimsTest"/>
        <testcase name="verifyIssuerClaim" time="0.059" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RequiredClaimsTest"/>
        <testcase name="verifyJTI" time="0.035" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RequiredClaimsTest"/>
        <testcase name="verifyOptionalAudience" time="0.036" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RequiredClaimsTest"/>
        <testcase name="verifySubClaim" time="0.031" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RequiredClaimsTest"/>
        <testcase name="verifyTokenWithIatOlderThanExp" time="0.041" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RequiredClaimsTest"/>
        <testcase name="verifyTokenWithoutExpiration" time="0.036" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RequiredClaimsTest"/>
        <testcase name="verifyTokenWithoutName" time="0.033" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RequiredClaimsTest"/>
        <testcase name="verifyUPN" time="0.041" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RequiredClaimsTest"/>
        <testcase name="verifyInjectedAudience" time="0.428" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ClaimValueInjectionTest"/>
        <testcase name="verifyInjectedAudienceStandard" time="0.062" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ClaimValueInjectionTest"/>
        <testcase name="verifyInjectedAuthTimeStandard" time="0.058" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ClaimValueInjectionTest"/>
        <testcase name="verifyInjectedCustomBoolean" time="0.041" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ClaimValueInjectionTest"/>
        <testcase name="verifyInjectedCustomDouble" time="0.041" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ClaimValueInjectionTest"/>
        <testcase name="verifyInjectedCustomInteger" time="0.04" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ClaimValueInjectionTest"/>
        <testcase name="verifyInjectedCustomString" time="0.032" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ClaimValueInjectionTest"/>
        <testcase name="verifyInjectedIssuedAt" time="0.026" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ClaimValueInjectionTest"/>
        <testcase name="verifyInjectedIssuedAtStandard" time="0.036" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ClaimValueInjectionTest"/>
        <testcase name="verifyInjectedJTI" time="0.046" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ClaimValueInjectionTest"/>
        <testcase name="verifyInjectedJTIStandard" time="0.042" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ClaimValueInjectionTest"/>
        <testcase name="verifyInjectedOptionalAuthTime" time="0.039" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ClaimValueInjectionTest"/>
        <testcase name="verifyInjectedOptionalCustomMissing" time="0.034" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ClaimValueInjectionTest"/>
        <testcase name="verifyInjectedOptionalSubject" time="0.023" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ClaimValueInjectionTest"/>
        <testcase name="verifyInjectedRawToken" time="0.026" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ClaimValueInjectionTest"/>
        <testcase name="verifyInjectedRawTokenStandard" time="0.029" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ClaimValueInjectionTest"/>
        <testcase name="verifyInjectedSubjectStandard" time="0.027" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ClaimValueInjectionTest"/>
        <testcase name="verifyIssuerClaim" time="0.025" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ClaimValueInjectionTest"/>
        <testcase name="verifyIssuerStandardClaim" time="0.025" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ClaimValueInjectionTest"/>
        <testcase name="verifyInjectedAudience" time="0.502" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyInjectedAudience2" time="0.064" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyInjectedAuthTime" time="0.042" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyInjectedAuthTime2" time="0.045" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyInjectedCustomDouble" time="0.043" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyInjectedCustomDouble2" time="0.054" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyInjectedCustomDoubleArray" time="0.043" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyInjectedCustomInteger" time="0.055" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyInjectedCustomInteger2" time="0.049" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyInjectedCustomIntegerArray" time="0.036" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyInjectedCustomString" time="0.037" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyInjectedCustomString2" time="0.036" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyInjectedCustomStringArray" time="0.032" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyInjectedIssuedAt" time="0.035" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyInjectedIssuedAt2" time="0.04" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyInjectedJTI" time="0.043" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyInjectedJTI2" time="0.045" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyInjectedRawToken" time="0.037" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyInjectedRawToken2" time="0.058" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyIssuerClaim" time="0.054" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyIssuerClaim2" time="0.076" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.JsonValueInjectionTest"/>
        <testcase name="verifyInjectedAudience" time="0.385" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyInjectedAudience2" time="0.038" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyInjectedCustomDouble" time="0.025" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyInjectedCustomDouble2" time="0.022" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyInjectedCustomInteger" time="0.022" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyInjectedCustomInteger2" time="0.038" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyInjectedCustomString" time="0.042" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyInjectedCustomString2" time="0.028" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyInjectedIssuedAt" time="0.053" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyInjectedIssuedAt2" time="0.024" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyInjectedJTI" time="0.027" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyInjectedJTI2" time="0.026" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyInjectedOptionalAuthTime" time="0.032" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyInjectedOptionalAuthTime2" time="0.025" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyInjectedOptionalCustomMissing" time="0.027" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyInjectedOptionalSubject" time="0.028" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyInjectedOptionalSubject2" time="0.026" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyInjectedRawToken" time="0.027" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyInjectedRawToken2" time="0.025" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyIssuerClaim" time="0.029" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="verifyIssuerClaim2" time="0.03" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ProviderInjectionTest"/>
        <testcase name="callEcho" time="0.395" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RolesAllowedTest"/>
        <testcase name="callEcho2" time="0.065" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RolesAllowedTest"/>
        <testcase name="callEchoBASIC" time="0.025" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RolesAllowedTest"/>
        <testcase name="callEchoNoAuth" time="0.027" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RolesAllowedTest"/>
        <testcase name="callEchoNoGroups" time="0.032" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RolesAllowedTest"/>
        <testcase name="callEchoSignEncryptToken" time="0.027" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RolesAllowedTest"/>
        <testcase name="callEchoSignToken" time="0.028" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RolesAllowedTest"/>
        <testcase name="callHeartbeat" time="0.074" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RolesAllowedTest"/>
        <testcase name="checkIsUserInRole" time="0.042" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RolesAllowedTest"/>
        <testcase name="checkIsUserInRoleToken2" time="0.043" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RolesAllowedTest"/>
        <testcase name="echoNeedsToken2Role" time="0.039" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RolesAllowedTest"/>
        <testcase name="echoWithToken2" time="0.215" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RolesAllowedTest"/>
        <testcase name="getInjectedPrincipal" time="0.026" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RolesAllowedTest"/>
        <testcase name="getPrincipalClass" time="0.05" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RolesAllowedTest"/>
        <testcase name="noTokenHeaderSetToCookie" time="0.025" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RolesAllowedTest"/>
        <testcase name="callEchoBadIssuer" time="0.237" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.InvalidTokenTest"/>
        <testcase name="callEchoBadSigner" time="0.213" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.InvalidTokenTest"/>
        <testcase name="callEchoBadSignerAlg" time="0.015" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.InvalidTokenTest"/>
        <testcase name="callEchoExpiredToken" time="0.015" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.InvalidTokenTest"/>
        <testcase name="verifyInjectedAudience" time="0.505" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.PrimitiveInjectionTest"/>
        <testcase name="verifyInjectedCustomBoolean" time="0.078" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.PrimitiveInjectionTest"/>
        <testcase name="verifyInjectedCustomString" time="0.044" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.PrimitiveInjectionTest"/>
        <testcase name="verifyInjectedExpiration" time="0.056" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.PrimitiveInjectionTest"/>
        <testcase name="verifyInjectedGroups" time="0.088" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.PrimitiveInjectionTest"/>
        <testcase name="verifyInjectedIssuedAt" time="0.07" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.PrimitiveInjectionTest"/>
        <testcase name="verifyInjectedJTI" time="0.068" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.PrimitiveInjectionTest"/>
        <testcase name="verifyInjectedRawToken" time="0.042" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.PrimitiveInjectionTest"/>
        <testcase name="verifyInjectedSUB" time="0.038" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.PrimitiveInjectionTest"/>
        <testcase name="verifyInjectedUPN" time="0.039" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.PrimitiveInjectionTest"/>
        <testcase name="verifyIssuerClaim" time="0.04" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.PrimitiveInjectionTest"/>
        <testcase name="verifyInjectedPrincipal" time="0.433" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.PrincipalInjectionTest"/>
        <testcase name="testRequiredAudMatch" time="0.432" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.AudValidationTest"/>
        <testcase name="testRequiredAudMatch" time="0.374" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.AudArrayValidationTest"/>
        <testcase name="testRequiredAudMismatchFailure" time="0.357" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.AudValidationBadAudTest"/>
        <testcase name="testRequiredAudMissingFailure" time="0.282" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.AudValidationMissingAudTest"/>
        <testcase name="verifyInjectedRawToken1Provider" time="0.407" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ApplicationScopedInjectionTest"/>
        <testcase name="verifyInjectedRawTokenClaimValue" time="0.04" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ApplicationScopedInjectionTest"/>
        <testcase name="verifyInjectedRawTokenJwt" time="0.061" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.ApplicationScopedInjectionTest"/>
        <testcase name="callEcho" time="0.422" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.RsaKeySignatureTest"/>
        <testcase name="testKeyAsPEM" time="0.654" classname="org.eclipse.microprofile.jwt.tck.config.PublicKeyAsPEMTest"/>
        <testcase name="testKeyAsLocationResource" time="0.385" classname="org.eclipse.microprofile.jwt.tck.config.PublicKeyAsPEMLocationTest"/>
        <testcase name="validateLocationUrlContents" time="0.235" classname="org.eclipse.microprofile.jwt.tck.config.PublicKeyAsPEMLocationURLTest"/>
        <testcase name="testKeyAsLocationUrl" time="0.169" classname="org.eclipse.microprofile.jwt.tck.config.PublicKeyAsPEMLocationURLTest"/>
        <testcase name="testKeyAsJWK" time="0.374" classname="org.eclipse.microprofile.jwt.tck.config.PublicKeyAsJWKTest"/>
        <testcase name="testKeyAsLocation" time="0.397" classname="org.eclipse.microprofile.jwt.tck.config.PublicKeyAsJWKLocationTest"/>
        <testcase name="validateLocationUrlContents" time="0.326" classname="org.eclipse.microprofile.jwt.tck.config.PublicKeyAsJWKLocationURLTest"/>
        <testcase name="testKeyAsLocationUrl" time="0.239" classname="org.eclipse.microprofile.jwt.tck.config.PublicKeyAsJWKLocationURLTest"/>
        <testcase name="testKeyAsJWKS" time="0.538" classname="org.eclipse.microprofile.jwt.tck.config.PublicKeyAsJWKSTest"/>
        <testcase name="testKeyAsLocation" time="0.537" classname="org.eclipse.microprofile.jwt.tck.config.PublicKeyAsJWKSLocationTest"/>
        <testcase name="testKeyAsBase64JWK" time="0.38" classname="org.eclipse.microprofile.jwt.tck.config.PublicKeyAsBase64JWKTest"/>
        <testcase name="testKeyAsLocationUrl" time="0.471" classname="org.eclipse.microprofile.jwt.tck.config.PublicKeyAsFileLocationURLTest"/>
        <testcase name="testKeyAsPEM" time="0.367" classname="org.eclipse.microprofile.jwt.tck.config.ECPublicKeyAsPEMTest"/>
        <testcase name="testKeyAsLocationResource" time="0.431" classname="org.eclipse.microprofile.jwt.tck.config.ECPublicKeyAsPEMLocationTest"/>
        <testcase name="testKeyAsLocation" time="0.525" classname="org.eclipse.microprofile.jwt.tck.config.ECPublicKeyAsJWKLocationTest"/>
        <testcase name="testRequiredIss" time="0.407" classname="org.eclipse.microprofile.jwt.tck.config.IssValidationTest"/>
        <testcase name="testNotRequiredIssMismatchFailure" time="0.457" classname="org.eclipse.microprofile.jwt.tck.config.IssValidationFailTest"/>
        <testcase name="emptyCookie" time="0.313" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.CookieTokenTest"/>
        <testcase name="expiredCookie" time="0.129" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.CookieTokenTest"/>
        <testcase name="ignoreHeaderIfCookieSet" time="0.03" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.CookieTokenTest"/>
        <testcase name="validCookieJwt" time="0.072" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.CookieTokenTest"/>
        <testcase name="wrongCookieName" time="0.018" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.CookieTokenTest"/>
        <testcase name="noTokenHeaderSetToCookie" time="0.278" classname="org.eclipse.microprofile.jwt.tck.config.TokenAsCookieIgnoredTest"/>
        <testcase name="validJwt" time="0.18" classname="org.eclipse.microprofile.jwt.tck.config.TokenAsCookieIgnoredTest"/>
        <testcase name="validJwt" time="0.385" classname="org.eclipse.microprofile.jwt.tck.config.TokenAsCookieTest"/>
        <testcase name="emptyToken" time="0.277" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.EmptyTokenTest"/>
        <testcase name="invalidToken" time="0.075" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.EmptyTokenTest"/>
        <testcase name="validToken" time="0.069" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.EmptyTokenTest"/>
        <testcase name="callEcho" time="0.416" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.jwe.RolesAllowedSignEncryptTest"/>
        <testcase name="callEcho2" time="0.07" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.jwe.RolesAllowedSignEncryptTest"/>
        <testcase name="callEchoBASIC" time="0.022" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.jwe.RolesAllowedSignEncryptTest"/>
        <testcase name="callEchoNoAuth" time="0.019" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.jwe.RolesAllowedSignEncryptTest"/>
        <testcase name="callEchoSignEncryptToken" time="0.018" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.jwe.RolesAllowedSignEncryptTest"/>
        <testcase name="callEchoSignToken" time="0.026" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.jwe.RolesAllowedSignEncryptTest"/>
        <testcase name="callEchoWithoutCty" time="0.025" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.jwe.RolesAllowedSignEncryptTest"/>
        <testcase name="callHeartbeat" time="0.015" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.jwe.RolesAllowedSignEncryptTest"/>
        <testcase name="checkIsUserInRole" time="0.023" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.jwe.RolesAllowedSignEncryptTest"/>
        <testcase name="checkIsUserInRoleToken2" time="0.04" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.jwe.RolesAllowedSignEncryptTest"/>
        <testcase name="echoNeedsToken2Role" time="0.033" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.jwe.RolesAllowedSignEncryptTest"/>
        <testcase name="echoWithToken2" time="0.029" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.jwe.RolesAllowedSignEncryptTest"/>
        <testcase name="getInjectedPrincipal" time="0.019" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.jwe.RolesAllowedSignEncryptTest"/>
        <testcase name="getPrincipalClass" time="0.02" classname="org.eclipse.microprofile.jwt.tck.container.jaxrs.jwe.RolesAllowedSignEncryptTest"/>
        <testcase name="testKeyAsLocationResource" time="0.472" classname="org.eclipse.microprofile.jwt.tck.config.jwe.PrivateKeyAsPEMClasspathTest"/>
        <testcase name="testKeyAsLocation" time="0.725" classname="org.eclipse.microprofile.jwt.tck.config.jwe.PrivateKeyAsJWKClasspathTest"/>
        <testcase name="testKeyAsLocation" time="0.504" classname="org.eclipse.microprofile.jwt.tck.config.jwe.PrivateKeyAsJWKSClasspathTest"/>
    </testsuite>
    <testsuite hostname="node1"  name="extended-tests" tests="6" failures="0" timestamp="2023-07-17T11:26:22 CST" time="0.05" errors="0">
        <testcase name="callEjbEcho" time="0.008" classname="org.eclipse.microprofile.jwt.tck.container.ejb.EjbTest"/>
        <testcase name="getSubjectClass" time="0.001" classname="org.eclipse.microprofile.jwt.tck.container.ejb.EjbTest"/>
        <testcase name="testEJBPrincipalClass" time="0.001" classname="org.eclipse.microprofile.jwt.tck.container.ejb.EjbTest"/>
        <testcase name="getSubjectClass" time="0.027" classname="org.eclipse.microprofile.jwt.tck.container.jacc.SubjectTest"/>
        <testcase name="getServletPrincipalClass" time="0.001" classname="org.eclipse.microprofile.jwt.tck.container.servlet.ServletTest"/>
        <testcase name="getServletSubjectClass" time="0.0" classname="org.eclipse.microprofile.jwt.tck.container.servlet.ServletTest"/>
    </testsuite>
</testsuites>
```