---
layout: post
title:  "Jekyll setup"
date:   2015-06-07 

---
I wanted to start practicing documenting everything as I learn. So I set up my git hub account to put all of the app development while following the book. Then I also wanted to document challenges I faced, what I did to fix it and all so, a friend of mine suggested me using [Jekyll]([1]) for that purpose. I am new to blogging so I thought to use Jekyll for now. It is an awesome tool and meets the need of a beginner. I followed the instructions in the official [Jekyll site]([1]) and set it up. It was quite a process but it helped me learn about brew ( I am a Mac user), brew doctor, brew update, brew upgrade, chown, sudo etc.

To set up Jekyll, also stated in the site, there are certain system requirements. One of them is Ruby. Now Mac comes with a version of Ruby built into it. I had it too. But I wasn't able to `gem install jekyll` because I did not have permission to write to it. I could have bypassed it just by using chown (change ownership) command but I thought to leave the mac preinstalled Ruby alone. So I `brew install Ruby`. Once I got the Ruby going, I used brew doctor to fix all the warnings and errors. The warnings mostly had to do with not having the right permission. Once all the warnings were taken care, I was able to `jekyll new myblog` and begin writing my blogs.

[1] http://jekyllrb.com/