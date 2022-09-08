---
layout: page
title: dbinterpy
description: Simple Python wrapper module around basic SQL commands
img: assets/img/databases.jpg
category: project
importance: 2
---

To teach myself about **publishing Python packages** and to learn about dynamic
databases, I produced a simple python module <code>dbinterpy</code> which acts
as a wrapper around basic commands in SQLite.

With this module, the connection to the database is **safe** as it is properly
opened and closed on initialising an instance of the interface class and on exiting
respectively.

<div class="row">
    <center>
    <div class="col-sm-6 mt-4 mt-md-0">
        {% include figure.html path="assets/img/databases.jpg" title="Jet cross sections at the LHC" class="img-fluid rounded z-depth-1" %}
    </div>
    </center>
</div>
<div class="caption">
    Image courtesy of <a href="https://pixabay.com/users/tumisu-148124/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=1954920)">
    Tumisu</a>.
</div>

The code is hosted on [GitHub](https://github.com/Hitham2496/DatabaseInterface)

The package is published on <code>PyPI</code>, latest release:
[v0.0.2](https://pypi.org/project/dbinterpy/).
