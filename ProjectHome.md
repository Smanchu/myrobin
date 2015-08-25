**Mission**

|Filtering bug reports and isolating suspicious code area.|
|:--------------------------------------------------------|

**Description**

During the development and maintenance of software, bug processing starts when bug reports arrive at the bug repository. Test engineers review these reports and assign bugs to developers who are responsible for them. Developers reproduce the failures and try to locate the faults based on experience and observation.

To improve the efficiency of the whole process above, we propose an integrated bug processing framework that tries to obtain essential information from bug reports to locate the faults automatically. This project implements an instance of the framework Robin. We evaluate Robin on an open source project Lilypond (http://lilypond.org/).

![http://myrobin.googlecode.com/files/The%20extractor.png](http://myrobin.googlecode.com/files/The%20extractor.png)
![http://myrobin.googlecode.com/files/The%20visualizer.png](http://myrobin.googlecode.com/files/The%20visualizer.png)

**Support**

[Tutorial](http://myrobin.googlecode.com/files/tutorial.pdf) Robin usage scenario

[Isolator](http://myrobin.googlecode.com/files/isolator.rar) Combine git bisect and Delta Debugging to provide suspicious snippets and related information

[Experiment](http://code.google.com/p/myrobin/wiki/Regressions) 17 regressions for experiment