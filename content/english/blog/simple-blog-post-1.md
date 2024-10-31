---
title: "My First Blog!"
# date: 2018-09-12T12:52:36+06:00
image_webp: images/blog/blog-post-3.webp
image: images/blog/blog-post-3.jpg
author: Avyay C
description : "This is meta description"
---
I created this website for pure fun. I saw a lot of people making websites, so I was really motivated to make mine. I went up on Gohugo.io, searched for a theme that I really liked, and ended up finding this theme, Meghna Hugo. I initially had acquired a free domain at Freenom and set up Google Analytics and a Zoho mailserver for it (after mailing the people at Zoho), but my domain ended up expiring, so I migrated this whole thing to a github.io subdomain. I still don't understand why I picked "theyoungwriter-tk"!

To create a website like this, first install Git and Hugo. Then, run the command "hugo new site" followed by your site name. Once you find yourself a theme, go to its Github page and copy the repo's URL. Then paste it into this command: git submodule add <theme-repo-url> themes/<theme-name>. After doing this, update your config.toml or config.yaml to your new theme name. Now, your website should be up and running on locahost! (More in the next post)