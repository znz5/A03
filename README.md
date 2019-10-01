echo "# A03" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/znz5/A03.git
git push -u origin master

GitHub, an online software development platform, uses Git, a version control system that is used for tracking changes in source code among several programmers. To get started on GitHub, simply make an account and after verifying your email address, the site will walk you through making a repository, which contain all the necessary files and folders for a project. 

After creating your repository, it is possible to create a local clone on your desktop, which can sync with the remote repository on GitHub and you can sync the two when you choose. It lives on your computer. 

Changes in GitHub repositories are called "Commits". Because GitHub uses Git, a system to control versions of repositories that many people could be working on at once, it is important that these changes are documented. When saving changes in GitHub, you can label your "commit" with a description, an extremely helpful and sometimes necessary tool when working with others.

When these changes are sent to a remote depository, such as the one hosted on GitHub, it is called a push. If you are working on a file and somebody has added changes to it, and you would like to access these changes, you want to pull the changes so you can access them and be working on an up-to-date copy. 

Branches are a safe way to organize and isolate work in a repository. Branches can be created to work on anything while keeping it away from the main repository, to avoid creating errors, or to experiment with new code without affecting the main branch. Branches can be merged with other branches using pull requests. 

Merges take everything from one branch and applies everything to another branch. This is accomplished using a pull request. Merge conflicts occur when there are several commits changing the same code, or some person edits a file when another person deletes it. Pull requests cannot be merged if there is a merge conflict, so it must be corrected or else the merge cannot go through. 

Getting the latest changes from an online repository and putting them on your local machine without merging them is called fetching. You can then compare the code to your code and then decide whether to merge or not by using a pull request after analyzing. 

Everything hosted on GitHub is called a remote repository, meaning it is hosted on a server, and then can be connected and synced to the local clones. This way, the local clones can be individually worked on by different people on their computers, and then push their changes to the remote repository where everybody else can pull the changes onto their local clones. 

References 

https://help.github.com/en/articles/github-glossary
https://help.github.com/en/articles/merging-a-pull-request
https://help.github.com/en/articles/about-merge-conflicts
