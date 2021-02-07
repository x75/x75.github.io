---
layout: post
title: Computer music reading
author: Oswald Berthold
comments: true
tags: audio sound music computer-music signal-processing research compmus dsp smp jcl gt
---

### Computer music reading and literature

#### This document

Chatting with @imf over at the pulsar.scramble group, taking the
opportunity to collect a few bits and pieces in one place, clean out
the duplicates and post a draft of a computer music bibliography.

**TODO** merge dsp.org, dsp.bib, gnuradio.org, SDR.org, make awesome
github list collab, **Changes** 2020-12-21 adding SC3 Tutorial Cottle
[@imf], 2020-12-20 draft v1

#### music: math:
- Formalized music, Iannis Xenakis, 1992, Pendragon, 
- Music: A Mathematical Offering, David Benson, 2006/2008, <https://homepages.abdn.ac.uk/d.j.benson/pages/html/maths-music.html>

#### music: technique: analysis: synthesis: generative:
- Computer music tutorial, Curtis Roads
- Theory and Techniques of Electronic Music, Miller S. Puckette
- Current Directions in Computer Music Research, Max V. Mathews and John R. Pierce (Editors), <https://mitpress.mit.edu/books/current-directions-computer-music-research-1>
- Computer Music, Charles Dodge and Thomas A. Jerse
- Elements of Computer Music, F. Richard Moore
- The Cambridge Companion to Electronic Music Series: Cambridge Companions to Music Edited by *Nick Collins* University of Sussex, <https://www.cambridge.org/core/books/cambridge-companion-to-electronic-music/59CE625E910B05CEC434F3F90BCA9C74>
- Audible design, Trevor Wishart
- The Digital Musician, Andrew Hugill, <http://www.andrewhugill.com/thedigitalmusician/>
- Designing Sound, Andy Farnell, now MIT Press, <http://aspress.co.uk/ds/>

#### music: signal processing:
- Digital filters, Richard W. Hamming
- The scientist and engineer's guide to digital signal processing, Steven W. Smith, <http://www.dspguide.com>
- Musical Signal Processing, Curtis Roads
- Digital Audio Signal Processing, John Strawn (Editor), 1993
- Cellular neural networks and visual computing, Leon Chua

#### music: neuro: psycho-acoustics:
- Rhythmus. Tanz in Körper und Gehirn, Gerold Baier, 2001. This is an amazing book, just realizing it is probably not available in an English translation.
- Musik im Kopf, Manfred Spitzer, 2002, German only too.
- This Is Your Brain On Music, Daniel Levitin, 2007, <https://www.penguinrandomhouse.com/books/298964/this-is-your-brain-on-music-by-daniel-j-levitin/>

#### generative: data-driven:
- Auditory Display - Sonification, Audification, and Auditory Interfaces. Gregory Kramer (Editor). Addison-Wesley, 1994.
- Sonification for exploratory data analysis, Thomas Herrmann, Thesis

#### music: articles: papers:
- Experiments in Computer Controlled Acoustic Modelling (A step backwards ??), Ron W. Berry, 1988, in ICMC Proceedings 1988, <http://www.ron-berry.co.uk/RBacmodelling.pdf>
- 1/f Noise, Modelling planets, Paul Bourke, <http://paulbourke.net/fractals/noise/>
- Musical robots and listening machines, Nick Collins, <https://www.cambridge.org/core/books/cambridge-companion-to-electronic-music/musical-robots-and-listening-machines/CE25158536AF733C35BEEC78615675BC>

#### music: unsorted:
- Signal Processing, Speech and Music, Stan Tempelaars, 2016, <https://www.routledge.com/Signal-Processing-Speech-and-Music/Tempelaars/p/book/9781138981928>
- Computer Sound Synthesis in 1951: TheMusicOfCSIRAC by libarynth:PaulDoornbusch (from ComputerMusicJournal Spring 2004, pg. 10-25)
- ElseIfLiveCoding by libarynth:AlbertoDeCampo and libarynth:JulianRohrhuber

#### music: SuperCollider
- Rethinking The Computer Music Language SuperCollider, James McCartney, 2002, <https://www.mitpressjournals.org/doi/pdf/10.1162/014892602320991383>
- Computer Music with examples in SuperCollider 3, David Cottle, <http://rhoadley.net/courses/tech_resources/supercollider/tutorials/cottle/CMSC7105.pdf>
- The SuperCollider Book, Wilson et al. (Editors), <https://mitpress.mit.edu/books/supercollider-book>

#### music: python: MIR:

- George Tzanetakis and Perry Cook, "Musical genre classification of audio signals", IEEE Transactions on Speech and Audio Processing, vol. 10, No. 5, July 2002. [tsap02gtzan.pdf](/home/lib/topics/classification/tsap02gtzan.pdf)
- Juan José Burred and Alexander Lerch, "Hierarchical Automatic Audio Signal Classification", Journal of the Audio Engineering Society (JAES), Vol. 52 No.7/8, July/August 2004, pp. 724-739, [dafx06.pdf](/home/lib/topics/classification/dafx06.pdf)

#### music: examples: example works:
- Cornelius Cardew: Treatise, graphical score

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

