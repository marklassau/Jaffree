# Jaffree [![Sparkline](https://stars.medv.io/kokorin/Jaffree.svg)](https://stars.medv.io/kokorin/Jaffree)

This is the `sb-fork` branch of Jaffree.
It contains bug-fixes for Jaffree that we want to include in SB, before they are included in a mainstream Jafree release.

## Release

```
mvn clean install
```

or

```
mvn clean install -DskipTests
```

This will produce jar with version based on the date of latest git commit, and `-sb-fork` qualifier.
eg `jaffree-2021.08.03-sb-fork.jar`

See `maven-git-versioning-extension.xml` for artifact naming configuration.
