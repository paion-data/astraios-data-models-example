astraios.io Data Models Example
===============================

![Java Version Badge][Java Version Badge]
[![Javadoc][Javadoc Badge]][Javadoc URL]
[![Maven Central Version][Maven Central Version Badge]][Maven Central Version URL]
[![GitHub Workflow Status][GitHub Workflow Status]][GitHub Workflow Status URL]
[![Apache License][Apache License Badge]][Apache License, Version 2.0]

This project serves as an example of how to define [JPA Data Model for astraios.io]; there also comes with a
production-ready [test framework] to make sure the model compiles with business requirements.

To install the data models locally, run:

> [!TIP]
>
> The local version will always be `2.0-SNAPSHOT` under `~/.m2/repository/com/paiondata/astraios-data-models-example/`

```console
mvn clean install
```

The models in this example has also been published to [Maven Central][Maven Central Version URL] and can be imported
by specifying a semantic version

```xml
<dependency>
    <groupId>com.paiondata</groupId>
    <artifactId>astraios-data-models-example</artifactId>
    <version>x.y.z</version>
    <scope>test</scope>
</dependency>
```

More information about the model can be found in [Javadoc page][Javadoc URL] <img src="https://github.com/QubitPi/QubitPi/blob/master/img/please-read-the-doc.png?raw=true" width="70px" />

License
-------

The use and distribution terms for [astraios-data-models-example] are covered by the [Apache License, Version 2.0].

[Apache License Badge]: https://img.shields.io/badge/Apache%202.0-F25910.svg?style=for-the-badge&logo=Apache&logoColor=white
[Apache License, Version 2.0]: https://www.apache.org/licenses/LICENSE-2.0

[GitHub Workflow Status]: https://img.shields.io/github/actions/workflow/status/paion-data/astraios-data-models-example/ci-cd.yml?branch=master&logo=github&style=for-the-badge
[GitHub Workflow Status URL]: https://github.com/paion-data/astraios-data-models-example/actions/workflows/ci-cd.yml

[Javadoc Badge]: https://img.shields.io/badge/Javadoc-000000.svg?style=for-the-badge&logo=openjdk&logoColor=white
[Javadoc URL]: https://jpa-model.qubitpi.org/
[Java Version Badge]: https://img.shields.io/badge/Java-17-brightgreen?style=for-the-badge&logo=OpenJDK&logoColor=white
[astraios-data-models-example]: https://github.com/paion-data/astraios-data-models-example
[JPA Data Model for astraios.io]: https://elide.paion-data.dev/docs/data-model

[Maven Central Version Badge]: https://img.shields.io/maven-central/v/com.paiondata/astraios-data-models-example?style=for-the-badge&logo=apachemaven&labelColor=1B1C30&color=4D9FEA
[Maven Central Version URL]: https://central.sonatype.com/artifact/com.paiondata/astraios-data-models-example

[test framework]: https://github.com/paion-data/astraios-data-models-acceptance-tests
