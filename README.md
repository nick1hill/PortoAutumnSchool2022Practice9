# PortoAutumnSchool2022Practice1

This repository is intended to allow attendees of the practical portion of docs-as-code session at the Porto Autumn School 2022 to have something to experiment with.

The DITA source files are taken from https://github.com/dita-ot/docs repository, which are licensed under the terms of its Apache License 2.0.
These files with converted to markdown using the DITA to markdown conversion job in DITA OT.

This repo also has an Apache License 2.0.

This repo has the following GitHub Actions:

- Docker-based mdbook build of the source files into uncustomized html

## Contents of this repo

README.md - this file
License - Apache License 2.0 for this repo
markdown/src - folder for the markdown files
  - SUMMARY.md - file to structure the document
    - taskbook - source files for the document
  - .github
    - workflows
      - markdown-engine.yml -YAML file that provides instructions for the GitHub Action used to build the html
