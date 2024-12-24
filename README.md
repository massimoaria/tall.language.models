README
================

# Pre-Trained Annotation Models for Tall

## Overview

**TALL - *Text Analysis for ALL*** is an R Shiny application that
provides a comprehensive suite of methodologies for various text
analysis tasks. It is designed to meet the needs of researchers who may
lack extensive programming skills, offering a versatile and
user-friendly tool for analyzing textual data. With TALL, users can
apply a wide range of text analysis techniques, making it easier to
extract valuable insights from textual data in an efficient and
accessible manner.

TALL leverages the `udpipe` library for preprocessing, tokenization,
lemmatization, and parsing of raw texts. The `udpipe` R package allows
users to easily tokenize, tag, lemmatize, and perform dependency parsing
on texts in multiple languages by providing convenient access to
pre-trained annotation models. Previously, these models were based on
Universal Dependencies (UD) version 2.5 and had not been updated in some
time.

This repository, `udpipe.models`, provides updated pre-trained NLP
language models, trained on linguistic data from the [Universal
Dependencies](https://universaldependencies.org/) (UD) project, version
2.15, using the `udpipe` R package ([CRAN
link](https://CRAN.R-project.org/package=udpipe)).

The models are intended for use in Natural Language Processing (NLP)
tasks, including tokenization, parsing, and tagging. This repository
serves as a resource for researchers and developers working with TALL
([Tall GitHub repository](https://github.com/massimoaria/tall)).

## Purpose

The primary objectives of this repository are:

- To provide updated pre-trained `udpipe` models for a wide range of
  languages, aligned with the latest version of the UD corpora (2.15).
- To facilitate reproducible NLP research and applications by making
  these models readily available.
- To support projects that use Universal Dependencies data for
  tokenization, parsing, and tagging tasks in R and other environments.

## Data Source

The linguistic data used to train these models are sourced from the
Universal Dependencies project ([Universal Dependencies GitHub
repository](https://github.com/UniversalDependencies)).

Universal Dependencies is a community-driven initiative that offers
high-quality annotated corpora in the standardized CoNLL-U format for
many languages. The models in this repository are trained specifically
on data from version 2.15.

## Structure

The repository is organized as follows:

- **`2.15/`**: Contains pre-trained `udpipe` models for individual
  languages. Each model file is named according to the corresponding
  language and the version of the Universal Dependencies data used.
- **`README.rmd`**: This document provides an overview of the
  repository’s contents and purpose.

## Using the Models

To use these models, simply install **TALL**, which will automatically
handle the downloading of the pre-trained model required for analyzing
your corpus.

\`\`\`r \# Install the remotes package if not already installed
(uncomment the next line) \# install.packages(“remotes”)

remotes::install_github(“massimoaria/tall”)

library(tall)

tall()
