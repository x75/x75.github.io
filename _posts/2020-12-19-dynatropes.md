---
layout: post
title: dynatropes
comments: true
tags: definitions motion robotics principles research philosophy organization-of-behavior smp jcl gt
---

### Dynatropes

#### What is a dynatrope?

tl;dr Like plants are things that move towards more light, dynatropes
are things that move towards more options. A dynatropism is a motion
towards regions in space that provide more possibilities for different
and effective actions. A dynatrope is a thing performing this motion.

#### That's cool, but do we need this word?

The phenomenon is real for all we know and thus deserves a name. It
has come to play an important part in my personal thinking and thus
also in the projects I am in involved in,
[farmersmanual](https://web.fm) for one and even more so for
[Jetpack](https://jetpack.cl). There, we are looking hard for
appropriate names as part of a larger effort for developing
appropriate language to talk about the things that we are making.
That making even includes the language itself ⥁.
#### Just give the definition and be done, OK?

Dynatropism. from greek dynamis (power)[4] and tropos (a
turning)[5]. Drive to option, Streben nach Möglichkeit oder Kraft,
search for empowering states.

The dyna- part indicates power as the characteristic sensorimotor
modality. The -tropos bit means 'directed motion towards' by the
ability to turn into any direction at all.

Things that are controlled by a dynatropism are dynatropes.

The naming is compatible with the biological naming system [5], and
integrates seamlessly into the taxonomy of movements. It is used by
the BEAM [0] robotics community to categorize different BEAMbots
according to their goal seeking behavior, for example audiotropes,
phototropes, radiotropes, and thermotropes.

There is a precedent use of the term 'Dynatrope' [7] in the universe
of the TV series 'Doctor Who', produced by the BBC since 1963. By the
account in the fandom wiki [7], they "... were powered by mental
energy".

#### Context

An open question in robotics research is how does autonomous
development work? The type of thing we are going through, starting
with the egg cell, over fetus, infant, teenager to adult and then
onwards. The learning going on during all that time is immense and
intricately staged. We want to understand how this works and build our
machines in a similar way.

A good part of it can be accounted for with goals, how to choose goals
when no one provides them to you, how to tell good goals from the
too-easy or too-hard ones, when to persist and when to give up. This
goal juggling is the motivation. Many interesting models have been
proposed for motivation systems [citation needed]. One general
approach is called intrinsic motivation, and one variant of it is the
Klyubin-Polani-Nehaniv empowerment [6,citation needed,1,3], an
information theoretic measure.

As such, it provides a general measuring stick for the amount of
empowerment available in a region of space by 'counting' the number of
available options. Now a map of the space can be built visiting random
places and taking a measure at each place. The things that perform
directed motion in this space using the map can now be called
empowerment maximizing agents or intrinsically motivated agents. These
names are correct but bulky and awkward.

#### Get the word out

Working on the scientific and technical aspects of the concept, and on
the sensorimotor account of the method, are only one reason for a need
of language. From our specialist point of view it is obvious that an
account of the concept in everyday language terms could be quite
helpful in many other areas. Seeing it as part of our mission to help
create a broader understanding and the ability to apply the concept
and the learnings it provides. The diffusion of several important
research insights which have not made it into the general public
knowledge is a larger communication task worth a post of its own
[WIP].

#### We build bridges

We use the metaphors of building-bridges or playing-message-ferry for
reflecting this activity. As explorers and scientists it is part of
the job spec to do that. For some reason the task has been
insufficiently attended to or even neglected by the science community
at large for a long time. We think that this is part of the reason for
a gaping divide in people's and organizations' abilities of
reality-understanding.

Confounding causes with effects alone is bad enough, but teamed up
with dramatic social disparity it just creates a massive vortex cloud
of planet-scale annihilation options for humans and friends. Obviously
very undesirable and action required.

### Refs

[1] Klyubin-Polani-Nehaniv empowerment is a concept from artifical life and developmental learning research. Related concepts are intrinsic motivation, artificial motivation, autonomous learning, autonomous mental development, lifelong learning, homeokinesis, ultrastability, predictive information maximization, guided self-organization, and more. Highly recommended topic, also worth a post on its own [WIP].

[3] The everyday language meaning of empowerment corresponds quite well with whats made more precise in the mathematical model.

[0] <https://en.wikipedia.org/wiki/BEAM_robotics>

[4] <https://en.wikipedia.org/wiki/Dynamics>

[5] <https://en.wikipedia.org/wiki/Tropism>

[6] A. S. Klyubin, D. Polani, and C. L. Nehaniv, “All Else Being Equal Be Empowered,” in Advances in Artificial Life, vol. 3630, M. S. Capcarrère, A. A. Freitas, P. J. Bentley, C. G. Johnson, and J. Timmis, Eds. Berlin, Heidelberg: Springer Berlin Heidelberg, 2005, pp. 744–753.

[7] in: Spacecraft types: Dynatrope - Dynatropes were the machine spacecraft used by the Krotons. <https://tardis.fandom.com/wiki/Dynatrope>

### Extra detail
#### Tropisms basics

When things are moving around in space in any kind of way that's
motion. When things move around in a directed way thats a tropic
motion. Tropic motion is generated by a tropism, a biological control
system.

In perception the different channels like ears, eyes, noses, feet, and
so on are called sensory modalities. Sensory modality can be used to
put tropisms into different groups and then look at what is shared
among all tropisms and what is unique to particular tropisms.

There is a lot of cool words for many kinds of modalities. These words
are chosen to indicate the physical phenomenon that is the basis for
the biochemical reactions of biological receptors, like a hair cell in
the inner ear, or a photo cell on the retina. Gah, spilled it, so
photo means light, chemo means molecules, hydro means water, electro
means electro, everything else needs to be looked up on Wikipedia.

Now we can build a phototropism, understand that this is something
that looks where the light is coming from and directs the motion of
another thing doing the actual moving around. That thing is called a
phototrope. Chemotropes are things that move towards or away from
particular molecules. Most plants are phototropes, animals are
chemotropes, people too.

### TODO
- add fm/jcl logos and fandom wiki pic as dynatrope examples
- add reference to teleology in Context section re: BEAM goal seeking behavior

### Changes
- updates 2020-12-21
- early feedback fixing names and references 2020-12-20
- init 2020-12-19

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

