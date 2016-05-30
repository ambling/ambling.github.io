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
  - Since the [source code of Spark](https://github.com/apache/spark/) is managed with git, basic knowledge of git is necessary.
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

## Linux
- env
- script

## Java
- Language
- Maven
- log4j
- garbage collection

## Scala
- Language
- sbt
- Typesafe Config
- scalatest

## Hadoop
- Config
- basic
- HDFS

## Spark
- Config
- basic
- RDD
- Spark SQL
