---
kind: article
created_at: March 17, 2010, 9:41 pm
title: Updates to the MassTexter
---

<div><p>I just pushed a few changes to <a href="http://github.com/jaycee/masstext/">masstext</a> on github.</p>
<p>As I said, I was working on setting up some basic call list style groups and moderation. A few updates have laid some groundwork for that, and now there&#8217;s full support for simple groups:</p>
<ul><li>A user&#8217;s phone number can belong to one, and only one call list.</li>
<li>A call list can be marked as moderated or unmoderated from the web interface (a django admin site).</li>
<li>On moderated lists, a phone number must be listed as one that can_send in order to broadcast to the list.</li>
<li>On unmoderated lists, anyone can send.</li>
<li>New lists default to unmoderated; new phone numbers default to having send privileges.</li>
</ul><p>If anyone has successfully used the application themselves, I would love to hear about it!</p></div>