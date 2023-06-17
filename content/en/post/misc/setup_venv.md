---
title: "Setting Up Virtual Environment"
#date: 2023-06-12T22:24:47+05:30
tags: ['Virtual Environment', 'Miscellaneous', 'Setting Up Environment']
featured_image: false
show_reading_time: true
summary: "Virtual environment is necessary to bury down the binary f-ups. Now you're interested."
---
---
#### 1. In Pycharm:
In new version of PyCharm, you've been provided the virtual environment while creating new projects.
[{{< figure src="/images/misc/pp4.png" title="" >}}](/images/misc/pp4.png)
Click on create button and wait to let PyCharm to show its charm.

#### 2. In All:

Open the terminal by clicking on (In PyCharm: "View" > "Tool Windows" > "Terminal")

In the terminal, navigate to the project directory.

Activate the virtual environment by running the appropriate command based on your operating system. For example, on Windows, use:
 
```
.\venv\Scripts\activate
```
On macOS or Linux, use:

```bash
source venv/bin/activate
```

 
### Check:

You can see the (venv) sign infront of terminal.

```bash
(venv) tuhinmajumder@Tuhins-MacBook-Air my_awesome_website %
```

Well done, you've successfully activated virtual environment.