Jersey Webservice Template JPA Data Model Examples
==================================================

![Java Version Badge][Java Version Badge]
[![Maven Central Version][Maven Central Version Badge]][Maven Central Version URL]
[![GitHub Workflow Status][GitHub Workflow Status]](https://github.com/QubitPi/jersey-webservice-template-jpa-data-models/actions/workflows/ci-cd.yml)
[![GitHub Actions Badge](https://img.shields.io/badge/GitHub%20Actions%20CI/CD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/QubitPi/jersey-webservice-template-jpa-data-models/actions/workflows/ci-cd.yml)
[![Apache License Badge]](https://www.apache.org/licenses/LICENSE-2.0)

This example project serves as an example of how to define [JPA Data Model for JWT]; there also comes with a
production-ready [test framework] to make sure the model compiles with business requirements.

Its CI/CD, as part of this template, will trigger the CI/CD of [test framework] as well to make them a standard
pipeline. See
[Jersey Webservice Template documentation](https://qubitpi.github.io/jersey-webservice-template/docs/elide/configuration#cicd-chain)
on how to configure.

To build the data models, run:

```console
mvn clean package
```

The models in this example has also been published to
[Maven Central](https://central.sonatype.com/artifact/io.github.qubitpi/jersey-webservice-template-jpa-data-models) and
can be imported with the following way for testing purposes

```xml
<dependency>
    <groupId>io.github.qubitpi</groupId>
    <artifactId>jersey-webservice-template-jpa-data-models</artifactId>
    <version>1.0.1</version>
    <scope>test</scope>
</dependency>
```

License
-------

The use and distribution terms for [jersey-webservice-template-jpa-data-models] are covered by the
[Apache License, Version 2.0].

<div align="center">
    <a href="https://opensource.org/licenses">
        <img align="center" width="50%" alt="License Illustration" src="https://github.com/QubitPi/QubitPi/blob/master/img/apache-2.png?raw=true">
    </a>
</div>

[Apache License Badge]: https://img.shields.io/badge/Apache%202.0-F25910.svg?style=for-the-badge&logo=Apache&logoColor=white
[Apache License, Version 2.0]: http://www.apache.org/licenses/LICENSE-2.0.html

[GitHub Workflow Status]: https://img.shields.io/github/actions/workflow/status/QubitPi/jersey-webservice-template-jpa-data-models/ci-cd.yml?branch=master&logo=github&style=for-the-badge

[Java Version Badge]: https://img.shields.io/badge/Java-17-brightgreen?style=for-the-badge&logo=OpenJDK&logoColor=white
[jersey-webservice-template-jpa-data-models]: https://qubitpi.github.io/jersey-webservice-template-jpa-data-models/
[JPA Data Model for JWT]: https://qubitpi.github.io/jersey-webservice-template/docs/elide/data-model

[Maven Central Version Badge]: https://img.shields.io/maven-central/v/io.github.qubitpi/jersey-webservice-template-jpa-data-models?style=for-the-badge&logo=apachemaven&labelColor=1B1C30&color=4D9FEA
[Maven Central Version URL]: https://central.sonatype.com/artifact/io.github.qubitpi/jersey-webservice-template-jpa-data-models

[test framework]: https://github.com/QubitPi/jersey-webservice-template-jpa-data-models-acceptance-tests
