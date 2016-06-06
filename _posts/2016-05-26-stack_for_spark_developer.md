---
layout: post
title:  "The Technical Stack For An Apache Spark Developer"
date:   2016-05-26 18:35:00
categories: Tutorial
author: "Ambling"
---

In this post, I'd like to list the technical stack with some useful links for a *fresh new* [Apache Spark](http://spark.apache.org/) developer, who may have some fundamental programming skills while feeling lacking of a mass of background knowledge to be an efficient user or developer of Spark. I hope that the list can serve as index of the path to be a skilled Spark developer.

Without assumption of the reader's technical background, I will start with some *Basic Tools*. Readers can skip any section if he/she has been familiar to the subject.

## Basic Tools
- **Git**
  - Since the [source code of Spark](https://github.com/apache/spark/) is managed with git, basic knowledge of git is necessary, at least, you should know how to checkout the appropriate branch for the Spark version as you need.
  - Easy Way: [Try Git](https://try.github.io/)
  - Hard Way: [Documentations](https://git-scm.com/doc), [Tutorial](https://www.atlassian.com/git/tutorials/), [A successful Git branching model](http://nvie.com/posts/a-successful-git-branching-model/)

- **Eclipse** or **IntelliJ IDEA**
  - The IDE is important for efficiency, choose *your own favorite*. You can actually just learn by using and Google is your friend when you have trouble. However, if you find it difficult to get started, the following tutorials maybe helpful.
  - Eclipse: [Eclipse IDE - Tutorial](http://www.vogella.com/tutorials/Eclipse/article.html), [Tutorials](http://eclipsetutorial.sourceforge.net/)
  - IntelliJ IDEA: [Official Docs](https://www.jetbrains.com/idea/documentation/), [Mininal survival guide](http://hadihariri.com/2014/01/06/intellij-idea-minimal-survival-guide/)

- **Vi/Vim** or **Emacs**
  - Being able to use one of the editors which can be run inside of a terminal is absolutely necessary for users or developers of backend services. With the editors, you can make changes on the source code or check the log files totally on the remote server, which saves tons of time for cumbersome downloading and uploading. However, the learning curve is relatively steep, thus good tutorials are recommended for newbies.
  - Vi/Vim
    - Easy Way: [A simple tutorial](http://www.tutorialspoint.com/unix/unix-vi-editor.htm), [A quick introduction](http://heather.cs.ucdavis.edu/~matloff/UnixAndC/Editors/ViIntro.html), [interactive vim](http://www.openvim.com/)
    - Hard Way: [Learn Vimscript the Hard Way](http://learnvimscriptthehardway.stevelosh.com/)
  - Emacs
    - Easy Way: [Beginner's Guide](http://www.jesshamrick.com/2012/09/10/absolute-beginners-guide-to-emacs/), [Minimal Manual](http://tuhdo.github.io/emacs-tutor.html)
    - Hard Way: [A Guided Tour of Emacs](http://www.gnu.org/software/emacs/tour/), [Learn Emacs in Ten Years](http://edward.oconnor.cx/2009/07/learn-emacs-in-ten-years)

## Java
- The stack of Java programming language is the basis for all projects that are built on a JVM-based language (Scala, Closure, Jython...), and I believe readers can conveniently find many tutorials or courses for this popular language. A deep understanding of programming with Java may not necessary for a Spark developer, but the knowledge of some useful tools are really important to understand how programs on Spark is built and used.
- **Maven**
  - [Apache Maven](https://maven.apache.org/index.html) is one of the most popular `project management and comprehension tools`. It organizes dependencies in a *central manner* (which means that all dependencies can be downloaded from one or several central sites) *recursively* (which means that the dependencies of dependencies are managed automatically). It also contains the configurations of how to built the project, including the *root of source code*, *necessary plugins*, etc. All configurations of Maven are organized in a XML-style file with filename suffix of .pom (project object model). As a well-known open source project, the documentations on the official site are very clear and helpful.
  - Easy Way: [Maven in 5 Minutes](https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html)
  - Hard Way: [Maven Getting Started Guide](https://maven.apache.org/guides/getting-started/index.html)
- **log4j**
  - This lists some common guide for log4j, as a background knowledge of the logging mechanism of Spark. If you just want to know how to log in a Spark application, move to the Spark section at the end of this list.
  - Easy Way: [log4j - Quick Guide](http://www.tutorialspoint.com/log4j/log4j_quick_guide.htm)
  - Hard Way: [Official Docs](http://logging.apache.org/log4j/2.x/manual/index.html)
- **garbage collection**
  - GC is always a key factor for the performance of java programs, especially for in-memory applications like Spark. However, GC tuning is not easy for a common user, and is not recommended unless it is verified that GC is the culprit of the unacceptable performance. There's no easy way for GC anyway.
  - Hard Way: [Tuning Java Garbage Collection for Spark Applications](https://databricks.com/blog/2015/05/28/tuning-java-garbage-collection-for-spark-applications.html), [What every programmer should know about memory](http://lwn.net/Articles/250967/), [G1: One Garbage Collector To Rule Them All](http://www.infoq.com/articles/G1-One-Garbage-Collector-To-Rule-Them-All), [Tips for Tuning the Garbage First Garbage Collector](http://www.infoq.com/articles/tuning-tips-G1-GC)

## Scala
- **Language**
  - Though easy to use, Scala is a complicated programming language. I learned Scala systematically through a [MOOC](https://www.coursera.org/learn/progfun1) by Martin Odersky, who is one of the language designers. Limited by my experience, I cannot recommend more materials about the language.
- **sbt**
  - sbt is a very useful and advanced build tool for Scala and Java. It is more convenient to configure than Maven and makes the project containing a clear project structure. For a Spark developer, a knowledge of basic configurations and commands of sbt is enough.
  - Easy Way: [A simple tutorial](https://github.com/shekhargulati/52-technologies-in-2016/blob/master/02-sbt/README.md), [Another simple one](http://grosdim.blogspot.tw/2013/01/quick-sbt-tutorial.html)
  - Hard Way: [Official reference](http://www.scala-sbt.org/0.13/docs/index.html)
- **Typesafe Config**
  - Typesafe Config is a useful configuration library for JVM-based languages, [docs on Github](https://github.com/typesafehub/config) is clear and comprehensive enough for users.
- **ScalaTest**
  - ScalaTest is another advanced yet complicated tool in Scala stack. It enables various testing styles, and users can find their comfortable one to use. The [User guide](http://www.scalatest.org/user_guide) is fairly clear.

## Hadoop
- Config
- basic
- HDFS

## Spark
- Config
- basic
- RDD
- Spark SQL
- Others
  - [How to Log in Apache Spark](https://www.mapr.com/blog/how-log-apache-spark)
  - [Mastering Apache Spark](https://jaceklaskowski.gitbooks.io/mastering-apache-spark/content/)
