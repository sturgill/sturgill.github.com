---
layout: post
title: "Why Automate View Testing?"
description: ""
category: 
tags: []
---
{% include JB/setup %}

Before getting into the meat of the article, let me define the scope of my argument.
For the purposes of this post, I am only interested in dealing with web applications.
My specific expertise is in the Rails framework, but I think my concerns are framework 
and language agnostic.

Alright, so with an understanding that I'm only talking about web development let me just
put it out there: I don't see the value of writing automated tests for view logic.

Allow me to explain:

Let's say that we want a given endpoint to display a given object.  So we write a test
that ensures that the output of the view includes that object.  If your only business
requirement is that said object happens to be in the returned source code, an automated test
would provide value.  But I've never worked in an environment whose only concern was that 
an object was delivered to a page.

With the exception of API endpoints that render in a format like JSON or XML, how an
object renders on a given page (e.g., its styling) is almost as important as whether or
not that object appears on the page.  The presence of the object is a necessary but insufficient
requirement.

As long as different browsers have different rendering engines, you will still need
to manually load up a given endpoint in as many browsers as you support to make sure that
things *look* they way you want, not just that all information is *present*.

Everything except the most trivial changes to your views will require manual testing in a 
variety of browsers.  And if you have to fire up N browsers to check that something looks 
right, how do you come out ahead by writing an automated test?

Now if someone can point me to a test that can automagically tell me that IE hasn't destroyed
my layout, I'd love to be wrong!...