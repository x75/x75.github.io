---
layout: post
title: From snowboarding to motion, music, and robotics
comments: true

---

## From snowboarding to motion, music, and robotics

__Keywords__: motion, robot learning, exploration, music, bio-inspiration

Recently while browsing my [favorite robotics
magazine](https://www.redbulletin.com/at/de/the-red-bulletin-magazin)
I started reading an interview with Travis Rice, previously unknown to
me, promoting his recent film [The Fourth
Phase](http://www.thefourthphase.com/). It's usual that athletes
mention issues interesting to robotics when talking about their body
and the challenges involved in particular stunts, which is the reason
why RB in fact is my fav'ed robotics mag in the first place. What
struck me about this interview, though, is that Travis just didn't
stop dropping major agreeable insights about motion and environments
and possible responses of an agent. Sorry for the german text, here's
the [english version of the
interview](https://www.redbulletin.com/uk/en/sports/travis-rices-quest-for-the-ultimate-snowboard-adventure)
which seems nicer in the formulations anyway ;)

![Snowboarding and music]({{ site.url }}/assets/20161109_rb_rice/rbrice_01_IMG_20161103_091430_400.jpg "Snowboarding and music")

This is about adaptive rhythms which _play_ with the topographic
situation and the transitions between local configurations, the result
being a combination of the influences of the environment and the
individual response. The same evaluation criteria seem to apply for
music and motion in terms of the _groove_. Would be nice if we could
capture that as a loss criterion for learning motions, like, what is
a nice dance for a given song.

![Topography, saliency, navigation]({{ site.url }}/assets/20161109_rb_rice/rbrice_02_IMG_20161103_091444_400.jpg "Topography, saliency, navigation")

First we need errors to do any actual learning, no problem. Then this
is about picking salient features of the topography, landmarks, as
reference points to attach triggers for specific action sequences.

![Flow, reaction speed and mental simulation]({{ site.url }}/assets/20161109_rb_rice/rbrice_03_IMG_20161103_091455_400.jpg "Flow, reaction speed and mental simulation")

Adequate reaction speed requires a flow-state which means very little
or zero conscious participation in the motion control. Not sure about
the fear stuff in the context of robotics. Finally, mental simulation
is being used for finding an action sequence that copes with some
topographic situation and is being pushed down during the simulations
into low-level action control.

![Search objectives, exploration]({{ site.url }}/assets/20161109_rb_rice/rbrice_04_IMG_20161103_091506_400.jpg "Search objectives, exploration")

This is about search criteria where you are trying to find features
that provoke motion solutions which are supposed to be rewarding in
the musical sense, which provides inspiration for interesting
exploration objectives for robots ("... geological oddities. We want
weird. Weird is good"). Actively seek out environmental and perceptual
challenges such that entirely new behaviour needs to be generated in
response.

![Motivations, objectives]({{ site.url }}/assets/20161109_rb_rice/rbrice_05_IMG_20161103_091511_400.jpg "Motivations, objectives")

Finding an _answer_ to weird and unusual environmental stimuli that
you have sought out earlier using the weirdness search objective.

Cheers, let's move.

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
