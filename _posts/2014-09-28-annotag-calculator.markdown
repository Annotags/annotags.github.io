---
layout: post
title: Annotag Calculator 1.0
author: Jon Reeve
---

Following [my initial spec for Annotags](/projects/annotags/about.html), a decentralized literary annotation protocol, I've just posted [the first rough version of a webapp](/projects/annotags/) designed to encode and decode the tags. Now you can annotweet books, plays, poems, and other texts with shortened ISBNs, thus saving precious microblogging characters.

For example, my first annotweet using this system annotates the Folger Library Shakespeare edition of *Hamlet*, in the famous soliloquy that appears on page 127, at line 64. The ISBN-10 for that book, as Amazon tells me, is `074347712X`. I put this in the annotag calculator like so:

![Annotag Calculator](/images/annotags/annotag-calc.png)

This generated the annotag `#iEtVGa:p127l64`. I copied and pasted this into my annotweet like this:

![Annotweet](/images/annotags/first-annotweet.png)

Because Twitter doesn't like colons in hashtags, only the first part of the annotag is highlighted as a hashtag. This works to keep more specific annotags locatable, since it connects you to the other annotweets from the book, but isn't so specific that it limits you to the line you're annotagging. Eventually, I'll write an aggregator that can find annotags and linkify the page numbers and lines, where possible, to electronic versions of those lines and pages.

Happy annotweeting! If your annotweet has a few extra characters left at the end, give me a shoutout at @j0_0n.
