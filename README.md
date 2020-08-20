---
title: hello world
---

## What is the Problem

My references are missing `role=doc-biblioentry` even though it seems `doc-biblioentry` support was added in [#4213](https://github.com/jgm/pandoc/issues/4213) and `doc-biblioentry` is present in the examples.

this is a test citation [@linReimaginingClinicalDocumentation2018]

## Reproduce Command

```
pandoc -s --bibliography library.json --filter pandoc-citeproc README.md -o README.html
```

## System Information

Pandoc Version

```
pandoc 2.10.1
Compiled with pandoc-types 1.21, texmath 0.12.0.2, skylighting 0.8.5
Default user data directory: /Users/lukemurray/.local/share/pandoc or /Users/lukemurray/.pandoc
Copyright (C) 2006-2020 John MacFarlane
Web:  https://pandoc.org
This is free software; see the source for copying conditions.
There is no warranty, not even for merchantability or fitness
for a particular purpose.
```

Pandoc Citeproc Version

```
pandoc-citeproc 0.17.0.1
```
