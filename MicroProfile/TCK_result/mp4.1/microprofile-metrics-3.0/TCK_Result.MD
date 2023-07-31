- [x] Organization Name ("Organization") and, if applicable, URL:<br/>
     AsiaInfo
- [x] Product Name, Version and download URL (if applicable):<br/>
  [flyingserver-mp-v3.5.0](http://www.antdb.net/flyingserver)
- [x] Specification Name, Version and download URL:<br/>
  [microprofile-metrics-3.0](https://download.eclipse.org/microprofile/microprofile-metrics-3.0/microprofile-metrics-spec-3.0.html)
- [x] Public URL of TCK Results Summary:<br/>
  [flyingserver microprofile-metrics-3.0 TCK Result](https://github.com/AsiainfoAnhui/aisware_flyingserver_v2_ee8/blob/master/MicroProfile/TCK_result/mp4.1/microprofile-metrics-3.0/TCK_Result.MD)
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
    <testsuite name="org.eclipse.microprofile.metrics.tck.cdi.ApplicationScopedTimedMethodBeanTest" time="18.41" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="timedMethodNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.cdi.ApplicationScopedTimedMethodBeanTest" time="1.112"></testcase>
        <testcase name="callTimedMethodOnce" classname="org.eclipse.microprofile.metrics.tck.cdi.ApplicationScopedTimedMethodBeanTest" time="0.044"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.cdi.GaugeInjectionBeanTest" time="18.769" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="gaugeCalledWithDefaultValue" classname="org.eclipse.microprofile.metrics.tck.cdi.GaugeInjectionBeanTest" time="1.3">
        </testcase>
        <testcase name="callGaugeAfterSetterCall" classname="org.eclipse.microprofile.metrics.tck.cdi.GaugeInjectionBeanTest" time="0.055"/>
    </testsuite>
    <testsuite  name="org.eclipse.microprofile.metrics.tck.cdi.MeterInjectionBeanTest" time="21.018" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="meteredMethodNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.cdi.MeterInjectionBeanTest" time="1.057">
        </testcase>
        <testcase name="callMeteredMethodOnce" classname="org.eclipse.microprofile.metrics.tck.cdi.MeterInjectionBeanTest" time="0.048"/>
    </testsuite>
    <testsuite  name="org.eclipse.microprofile.metrics.tck.cdi.SimpleTimerInjectionBeanTest" time="20.306" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="simplyTimedMethodNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.cdi.SimpleTimerInjectionBeanTest" time="1.194">
        </testcase>
        <testcase name="callSimplyTimedMethodOnce" classname="org.eclipse.microprofile.metrics.tck.cdi.SimpleTimerInjectionBeanTest" time="2.061"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.cdi.stereotype.StereotypeCountedClassBeanTest" time="19.722" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="testWithMetadata" classname="org.eclipse.microprofile.metrics.tck.cdi.stereotype.StereotypeCountedClassBeanTest" time="1.398">
        </testcase>
        <testcase name="testPlainAnnotation" classname="org.eclipse.microprofile.metrics.tck.cdi.stereotype.StereotypeCountedClassBeanTest" time="0.083"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.cdi.TimerInjectionBeanTest" time="22.098" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="timedMethodNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.cdi.TimerInjectionBeanTest" time="1.245">
        </testcase>
        <testcase name="callTimedMethodOnce" classname="org.eclipse.microprofile.metrics.tck.cdi.TimerInjectionBeanTest" time="2.051"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.inheritance.InheritedGaugeMethodBeanTest" time="20.119" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="gaugesCalledWithDefaultValues" classname="org.eclipse.microprofile.metrics.tck.inheritance.InheritedGaugeMethodBeanTest" time="1.065">
        </testcase>
        <testcase name="callGaugesAfterSetterCalls" classname="org.eclipse.microprofile.metrics.tck.inheritance.InheritedGaugeMethodBeanTest" time="0.086"/>
    </testsuite>
    <testsuite  name="org.eclipse.microprofile.metrics.tck.inheritance.InheritedSimplyTimedMethodBeanTest" time="19.126" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="simplyTimedMethodsNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.inheritance.InheritedSimplyTimedMethodBeanTest" time="1.18">
        </testcase>
        <testcase name="callSimplyTimedMethodsOnce" classname="org.eclipse.microprofile.metrics.tck.inheritance.InheritedSimplyTimedMethodBeanTest" time="0.088"/>
    </testsuite>
    <testsuite  name="org.eclipse.microprofile.metrics.tck.inheritance.InheritedTimedMethodBeanTest" time="19.757" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="timedMethodsNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.inheritance.InheritedTimedMethodBeanTest" time="1.277">
        </testcase>
        <testcase name="callTimedMethodsOnce" classname="org.eclipse.microprofile.metrics.tck.inheritance.InheritedTimedMethodBeanTest" time="0.047"/>
    </testsuite>
    <testsuite  name="org.eclipse.microprofile.metrics.tck.inheritance.VisibilitySimplyTimedMethodBeanTest" time="18.874" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="simplyTimedMethodsNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.inheritance.VisibilitySimplyTimedMethodBeanTest" time="1.29">
        </testcase>
        <testcase name="callSimplyTimedMethodsOnce" classname="org.eclipse.microprofile.metrics.tck.inheritance.VisibilitySimplyTimedMethodBeanTest" time="0.126"/>
    </testsuite>
    <testsuite  name="org.eclipse.microprofile.metrics.tck.inheritance.VisibilityTimedMethodBeanTest" time="18.535" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="timedMethodsNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.inheritance.VisibilityTimedMethodBeanTest" time="0.991">
        </testcase>
        <testcase name="callTimedMethodsOnce" classname="org.eclipse.microprofile.metrics.tck.inheritance.VisibilityTimedMethodBeanTest" time="0.046"/>
    </testsuite>
    <testsuite   name="org.eclipse.microprofile.metrics.tck.MetricFilterTest" time="18.069" tests="1" errors="0" skipped="0" failures="0">
        <testcase name="theAllFilterMatchesAllMetrics" classname="org.eclipse.microprofile.metrics.tck.MetricFilterTest" time="1.083">
        </testcase>
    </testsuite>
    <testsuite   name="org.eclipse.microprofile.metrics.tck.MetricIDTest" time="18.24" tests="1" errors="0" skipped="0" failures="0">
        <testcase name="removalTest" classname="org.eclipse.microprofile.metrics.tck.MetricIDTest" time="1.069">
        </testcase>
    </testsuite>
    <testsuite  name="org.eclipse.microprofile.metrics.tck.MetricRegistryTest" time="21.137" tests="7" errors="0" skipped="0" failures="0">
        <testcase name="nameTest" classname="org.eclipse.microprofile.metrics.tck.MetricRegistryTest" time="1.175">
        </testcase>
        <testcase name="registerTest" classname="org.eclipse.microprofile.metrics.tck.MetricRegistryTest" time="0.049"/>
        <testcase name="removeTest" classname="org.eclipse.microprofile.metrics.tck.MetricRegistryTest" time="0.037"/>
        <testcase name="useExistingMetaDataTest" classname="org.eclipse.microprofile.metrics.tck.MetricRegistryTest" time="0.031"/>
        <testcase name="testMetricRegistryType" classname="org.eclipse.microprofile.metrics.tck.MetricRegistryTest" time="0.029"/>
        <testcase name="sanitizeMetadataTest" classname="org.eclipse.microprofile.metrics.tck.MetricRegistryTest" time="0.029"/>
        <testcase name="conflictingMetadataTest" classname="org.eclipse.microprofile.metrics.tck.MetricRegistryTest" time="0.074"/>
    </testsuite>
    <testsuite  name="org.eclipse.microprofile.metrics.tck.metrics.ConcreteExtendedTimedBeanTest" time="18.952" tests="4" errors="0" skipped="0" failures="0">
        <testcase name="timedMethodNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcreteExtendedTimedBeanTest" time="1.056">
        </testcase>
        <testcase name="extendedTimedMethodNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcreteExtendedTimedBeanTest" time="0.048"/>
        <testcase name="callTimedMethodOnce" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcreteExtendedTimedBeanTest" time="0.045"/>
        <testcase name="callExtendedTimedMethodOnce" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcreteExtendedTimedBeanTest" time="0.032"/>
    </testsuite>
    <testsuite   name="org.eclipse.microprofile.metrics.tck.metrics.ConcreteTimedBeanTest" time="18.909" tests="4" errors="0" skipped="0" failures="0">
        <testcase name="timedMethodNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcreteTimedBeanTest" time="1.067">
        </testcase>
        <testcase name="extendedTimedMethodNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcreteTimedBeanTest" time="0.047"/>
        <testcase name="callTimedMethodOnce" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcreteTimedBeanTest" time="0.036"/>
        <testcase name="callExtendedTimedMethodOnce" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcreteTimedBeanTest" time="0.025"/>
    </testsuite>
    <testsuite  name="org.eclipse.microprofile.metrics.tck.metrics.ConcurrentGaugedClassBeanTest" time="18.547" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="countedMethodsNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcurrentGaugedClassBeanTest" time="1.022">
        </testcase>
        <testcase name="callCountedMethodsOnce" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcurrentGaugedClassBeanTest" time="0.1"/>
    </testsuite>
    <testsuite  name="org.eclipse.microprofile.metrics.tck.metrics.ConcurrentGaugedConstructorBeanTest" time="16.731" tests="1" errors="0" skipped="0" failures="0">
        <testcase name="countedConstructorCalled" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcurrentGaugedConstructorBeanTest" time="1.011">
        </testcase>
    </testsuite>
    <testsuite  name="org.eclipse.microprofile.metrics.tck.metrics.ConcurrentGaugedMethodBeanTest" time="19.393" tests="4" errors="0" skipped="0" failures="0">
        <testcase name="countedMethodNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcurrentGaugedMethodBeanTest" time="1.139">
        </testcase>
        <testcase name="metricInjectionIntoTest" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcurrentGaugedMethodBeanTest" time="0.088"/>
        <testcase name="callCountedMethodOnce" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcurrentGaugedMethodBeanTest" time="0.058"/>
        <testcase name="removeCounterFromRegistry" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcurrentGaugedMethodBeanTest" time="0.05"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.ConcurrentGaugeFunctionalTest" time="103.955" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="testMinMax" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcurrentGaugeFunctionalTest" time="87.171">
        </testcase>
        <testcase name="testConcurrentInvocations" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcurrentGaugeFunctionalTest" time="0.101">
        </testcase>
    </testsuite>
    <testsuite  name="org.eclipse.microprofile.metrics.tck.metrics.ConcurrentGaugeTest" time="19.797" tests="3" errors="0" skipped="0" failures="0">
        <testcase name="getCountTest" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcurrentGaugeTest" time="1.029">
        </testcase>
        <testcase name="incrementTest" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcurrentGaugeTest" time="0.033"/>
        <testcase name="decrementTest" classname="org.eclipse.microprofile.metrics.tck.metrics.ConcurrentGaugeTest" time="0.018"/>
    </testsuite>
    <testsuite  name="org.eclipse.microprofile.metrics.tck.metrics.CountedClassBeanTest" time="19.017" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="countedMethodsNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.metrics.CountedClassBeanTest" time="1.265">
        </testcase>
        <testcase name="callCountedMethodsOnce" classname="org.eclipse.microprofile.metrics.tck.metrics.CountedClassBeanTest" time="0.091"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.CountedMethodBeanTest" time="18.507" tests="4" errors="0" skipped="0" failures="0">
        <testcase name="countedMethodNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.metrics.CountedMethodBeanTest" time="1.102">
        </testcase>
        <testcase name="metricInjectionIntoTest" classname="org.eclipse.microprofile.metrics.tck.metrics.CountedMethodBeanTest" time="0.083"/>
        <testcase name="callCountedMethodOnce" classname="org.eclipse.microprofile.metrics.tck.metrics.CountedMethodBeanTest" time="0.044"/>
        <testcase name="removeCounterFromRegistry" classname="org.eclipse.microprofile.metrics.tck.metrics.CountedMethodBeanTest" time="0.04"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.CountedMethodTagBeanTest" time="19.005" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="counterTagMethodsRegistered" classname="org.eclipse.microprofile.metrics.tck.metrics.CountedMethodTagBeanTest" time="1.033">
        </testcase>
        <testcase name="countedTagMethodNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.metrics.CountedMethodTagBeanTest" time="0.072"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.CounterFieldBeanTest" time="21.765" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="counterFieldRegistered" classname="org.eclipse.microprofile.metrics.tck.metrics.CounterFieldBeanTest" time="1.135">
        </testcase>
        <testcase name="incrementCounterField" classname="org.eclipse.microprofile.metrics.tck.metrics.CounterFieldBeanTest" time="0.037"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.CounterTest" time="18.539" tests="3" errors="0" skipped="0" failures="0">
        <testcase name="getCountTest" classname="org.eclipse.microprofile.metrics.tck.metrics.CounterTest" time="1.026">
        </testcase>
        <testcase name="incrementTest" classname="org.eclipse.microprofile.metrics.tck.metrics.CounterTest" time="0.037"/>
        <testcase name="incrementLongTest" classname="org.eclipse.microprofile.metrics.tck.metrics.CounterTest" time="0.047"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.DefaultNameMetricMethodBeanTest" time="19.227" tests="1" errors="0" skipped="0" failures="0">
        <testcase name="metricMethodsWithDefaultNamingConvention" classname="org.eclipse.microprofile.metrics.tck.metrics.DefaultNameMetricMethodBeanTest" time="1.091">
        </testcase>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.GaugeMethodBeanTest" time="18.753" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="gaugeCalledWithDefaultValue" classname="org.eclipse.microprofile.metrics.tck.metrics.GaugeMethodBeanTest" time="1.126">
        </testcase>
        <testcase name="callGaugeAfterSetterCall" classname="org.eclipse.microprofile.metrics.tck.metrics.GaugeMethodBeanTest" time="0.103"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.GaugeTest" time="18.16" tests="1" errors="0" skipped="0" failures="0">
        <testcase name="testManualGauge" classname="org.eclipse.microprofile.metrics.tck.metrics.GaugeTest" time="0.968">
        </testcase>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.HistogramFieldBeanTest" time="19.257" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="histogramFieldRegistered" classname="org.eclipse.microprofile.metrics.tck.metrics.HistogramFieldBeanTest" time="1.026">
        </testcase>
        <testcase name="updateHistogramField" classname="org.eclipse.microprofile.metrics.tck.metrics.HistogramFieldBeanTest" time="0.051"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.HistogramTest" time="18.509" tests="15" errors="0" skipped="0" failures="0">
        <testcase name="testSum" classname="org.eclipse.microprofile.metrics.tck.metrics.HistogramTest" time="1.077">
        </testcase>
        <testcase name="testCount" classname="org.eclipse.microprofile.metrics.tck.metrics.HistogramTest" time="0.085"/>
        <testcase name="testSnapshot99thPercentile" classname="org.eclipse.microprofile.metrics.tck.metrics.HistogramTest" time="0.051"/>
        <testcase name="testSnapshotMax" classname="org.eclipse.microprofile.metrics.tck.metrics.HistogramTest" time="0.029"/>
        <testcase name="testSnapshotMin" classname="org.eclipse.microprofile.metrics.tck.metrics.HistogramTest" time="0.031"/>
        <testcase name="testSnapshot98thPercentile" classname="org.eclipse.microprofile.metrics.tck.metrics.HistogramTest" time="0.031"/>
        <testcase name="testSnapshotMean" classname="org.eclipse.microprofile.metrics.tck.metrics.HistogramTest" time="0.036"/>
        <testcase name="testSnapshotSize" classname="org.eclipse.microprofile.metrics.tck.metrics.HistogramTest" time="0.037"/>
        <testcase name="testSnapshot95thPercentile" classname="org.eclipse.microprofile.metrics.tck.metrics.HistogramTest" time="0.041"/>
        <testcase name="testMetricRegistry" classname="org.eclipse.microprofile.metrics.tck.metrics.HistogramTest" time="0.093"/>
        <testcase name="testSnapshotMedian" classname="org.eclipse.microprofile.metrics.tck.metrics.HistogramTest" time="0.073"/>
        <testcase name="testSnapshotStdDev" classname="org.eclipse.microprofile.metrics.tck.metrics.HistogramTest" time="0.069"/>
        <testcase name="testSnapshotValues" classname="org.eclipse.microprofile.metrics.tck.metrics.HistogramTest" time="0.092"/>
        <testcase name="testSnapshot999thPercentile" classname="org.eclipse.microprofile.metrics.tck.metrics.HistogramTest" time="0.052"/>
        <testcase name="testSnapshot75thPercentile" classname="org.eclipse.microprofile.metrics.tck.metrics.HistogramTest" time="0.06"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.MeteredClassBeanTest" time="20.892" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="meteredMethodsNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.metrics.MeteredClassBeanTest" time="1.179">
        </testcase>
        <testcase name="callMeteredMethodsOnce" classname="org.eclipse.microprofile.metrics.tck.metrics.MeteredClassBeanTest" time="0.054"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.MeteredConstructorBeanTest" time="17.38" tests="1" errors="0" skipped="0" failures="0">
        <testcase name="meteredConstructorCalled" classname="org.eclipse.microprofile.metrics.tck.metrics.MeteredConstructorBeanTest" time="1.202">
        </testcase>
    </testsuite>
    <testsuite  name="org.eclipse.microprofile.metrics.tck.metrics.MeteredMethodBeanTest" time="20.856" tests="3" errors="0" skipped="0" failures="0">
        <testcase name="meteredMethodNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.metrics.MeteredMethodBeanTest" time="1.905">
        </testcase>
        <testcase name="callMeteredMethodOnce" classname="org.eclipse.microprofile.metrics.tck.metrics.MeteredMethodBeanTest" time="0.096"/>
        <testcase name="removeMeterFromRegistry" classname="org.eclipse.microprofile.metrics.tck.metrics.MeteredMethodBeanTest" time="0.064"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.MeterTest" time="92.828" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="testCount" classname="org.eclipse.microprofile.metrics.tck.metrics.MeterTest" time="1.103">
        </testcase>
        <testcase name="testRates" classname="org.eclipse.microprofile.metrics.tck.metrics.MeterTest" time="75.167"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.MultipleMetricsConstructorBeanTest" time="19.6" tests="1" errors="0" skipped="0" failures="0">
        <testcase name="metricsConstructorCalled" classname="org.eclipse.microprofile.metrics.tck.metrics.MultipleMetricsConstructorBeanTest" time="1.12">
        </testcase>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.MultipleMetricsMethodBeanTest" time="17.712" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="metricsMethodNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.metrics.MultipleMetricsMethodBeanTest" time="1.356">
        </testcase>
        <testcase name="callMetricsMethodOnce" classname="org.eclipse.microprofile.metrics.tck.metrics.MultipleMetricsMethodBeanTest" time="0.078"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.OverloadedTimedMethodBeanTest" time="18.833" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="overloadedTimedMethodNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.metrics.OverloadedTimedMethodBeanTest" time="0.991">
        </testcase>
        <testcase name="callOverloadedTimedMethodOnce" classname="org.eclipse.microprofile.metrics.tck.metrics.OverloadedTimedMethodBeanTest" time="0.065"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.SimpleTimerFieldBeanTest" time="20.809" tests="1" errors="0" skipped="0" failures="0">
        <testcase name="simpleTimerFieldsWithDefaultNamingConvention" classname="org.eclipse.microprofile.metrics.tck.metrics.SimpleTimerFieldBeanTest" time="1.313">
        </testcase>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.SimpleTimerFunctionalTest" time="101.894" tests="1" errors="0" skipped="0" failures="0">
        <testcase name="testMinMaxEqual" classname="org.eclipse.microprofile.metrics.tck.metrics.SimpleTimerFunctionalTest" time="83.798">
        </testcase>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.SimpleTimerTest" time="19.323" tests="4" errors="0" skipped="0" failures="0">
        <testcase name="testTime" classname="org.eclipse.microprofile.metrics.tck.metrics.SimpleTimerTest" time="2.055">
        </testcase>
        <testcase name="testTimerRegistry" classname="org.eclipse.microprofile.metrics.tck.metrics.SimpleTimerTest" time="0.032"/>
        <testcase name="timesCallableInstances" classname="org.eclipse.microprofile.metrics.tck.metrics.SimpleTimerTest" time="0.056"/>
        <testcase name="timesRunnableInstances" classname="org.eclipse.microprofile.metrics.tck.metrics.SimpleTimerTest" time="0.053"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.SimplyTimedClassBeanTest" time="18.548" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="simplyTimedMethodsNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.metrics.SimplyTimedClassBeanTest" time="1.038">
        </testcase>
        <testcase name="callSimplyTimedMethodsOnce" classname="org.eclipse.microprofile.metrics.tck.metrics.SimplyTimedClassBeanTest" time="0.039"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.SimplyTimedConstructorBeanTest" time="20.259" tests="1" errors="0" skipped="0" failures="0">
        <testcase name="simpleTimerConstructorCalled" classname="org.eclipse.microprofile.metrics.tck.metrics.SimplyTimedConstructorBeanTest" time="1.077">
        </testcase>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.SimplyTimedMethodBeanLookupTest" time="19.845" tests="3" errors="0" skipped="0" failures="0">
        <testcase name="simplyTimedMethodNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.metrics.SimplyTimedMethodBeanLookupTest" time="1.198">
        </testcase>
        <testcase name="callSimplyTimedMethodOnce" classname="org.eclipse.microprofile.metrics.tck.metrics.SimplyTimedMethodBeanLookupTest" time="2.058"/>
        <testcase name="removeSimplyTimedFromRegistry" classname="org.eclipse.microprofile.metrics.tck.metrics.SimplyTimedMethodBeanLookupTest" time="0.042"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.SimplyTimedMethodBeanTest" time="21.479" tests="3" errors="0" skipped="0" failures="0">
        <testcase name="simplyTimedMethodNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.metrics.SimplyTimedMethodBeanTest" time="0.983">
        </testcase>
        <testcase name="callSimplyTimedMethodOnce" classname="org.eclipse.microprofile.metrics.tck.metrics.SimplyTimedMethodBeanTest" time="2.067"/>
        <testcase name="removeSimpleTimerFromRegistry" classname="org.eclipse.microprofile.metrics.tck.metrics.SimplyTimedMethodBeanTest" time="0.043"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.TimedClassBeanTest" time="18.907" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="timedMethodsNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.metrics.TimedClassBeanTest" time="1.118">
        </testcase>
        <testcase name="callTimedMethodsOnce" classname="org.eclipse.microprofile.metrics.tck.metrics.TimedClassBeanTest" time="0.069"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.TimedConstructorBeanTest" time="19.39" tests="1" errors="0" skipped="0" failures="0">
        <testcase name="timedConstructorCalled" classname="org.eclipse.microprofile.metrics.tck.metrics.TimedConstructorBeanTest" time="1.311">
        </testcase>
    </testsuite>
    <testsuite  name="org.eclipse.microprofile.metrics.tck.metrics.TimedMethodBeanLookupTest" time="21.195" tests="3" errors="0" skipped="0" failures="0">
        <testcase name="timedMethodNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.metrics.TimedMethodBeanLookupTest" time="1.227">
        </testcase>
        <testcase name="callTimedMethodOnce" classname="org.eclipse.microprofile.metrics.tck.metrics.TimedMethodBeanLookupTest" time="2.039"/>
        <testcase name="removeTimerFromRegistry" classname="org.eclipse.microprofile.metrics.tck.metrics.TimedMethodBeanLookupTest" time="0.04"/>
    </testsuite>
    <testsuite  name="org.eclipse.microprofile.metrics.tck.metrics.TimedMethodBeanTest" time="20.478" tests="3" errors="0" skipped="0" failures="0">
        <testcase name="timedMethodNotCalledYet" classname="org.eclipse.microprofile.metrics.tck.metrics.TimedMethodBeanTest" time="1.039">
        </testcase>
        <testcase name="callTimedMethodOnce" classname="org.eclipse.microprofile.metrics.tck.metrics.TimedMethodBeanTest" time="2.041"/>
        <testcase name="removeTimerFromRegistry" classname="org.eclipse.microprofile.metrics.tck.metrics.TimedMethodBeanTest" time="0.039"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.TimerFieldBeanTest" time="18.717" tests="1" errors="0" skipped="0" failures="0">
        <testcase name="timerFieldsWithDefaultNamingConvention" classname="org.eclipse.microprofile.metrics.tck.metrics.TimerFieldBeanTest" time="1.087">
        </testcase>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.metrics.TimerTest" time="95.18" tests="17" errors="0" skipped="0" failures="0">
        <testcase name="testSnapshot99thPercentile" classname="org.eclipse.microprofile.metrics.tck.metrics.TimerTest" time="0.952">
        </testcase>
        <testcase name="testSnapshotMax" classname="org.eclipse.microprofile.metrics.tck.metrics.TimerTest" time="0.031"/>
        <testcase name="testSnapshotMin" classname="org.eclipse.microprofile.metrics.tck.metrics.TimerTest" time="0.032"/>
        <testcase name="testSnapshot98thPercentile" classname="org.eclipse.microprofile.metrics.tck.metrics.TimerTest" time="0.036"/>
        <testcase name="testSnapshotMean" classname="org.eclipse.microprofile.metrics.tck.metrics.TimerTest" time="0.033"/>
        <testcase name="testSnapshotSize" classname="org.eclipse.microprofile.metrics.tck.metrics.TimerTest" time="0.022"/>
        <testcase name="testSnapshot95thPercentile" classname="org.eclipse.microprofile.metrics.tck.metrics.TimerTest" time="0.031"/>
        <testcase name="testSnapshotMedian" classname="org.eclipse.microprofile.metrics.tck.metrics.TimerTest" time="0.026"/>
        <testcase name="testSnapshotStdDev" classname="org.eclipse.microprofile.metrics.tck.metrics.TimerTest" time="0.02"/>
        <testcase name="testSnapshotValues" classname="org.eclipse.microprofile.metrics.tck.metrics.TimerTest" time="0.027"/>
        <testcase name="testSnapshot999thPercentile" classname="org.eclipse.microprofile.metrics.tck.metrics.TimerTest" time="0.018"/>
        <testcase name="testSnapshot75thPercentile" classname="org.eclipse.microprofile.metrics.tck.metrics.TimerTest" time="0.02"/>
        <testcase name="testRate" classname="org.eclipse.microprofile.metrics.tck.metrics.TimerTest" time="75.113"/>
        <testcase name="testTime" classname="org.eclipse.microprofile.metrics.tck.metrics.TimerTest" time="1.024">
        </testcase>
        <testcase name="testTimerRegistry" classname="org.eclipse.microprofile.metrics.tck.metrics.TimerTest" time="0.017"/>
        <testcase name="timesCallableInstances" classname="org.eclipse.microprofile.metrics.tck.metrics.TimerTest" time="0.054"/>
        <testcase name="timesRunnableInstances" classname="org.eclipse.microprofile.metrics.tck.metrics.TimerTest" time="0.022"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.tags.CounterFieldTagBeanTest" time="19.871" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="counterTagFieldsRegistered" classname="org.eclipse.microprofile.metrics.tck.tags.CounterFieldTagBeanTest" time="1.174">
        </testcase>
        <testcase name="incrementCounterTagFields" classname="org.eclipse.microprofile.metrics.tck.tags.CounterFieldTagBeanTest" time="0.066"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.tags.GaugeTagMethodBeanTest" time="18.021" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="gaugeTagCalledWithDefaultValue" classname="org.eclipse.microprofile.metrics.tck.tags.GaugeTagMethodBeanTest" time="1.02">
        </testcase>
        <testcase name="callGaugeTagAfterSetterCall" classname="org.eclipse.microprofile.metrics.tck.tags.GaugeTagMethodBeanTest" time="0.03"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.tags.HistogramTagFieldBeanTest" time="18.044" tests="2" errors="0" skipped="0" failures="0">
        <testcase name="histogramTagFieldRegistered" classname="org.eclipse.microprofile.metrics.tck.tags.HistogramTagFieldBeanTest" time="1.115">
        </testcase>
        <testcase name="updateHistogramTagField" classname="org.eclipse.microprofile.metrics.tck.tags.HistogramTagFieldBeanTest" time="0.032"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.tags.MeteredTagMethodBeanTest" time="23.337" tests="1" errors="0" skipped="0" failures="0">
        <testcase name="meteredTagMethodRegistered" classname="org.eclipse.microprofile.metrics.tck.tags.MeteredTagMethodBeanTest" time="1.597">
        </testcase>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.tags.SimplerTimerTagFieldBeanTest" time="18.743" tests="1" errors="0" skipped="0" failures="0">
        <testcase name="simpleTimersTagFieldRegistered" classname="org.eclipse.microprofile.metrics.tck.tags.SimplerTimerTagFieldBeanTest" time="1.145">
        </testcase>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.tags.SimplyTimedTagMethodBeanTest" time="19.569" tests="1" errors="0" skipped="0" failures="0">
        <testcase name="simplyTimedTagMethodRegistered" classname="org.eclipse.microprofile.metrics.tck.tags.SimplyTimedTagMethodBeanTest" time="1.114">
        </testcase>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.tags.TagsTest" time="18.635" tests="8" errors="0" skipped="0" failures="0">
        <testcase name="simpleTagTest" classname="org.eclipse.microprofile.metrics.tck.tags.TagsTest" time="1.419">
        </testcase>
        <testcase name="lastTagValueTest" classname="org.eclipse.microprofile.metrics.tck.tags.TagsTest" time="0.084"/>
        <testcase name="counterTagsTest" classname="org.eclipse.microprofile.metrics.tck.tags.TagsTest" time="0.039"/>
        <testcase name="meterTagsTest" classname="org.eclipse.microprofile.metrics.tck.tags.TagsTest" time="0.052"/>
        <testcase name="timerTagsTest" classname="org.eclipse.microprofile.metrics.tck.tags.TagsTest" time="0.036"/>
        <testcase name="histogramTagsTest" classname="org.eclipse.microprofile.metrics.tck.tags.TagsTest" time="0.047"/>
        <testcase name="simpleTimerTagsTest" classname="org.eclipse.microprofile.metrics.tck.tags.TagsTest" time="0.037"/>
        <testcase name="concurrentGuageTagsTest" classname="org.eclipse.microprofile.metrics.tck.tags.TagsTest" time="0.036"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.tags.TimedTagMethodBeanTest" time="21.249" tests="1" errors="0" skipped="0" failures="0">
        <testcase name="timedTagMethodRegistered" classname="org.eclipse.microprofile.metrics.tck.tags.TimedTagMethodBeanTest" time="1.038">
        </testcase>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.tck.tags.TimerTagFieldBeanTest" time="21.022" tests="1" errors="0" skipped="0" failures="0">
        <testcase name="timersTagFieldRegistered" classname="org.eclipse.microprofile.metrics.tck.tags.TimerTagFieldBeanTest" time="1.175">
        </testcase>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.test.MpMetricTest" time="24.605" tests="47" errors="0" skipped="0" failures="0">
        <testcase name="testApplicationJsonResponseContentType" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.342">
        </testcase>
        <testcase name="testTextPlainResponseContentType" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.051"/>
        <testcase name="testBadSubTreeWillReturn404" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.047"/>
        <testcase name="testListsAllJson" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.817"/>
        <testcase name="testBase" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.059"/>
        <testcase name="testBaseOpenMetrics" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.028"/>
        <testcase name="testBaseAttributeJson" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.023"/>
        <testcase name="testBaseSingularMetricsPresent" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.04"/>
        <testcase name="testBaseAttributeOpenMetrics" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.017"/>
        <testcase name="testBaseMetadata" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.054"/>
        <testcase name="testBaseMetadataSingluarItems" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.047"/>
        <testcase name="testBaseMetadataTypeAndUnit" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.054"/>
        <testcase name="testOpenMetricsFormatNoBadChars" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.022"/>
        <testcase name="testBaseMetadataSingluarItemsOpenMetrics" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.062"/>
        <testcase name="testBaseMetadataGarbageCollection" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.041"/>
        <testcase name="testApplicationMetadataOkJson" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.013"/>
        <testcase name="testSetupApplicationMetrics" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="1.668"/>
        <testcase name="testApplicationMetricsJSON" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.959"/>
        <testcase name="testApplicationMetadataItems" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.052"/>
        <testcase name="testApplicationMetadataTypeAndUnit" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.054"/>
        <testcase name="testApplicationTagJson" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.049"/>
        <testcase name="testApplicationTagOpenMetrics" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.012"/>
        <testcase name="testApplicationMeterUnitOpenMetrics" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.013"/>
        <testcase name="testApplicationTimerUnitOpenMetrics" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.026"/>
        <testcase name="testApplicationHistogramUnitBytesOpenMetrics" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.017"/>
        <testcase name="testApplicationHistogramUnitNoneOpenMetrics" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.02"/>
        <testcase name="testOpenMetrics406ForOptions" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.011"/>
        <testcase name="testConvertingToBaseUnit" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.032"/>
        <testcase name="testNonStandardUnitsJSON" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.026"/>
        <testcase name="testNonStandardUnitsOpenMetrics" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.014"/>
        <testcase name="testOptionalBaseMetrics" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.044"/>
        <testcase name="testSetupPromNoBadCharsInNames" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.034"/>
        <testcase name="testPromNoBadCharsInNames" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.046"/>
        <testcase name="testAccept1" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.014"/>
        <testcase name="testAccept2" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.015"/>
        <testcase name="testAccept3" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.014"/>
        <testcase name="testAccept4" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.023"/>
        <testcase name="testAccept5" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.02"/>
        <testcase name="testNoAcceptHeader" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.018"/>
        <testcase name="testCustomUnitAppendToGaugeName" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.027"/>
        <testcase name="testNoCustomUnitForCounter" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.033"/>
        <testcase name="testGcCountMetrics" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.021"/>
        <testcase name="testGcTimeMetrics" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.022"/>
        <testcase name="testMultipleTaggedMetricsJSON" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="1.524"/>
        <testcase name="testTranslateSemiColonToUnderScoreJSON" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.06"/>
        <testcase name="testApplicationConcurrentGaugeOpenMetrics" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.012"/>
        <testcase name="testApplicationSimpleTimerUnitOpenMetrics" classname="org.eclipse.microprofile.metrics.test.MpMetricTest" time="0.012"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.test.multipleinstances.MultipleBeanInstancesTest" time="20.467" tests="3" errors="0" skipped="0" failures="0">
        <testcase name="testMeter" classname="org.eclipse.microprofile.metrics.test.multipleinstances.MultipleBeanInstancesTest" time="1.485">
        </testcase>
        <testcase name="testTimer" classname="org.eclipse.microprofile.metrics.test.multipleinstances.MultipleBeanInstancesTest" time="0.085"/>
        <testcase name="testCounter" classname="org.eclipse.microprofile.metrics.test.multipleinstances.MultipleBeanInstancesTest" time="0.062"/>
    </testsuite>
    <testsuite name="org.eclipse.microprofile.metrics.test.ReusedMetricsTest" time="24.469" tests="4" errors="0" skipped="0" failures="0">
        <testcase name="setA" classname="org.eclipse.microprofile.metrics.test.ReusedMetricsTest" time="1.104">
        </testcase>
        <testcase name="testSharedCounter" classname="org.eclipse.microprofile.metrics.test.ReusedMetricsTest" time="3.409"/>
        <testcase name="setB" classname="org.eclipse.microprofile.metrics.test.ReusedMetricsTest" time="0.027"/>
        <testcase name="testSharedCounterAgain" classname="org.eclipse.microprofile.metrics.test.ReusedMetricsTest" time="0.128"/>
    </testsuite>
</testsuites>
```