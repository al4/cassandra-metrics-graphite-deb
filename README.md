cassandra-metrics-graphite
==========================

Building
--------

1. Set the version you want to use in both cassandra-metrics-graphite/DEBIAN/control and build.
2. Rename the cassandra-metrics-graphite dir to match the version
3. Place a metrics-graphite jar from [here](http://search.maven.org/#artifactdetails|com.yammer.metrics|metrics-graphite|2.2.0|jar) in usr/share/cassandra/lib
4. Run `build`

Links
-----
* http://www.datastax.com/dev/blog/pluggable-metrics-reporting-in-cassandra-2-0-2
* http://www.sj-vs.net/creating-a-simple-debian-deb-package-based-on-a-directory-structure/
