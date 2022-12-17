---
layout: post
title: Sound, music, sequences, search
comments: true
tags: models robotics music language
---

### Sound, music, sequences, search

This turned out the quickest way to get it done, a graphical dump of
my current picture related to the relationship of sound, music,
sequences and search, based on a shared modeling approach. Incomplete
but more or less consistent [claim]. Domain layer in black, modeling
layer in green.

![Graphical description of the scenery drawing]({{ site-url }}/assets/2018-08-14-Sound-music-sequences-search/aib-sound-music-sequences-search.svg)

By combining *coding*, *latent space state propagation*, and
*hierarchical composition*, most of the phenomena in sound, music,
vocalization, spoken language, and written language can be modelled,
all with the *same few components*.

Taking language as variable length sequences of actions, this can be
extended straightforwardly to model navigation problems.

<!--
References: autopop, augmented creativity, augmented editing,
teaching, game sounds, sonification, information sound scapes.
-->

### Music and robotics

(Merging previous standalone post from 2019-02-12, because it was only a mini-draft and relates to sequence models.)

The strong connection between robots and music is not so easily seen
by surprisingly many people. Let's try and tell the story in an
accessible way and then provide high level of detail for those
interested.

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

### Footnotes

<sup><a id="fn.1" href="#fnr.1">1</a></sup>fn.1
