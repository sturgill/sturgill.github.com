---
layout: post
title: "Tests Are Overhyped"
description: ""
category: 
tags: []
---
{% include JB/setup %}

Let me lead off by saying that I don't think tests are bad.  I really don't.  But here's the thing:
I don't care what your test-code ratios are.  You know what the best test-code ratio is? Whatever you
need to make sure your crap works while still getting product out the door.

I can't remember the last startup I read about that didn't claim to have a strong TDD core.  I'm a little
weary of reading things like "If you don't RSpec your Cucumbers then don't bother applying here, because
this startup is only for testing All-Starz."

I want to reiterate that I believe that the optimal amount of testing > 0.  That said, I think
those who stand the most to gain by excessive testing are big house development shops that can keep
billing their clients on an hourly basis.

Almost every place I've actually spoken with on a personal basis feels pretty much the same as I do.
They'll list on a job opening how committed they are to tests, and when you call them on it they
just start to mumble in the background.  I think this might just be a sign of my getting old and
cranky, but when the issue of testing comes up I like to hit it dead on.  Here's a representative
example of an interview I've had:

**Interviewer:** "We're big into TDD over here and don't create any new features without going through
the red-green cycle.  What are your thoughts on tests and how comfortable are you with that
environment?"

**Me:** "Honestly?  I think tests are highly over-hyped in the tools that we use to get products
out the door.  I believe in testing what needs to be tested, and nothing more.  Because in business,
people buy products, not tests.  Writing tests for the sake of writing tests is a waste of my time
and talents."

Writing tests is not costless.  It takes a lot of time to write tests, and if any portion of your site
changes (pivot, any one?) you're now in a position of having to rewrite large portions of your tests.
And the larger the pivot, the more useless your old testing becomes.

We wrote the first scoring algorithm at [Goalee](http://www.goalee.com) based on the red-green light.
Within a couple of weeks we made our first algorithmic change, and made several quick fix releases to
update the scoring methods in the following weeks.  By the end of the month, a whole section of our
testing suite was almost completely worthless.  In a world where cash is king, I wouldn't mind having
those dollars back.

So in the world of tech entrepreneurship, where being first-to-market is one of the few competitive
advantages you can hope for, where the world moves fast and you're expected to be nimble, and where
all that matters is how much money you have in the bank, be smart about where, when, and what you test.

**UPDATE:** Check out the additional discussion had on [Hacker News](https://news.ycombinator.com/item?id=5554600).