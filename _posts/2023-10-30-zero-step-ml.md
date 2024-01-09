---
layout: python-post
title: Canary - A framework for detecting prompt injection attacks.
categories: [AI, LangChain, FastAPI, LLM]
---

## Overview

Auto ML is the process for automating the time-consuming of iterative machine learning model development. Commonly the 2nd most automated tier of machine learning development (on cloud platforms such as Google Cloud or Azure) (after pre-trained ML APIs), it enables data scientists to automate hyperparameter searching to produce optimised models.

However, Auto ML is not 100% automated - users must still manually identify features / targets from training data as well as the type of ML task. Zero-step-ML is an experiment into using LLMs to analyse training data metadata (e.g.: column names, data types, etc.) to automate these initial steps (hence **zero** step machine learning).

[![](https://mermaid.ink/img/pako:eNo1kE1PwzAMhv-K5QOnruLj1gMSWy9ITEJiXGg5WImzVeSjShyhadp_x5TiU_zmyfs6vqBJlrFD59O3OVEWOPRjBK2n4baF99knsmBJqLB8rjew2TzCdrhr4dlylMmdYf8Cinw14JikZgaTfA2xwI3q-ciyCqvFdrHYDfctvGaeczJcyhKzArsF6IeHFg6ZpghB5_TqRpH8uTDMnF3KgaJhfYINBtZusvqXy6_FiHLiwCN2erTsqHoZcYxXRalKejtHg53kyg3WWZO5n-iYKWDnyBdV2U6S8v5vP8uaGpwpfqT0z1x_AGR2Z_k?type=png)](https://mermaid.live/edit#pako:eNo1kE1PwzAMhv-K5QOnruLj1gMSWy9ITEJiXGg5WImzVeSjShyhadp_x5TiU_zmyfs6vqBJlrFD59O3OVEWOPRjBK2n4baF99knsmBJqLB8rjew2TzCdrhr4dlylMmdYf8Cinw14JikZgaTfA2xwI3q-ciyCqvFdrHYDfctvGaeczJcyhKzArsF6IeHFg6ZpghB5_TqRpH8uTDMnF3KgaJhfYINBtZusvqXy6_FiHLiwCN2erTsqHoZcYxXRalKejtHg53kyg3WWZO5n-iYKWDnyBdV2U6S8v5vP8uaGpwpfqT0z1x_AGR2Z_k)

In this blog, we'll run an experiment using a ongoing [competition dataset](https://www.kaggle.com/competitions/titanic/overview) on Kaggle and compare `zero-step-ml`'s performance against other submissions on the [leaderboard](https://www.kaggle.com/competitions/titanic/leaderboard).

## Experimentation



## Conclusion


