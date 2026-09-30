---
layout: page
title: About Me
eyebrow: ¡Wepa! Welcome
intro: >-
  Data scientist by trade, statistician by training, and a teacher at heart.
  Born and raised in Puerto Rico.
permalink: /about/
---

<img src="{{ site.avatar | relative_url }}" alt="Dayanara Lebrón-Aldea" style="width:180px;border-radius:50%;margin:0 0 1.5em">

I'm a first-generation college graduate who fell for mathematics early. As a high-school senior I joined the Saturday Research Academy at the *Universidad Metropolitana* in San Juan and did my first research project in **biostatistics**, and saw that statistics applied to biology and medicine has real impact on people's lives. I've been following that thread ever since.

I earned a **B.S. in Applied Mathematics** (Universidad Metropolitana, 2015). Along the way I did five undergraduate research projects at four universities:

- **University of Alabama at Birmingham**, Section of Statistical Genetics (2013–2015): *Genome Enabling Models for Type 2 Diabetes Risk Assessment* and *Genetic Variance in BMI Associated with the FTO Gene in Young Adults*
- **Universidad Metropolitana**, San Juan (2014–2015): *Population Dynamics of the Green Iguana in Puerto Rico: a Pest Control Method*
- **University of Iowa**, Iowa Summer Institute in Biostatistics (2012): *Using Actigraphy Watches to Measure Sleep Activity in Subjects with Obstructive Sleep Apnea*
- **Saint Michael's College**, Vermont EPSCoR (2011): *Community Productivity with Sand Exposure in Urban and Forested Streams and the Effect of Fine Sediments in Grazers and Scrapers*

My UAB work became my first-author, peer-reviewed paper in data science applied to genomics, [published in *Frontiers in Genetics*](https://doi.org/10.3389/fgene.2015.00075). I started the research as a junior during my summer internship and kept working on it until February 2015, finalizing the analysis and preparing the manuscript.

I then completed an **M.S. in Statistics (Data Science track) at UC Davis** while working full time as a data scientist at **Lawrence Livermore National Laboratory**.

Since then I've spent eight years in data science: at LLNL in metagenomics and biosecurity, then in biotech product development at **Tecan Genomics** and **Eclipse Bioinnovations**, where I owned the eSHAPE RNA structure product line, led bioinformatics scientists, data scientists and DevOps teams, and developed and led a QC team. That work also made me a co-inventor on a [patent application](https://patents.justia.com/patent/20260250666) published in August 2026.

## What I Care About

- **Getting the question right before the method.** Most analysis problems are really design problems.
- **Making data usable by the people who need it:** scientists, marketers, customers and leadership alike.
- **Teams where people ask questions freely.** I've written about what that means for [product development]({{ '/Thoughts-on-Product-Development/' | relative_url }}).

## Right Now

I'm looking for my next role in **data science, analytics, or product/project management**. Since 2024 I've been tutoring math and statistics and teaching Spanish ([see my freelance work]({{ '/freelance/' | relative_url }})), completed a Leland grant program in Product Management, and keep building on my [statistics and ML notebooks](https://github.com/dlebron12/Statistics).

## Publications & Patent

<ul class="pubs">
{% for p in site.data.publications %}
  <li>
    {% if p.link %}<a href="{{ p.link }}">{{ p.citation }}</a>{% else %}{{ p.citation }}{% endif %}
    {% if p.first_author %}<span class="badge">First author</span>{% endif %}
    {% if p.patent %}<span class="badge">Patent</span>{% endif %}
    <span class="venue">{{ p.venue }}</span>
  </li>
{% endfor %}
</ul>

## Selected Recognition

- **Most Outstanding Poster Presentation in Computation**, LLNL Poster Symposium, 2015
- **GEM Fellowship**, Full Fellow (LLNL – UC Davis), 2016–2017
- **NSF Research Training Group Grant**, 2016–2017
- **KDD Conference & BPDM Workshop Travel Fellowship**, 2016 (awarded to ~10% of applicants)
- Best poster awards at SACNAS (2011), AGMUS (2012) and UAB Research Expo (2013)
- NSF Bio-Mathematics Scholar (2011–2014) and Mathematics Alliance Scholar (2012–2014)

## Languages

English and Spanish, both fluent.

I'd love to hear from you, so [get in touch](mailto:{{ site.email }}).
