---
layout: post
date:   2016-09-19 18:09:45 -0500
title: Digital Literacy Narrative - Final
---

In 1998, when I was 13 or 14 years old, I created my first email
address: goddessaphrodite84@gURL.com. Yes, probably the most
ridiculous handle anyone has ever heard (I can hear laughing through
time and space), but I was barely a teenager and my friends and I were
obsessed with boys. Embarrassingly, we would also frequent Yahoo!
chatrooms looking for boyfriends overseas. One time I became penpals
with a teenage boy from Liverpool and I swear I spent days thinking of
ways I could insert uniquely American words and spellings into emailed
conversations. For example, elevators instead of lifts and tires
instead of tyres. Such. A. Dork.

![alt text](/dwblog/images/amy1998-2.jpg "Photo of myself circa 1998")

Anyway, this was way before the internet was used for everyday
purposes including communication or as a reliable information source,
and even my parents did not have their own email accounts. It was a
bit like installing Snapchat today: most parents kind of knew what the
internet was, but not really how to use it.

In those days, my hosting, gURL.com, was a lot like a 'zine had a baby
with the World Wide Web. And I say it like that exactly because of how
it appeared and operated: like something made when the term "World
Wide Web" was still widely used. It was difficult to read, loosely
organized, non-responsive, and animated-gif-heavy. But it was an
awesome home for teenage girls trying out the internet for the first
time. Like a teen magazine, gURL.com walked young women through
relationships, style advice, school, entertainment, and female
physiology. However, unlike other teen 'zines, it also gave young
women a place to learn how to create and publish their own web pages.

![alt text](/dwblog/images/gURL_Hompage_2000.PNG "Screenshot of the gURL.com homepage in 2000")

Using their interface, someone with no experience in programming
languages could develop and design a site piece by piece. It was
pretty limited to HTML markup and so I started to learn the basics of
the new language in an effort to build my very own webpage for the
internet. To me, this was the coolest thing in the world, and I
happily gave out my web address to all of my friends. At the time, it
was nothing more than a personal diary, or what we consider these days
a “blog,” but it was my own little space on the web.

The specifics of what my website contained have mostly been lost to
time and memory. However, there are a few bits and pieces that I can
still recall. I remember I had a page that contained creatively
written accounts of dreams I found memorable. Another page had several
poems that I had written, and to this day, I can only remember one
line:

The butcher isn't really butch but everybody's acting.

So strange. There were also -- of course -- some animated gifs
sprinkled throughout the site, a page hit counter and at least one
page that just said "UNDER CONSTRUCTION." Ultimately, I think the idea
was to have some kind of creative outlet in a place that I felt was
safe from parental scrutiny, as well as my own connection to the
potential-filled world that existed outside of my small hometown. My
web pages became a small piece of me in the ocean that is the
internet.

The HTML knowledge was something else that was lost to time. I
remember learning the importance of tags and formatting as I switched
back and forth from the coding interface to the output preview,
watching my pages come to life. Tags like \<b> and \<i> were used
extensively as well as some tags pointing to other URLs, but honestly,
I don't recall much beyond that. gURL.com offered as a resource some
templates, tutorials, and today what we would call "spec" on HTML
markup that really helped me to understand how to accomplish what I
was trying to do on each page.  And ultimately, I remember being proud
of what I had done.

About six months later, the summer before my freshman year of high
school, I met my first real boyfriend. Spending all my time with him,
I allowed my interest in creating web pages to languish and my hard
work became lost to the void of the internet. I no longer used my
markup skills and eventually, all but the above was forgotten.
However, I know that this small experience with markup as a teenager
was certainly one of the most helpful experiences I could have had as
I came into my first web development class at Illinois Tech.

Now, as an adult, I’m am relearning what it feels like to write for
the internet and build a space for myself among the billions of web
pages that exist. My latest attempt has me using Jekyll, a static site
generator that has allowed me to build a blog using only the simplest
of markdown text. While HTML still has immense usefulness (I built my
professional website using it with CSS last semester), markdown with
Jekyll is faster and more intuitive when creating a simple layout like
a blog.

For example, instead of using heading tags, I just place a hash mark
or two in front of my heading text.  And instead of paragraph tags, I
can simply write my copy. The text is automatically generated into
neatly formatted paragraphs.  Bold and italic text is similarly
intuitive with simple underscore or star characters surrounding the
words I want to emphasize.  However, probably my favorite thing to do
with markdown is make a list.  All I have to do to create a bulleted
or numbered list is to list my items as I normally would in any other
software using a dash or numbers!  It's ridiculously easy and I love
it.

This functionality is great... if you're writing a blog.  Other needs
may require other tools besides Jekyll.  And while I can honestly say
that this new experience resembles my old experiences with gURL.com in
a couple of ways -- namely the text input interface and general layout
of my current blog made with Jekyll -- there are several other things
that I struggled with and am still learning.

To date, one of the biggest struggles in getting Jekyll to work was
merely using my Terminal in Linux to complete the installation of Ruby
on Rails. I encountered a hiccup when I accidentally installed RVM
over rbenv - a big no-no.  After removing rbenv, I continued with the
gem and bundle installation process, which seemed to go a bit more
smoothly.

![alt text](/dwblog/images/Yay_Rails.jpg "Yay! I did it!")

Once that was done, I was able to install the specific Jekyll gem that
I would use to make my blog communicate with github pages, and then
created a new repository on github for my new blog for this class
under “dwblog.” Writing new posts from there has been relatively easy,
as all it required was reviewing the sample post the Jekyll dev team
built, copying it with my own info and text within gedit, and pushing
it to github.

Although, as I began playing with the appearance of my site, including
adding relevant links and emails and such, I encountered one more
problem that vexed me for at least an hour.  Suddenly, my .scss file
stopped compiling and rendering my - admittedly default - styles.
Boo!  My process to bugfix was research, trial, and error.  I'd look
up the spec, look up examples, try a "solution," see no results, and
then try again.  After a good hour, I was exhausted and ready to do
something else, so I reached out to my classmates and Professor
Stolley for help.  Turns out, Professor Stolley, the professional that
he is, spotted my mistake right away: an SSL error caused by my URL
not containing the "s" in my "https://".  D'oh!

Everything seems to work well now that I've fixed that mistake.  I
guess my only real task left is to implement a theme to my blog.

Preliminary research has shown that I will need to do quite a bit of
copying, deleting, downloading, pushing, and pulling of files, among
probably other things. The prospect of what seems like should be a
simple task has me a little worried, but I’m sure it will all look
great in the end.
