<!--

author:   Bruna Piereck, Janick Mathys 
email:    training@vib.de
version:  1.0.0
language: en
narrator: UK English Female

icon:     https://vib.be/sites/vib.sites.vib.be/files/logo_VIB_noTagline.svg

comment:  This document shall provide an entire compendium and course on the
          development of Open-courSes with [LiaScript](https://LiaScript.github.io).
          As the language and the systems grows, also this document will be updated.
          Feel free to fork or copy it, translations are very welcome...

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js
          https://felixhao28.github.io/JSCPP/dist/JSCPP.es5.min.js

link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css
link:     https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css
link:     https://raw.githubusercontent.com/vibbits/material-liascript/master/img/org.css
link:     https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.11.2/css/all.min.css
link:     https://fonts.googleapis.com/css2?family=Saira+Condensed:wght@300&display=swap
link:     https://fonts.googleapis.com/css2?family=Open+Sans&display=swap
link:     https://raw.githubusercontent.com/vibbits/material-liascript/master/vib-styles.css

@orcid: [@0](@1)<!--class="orcid-logo-for-author-list"-->

-->

# Functional analysis: The biology behind the genes

<section>
Hello and welcome to our Functional analysis workshop! We are very happy to have you here.

This 1 day training aims to show you some online tools that can help you discover the functions of your set of genes/proteins.

> We are using the interactive Open Educational Resource online/offline course infrastructure called LiaScript. 
> It is a distributed way of creating and sharing educational content hosted on github.
> To see this document as an interactive LiaScript rendered version, click on the
> following link/badge:
>
> [![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://raw.githubusercontent.com/vibbits/functional_analysis_training/master/README.md)

### Lesson overview

> <i class="fa fa-bookmark"></i> **Description**  
> This is our hands-on course on Functional Analysis.
> 
> <i class="fa fa-arrow-left"></i> **Prerequisites**  
> To be able to follow this course, learners should have knowledge in:
>
> 1. Basic knowlegde of molecular biology   
> 
> <i class="fa fa-arrow-right"></i> **Learning Outcomes:**  
> By the end of the course, learners will be able to:
>
> 1. Explain the basic concepts and terminology of functional analysis, such as gene ontology, gene enrichment, pathways, and networks.
> 2. Use online tools to annotate and analyse human and plant datasets.
> 3. Compare and contrast different organisms, including those without a reference genome, in terms of their functional analysis.
> 4. Briefly evaluate the biological significance of the gene sets obtained from functional analysis.
> 
> <i class="fa fa-user"></i> **Target Audience:** Researchers, trainers, training providers
> 
> <svg xmlns="http://www.w3.org/2000/svg" height="14" width="16" viewBox="0 0 576 512"><!--!Font Awesome Free 6.5.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2023 Fonticons, Inc.--><path d="M384 64c0-17.7 14.3-32 32-32H544c17.7 0 32 14.3 32 32s-14.3 32-32 32H448v96c0 17.7-14.3 32-32 32H320v96c0 17.7-14.3 32-32 32H192v96c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h96V320c0-17.7 14.3-32 32-32h96V192c0-17.7 14.3-32 32-32h96V64z"/></svg> **Level:** Beginner  
>
> <i class="fa fa-lock"></i> **License:** [Creative Commons Attribution 4.0 International  License](https://creativecommons.org/licenses/by/4.0/)
> 
> <i class="fa fa-money-bill"></i> **Funding:** This project has received funding from ELIXIR Belgium.
> 
> <i class="fa fa-hourglass"></i> **Time estimation**: 8 hours
> 
> <i class="fa fa-envelope-open-text"></i> **Supporting Materials**:
>
>  1. [Activities](https://github.com/vibbits/functional_analysis_training/tree/master/activities)
>  2. [Slides](https://docs.google.com/presentation/d/1oNKXqt5olJPhFVUUFHvxU1EUmfnFNhZMXreW0Q8ccKs/edit?usp=sharing)
>  3. In the [data](https://github.com/vibbits/functional_analysis_training/tree/master/data) folder you can find **examples** that are smaller samples with limited opportunities but fast processed data.
>  4. In the [data](https://github.com/vibbits/functional_analysis_training/tree/master/data) folder you can find **exercises** that are bigger data sets that you can do more with.
>
> <i class="fa fa-asterisk"></i> **Requirements:** No
>
> <i class="fa fa-life-ring"></i> **Acknowledgement**: 
>
> * [ELIXIR Belgium](https://www.elixir-belgium.org/)
> * [VIB Technologies](https://www.vib.be/)
>
> <i class="fa fa-anchor"></i> **PURL**:  

### Authors

@[orcid(Janick Mathys)](https://orcid.org/0009-0007-1722-2370), @[orcid(Bruna Piereck)](https://orcid.org/0000-0001-5958-0669)

### Contributors

@[orcid(João Pacifico)](https://orcid.org/0000-0003-3861-4879), Mainak Guha Roy

</section>

## General context

Welcome to our Functional Analysis workshop! We are very happy to have you here.

This course will guide you into the steps of how to get the answers about what the genes can tell you! With the advances of technology, understanding the load of informations and giving it some meaning is becoming more challenging. To help you through this adventure and to get the answers your data is anxious to show you, we will use ONLINE tools to annotate and analyse some Human and Plant datasets and by the end of the day everything will make sense! We will shortly talk about how to start if you work with an organism that doesn't have a Reference genome. 

We will use Gene Ontology, Gene enrichment as much as Pathways to interpret our data and unravel the meaning of our gene set. This introduction of Functional Analysis will elucidate the biology behind the gene and bring to light what your data means.

### Schedule

Schedule day 1:

09:30 - 11:00 Organism without Reference Genome

11:00 - 11:30 Coffee break

11:30 - 11:45 Enrichment and Overrepresentation analysis (ORA)

11:45 - 12:30 Lunch

12:30 - 13:40 Gene ontology enrichment

13:40 - 15:00 Coffee break

15:00 - 15:15 Pathway (Networks) and gene functions

15:15 - 17:00 Gene-set enrichment

## Installations

Please read this page carefully **before** the start of the workshop.

### Common Setup

- Internet browser

## Citing this lesson

Please cite as:

  1. Bruna Piereck, Janick Mathys. (2023). Functional training (v1.0.0). Zenodo. tbc

## References

Here are some great tips for learning and to get inspired for writing your own pipelines:

- [VIB e-learning Functional Analysis](https://elearning.vib.be/courses/functional-analysis/)

- FUNAGE-Pro: comprehensive web server for gene set enrichment analysis of prokaryotes
    - [Publication](https://academic.oup.com/nar/article/50/W1/W330/6596090)
    - [Home page](http://gseapro.molgenrug.nl/)

- [Genomics Guru Youtube - How to perform GSEA](https://www.youtube.com/watch?v=KY6SS4vRchY) (desktop version)

- [Lars Juhl Jensen YouTube channel](https://www.youtube.com/@larsjuhljensen)

    - [Gene enrichment core concepts](https://www.youtube.com/watch?v=2NC1QOXmc5o)

    - [Gene Set enrichment explained](https://www.youtube.com/watch?v=egO7Lt92gDY)

    - [Interpreting Gene Set enrichment](https://www.youtube.com/watch?v=Yi4d7JIlAsM)

    - [String and 'My data' functionality](https://www.youtube.com/watch?v=VUwybb4ZLBY)

    - [String and Enrichment analysis](https://www.youtube.com/watch?v=VUwybb4ZLBY)

- [An intuitive explanation of PCA](https://medium.com/swlh/an-intuitive-explanation-of-principal-component-analysis-f0debe035c23)

--------------------------------------------

*About ELIXIR Training Platform*

The ELIXIR Training Platform was established to develop a training community that spans all ELIXIR member states (see the list of Training Coordinators). It aims to strengthen national training programmes, grow bioinformatics training capacity and competence across Europe, and empower researchers to use ELIXIR's services and tools. 

One service offered by the Training Platform is TeSS, the training registry for the ELIXIR community. Together with ELIXIR France and ELIXIR Slovenia, VIB as lead node for ELIXIR Belgium is engaged in consolidating quality and impact of the TeSS training resources (2022-23) (https://elixir-europe.org/internal-projects/commissioned-services/2022-trp3).

The Training eSupport System was developed to help trainees, trainers and their institutions to have a one-stop shop where they can share and find information about training and events, including training material. This way we can create a catalogue that can be shared within the community. How it works is what we are going to find out in this course.

*About VIB and VIB Technologies*

VIB is an entrepreneurial non-profit research institute, with a clear focus on groundbreaking strategic basic research in life sciences and operates in close partnership with the five universities in Flanders – Ghent University, KU Leuven, University of Antwerp, Vrije Universiteit Brussel and Hasselt University.

As part of the VIB Technologies, the 12 VIB Core Facilities, provide support in a wide array of research fields and housing specialized scientific equipment for each discipline. Science and technology go hand in hand. New technologies advance science and often accelerate breakthroughs in scientific research. VIB has a visionary approach to science and technology, founded on its ability to identify and foster new innovations in life sciences.

The goal of VIB Technology Training is to up-skill life scientists to excel in the domains of VIB Technologies, Bioinformatics & AI, Software Development, and Research Data Management.

--------------------------------------------

*Editorial team for this course*

Authors: @[orcid(Janick Mathys)](https://orcid.org/0009-0007-1722-2370), @[orcid(Bruna Piereck)](https://orcid.org/0000-0001-5958-0669)

Contributors: @[orcid(João Pacifico)](https://orcid.org/0000-0003-3861-4879), Mainak Guha Roy

Technical Editors: Alexander Botzki

License: [![CC BY](img/picture003.jpg)](http://creativecommons.org/licenses/by/4.0/)

