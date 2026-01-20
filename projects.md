---
title: null
subtitle: null
layout: page
---
# Project Phonè

The [Phoné](https://phonegroup.github.io/) consortium, formed by the University of Naples Federico II, the CNR-ISTI in Pisa and the Free University of Bozen-Bolzano, takes its name from the Greek word 'φωνή', meaning 'linguistic sound' or 'voice'. It was established as a voluntary initiative with the following objectives: 
- Collection of speech datasets (transcribed and non-transcribed) for training and evaluating Italian speech recognition and synthesis models;
- Definition of relevant use cases for model evaluation;
- System benchmarking using traditional and new metrics;
- Providing an independent evaluation of currently available automatic speech recognition and synthesis models in sensitive contexts such as industry, academia and government;
- Providing scientific and technological support for the third-party development of system architectures and training processes for speech recognition and synthesis.

Phoné products:

- Italian speech dataset: partially transcribed and useful for training speech recognition systems. The dataset can be distributed freely.
- two ASR models: trained from scratch using only Italian speech.
- a comprehensive speech synthesis and voice cloning system accessible via a web platform. This implementation is based on Gérard Bailly's (CNRS, Grenoble) PyTorch implementation of Tacotron 2. New contributions include (but are not limited to): the packaging of the TTS module into a containerised web service based on FastAPI; the setup of Kubernetes deployment.
- a pipeline of audio file manipulation tools that are useful for preparing additional training material for TTS and ASR.



