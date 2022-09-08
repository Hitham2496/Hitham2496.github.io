---
layout: page
title: TopClassifier
description: Unsupervised machine learning and image pre-processing to classify top quark jets at the LHC
img: assets/img/top_jets.png
importance: 3
category: project
---

This script and analysis was produced in 2018 as part of a summer studentship supervised by
Dr. Jonas Lindert and Prof. Frank Krauss at the [IPPP](https://www.ippp.dur.ac.uk/).

It analyses data from simulations of the LHC from
[SHERPA](https://sherpa.hepforge.org/doc/SHERPA-MC-2.2.2.html) with jets originating from the decay
of top quarks tagged using the [HEPTopTagger](https://www.ippp.dur.ac.uk/~mspannow/HEPTopTagger.html).

<div class="row">
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/img/top_jets.png" title="Top quark jets" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/img/non_top_jets.png" title="Non-top quark jets" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Average profile in rapidity-azimuthal angle of top quark jets (left) and jets not originating from a top quark decay (right).
</div>

This project involved creating and working with **data structures** and implementing sophisticated
**image pre-processing** routines before **classifying** top quark jets from their pre-processed
profiles with an **unsupervised machine learning** workflow.

This project was my first foray into data science and I have uploaded the code as originally
produced to [GitHub](https://github.com/Hitham2496/TopClassifier/). Details on the procedure
and the data format are shown in the repository as well as learning points from the project.
