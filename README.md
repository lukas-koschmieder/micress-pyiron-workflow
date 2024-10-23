# MICRESS&reg;Benchmark of Early-Stage Growth from Liquid State &ndash; pyiron Workflow

This repository contains a Jupyter notebook (`Workflow.ipynb`) designed to demonstrate how to run MICRESS simulations using the pyiron workflow management tool. The benchmark focuses on modeling early-stage microstructure growth from the liquid state.

## Prerequisites

Before starting, ensure that MICRESS is installed on your system. MICRESS is commercial software and must be obtained separately from the [MICRESS website](https://www.micress.de/).

## Installation

1. Install pyiron by following the instructions provided in the [pyiron documentation](https://pyiron.readthedocs.io). This process will guide you through setting up a conda environment that includes pyiron and its dependencies.
2. After installing pyiron, add the MicPy package by running the following command: `pip install micress-micpy`

## Usage

1. Clone this repository and navigate to the cloned directory.
2. Inside the `templates` folder, locate the MICRESS input file template (`.j2`) that corresponds to your version of MICRESS.
3. Copy the selected file into the directory where `Workflow.ipynb` is located, and rename it to `input.dri.js`.
4. Open `Workflow.ipynb` in your Jupyter environment to run the workflow.

This setup allows you to execute MICRESS simulations seamlessly through pyiron.
