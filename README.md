# MICRESS®Benchmark of Early-Stage Growth from the Liquid State – pyiron Workflow

This repository contains two Jupyter notebooks that demonstrate how to run [MICRESS](https://www.micress.de) simulations for a benchmark scenario involving early-stage grain growth from the liquid state:

- `pyiron.ipynb` – Shows how to perform MICRESS simulations using the [pyiron](https://pyiron.org) workflow management system in a traditional, job-centric manner, including job setup, execution, and basic analysis.
- `pyiron_workflow.ipynb` – Demonstrates how to run MICRESS simulations using the new [pyiron_workflow](https://github.com/pyiron/pyiron_workflow) interface, featuring a graph-based, function-oriented approach for building modular and reusable workflow pipelines.

Together, these notebooks illustrate two complementary mechanisms for managing MICRESS simulations within the pyiron ecosystem.

## Prerequisites

Before starting, ensure that MICRESS is installed on your system. MICRESS is commercial software and must be obtained separately from the [MICRESS website](https://www.micress.de/).

## Installation

1. Install pyiron by following the instructions provided in the [pyiron documentation](https://pyiron.readthedocs.io). This process will guide you through setting up a conda environment that includes pyiron and its dependencies.
2. After installing pyiron, add the MicPy package by running the following command: `pip install micress-micpy`

## Usage

1. Clone this repository and navigate to the cloned directory.
2. Inside the `templates` folder, locate the MICRESS input file template (`.j2`) that corresponds to your version of MICRESS.
3. Copy the selected file into the directory where the notebooks are located, and rename it to `input.dri.j2`.
4. Open the desired notebook in your Jupyter environment.
5. Follow the instructions within the notebook to set up and run the MICRESS simulations.
