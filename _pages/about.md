---
layout: about
title: about
permalink: /
subtitle: "<a href='https://github.com/AndrewMah44'>GitHub</a> | <a href='https://scholar.google.com/citations?user=i-TJXyUAAAAJ&hl=en&authuser=2'>Google Scholar</a> | <a href='https://www.linkedin.com/in/andrew-mah-98171128a/'>LinkedIn</a> | <a href='mailto:andrew.mah44@gmail.com'> Email</a> | <a href='/assets/pdf/mah_cv.pdf' target='_blank'> CV</a>"

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Center for Computational Neuroscience</p>
    <p>Flatiron Institute</p>
    <p>New York, NY 10010</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

## About Me 

I’m a Flatiron Research Fellow at the Flatiron Institute [Center for Computational Neuroscience](https://www.simonsfoundation.org/flatiron/computational-neuroscience/), working with [Alex Williams](https://neurostatslab.org/). I study how neural networks represent and use information to perform inference, using small, but surprisingly powerful, models that I can analyze fully.

Two recent results:

> **Why state-space models fail to length-generalize.** Across seeds, linear RNNs + MLP readout trained on bounded-depth Dyck languages varied widely in how well they extrapolated. I traced the failures to a slow drift mode in the linear recurrence that gradually pushes the representation out of the region where the readout is accurate. Clamping that mode at inference time, with no retraining, restores performance at up to 100x the training length.

> **When linear models are enough.** We proved error bounds showing that forward filters on a broad class of hidden Markov models can be well-approximted by linear recurrent models, which we validated the bounds on >900 randomly generated and adversarial HMMs (NeurIPS 2026). Finally, we provide easily computable heuristics to determine when a problem requires nonlinear inference.

These questions are inspired by my Ph.D. work at NYU [Christine Constantinople](https://constantinoplelab.com/), where I studied how uncertainty about hidden states shapes learning and decision-making in the brain. I now ask what artificial networks infer about hidden structure and how they use it. I've traded rats for JAX and behavioral rigs for GPU clusters, but the underlying questions remain the same.

I’m seeking research scientist roles in interpretable AI, sequence models, and probabilistic reasoning.

## Selected Publications

**Mah, A.**\*, Pughe-Sanford, J.L.\*, Harvey, S.E., & Williams, A. (2026) 
Linear approximations to HMM filtering
_Advances in Neural Information Processing Systems_.

<!-- <div style="margin-left: 16px;">
  <p>Summary: We show that linear dynamical systems can closely approximate Bayesian filtering in a class of hidden Markov models, including canonical examples from mechanistic interpretability research. We empirically validate these on linear RNNs trained across a variety of randomly-generated and adverserial HMMs.
  </p>
</div> -->

&emsp;<a href="/assets/pdf/NeurIPS_2026_Linear_HMMs.pdf">
  <button type="button">PDF</button>
</a>
<a href="https://github.com/AndrewMah44/linear-hmms">
  <button type="button">Code</button>
</a>

**Mah, A.**, Golden, C.E., & Constantinople, C.M. (2024). Dopamine transients encode reward prediction errors independent of learning rates. _Cell Reports_, 43(10). DOI: 10.1016/j.celrep.2024.114840

<!-- <div style="margin-left: 16px;">
  <p>Summary: Animals adjust their behavior in response to uncertainty about the environment’s overall reward rate, but dopamine reward prediction errors are unaffected by this uncertainty. However, these signals do reflect uncertainty about reward timing, suggesting that distinct forms of uncertainty differentially influence behavior and dopamine signaling.
  </p>
</div> -->

&emsp;<a href="/assets/pdf/mah_2024.pdf">
  <button type="button">PDF</button>
</a>
<a href="https://github.com/constantinoplelab/Mah2024_dynamic_learning_rate">
  <button type="button">Code</button>
</a>


**Mah, A.**, Schiereck, S.S., Bossio, V., & Constantinople, C.M. (2023). Distinct value computations support rapid sequential decisions. _Nature Communications_, 14(1), 7573. DOI: 10.1038/s41467-023-43250-x

<!-- <div style="margin-left: 16px;">
  <p>Summary: Using reinforcement learning models and behavioral data from more than 100 rats, we find that animals use hidden-state inference to guide some behaviors but not others, revealing distinct computations underlying sequential decisions.
  </p>
</div> -->

&emsp;<a href="/assets/pdf/mah_2023.pdf">
  <button type="button">PDF</button>
</a>
<a href="https://github.com/constantinoplelab/published/tree/main/rat_behavior">
  <button type="button">Code</button>
</a>

