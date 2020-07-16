=====
Maven
=====
Glotto uses the `Maven Wrapper <https://github.com/takari/maven-wrapper>`_ for builds.

* Run ``./mvnw -N io.takari:maven:0.7.7:wrapper -Dmaven=$VERSION`` to update the wrapper script.

=======
Linting
=======
* Run ``./mvnw spotbugs:spotbugs`` to run static analysis.
* Run ``./mvnw checkstyle:check`` to run checkstyle.

========
Releases
========
* Run ``./mvnw versions:set -DnewVersion=$VERSION`` to update the version.
* Run ``./mvnw versions:commit`` to commit version changes.
* Run ``./mvnw versions:display-plugin-updates`` to analyze the project for out of date plugins.
