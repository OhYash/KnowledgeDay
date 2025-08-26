---
published: true
layout: post
date: '2021-12-10 06:00:00 +0530'
title: Your own version of Knowledge•Day
img: fifty_hero.jpg
fig-caption: 50th issue
tags: [Technology]
issue: 50
description: >-
  The 50th issue! Such a special moment! I waana give you all of my website to play with.
---

Hello there,  

How are you doing?  
Great! I hope!  

**19.** That's the number of months it took for this newsletter to hit the half-century mark.  
Welcome to the **50th issue** of the Knowledge•Day newsletter.  

I wanna say thank you for being along this journey. I've learned a ton, I've shared tons, and I've experienced tons I wouldn't have if it was not for this hustle.  
I absolutely read all the feedback messages I get for my emails. Gotta say your love is what helps me keep this running string whenever I feel helpless with this newsletter's future. I'm sorry if I've failed to reply back to your feedback. That's bound to change. I'll try to respond to every feedback I get.  

Speaking of feedback, I'm happy to share we're moving away from using Google forms for the issue responses. The Like/Dislike buttons at the bottom of the email will take you to a dedicated issue response page on the website now.  

Much better experience it is. Try this through the like/dislike at the bottom of this issue.!  

> You're reading on the website  
No problem with that, but it's better if I do the hardwork of delivering it to you when a new awesome post is made. Right in your inbox.  
Just hit [this link](https://knowledgeday.in/signup/?utm_source=kdweb_issue50&utm_medium=blog_intro) and you won't have to come check back on the website in the future.  

Being the 50<sup>th</sup>, this issue should be a little different from the usual, right?  
Thought so. Today, instead of picking up a topic to talk about, I have prepared what's called a **Tutorial** for you.  

------
------

# Your personal Knowledge•Day
I mean, in literally any sense: Design, text, post sequence, logo, link, whatever you'd fancy.  

Yes, it's possible. Knowledge•Day's website is **open source** - meaning all of the code, text, and images that go into the website are available for you and everyone else to explore and play with.  
This has always been the case, and today I'm going to show you how to use it for your own learning.  
Today, we will run the entire website on our personal system.  

Understandably, this post is somewhat technical and can be intimidating to some people.  
However, if you have access to a laptop or a desktop right now... I'd still recommend you to stick along and try to follow this parallelly.  

## Is it WordPress or Jekyll?
**WordPress** is a vastly more common "software" (It's a Content Management System or CMS) for setting up most kinds of websites.  
To put a number, WordPress powers roughly over **40%** of all websites on the internet. Talk about blogging, and the score jumps to a whopping **97%** for WordPress.  
**Jekyll** is a static site builder that simply generates a website using a provided design template. That's mostly it! It's not a CMS like WordPress and doesn't support most of the features of WordPress (less than a quarter in total, in fact).  
But that means it's simpler to work with and is much faster. So fast, in fact, that often browsing the website feels like it's all pre-downloaded.

Knowledge•Day uses Jekyll as it's web-engine behind the website. Jekyll, just like the website, is also open-source.  
You can set up and run a Jekyll website on your system. Without requiring any active internet access once it's all set-up. You will be running the entire site of Knowledge•Day. Just follow the steps:  

## Install Ruby
Jekyll is written using a programming language called **Ruby**. For you, that means simply installing the Ruby language to your system.  

If you're running Ubuntu or Debian-based Operating System (Linux Mint, Zorin, Deepin, Kali, ...), type the following command in your terminal.
![install packages]({{site.baseurl}}/assets/img/install_pkgs.png)

Don't use [Ubuntu](https://jekyllrb.com/docs/installation/ubuntu/)? No problem, it is equally easy to install in [Windows](https://jekyllrb.com/docs/installation/windows/), [mac OS](https://jekyllrb.com/docs/installation/macos/), and [other linux](https://jekyllrb.com/docs/installation/other-linux/) based operating systems.  

## Install Jekyll
To run a Jekyll-based website, we, of course, need Jekyll installed.  
Before installing Jekyll, check if `ruby gems` was installed properly in the last step. The following command will tell you the gem version.
![Check gem version]({{site.baseurl}}/assets/img/gem_ver.png)
_You're gem version number doesn't have to be the same._
Got an error instead of version number? Check the installation steps from the link for your OS in the previous section for any additional gems-related setup.  

Time to install Jekyll
![Check gem version]({{site.baseurl}}/assets/img/install_jekyll.png)
^ same command for all the operating systems at this step.  

## Get the code for the website
Now, there are multiple ways to do this.  
You can [install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and clone the code to your system with the following command.  
![clone KD repo]({{site.baseurl}}/assets/img/clone_repo.png)  
[ OR ]  

You can simply download a zip of the website code from [this direct link](https://github.com/OhYash/KnowledgeDay/archive/refs/heads/master.zip) and extract it anywhere.  

## Final: Run the website
Woohoo! We got all we needed to get it up and running. Now just change your directory or `cd` to where you've cloned the code or extracted the zip and run the command to "serve" the Jekyll site:  
![clone KD repo]({{site.baseurl}}/assets/img/jekyll_serve.png)  
^ This command should give you a link something like `http://localhost:4000` or `http://127.0.0.1:4000/`. Open it in your webbrowser.  
Voila! YOUR OWN instance of Knowledge•Day website is running on YOUR system. Explore.  

![KD running on local IP]({{site.baseurl}}/assets/img/local_kd.jpg)
_Look at the url_

Easy, wasn't it?  
No database setup, no webserver setup on your system. Static sites don't need all that crap. We keep it simple.  

> If you face an issue at **any** step above, please feel free to reply to this email. I've compiled this for you to try the website out, and I'd be happy to help further I can.

## Okay. What now?
Now it's time to change stuff and see how it affects the website.  
Explore the files in the code; see the `_config.yml` file to make sense of some stuff.  
`_posts` contain... posts.  
How are `_layouts` defined?  
Design elements and all images are stored in the `assets` folder.  

Remember, every time you save any file with any change, Jekyll in the background will apply it. Just reload the page in the browser to see.  

------
------

Alrighty, that was it for this **KD** issue.   
You know you're reading this on the website, and you could get this sent through the mail as well?  

Mails I send are personalized too. You'll get the next knowledge day article delivered promptly. :)  

**How to Subscribe?**  
- [Click here](https://knowledgeday.in/signup/?utm_source=kdweb_issue50&utm_medium=blog_conclusion&utm_campaign=issue50) for a mere 20 second process; or  
- Send me a message on [Twitter](https://twitter.com/knowledgedaynl?utm_source=kdweb_issue50&utm_medium=blog_conclusion&utm_campaign=issue50)/[Instagram](http://instagram.com/knowledgedaynl?utm_source=kdweb_issue50&utm_medium=blog_conclusion&utm_campaign=issue50)  

Finally, time for you to try out the new feedback page. This will only be reachable through the email in future.  
 Do you [ [like](https://knowledgeday.in/feedback/?rx=1&is=50&utm_source=kdweb_feedback) ] this issue or [ [dislike](https://knowledgeday.in/feedback/?rx=0&is=50&utm_source=kdweb_feedback) ]?
