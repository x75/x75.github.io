---
layout: post
title: flatcat audio manual
author: Oswald Berthold
date: 2024-05-05
comments: true
tags: robotics message-passing computer-music supercollider
---

## how to make flatcat audio work

log into flatcat, ctrl-C on `ux0_serial` and start `./ux0_serial_osc`, or boot into `ux0_serial_osc` automatically via editing

    vim jetpack/flatcat_setup/boot/start-tmux.sh

to point to `./ux0_serial_osc`

for nupg setup, go to

    cd /home/src/supercollider/scapps/flatcat

and run

    python flatcat-server-2.py

this takes `/flatcat` messages on 8999, does some pre-processing and
the projection. outgoing messages on `/flatcat2nupg` that can be
plugged directly into the nupg channel control set.

to reload the projection matrix use this command. the density
parameter (0.8) can be varied between 0 and 1

    oscsend localhost 8999 /matrix_reload f 0.8

to run the audio, start supercollider / scide open the
`/home/src/supercollider/nupg/startup-interactive.scd` file and run
that. it starts the nupg and spawns the GUI. in the server window,
click the `boot` button to start the server.

open `/home/src/supercollider/scapps/flatcat/flatcat-nupg-2-synth.sc`

and run the code blocks

to use NTMI, stop the flatcat-server-2.py script, as NTMI uses the
`/flatcat` data directly

open `~/bla.sc` and run the line with

    NTMI.run;

again, the NTMI GUI starts

open `flatcat2NTMI_basic.scd` or `flatcat2NTMI_better.scd` and run the
respective file entirely (execute buffer)

note: in ~/NTMI/flatcat.desc.scd you need to add your flatcat source
address for supercollider to accept the messages. if you use flatty in
ap mode this is better, actually because the source IP is always the
same.

### flatcat audio links: slides & videos
- neural synthesis slides nov 23 <https://docs.google.com/presentation/d/1hsxpIO2ab4e1rv_Tq3vTuX-VcE2S1dQQoUhKD0Cljm0/edit?usp=sharing>
- artist talk kunsthochschule kassel may 3 <https://docs.google.com/presentation/d/1aHRP-3jBx_Ov5S937N2cYjaV8iJV9dG9ROk_iZkvZJM/edit?usp=sharing>
- flatcat audio initial prototype 1 <https://youtu.be/8twXVcml3dg?si=QRA_NGPoQa4TK549>
- flatcat audio initial prototype 2 <https://www.youtube.com/watch?v=piMOrglS96U>
- flatcat audio initial prototype 3 <https://www.youtube.com/watch?v=5vYb9miMJfE>
- flatcat audio initial prototype performed by thomas <https://www.youtube.com/watch?v=w1-2qQGfQYE>
- flatcat audio in the street front of lab <https://www.youtube.com/shorts/Vxv2nxqixLg>
- flatcat audio kensington 1, <https://www.youtube.com/watch?v=1zdpqvniwoQ>
- flatcat audio kensington 2, <https://www.youtube.com/watch?v=eZg3PI-37k0>
- flatcat audio on-stage nnoi bwo eva, <https://www.youtube.com/watch?v=dFJPtAW5Yjk>
- flatcat audio on-stage nnoi marcin, <https://www.youtube.com/shorts/mtdXeNPpbaM>
- flatcat audio on-stage novilla, <https://www.youtube.com/watch?v=KDftj5R7FeA&t=3780s>
- flatcat audio on-stage zügellosen bwo mitch, <https://www.youtube.com/watch?v=KxriWdqYuO4>
- neural synthesis recording <https://www.youtube.com/watch?v=3Knd6O4XKxg&t=264s>
- hellisotherpeople

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

