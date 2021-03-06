---
layout: post
title: IT is broken and how to fix it
author: Oswald Berthold
date: 2021-04-14
comments: true
tags: networking computing discrete math
---

### Information technology is broken

To the trouble of my surroundings I am going on at least three times a day about "IT is broken, see there!".

There are at least two reasons for why knowledge about this fact is not commonplace.

One reason is the people who actively and silently fix broken processes 24/7, see <https://twitter.com/x7557x/status/1374463844924289031>

Then, another one is that not all of it is utterly broken but only let's say 90%. The remaining 10% are so well designed and built to compensate away the broken stuff and keep things working on top, previously expressed here <https://twitter.com/x7557x/status/1361096165270372356>

On topical occasion, here is an example: Name:Wreck, which just came up to me through this article in [Wired](https://www.wired.com/story/namewreck-iot-vulnerabilities-tcpip-millions-devices/amp).

IT is broken at the seams if you agree with me for a minute that TCP/IP is part of those seams.

I have another latent thread about how *premature industrial order overscaling* of pretty much **anything** can lead to unforeseen problems regardless of the concrete reason. So with 150 million vulnerable objects that is industrial scale to me.

Naive mega-scaling is more of a problem than concrete reasons itself.

Discrete state machine based approaches are long known to be brittle, and the effect is called brittleness.

### The fix

Biological systems still outperform human-made technology in pretty much every relevant aspect.

One particular aspect in this regard is robustness which leads to graceful degradation of the overall system performance in case of any trouble, outage, or similar issue.

Bio-inspired design is an important key to unlocking robustness for our self-designed systems.

For example, in multi-agent systems (think swarm intelligence) agents must communicate by definition to enable a gross coordinated behavior.

In the sciences of intelligence we differentiate this into *explicit* and *implicit* communication.

Explicit communication means that one system (computer) is allowed to directly alter the nervous system (memory) of another system (computer) as a means of transmitting a chunk of information from one place to another.

IoT devices and all other computers and technical systems in general usually use explicit communication.

Implicit communication means that the sender and the receiver of the information are only indirectly coupled.

A metaphor is galvanic coupling among electric circuits which is avoided by design for sensitive applications to avoid some fundamental interferences.

Computer systems and networks should be built using implicit communication models.

EOT

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

