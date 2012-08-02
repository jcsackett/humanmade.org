---
kind: article
created_at: January 25, 2010, 9:07 pm
title: Writing Like A Programmer
---

<div><p>I fancy myself a writer. Not, mind you, a <em>good</em> one. Just a passable one.</p>
<p>I am, however, definitively a programmer. This means that I like things like version control, scriptable or programmable tools, and open, easily interchangeable formats.</p>
<p>Currently, when I write things I write them in RTF or in ASCII with Markdown. I <em>really</em> like Markdown. I used to like RTF, until I realized that it has no really standard implementation. So I have resolved to move my writing away from RTF and into Markdown only.</p>
<p>So, ideally, here&#8217;s my writing setup:</p>
<ul><li>Any writing project is a git repository.</li>
<li>All source files for the project are written in Markdown</li>
<li>When a project is finished, an HTML version is produced using the python implementation of Markdown</li>
<li>Additionally, when a project is finished, a PDF version is created with wkhtml2pdf</li>
<li>Optionally, if I want to get designery, output files include some nice CSS, injected in either through a hack or some sort of nice templating tool (Jinja, anyone?).</li>
</ul><p>It seems like a nice idea. Of course, the problem with it is that I have a bunch of stuff <strong>not</strong> produced in this fashion, and I need to convert it (mostly because I&#8217;m slightly OCD about having all my stuff in a similar state, but that is neither here nor there). Aaron Swartz has a nice tool called html2text, which works <em>reasonably</em> well as part of an RTF to HTML to Markdown conversion flow. The only problem now is that the Markdown produced doesn&#8217;t return to an entirely accurate final format.</p>
<p>I&#8217;ll continue on here about my experiments in this vein. In the meantime, other writers reading this: what is your setup, ideal or otherwise?</p></div>