# sbt-class-diagram [![Build Status](https://secure.travis-ci.org/xuwei-k/sbt-class-diagram.png?branch=master)](http://travis-ci.org/xuwei-k/sbt-class-diagram)

### requirement

- <http://www.graphviz.org/>
- sbt 0.13.5 or higher

### install

#### `build.sbt`

```scala
enablePlugins(ClassDiagramPlugin)
```

#### `project/plugin.sbt`

##### latest stable version

```scala
addSbtPlugin("com.github.xuwei-k" % "sbt-class-diagram" % "0.2.0")
```

##### snapshot version

```scala
resolvers += Opts.resolver.sonatypeSnapshots

addSbtPlugin("com.github.xuwei-k" % "sbt-class-diagram" % "0.2.1-SNAPSHOT")
```

### sample

#### scala.collection.immutable.List

![List](https://raw.githubusercontent.com/xuwei-k/sbt-class-diagram/master/sample/list.png)


#### scalaz 7.2.x

[![Scalaz](http://xuwei-k.github.io/scalaz-docs/diagram1.svg)](http://xuwei-k.github.io/scalaz-docs/diagram1.svg)
