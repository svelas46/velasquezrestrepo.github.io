---
layout: page
title: Cryptic species identification 
description: Onsite and real time identification using the MinION DNA sequencer and its application in a conservation context.
img: assets/img/_V2E9316.jpg
importance: 2
category: work
giscus_comments: true
---

The Neotropics harbors the largest species richness of the planet; however, even in well-studied groups, there are potentially hundreds of species that lack a formal description, and likewise, many already described taxa are difficult to identify using morphology. Specifically in small mammals, complex morphological diagnoses have been facilitated by the use of molecular data, particularly from mitochondrial sequences, to obtain accurate species identifications. Obtaining mitochondrial markers implies the use of PCR and specific primers, which are largely absent for non-model organisms. Oxford Nanopore Technologies (ONT) is a new alternative for sequencing the entire mitochondrial genome without the need for specific primers. Only a limited number of studies have employed exclusively ONT long-reads to assemble mitochondrial genomes, and few studies have yet evaluated the usefulness of such reads in multiple non-model organisms.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/20231208_083119.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1707780217902.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/IMG_0959.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Together with a team of 5 students and our PI Juan F. Diaz-Nieto we embarked on a two week trip to the northern Altiplano of Antioquia. The idea was to catch Marmosops handleyi and M. cauce and be able to identify them down to species using non-lethal tissue samples shotgun Nanopore sequencing and a custom built computational pipeline.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/workspaces/Velasquez-Restrepo/assets/img/_V2E9316.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
