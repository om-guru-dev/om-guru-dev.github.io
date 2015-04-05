---
layout: post
title:  "Installing Leiningen and LightTable on Windows"
date:   2015-04-03 17:00:00
categories: general setup
author: Prabhas Pokharel
---

For this class, we will use Leiningen for dependency and project management, and LightTable as our IDE. We could use any IDE, but the inline evaluation that LightTable allows is a great learning tool.

Anyways, settting up LightTable and Leiningen on Windows can be tricky, so our class participant Punit Jajodia wrote up instructions here:

[http://www.programtopia.net/clojure-leningin-lighttable-setup-windows](http://www.programtopia.net/clojure-leningin-lighttable-setup-windows)

The main steps are (the first four must be done in order:

 1. Install [the latest JDK](http://www.oracle.com/technetwork/java/javase/downloads/jdk7-downloads-1880260.html)
 2. Modify Environment Variables ($PATH, $JAVA_HOME) so Windows can find Java
 3. Install [Maven](https://maven.apache.org/download.cgi)
 4. Modify Environment Variables ($PATH)
 5. Install [Leiningen](http://leiningen.org/#install)
 6. Install [LightTable](http://lighttable.com/)

Modifying Windows Environment Variables actually requires some tricks (such as referring to the standard `Program Files` folder as `PROGA~1`, so be sure to check out  [Punit's post](http://www.programtopia.net/clojure-leningin-lighttable-setup-windows), complete with screenshots).