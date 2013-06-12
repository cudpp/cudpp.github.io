---
layout: post
title:  "CUDPP 2.0 Released!"
date:   2011-08-09 14:18:24
categories: releases
---

CUDPP release 2.0 is a major new release of the CUDPP library, with exciting new features. The public interface has undergone a minor redesign to provide thread safety. Parallel reductions ([cudppReduce](http://cudpp.github.io/cudpp/2.0/group__public_interface.html#ga21d9b2b3c74daffbec52ef628f835313)) and a tridiagonal system solver ([cudppTridiagonal](http://cudpp.github.io/cudpp/2.0/group__public_interface.html#gabd3c1f97e1d22839756fd2594aaefb56)) have been added, and a new component library, [cudpp_hash](http://cudpp.github.io/cudpp/2.0/hash_overview.html), provides fast data-parallel hash table functionality. In addition, support for 64-bit data types (double as well as long long and unsigned long long) has been added to all CUDPP algorithms, and a variety of bugs have been fixed.

For a complete list of changes, see the [change log](http://cudpp.github.io/cudpp/2.0/changelog.html).
