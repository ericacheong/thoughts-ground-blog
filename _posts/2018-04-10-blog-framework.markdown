---
layout: post
title:  "A very opinonated static site framework review"
date:   2018-04-10 12:23:41 +0800
categories: blog framework jekyll gatsbyjs hugo
---
I am a generalist. I am a pragmatist. I am impatient. I want to call myself full stack developer but I hate debugging system errors. Based on these assuptions, my blog is now built using [jekyll](https://jekyllrb.com).

Let's rewind a bit. Ruby on Rails is not my favorite programming tool (Ok, I agree it's very novice friendly and easy to start. Type a few commands and CRUD pages are geneated for you.) I tend to go for the hype and hip stack. The following is a list of things I have tried for my humble simple blog.

## GatsbyJS

Time spent: approx. 1 hour 15 min

[GatsbyJS](https://www.gatsbyjs.org/) looks very promising. It is very similar to [ReactJS](https://reactjs.org), which is my favorite front end tool at the moment. My search result brings me straight to the Starters page, where I find very useful blog templates that can be used at once. I tried a few and settled on the gatsby-starter-blog. Things then went wierd when I created, deleted and re-created the same title blog post, the blog title could be displayed and error became consistent. My Visual Studio Code has even crushed and restarted.

Given the features of this framework and the heavy duty nature of nodejs, the stack size becomes enormously large. The folder size is enormously 187MB!

I believe Gatsby is doing a good job as a Progressive Web App generator, which I am very interested to make it work. However, my simple blog does not deserve so much time in troubleshooting. So, next time round, Gatsby!

## Hugo

Time spent: approx. 15 mins

[Hugo](https://gohugo.io) made me excited for two things. One is that the programming language Go is on very top of my next to-learn list. Secondly it claims to be 'The world's fastest framework for building websites'. I really want to see how fast it is so I tried that out. As fast as I can claim, I have to put it aside after 15 mins. It may be my MacBook to blame. After typing `brew install hugo`, the screen shows errors. But it looks normal after typing `hugo version`. Then I proceed to `hugo new site quickstart` things got weird again. `hugo server -D` got even more errors to display. Naturally the site was no where to be seen as promised in http://localhost:1313.

Checking the hugo version it is still in v0.38, seems to be still in beta. Probably I will revisit this framework after it passes v1.0.


## Jekyll

Time spent: 10 mins (set up to deploy)

I can't fake it. The truth is Jekyll just works! With a few commands the local site is running. Deploying to [Netlify](https://netlify.com) is a breeze. I can use two less steps than those in the [official tutorial](https://www.netlify.com/blog/2015/10/28/a-step-by-step-guide-jekyll-3.0-on-netlify/). Just type `bundle exec jekyll serve` you can skip two steps.

There are still more features that I want to add. I am sure there are packages or tutorials on how to add Google Analytics, SEO or themes. Let's settle for this now.