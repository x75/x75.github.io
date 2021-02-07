---
layout: post
title: Embed scope audio visualization 🝚
author: Oswald Berthold
comments: true
tags: audio embedding linux mapping music pxp scope sound visualization
---

### Embed scope audio visualization 🝚

#### Intro / Angles of incidence

As events go in the lifes of over-associating headcases, down in the
crypt doing some Gullibloon archeology. While making sure not to
double release on a track, digging out the pxp track published on a
compilation CD by the Alienation label in 2002 [1].

While listening to the track starting to play with audio scopes,
looking for a real time vectorscope (aka phase scope). 'meterbridge'
is OK but not totally satisfying, so moving on to jack-scope [2]. We
are on Linux and are using the Jack Audio Connection Kit [4]. Seconds
before ditching jack-scope, attention tangles up in the `-m` option
for setting the scope operating mode. Clipping the manual entry for
drama,

```
-m : Set the scope operating mode (default=signal). The operating
modes are: signal and embed.
```

⚠ Ugh! Being in a relationship with 'embed' its name screams dopamine-ahead at me 🚨.

#### Embeddings

Embedding is a mathematical name for a family of structure-preserving
maps. Don't run yet, because everyone knows embeddings as a thing of
experience and this is only another name for it. As an example of an
embedding present in a real life process, take

> A set of counters each serving one customer taken from a queue of
> incoming customers arriving at a shop.

If you know what a delay line is, that's your embedding too. Same for
moving average and sliding window operators. What a delay line does,
besides delaying the stuff going into it, is create a map from single
consecutive events at several moments in time to a set of several
simultaneous events in a single moment of time. In the standard use
case this is not apparent because the delay line is only tapped at the
end, but the term 'line' tells it. The sum delay at the end is created
using a line of unit delays. Thinking multitap delay the embedding
comes out clearly. 🝚

TODO: picture

For sound visualization of a single channel signal which provides a
single number at every instant, we can use a delay line with two
elements and draw a dot at the two-dimensional coordinate made from
the current and the last number. Thats the basic principle, everything
else is parameters.

TODO: picture

#### Embed mode with jack-scope

Now jack-scope can do embed mode visualization from a jack audio
signal. Did that for the pxp - squeezer-2002 and recorded a screen cap
of that which you can watch below or on
<https://youtu.be/BQRzuW0mlBo>.

<iframe width="560" height="315" src="https://www.youtube.com/embed/BQRzuW0mlBo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

It works very well to indicate general phase coherence for
example. The more of that, the more stable the point cloud
becomes. Apart from that it makes awesome patterns on these drone
things with ultra low modulation depth. While the points' visibility
and rendering could be improved I suggest to contemplate the frailty
as a charm in this episode.

The command used for creating the scope in the video is

`jack-scope -m embed -n 2 -d 20 -p PortAudio:out_\%d`

where the track is playing from audacity on the PortAudio jack
terminals. The man-page has a link to a paper on the technique [3]
which is paywalled. If you join our audio research group the document
can be shared. Also discovered only while writing this up that bwo my
OS version I am using a slighly old or underdocumented version of
jack-scope compared with [2]. A nice feature of jack-scope is that
many visualization parameters can be controlled at run time via
OpenSoundControl commands. Ha! Awesome.

#### Relevance

I have known and used embedding technqiues for years but it never
occured to me to use it on the single sample level and look for, or
make, tools to do that. Maybe in commercial music software land it's a
commodity that everyone's using up and down. I think the embed scope
technique is little known and used and this is the reason for writing
this. Check if your scope has that and if not, talk to your scope
vendor and drop them a feature request. Please leave a comment on this
page about any findings or reports you might be able to share, curious
to learn.

#### Future work

Building autovideo I have become a daily user and passionate lover of
ffmpeg. Obviously, an aembedscope is needed. Have never done an ffmpeg
plugin but should be possible. Keep you posted and please let me know
if you happen to be working on that or even have it ready to use.

#### See also and further reading

-   Embedding, <https://en.wikipedia.org/wiki/Embedding>
-   Return maps and Poincare cut, <https://en.wikipedia.org/wiki/Poincar%C3%A9_map>
-   Recurrence plots, <https://en.wikipedia.org/wiki/Recurrence_plot>
-   Self-similarity matrix, <https://www.audiolabs-erlangen.de/resources/MIR/FMP/C4/C4S2_SSM.html>
-   Delay embedding theorem, Taken's theorem, <https://en.wikipedia.org/wiki/Takens%27s_theorem>
-   The Dripping Faucet As A Model Chaotic System, Robert Shaw, 1984, <https://archive.org/details/ShawRobertDrippingFaucetAsAModelChaoticSystem1984_201811>

### plinks

-   x pxp squeezer track autovideo foo
-   x jack-scope man page and embedding scope
-   x Sound Visualization Using Embedding: The Art and Science of Auditory Autocorrelation Gordon Monro and Jeff Pressing, <https://www.jstor.org/stable/3680961?seq=1#metadata_info_tab_contents>
-   x Sound Visualization Using Embedding: The Art and Science of Auditory Autocorrelation <https://www.jstor.org/stable/3680961>
-   x see also: embedding, recurrence plots, self-similarity matrix, embedding theorem, the dripping faucet as a model chaotic system
-   x see also: ffmpeg, aembedscope?, <https://amiaopensource.github.io/ffmprovisr/>

[1] Alienation Presents: International Compilation CDr<sub>4</sub>, SU40 <https://www.discogs.com/Various-Alienation-Presents-International-Compilation-CDr_4/release/1356487>, see also SU06 on <https://www.discogs.com/Various-Alienation-Presents-International-Compilation-CDr/release/116676>

[2] rju - jackd utilities, <http://rohandrape.net/?t=rju>

[3] Sound Visualization Using Embedding: The Art and Science of Auditory Autocorrelation, Monro and Pressing, 1998, CMJ, <https://www.jstor.org/stable/3680961>

[4] Jack Audio Connection Kit, <https://jackaudio.org/>

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
