# GitHub
## micrometer-core
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
io.micrometer.core.instrument.binder.jvm.ExecutorServiceMetrics
io.micrometer.core.instrument.binder.jvm.JvmGcMetrics
io.micrometer.core.instrument.binder.tomcat.TomcatMetrics
io.micrometer.core.instrument.config.MeterFilter
io.micrometer.core.instrument.config.NamingConvention
io.micrometer.core.instrument.distribution.CountAtBucket
io.micrometer.core.instrument.distribution.HistogramGauges
io.micrometer.core.instrument.distribution.HistogramSnapshot
io.micrometer.core.instrument.distribution.HistogramSupport
io.micrometer.core.instrument.distribution.ValueAtPercentile
io.micrometer.core.instrument.internal.Mergeable
io.micrometer.core.instrument.internal.TimedExecutor
io.micrometer.core.instrument.internal.TimedExecutorService
io.micrometer.core.instrument.util.JsonUtils
io.micrometer.core.instrument.util.MeterPartition
io.micrometer.core.ipc.http.OkHttpSender
```

## micrometer-registry-appoptics
```
io.micrometer.appoptics.AppOpticsConfig
io.micrometer.appoptics.AppOpticsMeterRegistry
io.micrometer.appoptics.AppOpticsNamingConvention
```

## micrometer-registry-cloudwatch2
### main
```
io.micrometer.cloudwatch2.CloudWatchConfig
io.micrometer.cloudwatch2.CloudWatchMeterRegistry
io.micrometer.cloudwatch2.CloudWatchUtils
io.micrometer.cloudwatch2.package-info
```

### test
```
io.micrometer.cloudwatch2.CloudWatchMeterRegistryCompatibilityTest
io.micrometer.cloudwatch2.CloudWatchMeterRegistryTest
io.micrometer.cloudwatch2.CloudWatchUtilsTest
```

## micrometer-registry-elastic
### main
```
io.micrometer.elastic.ElasticConfig
io.micrometer.elastic.ElasticMeterRegistry
io.micrometer.elastic.ElasticNamingConvention
```

### test
```
io.micrometer.elastic.ElasticMeterRegistryTest
```

## micrometer-registry-ganglia
```
io.micrometer.ganglia.GangliaMeterRegistry
```

## micrometer-registry-graphite
```
io.micrometer.graphite.GraphiteMeterRegistry
```

## etc.
* https://github.com/micrometer-metrics/micrometer/blob/master/README.md

## Wiki
* Releasing Micrometer
  * https://github.com/micrometer-metrics/micrometer/wiki/Releasing-Micrometer
* Migration guides
  * [1.13 Migration Guide](https://github.com/micrometer-metrics/micrometer/wiki/1.13-Migration-Guide)
* [Performance: criticality of code paths](https://github.com/micrometer-metrics/micrometer/wiki/Performance:-criticality-of-code-paths)
