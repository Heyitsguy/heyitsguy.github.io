---
published: true
layout: post
title: Create Your Own Personal Blog With Jekyll
---
![jekyll and github](../images/jekyll_github.png)

---
Programming is a journey and developers are constantly learning as new technologies are coming out. One of the most popular ways to learn a new technology is through user and community driven content whether it be blogs, youtube, or tutorial sites. It is important for developers to start contributing to or producing informative content early on into their development career so that they can document their own journey and help others who are less knowledgeable on a specific topic out. 
    
Most beginners might want to write a blog but do not have the technical abilities to create a blog website yet. Blogging sites like medium help beginners lower the barrier to entry and let them write blogs without worrying about the technical aspect of publishing their content. However, blogging sites like medium compromises on customizability for convenience. In this blog I am going to show you a very quick and easy way to set up your own blog from a template and host it for free on github pages. Even though you are using a template for your blog, Jekyll allows you full control over the template so that you can customize it to your heart’s content.

# About Jekyll
---
Jekyll is a static site generator. Without going into too much detail, a static site is a site that has all of its code pre-written so that everyone who accesses the site will always get the same site. Most websites now days are dynamic, which means that the site is not pre-written but gets generated on request by the user. 

![static vs dynamic](../images/part-1-dynamic-x-static-server.png)

Static sites have their own advantages and disadvantages, here are a couple of advantages:

1. Faster speed since static sites don't need a server side language.
2. More secure since there are no databases

A couple of disadvantages are:

1. Very limited user experience (no CRUD functionalities)
2. Not DRY(Don’t Repeat Yourself)

Jekyll is used to generate multiple static sites by combining user content and a template.
