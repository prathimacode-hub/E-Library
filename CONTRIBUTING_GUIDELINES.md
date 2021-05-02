## Contributing Guidelines

This documentation contains a set of guidelines to help you during the contribution process. 
I'm happy to welcome all the contributions from anyone willing to add documents to this repository. Any document added should be in pdf format. Thank you for helping out and remember,
**no contribution is too small.**

## 💥Steps to Contribute:

1. Fork the repository to your own GitHub account.

2. Clone the repository to your local machine
```
   $ git clone "https://www.github.com/{Username}/HelloWorld.git"
```
   where username is your GitHub account username.

3. Create a branch where you can do your local work. Never work on master branch as we do not allow master commits except by admins.
```
   $ git branch {branchname}
```

```
   $ git checkout branchname
```

4. Do your work and stage your changes.
```
   $ git add <filename>
 ``` 
5. Commit you changes with a commit message containing your name, file(s) worked upon, changes added.
```
   $ git commit -m "Name| files| Changes"
```
6. Push changes to your forked repository
```
   $ git push -u origin branchname
```
7. Create a pull request to the upstream repository.


<h2>📜Synchronize forked repository with Upstream repository</h2>

1. Create upstream as our repository
```
   $ git remote add upstream "https://www.github.com/prathimacode-hub/HelloWorld"
```
2. Fetch upstream changes in local machine
```
   $ git fetch upstream
```
3. Switch to master branch
```
   $ git checkout master
```
4. Merge changes in local machine
```
   $ git merge upstream/master
```
5. Push changes to your forked GitHub repository
```
   $ git push -f origin master
```

## Note:

> - Do not edit/delete someone else's file in this repository. You can only insert new files in this repository.

> - Give a meaningful name to file you are adding, for e.g., if you have uploaded a book on Python, then Bookname.pdf is one example of valid name.

## What should I keep in mind while contributing?
- When you are contributing, make sure if that document is added up in the repository well before.
- If you couldn't see a folder of tech stack or language you are planning to contribute, don't hesitate to add the same. Do follow the template of how a folder or file should be added [here](https://github.com/prathimacode-hub/E-Library/tree/main/Python).

## Resources
1. Markdown : Markdown is a lightweight markup language like HTML, with plain text formatting syntax. 

  * [Markdown Cheat-Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

2. Git : Git is a distributed version-control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files.
  * [Videos to get started](https://www.youtube.com/watch?v=xAAmje1H9YM&list=PLeo1K3hjS3usJuxZZUBdjAcilgfQHkRzW)
  * [Cheat Sheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)

## Need more help?🤔
You can refer to the following articles on basics of Git and Github and also contact me, in case you are stuck:
- [Forking a Repo](https://help.github.com/en/github/getting-started-with-github/fork-a-repo)
- [Cloning a Repo](https://help.github.com/en/desktop/contributing-to-projects/creating-an-issue-or-pull-request)
- [How to create a Pull Request](https://opensource.com/article/19/7/create-pull-request-github)
- [Getting started with Git and GitHub](https://towardsdatascience.com/getting-started-with-git-and-github-6fcd0f2d4ac6)
- [Learn GitHub from Scratch](https://lab.github.com/githubtraining/introduction-to-github)

## Tip from me😇
Sharing is caring. Contribute the resources concerning all the programmming languages and technical stack that made you shine or resourceful in any way. Help fellow coders in gaining technical guidance with this online library. 

Happy Contribution. 🌟
