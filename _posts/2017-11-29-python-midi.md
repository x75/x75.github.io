---
layout: post
title: python for MIDI
comments: true
tags: python music midi score event-representation
---

## python tools for midi

__Keywords__: python, music, midi, score, event representation

And the best is the non-python **midicsv**,
http://www.fourmilab.ch/webtools/midicsv/ which reads the midifile and
dumps it into a nice table of comma-separated values.

Some python candidate packages for working with MIDI, essentially reading and parsing MIDI files but musicology can be put on top.

**Mido** - MIDI Objects for Python, https://github.com/olemb/mido

> Mido is a library for working with MIDI messages and ports. It's designed to be as straight forward and Pythonic as possible.

Docs: https://mido.readthedocs.io/en/latest/

**Python MIDI**, https://github.com/vishnubob/python-midi,

> Python, for all its amazing ability out of the box, does not provide you with an easy means to manipulate MIDI data. There are probably about ten different python packages out there that accomplish some part of this goal, but there is nothing that is totally comprehensive.
> 
> This toolkit aims to fulfill this goal.

**music21**: a toolkit for computer-aided musicology, http://web.mit.edu/music21/

> Music21 is a set of tools for helping scholars and other active listeners answer questions about music quickly and simply.

**mingus**, https://github.com/bspaans/python-mingus, Docs: http://bspaans.github.io/python-mingus/

> mingus is a package for Python used by programmers, musicians, composers and researchers to make and analyse music

**Result**: Pip installed all four of them without issues, music21 nags about running in python2, loaded and dumped some midi data.

**Open ends**: musicxml, configure music21 with all helper programs, workflows for some common conversion tasks.

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
