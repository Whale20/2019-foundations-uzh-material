# Module:  Managing Research Projects with SnakeMake

## Meta-Information

*   Module Maintainer: Lachlan Deer (`@lachlandeer`)
*   Course: [Programming Practices for Research in Economics](https://github.com/pp4rs)
*   Institute: Dept of Economics, Uni Zurich
*   Current Version: [Fall 2017 edition](https://pp4rs.github.io/2017-uzh)

## Contents

This module aims to show how to use SnakeMake to:

*   Divide a workflow into a set of individual rules that specify outputs and inputs
*   Correctly specify file dependencies to generate partial builds
*   Construct generalized rules to reduce repitition and minimize error
*   Split a research project into manageable subworkflows that are easily combined
*   Decorate our examples to reflect a simple workflow that
resemebles how a full-blown project should be managed

## Building this repository

(TO BE DONE)

### Build  Help?

*   Install snakemake:

```
pip install snakemake
# or OSX: brew install snakemake
```

*   Snakemake Tutorial: [click here](https://snakemake.readthedocs.io/en/stable/)
*   Install pandoc: follow set up [here](http://pandoc.org/installing.html)
*   pandoc help: [click here](http://pandoc.org/getting-started.html)

## Want to Contribute?

* See the contributing guide [here](CONTRIBUTING.md).
* By contributing you agree to abide by the [Code of Conduct](CONDUCT.md)

## Acknowledgements

*   This module is designed after and borrows a lot from:
    *   [`Effective Programming Practices for Economists`](http://wiwi.uni-bonn.de/gaudecker/teaching/prog_econ_slides.html#prog-econ-slides), a course by [Hans-Martin von Gaudecker](http://wiwi.uni-bonn.de/gaudecker/index.html)
    *   Software Carpentry's [`Automation and Make` lesson](http://swcarpentry.github.io/make-novice/)

*   The [`Zipf Law` example](./examples/zipfLaw/) is an adaption of Software Carpentry's `Automation and Make` lesson from `GNU Make` to `Snakemake`
*   The [`Schelling Model` example](./examples/schelling) is a direct adaption of Hans Martin's [`Project Template`](http://hmgaudecker.github.io/econ-project-templates/) that uses the build system [`Waf`](https://waf.io/)

We hope that by mirroring the examples from previous tutorials on build tools we give learners the opportunity to look at different build tools and choose the one they most prefer.

*   Contact the module maintainer for the Zipf Law example written in Waf, or the Schelling Model written in GNU make if you would like additional materials for comparison.

## Suggested Citation

The suggested citation for this repository is:

```
Lachlan Deer, Adran Etter, Julian Langer & Max Winkler, 2017, Managing Research Projects with SnakeMake, Programming Practices for Research in Economics, University of Zurich
```

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />

This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
