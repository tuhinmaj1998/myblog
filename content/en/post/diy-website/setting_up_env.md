---
title: "III. DIY-Website - Environment Setup"
#date: 2023-06-14T22:24:47+05:30
tags: ['Setting Up Environment','DIY-Website']
featured_image: false
show_reading_time: true
Summary: "Environment is where we actually create the magic. Click to learn the magic."
toc:
    toclevels: 4
hasCJKLanguage: true
---
----
I am a big fan of PyCharm IDE since it's free. To set up your development environment in PyCharm Community Edition 
and link it with GitHub using a virtual environment (venv), follow these steps:

### Prerequisites
> Before diving into the action, let's assume we know at least the name of below things.
> 1. [x] [Pycharm](/post/misc/setup_pycharm/)
> 2. [x] [Virtual Environment](/post/misc/setup_venv/)
> 3. [x] [GitHub](/post/github/setup_github/)
> 
> No worries if you don't know, you can either explore the provided link or embark on a brave 
> quest to test your adaptability. After all, as humans, we have come a long way from apes,
> and it's our choice to embrace challenges and grow.

### Choose Project in PyCharm

* File > New Project

[{{< figure src="/images/misc/pp1.png" title="" height="120vf;" >}}](/images/misc/pp1.png)

* Choose the Location and Name. (Make sure you don't have same-named repository in GitHub)

[{{< figure src="/images/misc/pp4.png" title="" >}}](/images/misc/pp4.png)

### Virtual Environment Setup

You need to select `New environment using ` **Virtualenv**. Hit Create on bottom-right corner of the screen.
Wait to finishing up the setup, you'll see `(venv)` like below in terminal window.
```bash
(venv) tuhinmajumder@Tuhins-MacBook-Air my_awesome_website %
```
For more information how to setup virtual environment [click here.](/post/misc/setup_venv/)

### Link with GitHub
Now we have to create a repository in GitHub and link with pycharm present project. (A GitHub repository is a storage space where you can store and organize your code, collaborate with others, and track changes to your project over time.)
Fortunately PyCharm has inbuilt functionality to do it without a single line of command.

Select VCS > Click on 'Share Project on GitHub'
[{{< figure src="/images/misc/pp3.png" title="" width="230vf;" >}}](/images/misc/pp3.png)

If you are facing difficulties linking with GitHub, you may check [Setting Up GitHub](/post/misc/setup_github/).

At this point of time, I am assuming we have created GitHub account. If not, don't worry, [Sign up with GitHub](https://github.com/signup) and come back.

Your project is now set up in PyCharm Community Edition with a virtual environment, and your code is linked to a GitHub repository. 
You can continue developing your project, committing changes, and pushing them to GitHub as needed.

___

DIY-Website Series:
* [x] [Introduction to DIY-Website](/post/diy-website/intro/)
* [x] [Understanding Static Website](/post/diy-website/static_website/)
* [x] [Setting Up Environment](/post/diy-website/setting_up_env/)
* [ ] [Setting Up Environment](/post/diy-website/create_content/)
* [ ] [Setting Up Environment](/post/diy-website/deploy_page/)
