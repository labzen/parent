
![LOGO](http://r7jiu5wkl.hd-bkt.clouddn.com/images/2022/02/19/16-34-57-167.png)
# Labzen Parent

![Labzen Dependencies](https://img.shields.io/badge/Labzen-Parent-green)
![Maven Central](https://img.shields.io/maven-central/v/cn.labzen/parent)
![GitHub](https://img.shields.io/github/license/labzen/parent)

![GitHub last commit](https://img.shields.io/github/last-commit/labzen/parent)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/labzen/parent)

Labzen Parent 默认为所有`groupId is cn.labzen`的项目父/根POM，也可作为其他自建项目的父POM引用

## Installation

Install with Maven

```xml
  <parent>
    <artifactId>parent</artifactId>
    <groupId>cn.labzen</groupId>
    <version>11.0</version>
    <relativePath />
  </parent>
```
## Documentation

`cn.labzen:parent`为所有以它为父POM的项目，提供一致的构建配置，主要目的还是为统一多个项目之间的技术选型

`cn.labzen:parent:11.x` 版本对应的是 JDK 11 ； 后续可能会创建对应 JDK 17 的 cn.labzen:parent:17.x； 不出意外不会创建基于这两个 JDK LTS 版本之外的父POM，直到17之后的下一个 LTS JDK