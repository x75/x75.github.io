---
layout: post
title: chatGPT reveals itself to be ungrounded by its comment on proprioception
author: Oswald Berthold
date: 2023-01-23
comments: true
tags: robotics AI
---

## A one-shot interaction with chatGPT asking for comment on proprioception

Refraining from the usual screenshot-based commentary but otherwise
standard, chat session starts with a prompt by an agent

> **Oswald Berthold**:
>
> what do you know about proprioception and why it is so important for safe AI?

Which is reacted on by the other agent. Will dissect the original
four-paragraph reply with immediate inline comment.

> **chatGPT**: 
>
> Proprioception is the sense of the position and movement of the body,
> and it is important for safe AI because it allows a robot or AI system
> to be aware of its own body and its position in relation to its
> environment. This is important for a number of reasons.

This is entirely correct, proprioception is the sense of position and
movement of the body. Most importantly, this refers to that part of the
sensation which is conveyed even with your eyes closed, a point missed
by the AI.

> First, proprioception helps a robot or AI system to navigate its
> environment safely. For example, if a robot has proprioception, it can
> detect when it is about to bump into an obstacle and take appropriate
> action to avoid the collision.

Proprioception does help a robot to navigate its environment
safely, you are good there chatty. The example on the other hand is
old-school in terms of framing it as obstacle
avoidance. Framed more accurately, proprioception allows us to detect
obstacles, but not so much in the "when-we-are-about-to" way, instead
more in the "when-it-has-already-happened" way. The special thing
about proprioception then is, that it is incredibly fast. It is so
fast, that it allows you to adapt your speed or direction of motion so
quickly, that many times you will manage to influence the action
(motion) consequence, **while** you are bumping into
something. Consider the timescale of these events, it is in the
few-milliseconds range.

> Second, proprioception can help a robot or AI system to interact with
> its environment in a more natural and intuitive way. For example, if a
> robot has proprioception, it can use its sense of touch to detect when
> it is holding an object and adjust its grip accordingly.

This is correct again on a superficial level, but misses the point in
the same way as for the previous items, in the framing. Proprioception
does not happen primarily on the *object* level, but instead on the
level of the individual motion. So the salient stimulus here is the
moment when the motion does not yield the predicted response, because
it is hitting the object (general class of external entropy by way of
condensed matter physics), but this applies to each individually
moving articulation of the body, and foremost, their integration needs
to be taken into account.

This is quite informative since we know how the response was informed
(average internet discourse), so the issue is there but it is
discussed in wrong terms, entirely.

> Overall, proprioception is an important capability for any robot or AI
> system that is designed to interact with the physical world, as it
> allows the system to be aware of its own body and its position in
> relation to its environment, which is necessary for safe and effective
> operation.

This only repeats what we said two paragraphs ago, and is cyclical
reasoning in its reference to safe operation. Two slightly vague
paragraphs of response do not count as "a number of" reasons, so again
we are cyclical in the argument.

There certainly is a larger discussion going on about common sense and
an understanding of physics which we require of trustworthy AI. This
discussion aligns very well with our own framing in terms of *grounding*.

### References
 - chatGPT errors: submit form: <https://researchrabbit.typeform.com/llmerrors>
 - chatGPT errors: database: <https://docs.google.com/spreadsheets/d/1kDSERnROv5FgHbVN8z_bXH9gak2IXRtoqz0nwhrviCw/edit#gid=1302320625>

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

