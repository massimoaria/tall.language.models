README
================

# udpipe.models

## Overview

The `udpipe.models` repository contains pre-trained models for various
languages that have been developed using linguistic data from the
[Universal Dependencies](https://universaldependencies.org/) (UD)
project, version 2.15. These models are designed for Natural Language
Processing (NLP) tasks, including tokenization, parsing, and tagging.
The repository is intended to serve as a resource for researchers and
developers using the R library `udpipe` and the software `Tall` ([Tall
GitHub repository](https://github.com/massimoaria/tall)).

## Purpose

The main goals of this repository are:

- To provide pre-trained `udpipe` models for a wide range of languages.
- To facilitate reproducible NLP research and applications by making
  these models easily accessible.
- To support projects utilizing Universal Dependencies data for
  tokenization, parsing, and tagging tasks in R and other environments.

## Data Source

The linguistic data used to train these models are sourced from the
Universal Dependencies project ([Universal Dependencies GitHub
repository](https://github.com/UniversalDependencies/)). Universal
Dependencies is a community-driven initiative that provides high-quality
annotated corpora in the standardized CoNLL-U format for many languages.
The data from version 2.15 were specifically used for training the
models available in this repository.

## Structure

The repository is organized as follows:

- **`models/`**: Contains pre-trained `udpipe` models for individual
  languages. Each model file is named according to the corresponding
  language and version of the Universal Dependencies data used.
- **`scripts/`**: Includes R scripts for training models using the
  `udpipe` package, with examples and configurations for various
  languages.
- **`examples/`**: Demonstrates how to use the pre-trained models in NLP
  tasks with the `udpipe` package and the `Tall` software.
- **`README.rmd`**: This document provides an overview of the
  repository’s contents and purpose.

## Using the Models

To use these models, download the desired language model from the
`models/` directory and load it into R using the `udpipe` library. For
example:

\`\`\`r library(udpipe) model \<-
udpipe_load_model(“models/english-ud-2.15-2023.udpipe”) text \<- “This
is a sample text for testing.” annotated \<- udpipe_annotate(model, x =
text) print(annotated)
