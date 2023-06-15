---
title: "Setting Up Environment"
date: 2023-06-12T22:24:47+05:30
tags: ['Setting Up Environment','DIY-Website']
featured_image: false
show_reading_time: true
Summary: "Environment is where we actually create the magic. Click to learn the magic."
---
----
I am a big fan of PyCharm IDE. To set up your development environment in PyCharm Community Edition 
and link it with GitHub using a virtual environment (venv), follow these steps:

### Prerequisites:
> Before diving into the action, let's assume we know at least the name of below things.
> * [Pycharm](/post/misc/setup_pycharm/)
> * [Virtual Environment](/post/misc/setup_venv/)
> * [Github](/post/misc/setup_github/)


### Create Project in PyCharm:

File > New Project

[//]: # ({{< figure src="/images/misc/pp1.png" title="" height="120vf;" >}})
[{{< figure src="/images/misc/pp1.png" title="" height="120vf;" >}}](/images/misc/pp1.png)

 Choose the Location and Name and create. (Make sure you don't have same named repository in Github)
[{{< figure src="/images/misc/pp4.png" title="" >}}](/images/misc/pp4.png)

### Link with Github
Now we have to create a repository in Github and link with pycharm present project. 
Fortunately PyCharm has inbuilt functionality to do it without a single line of command.

Select VCS > Click on 'Share Project on Github'
[{{< figure src="/images/misc/pp3.png" title="" width="230vf;" >}}](/images/misc/pp3.png)

If you are facing difficulties linking with GitHub, you may check [Setting Up Github](/post/misc/setup_github/).

At this point of time, I am assuming we have created Github account. If not, don't worry, [Sign up with Github](https://github.com/signup) and come back.

Your project is now set up in PyCharm Community Edition with a virtual environment, and your code is linked to a GitHub repository. 
You can continue developing your project, committing changes, and pushing them to GitHub as needed.

___

* Previous Section: [Introduction to DIY-Website](/post/diy-website/intro/)

* Next Section: [Understanding Static Website](/post/diy-website/static_website/)