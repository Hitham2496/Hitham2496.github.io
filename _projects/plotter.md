---
layout: page
title: Plotter
description: A simple routine to produce publication-quality plots from <code>rivet-mkhtml</code>
img: assets/img/jet_rates.png
importance: 3
category: project
---

The HEP analysis package [Rivet](rivet.hepforge.org/) is an incredibly versatile tool for analysing
data, though its plotting routines often lack in customisability. I produced a simple **object-oriented**
Python routine for producing high quality plots from the raw data output of <code>rivet-mkhtml</code>, fit
for publication and with much customisability.

<div class="row">
    <center>
    <div class="col-sm-8 mt-4 mt-md-0">
        <a href="../../assets/pdf/jet_rates.pdf">
            {% include figure.html path="assets/img/jet_rates.png" title="Jet cross sections at the LHC" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    </center>
</div>
<div class="caption">
    Example of a plot produced with this routine from raw data, experimental data and theoretical predictions are shown with
    theoretical uncertainty on the red band and statistical uncertainty as error bars on all predictions.
</div>

The most useful feature is the ability to specify uncertainty bands (as shown in the red band in the plot
above) for theoretical predictions, which arise often in HEP calculations.

The code is hosted on [GitHub](https://github.com/Hitham2496/Plotter) where other examples are shown.
