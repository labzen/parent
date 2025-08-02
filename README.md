
![LOGO](http://r7jiu5wkl.hd-bkt.clouddn.com/images/2022/02/19/16-34-57-167.png)
# Labzen Parent

![Labzen Parent](https://img.shields.io/badge/Labzen-Parent-green)
![Maven Central](https://img.shields.io/maven-central/v/cn.labzen/parent)
![GitHub](https://img.shields.io/github/license/labzen/parent)

![CircleCI](https://img.shields.io/circleci/build/github/labzen/parent?token=8953c094c11cf9c1d5ac53befed4eb49b770f4f0)

![GitHub last commit](https://img.shields.io/github/last-commit/labzen/parent)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/labzen/parent)

Labzen Parent 默认为所有`groupId is cn.labzen`的项目父/根POM，也可作为其他自建项目的父POM引用

## Installation

Install with Maven

```xml
  <parent>
    <artifactId>parent</artifactId>
    <groupId>cn.labzen</groupId>
    <version>21.x</version>
    <relativePath />
  </parent>
```
## Documentation

`cn.labzen:parent`为所有以它为父POM的项目，提供一致的构建配置，主要目的还是为统一多个项目之间的技术选型

`cn.labzen:parent:21.x` 版本对应的是 JDK 21