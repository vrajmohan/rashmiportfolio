---
layout: default
title: Work
permalink: /work/
---

<!-- Work Grid Section -->
<div class="container">
    <div class="row">
        <div class="col-lg-12 text-center">
            <h2 class="section-heading">Work</h2>
        </div>
    </div>
    <div class="row">
    {% for work in site.data.work %}
        <div class="col-md-6 work-item">
            <a href="#" class="work-link" data-toggle="modal">
                <figure class="figure">
                  <img src="{{ work.image }}" class="figure-img img-fluid rounded" alt="A generic square placeholder image with rounded corners in a figure.">
                    <figcaption class="figure-caption text-center">{{ work.category }}</figcaption>
                    </figure>
            </a>
        </div>
    {% endfor %}
    </div>
</div>
