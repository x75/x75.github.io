---
layout: post
title: Book review - Wayfinding by Michael Bond
author: Oswald Berthold
date: 2022-04-24
comments: true
tags: feed books navigation wyafinding cognition mapping psychology decision risk robotics AI intelligence computational ethology
---

## Wayfinding

![Wayfinding (paperback) by Michael Bond](/assets/wayfinding-signal-2022-04-26-124833-600.jpeg){:class="img-responsive"}

By way of a friend I got my hands on a very nice little book called '[Wayfinding - The science of how we find and lose our way](https://www.amazon.co.uk/Wayfinding-Art-Science-Find-Lose-ebook/dp/B07XP8P2NW)' by [Michael Bond](https://www.michaelbond.co.uk/). Sometimes life is fast and we dived right in.

In short, it is a very sensitive, gentle, empathic, and well researched book on the topic of human wayfinding. It is about different kinds of spaces that we end up navigating as humans, and the effect they have as well as the different challenges these environments pose. It is, at the same time, about the neuro- and cognitive science of how animals, including humans, actually manage to traverse space in coordinated manner utilizing their neuronal circuits, aka the brain.

Starting out with a historical and evolutionary account of wayfinding, it covers the importance of the right to roam for children with respect to their cognitive development, goes into two chapters of the neuroscience of first, the actual navigation in extrinsic space, and then, that about how these same circuits are reappropriated for more abstract types of cognitive activity, aka thinking, and how extrinsic navigation skills affect the ability to navigate mental spaces. The second half of the book is about how all this plays out in real world scenarios, touching on mindfulness, non-existent gender differences, getting lost and decision making under fear, getting lost under dementia or depression, inhumane architecture and state-fo-the-art-neglect in city planning.

Having looked a lot at bio-inspired navigation strategies for robots, including the neuroscience of animal navigation, it was an extremely satisfying and reaffirming read, and it was an interesting one with a lot of enriching context, that again is highly relevent for reappropriating into robotics. I would totally recommend chapters 3 & 4 as a gentle introduction into brain-based navigation for both humans and robots.

The book is great and a recommended read, the rest below here is just my roboticist ruminations.

### Possible additions

In robotics we are concerned with putting it all together in a functional and resilient way. A universal algorithm for getting any articulated (having limbs and inner degree of freedom) robot to locomote, is an open challenge.

Starting with a mammal is already quite high up an organizational ladder. All animals possess an acute sense of space, and it is devilishly interesting, to see how such an abstract concept of space like Euclid's R3 is extracted and bootstrapped from a massive set of very rudimentary yet fully grounded and overcomplete spatial senses, including chemical gradients, force, and touch.

Based on mentions of desert ant navigation, it would be straighforward to include an entire chapter on the motion and navigation strategies used by anyone up from single celled organisms, to insects, fish, and birds. There is quite some theory about how the brain evolved as a motion computer in the first place. Plants do not have brains, it is said (It does not mean they are any less intelligent, though).

My personal mission is to expound the importance of proprioception to any trustworthy type of so-called intelligence that roams the world. Proprioception is intricately tied to our perception of force, our orientation in the gravitational field of earth, to our predictive learning circuits in our amazing brain, and curiously to the foundations of physics. The point is, that our understanding of three-dimensional space was actually bootstrapped through a much higher dimensional space of articulate proprioception. This is a truly astonishing feat of the inside-out learners we all are, including both onto- and phylogenetic adaptation.

There is a robot mentioned in the book and it does get a page or so. Another entire chapter could be added about robot navigation in fact, choosing freely from a large variety of documented robot navigation systems acting out in the real world.

### Final notes

There is a notion and some evidence that the brain evolved as a motion computer in the first place, thus it is a spatial reasoning engine. Embodiment research has documented a trajectory of where abstract thinking (aka intelligence) including mathematics (Where mathematics comes from) comes from. This is one of the weirdest and most interesting bits about the brain, that it kind of finds out how it can *reuse* the circuits adapted for one particular domain to an entirely different domain, by way of a matched modeling relation (Rosen).

The canonical three-dimensional euclidean space of cultural perception is a great achievement and the intrinsic perceptual spaces of almost all orgamisms have more dimensions. Thinking is all about spatial reasoning, only that the dimensionality of mental spaces is not restricted to three dimensions.

In robotics we need to model at least four layers of spatial competence:
 1. The biochemical layer for joint action and coordinated limb movement
 2. The inner space of inter-limb-coordinated movement
 3. How particular limb movement coordinated with respect to gravity leads to locomotion
 4. Once you locomote, how to navigate and bridge large distances with the entire body viewed as a point mass
 
All these layers connect with questions about adequate spatial exploration and modeling strategies. One of the most pressing ones is exploration, that is, what do you do when you have no idea? Without energy constraints, exploration can do everything that knowledge can do, only alas, energy is asking for a trade-off. What does it have to do with dynatropes? Well, if dynatropes are moving in the space of empowerment, they are still down to a locomotion and navigation task, only that the space is a bit more weird but no less relevant.

### References & see also
 - Bond, 2020, Wayfinding, The art and science of how we find and lose our way, <https://www.amazon.co.uk/Wayfinding-Art-Science-Find-Lose-ebook/dp/B07XP8P2NW>
 - Rössler, 1976, Rössler, O.E., 1974. Adequate locomotion strategies for an abstract organism in an abstract environment—a relational approach to brain function. In Physics and Mathematics of the Nervous System (pp. 342-369). Springer, Berlin, Heidelberg. <https://link.springer.com/chapter/10.1007/978-3-642-80885-2_19> Write me for a copy of the article.
 - Franz & Mallot, 2000, Biomimetic robot navigation, page 3, Navigation hierarchy, <https://www.sciencedirect.com/science/article/abs/pii/S092188909900069X>
 - Poincare, Science and hypothesis, Part II: Space, Chapter IV: Space and geometry, <https://www.gutenberg.org/ebooks/37157>

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

