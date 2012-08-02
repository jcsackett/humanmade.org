---
kind: article
created_at: February 21, 2011, 5:06 pm
title: ZNC
---

<div><h3>The Situation</h3>
<p>Staying in touch is a requirement for everyone working on <a href="http://launchpad.net" title="Launchpad">Launchpad</a>, much as it is for all of Canonical.</p>
<p>In addition to using a ton of email, voice chat tools like <a href="http://mumble.sourceforge.net/" title="Mumble">mumble</a> and <a href="http://skype.com" title="Skype">skype</a>, our biggest communication medium is IRC. While any other tool is a &#8220;use when you need it&#8221; sort of thing, the expectation is that you will always be on IRC.</p>
<h3>The Problem</h3>
<p>I use two computers in my work day&#8212;my mac for a lot of coding and some design work, as well as project tracking, and my <a href="http://knowledge76.com/index.php/Daru2">Darter Ultra</a> for serious work and ui testing. Staying on IRC on both computers can be a hassle. Either I&#8217;m using different nicks on each one and making my colleagues figure out which one is the &#8220;real&#8221; me at any given moment, or I&#8217;m going through a sign-off, sign-on dance as I swith between machines. Add in that I have an IRC client on my phone and my iPad that I sometimes use (if I&#8217;m moving away from the computer or commuting for a bit, but want to stay in touch) and I have serious complications and hassles for me, my coworkers, or both.</p>
<h3>The Solution</h3>
<p>There is a <em>fantastic</em> tool called <a href="http://en.znc.in/wiki/ZNC" title="ZNC">ZNC</a> which steps into save the day. It&#8217;s an IRC bouncer, which relays connections from one computer to another. I set it up on my server, and have it login to all of my IRC networks. Then, I connect to it from all of my IRC clients.</p>
<p>The end result is that each client is actually just using the same connection; I can be on IRC from all of my devices, using the same nick, and sharing the same chat history, without going through any sort of odd sequence of signing off and signing on.</p>
<p>There are some additional perks too. ZNC lets me always be on IRC, so I don&#8217;t miss any mentions of my nick or conversations I need to know about. It can log all conversations on the server, as well as transmitting some set number of lines of history to any client when you sign on. There&#8217;s also a host of plugins, like a <a href="http://en.znc.in/wiki/Webadmin">webadmin</a> for your ZNC configuration or a <a href="http://en.znc.in/wiki/Notifo">notifo plugin</a> to send your highlights to your mobile device.</p>
<p>It&#8217;s easy to setup on ubuntu servers; &#8221;&#8217;sudo aptitude install znc&#8221;&#8217; and then some simple configuration. If you use IRC a lot, especially from several devices, give it a try!</p></div>