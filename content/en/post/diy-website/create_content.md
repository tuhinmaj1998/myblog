---
title: "IV. DIY-Website - Create Content"
#date: 2023-06-14T22:24:47+05:30
tags: ['DIY-Website']
featured_image: false
show_reading_time: true
Summary: "Create your content and push it to GitHub"
toc: true
---
----
## Prerequisites
> Assuming you have followed the previous tutorials in this DIY-Website series, 
> you should now be equipped to create the following prerequisites:
> 1. [x] [Create project in your IDE (We are using PyCharm here)](/post/diy-website/setting_up_env/#create-project-in-pycharm)
> 2. [x] [Set up virtual Environment](/post/misc/setup_venv/)
> 3. [x] [Link your project with GitHub repository]()

## Be Creative, Be Bold

Now we've reached the most captivating phase: the creation process begins. We'll make a very basic webpage
and try to upload over GitHub.

### Create HTML File
* Create a file by Right-Clicking over your project folder > New > HTML File.
[{{< figure src="/images/misc/html1.png" title="" height="255px;">}}](/images/misc/html1.png)
If you encounter any pop-up prompting you to add/push the file to GitHub, 
you can choose to cancel or ignore it for the time being.


* Paste this basic html content below to check if it is working.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Index</title>
</head>
<body>
<h1>Welcome Folks!</h1>
<h2> Thank you for visiting <strong> My Awesome Website </strong> </h2>
</body>
</html>
```
### Push Code to GitHub

We are ready to deploy our basic index page for now. Now click over Commit section at left > Select All Changes > Add Commit message > Press ```Commit and Push```.

[{{< figure src="/images/misc/gitpush1.png" title="">}}](/images/misc/gitpush1.png)

let's add "First Commit" as Commit Message and then hit Push.

[{{< figure src="/images/misc/gitpush12.png" title="">}}](/images/misc/gitpush12.png)

Once you have successfully pushed the changes, navigate to your GitHub repository 
(in this case, <your_github_username/my_awesome_website) and verify if your repository appears as shown below.
[{{< figure src="/images/misc/gitpush3.png" title="">}}](/images/misc/gitpush3.png)

&nbsp;

Almost there! Just one final task remaining: deploy the page.

---

DIY-Website Series:
* [x] [Introduction to DIY-Website](/post/diy-website/intro/)
* [x] [Understanding Static Website](/post/diy-website/static_website/)
* [x] [Setting Up Environment](/post/diy-website/setting_up_env/)
* [x] [Setting Up Environment](/post/diy-website/create_content/)
* [ ] [Setting Up Environment](/post/diy-website/deploy_page/)
