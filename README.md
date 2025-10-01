# A02
UCID: jvn 

A02 Repository for IS117

*Part 1: Tutorial on how to use Git, Webstorm, & Github:*
1. First download Git for your operating system. (link: https://git-scm.com/downloads)
2. Then download Webstorm from JetBrains for your operating system. (link: https://www.jetbrains.com/student)
3. Sign up for a github account with your email. (link: https://github.com/join)
4. Open your git terminal.
5. Generate an SSH key: type ssh-keygen -t ed25519 -C “github_email@example.com"
6. Copy the path in the parentheses and change the ending to a unique name (i.e. “is117)
7. Enter “cat ~/.ssh/your-key.pub”
8. Copy the output.
9. Click your profile in Github -> Settings -> SSH and GPG keys
10. Click new key and paste the output.
11. Go to your repository on Github -> green code button -> SSH
12. Copy link in SSH.
13. Git clone [SSH link]
14. If that doesn’t work, type eval "$(ssh-agent -s)" and then ssh-add ~/.ssh/github_key to add your private key.
15. Try to clone again. 
16. On Webstorm, go to Settings -> Version Control -> Git
17. Make sure “Path to Git Executable” is “C:\Program Files\Git\bin\git.exe”.
18. Click create new project, then create new file.
19. Click the top bar, then click Git and select Create Git Repository.
20. Make changes to your file, then hit Git -> Commit. You might have to sign into Github.
21. Finally go to Import into Version Control, then choose Share Project on Github. Now you can make edits, pull, push, and more on your local and remote repositories.
22. Now you’ve connected Git, Webstorm (or your editor of choice), and Github so you can use all these tools together for coding and version control!

*Part 2: Glossary:*

**Branch**: A copy of the repository at that time. They are parallel versions of your project that are created for each feature/task, letting users work separately without affecting previous branches. 

**Clone**: Also called a working copy, the clone is your copy of all the files in a project, allowing you to make changes without affecting other teammates. 

**Commit**: A commit is a change from the working copy/clone to the repository. 

**Fetch**: Fetching brings changes from a remote repository to a local repository. 

**GIT**: Git is a protocol with the purpose of tracking file changes. It's the most popular version control system.

**Github**: Github hosts a server for a remote Git repository. Allows for multiple people to work on the same project at the same time. 

**Merge**: Merging is when you bring changes from one branch into another one, combining them into one. 

**Merge Conflict**: These happen when two different people make different changes to the same line in a file simultaneously. Git doesn't know which change is the correct one, so the conflict needs to be solved manually. 

**Push**: Pushing a change is when changes on a local repository are considered the best they can be and are sent to the remote repository.

**Pull**: First fetches so that the local repository matches the remote one, then it updates, changing the working copy so that it matches your local repository. This is how you request changes from one branch to another.

**Remote**: Remote repositories are stored in Github and are hosted on a server that multiple devices can access, compared to a local repository which is on your computer.

**Repository**: A repository tracks differences between files, so it is a database of the edits in your project.



*References*


Ernst, M. (2022, March 7). Version control concepts and best practices. Washington.edu. https://homes.cs.washington.edu/~mernst/advice/version-control.html

GitHub (2019) GitHub Guides Tutorial. Retrieved March
19, 2019, from
https://guides.github.com/activities/hello-world/
21

GitHub. (2024, May 26). A brief introduction to Git for beginners | GitHub. YouTube. https://www.youtube.com/watch?v=r8jQ9hVA2qs


Jetbrains. (2019). Git. Retrieved March 21, 2019, from
https://www.jetbrains.com/help/webstorm/using-git-
Integration.html

Toegel, M. (n.d.). Github Version Control [Review of Github Version Control]. Learn Ethereal ; Matt Toegel.

‌
