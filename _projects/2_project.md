---
layout: page
title: Cryptic species identification 
description: Onsite and real time identification using the MinION DNA sequencer and its application in a conservation context.
img: assets/img/V2E9316.jpg
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
        {% include figure.liquid loading="eager" path="assets/img/V2E9316.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A male Marmosops handleyi successfully identified to the species level in the field with our species identification pipeline. 
</div>

We implemented fieldwork to collect small mammals, including rodents, bats, and marsupials, in five localities in the northern extreme of the Cordillera Central of Colombia. DNA samples were sequenced using the MinION device and Flongle flow cells. Shotgun-sequenced data was used to reconstruct the mitochondrial genome of all the samples. In parallel, using a customized computational pipeline, species-level identifications were obtained based on sequencing raw reads (Whole Genome Sequencing). ONT-based identifications were corroborated using traditional morphological characters and phylogenetic analyses.

<div class="row justify-content-sm-center">
    <div class="col-sm-9 mt-3 mt-md-4">
        {% include figure.liquid path="assets/img/20231203_172647.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-3 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/sara.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
 </div>
 
This study was able to evaluate different pipelines to reconstruct mitochondrial genomes from non-model organisms, using exclusively ONT reads, benchmarking these protocols on a multi-species dataset. The proposed methodology can be applied by non-expert taxonomists and has the potential to be implemented in real-time, without the need to euthanize the organisms and under field conditions. Therefore, it stands as a relevant tool to help increase the available data for non-model organisms, and the rate at which researchers can characterize life specially in highly biodiverse places as the Neotropics.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/V2E9121.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This was the individual M. cauce that we trapped and were able to successfully identify to species level using our species identification pipeline.
</div>
