---
layout: post
title: Apparent uselessness
comments: true
tags: epistemology learning exploration motivation robotics
---

## Apparent uselessness

> The illusion of progress, and the difficulty of finding your way in
> complicated and unknown spaces.

Last year I picked up on Kenneth Stanley's and Joel Lehmann's 2015
book called [Why Greatness Cannot Be Planned - The Myth of the
Objective](http://mythoftheobjective.com/). In the book they develop
an argument for an advanced teleology based on experiments with
synthetic processes of knowledge acquisition in the context of AI,
ALife, and Learning. The argument roughly says, that if you want to
reach a goal, that is ambitious in the sense that the *exact* sequence
of steps (the route) which will get you there, is not known, then
accumulating possible steps is a better strategy than heading directly
into the direction of the goal. That's because chances are, that some
of these steps will turn out, but unforseeably so, to be precisely
what is needed to make the next move when negotiating the route. So
far so good, I agree with this line of reasoning.

In the meantime, additional manifestations of that same idea keep
popping up urging the collector inside me to collect. Here we go.

 - __2015__ Stanley and Lehmann argue that, considering results on
   "novelty search" in learning experiments with artificial agents,
   unreflected measures of the distance to a given "goal" are bound to
   get you stuck in a local extremum in all but trivial cases [^1].
 - __1939__ Abraham Flexner's article "The usefulness of useless
   knowledge" [^2], published in Harper's issue 179 June/November 1939 (available online as [PDF](https://library.ias.edu/files/UsefulnessHarpers.pdf)). Flexner curiously sketches out a similar line of argument as
   Stanley and Lehmann reinvigorating satisfaction of _curiosity_ as a sufficient and ultimately fruitful guide in the pursuit of knowledge.
 - __198X__ The field of media archaeology has been promoting the stance
   that complex techno-mathematical media can only be understood by
   reconstructing original forward-looking perspectives and
   emphasizing the genealogical importance of developments which
   became "dead media" only in hindsight.
 - __2007__ Nicholas Nassim Taleb, deserving a separate comment on the black
   swan idea (2007), meticulously expounds the difference of the
   forward and the retrospective narration and substantializes the
   phenomenon of unpredictability in the domain of complex systems (Extremistan). Honouring
   this fundamental unpredictabilty we should be highly doubtful
   about our ability to predict the future utility of any given idea.
 - This is an open list and this entry is a placeholder for things to
   come ...

Realizing the validity of this issue there are fundamental
consequences for many areas of human activity, two of which are:
autonomous robotic learning (no universal recipe) and funding of
professional and amateur scientific pursuits (no maps for uncharted
territory [^3]).

### Spectrum of difficulties in reaching goals

Based on my own understanding of different learning problems for
artificial agents there exists a spectrum of difficulty, open to the
top, along which learning tasks can be positioned. In that spectrum we
can draw a line somewhere separating two types of such
problems. **Update [2016-11-03]**: There is a direct correspondence here
with the complexity of functional relationships which could be ordered
like linear, monotonic, non-monotonic, zero/random. The line that I am
referring to above goes through the spectrum between monotonic and
non-monotonic problems.

There are those problems, in which the goal-seeker (agent) and the
goal are alone in "free space", meaning that the goal is visible to
the agent and the goal can be reached by following a monotonic
gradient, that is, by greedily reducing the distance on all axes of
space independently, reducing the problem to finding out about the
effects of the primitive actions (SMP) available to the agent.

The other type are those in which other objects, usually referred to
as obstacles, are present in the same space. Here already no universal
recipe whatsoever can be given on how to reach the goal without
exploring the space first and building a map. In order to reach a goal
or desired destination, the distance to the goal has to increase on at
least one axis of the given space at some point
(non-monotonicity). This means, that if the wrong distance measure is
used, you easily end up in a local extremum.

This issue also seems related to a) convexity, leaving the respective
reasoning and diagram as an exercise for a possible later post, and b)
to Franz & Mallot's navigation hierarchy from their 2000 paper [^4].

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

[^1]: See [this section](#spectrum-of-difficulties-in-reaching-goals)

[^2]: Thanks Giulio Sandini.

[^3]: Please describe in precise steps how you are going to reach an
	objective (draw a route on a map), which at best is likely to exist
	and usually is only a vision, and where no one has gone before (on
	parts of the map labelled "Terra incognita").

[^4]: Biomimetic robot navigation. M. Franz, and H. Mallot. Robotics and Autonomous Systems 30 (1-2): 133-153 (2000)

