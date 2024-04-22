astraios.io Data Models Example
===============================

![Java Version Badge][Java Version Badge]
[![Maven Central Version][Maven Central Version Badge]][Maven Central Version URL]
[![GitHub Workflow Status][GitHub Workflow Status]][GitHub Workflow Status URL]
[![Apache License Badge]][Apache License, Version 2.0]

This project serves as an example of how to define [JPA Data Model for astraios.io]; there also comes with a
production-ready [test framework] to make sure the model compiles with business requirements.

To install the data models locally, run:

```console
mvn clean install
```

The models in this example has also been published to [Maven Central][Maven Central Version URL] and can be imported
with the following way for testing purposes

```xml
<dependency>
    <groupId>com.paiondata</groupId>
    <artifactId>astraios-data-models-example</artifactId>
    <version>x.y.z</version>
    <scope>test</scope>
</dependency>
```

License
-------

The use and distribution terms for [astraios-data-models-example] are covered by the [Apache License, Version 2.0].

[Apache License Badge]: https://img.shields.io/badge/Apache%202.0-F25910.svg?style=for-the-badge&logo=Apache&logoColor=white
[Apache License, Version 2.0]: https://www.apache.org/licenses/LICENSE-2.0

[GitHub Workflow Status]: https://img.shields.io/github/actions/workflow/status/paion-data/astraios-data-models-example/ci-cd.yml?branch=master&logo=github&style=for-the-badge
[GitHub Workflow Status URL]: https://github.com/paion-data/astraios-data-models-example/actions/workflows/ci-cd.yml

[Java Version Badge]: https://img.shields.io/badge/Java-17-brightgreen?style=for-the-badge&logo=OpenJDK&logoColor=white
[astraios-data-models-example]: https://github.com/paion-data/astraios-data-models-example
[JPA Data Model for astraios.io]: https://elide.paion-data.dev/docs/data-model

[Maven Central Version Badge]: https://img.shields.io/maven-central/v/com.paiondata/astraios-data-models-example?style=for-the-badge&logo=apachemaven&labelColor=1B1C30&color=4D9FEA
[Maven Central Version URL]: https://central.sonatype.com/artifact/com.paiondata/astraios-data-models-example

[test framework]: https://github.com/paion-data/astraios-data-models-acceptance-tests
