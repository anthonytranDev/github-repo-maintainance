<h1 align="center"> GitHub Repo Maintenance :rocket: </h1>


<p align="center">Set of guidelines on how to organise and maintain your GitHub repos (repositories).</p>

---

## What’s In This Document

- [What is Git and GitHub?](#-what-is-git-and-github?)
- [Git Repo Checklist](#-git-repo-checklist)
- [Guidelines made "Easier to Read"](#-Guidelines-made-"Easier-to-Read")
- [How to Contribute](#-how-to-contribute)
- [Our Contributors](#-our-contributors)


---

## :confused: What is Git and GitHub?

Here `repo` is short for `repository`

[Git](#Git) - is the version control technology, that helps keep track of files you want to add to your project ands ones you don't.


[GitHub](#GitHub) - is a repo hosting platform that uses `Git` technology to control the different versions of your software or website

---

## :+1: Git Repo Checklist

### :sparkles: Requirements

This lists what your JavaScript repo **MUST** contain. For every basic repo setup that exists out there.

- [README.md](#readme.md) - this is the starting point of any repo. Plus it's the first document any developer regardless of whether the codebase is in `JavaScript`, `Python` or `C++`. Projects that do not contain any README.md are seen as carelessly written, it gives the impression that the developer didn't care about the project they owned. So please include one

- [package.json](#package.json) - whether or not your projects includes the use of libraries. The `package.json` includes everything from the author's name and details, GitHub URL and clearly states the version of Node used to create the project; and more

- [package-lock.json]() - this file is automatically produced upon `npm install`. After installation this file is produced to lock in the different packages and their subsequent dependencies

- [/src]() - is a directory that includes all the development code that will part of the final project. Files such as `index.js`, `index.css`, and `index.html`.

- [.gitignore]() - this files allows a Git repo ignores a single filesfiles, or files in those directories. Remember that git is used to commit files not specifically directories. Meaning if you have an _empty_ directory. Again this does not depend on whether you are writing JavaScript, Python of C++

### :star2: Suggestions

This lists what your JavaScript repo **COULD** contain. These suggestions are mainly here to encourage new contributors to your codebase.

- [.editorconfig]() - a format file contains details on mainly such as.
  - spacing for spacebar
  - tab spacing

- [.eslintrc]() - a format file that contains information how the JavaScript code they write, must be styled

- [LICENSE]() - the license provided here will tell developers what they are legally allowed to do the code written, such as making changes. What they should expect from the software they are using. Who is responsible if the code they use breaks, causes financial loss. It all depends on what license is being used. Here are popular license used by the open source community. See more details - https://choosealicense.com/licenses/
  - **MIT**
  - **GNU** (with different variations and versions available)
  - **Apache License 2.0**
  - Projects can even be **Unlicensed**

- [/docs]() - this usually contains Markdown (i.e. `.md` files) on aspects of the project or tool
  - **features** - what main parts of the project or tool have got to offer
  - **tutorial** - a basic guide on how to use your project. This is usually useful if the project is large. Else just stick to including the tutorial in the `README.md`
  - **blog** - this usually includes blogs on how your project has been used etc

- [AUTHORS]() - this usually contains the list of all contributors or just main contributors to a specific git repo project

- [CHANGELOG.md]() - this mainly used for recording the history of different changes to the version of software or JavaScript libraries you are using. Such version 2.0.0, 2.0.1 or 2.1.0. A system called "semver" known as "semantic versioning" is used to record changes to each version of the software. Below bullet points, display how semantic versioning works
  - The letter `v` means `version`, so `v1.0.0` means version 1.0.0

  - **Major changes (v1 -> v2)** - changing from version v1.0.0 to v2.0.0. This is where the code is usually NOT "reversely compatible" with the older version of software.

  - **Minor changes (v1.1 -> v1.2)** - changing from version v1.1.0 to v1.2.0. This is where the code is usually is "reversely compatible" with the older version of software. This change usually include release of additional features to the software produced.

  - **Patch changes (v1.0.1 -> v1.0.2)** - changing from version v1.0.1 to v1.0.2. This is where the code is is "reversely compatible" with the older version of software. This change usually include bug fixes or other changes such as code refactoring or styling to be included.


- [CONTRIBUTING.md]() - This usually gives developers instructions and encourages those who want to add or change something to git repo. Depending on repo maintainers, this document can be either 
  - **Words of Encouragement** - used to movivate new contributors to the codebase
  - **Detailed Instuctions** -  includes specific instructions on how to contribute to the codebase; usually includes **Words of Encouragement**

- [CODE_OF_CONDUCT.md]() - Gives contributors a set of rules to follow and help new contributors to join and maintain a place where every can be treated fairly

---

## :innocent: Guidelines made "Easier to Read"
These guidelines have been aimed at developers whose first language is not English, so some of the wording has been changed to cater for all. This means;

- **Use of Simpler Words** - so rather than have the set of words or word like "come across" or "observed" this will be replaced with "find" or "noticed". Another example is the phrase "fully grasp", which will be replaced with the word "understand" instead.

- **Conventional Phrases Removed** - phrases that can understood by the English speaking world, such as "It's just a lot fluff" aren't really required here and so one should just stick to "International English"

- **No Idioms** - idioms usually require both a knowledge of the English culture and historical significane to be fully understood. It means readers would have to spend more time searching for what phrases like "breaking the ice" actually means.

- **Absolutely NO Sarcasm** -  this may even confuse native English speakers who have started off learning to code; as it requires the reader to understand the "context", before understanding that such an action should be avoided. So no sarcasm

---

## 🤝 How to Contribute

First off, thank you for considering contributing to GitHub Repo Maintenance. 

<br>

:see_no_evil: These documents are currently at the initially `drafting stage` :see_no_evil:

<br>

We expect everyone participating in the Maintaining GitHub Repo documents to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it. Please follow it.

We hope to make these notes available to all coding and JavaScript beginers alike.

### Where to start?

To make changes to the repo, please `fork` the repo. If 
you are new to contributing please could you email the contributors below for advice (just click on of those below) and they'll be happy help you on how to make pull request to this repo.

### Code of Conduct

You can find our full code of conduct [here](/CODE_OF_CONDUCT.md).

---

## :octocat: Our Contributors

- Anthony Tran - anthonytran.dev@gmail.com
