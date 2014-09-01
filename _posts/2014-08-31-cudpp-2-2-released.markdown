---
layout: post
title:  "CUDPP 2.2 Released!"
date:   2014-8-31 21:00:00
categories: releases
---

CUDPP release 2.2 is a feature release that adds a new parallel primitive and improves some existing primitives. We have added[cudpSuffixArray](http://cudpp.github.io/cudpp/2.2/group__public_interface.html#gabf9b40f6aaa7039aff1aa33a441d980f), a parallel skew algorithm(SA) implementation to compute the suffix array of a string. And it has been used in [burrowsWheelerTransform](http://cudpp.github.io/cudpp/2.2/group__cudpp__app.html#gadf315a304a78117955cad6d8c32a8fab) to achieve better performance than originally using the [cudppStringSort](http://cudpp.github.io/cudpp/2.2/group__public_interface.html#gaee8a05e38479c8b54b5d5b6655022d0a). And the new BWT is further used in [cudppCompress](http://cudpp.github.io/cudpp/2.2/group__public_interface.html#ga9d6e16e3dcf36a46be5bd98a675992c8) which is now faster than the origianl parallel compression and supports to compress text containing all possible unsigned char values. Some bugs in [cudppMoveToFrontTransform](http://cudpp.github.io/cudpp/2.2/group__public_interface.html#gadbb42fbc58ea70582dc1110c798ece38) and [cudppStringSort](http://cudpp.github.io/cudpp/2.2/group__public_interface.html#gaee8a05e38479c8b54b5d5b6655022d0a) have been fixed.

A full list of changes can be viewed in the [change log](http://cudpp.github.io/cudpp/2.2/changelog.html).
