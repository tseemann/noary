[![Build Status](https://travis-ci.org/tseemann/noary.svg?branch=master)](https://travis-ci.org/tseemann/noary)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
![Don't judge me](https://img.shields.io/badge/Language-Perl_5-steelblue.svg)

:warning: This software is still in early development

# noary

A lightweight nucleotide bacterial ortholog clustering tool

## Introduction

If you want to cluster bacterial protein sequences, you usually use
[Roary](https://sanger-pathogens.github.io/Roary/) the pan-genome pipeline;
to incorporate non-coding transcripts you may use
[PIRATE](https://github.com/SionBayliss/PIRATE); 
and examination of intergenic regions may lead you to 
[Piggy](https://github.com/harry-thorpe/piggy).

Noary tries to fill the niche of nucleotide gene/sequence clustering.
It is intended to be a simple tool for use by other more complex pipelines.
It was originally conceived with 
[Harry Thorpe](https://github.com/harry-thorpe)
when I visited
[University of Bath, UK](https://www.bath.ac.uk/) in 2017.

## Quick Start

```
% noary --version
noary 0.1.2

```

## Installation

### Conda
Install [Conda](https://conda.io/docs/) or [Miniconda](https://conda.io/miniconda.html):
```
conda install -c conda-forge -c bioconda -c defaults noary # COMING SOON
```

### Homebrew
Install [HomeBrew](http://brew.sh/) (Mac OS X) or [LinuxBrew](http://linuxbrew.sh/) (Linux).
```
brew install brewsci/bio/noary # COMING SOON
```

### Source
This will install the latest version direct from Github.
You'll need to add the noary `bin` directory to your `$PATH`,
and also ensure all the [dependencies](#Dependencies) are installed.
```
cd $HOME
git clone https://github.com/tseemann/noary.git
$HOME/noary/bin/noary --help
```

## Dependencies

* `perl` >= 5.26

## License

noary is free software, released under the
[GPL 3.0](https://raw.githubusercontent.com/tseemann/noary/master/LICENSE).

## Issues

Please submit suggestions and bug reports to the
[Issue Tracker](https://github.com/tseemann/noary/issues)

## Author

[Torsten Seemann](https://twitter.com/torstenseemann)
