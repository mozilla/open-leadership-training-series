---
layout: page
title: "Project Set-Up"
module: "4.3"
date: 2016-10-06 14:05:56
time: "30 min"
following: _articles/get-your-project-online/sharing-your-work-in-the-open.md
summary: "In this module, you’ll learn how to organize your project files so they are easy for newcomers to navigate. You’ll also create your very first GitHub issue!"
prereq: "Have completed all previous sections and modules"
format: "Read, watch videos, use GitHub"
materials: "A computer, an internet connection, and a free GitHub account"
---
* TOC
{:toc}

### Project Structure and Organization

To work most effectively with contributors, your project structure should be clean and welcoming, with folder titles that make sense. For example, your project might have different folders for data, technical documentation, and images. README.md and CONTRIBUTING.md (which you’ll make in the next module) should be in your root directory, along with your ROADMAP. Think of these documents as an anchor for your project. As you add files, you may want to organize these into folders and create a consistent naming convention. Here’s an example of a good project set-up.

    .
    ├── docs
    ├── images
    ├── src
    ├── .gitignore
    ├── CONTRIBUTING.md
    └── README.md
    └── ROADMAP

Few example projects,

- [GitHub hubot](https://github.com/github/hubot) - CoffeeScript
- [nteract](https://github.com/nteract/nteract) - JavaScript
- [Picasso](https://github.com/square/picasso) - Java
- [Laravel](https://github.com/laravel/framework) - PHP
- [Ansible](https://github.com/ansible/ansible) - Python

GitHub is not only a place to store your files, and a way of managing collaborations, but also a great tool to organize the work you plan to do, and keep you on task. Here’s how:


{% include videowrapper.html
  url="https://www.filepicker.io/api/file/LjOBbVuSRhuJLFJlulZn"
  title="Github For Project Management, Hannah Kane" %}

Now that you’ve seen how GitHub can be used to organize and plan work, you’re ready to plan some work in your own GitHub repository.

### {{ site.assignment }} Add Your First Issue

![Creating your first milestone]({{ site.baseurl }}/img/create-milestone.gif)

1.  Create some milestones for your project. Refer to the roadmap you created in Section 2 (and added to the repo in the previous module). If you have milestones already specified in the roadmap, add them to your GitHub repo. If you don't have milestones, come up with two or three-- these are significant turning points or events that will move the project forward. You will use these to organize your issues.
    *  Give each milestone a title and brief description.
    *  Use the calendar interface to assign a date to the milestone.
    *  Save this milestone. It will now appear as an option
2.  (Optional) Create some labels. Click on the labels tab and add any new labels you’d like. These labels can help categorize an issue, or provide information about the priority or status of the issue. GitHub has some label options already baked in. These give you an idea of the kinds of labels that can be useful.
3.  Add some issues. As you’ve seen, an issue is a bit of information about work that needs to be done, a description of the next task you’re planning on doing. If you’re not sure what task to start with, go back and check out the Roadmap you created in Module 2, where you’ve outlined upcoming work.
    * Describe the work you plan to do. Use a checklist, if a task has multiple parts.
    * Provide context to show how this task relates to the larger plan described in your Roadmap.
    * If you like, give your new issue a label. Use the ones you’ve created, or the ones GitHub provides.
    * Add a milestone to your issue, to add a bit more information about the task, and how it fits into your larger project roadmap. Click on the Milestones button in the sidebar and select from the list of options you created in Step 1\.
    * Save the issue. Now you’re ready to get to work! (When this issue is eventually completed, you can close it. It will disappear from your Open issues tab and appear under the Closed issues tab. You can revisit it there at any time, to review work completed.) If you have an issue with multiple steps or tasks, use Markdown’s “checkbox” feature, and check off each task as you complete it.

![Creating your first issue]({{ site.baseurl }}/img/create-issue.png)

For more on GitHub and what the platform can do, see our list of Resources and Tutorials below.

### More GitHub Resources and Tutorials

- [Try GitHub](https://try.github.io) - Interactive Tutorial to learn GitHub
- [Git Tutorial](https://www.atlassian.com/git/tutorials/) - Illustrated Git Tutorial
- [GitHub Guides](https://guides.github.com/) - General guides authored by GitHub
- [Creating an Issue](https://help.github.com/articles/creating-an-issue/) - GitHub authored article on how to create an issue
- [Mastering Issues](https://guides.github.com/features/issues/) - Issues are a great way to keep track of tasks, enhancements, and bugs for your projects
- [Adding Existing Projects to GitHub](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/) - Learn how to add existing projects to GitHub using the command line
- [Creating a Repo](https://help.github.com/articles/create-a-repo/) - Learn how to create a repo
- [Fork a Repo](https://help.github.com/articles/fork-a-repo/) - Learn how to fork a repo
- [Adding a remote](https://help.github.com/articles/adding-a-remote/) - Learn how to add a new remote
- [Renaming a remote](https://help.github.com/articles/renaming-a-remote/) - Learn how to rename an existing remote
- [Working with remote](https://help.github.com/articles/renaming-a-remote/) - Git Basics-Working with remote


Now that your project is on GitHub, it’s ready to be shared widely. In the final module of this section, you’ll learn about licenses for sharing an open project.
