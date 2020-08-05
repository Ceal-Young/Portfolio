---
title: "Static Site Generator"
title: "Static Site Generator"
date: 2020-08-04T11:30:43+04:00
description: "About static site generator"
author: "Alec Young Tie Yang"
---

# What is a static site generator?

In the past, Developing, Publishing and Writing content on a website required HTML, CSS and JavaScript skills.

Nowadays, **C**ontent **M**anagement **S**ystems (**CMS**) has allowed users with no technical skills to create contents on the web.

But these CMS have also got notorious over time for their problems.
They can be hard to work with; they can be slow, heavy and quite of a struggle when it comes to scalability and security.

Because of these flaws and the rise of DevOps, static websites generator such as Hugo, Jekyll or Hexo have become popular lately.

They offer the possibility to create static websites without the need for technical skills.



# Why use a static site generator?

The main reason we would want to use a static site generator is to simplify and speed up the process of spinning up a website.

Thanks to these static site generators, we can build a website without writing a single line of HTML, CSS or JavaScript.

They simplify the process by having a small learning curve, ready-to-go themes and easier to read files with markdown languages and YAML, TOML and JSON files.

More so, they still allow users to have deep customization with fine-grained control over their projects.
Static websites are very simple to setup and scale. It only requires installing a web server and load balance for a single service. Because there is no database, managing security is also made easier as any SQL injections is rendered impossible.    On top of that, the content delivery is very fast as web servers are good at handing out the static pages.

And finally, these generators work well with version control which enables continuous development, deployment and easy rollbacks. It ties down perfectly with the use of microservices such as headless **CMS**.

In contrast to Static Sites, **CMS** require both a database and a web server making modification of the architecture much harder while also being slower to serve pages as it first need to generate them before serving the content.
