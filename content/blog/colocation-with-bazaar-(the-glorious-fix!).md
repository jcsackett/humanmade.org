---
kind: article
created_at: March 16, 2012, 4:36 pm
title: Colocation with Bazaar (the glorious fix!)
---

<div><p>Last I <a href="http://blog.humanmade.org/post/19018238488/colocation-with-bazaar">blogged about bzr</a>, I complained about screwing up my use of
<code>bzr lp-propose</code>. As suspected, this was entirely my fault, and there is one
line to fix it.</p>
<p>In my locations.conf file I added the following.</p>
<pre><code>[/home/jc/Code/launchpad/devel/.bzr/branches/devel]
public_branch = bzr+ssh://bazaar.launchpad.net/~launchpad-pqm/launchpad/devel
</code></pre>
<p>The public branch for your trunk is pretty important, as it turns out. So, bzr
becomes a little bit closer for me, and if you&#8217;re following along and using
it, hopefully for you too.</p></div>