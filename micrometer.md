# Micrometer
## Home
* https://micrometer.io/

## Documentation
* Home
  * https://micrometer.io/docs
* Installing
  * https://micrometer.io/docs/installing
* Concepts
  * https://micrometer.io/docs/concepts
* Setup
  * Datadog
    * https://micrometer.io/docs/registry/datadog
  * Graphite
    * https://micrometer.io/docs/registry/graphite
  * JMX
    * https://micrometer.io/docs/registry/jmx
  * StatsD
    * https://micrometer.io/docs/registry/statsD
* Guides
  * Passing through to Dropwizard's console reporter
    * http://micrometer.io/docs/guide/consoleReporter

## GitHub
### micrometer-core
```
io.micrometer.core.instrument.AbstractMeter
io.micrometer.core.instrument.AbstractTimer
io.micrometer.core.instrument.Clock
io.micrometer.core.instrument.Counter
io.micrometer.core.instrument.Gauge
io.micrometer.core.instrument.ImmutableTag
io.micrometer.core.instrument.Measurement
io.micrometer.core.instrument.Meter
io.micrometer.core.instrument.Statistic
io.micrometer.core.instrument.StrongReferenceGaugeFunction
io.micrometer.core.instrument.Tag
io.micrometer.core.instrument.Tags
io.micrometer.core.instrument.binder.MeterBinder
io.micrometer.core.instrument.binder.jvm.JvmGcMetrics
io.micrometer.core.instrument.binder.tomcat.TomcatMetrics
io.micrometer.core.instrument.config.MeterFilter
io.micrometer.core.instrument.config.NamingConvention
io.micrometer.core.instrument.distribution.CountAtBucket
io.micrometer.core.instrument.distribution.HistogramGauges
io.micrometer.core.instrument.distribution.ValueAtPercentile
io.micrometer.core.instrument.util.JsonUtils
io.micrometer.core.ipc.http.OkHttpSender
```

### micrometer-registry-appoptics
```
io.micrometer.appoptics.AppOpticsConfig
io.micrometer.appoptics.AppOpticsMeterRegistry
io.micrometer.appoptics.AppOpticsNamingConvention
```

### micrometer-registry-elastic
#### main
```
io.micrometer.elastic.ElasticConfig
io.micrometer.elastic.ElasticMeterRegistry
io.micrometer.elastic.ElasticNamingConvention
```

#### test
```
io.micrometer.elastic.ElasticMeterRegistryTest
```

### micrometer-registry-ganglia
```
io.micrometer.ganglia.GangliaMeterRegistry
```

### micrometer-registry-graphite
```
io.micrometer.graphite.GraphiteMeterRegistry
```

### etc.
* https://github.com/micrometer-metrics/micrometer/blob/master/README.md

### Wiki
* Releasing Micrometer
  * https://github.com/micrometer-metrics/micrometer/wiki/Releasing-Micrometer
