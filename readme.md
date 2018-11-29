---
title: "Readme/documentation: ODD for the Bibliotheca Islamica"
author: Till Grallert
date: 2018-11-27
tags:
- documentation
- periodicals
- schema
- tei
- xml
---

This repository was forked from [OpenArabicPE_ODD](https://github.com/OpenArabicPE/OpenArabicPE_ODD). Please go there for a documentation of `tei_periodical.odd`.

# ODD chaining

ODD can be chained using the `@source` attribute on `<schemaSpec>`, which needs to point to a **compiled** ODD. In order to compile an ODD which is a subset of the TEI Guidelines.

>This is easily done using the stylesheet odd2odd.xsl which is supplied as part of the TEI Stylesheet package, but is not currently included in the TEI oXygen framework. There is however a command line utility teitoodd which does the job, and it is also easy to set up your own oXygen transformation to do it. We leave this as an exercise for the reader.

source: <http://teic.github.io/TCW/howtoChain.html>