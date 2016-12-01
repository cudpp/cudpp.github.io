---
layout: post
title:  "CUDPP 2.3 Released!"
date:   2016-11-30 21:00:00
categories: releases
---

CUDPP release 2.3 is a feature release that adds the new [cudppMultiSplit](http://cudpp.github.io/cudpp/2.3/group__public_interface.html#ga61549b462de6627af02cc628ead17d22) parallel primitive. This function takes as input an array of elements (unsigned ints) and outputs an array where the elements have been split into ordered buckets. A second version of this function, [cudppMutliSplitCustomBucketMapper](http://cudpp.github.io/cudpp/2.3/group__public_interface.html#ga456800cc09f78c4dac6f48cf53b60e3c), allows the user to specify a custom function that assigns an element to a bucket.



A full list of changes can be viewed in the [change log](http://cudpp.github.io/cudpp/2.3/changelog.html). The release czar for CUDPP 2.3 was [Jason Mak](https://github.com/jwmak).
