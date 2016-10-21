---
layout: page
title: "Getting Around in GitHub"
module: "5.1"
date: 2016-10-06 14:05:56
time: "10 mins"
following: _articles/github-for-collaboration/collaborative-workflow-for-contributions.md
summary: "This module will help you understand how and where you and your collaborators will save changes and any work on a collection of files (a repository) when using gitHub."
prereq: "Have completed all previous sections and modules"
format: "Read and look at diagrams"
materials: "None"

---
* TOC
{:toc}

### Repos, Forks, and Branches, Oh My!

What's special about Git and GitHub is that every instance or copy of a repository (or collection of files) has its full life history, the full timeline of changes bundled with it. When you’re working with GitHub, you may have multiple copies of the same repository in use at once, and it’s helpful to understand how that works, and why. Let’s take a moment to understand how this works, starting with the simplest scenario.

If you're working alone you might use version control on a single repository on your local computer. Here’s a diagram that illustrates that scenario:

![Open-Leadership-Curriculum-Diagrams-and-Line-Art-10.png](https://lh6.googleusercontent.com/ylFY_bZygXEAUq7faPluylRBp9BR-CT7TE11xnEoonRd0QnxcE-jXzDLKCZJo21bE5hj37nzb_e6zktHcigv_XInUivAmCpeqKS2X1Dpke-loQb6bVpKJG51uvbr5UYKwX8i6bKv)

Every save or commit you make is tracked and we can step back and forth between versions.

This is great! But what if you have a crazy new idea you want to try out, that you’re excited about but not sure will work. You might make a whole boatload of changes that could take your project to amazing new levels-- OR totally break everything you’ve done so far. To experiment with your repository without permanently altering it, you can use a special feature enabled by GitHub (and the underlying technology Git) to create a copy or branch of your existing code that has all the functionality of the original, but is still connected to the original (it’s not a separate duplicate or clone), which is called the master branch.

This concept of branching is a bit tricky to explain. For a metaphor, you can imagine a river. This river is just flowing along, but every once in awhile, there might be a stream that flows out from the river in a new direction-- let’s call this a new branch. This new branch is doing its own thing. It may flow along with lots of twists and turns but go nowhere and just peter out... or it may splash along and then join up and flow into the river again somewhere down the line.

Back in your repository, your new experimental branch (which contains a copy of all your code or content) is connected to the master branch (also containing code and content) in the same way as our stream is connected to the river. In your new branch (the stream), you make all sorts of great changes, and if they work out, you can choose to merge (or flow) them back into the master branch (the river). Our new branch and the master branch are always connected, and part of the same project.

If you’ve got lots of new ideas, you can make lots of branches. This concept of branching allows you to work in many new directions without altering your code or content base in the master branch until you are ready.

But what about sharing your files? You can’t do that if they are only stored your own, local computer. You need GitHub! To get your files on GitHub, you’ll make a copy or clone of your local repository and upload it to GitHub. When you put a repository on GitHub, it’s stored on GitHub server, so anyone can find them on the web. An added benefit is that the clone on GitHub serves as a backup of your local repository, in case the files on your own computer catch a virus, get lost, or are accidentally erased. To work with this repository, you’d most likely make changes to the files on your local machine, using your favorite text or code editor. Then you’d PUSH those changes as commits to the copy of the repo on the server. Your local copy of the repo and the one on the server are in sync, and you have a stable, reliable back-up.

![Open-Leadership-Curriculum-Diagrams-and-Line-Art-11.png](https://lh3.googleusercontent.com/cphihMu1zjZlAsuA5dxo1hbrpiBIPaGoVwX38KqaW6NJ7_YlRdJFG4fvXEbgp8qYMhGdQZ7_16gQka_dSY2OjqDwHHecGm0_REQvsR-O2b-aE4MEy6OJ-XyjkWnQRiwRmhHWXjTs)

This method where you’re working locally and pushing changes to the server is pretty simple. It gets a teeny bit more complex when you have lots of contributors. Luckily, and this is where GitHub really shines.

To work with contributors, you need to designate a main repo, hosted on GitHub. This repo that contains all the project code, content, and changes your community agrees should be part of the project. There's nothing structurally different or special about this repo (since all repos contain a full history of changes), it's just the one all your contributors agreed to use. We’ll call this repo the main repo.

![Open-Leadership-Curriculum-Diagrams-and-Line-Art-12.png](https://lh6.googleusercontent.com/Luq9N7LHpv8KMf4pFLnS9Wni2PeLt7ulIEbW4wh4log9235dgNOySPOro3X-q1Oao_znDlTRGj33k3EEWQA_NIES7F6gIY5ZUUtvKfzcEW-zfHa7NnK-iwS133sTmXHF4E2rmx_G)

Usually in this workflow, each collaborator makes their own local copy or clone of the main repo, so they can work and make changes locally. In addition, they may make a BRANCH in their clone of the main repository. ![Open-Leadership-Curriculum-Diagrams-and-Line-Art-13.png](https://lh5.googleusercontent.com/JqyTz_ULhjJzvNtwXqwOlDBmfzlcK3lk18Ps4eNwStGIk5tM1Gpg167IMq4YMsWXQ4_Ro1_9ZVT2tu5VrEsyjzYvk_5Kkb2RR34uXT1Mpzl455AYSmuh83tr89Y2pSNBvj8dA4T2)

Work on a collaborator’s branch won't change anything in the main repo until the collaborator makes what's called a pull request, a request for the main owner of the repo to incorporate the changes from the branch. The project lead or owner (that’s you!) will review the changes and may decide to merge them into the master branch. A collaborator working on a branch is working along with, in the same direction as everyone else on the master branch, and communicating about their work within the context of that repo.

![Open-Leadership-Curriculum-Diagrams-and-Line-Art-14.png](https://lh5.googleusercontent.com/I5AnTX_uXcppmAcChH0hCAjqWMa8zMfgSCpxBokciF2hmgUn2N1eiHjxNPQ-joObxifZZWqnR_yrGvVsInlsm6q8CshE1xvudniLVg_iqlaBOaLT_C0hw5Xkn47Hppz9CAxoUB0k)

A collaborator might make a complete copy of a master repo from another user’s account and bring it into their own account-- this is called a fork. A fork is a complete copy of a repo made from one user’s account to another account, often for repurposing or independent work.

![Open-Leadership-Curriculum-Diagrams-and-Line-Art-15.png](https://lh6.googleusercontent.com/ulru10eSxqfjrhdnD3g7Ve3OCyhIA-CfAQDDr7NOd4FWue4K9l3HkZtckcf-8u9uSICeUghZL_Io82evKwgIKblcEGasYs2gg0dxjJHZUPooSV7Q0az2jQQhypCaingKO1LTOjG4)

People often fork when they are going to take the content or code and repurpose it or take it into a completely different direction. The project lead will have specified what can and can’t be done with the original work in a the project license (refer back to module 4\. 5 for a refresher on licensing). When a project is forked, work and decisions happen independently, outside of the context of the original or upstream repo, independently, in the new fork. Now that you’ve got some sense of how and where work happens in GitHub, head to the next section to practice a collaborative workflow.