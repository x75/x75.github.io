---
layout: post
title: grounding
comments: true
tags: jetpack, jcl, robotics, research, startups
---

### grounding

> what is meant by grounding and why is it important

Over the last few years I have picked up strongly on the term
_grounding_ to talk about a robots "knowledge" (robot epistemology)
and especially for discussing _grounding fails_ as they come in
through the news or through experience.

Grounding is related to the symbol grounding problem (SGP) in AI where
_thinking_ is often modeled as inference on mental _symbols_. The
symbols represent outside objects or object relationships. Now, the
SGP asks to what extent and how precisely any such symbol is
__grounded__ in, that is, connected to, the raw sensory data.

The grounding should be a complete description of how sensor values
change symbol states and how sensor values can be predicted from
symbol states. If a symbol's grounding is even only slightly off, this
might be amplified during inference, producing potentially large and
disastrous errors when the inference is being committed to, aka sent
to the motors.

Depending on your philosophical stance you might disagree but raw
sensory data is the only source of information available to an
organism, both individually and phylogenetically. Introducing symbols
taken from the introspection into mental activity creates large risk
to end up with _dangling_ symbols and associated downstream
effects. It appears the issue has crucial relevance for building
trustworthy robots.

> grounding fails

**insert** image scaffold and pile

The systems that are being built and which surround us and shape our
lives are usually built to a specification which is held in vague
(natural language) terms. Then engineering kicks in to solve each
point of the spec. If the project is framed in narrow terms
(Kahneman), it is likely that a solution is created that fits the spec
but does so in a fragile way that relies on assumptions that often do
not hold.

A premium grounding fail is the story of Alexa ordering an expensive
dollhouse in interaction with a kid playing dolls at home (Alexa,
order me the nicest dollhouse you know). This story made it onto a
radio news broadcast. During the live broadcast the scenario was acted
out and a few hundred Alexa's that listened to the radio show went on
to order the same dollhouse again (TODO: citation needed).

The fail here is that Alexa pretends to understand spoken human
language but in a fundamental way it doesn't. My favorite term here is
/preverbal/ auditory skills. Preverbal means things related to the
general acoustic setting which we constantly compute, such as general
acoustic activity; presence and location of sound sources; intermodal
cues from vision, smell, memory; tonus of a speakin voice; variability
of a speaking voice; and so. These properties allow to distinguish
fundamentally between different types of sound sources and we expect
them to be mastered before we even begin to speak ourselves.

**insert** list of funny examples

> pile of sheets

The proposal is to build these systems as piles of sheets. This
approach leads to a thickly interwoven structure that has very
favorable properties when sheets or groups of them fail. It is a
visual and metaphorical proposal but just as serious and we're out to
do it.

Each sheet can be thought of as a computational module, that has some
function and some capacity for adaptation. It solves some small part
in the large job of translating all raw sensory information to a
consistent high level state as it is perceived in conscious
experience. The high level is reached by piling thousand of sheets on
top of each other with higher level concepts represent by sheets
higher up in the pile.

Now if we fail and pull out one or more of these sheets from the pile,
nothing really happens. There will only be small readjustment to a new
equilibrium under the gravitational pull of unexplanation.

TODO: Explain nonintuitive decompositions.

TODO: Is intuition the same as introspection? Does intuitive mean recognizable by means of introspection?

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

