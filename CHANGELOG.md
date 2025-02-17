# CHANGELOG

## 0.2.0

* Added support for SCRAM-SHA-256 and SCRAM-SHA-512 authentication (#130)
* Added Python script tool to calculate latencies and quantiles from canary log for producer, consumer and connection buckets
* Turned off producer retry and added a consumer error metric (#133)
* Updated dependency to Sarama 1.30.0 with Kafka 3.0.0 support (#134)
* Fixed connection check service missing latency metrics for one broker (#141)
* Fixed wrong content type "text/plain" returned by status endpoint instead of "application/json" (#144)
* Fixed canary not recovering after a "connection reset by peer" from brokers (#148)

## 0.1.0

First implementation.
