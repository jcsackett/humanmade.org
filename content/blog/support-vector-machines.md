---
kind: article
created_at: September 2, 2008, 5:22 pm
title: Support Vector Machines
---

<div><p>This is old hat to anyone doing machine learning. Once upon a time I had a pretty good grasp on it myself.</p>
<p>The trivial idea is that given two vectors representing two classes of <i>something</i>, you can divide the n-space that those two vectors are in roughly equally between them. Any new class of that <i>something</i> can then be identified by which side of that divider it falls into.</p>
<p>The vectors in question are numerical representations of various bits of data. Since everything I work with right now that would require this sort of thing is text, let&#8217;s talk about text. Sample attributes might be occurences of foreign words, occurences of particular grammatical errors, difficulty of the text, length of the text, number of really hard words in the text, and so on. As you add samples in your initial group you can find clusters which you divide on and can have more than one divider as long as anything on either side of the dividier is about the same distance from the divider.</p>
<p>There is, as always, a lot of math going on in that, and if you were to write your own SVM you would probably need to understand it all. Generally though, you should probably just grab someone else&#8217;s shot at it, but it helps to have some idea of what&#8217;s going on under the hood.</p></div>