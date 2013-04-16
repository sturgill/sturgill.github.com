---
layout: post
title: "Getting Stuff Done"
description: ""
category: 
tags: []
---
{% include JB/setup %}

Recently [one of my posts]({% post_url 2013-04-15-tests-are-overhyped %}) made a bit of a stir on 
[Hacker News](https://news.ycombinator.com/item?id=5554600). I really enjoyed the conversation that was
had, and it got me thinking more about the whole development cycle and what we do as managers and
development teams.  I've worn just about every hat you can imagine in the web development world, from a junior dev
on a larger team (i.e., pure code monkey) to being the technical co-founder of [Goalee](http://www.goalee.com)
(i.e., if anything breaks it's my neck on the line).

So, for both of you that care, here's what I have learned:

- Everything else held constant, faster deploys are preferable to delayed releases
- Everything else held constant, it's preferable to spend as little money as possible

Mind blowing, I know.  But as someone who takes great pride in the code that I write, it can be easy to
get so wrapped up in the purity of writing code that you lose sight of what the code is meant to do.
And as much as it might pain you to admit it, and this is especially true if you've taken outside investment, the
purpose of your code is to make money.

Every tool we use to write code should be looked at in this light.  If not by the junior level grunt, then
at least by those who profess to be managers.  The purpose of management isn't to process TPS reports, it's
to increase efficiency.  Whether that's breaking down barriers, dealing with investors, overseeing deployment
schedules, or analyzing development procedures and requirements, successful managers are those that
best help their development teams improve efficiency.

Let's take the Rails framework as an example.  I love Rails in all its omakase goodness.  And why do I
use Rails in most of my web projects?  Because it improves efficiency.  I'm not a homer; I recognize
there are tradeoffs with a framework like Rails.  But by and large it does a great job at helping me focus
on those parts of our software that make us different than everyone else.  It helps me do more with less.

[I wrote about tests]({% post_url 2013-04-15-tests-are-overhyped %}) and I'm not interested in going
down that rabbit hole again this week, but my views on testing might make more sense when understood
in this light.  I don't hate tests, and I don't hate TDD (and contrary to some in the Twitterverse, I
do understand the difference between the two).  But I would argue that the overhead incurred from TDD
might decrease efficiency in the early stages of development when you have absolutely no freaking clue
what your product/service will actually be when it grows up.  It doesn't bother me if other people
have a different cost/benefit analysis, I just don't feel beholden to the testing paradigm if I don't
think it is likely to be a positive NPV endeavor.

Why do people rave about the morning standup?  Because it has helped breakdown barriers and improve
the ability to get things done.  Is the morning standup the only way to do that?  No, and if you have
a more efficient way of doing business then you should adjust accordingly.  I honestly don't love 
morning standups and have rarely used them as prescribed.  This might get me flamed (again), but I've
found other ways that work better for me and my teams to overcome the same barriers that the standup is
meant to address.  I have a near irrational hatred towards organized meetings (mostly as a result of being
in so many that are absolute time-sinks).  I get the morning standup, I love you for doing it, but I don't
use it.  And I'm still going to sleep well tonight...

At the end of the day, all I really care about is getting stuff done.  From the services I use (from Mixpanel
to Geckoboard to Lighthouse to GitHub) to the development practices I enforce (peer-reviewed code and 
[problem ownership]({% post_url 2013-04-11-why-i-code %})) - what matters is getting
the best return on our investment.  For example, I *really* want to like GitHub Issues.  I *really* want
to be able use it as our team's main ticketing agent for our private repo.  But Lighthouse is still more
effective for us because I can't attach arbitrary files to GitHub.  They just recently introduced image
attachments, which is a great first step, but I need to be able to attach specs (like PSDs) to tickets as well.  I
*could* use Dropbox with links or some other hackery, or I could just use Lighthouse and be done with it.
For now, I've determined that Lighthouse is more efficient for us, but if GitHub ever allows for
arbitrary file attachment I'll make the shift in a heartbeat.

There are some general industry best practices that are likely to help me be more efficient,
but I don't hold any of them as sacrosanct.  Every team is different.  Every
manager is different.  And as we're all working on different projects, and we all have different abilities,
it would seem logical that the optimal way for our disparate groups to achieve maximum efficiency would
be diverse.

This doesn't mean that I advocate "different strokes for different folks."  Being different for
the sake of being different is probably less intelligent than just going with the crowd.  This is
simply an open admission that the optimal way of solving problems on my team is likely to be different than the
optimal way of solving problems on your team.

Tools and methods help me get what I want - and I use them in order to get the highest return on my time
and money as possible.  I use them to get stuff done.