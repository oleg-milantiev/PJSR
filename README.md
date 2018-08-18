<b>PJSR for FITS lovers</b>

Due to announced by PixInsight architect Juan Conejero FITS format war, the ability to use this international file format was restricted for majority of PCL processes and scripts.

We are going to soften the consequences of this war and convert back at least scripts to support FITS format.

<u>Disclaimer</u>. We consider that forced migration from FITS to XISF format is inconvenient and ineffective for our workflows. But this is only our personal opinion, we agree that we can make a mistake here. 

It is free for all, please feel free to contribute.


PJSR - PixInsight JavaScript Runtime
------------------------------------

The [PixInsight JavaScript Runtime](http://pixinsight.com/developer/pjsr/) (PJSR) is an [ECMA 262-5](http://www.ecma-international.org/ecma-262/5.1/) compliant environment readily available in the PixInsight Core application. PJSR is based on a custom embedding of the [SpiderMonkey JavaScript engine](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey) by [Mozilla Corporation](https://www.mozilla.org/en-US/). The current versions 1.8.x of PixInsight use the [SpiderMonkey 24](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey/24) engine.

Scripts are smoothly integrated with the whole PixInsight platform: all installed processes are automatically scriptable. For example, you can apply any sequence of processes to an image, extract its processing history, and generate a script automatically with just a couple clicks. PJSR allows advanced users to create their own tools to meet their specific needs, try out new algorithms, generate high-quality graphics, and perform complex tasks involving thousands of images. Many scripts already form part of the standard PixInsight distribution to implement mission-critical tasks such as batch image preprocessing, batch image analysis, image grading, plate solving, image annotation and 3-D rendering, just to name some well-known examples.

This repository contains the source code of a number of important scripts that form part of the standard PixInsight distribution on all platforms, including BatchPreprocessing, the PIDoc compiler, Makefile Generator, SubframeSelector, and other critical components.

###### Copyright (C) 2003-2015 Pleiades Astrophoto
