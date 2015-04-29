![](http://jenkins.imagej.net/job/pom-fiji/lastBuild/badge/icon)

Maven POM parent for [Fiji projects](https://github.com/fiji),
and for projects wishing to inherit the Fiji
[Bill of Materials](http://imagej.net/BOM).

Projects that use `pom-fiji` as a parent project need to
override the following configuration sections:
* `<name>`
* `<description>`
* `<url>`
* `<inceptionYear>`
* `<organization>`
* `<licenses>`
* `<developers>`
* `<scm>`
* `<issueManagement>`
* `<ciManagement>`
