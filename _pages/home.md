---
title: "Moses Stewart"
layout: homelay
classes: wide
sitemap: false
permalink: /
---

### About Me

<br>

I am an undergraduate student at Harvard University living in Cambridge, Massachusetts. I currently
work as a research assistant for [Rahul Singh](https://www.economics.harvard.edu/people/rahul-singh). 
I will start a PhD in Economics at \[Undecided\] in Fall of 2025.

As a college student, I am pursuing an BA degree in Honors Statistics with an expected graduation
date of May 2025. From 2022-2024, I spent two years working closely with
[Jesse Shapiro](https://scholar.harvard.edu/shapiro/home) and [Isaiah Andrews](https://economics.mit.edu/people/faculty/isaiah-andrews)
as a research assistent.


**Research interests:** My undergraduate research focused on causal inference under misspecified models in Economics. 
Currently my research is centered around nonparametric causal inference and identification. I hope to continue
this theme in my graduate studies.

**Contact me:** mosesstewart \[at\] college \[dot\] harvard \[dot\] edu

<br/>

### Work Experiences

<div class='jumbotron'>
{% for member in site.data.work %}
<ul>
    <li>
      {{ member.role }} at <b>{{ member.company }}</b> ({{ member.yearStart }} - {{ member.yearEnd }})
    </li>
</ul>
{% endfor %}
</div>

<br/>

### Working Papers

<div class="jumbotron">
{% bibliography --query @inproceedings %}
</div>

<br/>

