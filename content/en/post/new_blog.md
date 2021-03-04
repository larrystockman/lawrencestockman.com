---
date: 2021-03-03
description: "Creating websites can be a pain."
featured_image: "/images/new_blog.jpg"
tags: ["headless"]
title: New Headless Blog
---

Don't you like writting themes, maintaing a CMS and also making sure you database is working? How about those constant patches you have to do to ensure that security is up to par? I hate all of those things! I just wanted to write tech based articles without having to worry about the security of my user name, various passwords, the database or the endless patches for exploits that were discovered in a number of open source CMS systems.

I have used Wordpress, Joomla and a number of other popular packages but it always seemed there was something getting in the way when it came to writing. There was something there just blocking me from writting when I felt inspired. More often than not, I was searching for the next add-on or plugin to enhance the experiance but that just seemed to start bogging down the load times of the pages. This is when I decided to start thinking of a new project to take on and ditch the clunky CMS platforms for something that would allow me to write the way I wanted and also have faster performacne for the user experience.

This is when I stumbled upon **[Hugo](https://gohugo.io)** which is a static site generator. It allows me to create a template and then feed my data into it to create static pages of my content. The content is rather simple as it's written in Markdown and the templates are in HTML wtih some Javascript as required. I can even extend this further by adding in some react if required for the various modules.

What made this appealing to me is that I could write my posts in another CMS and have Hugo grab the content from there and host it as a static site. This gives me the flexibility to write in an interface I'm familiar with and then have Hugo do the heavy lifting and processing of the content.

If you're worried about Markdown being too restrictive, Hugo does support Goldmark and BlackFriday which allows you to use HTML elements in my posts as well as tune how the Markdown rendering is done. You can read more about that [here](https://gohugo.io/getting-started/configuration-markup/). Just to save you a little work on building your own site/blog/empire, you will want to confiugre this in order to open your links that you set in Markdown to be able to open in a new window or tab.

In short, this gives me the flexibility and power to build my site the way I want and have the greatest performance possible. Oh, and if you want to see how this page was composed, here's what the Markdown and front matter look like.

```markdown:
---
date: 2021-03-03
description: "Creating websites can be a pain."
featured_image: "/images/new_blog.jpg"
tags: ["headless"]
title: New Headless Blog
---

Don't you like writting themes, maintaing a CMS and also making sure you database is working? 
How about those constant patches you have to do to ensure that security is up to par? 
I hate all of those things! I just wanted to write tech based articles without having to 
worry about the security of my user name, various passwords, the database or the endless 
patches for exploits that were discovered in a number of open source CMS systems.

I have used Wordpress, Joomla and a number of other popular packages but it always seemed 
there was something getting in the way when it came to writing. There was something there 
just blocking me from writting when I felt inspired. More often than not, I was searching 
for the next add-on or plugin to enhance the experiance but that just seemed to start 
bogging down the load times of the pages. This is when I decided to start thinking of a 
new project to take on and ditch the clunky CMS platforms for something that would allow me 
to write the way I wanted and also have faster performacne for the user experience.

This is when I stumbled upon **[Hugo](https://gohugo.io)** which is a static site generator. 
It allows me to create a template and then feed my data into it to create static pages of my 
content. The content is rather simple as it's written in Markdown and the templates are in 
HTML wtih some Javascript as required. I can even extend this further by adding in some 
react if required for the various modules.

What made this appealing to me is that I could write my posts in another CMS and have Hugo 
grab the content from there and host it as a static site. This gives me the flexibility to 
write in an interface I'm familiar with and then have Hugo do the heavy lifting and 
processing of the content.

If you're worried about Markdown being too restrictive, Hugo does support Goldmark and 
BlackFriday which allows you to use HTML elements in my posts as well as tune how the  
Markdown rendering is done. You can read more about that [here](https://gohugo.io/getting-started/configuration-markup/). Just to save you a little work on building your own 
site/blog/empire, you will want to confiugre this in order to open your links that 
you set in Markdown to be able to open in a new window or tab.

In short, this gives me the flexibility and power to build my site the way I want and 
have the greatest performance possible. Oh, and if you want to see how this page was 
composed, here's what the Markdown and front matter look like.
```