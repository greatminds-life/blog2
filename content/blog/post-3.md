---
title: "Building websites with Hugo"
date: 2020-05-02T10:07:47+06:00
draft: false
summary: "Hugo makes it fun and easy to build your own websites"
# post thumb
image: "images/featured-post/hugo.png"

# meta description
description: "this is meta description"

# taxonomies
categories: 
  - "Web"
tags:
  - "Hugo"
  - "Web"
  - "HTML"
  - "CSS"
  - "Design"

# post type
type: "post"
---


#### What is 'Hugo'?
> **<mark>" Hugo is one of the most popular open-source static site generators. With its amazing speed and flexibility, Hugo makes building websites fun again."</mark>**
>
> [source : https://gohugo.io/](https://gohugo.io/)

As Hugo team claimed above, Hugo allows you to build websites quickly and very satisfying way. And in most cases for free without annual or monthly subscription fees. If you are using free hosting services like [Github](https://github.com/) or [Netlify](https://www.netlify.com/), you only need to buy your domain name, usually charged annually. (In my case, I'm paying ~$10/year on my domain name)

#### Quick start with variety of themes
Following list shows open source Hugo themes I personally prefer, for personal blogging, showcasing your portfolio and for business promotion. You can find the complete list of themes [here](https://themes.gohugo.io/). These themes serve as a great starting place to build great looking websites. You can pick one and tinker it to customize to your needs and preferences(requires some level of understandings of html, css and little bit of javascript, still much quicker to build a website than start from the scratch). I am using **Liva** theme with some tweaks for this blog site. <mark>Click the name of each theme to view the them in action.</mark>

###### [Minimal](https://themes.gohugo.io/theme/minimal/)
for personal front page, blog, contact,search, social links
<img src= "../../images/post/minimal.png" width = 100% />

---

###### [Liva](https://themes.gohugo.io/theme/liva-hugo/)
for personal front page, blog, contact, social links
<img src= "../../images/post/liva.png" width = 100% />

---

###### [Novela](https://themes.gohugo.io/theme/hugo-theme-novela/)
for simple blog, dark/light themes
<img src= "../../images/post/novela.png" width = 100% />

---

###### [Mainroad](https://themes.gohugo.io/theme/mainroad/)
for simple blog - [demo site]
<img src= "../../images/post/mainroad.png" width = 100% />

---

###### [Timer](https://themes.gohugo.io/theme/timer-hugo/)
for promotional home, about, service, gallery, blog, contact - [demo site]
<img src= "../../images/post/timer.png" width = 100% />

---

###### [Navigator](https://themes.gohugo.io/theme/timer-hugo/)
for promotional home, about, service, gallery, blog, contact
<img src= "../../images/post/navigator.png" width = 100% />

---

###### [Creative portfolio](https://themes.gohugo.io/theme/hugo-creative-portfolio-theme/portfolio/)
for promotional home, about, service, gallery, blog, contact
<img src= "../../images/post/creativeport.png" width = 100% />

---

#### Things to learn to build websites with Hugo
Hugo definitely provides great starting point to build high quality websites, but it does require some level of knowledge and experience on some areas. Unlike all-in-one platforms like [Wix](https://wix.com), [Squarespace](https://squarespace.com) or [Wordpress](https://wordpress.com), you would need to have prerequisite knowledges or experience on the following topics:
###### Basic html/css/javascript
If you are to use the given themes as they are, this may not be a big of an issue since Hugo provide easy configuations for basic information to customize. However, if you would like to do more than that, you may want to learn html/css/javascript basics to directly edit layout html files, editing css styling or add javascript codes on your own. [w3schools.com](https://www.w3schools.com/) is a great resource you can start from.

---

###### Web design principles
Any design related work comes to the topic of understanding human behavior and their needs. Having understanding on user experience design, visual design and web design principles would be great addition to all other technical skills listed here. I, as a UX specialist, would like to put special emphasis on this topic if you really want to get serious on designing and implementing great user experience. Since many of us are using our mobile phones day in day out, considering mobile layout when designing website would be very important factor should not be missed, for example. [10 Usability Heuristics for User Interface Design](https://www.nngroup.com/articles/ten-usability-heuristics/) is a great read, and you can learn a lot from NN/g group for UX design in general.

----

###### Web hosting
If you are using platforms like Wix, Squarespace or Wordpress, you don't need to worry about this at all since all source codes will be hosted on their own server by default. Which also means you barely have controls on your source codes directly in many cases. If you would like to manage your code on your own, or, don't want to pay extra dollars on those platforms subscription fees(usually will cost you from around $100 to several hundreds dollars a year based on the plan you choose), you may want to learn how to host your source code on services like [Github](https://github.com/) or [Netlify](https://www.netlify.com/) as mentioned earlier.  Github started in 2008 and widely used by many tech companies' engineering team for their version control and source code sharing platform. Netlify started in 2014, gaining trackion in the market with their differntiated services like providing private repo even with their free account unlike Github. Both are useful tools to learn to host and publish your websites, mostly free.

---

###### Code editors
Since you have to deal with 'some' level of coding experience, you would need to pick one code editor of your preference. I have tried [Atom editor](https://atom.io/), [Sublime text editor](https://www.sublimetext.com/), [Brackets](http://brackets.io/) and [Visual Studio code editor](https://code.visualstudio.com/), and settled down to **Vsual Studio code** editor for ease of use, lots of plugin supports, built in terminal support, etc. It may require some trial and error to find a code editor best suited for you. 

--- 
 ###### Markdown
 Hugo uses Markdown to write contents for sites. Markdown, according to Wikipedia, is defined as _<mark>"a lightweight markup language with plain-text-formatting syntax. Its design allows it to be converted to many output formats, but the original tool by the same name only supports HTML."</mark>_ Beauty of using Markdown instead of html is in its simplicity. You only have to remember several key Markdown syntax to write up your blog post without worrying about styling then Hugo will generate great-looking html files along with built in css for you. All you need to do is to keep writing your content using Markdown. This blog post is also written using Markdown. 

---
###### Setting custom domain
This is optional and very easy. If you are not interested in getting unique domain name for yourself or your business, you could use default domain name provided by Github for example. But if you are to use your own domain name(i.e, website address name), then you would need to pick your domain name(must be available one), buy it(from one of the domain name providers like [Godaddy](https://www.godaddy.com/)) and connect your domain name to your web hosting server. 

---

##### Command lines in terminal
You would also need to get familiarize yourself on command line environment in terminal to install and run required programs to run Hugo. 

---

 #### Conclustion
 All in all, Hugo is a great tool to allow you build your own websites in short amount of time, once you get over the learning curves listed above. I recently switched from Wix to Hugo for my personal design portfolio site. At first, I started pure curiosity how Hugo could work and now I moved my portfolio site completely to Hugo. This saved ~$200 a year, which I really don't needed to pay. Wix is a great all in one platform, I am still using it for my freelancing works to build websites for my clients. It has lots of features to support business like cusomter management, creating online stores, setting up online appoinment scheduler, variety of built in widgets, establishing online payment system, and so much more. However, in my case, I don't need those features, all I needed was to host my design works(mostly static) on secure space which Hugo served it perfectly. If you are looking for simple and affordable web solution like me, Hugo is definitely worth trying.