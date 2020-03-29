---
layout: post
title: android music studio
comments: true
tags: music android research startups
---

### android music studio

Making sounds and music on Android is my entertainment. This is an
attempt to document the setup.

#### Apps and tools

These are some apps sorted by approximate frequency of use

**VLC** open source power player for audio and video with music
scanning, playlists, directories, variable playback speed,
equilizer. Top player out there. App available from f-droid or Play
store.

**g-stomper studio** by planet-h.com, started to use it because it was
the first meaningful music app out there that supports Ableton Link to
synchronize with a session over wifi in the studio. Classical approach
32 channel drum machine and sampler plus 5+ synths plus a lot of
mixing, effects, arrangement functions. Made for performing live, nice
synthesis engine.

**Nanoloop** by nanoloop, legendary early Gameboy music app
reincarnated for Android, probly Apple as well. Unconventional
approach, 8 channels freely assignable to four types of instruments,
pulse-wave synth, fm synth, noise synth, sampler. Best bit is supports
full polyrhythmic sequencing for each channel, at least in the live
loop mode. It seems that recent updates have fixed the polyrhythm
issue for exporting song arrangement as well. Super nice, no audio
glitches ever, totally live suitable.

**Lexis Audio Editor** straight forward audio editor, load file, clip,
trim, compress, reverse, etc.

**RD4 Groovebox** by our friends at mikrosonic, has a drum machine,
one 303-style bass synth, and two generic synths, sequencer, pattern
composition, export etc. Unfortunately didn't get the Link update
until now, so phased out in favor of g-stomper.

**Audio Evolution Studio**, multitrack DAW app, does the job but is
just too crammed on my phone so not really using it.

**MobMuPlat** very nice idea, mobmuplat is an app that lets you build
graphical interfaces to libpd based patches that can run inside the
app. Need to design your patch and GUI, then send that over to the
phone to use it. Never really picked it up, mostly because getting
externals into libpd is not exactly trivial.

#### untested

**Caustic**, looks decent fully blown tracker, synth, sequencer, drum
machine sampler. Never really got into because other options. Still.

#### OSC

Some apps for sending OSC control from screen interaction or phone sensors.

**touchOSC**, classic.

**sensor2OSC**

#### termux power w/ command line tools

**Termux** is superpowers for the phone and v/ handy if you like
working on a linux shell. Let's you use Sox, aubiocut, the scientific
Python stack, even pulseaudio with a driver for OpenSL ES, and much
more. Does require significant attention though to get things working.

##### ReSampler

High quality command-line audio sample rate converter on [https://github.com/jniemann66/ReSampler](github).

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

