# Introductory material for overlapping generations modeling

This repository contains introductory material for overlapping generations modeling. The materials include chapters from Evans and Debacker (2022) textbook as well as suggestions for computational platforms and tutorial notebooks. Please feel free to comment or submit questions regarding these materials by submitting an issue on this repository and "at"-ing either `@rickecon` or `@jdebacker`. We have provided a copy of the current table of contents of Evans and DeBacker (2022) as well as the bibiography. We hope this book will be published and available sometime in 2023.

Richard Evans and Jason DeBacker have built overlapping generations models for fiscal policy analysis and trained the respective staff maintainers in the United States, European Commission, and India. Contact OpenRG (experts@openrg.com) if you would like Evans and/or DeBacker to provide a customized training to your organization.


## 1. Overlapping generations textbook chapters

Evans and DeBacker have provided the following four textbook chapters from Evans and DeBacker (2022) as an introduction to building and solving overlapping generations models for policy analysis. These chapters are all available in this repository in the `OGprimer/Chapters/` folder. They are also linked below.

| Chapter           | Description  |
|-------------------|--------------|
| [Table of Contents](https://github.com/OpenRG/OGprimer/blob/master/Chapters/OGtext_toc.pdf) | Contents     |
| [Ch. 2](https://github.com/OpenRG/OGprimer/blob/master/Chapters/OGtext_ch02.pdf) | Simple 3-period lived agents model |
| [Ch. 3](https://github.com/OpenRG/OGprimer/blob/master/Chapters/OGtext_ch03.pdf) | Simple S-period-lived agents model |
| [Ch. 4](https://github.com/OpenRG/OGprimer/blob/master/Chapters/OGtext_ch04.pdf) | S-period-lived agents with endogenous labor supply |
| [Ch. 8](https://github.com/OpenRG/OGprimer/blob/master/Chapters/OGtext_ch08.pdf) | Demographics and productivity growth |
| [Ch. 17](https://github.com/OpenRG/OGprimer/blob/master/Chapters/OGtext_ch17.pdf) | Multiple Static Industries, Endogenous Labor |
| [Bibliography](https://github.com/OpenRG/OGprimer/blob/master/Chapters/OGtext_bib.pdf) | Bibliography |

There are many modeling structures that can be included in an overlapping generations model, as is shown in the [Table of Contents](https://github.com/OpenRG/OGprimer/blob/master/Chapters/OGtext_toc.pdf) to Evans and DeBacker (2022). The full set of chapters are available to OpenRG training clients, and the book should be available for purchase in 2023.

Another great resource that describes an overlapping generations model with most of the structures described in the Evans and DeBacker (2022) textbook is the [documentation](https://pslmodels.github.io/OG-Core/) for the [`OG-Core`](https://github.com/PSLmodels/OG-Core) macroeconomic model and its country calibrations [`OG-USA`](https://github.com/PSLmodels/OG-USA) and [`OG-UK`](https://github.com/PSLmodels/OG-UK).


## 2. We recommend using the Anaconda distribution of Python

The computation necessary for coding up and solving overlapping generations models is best implemented in a full programming language that includes:
* matrix/array representations,
* flexible and modern root finders, minimizers, numerical integration, automatic differentiation,
* ability to parallelize computation across threads and processes on a particular machine and/or across nodes on a server,
* functional programming and object oriented programming

A number of programming languages and software platforms are used across practitioners, including Python, MATLAB, Julia, C, C++, Fortran. We strongly recommend Python as it ranks very high in all of the above categories. However, OG models could be implemented in any programming language.

In the Evans and DeBacker (2022) textbook, we reference the [Python](https://www.python.org/) programming language and many of its powerful libraries for solving exercises. Using an open source language, such as Python, has the advantage of being free and accessible for anyone who wishes to learn these materials or contribute to these projects. Being open source also allows Python users to go into the source code of any function to modify it to suit one's needs.

We recommend downloading the Anaconda distribution of Python provided by [Anaconda, Inc.](https://www.anaconda.com/distribution/). We recommend the most recent stable version of Python, which is currently Python 3.10. This can be done from the [Anaconda download page](https://www.anaconda.com/distribution/) for Windows, Mac OSX, and Linux machines.


## 3. References
* DeBacker, Jason and Richard W. Evans, "[OG-Core: Documentation for the Large-scale Dynamic General Equilibrium Overlapping Generations Model](https://pslmodels.github.io/OG-Core/)", (Apr. 2022).
* Evans, Richard W. and Jason DeBacker, *Overlapping Generations Models for Policy Analysis: Theory and Computation*, unpublished (2022).
