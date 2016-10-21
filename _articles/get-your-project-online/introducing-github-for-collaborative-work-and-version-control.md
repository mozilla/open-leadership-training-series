---
layout: page
title: "Introducing GitHub"
module: "4.1"
date: 2016-10-06 14:05:56
time: "20 min"
following: _articles/get-your-project-online/the-github-interface-and-markdown.md
summary: "For others to discover, contribute to, learn from, and re-use your project, it needs to be on the world wide web. We recommend using a web-based software platform called GitHub, which helps you with one of the main challenges in collaborating with lots of volunteers on a single project. This challenge is “version control,” the task of managing the many contributions your group makes to shared working documents. This module explains the more about version control, and how GitHub can help."
prereq: "Have completed all previous sections and modules"
format: "Read, look at diagrams, and watch videos"
materials: "None"
---
* TOC
{:toc}

### Collaborative Work and Version Control

Your contributors may be spread around the world or working in the same room; they may be working simultaneously or asynchronously. No matter how you’re working, all contributions need to be wrangled into a single project. Thankfully, we have version control, which is a way of keeping track of changes made to a collection of working documents. Version control also stores the history of changes, allowing you to revert or go back to earlier versions of those documents, and understand how contributions have changed the project over time. You may have used word processing software that has a “changes,” “history” or “revisions” feature, which also allows you to see and revisit any changes to the document: this is a form of version control!

How does it work? Let’s look at some diagrams to better understand version control, and learn some new vocabulary related to this concept.

When we code, write text, or create any kind of content using computers, we end up with a collection of files in a folder or directory, also known as a repository, or “repo.”

![Open-Leadership-Curriculum-Diagrams-and-Line-Art-04.png](https://lh3.googleusercontent.com/sQoNFN2_O3-LFT5UpKzSl1keSvQnjjfleeb9i5tFcBf_UdkazbUSnUWgIlCWpSonUK4_A0RKwZkNnEZ0wnZ8-eHFn3TH3nkEhDniiq4rwBwAE3F6sCNZ0_Gms7sQopBsFOotpdEc)

Even if you’re working alone, you’re probably going to make lots of changes to your content or code as you go-- you'll change some sections or functionality and leave others untouched, you'll make mistakes while you experiment with new ideas.

![Open-Leadership-Curriculum-Diagrams-and-Line-Art-05.png](https://lh3.googleusercontent.com/wYh-8kl_sBZn_3BXyFgYnesqZKhvanay2UGbCUW-AXundxHmqoxmmctWSof-UkDLR4JMx-xrbJ0ShDyGRE5JdtU5dXTDjQ33fj9JDgN-MhV9VDQMfAO5NKnhYx-sN5DodK_ef4tC)

You might make multiple copies of your files to preserve a version that's working while you try to improve it or add functionality, but keeping track of all these versions and the differences between them becomes difficult.

![Open-Leadership-Curriculum-Diagrams-and-Line-Art-06.png](https://lh5.googleusercontent.com/0PwkghcbzK4Zc43yPqZYEruVsFNXqL3sasQVyUdulBWnG8CgcKwHzZ7dA5OLybtyStzdakEajrG6AzJI-jp7zdiMHZMulqyxsRJYTPs3RvJmc7E1owOyLgcE0Guy0KJ747MCZeaX)

We need **version control.** Imagine your document has a life story. Version control is like a time machine, it can take you back to the moment your document was born, or any other point in time when you or a collaborator saved that document. You don’t save copies, you just save the the life story, or the document's timeline.

![Open-Leadership-Curriculum-Diagrams-and-Line-Art-07.png](https://lh4.googleusercontent.com/qVhOs9Zxx93AcLZ5lx_8Cpgzid0n2qwbOAhP9_47hJrrZKiQTLnB1D3BFXup3W3lB4k7F96vg988Ts6QPtNCInpVHURXdd6Hn2PwT4XOxBRZHBrUfaqApAFi564kwoP4ubFuQ8yF)

What’s on the timeline? For our purposes, let’s call any saved change a commit. The life story of your document is a timeline of commits.

![Open-Leadership-Curriculum-Diagrams-and-Line-Art-08.png](https://lh3.googleusercontent.com/jCQ9hAQOmRpoFC8Ma1cYeWkPWjDZO3JEpoXfEGDxvlN2UVbp7H9Pt4-vuuC14fkw3Fu-_pJJvBJrprZmZryLxe8_vh8qZGoZQxHHSZ6d_cpTjjxoM7MZezNqp44-emNygysqbGNL)

When we share and work on projects with collaborators, managing the changes, or commits that multiple collaborators working in different places at different times make to a single set of documents becomes very, very important.

![Open-Leadership-Curriculum-Diagrams-and-Line-Art-09.png](https://lh3.googleusercontent.com/fhQzq0KyVCM1gW4cvChCitB7XQvFk4fclo6L_AVUsUAdAkBKroBusH7hqrCS4C0LAaP7D4TDYqlwPHBtp8dvwGHR4-4kPAtV3eBRgkrfaywVaLJYUYdPfxagrqY_ifQN8QZNe4O2)

And when we’re working with multiple collaborators, everybody needs to know and understand what commits are being incorporated into the repository and why, so good communication becomes very very important. The great news is that there’s a piece of version control software to help us both manage and communicate with our collaborators about commits to our project-- that software is called Git, and it’s the basis for the online platform GitHub, where we recommend you work on your project.

### GitHub to the Rescue!

GitHub is a web-based tool originally developed by software engineers to work collaboratively on coding projects, but you don’t need to be a computer programmer to use it. GitHub has terrific project management features, a social platform, and communication tools that are useful for any project where a group of people are working together on the same set of documents. Because GitHub is online, it’s designed to share your work, and allows other people to “fork” your project-- meaning they can create an independent copy of your work to test, modify, remix and reuse it. Let's see how projects in real life (IRL) are using GitHub.

{% include videowrapper.html
  url="https://www.filepicker.io/api/file/GWtFi0eNTrO9wlLg59Xt"
  title="GitHub Projects IRL, Andre Garzia" %}

Before we go any further, let's talk for a minute about something that Andreas mentioned in his video, a piece of software called Git. Git is the command line software that powers GitHub and actually handles the version control work. When you use GitHub, Git is working behind the scenes. You can also use Git without ever using GitHub, and many software engineers do. This is what Git looks like to a user:

![](https://lh3.googleusercontent.com/p2_DZ7gP1go-UNjcb4Mk_K7ilO1Rn9vSQ7q_Kki1X795V6LbBc5035JqYJyJm4K_oa6Ax9oAWcOsNssj3495QBYen0PPDLI7dQPvIEdGnKPAJFFMJ-3i9Ls5-DKb_6LHLgcvvRk7)

**But, for nearly all your collaboration needs, you don’t won’t use the command line and Git directly.** You’ll use the GitHub web interface (with Git running in the background). That interface looks a bit friendlier, like this.

![Screen Shot 2016-01-27 at 12.35.04 PM.png](https://lh3.googleusercontent.com/ZLPBm0N15l3dgO0u5hv9_TeANzfHUM9aBbm7vmWciOJY12AmI7pu_HBYso7uEJd3VgiFnizV7TZIa0R_Ebqw4BCRypnCXdYRwHZKcadQNYlp8Bilb7VMRYyYOxUduPO-YT__XdYD)

Continue to the next module to get a closer look at the GitHub interface.