---
layout: page
title: projects
permalink: /projects/
description: A sample of relevant projects.
nav: true
---

## Stabilizing linear representations for length generalization

Length generalization remains a central challenge for sequence models. I found that, across random seeds, single-layer S5 state-space models varied substantially in their ability to extrapolate on bounded-depth Dyck languages, a canonical testbed for hierarchical sequence processing. I sought to understand what distinguished the models that generalized from those that did not.

I found that failures could be explained by a slow drift mode in the model's linear recurrent dynamics. Over long sequences, this mode gradually shifted the model's internal representation outside the region in which its learned readout was accurate. Strikingly, clamping this drift mode at inference time, without retraining the model or otherwise modifying its hidden representation, was sufficient to restore performance at long sequence lengths.

This suggests that length-generalization failures can arise not because a model has failed to learn the relevant computation, but because small errors in its recurrent dynamics accumulate outside the training horizon. Ongoing work asks whether this mechanistic insight can be used to develop training objectives that promote stable representations and more reliable length generalization.

#### Publications

#### Presentations

## Linear approximations to hidden-Markov model filtering 

In certain cases, for example in the canonical Mess3 HMM, linear models are capable of representing complex belief states in their hidden activations nearly identically to more complex models like transformers and state-space models. This raised a basic question: when can Bayesian filtering be accurately approximated within a linear recurrent model?

Together with Joshua L. Pughe-Sanford, we derived bounds for the approximation error of a linear system that depend on the easily computable features of the underlying HMM, proving that a broad class of HMMs, including many from recent literature, can be well-approximated by a linear recurrent model. We then validated these results by training linear recurrent models on a suite of 230 HMMs, including both randomly generated and hand-constructed adversarial examples.

These results highlight an important caveat for model and task design: for certain problems, optimal filtering is approximately linear, so gains from more expressive architectures may be limited unless the task fundamentally requires nonlinear inference.

#### Publications

#### Presentations

## Hidden-state inference in rodents
Animals can estimate the value of their environment in different ways: by relying on recent experience or by inferring the underlying state of the world. How these computations interact, and whether they can guide different decisions on the timescale of a single trial, was an open question.

Using a temporal wagering task in rats, we obtained a continuous readout of how animals valued different water rewards. We found that rats used distinct value computations for decisions made only seconds apart. Their decision of when to initiate a trial depended primarily on a retrospective estimate based on recent rewards, whereas their decision of how long to wait for a reward relied on inference about the environment's hidden reward state.

By combining high-throughput behavioral data from hundreds of animals with computational modeling, this work showed that distinct decision-making computations can rapidly alternate within individual trials. These results provide a framework for investigating how different neural circuits implement and coordinate value computations on fine timescales.

#### Publications

#### Presentations