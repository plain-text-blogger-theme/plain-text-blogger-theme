# plain-text-blogger-theme

"Once posted, can't be deleted" blogging platform

## Description

By using Blogger's post-by-email feature and discarding the Blogger (i.e.,
Google) password, you can create a blog where posts cannot be deleted once
published.

I am atelophobic and tempted to delete old posts, so I need such a blogging
system.

This repository contains [one Blogger theme](theme.xml).  A live example is on
[my blog](https://yuukikonnobot.blogspot.com/).

It is minimalist and displays plain text emailed posts as they are.  No date or
title is displayed.  Text is in a monospaced font and is not supposed to use
decorations, hyperlinks, images, or even non-ASCII characters.

Where I can use decorations, I am obsessed with displaying formulas nicely.  I
start using HTML tags, Unicode characters, or finally introducing MathJax, and I
can't concentrate on writing.  Therefore I need such a theme.

However, due to Blogger's limitations, it is impossible to remove HTML tags or
non-ASCII characters on the server side.  I do not want to complicate the blog's
HTML source by adding more JavaScript.  So I will achieve that by enforcing my
own rule of emailing in ASCII plain text.

Blogger does not appear to have plans to end its service or delete inactive
blogs.  Theoretically, my blog should continue to be accessible after my death.
