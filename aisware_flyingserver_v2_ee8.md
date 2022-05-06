# TCK Results
As required by the [Eclipse Foundation Technology Compatibility Kit License](https://www.eclipse.org/legal/tck.php), following is a summary of the TCK results for releases of Jakarta EE Platform, Full Profile.

## AISWare FlyingServer 2.0.0 Full Profile Certification Summary
Product Name, Version and download URL (if applicable):  
[AISWare Flying Server 2.0.0](https://cms.101test.com/ai_sino_info/zh_cn/content_603710660.html)

Specification Name, Version and download URL:

[Jakarta EE Platform, Full Profile 8](https://jakarta.ee/specifications/platform/8/)  
TCK Version, digital SHA-256 fingerprint and download URL:

[Jakarta EE Platform CTS 8.0.2](http://download.eclipse.org/jakartaee/platform/8/eclipse-jakartaeetck-8.0.2.zip) , SHA-256: 14a21b617bb646055c2952f1422ec04a71389fb37301e1c2969f6c3700aee965

Public URL of TCK Results Summary:

[AISWare Flying Server 2.0.0 TCK Results](https://cms.101test.com/ai_sino_info/en_us/preview_content_603710669.html)


Any Additional Specification Certification Requirements:

Jakarta Dependency Injection 1.0 TCK  

See test results in section di.  
Download URL & SHA-256: [jakarta.inject-tck-1.0-bin.zip](https://download.eclipse.org/jakartaee/dependency-injection/1.0/jakarta.inject-tck-1.0-bin.zip), SHA-256: b679bac9b1057df894753892a880ba6ade530607dd811157106ed767aa26481f

Jakarta Contexts and Dependency Injection 2.0 TCK  

See test results in section cdi.  
Download URL & SHA-256: [cdi-tck-2.0.6-dist.zip](https://download.eclipse.org/jakartaee/cdi/2.0/cdi-tck-2.0.6-dist.zip), SHA-256: 75e969a7a3b3c77332154a2008309aad821a923d8684139242048a7640762808

Jakarta Bean Validation 2.0 TCK,  

See test results in section beanvalidation.  
[beanvalidation-tck-dist-2.0.5.zip](https://download.eclipse.org/jakartaee/bean-validation/2.0/beanvalidation-tck-dist-2.0.5.zip), SHA-256: b6778914f78bfcce5d6934347d71502603b1b0a6bbfdfbcf956271c367d40974

Jakarta Batch 1.0 TCK tests are included in Jakarta EE 8 CTS tests, See test results in section jbatch  

Java SE Provider & Version tested with:

OpenJDK Runtime Environment (build 25.262-b02, mixed mode)

Summary of the information for the certification environment:

Apache Derby 10.14.2.0, Linux, 4.19.90-17.ky10.aarch64
Interoperatibility tests carried out against Eclipse Glassfish 5.1.0


## Test results

### appclient
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 50 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 50
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### assembly
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 30 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 30
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```
### compat12
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 12 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 12
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```
### compat13
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 15 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 15
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### concurrency
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 205 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 205
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### connector
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 495 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 495
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb/ee/bb
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 433 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 433
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb/ee/deploy
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 425 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 425
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb/ee/sec
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 208 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 208
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb/ee/timer
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 136 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 136
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb/ee/tx
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 416 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 416
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb/ee/pm
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 188 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 188
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb/ee/webservices
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 3 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 3
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/assembly
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 51 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 51
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/bb
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1200 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1200
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/appexception
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 365 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 365
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/async
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 300 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 300
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/basic
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 105 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 105
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/ejbcontext
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 50 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 50
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/enventry
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 30 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 30
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/interceptor
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 175 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 175
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/lookup
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 30 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 30
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/naming
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 54 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 54
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/nointerface
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 60 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 60
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/packaging
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 211 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 211
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/singleton
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 230 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 230
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/stateful
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 129 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 129
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/tx
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 358 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 358
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/view
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 95 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 95
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/xmloverride
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 30 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 30
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/misc
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 100 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 100
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/sec
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 99 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 99
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/timer
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 178 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 178
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/webservice
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 3 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 3
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/zombie
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb32
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 825 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 825
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### el
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 667 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 667
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### integration
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 18 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 18
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### j2eetools
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 134 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 134
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### javaee
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 24 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 24
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jms/core
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 2379 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 2379
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jms/core20
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 852 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 852
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jms/ee
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 207 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 207
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jms/ee20
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 72 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 72
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jsf
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 5526 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 5526
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jsonb/api
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 224 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 224
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jsonb/cdi
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 6 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 6
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jsonb/customizedmapping
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 344 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 344
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jsonb/defaultmapping
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 488 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 488
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jsonp
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 744 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 744
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jsp
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 731 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 731
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jstl
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 541 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 541
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jta
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 195 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 195
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### samples
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 13 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 13
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### securityapi
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 83 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 83
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### servlet
```console
[javatest.batch] ********************************************************************************
[javatest.batch] Completed running 1746 tests.
[javatest.batch] Number of Tests Passed      = 1746
[javatest.batch] Number of Tests Failed      = 0
[javatest.batch] Number of Tests with Errors = 0
[javatest.batch] ********************************************************************************
```

### rmiiiop
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 129 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 129
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### signaturetest
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 5 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 5
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### websocket
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 745 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 745
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```
### jacc
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 40 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 40
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```
### jaspic
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 68 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 68
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### javamail
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 112 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 112
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jdbc/ee/batchUpdate
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 68 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 68
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jdbc/ee/callStmt
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1592 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1592
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jdbc/ee/connection
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 36 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 36
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jdbc/ee/dateTime
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 152 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 152
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jdbc/ee/dbMeta
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 940 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 940
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jdbc/ee/escapeSyntax
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 324 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 324
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jdbc/ee/exception
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 56 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 56
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jdbc/ee/prepStmt
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1084 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1084
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jdbc/ee/resultSet
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 456 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 456
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jdbc/ee/rsMeta
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 84 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 84
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jdbc/ee/stmt
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 132 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 132
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/annotations
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 902 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 902
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/basic
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 12 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 12
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/cache
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 20 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 20
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/callback
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 396 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 396
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/criteriaapi
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 3732 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 3732
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/derivedid
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 72 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 72
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/EntityGraph
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 78 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 78
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/entityManager
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 193 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 193
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/entityManager2
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 132 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 132
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/entityManagerFactory
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 36 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 36
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/entityManagerFactoryCloseExceptions
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 6 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 6
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/entitytest
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1000 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1000
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/entityTransaction
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 20 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 20
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/enums
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 317 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 317
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/exceptions
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 34 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 34
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/inheritance
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 60 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 60
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/lock
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 34 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 34
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/metamodelapi
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1554 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1554
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/nestedembedding
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 18 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 18
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/override
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 156 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 156
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/persistenceUtil
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 6 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 6
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/persistenceUtilUtil
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 18 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 18
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/query
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1220 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1220
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/relationship
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 198 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 198
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/StoredProcedureQuery
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 226 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 226
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/types
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 300 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 300
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/core/versioning
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 6 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 6
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/ee
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 181 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 181
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa/jpa22
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 100 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 100
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### webservices
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 507 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 507
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### webservices12
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 242 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 242
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### webservices13
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 53 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 53
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### xa
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 66 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 66
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### interop/csiv2/ac_ssl_ssln_upr_noid
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 4 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 4
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### interop/csiv2/ew_ssl_ssln_upn_anonid
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 2 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 2
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### interop/csiv2/ew_ssl_ssln_upn_ccid
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 2 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 2
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### interop/csiv2/ew_ssl_ssln_upn_upid
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 2 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 2
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### interop/csiv2/ew_ssl_sslr_upn_anonid
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 2 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 2
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### interop/csiv2/ew_ssl_sslr_upn_ccid
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 2 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 2
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### interop/csiv2/ew_ssl_sslr_upn_upid
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 2 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 2
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### interop/csiv2/ew_ssln_ssln_upn_anonid
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 2 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 2
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### interop/csiv2/ew_ssln_ssln_upn_ccid
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 2 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 2
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### interop/csiv2/ew_ssln_ssln_upn_upid
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 2 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 2
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### interop/ejb
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 800 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 800
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 480 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 480
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/Association
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 36 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 36
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/Classification
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 32 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 32
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/ClassificationScheme
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 40 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 40
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/Concept
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 60 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 60
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/EmailAddress
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 24 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 24
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/ExtensibleObject
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 16 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 16
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/ExternalIdentifier
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 20 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 20
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/ExternalLink
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 16 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 16
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/ExtrinsicObject
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 4 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 4
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/InternationalString
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 40 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 40
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/Key
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 8 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 8
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/LocalizedString
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 28 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 28
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/Organization
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 84 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 84
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/PersonName
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 16 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 16
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/PostalAddress
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 56 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 56
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/RegistryEntry
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 12 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 12
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/RegistryObject
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 96 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 96
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/RegistryPackage
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 8 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 8
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/Service
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 20 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 20
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/ServiceBinding
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 40 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 40
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/Slot
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 24 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 24
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/SpecificationLink
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 16 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 16
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/TelephoneNumber
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 12 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 12
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/api/javax_xml_registry_infomodel/User
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 32 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 32
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxr/ee
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 152 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 152
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxrpc/api
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 654 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 654
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxrpc/ee/j2w
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 56 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 56
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxrpc/ee/sec
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 24 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 24
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxrpc/ee/w2j
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 128 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 128
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxrpc/ee/wsi
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 324 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 324
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxrpc/wsi
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 292 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 292
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxrs/api
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 996 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 996
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxrs/ee
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1176 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1176
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxrs/jaxrs21
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 184 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 184
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxrs/platform
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 124 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 124
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxrs/servlet3
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 6 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 6
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxrs/spec
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 319 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 319
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jbatch
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 322 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 322
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### beanvalidation
```console
Tests run: 1043, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 1,095.782 sec - in TestSuite

Results :

Tests run: 1043, Failures: 0, Errors: 0, Skipped: 0
```

### cdi
```console
Tests run: 1807, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 1,201.444 sec - in TestSuite

Results :

Tests run: 1807, Failures: 0, Errors: 0, Skipped: 0
```

### di
```console
[INFO] Tests run: 50, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 1.251 s - in SampleBootstrapTCK
```
