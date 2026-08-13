---
layout: about
title: about
permalink: /
subtitle: "<a href='https://github.com/AndrewMah44'>GitHub</a> | <a href='https://scholar.google.com/citations?user=i-TJXyUAAAAJ&hl=en&authuser=2'>Google Scholar</a> | <a href='https://www.linkedin.com/in/andrew-mah-98171128a/'>LinkedIn</a> | <a href='mailto:andrew.mah44@gmail.com'> Email</a> | <a href='/assets/pdf/mah_cv.pdf'> CV</a>"

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

I am a Flatiron Research Fellow working with <a href='https://neurostatslab.org/'>Alex Williams</a> at the <a href='https://www.simonsfoundation.org/flatiron/center-for-computational-neuroscience/'>Center for Computational Neuroscience</a>. Briefly, I study how neural networks keep track of things they can't observe directly, and how they use these internal "beliefs" to make decisions. My work sits at the intersection of mechanistic interpretability, dynamical systems, and computational neuroscience, and draws on large-scale modeling experiments in JAX.

Specifically, I use tools from mechanistic interpretability to study how recurrent neural networks represent latent variables, often through low-dimensional sufficient statistics, to perform probabilistic inference. 

Neuroscience and mechanistic interpretability share a common goal: understanding how a complex system, a biological brain or an artificial neural network, processes information to guide behavior. They also increasingly share a common toolkit. During my Ph.D. at New York University with <a href='https://constantinoplelab.com/'>Christine Constantinople</a>, I studied how dopamine neurons represent distinct sources of latent state uncertainty to modulate learning, and helped design targeted neural perturbations to test how the circuits underlying latent-state inference give rise to behavior. Representational analyses and causal perturbations, which allow us to understand not just what a system does, but how it does it, are exactly the tools that are now central to interpretability research.

My current work applies this same toolkit to artificial systems. With representational and decoding analyses, I can identify what information is store in the network's hidden units, and with targeted perturbations, I can understand how that information is used.

I'm looking to apply this experience in research scientist roles focused on interpretable AI, sequence models, and probabilistic reasoning.

## Selected Publications

**Mah, A.** , Pughe-Sanford, J.L, , Harvey, S.E., and Williams, A. (Under Review) 
Linear approximations to HMM filtering
_Advances in Neural Information Processing Systems_.

<div style="margin-left: 16px;">
  <p>Summary: Using a combination of theoretical analyses and model fitting, we demonstate that a class of canonical HMMs in mechanistic interpretability reseach are well-approximated by linear dynamical systems.
  </p>
</div>

&emsp;<a href="/assets/pdf/toporikova_2026_prepreint.pdf">
  <button type="button">PDF</button>
</a>
<a href="/assets/pdf/toporikova_2026_prepreint.pdf">
  <button type="button">Code</button>
</a>

**Mah, A.**, Golden, C. E., & Constantinople, C. M. (2024). Dopamine transients encode reward prediction errors independent of learning rates. _Cell Reports_, 43(10). DOI: 10.1016/j.celrep.2024.114840

<div style="margin-left: 16px;">
  <p>Summary: We found that dopamine release in rats reflects distinct types of latent state uncertainty.
  </p>
</div>

&emsp;<a href="/assets/pdf/mah_2024.pdf">
  <button type="button">PDF</button>
</a>
<a href="/assets/pdf/mah_2020.pdf">
  <button type="button">Code</button>
</a>


**Mah, A.**, Schiereck, S. S., Bossio, V., & Constantinople, C. M. (2023). Distinct value computations support rapid sequential decisions. _Nature Communications_, 14(1), 7573. DOI: 10.1038/s41467-023-43250-x

<div style="margin-left: 16px;">
  <p>Summary: Using a combination of reinfocement learning modeling and careful behavioral analyses of a dataset consisting of >100 rats, we found that rats use hidden state inference for some behaviors but not others.
  </p>
</div>

&emsp;<a href="/assets/pdf/mah_2023.pdf">
  <button type="button">PDF</button>
</a>
<a href="/assets/pdf/mah_2020.pdf">
  <button type="button">Code</button>
</a>

