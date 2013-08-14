---
layout: post
title: "So you've heard of Vim?"
date: 2013-08-14 18:00
comments: true
categories: [vim, dotfiles]
---

I'm sure the majority of developers out there have heard of Vim. I'm also sure 
that most of you are frightened by it. *No offense*. I suppose you have good 
reasons for that. 

### Let's recreate the first time you encountered vim.. 

{% pullquote %}
You get access to your first remote box and locate the file you want to edit. So
you google how to edit it and you discover this program valled "Vim".
Excited to use this new program you type in vim filename.ext and it opens up
the file and you see the content. "Yay!!" you say to yourself. Then you attempt
to use the mouse to go to where you want to edit and click.. "Hmm.. it's not
working.." then you try to type in some letters to make sure you can at least do
that. click click click.. "That's not working either! what is wrong with this
program!!". Shortly after this frustration you realize that you can use the
arrow keys to move around and after a quick google you can insert text after
clicking 'i'. At this point you can move around and edit files but you're having
a terrible time. {" "THIS EDITOR SUCKS" you say to yourself. "}
{% endpullquote %}

Don't worry, we'e all been there. I would venture to say no one likes Vim the
first time they open it up. 

{% blockquote @jakecraige https://gist.github.com/jakecraige/6236660 %}
Here is my current monster of a .vimrc
{% endblockquote %}


Yikes! That's pretty scary! I agree, when you first lay eyes on this it looks to
be pretty wild. Though it's really not so bad when you start to
look through it. It's only a collection of alias's for different commands
to make life easier. While vim is powerful at it's basic level, adding in plugins 
and custom aliases is where it really starts to shine. *And hey, I've organized
it into folds for easy navigation.*

My Vim Journey
--------------

{% pullquote %}
I had messed around with Vim a few times throughout the years and always
switched back to using a modern text editor like Sublime Text 2. It just seemed
easier, and yeah, it was, but that doesn't mean it was the best solution for me.
About 3 or 4 months ago I read lots of articles and setup a vimrc and began to
actively using vim as my primary text editor. At work I still used Sublime Text
2 so as to not slow me down, and at home I would use Vim and continued to get
better. After a few weeks I felt pretty confident in using it and set it up on
the computer at work as well. {" Slowly but surely I continued to improve until
I didn't really want to use Sublime Text anymore. I actually had more typos in
it from hitting my Vim binds in it. "} It starts to become muscle memory after
awhile and you just can't stop. You just get that itch to hit 'll the time!!
(more on that later) I am constantly updating my vimrc with new things that
would be helpful and have completely changed it multiple times throughout this
experience. At first I was using spf13's vim setup and that was good for awhile
but seemed to run slower than I wanted it to and included things I didn't want
to use so I got rid of it. Now I have a complete custom vimrc (lots stolen from
others) but one that I have put together so it works best for me. It takes time
to get to learn to use Vim but I think it's worth it. 
{% endpullquote %}

Now that I've scared you a bit. Let's get to it!
-------------------------------------------------
First step, open up terminal and type in 'vimtutor'.(minus the quotes). Run
through that tutorial to get a basic understanding of how to move around the
file and edit things. That alone will help you start to see some of it's power.
I haven't used this site, but it seems very similar to vimtutor but a bit more
interactive so you could give it a shot as well 
http://www.openvim.com/tutorial.html.

After that it's time to start setting up a vimrc. 

Ugh. I'll continue this later. If anyone comes upon it before then, these helped
me get started.

-   http://stevelosh.com/blog/2010/09/coming-home-to-vim/
-   http://net.tutsplus.com/articles/general/top-10-pitfalls-when-switching-to-vim/
-   https://github.com/spf13/spf13-vim


