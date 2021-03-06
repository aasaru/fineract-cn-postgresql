# Apache Fineract CN PostgreSQL [![Build Status](https://api.travis-ci.com/apache/fineract-cn-postgresql.svg?branch=develop)](https://travis-ci.com/apache/fineract-cn-postgresql)

For fineract-cn-* repositories this library provides tenant-separation based on header contents.
[Read more](https://cwiki.apache.org/confluence/display/FINERACT/Fineract+CN+Project+Structure#FineractCNProjectStructure-postgresqlDBanddatapersistence).

## Abstract
Apache Fineract CN is an application framework for digital financial services, a system to support nationwide and cross-national financial transactions and help to level and speed the creation of an inclusive, interconnected digital economy for every nation in the world.

## Prerequisites
### Runtime
Install Java 8 as described at https://docs.oracle.com/javase/8/docs/technotes/guides/install/install_overview.html.

### Installation
Install PostgreSQL as described at 
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-16-04.

## Multi-tenancy
Multi-tenancy is reached by providing separate data storage on a per tenant basis.

For every tenant a new database instance is created internally. A tenant aware component provides transparent access to these resources.

## Versioning
The version numbers follow the [Semantic Versioning](http://semver.org/) scheme.

In addition to MAJOR.MINOR.PATCH the following postfixes are used to indicate the development state.

* BUILD-SNAPSHOT - A release currently in development. 
* RELEASE - _General availability_ indicates that this release is the best available version and is recommended for all usage.

The versioning layout is {MAJOR}.{MINOR}.{PATCH}-{INDICATOR}[.{PATCH}]. Only milestones and release candidates can  have patch versions. Some examples:

1.2.3-BUILD-SNAPSHOT  
1.3.5-RELEASE

## License
See [LICENSE](LICENSE) file.
