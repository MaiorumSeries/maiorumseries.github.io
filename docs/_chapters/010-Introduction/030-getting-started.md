---
title: Getting started
slug: getting-started
abstract: A guide to quickly setting up.
---

## GEDCOM Conversion

The conversion of the GEDCOM File requires the *gc2book* command line tool and a LaTeX distribution which can generate a PDF file. I am using the [(MiKTeX)](references.html#MiKTeX).

## System requirements

Running the tool chain requires:

* A package manager like *chocolatey*
* The .NET 6.0 runtime
* The gc2book application
* LaTeX distribution

## Setting up the system

In general there are several possibilities to install the required software packages. I personally prefer the usage of package manager also on Windows. There are too choices either [(WinGet)](references.html#WinGet) or [(Chocolatey)](references.html#Chocolatey).

I describe the installation here with *chocolatey*. To use this software you must install it as described on [(Chocolatey)](references.html#Chocolatey).

Install the MaiorumSeries chocolatey package.

``` cmd
choco install maiorumseries -y
```

The installation of the LaTeX distribution is required to compile the documents and the MiKTeX distribution is highly recommended.

``` cmd
choco install miktex -y
```

[Learn more about getting started.]({{ site.baseurl }}/index.html#getting-started)

<!-- ---
```
This file is located at: {{ page.path }}
```
--- -->
