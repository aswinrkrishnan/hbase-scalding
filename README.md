hbase-scalding
==============

Project template for anyone wanting to write scalding jobs while keeping scalding as a dependency, instead of mixing in their own files into the scalding project. Also includes minimal support for HBase sources and sinks.

Simply add a file in src/main/scala/jobs, import com.twitter.scalding._, and make sure the class inside extends Job.
