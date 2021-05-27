---
title: "Did You Read the Logs?"
date: 2021-05-26T16:53:24-06:00
draft: false
---

I recently started at a new company and began setting up my dev environment. During the process, I got stuck and asked for help. I asked the coworker giving me a hand what sorts of things I could do to improve and he had a couple suggestions that I wanted to type out here so I hopefully never forget to do them when they'll invariably need to be applied.
 
## "Did You Read the Logs?"

Sorry I spoiled this in the post title. Whoops! Anyway, you might think it's obvious and silly and you're right. But it's important.

Recently, I was redploying an app to Heroku and it broke instantly. Heroku advises you to read the logs from that error screen everyone who has ever used Heroku has seen before, but up to this point it had never occured to me that the logs weren't just programming-ese that would confuse my feeble mind. I put on my big boy pants and took a look, and y'know what? That log told me, in what I thought were pretty clear terms, that I had an issue with an environmental variable. I popped open the hood, put the missing ENV into place, tried it again, and it worked!

Generations of programmers who came before put lots of smart tools in place to save your bacon. Take advantage of them!

## "Can You Recreate the Error?"

It's only polite that you do your due diligence so that you can a. ask for help in a productive way, laying out what you've already attempted and b. make sure that yes, it is ***actually*** broken, and no, I did not just pull you away from what you were working on to discuss something that is now mysteriously working just fine.

Now, for the real challenge- can I remember to do these things before asking for help next time?