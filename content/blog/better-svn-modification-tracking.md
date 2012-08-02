---
kind: article
created_at: March 30, 2010, 5:25 pm
title: Better svn modification tracking
---

<div><p>We use svn at work (we&#8217;re looking at hg or git, but that&#8217;s a different discussion) and we have projects with huge external lists. That means the output of a generic <strong>svn st</strong> command can be incredibly difficult to parse.</p>
<p>I&#8217;ve been using <strong>&#8212;ignore-externals</strong> and piping through grep often enough that I finally slapped it into a shell script on my path. It&#8217;s been incredibly useful for me; perhaps it will be for you as well.</p>
<script src="http://gist.github.com/349610.js?file=find-mods"></script></div>