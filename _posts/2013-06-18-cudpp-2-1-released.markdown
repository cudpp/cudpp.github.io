---
layout: post
title:  "CUDPP 2.1 Released!"
date:   2013-6-18 14:18:24
categories: releases
---

CUDPP release 2.1 is a feature release that adds many new parallel primitives. We have added [cudppCompress](http://cudpp.github.io/cudpp/2.1/group__public_interface.html#gae537bc8a91bb7d86f670c2065473b777), a lossless data compression algorithm. This compression utilizes efficient parallel Burrows-Wheeler and Move-to-Front transforms which are also exposed through the API. In addition, the library now contains two new sorting algorithms, [cudppMergeSort](http://cudpp.github.io/cudpp/2.1/group__public_interface.html#ga6dfdfa4fd5c580302c5ab61b45c53b0a) and [cudppStringSort](http://cudpp.github.io/cudpp/2.1/group__public_interface.html#ga9436ce9ee1b4dfefa70ece1b3776f338), adding to the existing radix sort. Minor code refactoring and build time fixes were completed.

CUDPP 2.1 is the first release to mark our transition from Google Code to Github.  We hope this transition will facilitate more community involvement and easier project management in the future.

A full list of changes can be viewed in the [change log](http://cudpp.github.io/cudpp/2.1/changelog.html).

Papers Cited:
- Ritesh A. Patel, Yao Zhang, Jason Mak, Andrew Davidson, John D. Owens. **"Parallel Lossless Data Compression on the GPU"**. In *Proceedings of Innovative Parallel Computing (InPar '12)*, May 2012. [http](http://idav.ucdavis.edu/publications/print_pub?pub_id=1087)
- Andrew Davidson, David Tarjan, Michael Garland, and John D. Owens. **"Efficient Parallel Merge Sort for Fixed and Variable Length Keys"**. *In Proceedings of Innovative Parallel Computing (InPar '12)* May 2012. [http](http://www.idav.ucdavis.edu/publications/print_pub?pub_id=1085)