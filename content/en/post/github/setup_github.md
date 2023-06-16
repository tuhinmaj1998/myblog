---
title: "Link Project with Github"
date: 2023-06-12T22:24:47+05:30
tags: ['Github', 'Miscellaneous', 'Setting Up Environment']
featured_image: false
show_reading_time: true
summary: "Let's learn how to link project with github. Click to learn more."

---
There are two ways to set up GitHub with your project.

## In GitHub:

#### Run the following command to initialize a Git repository
```csharp
git init
````
#### Link your project to a GitHub repository
* Create a new repository on [GitHub](https://github.com/new) without initializing it with a README, .gitignore, or license.

* Copy the repository URL 

```https://github.com/<yourusername>/<your-repo.git>```



## In PyCharm: 

* Go to `VCS > Git > Remotes`.
* Click on the `+` button to add a new remote.
* Enter a name for the remote (e.g., "origin") and paste the repository URL. Click `OK` to save the remote configuration.

#### Commit and Push Your Code
* In the PyCharm IDE, create or import your files as needed.

* Use the Git integration in PyCharm to stage and commit your changes.
* After committing, select `VCS > Git > Push` to push your code to the GitHub repository.

[//]: # ([{{< figure src="/images/misc/git2.png" title="" >}}]&#40;/images/misc/git2.png&#41;)
[{{< figure src="/images/misc/git2.png" title="" >}}](/images/misc/git2.png)

* Provide your GitHub credentials if prompted.

That's it!!

Your project is now linked to a GitHub repository. 
You can continue developing your project, committing changes, and pushing them to GitHub as needed.