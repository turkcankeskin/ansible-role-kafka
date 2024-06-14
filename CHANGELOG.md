### 0.9.0 (Jun 14, 2024)

* Fix issue with checking if `kafka_node_id` is integer.

### 0.8.0 (May 27, 2024)

* Fix issue with ordering of servers. It could happen that for some tasks where `run_once` is used when action is required to run on controller to be actually run on broker only if such instance is present.

### 0.7.0 (April 18, 2024)

* Updated default kafka version to 3.7.0 -- [Release notes](https://kafka.apache.org/blog#apache_kafka_370_release_announcement)
* Remove `kafka_checksum` variable and get checksum from kafka download page.

### 0.6.0 (December 19, 2023)

* Updated default kafka version to 3.6.1 -- [Release notes](https://downloads.apache.org/kafka/3.6.1/RELEASE_NOTES.html)

### 0.5.0 (November 07, 2023)

* Updated default kafka version to 3.6.0 -- [Release announcement](https://kafka.apache.org/blog#apache_kafka_360_release_announcement)

### 0.4.0 (September 12, 2023)

* Added `kafka_opts` variable which later creates `KAFKA_OPTS` environment variable for specifying additional kafka options.

### 0.3.0 (August 10, 2023)

* Added additional variable which can be used to provide config parameters that are not defined in role.
* Updated default kafka version to 3.5.1 -- [Release announcement](https://kafka.apache.org/blog#apache_kafka_351_release_announcement)

### 0.2.0 (July 03, 2023)

* Updated default kafka version to 3.5.0 -- [Release announcement](https://kafka.apache.org/blog#apache_kafka_350_release_announcement)
* Updated molecule configuration to install dependencies by default in order for tests to work out of box.

### 0.0.1 (May 25, 2023)

* Ansible kafka role init.
