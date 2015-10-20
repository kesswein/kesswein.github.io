---
layout: post
title: Gearing up the allocator
---

Heap management is rather interesting to examine, given its ties to addressing and reference values, things that I consider to consider to be weaknesses of mine. The dilemma of finding out precisely which data blocks refer to the corresponding sentinels at the ends of each data block and which ones represent the actual data contents is one which I had never previously considered. By keeping constant sizes of data blocks in mind may help in making sure no leftover data ends up outside of the data blocks in the heap with no room for other data blocks to use the leftover data, which would only confuse the heap manager as to whether those particular values are data or sentinels. I'll probably make more sense of it all as I head on into the the coding to see the effects of certain coding segments for myself, but for the time being, it's a rather befuddling issue to try to resolve.
The examination of vectors goes a way to figuring out how to make the allocator work. Vectors are rather similar to the heap allocator in that they both rely on static allocations of memory and keeping track of the ending points of both the vectors and the heap allocator goes a long way in trying to make sure the structures can remember where all of the data is.
Tip of the day: Try not to let a partner's procrastination make you procrastinate as well. Find something to work on no matter what.
