---
kind: article
created_at: July 20, 2009, 8:13 pm
title: Introducing Weaver
---

<div><h3>The Problem</h3>
<p>I work in Django, both professionally and in side projects. This leads to an ever growing number of sites to do deployment and updates on. Deployment is repetitive and irritating, even when you can just copy and paste config files around and do some local edits. Stuff always breaks, and take way more time than you thought you would.</p>
<h3>The Solution</h3>
<p>Automated deployments. For Django, right now, that means <a href="http://www.nongnu.org/fab/">Fabric</a>, which is a great utility. Simply write a fabfile, maybe with a few helper scripts here and there, and you have a utility to deploy to server after server, and update whenever you need to.</p>
<h3>The  Problem With The Solution</h3>
<p>You still have to write the fabfile conf files and scripts (if any). And while there&#8217;s less tweaking to be done once you&#8217;ve written it all, it&#8217;s still a pain. Again, you can do the copy and paste thing, but it&#8217;s still error prone, and if you&#8217;re me, still annoying.</p>
<h3>Enter Weaver</h3>
<p><a href="http://github.com/jaycee/weaver/tree/master">Weaver</a> makes fabric. Which is a pithy way of saying that weaver is a simple utility to create a fabfile, conf files, and some helper scripts to get everything laid out nicely.</p>
<h3>Problems with the Solution to the Problem with the&#8230;yeah</h3>
<p>Weaver is really suited to my style of deployments. As such, it makes a whole host of assumptions about the nature of your deployment. These are outlined in the README.</p>
<h3>Other Stuff</h3>
<p>It&#8217;s released under BSD.</p>
<p>I hope you find some use for it. Comments are welcome here. Issues are welcome at github.</p></div>