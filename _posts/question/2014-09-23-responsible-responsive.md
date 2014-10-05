---
layout: question
title:  "Responsible and Responsive"
date:   2014-09-23 12:00:00
author: James Milne
categories:
- question
---

####Responsible and Responsive
It's not just enough to follow the [Latest Standards]({{ "/question/latest-standards" | prepend: site.baseurl }}), making sure a website is managed correctly is hugely important.

Every popular website makes a backup, because they know issues will come.

Even if no one ever tries to attack your website, which thanks to roaming bots, ```(little scripts hackers write that search for random places to attack)```, will happen one day or another, just having your website popular can bring it down. (An explanation of why this works can be found [here](https://www.reddit.com/r/explainlikeimfive/comments/1wne3s/why_do_sites_break_due_to_the_reddit_hug_of_death/)).

So, backups are essential.

####Our Take
Backups aren't enough.

Every version of every site we work on is catalogued and saved, but when you update a website, you replace files that are running.

What if an error happens during an update?

Does that mean part of your website breaks?

We don't think it should mean that, but hosts that rely on systems like cPanel... That's exactly what will happen.

So we use fancy things called *'hooks'*.

Your old website is running normally, you tell it you want to update.

It builds the new website next to the old one, instead of on top of it.

If it builds fine, then it takes down the old one, and everyone will see the new.

Making sure a website always has minimal "down time" is essential, and that is what we call being responsible.

<p><br/><a href="{{ "/contact/" | prepend: site.baseurl }}" class="btn btn-theme">Want to talk to us?</a></p>
