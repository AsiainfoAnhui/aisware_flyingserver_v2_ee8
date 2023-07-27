- [x] Organization Name ("Organization") and, if applicable, URL:<br/>
     AsiaInfo
- [x] Product Name, Version and download URL (if applicable):<br/>
  [flyingserver-micro-5.0.1](http://www.antdb.net/flyingserver)
- [x] Specification Name, Version and download URL:<br/>
  [microprofile-rest-client-2.0](https://download.eclipse.org/microprofile/microprofile-rest-client-2.0/microprofile-rest-client-spec-2.0.html)
- [x] Public URL of TCK Results Summary:<br/>
  [microprofile-rest-client-2.0 TCK Result](https://github.com/AsiainfoAnhui/aisware_flyingserver_v2_ee8/blob/master/MicroProfile/TCK_result/mp4.1/microprofile-rest-client-2.0/TCK_Result.MD)
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
    <testsuite hostname="node1" name="Surefire test" tests="182" failures="0" timestamp="2023-07-14T17:32:35 CST" time="1368.987" errors="0">
        <testcase name="sendsParamsSpecifiedInBeanParam" time="2.587" classname="org.eclipse.microprofile.rest.client.tck.BeanParamTest"/>
        <testcase name="test301Default" time="5.451" classname="org.eclipse.microprofile.rest.client.tck.FollowRedirectsTest"/>
        <testcase name="test301Follows" time="0.34" classname="org.eclipse.microprofile.rest.client.tck.FollowRedirectsTest"/>
        <testcase name="test302Default" time="0.25" classname="org.eclipse.microprofile.rest.client.tck.FollowRedirectsTest"/>
        <testcase name="test302Follows" time="0.398" classname="org.eclipse.microprofile.rest.client.tck.FollowRedirectsTest"/>
        <testcase name="test303Default" time="0.371" classname="org.eclipse.microprofile.rest.client.tck.FollowRedirectsTest"/>
        <testcase name="test303Follows" time="0.211" classname="org.eclipse.microprofile.rest.client.tck.FollowRedirectsTest"/>
        <testcase name="test307Default" time="0.188" classname="org.eclipse.microprofile.rest.client.tck.FollowRedirectsTest"/>
        <testcase name="test307Follows" time="0.257" classname="org.eclipse.microprofile.rest.client.tck.FollowRedirectsTest"/>
        <testcase name="testClientHeadersFactoryInvoked" time="2.117" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIClientHeadersFactoryTest"/>
        <testcase name="testInvokesPostOperation_viaAnnotation" time="4.411" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIInvokeWithRegisteredProvidersTest"/>
        <testcase name="testInvokesPostOperation_viaMPConfig" time="0.393" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIInvokeWithRegisteredProvidersTest"/>
        <testcase name="testInvokesPostOperation_viaMPConfigWithConfigKey" time="0.408" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIInvokeWithRegisteredProvidersTest"/>
        <testcase name="testInvokesPutOperation_viaAnnotation" time="0.34" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIInvokeWithRegisteredProvidersTest"/>
        <testcase name="testInvokesPutOperation_viaMPConfig" time="0.352" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIInvokeWithRegisteredProvidersTest"/>
        <testcase name="testInvokesPutOperation_viaMPConfigWithConfigKey" time="0.258" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIInvokeWithRegisteredProvidersTest"/>
        <testcase name="testConfigKeyUsedForUri" time="2.495" classname="org.eclipse.microprofile.rest.client.tck.cditests.ConfigKeyTest"/>
        <testcase name="testFullyQualifiedClassnamePropTakesPrecedenceOverConfigKey" time="0.325" classname="org.eclipse.microprofile.rest.client.tck.cditests.ConfigKeyTest"/>
        <testcase name="testCDIProviderSpecifiedInMPConfig" time="2.4" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIManagedProviderTest"/>
        <testcase name="testCDIProviderSpecifiedViaAnnotation" time="0.248" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIManagedProviderTest"/>
        <testcase name="testCDIProviderSpecifiedViaRestClientBuilder" time="0.286" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIManagedProviderTest"/>
        <testcase name="testInstanceProviderSpecifiedViaRestClientBuilderDoesNotUseCDIManagedProvider" time="0.32" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIManagedProviderTest"/>
        <testcase name="testInterceptorInvoked" time="1.786" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIInterceptorTest"/>
        <testcase name="testInterceptorNotInvokedWhenNoAnnotationApplied" time="0.14" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIInterceptorTest"/>
        <testcase name="arrayPairs" time="2.239" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIQueryParamStyleTest"/>
        <testcase name="commaSeparated" time="0.327" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIQueryParamStyleTest"/>
        <testcase name="defaultStyleIsMultiPair" time="0.535" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIQueryParamStyleTest"/>
        <testcase name="explicitMultiPair" time="0.499" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIQueryParamStyleTest"/>
        <testcase name="testBaseUriInRegisterRestClientAnnotation" time="4.048" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIURIvsURLConfigTest"/>
        <testcase name="testMPConfigURIOverridesBaseUriInRegisterRestClientAnnotation" time="0.336" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIURIvsURLConfigTest"/>
        <testcase name="testURItakesPrecedenceOverURL" time="1.003" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIURIvsURLConfigTest"/>
        <testcase name="testConfigKeyUsedForUri" time="2.13" classname="org.eclipse.microprofile.rest.client.tck.cditests.ConfigKeyForMultipleInterfacesTest"/>
        <testcase name="shouldFailedMutualSslWithoutSslContext" time="2.644" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslContextTest"/>
        <testcase name="shouldSucceedMutualSslWithValidSslContext" time="0.648" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslContextTest"/>
        <testcase name="shouldFailWithInvalidClientSignature" time="3.982" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslMutualTest"/>
        <testcase name="shouldFailWithInvalidClientSignatureCDI" time="1.163" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslMutualTest"/>
        <testcase name="shouldFailWithNoClientSignature" time="0.992" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslMutualTest"/>
        <testcase name="shouldFailWithNoClientSignatureCDI" time="0.738" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslMutualTest"/>
        <testcase name="shouldWorkWithClientSignature" time="0.979" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslMutualTest"/>
        <testcase name="shouldWorkWithClientSignatureCDI" time="0.99" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslMutualTest"/>
        <testcase name="shouldWorkWithClientSignatureFromClasspathCDI" time="0.921" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslMutualTest"/>
        <testcase name="testRequestFilterReturnsMethodInvoked" time="2.006" classname="org.eclipse.microprofile.rest.client.tck.InvokedMethodTest"/>
        <testcase name="testClientHeadersFactoryInvoked" time="2.163" classname="org.eclipse.microprofile.rest.client.tck.ClientHeadersFactoryTest"/>
        <testcase name="testRestClientListenerInvoked" time="1.893" classname="org.eclipse.microprofile.rest.client.tck.RestClientListenerTest"/>
        <testcase name="testNoExceptionThrownWhenDisabledDuringBuild" time="3.244" classname="org.eclipse.microprofile.rest.client.tck.DefaultExceptionMapperConfigTest"/>
        <testcase name="testComputedClientHeaderParamOnInterface" time="4.428" classname="org.eclipse.microprofile.rest.client.tck.ClientHeaderParamTest"/>
        <testcase name="testComputedClientHeaderParamOnMethod" time="0.27" classname="org.eclipse.microprofile.rest.client.tck.ClientHeaderParamTest"/>
        <testcase name="testComputedClientHeaderParamOnMethodOverridesClientHeaderParamOnInterface" time="0.223" classname="org.eclipse.microprofile.rest.client.tck.ClientHeaderParamTest"/>
        <testcase name="testExceptionInRequiredComputeMethodThrowsClientErrorException" time="0.116" classname="org.eclipse.microprofile.rest.client.tck.ClientHeaderParamTest"/>
        <testcase name="testExplicitClientHeaderParamOnInterface" time="0.162" classname="org.eclipse.microprofile.rest.client.tck.ClientHeaderParamTest"/>
        <testcase name="testExplicitClientHeaderParamOnMethod" time="0.165" classname="org.eclipse.microprofile.rest.client.tck.ClientHeaderParamTest"/>
        <testcase name="testExplicitClientHeaderParamOnMethodOverridesClientHeaderParamOnInterface" time="0.142" classname="org.eclipse.microprofile.rest.client.tck.ClientHeaderParamTest"/>
        <testcase name="testHeaderNotSentWhenExceptionThrownAndRequiredIsFalse" time="0.229" classname="org.eclipse.microprofile.rest.client.tck.ClientHeaderParamTest"/>
        <testcase name="testHeaderParamOverridesComputedClientHeaderParamOnInterface" time="0.169" classname="org.eclipse.microprofile.rest.client.tck.ClientHeaderParamTest"/>
        <testcase name="testHeaderParamOverridesComputedClientHeaderParamOnMethod" time="0.163" classname="org.eclipse.microprofile.rest.client.tck.ClientHeaderParamTest"/>
        <testcase name="testHeaderParamOverridesExplicitClientHeaderParamOnInterface" time="0.187" classname="org.eclipse.microprofile.rest.client.tck.ClientHeaderParamTest"/>
        <testcase name="testHeaderParamOverridesExplicitClientHeaderParamOnMethod" time="0.182" classname="org.eclipse.microprofile.rest.client.tck.ClientHeaderParamTest"/>
        <testcase name="testMultivaluedHeaderInterfaceExplicit" time="0.218" classname="org.eclipse.microprofile.rest.client.tck.ClientHeaderParamTest"/>
        <testcase name="testMultivaluedHeaderSentWhenInvokingComputeMethodFromSeparateClass" time="0.173" classname="org.eclipse.microprofile.rest.client.tck.ClientHeaderParamTest"/>
        <testcase name="testInvokesPostOperationWithRegisteredProviders" time="3.724" classname="org.eclipse.microprofile.rest.client.tck.InvokeWithBuiltProvidersTest"/>
        <testcase name="testInvokesPutOperationWithRegisteredProviders" time="0.23" classname="org.eclipse.microprofile.rest.client.tck.InvokeWithBuiltProvidersTest"/>
        <testcase name="shouldRegisterAMultiTypedProviderClass" time="1.703" classname="org.eclipse.microprofile.rest.client.tck.AdditionalRegistrationTest"/>
        <testcase name="shouldRegisterAMultiTypedProviderClassWithPriorities" time="0.07" classname="org.eclipse.microprofile.rest.client.tck.AdditionalRegistrationTest"/>
        <testcase name="shouldRegisterAMultiTypedProviderInstance" time="0.044" classname="org.eclipse.microprofile.rest.client.tck.AdditionalRegistrationTest"/>
        <testcase name="shouldRegisterAMultiTypedProviderInstanceWithPriorities" time="0.039" classname="org.eclipse.microprofile.rest.client.tck.AdditionalRegistrationTest"/>
        <testcase name="shouldRegisterInstance" time="0.058" classname="org.eclipse.microprofile.rest.client.tck.AdditionalRegistrationTest"/>
        <testcase name="shouldRegisterInstanceWithPriority" time="0.033" classname="org.eclipse.microprofile.rest.client.tck.AdditionalRegistrationTest"/>
        <testcase name="shouldRegisterProvidersWithPriority" time="0.036" classname="org.eclipse.microprofile.rest.client.tck.AdditionalRegistrationTest"/>
        <testcase name="testPropertiesRegistered" time="0.044" classname="org.eclipse.microprofile.rest.client.tck.AdditionalRegistrationTest"/>
        <testcase name="canInvokeMethodOnSubResourceInterface" time="2.026" classname="org.eclipse.microprofile.rest.client.tck.SubResourceTest"/>
        <testcase name="testConnectTimeout" time="9.736" classname="org.eclipse.microprofile.rest.client.tck.timeout.TimeoutTestBase"/>
        <testcase name="testReadTimeout" time="5.464" classname="org.eclipse.microprofile.rest.client.tck.timeout.TimeoutTestBase"/>
        <testcase name="testOverrideInterfaceAndProviderAnnotationOnBuilder" time="3.551" classname="org.eclipse.microprofile.rest.client.tck.MultiRegisteredTest"/>
        <testcase name="testOverrideProviderAnnotationOnBuilder" time="0.235" classname="org.eclipse.microprofile.rest.client.tck.MultiRegisteredTest"/>
        <testcase name="expectIllegalStateExceptionAfterAutoCloseableClose" time="1.822" classname="org.eclipse.microprofile.rest.client.tck.CloseTest"/>
        <testcase name="expectIllegalStateExceptionAfterCloseOnInterfaceThatExtendsAutoCloseable" time="0.162" classname="org.eclipse.microprofile.rest.client.tck.CloseTest"/>
        <testcase name="expectIllegalStateExceptionAfterCloseOnInterfaceThatExtendsCloseable" time="0.172" classname="org.eclipse.microprofile.rest.client.tck.CloseTest"/>
        <testcase name="expectIllegalStateExceptionAfterCloseableClose" time="0.156" classname="org.eclipse.microprofile.rest.client.tck.CloseTest"/>
        <testcase name="testInvokesPostOperationWithAnnotatedProviders" time="3.151" classname="org.eclipse.microprofile.rest.client.tck.InvokeWithRegisteredProvidersTest"/>
        <testcase name="testInvokesPutOperationWithAnnotatedProviders" time="0.297" classname="org.eclipse.microprofile.rest.client.tck.InvokeWithRegisteredProvidersTest"/>
        <testcase name="arrayPairs" time="2.075" classname="org.eclipse.microprofile.rest.client.tck.QueryParamStyleTest"/>
        <testcase name="commaSeparated" time="0.222" classname="org.eclipse.microprofile.rest.client.tck.QueryParamStyleTest"/>
        <testcase name="defaultStyleIsMultiPair" time="0.172" classname="org.eclipse.microprofile.rest.client.tck.QueryParamStyleTest"/>
        <testcase name="explicitMultiPair" time="0.17" classname="org.eclipse.microprofile.rest.client.tck.QueryParamStyleTest"/>
        <testcase name="testGetExecutionWithBuiltClient" time="3.592" classname="org.eclipse.microprofile.rest.client.tck.InvokeSimpleGetOperationTest"/>
        <testcase name="testExceptionThrownWhenClientHeaderParamComputeValueSpecifiesMethodWithInvalidSignature" time="1.851" classname="org.eclipse.microprofile.rest.client.tck.InvalidInterfaceTest"/>
        <testcase name="testExceptionThrownWhenClientHeaderParamComputeValueSpecifiesMissingMethod" time="0.121" classname="org.eclipse.microprofile.rest.client.tck.InvalidInterfaceTest"/>
        <testcase name="testExceptionThrownWhenInterfaceHasMethodWithMismatchedPathParameter" time="0.145" classname="org.eclipse.microprofile.rest.client.tck.InvalidInterfaceTest"/>
        <testcase name="testExceptionThrownWhenInterfaceHasMethodWithMissingPathParamAnnotation_templateDeclaredAtMethodLevel" time="0.1" classname="org.eclipse.microprofile.rest.client.tck.InvalidInterfaceTest"/>
        <testcase name="testExceptionThrownWhenInterfaceHasMethodWithMissingPathParamAnnotation_templateDeclaredAtTypeLevel" time="0.096" classname="org.eclipse.microprofile.rest.client.tck.InvalidInterfaceTest"/>
        <testcase name="testExceptionThrownWhenInterfaceHasMethodWithMultipleHTTPMethodAnnotations" time="0.107" classname="org.eclipse.microprofile.rest.client.tck.InvalidInterfaceTest"/>
        <testcase name="testExceptionThrownWhenInterfaceHasMethodWithPathParamAnnotationButNoURITemplate" time="0.084" classname="org.eclipse.microprofile.rest.client.tck.InvalidInterfaceTest"/>
        <testcase name="testExceptionThrownWhenMultipleClientHeaderParamsSpecifySameHeaderOnInterface" time="0.09" classname="org.eclipse.microprofile.rest.client.tck.InvalidInterfaceTest"/>
        <testcase name="testExceptionThrownWhenMultipleClientHeaderParamsSpecifySameHeaderOnMethod" time="0.074" classname="org.eclipse.microprofile.rest.client.tck.InvalidInterfaceTest"/>
        <testcase name="testExceptionThrownWhenMultipleHeaderValuesSpecifiedIncludeComputeMethodOnInterface" time="0.077" classname="org.eclipse.microprofile.rest.client.tck.InvalidInterfaceTest"/>
        <testcase name="testExceptionThrownWhenMultipleHeaderValuesSpecifiedIncludeComputeMethodOnMethod" time="0.075" classname="org.eclipse.microprofile.rest.client.tck.InvalidInterfaceTest"/>
        <testcase name="testExceptionThrownWhenPropertySetToFalse" time="3.199" classname="org.eclipse.microprofile.rest.client.tck.DefaultExceptionMapperTest"/>
        <testcase name="testLowerPriorityMapperTakesPrecedenceFromDefault" time="0.248" classname="org.eclipse.microprofile.rest.client.tck.DefaultExceptionMapperTest"/>
        <testcase name="testNoExceptionThrownWhenDisabledDuringBuild" time="0.239" classname="org.eclipse.microprofile.rest.client.tck.DefaultExceptionMapperTest"/>
        <testcase name="testPropagationOfResponseDetailsFromDefaultMapper" time="0.24" classname="org.eclipse.microprofile.rest.client.tck.DefaultExceptionMapperTest"/>
        <testcase name="invokesUserDefinedHttpMethod" time="2.216" classname="org.eclipse.microprofile.rest.client.tck.CustomHttpMethodTest"/>
        <testcase name="testRegistrarInvoked" time="1.738" classname="org.eclipse.microprofile.rest.client.tck.RestClientBuilderListenerTest"/>
        <testcase name="testHasSingletonScoped" time="1.357" classname="org.eclipse.microprofile.rest.client.tck.cditests.HasSingletonScopeTest"/>
        <testcase name="testHasSingletonScopedFromConfigKey" time="0.054" classname="org.eclipse.microprofile.rest.client.tck.cditests.HasSingletonScopeTest"/>
        <testcase name="testHasSingletonScopedWhenAnnotated" time="0.064" classname="org.eclipse.microprofile.rest.client.tck.cditests.HasSingletonScopeTest"/>
        <testcase name="testHasSessionScopedFromConfigKey" time="1.359" classname="org.eclipse.microprofile.rest.client.tck.cditests.HasSessionScopeTest"/>
        <testcase name="testHasSessionScopedWhenAnnotated" time="0.048" classname="org.eclipse.microprofile.rest.client.tck.cditests.HasSessionScopeTest"/>
        <testcase name="testHasSingletonScoped" time="0.033" classname="org.eclipse.microprofile.rest.client.tck.cditests.HasSessionScopeTest"/>
        <testcase name="testProxy" time="3.814" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIProxyServerTest"/>
        <testcase name="testHasApplicationScoped" time="1.295" classname="org.eclipse.microprofile.rest.client.tck.cditests.HasAppScopeTest"/>
        <testcase name="testHasApplicationScopedFromConfigKey" time="0.03" classname="org.eclipse.microprofile.rest.client.tck.cditests.HasAppScopeTest"/>
        <testcase name="testHasApplicationScopedWhenAnnotated" time="0.04" classname="org.eclipse.microprofile.rest.client.tck.cditests.HasAppScopeTest"/>
        <testcase name="testHasRequestScoped" time="1.331" classname="org.eclipse.microprofile.rest.client.tck.cditests.HasRequestScopeTest"/>
        <testcase name="testHasRequestScopedFromConfigKey" time="0.055" classname="org.eclipse.microprofile.rest.client.tck.cditests.HasRequestScopeTest"/>
        <testcase name="testHasRequestScopedWhenAnnotated" time="0.05" classname="org.eclipse.microprofile.rest.client.tck.cditests.HasRequestScopeTest"/>
        <testcase name="testHasConversationScoped" time="1.524" classname="org.eclipse.microprofile.rest.client.tck.cditests.HasConversationScopeTest"/>
        <testcase name="testHasConversationScopedFromConfigKey" time="0.03" classname="org.eclipse.microprofile.rest.client.tck.cditests.HasConversationScopeTest"/>
        <testcase name="testHasConversationScopedWhenAnnotated" time="0.032" classname="org.eclipse.microprofile.rest.client.tck.cditests.HasConversationScopeTest"/>
        <testcase name="testHasDependentScopedByDefault" time="2.889" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIInvokeSimpleGetOperationTest"/>
        <testcase name="testInvokesGetOperationWithCDIBean" time="0.86" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIInvokeSimpleGetOperationTest"/>
        <testcase name="test301Default" time="3.531" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIFollowRedirectsTest"/>
        <testcase name="test301Follows" time="0.35" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIFollowRedirectsTest"/>
        <testcase name="test302Default" time="0.299" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIFollowRedirectsTest"/>
        <testcase name="test302Follows" time="0.327" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIFollowRedirectsTest"/>
        <testcase name="test303Default" time="0.323" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIFollowRedirectsTest"/>
        <testcase name="test303Follows" time="0.257" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIFollowRedirectsTest"/>
        <testcase name="test307Default" time="0.238" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIFollowRedirectsTest"/>
        <testcase name="test307Follows" time="0.258" classname="org.eclipse.microprofile.rest.client.tck.cditests.CDIFollowRedirectsTest"/>
        <testcase name="testCommentOnlySse" time="1.653" classname="org.eclipse.microprofile.rest.client.tck.sse.BasicReactiveStreamsTest"/>
        <testcase name="testDataOnlySse_InboundSseEvent" time="0.131" classname="org.eclipse.microprofile.rest.client.tck.sse.BasicReactiveStreamsTest"/>
        <testcase name="testDataOnlySse_JsonObject" time="0.159" classname="org.eclipse.microprofile.rest.client.tck.sse.BasicReactiveStreamsTest"/>
        <testcase name="testDataOnlySse_String" time="0.126" classname="org.eclipse.microprofile.rest.client.tck.sse.BasicReactiveStreamsTest"/>
        <testcase name="testNamedEventSse" time="1.084" classname="org.eclipse.microprofile.rest.client.tck.sse.BasicReactiveStreamsTest"/>
        <testcase name="testServerClosesConnection" time="1.575" classname="org.eclipse.microprofile.rest.client.tck.sse.BasicReactiveStreamsTest"/>
        <testcase name="testWithOneRegisteredProvider" time="3.587" classname="org.eclipse.microprofile.rest.client.tck.ExceptionMapperTest"/>
        <testcase name="testWithTwoRegisteredProviders" time="0.185" classname="org.eclipse.microprofile.rest.client.tck.ExceptionMapperTest"/>
        <testcase name="shouldFailWithNonMatchingKeystore" time="2.868" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslTrustStoreTest"/>
        <testcase name="shouldFailWithNonMatchingKeystoreCDI" time="0.737" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslTrustStoreTest"/>
        <testcase name="shouldFailWithSelfSignedKeystore" time="0.776" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslTrustStoreTest"/>
        <testcase name="shouldFailWithSelfSignedKeystoreCDI" time="0.432" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslTrustStoreTest"/>
        <testcase name="shouldSucceedWithRegisteredSelfSignedKeystore" time="0.657" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslTrustStoreTest"/>
        <testcase name="shouldSucceedWithRegisteredSelfSignedKeystoreCDI" time="0.42" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslTrustStoreTest"/>
        <testcase name="shouldSucceedWithRegisteredSelfSignedKeystoreFromResourceCDI" time="0.46" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslTrustStoreTest"/>
        <testcase name="shouldFailWithRejectingHostnameVerifier" time="2.251" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslHostnameVerifierTest"/>
        <testcase name="shouldFailWithRejectingHostnameVerifierCDI" time="0.288" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslHostnameVerifierTest"/>
        <testcase name="shouldFailWithoutHostnameAndNoVerifier" time="0.45" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslHostnameVerifierTest"/>
        <testcase name="shouldPassSslSessionAndHostnameToHostnameVerifier" time="0.716" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslHostnameVerifierTest"/>
        <testcase name="shouldPassSslSessionAndHostnameToHostnameVerifierCDI" time="0.268" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslHostnameVerifierTest"/>
        <testcase name="shouldSucceedWithAcceptingHostnameVerifier" time="0.374" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslHostnameVerifierTest"/>
        <testcase name="shouldSucceedWithAcceptingHostnameVerifierCDI" time="0.214" classname="org.eclipse.microprofile.rest.client.tck.ssl.SslHostnameVerifierTest"/>
        <testcase name="testProducesConsumesAnnotationOnInterface" time="2.274" classname="org.eclipse.microprofile.rest.client.tck.ProducesConsumesTest"/>
        <testcase name="testProducesConsumesAnnotationOnMethod" time="0.172" classname="org.eclipse.microprofile.rest.client.tck.ProducesConsumesTest"/>
        <testcase name="testCallsTwoProvidersWithTwoRegisteredProvider" time="3.285" classname="org.eclipse.microprofile.rest.client.tck.CallMultipleMappersTest"/>
        <testcase name="testFeatureRegistrationViaBuilder" time="3.021" classname="org.eclipse.microprofile.rest.client.tck.FeatureRegistrationTest"/>
        <testcase name="testFeatureRegistrationViaCDI" time="0.161" classname="org.eclipse.microprofile.rest.client.tck.FeatureRegistrationTest"/>
        <testcase name="testHasDependentScopedByDefault" time="3.489" classname="org.eclipse.microprofile.rest.client.tck.asynctests.CDIInvokeAsyncSimpleGetOperationTest"/>
        <testcase name="testInvokesGetOperationWithCDIBean" time="0.789" classname="org.eclipse.microprofile.rest.client.tck.asynctests.CDIInvokeAsyncSimpleGetOperationTest"/>
        <testcase name="testAsyncInvocationInterceptorProvider" time="4.659" classname="org.eclipse.microprofile.rest.client.tck.asynctests.AsyncMethodTest"/>
        <testcase name="testExecutorService" time="0.414" classname="org.eclipse.microprofile.rest.client.tck.asynctests.AsyncMethodTest"/>
        <testcase name="testInterfaceMethodWithCompletionStageObjectReturnIsInvokedAsynchronously" time="0.273" classname="org.eclipse.microprofile.rest.client.tck.asynctests.AsyncMethodTest"/>
        <testcase name="testNullExecutorServiceThrowsIllegalArgumentException" time="0.323" classname="org.eclipse.microprofile.rest.client.tck.asynctests.AsyncMethodTest"/>
        <testcase name="shouldReuseClientAfterFailure" time="3.352" classname="org.eclipse.microprofile.rest.client.tck.ClientReuseTest"/>
        <testcase name="testCanCallStaticLoader" time="1.309" classname="org.eclipse.microprofile.rest.client.tck.ProvidesRestClientBuilderTest"/>
        <testcase name="testIllegalStateExceptionThrownWhenNoBaseUriOrUrlSpecified" time="0.092" classname="org.eclipse.microprofile.rest.client.tck.ProvidesRestClientBuilderTest"/>
        <testcase name="testLastBaseUriOrBaseUrlCallWins" time="0.578" classname="org.eclipse.microprofile.rest.client.tck.ProvidesRestClientBuilderTest"/>
        <testcase name="testConnectTimeout" time="11.344" classname="org.eclipse.microprofile.rest.client.tck.timeout.TimeoutTestBase"/>
        <testcase name="testReadTimeout" time="5.479" classname="org.eclipse.microprofile.rest.client.tck.timeout.TimeoutTestBase"/>
        <testcase name="testConnectTimeout" time="10.129" classname="org.eclipse.microprofile.rest.client.tck.timeout.TimeoutTestBase"/>
        <testcase name="testReadTimeout" time="7.534" classname="org.eclipse.microprofile.rest.client.tck.timeout.TimeoutTestBase"/>
        <testcase name="testConnectTimeout" time="10.019" classname="org.eclipse.microprofile.rest.client.tck.timeout.TimeoutTestBase"/>
        <testcase name="testReadTimeout" time="7.472" classname="org.eclipse.microprofile.rest.client.tck.timeout.TimeoutTestBase"/>
        <testcase name="testCanSeePrivatePropertiesViaContextResolver" time="3.906" classname="org.eclipse.microprofile.rest.client.tck.jsonb.InvokeWithJsonBProviderTest"/>
        <testcase name="testGetExecutesForBothClients" time="0.401" classname="org.eclipse.microprofile.rest.client.tck.jsonb.InvokeWithJsonBProviderTest"/>
        <testcase name="testGetExecutesForBothClients" time="3.828" classname="org.eclipse.microprofile.rest.client.tck.InvokeWithJsonPProviderTest"/>
        <testcase name="testGetSingleExecutesForBothClients" time="0.421" classname="org.eclipse.microprofile.rest.client.tck.InvokeWithJsonPProviderTest"/>
        <testcase name="testPostExecutes" time="0.551" classname="org.eclipse.microprofile.rest.client.tck.InvokeWithJsonPProviderTest"/>
        <testcase name="testPutExecutes" time="0.398" classname="org.eclipse.microprofile.rest.client.tck.InvokeWithJsonPProviderTest"/>
        <testcase name="testDefaultMIMETypeIsApplicationJson_Accept" time="1.848" classname="org.eclipse.microprofile.rest.client.tck.DefaultMIMETypeTest"/>
        <testcase name="testDefaultMIMETypeIsApplicationJson_ContentType" time="0.129" classname="org.eclipse.microprofile.rest.client.tck.DefaultMIMETypeTest"/>
        <testcase name="canInvokeMethodOnBaseInterface" time="2.029" classname="org.eclipse.microprofile.rest.client.tck.InheritanceTest"/>
        <testcase name="canInvokeMethodOnChildInterface" time="0.157" classname="org.eclipse.microprofile.rest.client.tck.InheritanceTest"/>
        <testcase name="canInvokeOverriddenMethodOnChildInterface" time="0.144" classname="org.eclipse.microprofile.rest.client.tck.InheritanceTest"/>
    </testsuite>
    <testsuite hostname="node1" ignored="0" name="Surefire test" tests="43" failures="0" timestamp="2023-07-17T09:55:29 CST" time="402.992" errors="0" skipped="10">
        <testcase name="optional_spec104_mustSignalOnErrorWhenFails" time="0.006" classname="org.reactivestreams.tck.PublisherVerification">
            <skipped/>
        </testcase> <!-- optional_spec104_mustSignalOnErrorWhenFails -->
        <testcase name="optional_spec105_emptyStreamMustTerminateBySignallingOnComplete" time="6.149" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="optional_spec111_maySupportMultiSubscribe" time="5.115" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="optional_spec111_multicast_mustProduceTheSameElementsInTheSameSequenceToAllOfItsSubscribersWhenRequestingManyUpfront" time="0.099" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="optional_spec111_multicast_mustProduceTheSameElementsInTheSameSequenceToAllOfItsSubscribersWhenRequestingManyUpfrontAndCompleteAsExpected" time="0.131" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="optional_spec111_multicast_mustProduceTheSameElementsInTheSameSequenceToAllOfItsSubscribersWhenRequestingOneByOne" time="0.101" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="optional_spec111_registeredSubscribersMustReceiveOnNextOrOnCompleteSignals" time="5.056" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="optional_spec309_requestNegativeNumberMaySignalIllegalArgumentExceptionWithSpecificMessage" time="5.057" classname="org.reactivestreams.tck.PublisherVerification">
            <skipped/>
        </testcase> <!-- optional_spec309_requestNegativeNumberMaySignalIllegalArgumentExceptionWithSpecificMessage -->
        <testcase name="required_createPublisher1MustProduceAStreamOfExactly1Element" time="0.087" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_createPublisher3MustProduceAStreamOfExactly3Elements" time="0.063" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_spec101_subscriptionRequestMustResultInTheCorrectNumberOfProducedElements" time="15.091" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_spec102_maySignalLessThanRequestedAndTerminateSubscription" time="0.122" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_spec105_mustSignalOnCompleteWhenFiniteStreamTerminates" time="5.278" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_spec107_mustNotEmitFurtherSignalsOnceOnCompleteHasBeenSignalled" time="5.059" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_spec109_mayRejectCallsToSubscribeIfPublisherIsUnableOrUnwillingToServeThemRejectionMustTriggerOnErrorAfterOnSubscribe" time="0.001" classname="org.reactivestreams.tck.PublisherVerification">
            <skipped/>
        </testcase> <!-- required_spec109_mayRejectCallsToSubscribeIfPublisherIsUnableOrUnwillingToServeThemRejectionMustTriggerOnErrorAfterOnSubscribe -->
        <testcase name="required_spec109_mustIssueOnSubscribeForNonNullSubscriber" time="0.054" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_spec109_subscribeThrowNPEOnNullSubscriber" time="0.064" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_spec302_mustAllowSynchronousRequestCallsFromOnNextAndOnSubscribe" time="5.054" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_spec303_mustNotAllowUnboundedRecursion" time="0.074" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_spec306_afterSubscriptionIsCancelledRequestMustBeNops" time="5.058" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_spec307_afterSubscriptionIsCancelledAdditionalCancelationsMustBeNops" time="5.045" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_spec309_requestNegativeNumberMustSignalIllegalArgumentException" time="5.049" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_spec309_requestZeroMustSignalIllegalArgumentException" time="5.049" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_spec312_cancelMustMakeThePublisherToEventuallyStopSignaling" time="10.061" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_spec313_cancelMustMakeThePublisherEventuallyDropAllReferencesToTheSubscriber" time="0.5" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_spec317_mustNotSignalOnErrorWhenPendingAboveLongMaxValue" time="5.073" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_spec317_mustSupportACumulativePendingElementCountUpToLongMaxValue" time="0.037" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_spec317_mustSupportAPendingElementCountUpToLongMaxValue" time="0.051" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_validate_boundedDepthOfOnNextAndRequestRecursion" time="0.0" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="required_validate_maxElementsFromPublisher" time="0.001" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="stochastic_spec103_mustSignalOnMethodsSequentially" time="4.926" classname="org.reactivestreams.tck.PublisherVerification"/>
        <testcase name="untested_spec106_mustConsiderSubscriptionCancelledAfterOnErrorOrOnCompleteHasBeenCalled" time="0.001" classname="org.reactivestreams.tck.PublisherVerification">
            <skipped/>
        </testcase> <!-- untested_spec106_mustConsiderSubscriptionCancelledAfterOnErrorOrOnCompleteHasBeenCalled -->
        <testcase name="untested_spec107_mustNotEmitFurtherSignalsOnceOnErrorHasBeenSignalled" time="0.001" classname="org.reactivestreams.tck.PublisherVerification">
            <skipped/>
        </testcase> <!-- untested_spec107_mustNotEmitFurtherSignalsOnceOnErrorHasBeenSignalled -->
        <testcase name="untested_spec108_possiblyCanceledSubscriptionShouldNotReceiveOnErrorOrOnCompleteSignals" time="0.0" classname="org.reactivestreams.tck.PublisherVerification">
            <skipped/>
        </testcase> <!-- untested_spec108_possiblyCanceledSubscriptionShouldNotReceiveOnErrorOrOnCompleteSignals -->
        <testcase name="untested_spec109_subscribeShouldNotThrowNonFatalThrowable" time="0.0" classname="org.reactivestreams.tck.PublisherVerification">
            <skipped/>
        </testcase> <!-- untested_spec109_subscribeShouldNotThrowNonFatalThrowable -->
        <testcase name="untested_spec110_rejectASubscriptionRequestIfTheSameSubscriberSubscribesTwice" time="0.0" classname="org.reactivestreams.tck.PublisherVerification">
            <skipped/>
        </testcase> <!-- untested_spec110_rejectASubscriptionRequestIfTheSameSubscriberSubscribesTwice -->
        <testcase name="untested_spec304_requestShouldNotPerformHeavyComputations" time="0.0" classname="org.reactivestreams.tck.PublisherVerification">
            <skipped/>
        </testcase> <!-- untested_spec304_requestShouldNotPerformHeavyComputations -->
        <testcase name="untested_spec305_cancelMustNotSynchronouslyPerformHeavyComputation" time="0.001" classname="org.reactivestreams.tck.PublisherVerification">
            <skipped/>
        </testcase> <!-- untested_spec305_cancelMustNotSynchronouslyPerformHeavyComputation -->
        <testcase name="testInvalidPortNumber" time="1.364" classname="org.eclipse.microprofile.rest.client.tck.ProxyServerTest"/>
        <testcase name="testInvalidPortNumber1" time="0.047" classname="org.eclipse.microprofile.rest.client.tck.ProxyServerTest"/>
        <testcase name="testInvalidPortNumber2" time="0.068" classname="org.eclipse.microprofile.rest.client.tck.ProxyServerTest"/>
        <testcase name="testNullHostName" time="0.035" classname="org.eclipse.microprofile.rest.client.tck.ProxyServerTest"/>
        <testcase name="testProxy" time="1.31" classname="org.eclipse.microprofile.rest.client.tck.ProxyServerTest"/>
    </testsuite>
</testsuites>

```