# Framework for the creation and automatisation of tasks in open-source software development

### Contents
  - [Goals](#Goals)
  - [Training class program](1)
  - [Support material](3)
  - [Final result](4)
  - [Acknowledgments](5)

The development of open-source softwares for numerical simulations is currently taking
a growingly greater importance in scientific research. It helps to validate numerical
methods, to develop new algorithms and allows almost anyone to take hold of these tools,
use them, and build on top of them. Publishing scientific codes, scripts and softwares is
also an inherent part of open-science that goes beyond placing them on a webpage used as
an online archive.

The logic and structure of a software stem from its forerunners, and both evolves over
time as contributions accumulate. That being said, in order to prevent a software's
architecture to crumble after any minute change, it is necessary to have a framework
set in place. Staging this setup can be a hindrance as well as a challenge.
It all goes about easing contributors into these new work practices, and also about
reaching a middle-ground between a rigid development framework and giving free reins
to creativity.

Over the course of a framework's creation, many tasks are repetitive and might lead
to errors or even rollbacks in the software development. We can mention here unitary
tests, code formatting, errors revealed by static analysis, documentation generation,
as well as creating new releases and publishing them over package managers (pypi, conda,
vcpkg, spack, nix, guix, ...).

This document stands as the content and core of a training class, aiming at considering
any and all actions that might facilitate the workload of different actors of software
development such simple users, but developpers and maintainers too. We shall make use
GitHub Actions to automatize some of these repetitive tasks.

#### [Goals](#Goals)
- Improve and ensure the security of the development processes
- Publish your works semi-automaticaly and share it with a larger crowd
- Understand the workings of GitHub Actions
- Acquire a degree of personal autonomy in the setting up of (GitHub) workflows

#### [Training class program](2)
This document is divided in two parts:
- An overview that attempts to describe the differents steps and processes, permitting
an open-source software to reach a degree of maturity, quality-wise. Setting up a
development framework is almost unavoidable in order to allow each and every player
of the software development team to have their own place.
During this overview, we'll discuss several tools and scripts that might be helpful
to that end. The authors have tried, as much as possible, to make them independant
from the programming language used.

- Instructions and pointers to put into pratice the different concepts discussed in
the first half, and implement tools for continuous integration in the context pf
GitHub Actions. We shall see to automatically setup a development framework avoiding,
or at least limiting numbers of mistakes and human errors.

#### [Support material](3)

All the material required for the hands-on part of this training class is available
on the associated GitHub repo: https://github.com/gouarin/dev_env_and_automatisation.

For every part of the hands-on part, you will find a corresponding directory in the
''material'' folder. Should files be required to complete some exercises, they will
be found in the directory corresponding to the exercise, in a ''required_files''
folder.

#### [Final result](4)
Should you be curious about the final result of this training class, of the scripts
and development workflows developped, you can already check the splineart-cpp project
by clicking on the image below.

If you like the contents of this document, don't hesitate to star the GitHub
repository.

#### [Acknowledgments](5)
A great many thanks to [Matthieu Haefele]{https://github.com/mathaefele} for his
careful proofing and being the first to try-out the contents of this training class.
