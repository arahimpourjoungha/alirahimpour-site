---
title: "Research"
aliases: ["/projects/"]
lead: "I translate advanced neuroimaging and cognitive neuroscience into scalable, real-world tools for mental health and decision support."
---

<div class="research">

<section class="project">

## Wearable fNIRS for precision mental health

A low-cost, wireless functional near-infrared spectroscopy (fNIRS) platform for objective assessment and repeated monitoring of brain function in naturalistic settings. The system pairs portable hardware with cloud-based signal processing, behavioral tasks, and ecological momentary assessment (EMA). This makes dense-sampling, individual-level neuroimaging practical outside the lab.

<p class="project-meta"><strong>Applications</strong> ADHD · stress-related disorders · PTSD · treatment-response monitoring</p>
<p class="project-meta"><strong>Key papers</strong> <a href="https://doi.org/10.1038/s41746-025-01690-3"><em>npj Digital Medicine</em> 2025</a> · <a href="https://doi.org/10.1101/2024.12.20.24318425">NIRDuino, <em>medRxiv</em> 2024</a> · <a href="https://doi.org/10.1038/s41598-025-20844-7"><em>Scientific Reports</em> 2025</a></p>

</section>

<section class="project">

## wnirs: open-source toolbox for wearable fNIRS

wnirs is my open-source Python toolbox for dense-sampling wearable fNIRS, covering the full path from raw headband light to an int8 model that runs on-device. It implements the methods of my *npj Digital Medicine* 2025 paper and is released under the MIT license with about 270 tests.

<p class="project-meta"><strong>Highlights</strong> Device I/O and quality control with 16 channel-quality metrics and TDDR motion repair · Precision-imaging statistics: AR-IRLS GLM in NumPy and JAX (8.6× faster, identical results), reliability, fingerprinting, ICC · A 3,143-parameter causal CNN with a 3.3 KB int8 streaming kernel and ONNX export · On 200 wearable recordings, it detects bad channels better than a DSP baseline (AUC 0.89 vs 0.84), even after int8 compression</p>
<p class="project-meta"><strong>Links</strong> <a href="https://github.com/arahimpourjoungha/wnirs">Code (GitHub)</a> · <a href="https://doi.org/10.1038/s41746-025-01690-3"><em>npj Digital Medicine</em> 2025</a></p>

</section>

<section class="project">

## Neuromonitoring-guided intervention in ADHD

Characterizing neurobiological heterogeneity in ADHD with multimodal wearable neuroimaging and behavior, and using neural markers to personalize intervention. This work combines task-based and naturalistic fNIRS paradigms with neurofeedback-informed working-memory training. The aim is objective markers of executive function and treatment response, supporting precision psychiatry beyond symptom-based diagnosis.

<p class="project-meta"><strong>Funding</strong> NIH STTR Phase I (R41), PI · NIH T32 Postdoctoral Fellowship</p>
<p class="project-meta"><strong>Key papers</strong> <a href="https://doi.org/10.1016/j.isci.2024.111087"><em>iScience</em> 2024</a> · <a href="https://news.stanford.edu/stories/2025/03/digital-tool-adhd-feedback-brain-research">Stanford Report coverage</a></p>

</section>

<section class="project">

## Foundation models for optical neuroimaging

Self-supervised representation learning for fNIRS time series, enabling brain-state discovery that generalizes across tasks, populations, and contexts. The work spans large-scale aggregation of wearable fNIRS data, masked and contrastive learning objectives, and a phenotype-first modeling strategy that keeps the learned representations interpretable and clinically relevant.

<p class="project-meta"><strong>Directions</strong> cross-task generalization · individualized brain profiling · downstream clinical prediction</p>

</section>

<section class="project">

## Naturalistic, at-home neuroimaging

Measuring the brain where people actually live. In a pilot of self-initiated, ambulatory prefrontal fNIRS recordings during everyday activities paired with ecological momentary assessment (98 sessions over 24 days), we examine task- and mood-dependent prefrontal functional connectivity, alongside dense-sampling deep phenotyping in ADHD.

