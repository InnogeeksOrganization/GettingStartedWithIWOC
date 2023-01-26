# Getting Started With IWOC

So you finally decided to open to contribute to open source , but are overwhelmed by git wizards and large codebases.Then my friend , IWOC 2023 is the place for you! Start your opensource journey from IWOC.IWOC (Innogeeks Winter of Code) is a beginner-friendly open source event, where individuals of all skill levels can come together to learn and contribute to the open source community. The event is designed to provide hands-on experience and guidance for participants as they work on real-world projects and improve their skills. Whether you're a seasoned developer or new to coding, IWOC is the perfect opportunity to get involved in open source and make a meaningful impact. This repository contains various resources which will be useful for Mantainers as well as Contributors.

# Contributors

## What exactly is Github?

GitHub is a website that uses Git, a version control system, to allow developers to store and share their code online. It allows for easy collaboration on projects, as well as the ability to view and download other people's code. It also provides tools for developers to track bugs, review code, and manage projects. In simple terms, it's a platform for developers to store, share and collaborate on their software projects with others.

## Okay , but then what exactly is Git?

Git is a tool that helps developers keep track of changes to their code. It does this by taking "snapshots" of the code at different times, so that developers can go back to an earlier version if needed. Git also allows multiple people to work on the same codebase at the same time, without interfering with each other's changes. Think of it like a "save" button for code that keeps a history of all the changes and allows multiple people to work on it together.

## So how are Git and Github different?

Git and GitHub are related but serve different purposes.

Git is a version control system (VCS) that allows developers to track changes made to the source code of a project over time, and collaborate with others on the same codebase. It is a command-line tool that developers can use to manage their code locally on their own computer.

GitHub, on the other hand, is a web-based platform that uses Git as its VCS. It allows developers to store and share their code online, and provides a variety of tools to collaborate and manage software projects. GitHub is a hosting service for Git repositories, it provides an easy web interface to interact with the git repository, it also provides additional features such as issue tracking, pull request, Wiki, etc.

In summary, Git is a tool that developers use to track changes to their code, and GitHub is a web-based platform that provides a home for Git repositories and a variety of tools to collaborate on software projects.

## What is open-source?

Open source development is a type of software development where the source code (the code that makes a program work) is available for anyone to view, use, and modify. This means that anyone can take the code, make changes to it, and use it for their own purposes.

Open source culture is a way of working together on software development where the community can contribute to the codebase, and collaborate on improving the software. This allows for a more inclusive and democratic approach to software development, and encourages collaboration and sharing of knowledge.

In simple terms, open source development is a way of creating and sharing software where anyone can access, use and improve the code, and open source culture is a way of working together on software projects that is inclusive and collaborative.

## How can I contribute to open source?

**Find a project:** Look for open source projects that you are interested in and that align with your skills and experience. There are many platforms like GitHub, GitLab, and SourceForge where you can find open source projects.

**Read the documentation:** Most open source projects have documentation that explains how to contribute. This includes information on how to set up the development environment, how to submit changes, and the project's coding standards.

**Fork the repository:** Make a copy of the project's codebase to your own account, this is called "forking." This allows you to make changes to the code without affecting the original repository.

**Make your changes:** Once you have your own copy of the project, you can make changes to the code. Be sure to test your changes and make sure they work as expected.

**Create a pull request:** Once you've made your changes, submit them back to the original repository through a pull request. This allows the project maintainers to review your changes and decide if they should be included in the project.

**Communicate:** Keep in touch with the maintainers, if there are any issues or questions regarding your pull request.

**Keep an eye on the project:** Keep an eye on the project after your contributions have been accepted, and if you see any bugs or issues, report them or fix them. Also, if you are interested, you can continue to contribute to the project.

# Mantainers

So you've decided to open source your work? 
Congratulations! The world appreciates your contribution to developing a project that creates an impact!
Here are some guidelines for Project Maintainers:

