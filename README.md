# plain-text-blogger-theme

"Once posted, can't be deleted" blogging platform

## Description

By using Blogger's post-by-email feature and discarding the Blogger (i.e.,
Google) password, you can create a blog where posts cannot be deleted once
published.

I need such a blogging system because I am atelophobic and tempted to delete old
posts.

This repository contains [a single Blogger theme](theme.xml).  A live example is
on [my blog](https://yuukikonnobot.blogspot.com/).

It is for minimalists, displaying posts emailed in plain text as they are.  No
date or post title is displayed.  Text is in a monospaced font and is not
supposed to use any decorations, hyperlinks, images, or even non-ASCII
characters.

Where I can use decorations, I am obsessed with displaying mathematical formulas
nicely, starting to use HTML tags or Unicode characters, and finally introducing
MathJax or KaTeX, and I cannot concentrate on writing.  This is why I need such
a theme.

However, due to Blogger's limitations, it is impossible to remove HTML tags or
non-ASCII characters on the server side, and writing JavaScript to replace them
is cumbersome, so these are achieved by enforcing my own rule of emailing in
ASCII plain text.

Blogger does not appear to have any plans to end its service or delete inactive
blogs.  Theoretically, my blog should continue to be accessible after my death.
