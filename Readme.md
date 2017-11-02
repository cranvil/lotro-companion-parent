lotro-companion-parent
======================

This repository aims to deliver a Maven POM and references to git submodules in
order to provide a basic entry point for compilation and packaging of the
application [LOTRO
Companion](https://sourceforge.net/projects/lotrocompanion/).


Prerequisites
=============

To make use of this project, you need recent versions of [Apache
Maven](https://maven.apache.org/) (as of now, version 3.5.0 is in use here) and
a Java Development Kit like the ones issued by [Oracle
JDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html).


Get up and running
==================

To fetch the project files in one step with the referenced repositories, just
run the following commands in your favourite terminal:
```
git clone --recurse-submodules https://github.com/cranvil/lotro-companion-parent
cd lotro-companion-parent
mvn verify
```

**BEWARE**: At this early stage, the Maven run doesn't produce any usable
artifact!


Working with git submodules
===========================

Since the internet says that using submodules can lead to unexpected results,
here are a few links about this topic:
- [Pro Git Book - Chapter 6.6 Git Tools - Submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules)
- [Atlassian - Git submodules: core concept, workflows, and tips](https://www.atlassian.com/blog/git/git-submodules-workflows-tips)
- [Kernel Wiki - Git Submodule Tutorial](https://git.wiki.kernel.org/index.php/GitSubmoduleTutorial)


