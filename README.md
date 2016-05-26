# Computer Science 441 Spring 2016

This repository contains the LaTeX and HTML source code for the laboratory and practical assignments, course teaching
slides, study guides, and the syllabus for Computer Science 441, Spring 2016.  Taught by [Gregory M.
Kapfhammer](http://www.cs.allegheny.edu/sites/gkapfham) in the [Department of Computer
Science](http://www.cs.allegheny.edu) at [Allegheny College](http://www.allegheny.edu), the course has the following
description:

> An examination of the principles and paradigms associated with the design, implementation, and analysis of distributed
> systems. Topics include the characterization of distributed system models, remote communication, distributed scheduling,
> synchronization and mutual exclusion, naming and time, consistency and replication, and fault tolerance. Selected
> distributed system development environments are discussed in the context of the above topics. One laboratory per week.
> Prerequisites: CMPSC 280 or CMPSC 440 or permission of the instructor.

The source code of the LaTeX documents uses a custom LaTeX style file and several other packages that are normally
standard with a modern LaTeX distribution such a TeXLive 2015. All of the slides are programmed with the
[reveal.js](https://github.com/hakimel/reveal.js/) framework. The background images in the slides were all collected
from the [Flickr Creative Commons](https://www.flickr.com/creativecommons/) through the use of the
[cogdog/flickr-cc-helper](https://github.com/cogdog/flickr-cc-helper) tool.

You are invited to use this repository as a means for learning more about instruction in an advanced computer science
course in the field of distributed computing. If you find this repository useful, could I trouble you to star it and
then acknowledge it in your own teaching efforts?

You can type the following command if you want to clone this repository:

```shell
git clone https://github.com/gkapfham/cs441S2016.git
```

If you want to compile the LaTeX document to a PDF, then you should type the following commands. In this example, I
show how to compile the syllabus for the course.

```shell
cd cs441S2016
cd syllabus
pdflatex cs441S2016_syllabus.tex
```

If you want to view the slides, then you should type the following commands. In this example, I show how to view the
slides for the first chapter of the textbook.

```shell
cd cs441S2016
cd slides
chromium-browser cs441_chapter1.html
```

Please note that the LaTeX documents have been compiled on an Ubuntu 15.04 workstation running a very recent version of
LaTeX that was manually installed using the TeXLive installer.  It is also worth noting that you can also compile the
documents using other LaTeX development tools, such as `latexmk`. If you are unable to compile the LaTeX source code
with your development tools and your execution environment, then please open a new issue and I will attempt to resolve
your concerns.

Additionally, the HTML slides have been tested on modern Web browsers (e.g., Chrome and Firefox) that run on the Ubuntu
and Android operating systems.  If the HTML slides do not correctly display on your Web browser, then I also encourage
you to open an issue so that I can handle the problem that you have found.
