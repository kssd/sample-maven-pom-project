sample-maven-pom-project
========================

Created using pom-root archetype

> Command used for generating simple parent project

```
mvn archetype:generate -DarchetypeGroupId=org.codehaus.mojo.archetypes \
    -DarchetypeArtifactId=pom-root \
    -DarchetypeVersion=RELEASE \
    -DartifactId=sample-maven-pom-project \
    -DgroupId=in.sangram \
    -Dversion=1.0.0-SNAPSHOT \
    -DinteractiveMode=false
```

Pending
-------
1. Create/find archetype for root project with parent and aggregate poms.
2. Add project documentation samples
