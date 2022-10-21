---
layout: post
title: grounding
comments: true
tags: robotics research AI startups grounding fail robot epistemology
---

### grounding

> what is 'grounding' and why is it important

Over the last few years I have picked up more and more on the term
_grounding_ to talk about a robot's knowledge of the physical world
and especially for identifying _grounding fails_ as they occur in
my own robot experiments, personal experience of the technicized
world, or through the news.

Grounding is related to the symbol grounding problem (SGP) in AI,
which you might be familiar with. Especially in good old-fashioned AI,
reasoning is often modeled as inference over mental _symbols_. The
symbols represent outside objects, their relations to other objects,
or other environmental states. Now, the symbol grounding problem
occurs when you ask to what extent, and how precisely any such symbol
is __grounded__ in, aka connected to, the raw sensorimotor data. The
raw sensorimotor data is a multidimensional stream of noisy data
impinging on the robot via the entirety of its sensors.

The grounding should be a complete description of how sensor values
change symbol states and how sensor values can be predicted from
symbol states. If a symbol's grounding is even only slightly off, this
might be amplified during inference, producing potentially large and
disastrous errors when the inference is being committed to, aka sent
to the motors and an action is performed.

Depending on your philosophical stance you might disagree but raw
sensorimotor data is the only source of information available to an
organism in any given moment, apart from the phylogenetic information
it carries. Introducing symbols into robots where the symbols are
taken from introspection into human mental activity creates large risk
to end up with _dangling_ symbols and associated downstream
effects. Introspection is very limited in what brain processes it can
actually access. This issue has crucial relevance for the
trustworthiness of a robot.

> grounding fails

What happens if the grounding is bad and a grounding fail occurs?

Many systems being built which surround us and shape our lives are
usually designed according to a natural language specification which
is known to be ambigous. Then engineering kicks in to solve each
point of the spec. If the project is framed in narrow terms
(Kahneman), it is likely that a solution is created that fits the spec
but does so in a fragile way that relies on assumptions that often do
not hold. The situation is illustrated in the picture below.

![Classical scaffolding and newschool piling.](/assets/2020-02-28-grounding/smp_scaffold_pile_classical_piling_v3_small.jpg){:height="100%" width="100%"}

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

List of funny and serious examples
- Janelle Shane's supernice blog on [https://aiweirdness.com](https://aiweirdness.com) is full of this
- Alexa doll house incident, radio runaway / replay attack, [https://www.theverge.com/2017/1/7/14200210/amazon-alexa-tech-news-anchor-order-dollhouse](https://www.theverge.com/2017/1/7/14200210/amazon-alexa-tech-news-anchor-order-dollhouse)
- Accidental recording and leak of couple arguing to random addressbook contact, [https://www.theguardian.com/technology/2018/may/24/amazon-alexa-recorded-conversation](https://www.theguardian.com/technology/2018/may/24/amazon-alexa-recorded-conversation)
- new scientist: adversarial foo: [https://twitter.com/newscientist/status/1122794657568698369](https://twitter.com/newscientist/status/1122794657568698369)
- AI hallucination problem: pareidolia: face in the street: [https://www.wired.com/story/ai-has-a-hallucination-problem-thats-proving-tough-to-fix/](https://www.wired.com/story/ai-has-a-hallucination-problem-thats-proving-tough-to-fix/), [https://en.wikipedia.org/wiki/Pareidolia](https://en.wikipedia.org/wiki/Pareidolia)
- steganographic audio attacks to voice recognition
- Darling: mobile office printer falling off the stairs
- Darling: Elon Musk conceding to problems in attaining desired scope of automation in tesla factory
- Chess robot in Moscow pinches and breaks finger of seven year old, twitter opt?
- ** DONE posts: chess robot breaks finger of seven year old <2022-08-10 Mi>
- 2020 first year a human got killed by a fully autonomous drone, twitter opt?
- feed: robotics: fails: drone lands on power lines https://twitter.com/BotJunkie/status/1575704353536868352, https://www.abc.net.au/news/2022-09-30/food-delivery-drone-lands-on-power-lines-qld-browns-plains/101489670
- feed: AI: fail: https://spectrum.ieee.org/machine-learningbackdoor
- feed: AI: fail: https://spectrum.ieee.org/artificial-intelligence-in-government
- feed: tech: fail: https://spectrum.ieee.org/can-you-trust-nist

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

- TODO: Explain proprioceptive grounding and force gauging
- TODO: Explain nonintuitive decompositions
- TODO: Q: Is intuition the same as introspection? Does intuitive mean recognizable by means of introspection?

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

