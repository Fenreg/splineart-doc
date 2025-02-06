# Development environment

---
Section's goals
- Defining a development environment
- Present different models
- Understand the associated issues
- Use *pixi* to illustrate the set-up of a development environment
---

### General overview
Setting up a development framework requires to first define the tools and
dependancies necessary to develop and test one' software or one's library. The
goalpost being here that anyone aspiring to contribute to the project might do
so promptly and easily. Furthermore, should an issue appear during the
installation or the test phase, iterations to solve that problem will be
minimized, as the development environment will be fixed. Any arising problem
would thus be probably coming from the code itself and not be due to a
dependancy that hasn't been updated.

For many programming languages, we find packages manager available in a more
or less evolved form. Specifying the environment can be achieved through a
text file entirely assembled by one person's hand. This is the case in Python
with the *requirements.txt* text file, used by pip, and which allows to list
a collection of packages. The limits of this approach are that it is easy to
forget one dependancy, and that it can be difficult to clearly explicit which
version(s) of the dependancies are relevant.
Similar issues arise in the [conda](https://docs.conda.io/) universe, and in
particular with [conda-forge](https://conda-forge.org/) as it hosts an
assortment of packages created and published by the community. These packages
are not necessarily written with a specific programming language. They might
be written in either C++, Python, R or other languages. Setting up a conda
development environment requires to place a *environment.yml* text file,
which might constitute a doorway for human errors.
[Spack](https://github.com/spack/spack) allows to define various recipes for
the compilation of one' software, as well as its dependancies.

#### Pixi
#### Installation
#### Creating the environment
#### Setting up automated tasks
### Conclusions
