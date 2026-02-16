---
layout: post
title: LLMs, coding agents, benchmarks grounding
author: Oswald Berthold
date: 2026-02-09
comments: true
tags: ai llms coding-agents benchmarks criticism
---

## LLMs, coding agents, benchmarks grounding

Grounded airplanes are airplanes that need to stay on the ground, not fly.

The openclaw x codex 5.2 x claude 4.6 x codex 5.3 avalanche from end
of Jan to beg of Feb didn't quite leave me alone, so here goes some
self-normalization attempt.

Despite big claims floating around, it is LLMs all the way down, so there is good reason for skepticism.

There is two parts of the perceived narrative, one is the companies themselves making ungrounded claims based on ungrounded benchmarks. And then there is user claims based on their specific usage profile.

On the other hand there is general longstanding critical evaluation, and my own individual experience with coding bots.

Benchmarks are good to have but they are usually far from providing a complete picture. I summarize this to myself as "the smarter the thing to be evaluated, the harder the evaluation". This is to say, any such evaluation trying to cram the entirety into a single (or a few) numbers, is suspicious at best.

Benchmarks are being gamed (anyone remember Llama 4 release a year ago?). Benchmarks are not only gamed by the human stakeholders, but also by the models under evaluation themselves (cheating). This seems new as of last year, 2025.

The incentive for a vendor is clear, if benchmark number go up, business number go up. Good for them, but

>   LLM vendors seem to regard benchmarks as marketing tools to
>   increase their valuation, and have noticed that while valuations
>   go up if they report good benchmark performance, they dont go down
>   if obscure academics question the validity of their claims.

Granted. For individual users, they are testing things based on their own specific context, and while things might work well there, it doesn't say much about how well it might work for my own specific context. The smarter the thing, the harder to evaluate. Repeat.

If LLMs are anything, they are prime stereotyping machines, cutting out the long tail and professing on serving the 1% tasks that get 99% of the popularity. This popularity might be a real world usage frequency, no question. Boilerplate code. Repetive tasks. Either way, whenever I tried to do something less stereotypical, I was met with zero shot failure and had to take the thing by the hand, break it down into small digestible pieces, and work it from there. This is a type of "drift" across category and I claim the "adaptation" to myself.

I can see that there is a point in this one off "throwaway" prototyping approaches or other simple, well defined applications with plenty of precursors. I have not seen maintainability of agent's code output being evaluated. And again, the stereotyping machine will make good interpolations between minor variations of the same thing, but it will fail without notice on anything that is not in the training distribution. By construction. Period.

This is my personal take and rant, done. Let's try and broaden the persepctive. One well-known problem with benchmarks is, that as soon as they become available, they become available for training. This is called train / test contamination, and if it occurs, it will lead to exaggerated results. Usually, neither the precise training data nor the benchmark trajectories themselves are disclosed. Will I trust any claim in this situation? I trust your guess.

Contamination seems rather minor though when you can just cheat on your exam. The cheating phenomenon seems to have become large during last year. For completeness, also called reward hacking. The issue not only pertains to benchmarking but also to in-the-field use.

Prime example for cheating? ImpossibleBench :) If you report more than 0% on this benchmark, you cheated, I love it <https://arxiv.org/pdf/2510.20270v1>

Silent but deadly failures <https://spectrum.ieee.org/ai-coding-degrades>

Do LLM coding benchmarks measure real-world utility? <https://ehudreiter.com/2025/01/13/do-llm-coding-benchmarks-measure-real-world-utility/>

Do LLMs cheat on benchmarks <https://ehudreiter.com/2025/12/08/do-llms-cheat-on-benchmarks/>

I mentioned the non-evaluation of maintainability above. Other people have much more fine-grained criticism going here, but that aspect is always included. This one goes beyond coding and touches upon these mistaken (gently said) AGI aspirations. Bottom line: right for the wrong reason. Check Melanie Mitchell's NeurIPS 2025 keynote writeup <https://aiguide.substack.com/p/on-evaluating-cognitive-capabilities>

Finally, crawling the 39C3 recordings, this presentation came to meet me going down the popularity ranking, "Agentic ProbLLMs: Exploiting AI Computer-Use and Coding Agents" by Johann Rehberger. Agents have been set up to not trust claims without visiting the link. Agents love to click on links: <https://media.ccc.de/v/39c3-agentic-probllms-exploiting-ai-computer-use-and-coding-agents>

And even more finally, I got interested in a comparison of genealogical trajectories, like how we went from transistor to integrated circuit, it took 13 years (1947 to 1960) <https://en.wikipedia.org/wiki/Invention_of_the_integrated_circuit>

Like how we got from transformers to reliability. If things get more difficult, the timeline might extend, despite acceleration narratives. After all, a narrative is just a narrative and not science, or something.

OK, Gary Marcus' super bowl vis-a-vis table from <https://garymarcus.substack.com/p/super-bowl-matchup-anthropic-vs-openai>

![](/assets/openai-x-anthropic-image.jpg){:class="img-responsive" width="100%"} 


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

