---
kind: article
created_at: September 2, 2008, 3:39 pm
title: Text Clustering and Latent Semantic Analysis
---

<div><p><img src="" /></p>
<p>Work involves a lot of natural language processing and information retrieval. Or at least, it&#8217;s <i>supposed to</i>. With that in mind, I thought it would be worthwhile to do a bit of research/relearning on a major NLP technique, Latent Semantic Analysis (LSA).</p>
<p>The basic idea of LSA is term clustering as a means of comparing documents. It&#8217;s pretty involved mathematics wise, and I haven&#8217;t yet grasped all the details. But, at its simplest it&#8217;s just a form of term/document clustering.</p>
<p>It starts with a bunch of documents, which are stoplisted and stemmed so that you&#8217;re left with the most important stuff. Basically &#8220;hate&#8221; and &#8220;hating&#8221; become the same token and things like &#8220;the&#8221; and &#8220;is&#8221; are removed. A matrix for the documents and their terms is then created, e.g.&#160;:<br /><br />D1 &#8220;I hate analysis.&#8221;<br />D2 &#8220;I hate, HATE cheese burgers.&#8221;</p>
<p>I     hate     analysis     cheese     burgers</p>
<p>D1      1    1          1              0             0</p>
<p>D2      1    2          0              1             1</p>
<p><img src="" /></p>
<p><img src="" /></p>
<p><img src="" /></p>
<p>From there you can start clustering data. A high occurrence of certain words indicates a likely semantic meaning.</p>
<p>And then you run up into the linear algebra. Since I barely remember what an eigenvector is, I&#8217;m still working on that part. I&#8217;ll continue blathering on this when and if I&#8217;ve got that sorted.</p>
<p>(<b>Argh: </b>that table up there is sort of unreadable, as tumblr has no real support for, well, tables. Sorry about that. If you&#8217;ve got a solution, post in the comments.)</p></div>
