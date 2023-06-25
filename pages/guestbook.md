---
layout: page
title: "Gästebuch"
subheadline: "Hinterlasse uns deine Nachricht"
teaser: ""
permalink: "/guestbook/"
sitemap: true
header:
    image_fullwidth: "hammer_scenic.jpg"
---

Gib unten deine Nachricht ein.
Man benötigt keinen Account, es gibt eine Option "I'd rather post as a guest", bei der man lediglich den Namen und eine E-Mail hinterlassen muss.
Beiträge, die ohne Account verfasst werden, müssen meistens leider noch manuell freigeschalten werden, hier also nicht wundern.

<div id="disqus_thread"></div>
<script type="text/javascript">
    /* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
    var disqus_shortname = '{{ site.disqus_shortname }}'; 
    var disqus_identifier = '{{ page.url }}';

    /* * * DON'T EDIT BELOW THIS LINE * * */
    (function() {
        var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
        dsq.src = '//' + disqus_shortname + '.disqus.com/embed.js';
        (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="http://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>