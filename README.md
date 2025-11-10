# spctools

Python package for Statistical Process Control (SPC) functionality.

This package will provide functions to support real world SPC workflows. SPC calculations involve several steps, and it is important to document the process. This package will be opinionated, based on my experiences as an industrial scientist and statistician using SPC.

My intent is to have transparent calculations. Control limits are calculated relatively infrequently with small amounts of data so it's more important to have clarity than be optimized. 

SPC is more than just calculations, it's a mindset that leads to improvement, with some tools. This package will output objects rich with context. Defining control limits for example is a special task, you have selected a baseline period of operation and you want to continue operating as well as, or better than that baseline. The objects will include context of this baseline for later reference.

I plan for this package to have a lot of tests, messages, and warnings. While the calculations are relatively simple, user error can easily happen so the messages and warnings are there to guide you. I have seen too many instances of both open source and commercial SPC software giving erroneous output. When spctools is "complete", I would like it to function correctly under any conceivable circumstance. 