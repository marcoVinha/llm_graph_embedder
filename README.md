# Fine-Tuning Gemma 2 2b-it for Graph-Related Tasks

This repository explores the use of Instruction Tuning to fine-tune the Gemma 2 2b-it language model for graph-related tasks. The objective is to investigate how well the model performs on tasks such as node-level classification, link prediction and other related stuff.

### Features
- **Fine-tuning Framework**: Implements a Instruction Tuning routine for graph related task-specific fine-tuning.
- **Evaluation**: Benchmarks Gemma’s performance on graph datasets to examine the effects of fine-tuning.

### Goals
- To evaluate if bare bones LLMs can be helpful when solving graph-related tasks.
- To explore the potential of using Instruction Tuning for adapting Gemma 2 2b-it to graph-related tasks.
- To evaluate the model’s ability to handle graph-specific problems after fine-tuning.

### Running the code

To be able to reproduce the notebook in this repo in a Python environment with the same requirements listed here:

- Install Python 3.10
- Install `uv` to manage the deps
- Run `uv sync`
- This will create a virtual environment in the `.venv/ dir`
- Use this virtual environment to run any Python code for this project
- Execute the single notebook inside the `notebooks/` directory