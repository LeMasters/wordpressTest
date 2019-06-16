---
ID: 234
post_title: 'tutorial: digital research methods'
author: Garrison
post_excerpt: ""
layout: post
permalink: >
  https://www.colophon.org/digital-research-methods-i-o-tutorial/
published: true
post_date: 2019-02-23 15:11:01
---
<!-- wp:heading {"level":3} -->
<h3>context</h3>
<!-- /wp:heading -->

<!-- wp:paragraph {"backgroundColor":"primary"} -->
<p class="has-background has-primary-background-color">In my courses, I make frequent use of tutorials, both text-based and video.  With few exceptions, I make them all myself:  Most of the material available online is too poorly structured, badly delivered, outdated, or just plain wrong to make use of it in a college classroom.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"backgroundColor":"primary"} -->
<p class="has-background has-primary-background-color">The copy included below is from a Digital Research Methods course blog, dated Feb 2, 2018.  This tutorial in particular is a Jupyter Notebook page, and is available to review by following the link at the very bottom of this page.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"backgroundColor":"primary"} -->
<p class="has-background has-primary-background-color">Jupyter<strong> </strong>Notebook is a modern marvel:  A <em>live</em>, browser-based implementation of a self-contained Python environment built especially for data scientists.  It is a terrific tool, but be forewarned:  Clicking the link sets in motion a series of servers across the cloud.  While subsequent launches are fast, <em>the first launch will take about 60 seconds</em>. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"align":"right"} -->
<p style="text-align:right">Read more about <a href="https://jupyter.org">Jupyter Notebook</a>.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>Code is Hard</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>I'm sure that some of you feel overwhelmed as you work to master these weird, radically new ideas.  It is OK to feel that way -- just keep chipping away at these fundamentals:  Pretty soon some of it will start to feel familiar.</p>
<!-- /wp:paragraph -->

<!-- wp:image {"align":"left","width":160,"height":439} -->
<div class="wp-block-image"><figure class="alignleft is-resized"><img src="https://www.digitalresearch.online/wp-content/uploads/2018/02/Sir_Hiss-1.gif" alt="The Slippery Sir Hiss" width="160" height="439"/><figcaption>The Slippery Sir Hiss.  Python genus <em>pythonidae</em>.</figcaption></figure></div>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Not that it will <em>ever</em> feel like home:  The fact is that these technologies are evolving too quickly for that.  (This is fast becoming an issue in software development among the coder rank and file).</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>But <em>fluency</em> is not your goal here:  I'll never ask you to write code from memory or invent code on-the-spot:  You will <em>always</em> have access to the references and resources you've come to trust; you'll always be able to lean on others in order to find your answers.  This is a class about <em>research</em>, not about <em>programming</em>.  In the long-term, I do think that the code we write has the potential to open up, in each of us, <em>new vectors of reason and novel forms of critique</em>.  But for now, refuse to let yourself be intimidated by it.   </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>The link below will take you to a tutorial that picks up on what we did not finish on Thursday.  It does a reasonable job of explaining how to open and read data files in Jupyter.  I'll try to post a few more of these this afternoon (Sunday, 11 February). </p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":4} -->
<h4>my<b>binder</b>.org</h4>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>The link itself is actually very interesting to us:  I'm using a Jupyter notebook hosting service called "myBinder."  It's new to me, and still in Beta, so there are some kinks to work out I'm sure, but it makes it so very easy to share your work with your peers as an interactive, live notebook.  I just put my .ipynb file on Github and tell Binder to host. </p>
<!-- /wp:paragraph -->

<!-- wp:ugb/blockquote {"quotationMark":"square-fat","quotationSize":0,"design":"huge"} -->
<blockquote class="wp-block-ugb-blockquote ugb-blockquote ugb-blockquote--v2 ugb--background-opacity-5 ugb-blockquote--design-huge ugb-blockquote--small-quote"><div class="ugb-content-wrapper"><svg viewbox="0 0 50 50" xmlns="http://www.w3.org/2000/svg" style="fill:;width:0;height:0"><path d="M12.5 9.2H19c1.1 0 1.8.2 2.3.7.5.5.7 1.2.7 2.3v3.4c0 1.1-.2 1.8-.7 2.3-.5.5-1.2.7-2.3.7h-5.8c-.7 0-1.3.2-1.7.6-.4.4-.6 1-.6 1.7v1.3H20c1.1 0 1.8.2 2.3.7.5.5.7 1.2.7 2.3v12.5c0 1.1-.2 1.8-.7 2.3-.5.5-1.2.7-2.3.7H3c-1.1 0-1.8-.2-2.3-.7-.5-.4-.7-1.2-.7-2.2V21.9c0-4.3 1.1-7.4 3.4-9.6 2.3-2 5.3-3.1 9.1-3.1zm26.9 0h6.5c1.1 0 1.8.2 2.3.7.5.5.7 1.2.7 2.3v3.4c0 1.1-.2 1.8-.7 2.3-.5.5-1.2.7-2.3.7h-5.8c-.7 0-1.3.2-1.7.6-.4.4-.6 1-.6 1.7v1.3H47c1.1 0 1.8.2 2.3.7.5.5.7 1.2.7 2.3v12.5c0 1.1-.2 1.8-.7 2.3-.5.5-1.2.7-2.3.7H30c-1.1 0-1.8-.2-2.3-.7-.5-.5-.7-1.2-.7-2.3V21.9c0-4.3 1.1-7.4 3.4-9.6 2.2-2 5.2-3.1 9-3.1z"></path></svg><p class="ugb-blockquote__text" style="color:">mybinder.org is powered by a complex series of Docker scripts!</p></div></blockquote>
<!-- /wp:ugb/blockquote -->

<!-- wp:paragraph -->
<p>Bonus "It's a Small World" detail:  Guess what happens in the interim?  Right:  myBinder fires up Docker, and builds your notebook into a custom Docker container that is then launched on demand.  See?  It all comes full circle! </p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":4} -->
<h4>tutorial</h4>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Work through the tutorial to learn the basics of loading a data file.  Sometimes it will seem overly complicated -- but don't be discouraged:  Once we get these first principles out of the way, <em>the rest will come much easier</em>.  And we can actually focus on the research and our arguments themselves, rather than on Python. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><a href="https://mybinder.org/v2/gh/LeMasters/Jupyter_Tutyr/master?filepath=IO_Tutorial_One.ipynb" target="_blank" rel="noreferrer noopener" aria-label="Launch I/O Tutorial Part 1 (opens in a new tab)">Launch I/O Tutorial Part 1</a></p>
<!-- /wp:paragraph -->