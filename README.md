# An Introduction to Simulating Human Survey Responses with Large Language Models: Potentials and Pitfalls

Welcome to **An Introduction to Simulating Human Survey Responses with Large Language Models: Potentials and Pitfalls.** This tutorial takes place at the [12th International Conference on Computational Social Science (IC²S²)](https://ic2s2-2026.org/) in Burlington, Vermont. This tutorial’s goal is to provide a hands-on introduction to simulating human survey responses with LLMs, with a focus on survey-centric use cases including survey pretesting, hybrid designs that combine human and simulated respondents, and missing-data imputation.

**Organizers:** Georg Ahnert, Maximilian Kreutner, Jens Rupprecht, Markus Strohmaier, Kristina Gligorić, Indira Sen

**Tutorial homepage:** <https://dess-mannheim.github.io/tutorial_simulating_survey_responses/>

## Run the code

You can clone the repo and run the code locally or run the notebooks directly in Google Colab.

If you want to run the code locally, simply clone the repo, install `uv` if you don't have it and run `uv sync`. If you want to follow the tutorial on Colab, simply click on one of the following links.

We offer two notebooks:

- Session 2 [![Session 2](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dess-mannheim/tutorial_survey_simulation/blob/main/notebooks/session2.ipynb): Runs inference with LLMs locally. We use QSTN to test multiple different setups. To run this you will need to have a GPU with at least 16GB VRAM. On Colab select the T4 GPU environment.

- Session 4 [![Session 4](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dess-mannheim/tutorial_survey_simulation/blob/main/notebooks/session4.ipynb): We evaluate our different runs with individual accuracy, population alignment and a simple regression.

## Learning Objectives

By the end of the session, participants will:

- Understand how to implement LLM-based survey simulations
- Learn the QSTN framework, a tool designed to structure LLM-based survey simulations and support transparent evaluation across design alternatives
- Generate simulated survey responses and compare modeling choices
- Evaluate outputs using multiple metrics
- Engage in critical discussion of methodological limitations, validation challenges, and ethical considerations

## Data and Tools

We introduce [QSTN](https://github.com/dess-mannheim/QSTN), a Python framework developed to structure LLM-based survey simulations. Through guided hands-on exercises, participants will generate simulated survey responses, compare modeling choices, and evaluate outputs using multiple metrics.

## Target Audience

The tutorial is intended for researchers and graduate students in computational social science, political science, sociology, communication, and related fields. No prior experience with LLMs is required, but basic familiarity with surveys and introductory Python (or willingness to follow along conceptually) is recommended.
