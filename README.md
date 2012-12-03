maven
========

Maven Repository for my Java/Scala projects. To use this repository
from SBT add one of the following line to your build.sbt file:

Releases:

   resolvers += "kydos-repo" at "http://kydos.github.com/maven/releases"	

Snapshots:

   resolvers += "kydos-repo" at "http://kydos.github.com/maven/releases"


Then you can add dependencies to specific projects, see examples
below.

escalier:
  libraryDependencies += "net.icorsaro" % "escalier_2.9.2" % "0.6.0"

dds-psm-java:
  libraryDependencies += "org.omg" % "dds-psm-java_2.10" % "1.0"

