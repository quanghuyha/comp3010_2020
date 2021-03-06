## COMP3010: Algorithm Theory and Design, 2020, Macquarie University

This is the public repository for COMP3010: Algorithm Theory and Design, offered in Semester 2, 2020 at Macquarie University. The main purpose for this repository is to make it easier to share files and materials that you need for this subject. We can also make use of the wiki section of this repository to post extra notes. 

I plan to write all of the Java codes in this repository using JDK 14.0.2 with compiler compliance level 12, i.e Java 12, but I imagine my codes will also be compatible with
Java 8.
The repository was also built so that you can easily import and run these codes using git in Eclipse. If you are not using Eclipse, then you need to use to clone this project and manually add them to whatever IDE or text editor you are running.

You do not need to understand Git for this subject, but if you are a third year computing student, you really should have a good understanding of the basics by now. If you do need to learn Git, then head over to https://www.atlassian.com/git and read the beginner articles. At the very least, you should understand what a pull is.

## How to use this repository

Every week, if there are any Java source codes that you can use in the workshops or to supplement the lecture materials, then they will be released here. In the workshop instructions, I will make it clear which files you can modify and which files you should not, but this won't be a hard and fast rule. You are free to experiment and modify any file that I upload. However, there may be cases where I need to update or change a file after I upload it for the first time, so if you have already modified that file locally, you may have to perform a git merge. If you are comfortable with merging, that's great! Otherwise, I will add instructions for this, if necessary. 
 I also plan to release the code base for your assignments via this repository. 

## Configuring Eclipse to work with Git

The following is based on the tutorial on https://www.vogella.com/tutorials/EclipseGit/article.html. Feel free to follow the tutorial if you want a more complete understanding, but this section should be enough for COMP3010. The following guide (particularly the screenshots) were written using a MacOS, so there could be some differences with other operating systems, but the differences should be minimal.

First, we need to show the `Git Repositories` sub-window. On Eclipse, select

> Window -> Show View -> Other -> Git -> Git Repositories

<p align="center">
<img src="/images/git-1-show-other.png" width="500">
<img src="/images/git-2-show-git-repo.png" width="240">
</p>

A new sub-window titled `Git Repositories` will open (on the bottom left corner by default). To clone this repository, follow these steps: 
1. Click on `Clone a Git repository` 

<p align="center">
<img src="/images/git-3-git-repo-window.png" width="500">
</p>

2. On the new window that pops up (Source Git Repository), enter `https://github.com/sutantyo/comp3010_2020` as the URI and click `Next`. 

<p align="center">
<img src="/images/git-4-clone-repo.png" width="500">
</p>

3. On the next page (Branch Selection), select the master branch if it hasn't already been ticked, and click `Next`.

<p align="center">
<img src="/images/git-5-clone-repo.png" width="380">
</p>


4. On the next page (Local Destination), you can change the local directory if you want to, and then click `Finish`.

<p align="center">
<img src="/images/git-6-clone-repo.png" width="440">
</p>


5. Once you have cloned the repository, you should see the `comp3010_2020 [master]` repository in the `Git Repositories` sub-window. Right click on this repo, and then select `Import Projects...`. 
<p align="center">
<img src="/images/git-7-import-project.png" width="620">
</p>

6. On the newly opened window, you have the option of choosing `comp3010_2020/codes` folder (which contains just the Eclipse project) and/or the
`comp3010_2020` folder (which contains the whole repository). 

<p align="center">
<img src="/images/git-9-import-project.png" width="600">
</p>

7. The project should now be shown under the `Package Explorer`, and you can start modifying it. In the sccreenshot below, I pulled both folders
which added an empty `codes` folder. I am not sure how to fix this, but I don't think it matters that much anyway.

<p align="center">
<img src="/images/git-11-project-explorer.png" width="320">
</p>


## Updating your repository 

To pull the new files whenever the repository is updated, you can simply right-click on the repository under `Git Repositories`
sub-window and select `Pull`.

<p align="center">
<img src="/images/git-10-pull.png" width="520">
</p>

The files in your project should be automatically updated after you perform the pull.
