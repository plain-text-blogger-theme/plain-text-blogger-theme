# plain-text-blogger-theme

A "once posted, can't be deleted" blogging platform

## Description

Based on Blogger's post-by-email feature, by publishing posts via a secret
address and discarding the Blogger (i.e. Google) password, it is possible to
create a blog where posts cannot be deleted once published.

I am atelophobic and find myself editing posts over and over again, or wanting
to delete them later, making it impossible to build up many posts.  This is why
I need such a blogging system.

This repository contains [a single Blogger theme](theme.xml).  This is for
minimalists, displaying posts emailed in plain text as they are.  No date or
post title is displayed.  Text is in a monospaced font and is not supposed to
use any decorations, hyperlinks, images, or even non-ASCII characters.

Where I can use decorations, I am obsessed with displaying mathematical formulas
nicely, starting to use HTML tags or Unicode characters, and finally introducing
MathJax or KaTeX, and I cannot concentrate on writing.  This is why I need such
a theme.

However, due to Blogger's limitations, it is impossible to remove HTML tags or
non-ASCII characters on the server side, and writing JavaScript to replace them
is cumbersome, so these are achieved by enforcing my own rule of emailing in
ASCII plain text.

A live example can be found on [my blog](https://yuukikonnobot.blogspot.com/).

Blogger does not appear to have any plans to end its service or delete inactive
blogs.  Theoretically, my blog should continue to be accessible after my death.