<p class="project-meta"><strong>Tools</strong> Precision Wearable, an open MATLAB toolbox (in development) for dense-sampling analysis of wearable fNIRS and EEG</p>

</section>

<section class="project">

## Clinical translation: Alzheimer's disease and presurgical mapping

As lead analyst with the Stanford Alzheimer's Disease Research Center, I study wearable fNIRS during NIH Toolbox cognitive tasks in an amyloid-characterized cohort, linked to amyloid and tau PET, plasma biomarkers, and cognition. A separate pilot compares whole-head and wearable fNIRS for covert language mapping, toward a bedside alternative to Wada testing and fMRI for presurgical language lateralization.

</section>

<section class="project">

## Timing, action, and the motor system

How context shapes the neural control of timed action. Using fNIRS, EEG, and deep learning, this work examines how auditory cues, task structure, and study design modulate activity in primary and supplementary motor cortex during rhythmic behavior, including in cochlear-implant users.

<p class="project-meta"><strong>Key papers</strong> <a href="https://doi.org/10.1093/cercor/bhae427"><em>Cerebral Cortex</em> 2024</a> · <a href="https://doi.org/10.1038/s41598-023-33780-1"><em>Scientific Reports</em> 2023</a> · <a href="https://doi.org/10.1016/j.jneumeth.2020.108790"><em>J. Neuroscience Methods</em> 2020</a></p>

</section>

<section class="project">

## Neurodiversity and decision-making under risk

How neurodiverse individuals process risk, loss aversion, and feedback frequency in financial and everyday decisions. The project brings wearable neuroimaging into decision tasks grounded in behavioral economics, bridging neuroscience and real-world decision support.

</section>

<section class="project">

## Clinical neuroimaging in vulnerable populations

Objective neurophysiological markers of stress and emotion regulation in clinically complex and underserved groups, including PTSD, adverse childhood experiences (ACE), and Prader–Willi syndrome. Current work links prefrontal responses during acute stress to childhood-adversity load and heart-rate variability. The emphasis is on ethical, scalable neuroimaging that can inform intervention and monitoring.

<p class="project-meta"><strong>Current project</strong> SYSTEMAATICS: Childhood adversity and acute stress (2026 – present) · computational analysis lead and lead of the brain measurement team</p>

</section>

<section class="project">

## Methods and open science in fNIRS

Contributing to community efforts that improve rigor and reproducibility in fNIRS research, including the multi-lab FRESH reproducibility initiative the consensus-based fNIRS Glossary Project, and a multiverse (specification-curve) replication of fNIRS findings on non-adjacent dependency learning.

<p class="project-meta"><strong>Key papers</strong> <a href="https://doi.org/10.1038/s42003-025-08412-1"><em>Communications Biology</em> 2025</a> · <a href="https://doi.org/10.1117/1.NPh.12.2.027801"><em>Neurophotonics</em> 2025</a> · <a href="https://doi.org/10.1364/brain.2026.bs5a.1"><em>Optics and the Brain</em> 2026</a></p>

</section>

<section class="project">

## Software and code

Open-source code from my research, available on GitHub.

<p class="project-meta"><strong>wnirs</strong> Python toolbox for dense-sampling wearable fNIRS, from raw headband light to an int8 model that runs on-device · <a href="https://github.com/arahimpourjoungha/wnirs">GitHub</a></p>
<p class="project-meta"><strong>ADHD-NFB-iScience2024</strong> Archived analysis code for the Supplementary Section 4 analyses of our <em>iScience</em> 2024 paper · <a href="https://github.com/arahimpourjoungha/ADHD-NFB-iScience2024">GitHub</a> · <a href="https://doi.org/10.1016/j.isci.2024.111087">Paper</a></p>
<p class="project-meta"><strong>LanguageMapping-fNIRS-Tasks</strong> Task battery of four covert language tasks in a block design, for language lateralization with fNIRS · <a href="https://github.com/arahimpourjoungha/LanguageMapping-fNIRS-Tasks">GitHub</a></p>

</section>

</div>
