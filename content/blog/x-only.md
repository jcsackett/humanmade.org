---
kind: article
created_at: November 17, 2010, 9:18 pm
title: X Only
---

<div><p><a href="http://onethingwell.org/post/1432068153/x-only">One Thing Well</a> had a really useful post not too long ago showing how to run an X application without firing up a full window manager.</p>
<p>In my work, I use a number of servers (running as VMs). These have firefox installed, because it&#8217;s a dependency for the launchpad windmill tests. But, because they&#8217;re servers, they don&#8217;t have any windowing environment, and I&#8217;d really rather not install one. This x only trick is so useful for me, that I scripted up a little version of it that I can pass an application and tty # to it without having to think about the xinit arguments.</p>
<p>The gist for it is below:</p>
<script src="https://gist.github.com/704532.js?file=xonly"></script><p>It is, obviously, trivially simple. But it is <em>so</em> handy. Thanks to One Thing Well for sharing this.</p></div>