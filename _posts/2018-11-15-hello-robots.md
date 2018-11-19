---
layout: post
title:  "Hello Robots!"
date:   2018-11-15 19:18:00 +0100
---

If you want web robots to visit your site you can use the file `robots.txt`. 
On the other hand, if you **_don't_** want them to visit your site you can also use `robots.txt` (but beware, don't trust the evil ones to stay away...).

The file `robots.txt` must be positioned in the root of the website. In this file, the site author can specify how the robot *should* behave on the site. The possibilities range from prohibiting all web robots activities, to gaining access to all content on the website for all web robots. You can also allow/disallow a certain web robot, or allow/disallow access to specific website folders. In addition, the site author can in this file specify the path to the sitemap.

The `robots.txt` of this website is shown below. This website does not contain any material needed to omit, so there is no need for disallowing specific folders. Usually the site owner is interested in getting the website to be spread to the world, thereby allowing many (all?) web robots. Since this site is under development (and this author is under education), for now only Googlebot and Bingbot is "allowed" on this site.

<iframe class = "code-text" 
  src="{{ site.url }}/robots.txt"
  width = "200"
  height = "115">
</iframe>

Keep in mind that a web robot (especially the evil ones) happily can choose to ignore your specifications in `robots.txt` and search the site regardless of your opinion!
