---
kind: article
created_at: August 6, 2009, 5:58 pm
title: Hacking Django to use Emails as Username
---

<div><p>There&#8217;s a fair number of times you want to use email as a login when you&#8217;re designing a site as opposed to say, a username.</p>
<p>In django, you can get partway there by setting up a custom auth backend, say as shown <a href="http://www.djangosnippets.org/snippets/74/">here</a>.</p>
<p>But that only goes so far.</p>
<p>The admin app (blessed though it may be) has its own ideas about usernames and authentication.</p>
<p>To deal with that, your best bet is subclassing the admin stuff and reregistering, comme ca:</p>
<script src="http://gist.github.com/163579.js"></script><p>Django admin: The handiest thing to beat up ever.</p></div>