### 1. The README
To get and keep the contributors, you will need a well-crafted README.md
Document the project to enhance the readability of the contributors. 
It may include the following details -
          -> What is your project about?
          -> Clear description of what the project does
          -> Easy installation and setup sections with screenshots
You may add a CONTRIBUTING.md file for new contributors, describing a step by step guide on how to contribute to your project.
Mentioning a Code of Conduct would be good. It'll reflect your values and what you expect from the contributors.

### 2. Opening issues
Including proper issues will help your contributors follow a convenient workflow for timely completion.
Creating issues will also help you track the progress and prioritize the tasks.
To help contributors open meaningful issues that provide the information that you need, you can use issue forms and issue templates.

### 3. Good Communication
Ensure that you are actively available for keeping a watch during the month of February.
Remember to engage with your contributors in healthy discussions about the development phase.
Being idle might result into decrement in the progress that is to be made in a stipulated time.

### 4. Efficient Auditing
Keep a watch on PRs actively, to ensure that all the meaningful PRs are merged timely and on priority.
If the contributor is inactive for more than 3 days over on an assigned Issue, you must nudge the contributor towards completing the work.
In case the contributor is unresponsive to all the reminders, you are free to discard them off from "Assignees" list. 
It also reflects that your project is active and might attract more new contributors to add on to the workforce.

###  5. Labels and Milestones
Ensure to add "IWOC2023" tag in your repo's and Issue's to be counted in for the participation in the IWOC event.
Make sure to add more value by categorizing your issues by:- ```Easy```, ```Medium``` and ```Hard``` Tags, so that contributors can easily classify the issues that they can contribute to for successful completion.
For e.g. tags labelled as "Easy" help new contributors navigate to issues for contribution that matches their current skillset.
If the proposed task is big and hard to be implemented in one go, you can divide the Issue in Sub-Issues and categorize them further with Easy, Medium and Hard Tags.

###  5. Issues Created by IWOC Contributors
All issues submitted must be verified by the project maintainer and assigned a difficulty level (easy, medium, hard) before any work begins. This ensures the issues are valid and can be properly addressed according to their complexity. Only after an issue is approved by the maintainer or admin, a contributor can start working on it. This process ensures that contributions align with the project's goals and maintain the quality of the codebase.

### Scoring Parameters 
* Easy - 10 Points
* Medium - 20 Points 
* Hard - 30 Points

Calculation of the scored points will be done at the end of the event by IWOC's team.

Now you're good to go!

# Resources ( For Mantainers )

This repository also contains some useful resources which you can use right out of the box!

## File templates

You can use the following templates in your repositories.

* [Contributing.md](Contributing.md)
* [Issue template](.github/ISSUE_TEMPLATE/)
* [PR template](.github/pull_request_template.md)

[How to configure Issue Templates for your repository?](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository)

## Github Actions

### What are github actions?

GitHub Actions is a tool that allows developers to automate various software development workflows directly within their GitHub repository. These workflows can include tasks such as building and testing code, deploying code to a production environment, and publishing releases.

Actions are defined as individual steps or "workflows" that can be run in response to specific events, such as a code push or the creation of a pull request. These workflows are defined in a file called a workflow file, which is written in YAML and stored in the repository's .github/workflows directory.

GitHub Actions can be used for a wide range of tasks such as continuous integration, continuous delivery, and automating deployments. It also allows integration with a variety of third-party services and tools, such as cloud providers, container registries, and more.

The most common use case for GitHub Actions is to automatically build and test code changes every time a developer pushes code to the repository. This helps to ensure that changes are working as expected and that the project remains in a releasable state.

[How to setup github actions in your repository?](https://towardsdatascience.com/github-actions-everything-you-need-to-know-to-get-started-537f1dffa0ed)

### Some sample github actions

These are some github actions which you can use in your repository.You can find the ```.yml``` files for some of these [here](.github/workflows/). You can use them as a refrence and setup your actions in your repositories.

* [Greeting New Contributors](https://github.com/marketplace/actions/welcome-new-contributors)
* [Adding Contributor Names in README](https://github.com/marketplace/actions/auto-add-contributors)
