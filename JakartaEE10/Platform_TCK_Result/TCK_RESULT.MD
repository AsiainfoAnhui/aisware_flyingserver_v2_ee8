## Jakarta EE 10 Compatibility TCK Results
As required by the [Eclipse Foundation Technology Compatibility Kit License](https://www.eclipse.org/legal/tck.php), following is a summary of the TCK results for releases of Jakarta EE Platform 10.
 
## AISWare FlyingServer V5.0.0  Jakarta EE 10 Platform Certification Summary
- [x] Organization Name ("Organization") and, if applicable, URL:<br/>
  - [AsiaInfo](https://www.asiainfo.com/zh_cn/index.html)
- [x] Product Name, Version and download URL (if applicable):<br/>
  - [AISWare FlyingServer V5.0.0](https://www.asiainfo.com/zh_cn/product_aisware_flyingServer.html)
- [x] Specification Name, Version and download URL:<br/>
   - [Jakarta EE Platform 10](https://jakarta.ee/specifications/platform/10/)
- [x] TCK Version, digital SHA-256 fingerprint and download URL:<br/>
  - [Jakarta EE Platform TCK 10.0.0](https://download.eclipse.org/jakartaee/platform/10/jakarta-jakartaeetck-10.0.0.zip)
- [x] Public URL of TCK Results Summary:<br/>
   - [TCK Result Summary](https://github.com/AsiainfoAnhui/aisware_flyingserver_v2_ee8/blob/master/JakartaEE10/Platform_TCK_Result/TCK_RESULT.MD)

- [x] Any Additional Specification Certification Requirements:<br/>
  - [Jakarta Activation 2.1.0 TCK](https://download.eclipse.org/jakartaee/activation/2.1/jakarta-activation-tck-2.1.0.zip), SHA-256: 6c4aad27e45761dd9f3e0f8506f37edea41f42401465db750689145718b27a0b
  - [Jakarta Authentication 3.0.1 TCK](https://download.eclipse.org/jakartaee/authentication/3.0/jakarta-authentication-tck-3.0.1.zip), SHA-256: 8b916f1b4aed828337bd88b34bb39b133f04611c2dfe71541c2ec5d2dd22cd54
  - [Jakarta Batch 2.1.1 TCK](https://download.eclipse.org/jakartaee/batch/2.1/jakarta.batch.official.tck-2.1.1.zip), SHA-256: 0dd8ca0f35cc696ea86d0dffaa1301cf2786806832ea1b2a491d528eaa57b3b7
  - [Jakarta Bean Validation 3.0.1 TCK](https://download.eclipse.org/jakartaee/bean-validation/3.0/beanvalidation-tck-dist-3.0.1.zip), SHA-256: 9da36d2d6e2eb8d413f886f15711820008419d210ce4c51af04f96e1ffd583b3
  - [Jakarta Concurrency 3.0.2 TCK](https://download.eclipse.org/jakartaee/concurrency/3.0/concurrency-tck-3.0.2.zip), SHA-256: 22728d729f620d6a85ae903e7d1184e0a7508a4328491b785f1b4f3d7215ca93
  - [Jakarta Contexts Dependency Injection 4.0.13 TCK](https://download.eclipse.org/jakartaee/cdi/4.0/cdi-tck-4.0.13-dist.zip), SHA-256: 566c547e1a9c66792eefcc6feafea87ab0c0f2e3f71385bf96865359a685df00
  - [Jakarta Debugging Support for Other Languages 2.0.0 TCK](https://download.eclipse.org/jakartaee/debugging/2.0/jakarta-debugging-tck-2.0.0.zip), SHA-256: 71999815418799837dc6f3d0dc40c3dcc4144cd90c7cdfd06aa69270483d78bc
  - [Jakarta Dependency Injection 2.0.2 TCK](https://download.eclipse.org/jakartaee/dependency-injection/2.0/jakarta.inject-tck-2.0.2-bin.zip), SHA-256: 23bce4317ca061c3de648566cdf65c74b57e1264d6891f366567955d6b834972
  - [Jakarta Faces 4.0.3 TCK](https://download.eclipse.org/jakartaee/faces/4.0/jakarta-faces-tck-4.0.3.zip), SHA-256: 153184ad38e522c45e74e5da7dd01b1f3be485f56e241a72728caa43479b07ec
  - [Jakarta JSON Binding 3.0 TCK](https://download.eclipse.org/jakartaee/jsonb/3.0/jakarta-jsonb-tck-3.0.0.zip), SHA-256: 954fd9a3a67059ddeabe5f51462a6a3b542c94fc798094dd8c312a6a28ef2d0b
  - [Jakarta JSON Processing 2.1.1 TCK](https://download.eclipse.org/jakartaee/jsonp/2.1/jakarta-jsonp-tck-2.1.1.zip), SHA-256: 949f203de84deffa8c7892b555918e42f1dd220ccb7b6800741ea58af62737c1
  - [Jakarta Jakarta Mail 2.1.1 TCK](https://download.eclipse.org/jakartaee/mail/2.1/jakarta-mail-tck-2.1.1.zip), SHA-256: c749d4245acc51a53c8c3058782f3da6dfd87384a4485ce3fee3c8d36bd0df1b
  - [Jakarta RESTful Web Services 3.1.0 TCK](https://download.eclipse.org/jakartaee/restful-ws/3.1/jakarta-restful-ws-tck-3.1.0.zip), SHA-256: ea8cd6cc857af55f19468bbb09e8a30f41c60e8f7413a093e7007c3902a49070
  - [Jakarta Security 3.0.2 TCK](https://download.eclipse.org/jakartaee/security/3.0/jakarta-security-tck-3.0.2.zip), SHA-256: 9ecad6406031369efa70ac429f94140b4e35a58f216599d296ce19f944e70254
  - [Jakarta XML Binding 4.0.1 TCK](https://www.eclipse.org/downloads/download.php?file=/jakartaee/xml-binding/4.0/jakarta-xml-binding-tck-4.0.1.zip), SHA-256: 146be8dc429eb6271a940bf7652f4e11421be702357dbca2cbd93c09c53fac2e
- [x] Java runtime used to run the implementation:<br/>
  - Java runtime: OpenJDK 11.0.2 (build 11.0.2+9)
- [x] Summary of the information for the certification environment, operating system, cloud, ...:<br/>
  - Ubuntu 20.04.4 LTS   
  - Apache Derby
- [x] By checking this box I acknowledge that the Organization I represent accepts the terms of the [EFTL](https://www.eclipse.org/legal/tck.php).
- [x] By checking this box I attest that all TCK requirements have been met, including any compatibility rules.


## Platform TCK Test results

1.Stage Name: appclient
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 50 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 50
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

2.Stage Name: assembly
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 30 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 30
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

3.Stage Name: connector
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 477 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 477
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

4.Stage Name: ejb
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1793 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1793
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

5.Stage Name: ejb30/assembly
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 51 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 51
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

6.Stage Name: ejb30/bb
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1193 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1193
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

7.Stage Name: ejb30/lite/appexception
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 365 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 365
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

8.Stage Name: ejb30/lite/async
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 300 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 300
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

9.Stage Name: ejb30/lite/basic
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 105 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 105
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

10.Stage Name: ejb30/lite/ejbcontext
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 50 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 50
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

11.Stage Name: ejb30/lite/enventry
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 30 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 30
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

12.Stage Name: ejb30/lite/interceptor
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 175 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 175
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

13.Stage Name: ejb30/lite/lookup
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 30 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 30
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

14.Stage Name: ejb30/lite/naming
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 54 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 54
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

15.Stage Name: ejb30/lite/nointerface
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 60 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 60
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

16.Stage Name: ejb30/lite/packaging
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 211 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 211
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

17.Stage Name: ejb30/lite/singleton
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 230 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 230
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

18.Stage Name: ejb30/lite/stateful
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 124 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 124
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

19.Stage Name: ejb30/lite/tx
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 358 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 358
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

20.Stage Name: ejb30/lite/view
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 95 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 95
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

21.Stage Name: ejb30/lite/xmloverride
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 30 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 30
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

22.Stage Name: ejb30/misc
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 100 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 100
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

23.Stage Name: ejb30/sec
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 99 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 99
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

24.Stage Name: ejb30/timer
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 178 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 178
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

25.Stage Name: ejb30/webservice
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 3 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 3
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

26.Stage Name: ejb30/zombie
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

27.Stage Name: ejb32
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 825 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 825
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

28.Stage Name: el
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 695 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 695
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

29.Stage Name: integration
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 18 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 18
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

30.Stage Name: jacc
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 40 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 40
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

31.Stage Name: javaee
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 24 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 24
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

32.Stage Name: javamail
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 112 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 112
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

33.Stage Name: jaxrs
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 138 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 138
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

34.Stage Name: jdbc_appclient
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1231 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1231
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

35.Stage Name: jdbc_ejb
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1231 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1231
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

36.Stage Name: jdbc_jsp
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1231 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1231
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

37.Stage Name: jdbc_servlet
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1231 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1231
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

38.Stage Name: jms
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 3510 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 3510
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

39.Stage Name: jpa_appmanaged
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1725 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1725
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

40.Stage Name: jpa_appmanagedNoTx
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1863 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1863
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

41.Stage Name: jpa_pmservlet
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1871 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1871
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

42.Stage Name: jpa_puservlet
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1861 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1861
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

43.Stage Name: jpa_stateful3
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1725 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1725
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

44.Stage Name: jpa_stateless3
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1873 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1873
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

45.Stage Name: jsonb
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 18 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 18
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

46.Stage Name: jsonp
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 76 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 76
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

47.Stage Name: jsp
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 735 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 735
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

48.Stage Name: jstl
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 541 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 541
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

49.Stage Name: jta
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 141 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 141
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

50.Stage Name: samples
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 12 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 12
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

51.Stage Name: servlet
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1733 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1733
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

52.Stage Name: signaturetest/javaee
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 4 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 4
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

53.Stage Name: webservices12
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 242 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 242
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

54.Stage Name: webservices13
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 53 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 53
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

55.Stage Name: websocket
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 748 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 748
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

56.Stage Name: xa
```java
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 66 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 66
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```


## Additional standalone TCK Test results

1.Jakarta JSON Processing 2.1.1 TCK
```java
TCK result summary:
Tests run: 179, Failures: 0, Errors: 0, Skipped: 0
Tests run: 18, Failures: 0, Errors: 0, Skipped: 0
```

2.Jakarta RESTful Web Services 3.1.0 TCK
```java
[INFO] Results:
[INFO]
[WARNING] Tests run: 2796, Failures: 0, Errors: 0, Skipped: 59
```

3.Jakarta Concurrency 3.0.2 TCK
```java
  [INFO] Results:
  [INFO]
  [INFO] Tests run: 148, Failures: 0, Errors: 0, Skipped: 0
```

4.Jakarta JSON Binding 3.0 TCK
```java
[INFO] Results:
[INFO]
[WARNING] Tests run: 295, Failures: 0, Errors: 0, Skipped: 5
```

5.Jakarta Contexts and Dependency Injection 4.0.13 TCK
```java
[INFO] Results:
[INFO]
[INFO] Tests run: 1821, Failures: 0, Errors: 0, Skipped: 0
```

6.Jakarta Activation 2.1 TCK
```java
[javatest.batch] ***************************************************************
[javatest.batch] Completed running 91 tests.
[javatest.batch] Number of Tests Passed      = 91
[javatest.batch] Number of Tests Failed      = 0
[javatest.batch] Number of Tests with Errors = 0
[javatest.batch] Number of Tests Not Run     = 0
[javatest.batch] ---------------------------------------------------------------
[javatest.batch] ***************************************************************
[javatest.batch] Completed running 2 tests.
[javatest.batch] Number of Tests Passed      = 2
[javatest.batch] Number of Tests Failed      = 0
[javatest.batch] Number of Tests with Errors = 0
[javatest.batch] Number of Tests Not Run     = 0
[javatest.batch] ---------------------------------------------------------------

```

7.Jakarta Dependency Injection 2.0.2 TCK 
```java
[INFO] Results:
[INFO]
[INFO] Tests run: 50, Failures: 0, Errors: 0, Skipped: 0
```

8.Jakarta Batch 2.1.1 TCK
```java
Jakarta Batch TCK completed running 380 tests.
Number of Tests Passed      = 380
Number of Tests with Errors = 0
Number of Tests Failed      = 0
Number of Tests Skipped     = 12
```

9.Jakarta Authentication 3.0.1 TCK
```java
########################################################
Tests run: 70, Failures: 0, Errors: 0, Skipped: 0
########################################################

old:
[INFO]      [exec] [javatest.batch] ********************************************************************************
[INFO]      [exec] [javatest.batch] Completed running 106 tests.
[INFO]      [exec] [javatest.batch] Number of Tests Passed      = 106
[INFO]      [exec] [javatest.batch] Number of Tests Failed      = 0
[INFO]      [exec] [javatest.batch] Number of Tests with Errors = 0
[INFO]      [exec] [javatest.batch] ********************************************************************************
```

10.Jakarta Faces 4.0.3 TCK
```java
[INFO] --------------< org.eclipse.ee4j.tck.faces.faces22:ajax >---------------
[WARNING] Tests run: 126, Failures: 0, Errors: 0, Skipped: 65
[INFO] --------< org.eclipse.ee4j.tck.faces.faces22:cdiBeanValidator >---------
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO] -------< org.eclipse.ee4j.tck.faces.faces22:cdiInitDestroyEvent >-------
[WARNING] Tests run: 5, Failures: 0, Errors: 0, Skipped: 3
[INFO] -------< org.eclipse.ee4j.tck.faces.faces22:cdiMethodValidation >-------
[INFO] Tests run: 3, Failures: 0, Errors: 0, Skipped: 0
[INFO] -----< org.eclipse.ee4j.tck.faces.faces22:cdiMultiTenantSetsTccl >------
[WARNING] Tests run: 1, Failures: 0, Errors: 0, Skipped: 1
[INFO] ----------< org.eclipse.ee4j.tck.faces.faces22:cdiNoBeansXml >----------
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO] ---------< org.eclipse.ee4j.tck.faces.faces22:childCountTest >----------
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO] -------< org.eclipse.ee4j.tck.faces.faces22:compositeComponent >--------
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO] ----< org.eclipse.ee4j.tck.faces.faces22:expressionLanguageLambda >-----
[INFO] Tests run: 2, Failures: 0, Errors: 0, Skipped: 0
[INFO] --- failsafe:3.0.0-M5:verify (default) @ expressionLanguageLambda ---
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO] ------< org.eclipse.ee4j.tck.faces.faces22:multiFieldValidation >-------
[INFO] Tests run: 5, Failures: 0, Errors: 0, Skipped: 0
[INFO] --- failsafe:3.0.0-M5:verify (default) @ multiFieldValidation ---
[INFO] Tests run: 8, Failures: 0, Errors: 0, Skipped: 0
[INFO] ------------< org.eclipse.ee4j.tck.faces.faces22:viewScope >------------
[INFO] Tests run: 3, Failures: 0, Errors: 0, Skipped: 0
[INFO] -----< org.eclipse.ee4j.tck.faces.faces22:viewActionCdiViewScoped >-----
[INFO] Tests run: 2, Failures: 0, Errors: 0, Skipped: 0
[INFO] -----------< org.eclipse.ee4j.tck.faces.faces22:viewExpired >-----------
[WARNING] Tests run: 1, Failures: 0, Errors: 0, Skipped: 1
[INFO] -----< org.eclipse.ee4j.tck.faces.faces22:viewParamNullValueAjax >------
[WARNING] Tests run: 2, Failures: 0, Errors: 0, Skipped: 1
[INFO] ---------------< org.eclipse.ee4j.tck.faces.faces23:pom >---------------
[WARNING] Tests run: 14, Failures: 0, Errors: 0, Skipped: 7
[INFO] ---------------< org.eclipse.ee4j.tck.faces.faces23:cdi >---------------
[WARNING] Tests run: 30, Failures: 0, Errors: 0, Skipped: 2
[INFO] ----------< org.eclipse.ee4j.tck.faces.faces23:commandScript >----------
[WARNING] Tests run: 2, Failures: 0, Errors: 0, Skipped: 1
[INFO] ------------< org.eclipse.ee4j.tck.faces.faces23:converter >------------
[INFO] Tests run: 4, Failures: 0, Errors: 0, Skipped: 0
[INFO] --< org.eclipse.ee4j.tck.faces.faces23:disableFaceletToXhtmlMapping >---
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO] ---------------< org.eclipse.ee4j.tck.faces.faces23:el >----------------
[INFO] Tests run: 3, Failures: 0, Errors: 0, Skipped: 0
[INFO] ----------< org.eclipse.ee4j.tck.faces.faces23:exactMapping >-----------
[WARNING] Tests run: 12, Failures: 0, Errors: 0, Skipped: 6
[INFO] -------< org.eclipse.ee4j.tck.faces.faces23:faceletCacheFactory >-------
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO] ------------< org.eclipse.ee4j.tck.faces.faces23:facelets >-------------
[WARNING] Tests run: 10, Failures: 0, Errors: 0, Skipped: 2
[INFO] ---------< org.eclipse.ee4j.tck.faces.faces23:facesConverter >----------
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO] ---------< org.eclipse.ee4j.tck.faces.faces23:facesDataModel >----------
[INFO] Tests run: 4, Failures: 0, Errors: 0, Skipped: 0
[INFO] --------------< org.eclipse.ee4j.tck.faces.faces23:flash >--------------
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO] ------------< org.eclipse.ee4j.tck.faces.faces23:getViews >-------------
[INFO] Tests run: 22, Failures: 0, Errors: 0, Skipped: 0
[INFO] ---------< org.eclipse.ee4j.tck.faces.faces23:importConstants >---------
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO] ---------< org.eclipse.ee4j.tck.faces.faces23:namespacedView >----------
[WARNING] Tests run: 4, Failures: 0, Errors: 0, Skipped: 2
[INFO] -----------< org.eclipse.ee4j.tck.faces.faces23:passthrough >-----------
[INFO] Tests run: 5, Failures: 0, Errors: 0, Skipped: 0
[INFO] --------< org.eclipse.ee4j.tck.faces.faces23:searchExpression >---------
[WARNING] Tests run: 4, Failures: 0, Errors: 0, Skipped: 2
[INFO] -----------< org.eclipse.ee4j.tck.faces.faces23:systemEvent >-----------
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO] -------------< org.eclipse.ee4j.tck.faces.faces23:uiinput >-------------
[WARNING] Tests run: 7, Failures: 0, Errors: 0, Skipped: 1
[INFO] ------< org.eclipse.ee4j.tck.faces.faces23:uiinput-required-true >------
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO] --------< org.eclipse.ee4j.tck.faces.faces23:validateWholeBean >--------
[INFO] Tests run: 2, Failures: 0, Errors: 0, Skipped: 0
[INFO] ------------< org.eclipse.ee4j.tck.faces.faces23:websocket >------------
[WARNING] Tests run: 5, Failures: 0, Errors: 0, Skipped: 4
[INFO] --< org.eclipse.ee4j.tck.faces.faces23:xhtmlMappingToFaceletByDefault >--
[INFO] Tests run: 2, Failures: 0, Errors: 0, Skipped: 0
[INFO] ---------------< org.eclipse.ee4j.tck.faces.faces40:pom >---------------
[WARNING] Tests run: 6, Failures: 0, Errors: 0, Skipped: 3
[INFO] ---------< org.eclipse.ee4j.tck.faces.faces40:beanValidation >----------
[WARNING] Tests run: 1, Failures: 0, Errors: 0, Skipped: 1
[INFO] ---------------< org.eclipse.ee4j.tck.faces.faces40:cdi >---------------
[INFO] Tests run: 9, Failures: 0, Errors: 0, Skipped: 0
[INFO] -------------< org.eclipse.ee4j.tck.faces.faces40:doctype >-------------
[INFO] Tests run: 3, Failures: 0, Errors: 0, Skipped: 0
[INFO] ------< org.eclipse.ee4j.tck.faces.faces40:extensionless-mapping >------
[INFO] Tests run: 3, Failures: 0, Errors: 0, Skipped: 0
[INFO] ------------< org.eclipse.ee4j.tck.faces.faces40:inputFile >------------
[WARNING] Tests run: 9, Failures: 0, Errors: 0, Skipped: 4
[INFO] ------------< org.eclipse.ee4j.tck.faces.faces40:inputText >------------
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO] ------------< org.eclipse.ee4j.tck.faces.faces40:javaPage >-------------
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO] ------< org.eclipse.ee4j.tck.faces.faces40:javaPageWithMetadata >-------
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO] -----------< org.eclipse.ee4j.tck.faces.faces40:namespaces >------------
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO] ------------< org.eclipse.ee4j.tck.faces.faces40:resources >------------
[INFO] Tests run: 2, Failures: 0, Errors: 0, Skipped: 0
[INFO] ---------< org.eclipse.ee4j.tck.faces.faces40:selectItemGroup >---------
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO] --------< org.eclipse.ee4j.tck.faces.faces40:selectItemGroups >---------
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO] -------< org.eclipse.ee4j.tck.faces.faces40:selectManyCheckbox >--------
[INFO] Tests run: 8, Failures: 0, Errors: 0, Skipped: 0
[INFO] ----------< org.eclipse.ee4j.tck.faces.old-tck-selenium:pom >-----------
[WARNING] Tests run: 12, Failures: 0, Errors: 0, Skipped: 7
[INFO] ------< org.eclipse.ee4j.tck.faces.old-tck-selenium:commandLink >-------
[WARNING] Tests run: 6, Failures: 0, Errors: 0, Skipped: 3
[INFO] -----< org.eclipse.ee4j.tck.faces.old-tck-selenium:protectedViews >-----
[WARNING] Tests run: 4, Failures: 0, Errors: 0, Skipped: 2
[INFO] ------------------< jakarta.faces.tck:faces-sigtest >-------------------
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0

Old-tck
[INFO]      [exec] [javatest.batch] ********************************************************************************
[INFO]      [exec] [javatest.batch] Completed running 5400 tests.
[INFO]      [exec] [javatest.batch] Number of Tests Passed      = 5400
[INFO]      [exec] [javatest.batch] Number of Tests Failed      = 0
[INFO]      [exec] [javatest.batch] Number of Tests with Errors = 0
[INFO]      [exec] [javatest.batch] ********************************************************************************
```

11.Jakarta Bean Validation 3.0.1 TCK
```java
Results :
Tests run: 1045, Failures: 0, Errors: 0, Skipped: 0
```

12.Jakarta Debugging Support for Other Languages 2.0.0 TCK
```java
testclient/org/apache/jsp/Hello_jsp.class.smap is a correctly formatted SMAP
<testsuite id="1" name="debugging-tck" tests="1" failures="0" errors="0" disabled="0" skipped="0">
```

13.Jakarta XML Binding 4.0.1 TCK
```java
Results :
Pass: 24,624  Fail: 0  Error: 0  Not-Run: 0
```

14.Jakarta Security 3.0.2 TCK
```java
[INFO] ---------< org.eclipse.ee4j.security.tck:app-securitycontext >----------
[INFO] Results:
[INFO]
[INFO] Tests run: 7, Failures: 0, Errors: 0, Skipped: 0

[INFO] -------< org.eclipse.ee4j.security.tck:app-securitycontext-auth >-------
[INFO] Results:
[INFO]
[INFO] Tests run: 5, Failures: 0, Errors: 0, Skipped: 0

[INFO] --< org.eclipse.ee4j.security.tck:app-securitycontext-customprincipal >--
[INFO] Results:
[INFO]
[INFO] Tests run: 4, Failures: 0, Errors: 0, Skipped: 0

[INFO] ---------------< org.eclipse.ee4j.security.tck:app-mem >----------------
[INFO] Results:
[INFO]
[INFO] Tests run: 4, Failures: 0, Errors: 0, Skipped: 0

[INFO] ----------------< org.eclipse.ee4j.security.tck:app-db >----------------
[INFO] Results:
[INFO]
[INFO] Tests run: 4, Failures: 0, Errors: 0, Skipped: 0

[INFO] ---------------< org.eclipse.ee4j.security.tck:app-ldap >---------------
[INFO] Results:
[INFO]
[INFO] Tests run: 4, Failures: 0, Errors: 0, Skipped: 0

[INFO] --------------< org.eclipse.ee4j.security.tck:app-ldap2 >---------------
[INFO] Results:
[INFO]
[INFO] Tests run: 4, Failures: 0, Errors: 0, Skipped: 0

[INFO] --------------< org.eclipse.ee4j.security.tck:app-ldap3 >---------------
[INFO] Results:
[INFO]
[INFO] Tests run: 4, Failures: 0, Errors: 0, Skipped: 0

[INFO] --------------< org.eclipse.ee4j.security.tck:app-custom >--------------
[INFO] Results:
[INFO]
[INFO] Tests run: 4, Failures: 0, Errors: 0, Skipped: 0

[INFO] ----------< org.eclipse.ee4j.security.tck:app-multiple-store >----------
[INFO] Results:
[INFO]
[INFO] Tests run: 4, Failures: 0, Errors: 0, Skipped: 0

[INFO] ------< org.eclipse.ee4j.security.tck:app-multiple-store-backup >-------
[INFO] Results:
[INFO]
[INFO] Tests run: 6, Failures: 0, Errors: 0, Skipped: 0

[INFO] --------------< org.eclipse.ee4j.security.tck:app-openid >--------------
[INFO] Results:
[INFO]
[INFO] Tests run: 3, Failures: 0, Errors: 0, Skipped: 0

[INFO] -------------< org.eclipse.ee4j.security.tck:app-openid2 >--------------
[INFO] Results:
[INFO]
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0

[INFO] -------------< org.eclipse.ee4j.security.tck:app-openid3 >--------------
[INFO] Results:
[INFO]
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0

[INFO] ------------< org.eclipse.ee4j.security.tck:app-mem-basic >-------------
[INFO] Results:
[INFO]
[INFO] Tests run: 4, Failures: 0, Errors: 0, Skipped: 0

[INFO] --------< org.eclipse.ee4j.security.tck:app-mem-basic-decorate >--------
[INFO] Results:
[INFO]
[INFO] Tests run: 2, Failures: 0, Errors: 0, Skipped: 0

[INFO] -------------< org.eclipse.ee4j.security.tck:app-mem-form >-------------
[INFO] Results:
[INFO]
[INFO] Tests run: 8, Failures: 0, Errors: 0, Skipped: 0

[INFO] ----------< org.eclipse.ee4j.security.tck:app-mem-customform >----------
[INFO] Results:
[INFO]
[INFO] Tests run: 4, Failures: 0, Errors: 0, Skipped: 0

[INFO] ----------< org.eclipse.ee4j.security.tck:app-custom-session >----------
[INFO] Results:
[INFO]
[INFO] Tests run: 5, Failures: 0, Errors: 0, Skipped: 0

[INFO] --------< org.eclipse.ee4j.security.tck:app-custom-rememberme >---------
[INFO] Results:
[INFO]
[INFO] Tests run: 25, Failures: 0, Errors: 0, Skipped: 0

[INFO] --< org.eclipse.ee4j.security.tck:app-custom-identity-store-handler >---
[INFO] Results:
[INFO]
[INFO] Tests run: 5, Failures: 0, Errors: 0, Skipped: 0

[INFO] --------------< org.eclipse.ee4j.security.tck:app-jaxrs >---------------
[INFO] Results:
[INFO]
[INFO] Tests run: 8, Failures: 0, Errors: 0, Skipped: 0

[INFO] ---------< jakarta.security.tck.sigtest:security-tck-sigtest >----------
[INFO] Results:
[INFO]
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0

old-tck:
[INFO]      [exec] [javatest.batch] ********************************************************************************
[INFO]      [exec] [javatest.batch] Completed running 84 tests.
[INFO]      [exec] [javatest.batch] Number of Tests Passed      = 84
[INFO]      [exec] [javatest.batch] Number of Tests Failed      = 0
[INFO]      [exec] [javatest.batch] Number of Tests with Errors = 0
[INFO]      [exec] [javatest.batch] ********************************************************************************
```

15.Jakarta Mail 2.1.1 TCK
```java
[javatest.batch] ***************************************************************
[javatest.batch] Completed running 321 tests.
[javatest.batch] Number of Tests Passed      = 321
[javatest.batch] Number of Tests Failed      = 0
[javatest.batch] Number of Tests with Errors = 0
[javatest.batch] Number of Tests Not Run     = 0
[javatest.batch] ---------------------------------------------------------------

pluggability
[javatest.batch] ***************************************************************
[javatest.batch] Completed running 1 tests.
[javatest.batch] Number of Tests Passed      = 1
[javatest.batch] Number of Tests Failed      = 0
[javatest.batch] Number of Tests with Errors = 0
[javatest.batch] Number of Tests Not Run     = 0
[javatest.batch] ---------------------------------------------------------------
```




