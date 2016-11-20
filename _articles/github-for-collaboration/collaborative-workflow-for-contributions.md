---
layout: page
title: "Collaborative Workflow"
module: "5.2"
date: 2016-10-06 14:05:56
time: "60 mins"
following: _articles/open-communications.md
summary: "In this module, you’ll be introduced to a good, open, welcome workflow for collaboration on GitHub. You’ll get some tips for good GitHub communications, and you’ll practice making and managing changes to repositories… You’ll play the role of both Project Lead and contributor. Get ready to make and merge your first pull requests!"
prereq: "Have completed all previous sections and modules"
format: "Read, watch videos, and work with GitHub in two roles: as a contributor, and as a project lead"
materials: "Your computer, GitHub account, your own project—  plus someone else’s project you’ll contribute to!"
---
* TOC
{:toc}

### Collaboration as Conversation

Good collaboration is a back and forth process, like a conversation, or a call and response. It’s not complicated, but you need to know the steps and the roles for contributor and lead. The series of videos below walks you through a workflow for collaboration on open projects, and demonstrates good communication with contributors. Watch closely, because you’ll be doing these steps (and playing both roles) yourself in the assignments at the end of this module! We’ve included screenshots in the assignment section to help you along.

<!--- Placeholder for video: collaborative workflow --->

If you master this workflow and practice it in your community, contribution can happen more smoothly and be more satisfying for all involved. You, the project lead, need to move this whole process forward! These handy tips should help.

*   Acknowledge when a new issue is posted by a contributor (remember, both contributors and project leads can post issues!)
*   Notify users when you start and finish work
*   Summarize the state of the issue
*   Give periodic status updates
*   Inform everyone if you slip
*   Inform everyone if you’re on track
*   Make responsibility handoffs clear
*   Notify when new functionality is added to the project, and when fixes are made
*   Always use friendly tone and correct grammar to increase legibility
*   Talk to users on their terms, follow their cues

### Writing Great Messages and Comments on GitHub

Your communications on GitHub don’t need to be literary masterpieces, but it’s really helpful if they are clear and well-written. Remember the history of your document is a timeline of commits. Each "commit message" is the backstory of your changes. A good, comprehensible, useful "commit message" is one that fills in that story. It lets collaborators and the project owner/lead know what you've done, what changes you’ve made, what you’ve added. This includes your own commits as project lead. While you might know the ins and outs of any change you made at the moment, in 5 days or 5 weeks or 5 years, those details will probably have slipped your mind. A detailed commit will capture that information forever.

When you’re writing commit messages, you’ll want to make them short, clear, and in a fairly uniform format so they're easy to read. Here are a few rules for writing messages like these, taken from this excellent blog post, [How to Write a Git Commit Message](http://chris.beams.io/posts/git-commit/), by Chris Beams. Read the post to learn about the rationale behind each rule.

1.  Separate subject from body with a blank line
2.  Limit the subject line to 50 characters
3.  Capitalize the subject line
4.  Do not end the subject line with a period
5.  Use the imperative mood in the subject line
6.  Wrap the body at 72 characters
7.  Use the body to explain what and why vs. how

Here is an example to illustrate the above points:

```
Add example commit message to collab workflow lesson

An example of what a nice commit message looks like to make the points from
the lesson text more concrete.
```

### {{ site.assignment }} As a Contributor, Make a Pull Request

1.  Find a project you’d like to contribute to and check out the README
2.  Read the contributing.md file and code of conduct
3.  Familiarize yourself with the project’s roadmap
4.  Review the issues and pick one-- ideally a “good first bug” that you can take on
5.  Comment on the issue, be sure to ask if you have any questions about the task
6.  Follow the contributor guidelines
    1.  Fork the repo
    2.  Make a branch
    3.  Make a commit
    4.  Write a great commit message
    5.  Make a pull request!

*Switch to your branch containing the changes*  
![New Pull Request]({{ site.baseurl }}/img/create-pull-req-1.png)

*Compare your changes with the remote branch*  
![Compare Changes]({{ site.baseurl }}/img/create-pull-req-2.png)

*Provide a title and a description for your pull request*  
![Create Pull Request]({{ site.baseurl }}/img/create-pull-req-3.png)

### {{ site.assignment }} As Project Lead, Merge a Pull Request

Follow the steps described for as project lead

1.  Make a label
2.  Make an issue for a good first bug
3.  Let your community know about this issue!
4.  Reply to Comment
5.  Wait for Pull request
6.  Review pull request, and be sure to provide useful feedback and encouragement
7.  Merge pull request
8.  Thank your contributor!
9.  Close the issue! Woo-Hoo!
