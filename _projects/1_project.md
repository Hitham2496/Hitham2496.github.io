---
layout: page
title: EventPlotter
description: A Python module for visualising events from High Energy Physics (HEP) simulations
img: assets/img/output_wm_4j.png
importance: 1
---

This project (still in development) is a Python module I am developing to **visualise** the complex
**data structures** used in High Energy Physics (HEP) simulations.

**Monte Carlo** event generators produce *events* as output which are containers of the particles
produced in a scattering experiment with extra information including intermediate particles, decay
products and initial parameters.

Analysing this output is difficult as such events are inherently visual phenomena, this library aims
to streamline the process of translating these configurations to a format that makes them easier to
analyse, with multiple options for customisation.

<div class="row">
    <div class="col-sm mt-2 mt-md-0">
    <a href="../../assets/pdf/output_wm_4j.pdf">
        {% include figure.html path="assets/img/output_wm_4j.png" title="W+4 jet event" class="img-fluid rounded z-depth-1" %}
    </a>
    </div>
    <div class="col-sm mt-2 mt-md-0">
    <a href="../../assets/pdf/output_wm_5j.pdf">
        {% include figure.html path="assets/img/output_wm_5j.png" title="W+5 jet event" class="img-fluid rounded z-depth-1" %}
    </a>
    </div>
</div>
<div class="caption">
    Examples of such heat maps for the production of a standard model W- boson at the LHC in association with 4 jets (left)
    and 5 jets (right). The decay products of the boson (an electron and antineutrino are shown as crosses)
</div>

This module currently displays events as **heat maps** in rapidity-azimuthal angle space with the
third axis coloured according to the transverse momentum of the particle.

This also allows for complex **statistical analyses** of multiple events, those shown above are
averages of the evolution of the input configurations shown below. The averages can be
conducted with respect to a **user-defined measure** and allows for selecting how the plots are
filled.

<div class="row">
    <div class="col-sm mt-2 mt-md-0">
    <a href="../../assets/pdf/input_wm_4j.pdf">
        {% include figure.html path="assets/img/input_wm_4j.png" title="W+4 jet event" class="img-fluid rounded z-depth-1" %}
    </a>
    </div>
    <div class="col-sm mt-2 mt-md-0">
    <a href="../../assets/pdf/input_wm_5j.pdf">
        {% include figure.html path="assets/img/input_wm_5j.png" title="W+5 jet event" class="img-fluid rounded z-depth-1" %}
    </a>
    </div>
</div>
<div class="caption">
    The input configurations corresponding to the averaged, evolved plots above. The left and right plots
    here are repsectively the input for the left and right images above.
</div>

Early forms of this module have been used by myself and colleagues in the IPPP for debugging which has
prompted me to formalise the project.

Currently the project contains classes for particles and events and reader classes for different formats
including the widely used Les Houches Event (LHE) format as well as the option to write a custom reader.

I would like to add much more to the project including:
<ul>
    <li>
    More customisability to plotting routines (e.g. colormaps, user identification of which
    particles are plotted, ...).
    </li>
    <li>
    Option to plot general variables (e.g. create distributions from events).
    </li>
</ul>

The code is hosted on [GitHub](https://github.com/Hitham2496/EventPlotter) and will
be made public after release.
