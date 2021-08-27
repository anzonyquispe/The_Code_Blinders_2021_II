# The Code Blinders 
## Introduction to Git & Github
This material is based on DIME Analytics - World Bank and [this web page](https://happygitwithr.com/big-picture.html#what-is-the-payoff).

## Version Control Issues
<img src="final_doc.jpg" alt="drawing" width="500"/>
It seems like a joke but it is an anecdote.

- Several copies of the same document.
- Problems in tracking changes.
- Accidental mistakes.
- Backups problems.
- Messy documents.
-  Team working problems:
    * For Dropbox users, **"Copy Conflict"** may sounds familiar.
    * Who did change the code?
- **No version history**.

### What is VERSION CONTROL (Version History)? 
Let see an example of  **Version Control** in DROPBOX.  [example](https://www.dropbox.com/history/Geocode_WB/2_Geocoded_Data/pp_list_2015_2019_part1_final_Attia.xlsx?_subject_uid=392562030&undelete=1)


<img src="dropbox_version_control.png" alt="REPO" width="900" title = "REPO"/>

Dropbox has a version history of every file. We can see every time a file has been saved. But, are all of them significant? why did we save that file two times?



## Git - The Hero
It is a **version control system** developed by Linus Torvalds, the famous creator of the Linux operating system kernel. We can track changes in our files in a highly structured way. 

### Benefits of Git

1. Git solves the "Final.doc" problem. **No more** files naming like this *final_version_last_2.doc*. We do not need to have many copies of the document. 

2. In this workflow, we can work in teams. Anyone can edit, anyone can access previous versions and the most recent versions.

3. Git helps us to track who has been editing the document.

4. No more emails asking Which one is “master”? Is it even possible to say? How do different versions relate to each other? How should versions be reconciled? If you want to see the current best version, how do you get it?


## GitHub 
It is a hosting service. It provides a "home" for your Git-based projects on the internet.

### Benefits of GitHub
1. Your projects are exposed on the internet and are easily shareable.

2. You can easily track the development of any project.

3. Everything is in the hosting service. Everything is going to be alright.


### Key concepts
* **Repository** : Set of files. It exists as a remote repository.
* **Clone** : When wee clone a repository, we create a local copy of all the repository on our computer at that point in time. 
* **Commit** : Snapshot of your repository. Git does not store data as a series of changesets or differences but instead as a series of **snapshots**.
* **Branch** :  It is simply a lightweight movable pointer to one of these snapshots or commits. A independent line of development.
* **Merge** :  Combine multiple sequence of commits to the main branch.



## **Clone**
It is not the same as downloading. When we clone a repository, we copy the complete history of that repository. Your computer uses Git software to download the version history. Additionally,  we can make updates in the cloned repository that can be merged with the remote repository. When we download a repository, we do not copy the project history.


### How to clone a respository? 
1. Go to **main page** de https://github.com/antonioalt23/The_Code_Blinders.
2. Click on green button _Code or download button_
<img src="clone_button.png" alt="REPO" width="500" title = "REPO"/>
3. Click ** Open with GitHub Desktop ** 4. It will be saved in the Documents folder by default, but you can move to another folder. ** Never save in a shared folder like Google Drive or Dropbox **


## **What is a Commit?**
It is a snapshot of your repository. Git does not store data as a series of changesets or differences but instead as a series of **snapshots**.

It has the metadata: author, date, message, parent commit, tree object hash, parent commit hash, and message.

It indicates the significant modification to our version control system. Finally, a commit object references a snapshot.

## **What is a Branch?**
It is simply a lightweight movable pointer to one of these snapshots or commits. It is brilliant.

<img src="git_branches.png" alt="REPO" width="700" title = "REPO"/>

It allows you to reference to any snapshot of your project.
When we create a branch, we create a new pointer to move around.



## **Pull Request**
When everything is fine, you can pull request your commits. Then, these commits can be merge with the main branch.

**PULL REQUESST** = Request your commits be accepted by the repository maintainer.

