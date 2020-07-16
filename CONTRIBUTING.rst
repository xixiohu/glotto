=======
Linting
=======
* Run ``mvn spotbugs:spotbugs`` to run static analysis.
* Run ``mvn checkstyle:check`` to run checkstyle.

========
Releases
========
* Run ``mvn versions:set -DnewVersion=<version>`` to update the version.
* Run ``mvn versions:commit`` to commit version changes.
* Run ``mvn versions:display-plugin-updates`` to analyze the project for out of date plugins.
