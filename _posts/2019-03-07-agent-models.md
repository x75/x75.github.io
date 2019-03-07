---
layout: post
title: Agent self-organisation principles
comments: true
tags: agents, principles, models, algorithms, brain, robotics
---

Principles for agent design is a hot research topic providing precious
raw material for applied uses. This article in progress is a place to
collect principles and associated mindsets, compare and organize them
into a workable catalog, and report on results for any of these
principles.

### Ad-hoc set of principles

Homeostasis (Cannon), Principle of adequate design (Rashevsky),
Anticipation (Rosen), Ratiomorphous decomposition (Lorenz, 1973),
Homeokinesis (Der), Empowerment (Klyubin et al), Autopoeisis (Maturana
& Varela), ...

### Ad-hoc set of approaches

| **Ad-hoc set of known approaches**             |     |  **Year**|     | **Attribution**           |
|:-----------------------------------------------|-----|---------:|-----|:--------------------------|
| Design for a brain, ultrastability             |     |      1952|     | Ashby                     |
| Autopoeisis                                    |     |      1972|     | Maturana & Varela         |
| Adequate locomotion strategies, brain equation |     |      1974|     | Rössler                   |
| Embodied agent design principles               |     |      2006|     | Pfeifer & Bongard         |
| Self-organization of behaviour                 |     |      1999|     | Der                       |
|                                                |     |      2008|     | Klyubin, Polani & Nehaniv |
|                                                |     |          |     |                           |

#### Embodied agent design principles

From the book "How the body shapes the way we think" by Pfeifer & Bongard, 2006.

|            |     | **Design principle** |     | **Description**                                      |
|-----------:|-----|:---------------------|-----|:-----------------------------------------------------|
|          P1|     | Three constituents   |     | Ecologial niche, behaviours and tasks, agent design  |
|            |     |                      |     |                                                      |
|          P2|     | Complete agent       |     | The complete agent behaving in the real world        |
|            |     |                      |     |                                                      |
|          P3|     | Cheap design         |     | Outsource as much as possible to environment         |
|            |     |                      |     |                                                      |
|          P4|     | Redundancy           |     | Verteilte physikalisches Substrat, teilweise         |
|            |     |                      |     | Überlappung in Funktion                              |
|            |     |                      |     | P+: No single cause, no single effect                |
|            |     |                      |     |                                                      |
|          P5|     | Sensorimotor         |     | Use motors to produce sensory stimulation,           |
|            |     | coordination         |     | P+: Closed-loop, Predictive processing               |
|            |     |                      |     |                                                      |
|          P6|     | Ecological balance   |     | 1) Complexity match task-environment / sensori-motor |
|            |     |                      |     | 2) Uniform task distribution over morphology,        |
|            |     |                      |     | material, control, environment                       |
|            |     |                      |     | P+: Adequate design                                  |
|            |     |                      |     |                                                      |
|          P7|     | Parallel, loosely    |     | Large number of concurrent async processes           |
|            |     | coupled processes    |     | P+: Population coding, Ensembles                     |
|            |     |                      |     |                                                      |
|          P8|     | Value                |     | Fundamental value definition - good / bad            |
|            |     |                      |     |                                                      |

### smp agent and pile theory

Coming [WIP]

### notes: auto: meme:

Two versions of the same stack of items, sorted in **bracing** order

|                    |     |                                                            |
|-------------------:|-----|------------------------------------------------------------|
|      **dynatropic**|     | motion towards option                                      |
|     **autoplastic**|     | subject to change by itself                                |
|  **autohedonistic**|     | subject to its own value                                   |
|       **autonomic**|     | subject to its own rules                                   |
|       **autotelic**|     | subject to its own goals                                   |
|     **autochronic**|     | subject to its own timing                                  |
|  **autogenerative**|     | subject to its own making                                  |
|      **autopoetic**|     | subject to its own storytelling                            |
|        **ecologic**|     | subject to its own limits and difference towards the other |

and sorted in **category contiguous** blocks

|                     |     |                                     |
|--------------------:|-----|-------------------------------------|
|   **autohedonistic**|     | subject to its own value            |
|        **autonomic**|     | subject to its own rules            |
|        **autotelic**|     | subject to its own goals            |
|      **autochronic**|     | subject to its own timing           |
|   **autogenerative**|     | subject to its own making           |
|       **autopoetic**|     | subject to its own storytelling     |
|  **autometaplastic**|     | subject to its own change by itself |
|       **dynatropic**|     | motion towards option               |
|         **ecologic**|     | limitation as resource              |

### Comments

{% if page.comments %}
<div id="disqus_thread"></div>
<script>

/**
*  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
*  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
/*
var disqus_config = function () {
this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
*/
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = '//x75.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}

