---
layout: post
title:  "Debugging Tip 001"
date:   2018-10-26 06:31:18 -0700
categories: sports
---

Yesterday I learned a few things on debugging in general. When I say "debugging" here, I mean "problem solving" in life, tech and so forth. 

Couple of issues that I faced yesterday.

Coworker wanted to run one of app that had JWT token based authentication on her local machine and kept getting JWT error. I spent big chunk of time looking into code base. But the problem was not even in the code base. It was that her machine's time was off by a few minutes; it wasn't synced with time server. JWT was complaining that JWT timestamp is in future. 

What I learned. 

- Never neglect the possibility of source of problem being somewhere else. 

For last week or so, I've been waking up with horrible headaches. I am planning to see sleep specialist for this matter soon, but in the meanwhile I decided to wear a fanny pack with tennis ball inside on my back so that it forces me to sleep on the side at all times. And it helped a little but still headache. So I decided to try a different pillow. Then I had a lot better sleep without headache. And the funny thing was that my old pillow was the one that actually helped me get rid of headache when I was sleeping on my back. So I just "assumed" that the pillow can't possibly be part of the problem. But when I started sleeping on my side, the pillow turned into a villan. 

- Never assume that what worked before would continue to work as before. 
