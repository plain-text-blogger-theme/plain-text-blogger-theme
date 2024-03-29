# plain-text-blogger-theme

"Once posted, can't be deleted" blogging platform

## Live example

See [my blog](https://ykonno.blogspot.com/?m=0).

## Description

By using Blogger's ["post using email"
feature](https://support.google.com/blogger/answer/154172), and by discarding
your Blogger (i.e., Google) password, you can create a blog where you can post
but can't edit or delete posts.

[Perfectionists](https://en.wikipedia.org/wiki/Perfectionism_(psychology)) (or
atelophobes) need such a blogging system to grow their blogs because they feel
old posts are "incomplete" or "embarrassing" and are tempted to delete them.

Blogger does not appear to have plans to end its service or delete inactive
blogs.  Theoretically, my blog should continue to be accessible after my death.

## The theme

This repository contains [one Blogger theme](theme.xml).  You can apply it to
your blog by uploading it in Blogger > Theme > Restore.

It is minimalist.  No title or date is displayed.  Text is in a monospaced font
and is not supposed to use decorations, hyperlinks, images, or even non-ASCII
characters.

Where I can use decorations, I become obsessed with displaying mathematical
formulas nicely; I start using HTML tags or Unicode characters, and finally
introduce MathJax, and I can't concentrate on writing.  Therefore I need such a
theme.

However, due to Blogger's limitations, it is impossible to remove HTML tags or
non-ASCII characters on the server side.  I do not want to complicate the blog's
HTML source by adding more JavaScript.  So I decided to achieve that by
enforcing my own rule of emailing in ASCII plain text.

## Alternatives

### WordPress

Such a system is not possible with WordPress because there is no "once you sign
up, you can't cancel" hosting.  In WP, however, you can create a "post-only"
user role using the [User Role
Editor](https://wordpress.org/plugins/user-role-editor/) plugin.

### Pastebin.com + Mastodon

Another way is to publish your posts as anonymous pastes on
[Pastebin.com](https://pastebin.com/).  However, Pastebin has stated that [it
may delete inactive pastes](https://pastebin.com/faq#18), and there is no way to
get a list of your anonymous pastes.

You can create a post-only Mastodon by connecting your account to
[Buffer](https://buffer.com/) and discarding your password.

It is possible to create a Mastodon where you toot your Pastebin links.
However, there are concerns about Buffer's persistence and the risk of you
recreating a Mastodon that excludes links to posts that are inconvenient for
you.

### Wikiversity

[English Wikiversity](https://en.wikiversity.org/) allows
[blogging](https://en.wikiversity.org/wiki/Help:Blog) under user pages.
However, on the Wikimedia projects, you can edit your pages (including blanking
them), and you can ask the administrators to delete them.  However, it may serve
as a backup in case Blogger shuts down.  I have created
[one](https://en.wikiversity.org/wiki/User:Yuuki_Konno_(mathematician)/Blog)
myself.
