---
layout: page
title: "Open Project Maintenance"
module: "8.1"
date: 2016-10-06 14:05:56
time: "60 mins"
following: _articles/open-leadership-outro-and-next-steps.md
summary: "Create a maintenance plan to prolong the life of your project and keep it accessible for your community and others."
prereq: "Your community project and its documentation and materials in your GitHub repo"
format: "You'll complete a project in GitHub."
materials: "Access to your GitHub project repo"
---
* TOC
{:toc}


### Mentorship as Maintenance

Imagine reaching the end of your project. You've shipped an open source product to a community of users who helped build it.

It's a natural time to ask, "What's next?" However, your project still needs your attention if it's to remain functional and useful in the long term. Maintenance of your open project is essential to its longevity and and is needed in order to be adopted by communities similar to yours.

Mentorship in an important, but often overlooked a next step. Maintaining your project is as much about keeping its technology fresh - or at least functional - as it is about continuing your relationship with your contributors. As an open leader, you should continue to find ways to support them even after the official end of your shared project. Perhaps your next step is to mentor someone who wants to become an open leader, as well, and to serve as a contributor on their project.

This draft of a [mentorship rubric](https://github.com/MozillaFoundation/curriculum-workshop/blob/master/march-8-2016/g-doc-transcript.md) for women mentors came out of the inaugural [Mozilla Curriculum Workshop](https://teach.mozilla.org/community/curriculum-workshop/) webcast on International Women’s Day. Consider forking or cloning it into your own GitHub repo and developing its guidelines further for your own mentorship work with community members.

[![](https://lh4.googleusercontent.com/_4h4xPUhInqRys3fyQ_45hnrSg9A24UxqPec-a3wc_ZuDLlg0m6moNQgXgX1t_s-ggRkjvQ8HvxqKMl04REyKwzvKvlzagU4WXRVR8oTNi1GSfsefL2SaeFoeXQMQozEbHst3m-h)](https://github.com/MozillaFoundation/curriculum-workshop/blob/master/march-8-2016/g-doc-transcript.md)

What would you add to those guidelines? What kind of mentorship practices should you adopt to help others, but also push yourself forward as a leader and community support? As a mentor, how would you use guidelines like these to help acclimate a mentee to the culture, contribution guidelines, and code of conduct for your project?

You can also help your contributors move along the “committment curve” to deepen their engagement with, and contribute to your project. Check out [this curve from the A-Team Bootcamp](http://ateam-bootcamp.readthedocs.io/en/latest/guide/curve.html) to help you consider how community members can “level-up.”

### Maintaining the Stuff

GitHub is a fine place to host your project as it enters maintenance mode; depositing your work and documentation in this kind of repository keeps its available for others to fork, clone, adapt, and improve over time. You don't need to update your project every day, but you should be able to update it when people offer suggestions or make pull requests through Git. You should also expect some questions or even requests for assistance from users who discover your project online and want to localize it for their communities.

As a first step in drafting and implementing your project maintenance plan, audit your documentation to see if there are parts of your project that aren't adequately explained. Be sure to fill in any gaps in documentation so potential users know which parts of your project do what and how they do it.

Consider setting aside a certain amount of time per week or month to check in on your project and with your community via your project's GitHub issues. If your project has a website hosted on GitHub Pages or another sever, keep the contact information on that site up to date. If your project collects user-data, review what gets collected frequently to make sure the data comes through in a useful format and doesn't expose private or sensitive information to anyone visiting your repo. In general, plan to check in on your project frequently enough to make sure it's working correctly and accessible to anyone who needs it.

Additionally, draft and upload documentation to your repo, outlining your plan for project maintenance. Take feedback from project participants and contributors and consider recruiting a volunteer with whom you can share maintenance duties.

For live communication between you and your contributors, set up a chat room through a service like [IRC](https://developer.mozilla.org/en-US/docs/Mozilla/QA/Getting_Started_with_IRC), [Gitter](https://gitter.im/), or [Mattermost](http://www.mattermost.org/) where people can ask questions and connect.

If your project makes heavy use of open data, check out [this presentation on Open Data Reuse](https://docs.google.com/presentation/d/1kZd-ZD5lru5a7jIbyi9q8cBYCCAKRnIBSRvixYFtoF0/edit?pref=2&pli=1#slide=id.g1088c5b110_0_72) from the [Mozilla Science Lab](https://mozillascience.org/). You'll want to ensure that your data "is made easily and freely available for anyone to access, use, and share without restriction" while addressing how you approach human data use, data ownership, and data formatting through your documentation.

If your project makes use of a particular open code-base for data visualization, web development, or any other kind of scripting, you'll want make such dependencies clear in your documentation and in the comments of your coded products. Part of your maintenance plan should be checking for updates for any of the APIs, coding languages, or libraries you use in your project and implementing them to keep your work as accessible as possible for others.

Finally, think about how you might deprecate, or stop supporting, your project if it outlasts its usefulness to its users. Is there a way to share its content and documentation even after it stops working? Can you turn the project over to new maintainers in the project community? How will its ultimate form the work you and your community members did create it?

### Questions to Consider

To help draft your maintenance plan and sustain your project, answer questions like these.

**Logistical**

*   Which parts of your documentation do you need to maintain or update?
*   Which parts of your content or codebase do you need to maintain or update?
*   How often should you perform maintenance on your repo?

**Interpersonal**

*   How will you identify and recruit community members who want to help maintain the project?
*   How will you decide when to end maintenance?
*   How will you keep your project’s documentation and content or codebase discoverable and functional enough to help communities that need and find it?


### {{ site.assignment }} Audit Your Documentation and Fill in the Blanks
(30 minutes)

Read through the GitHub documentation for your project. Look for gaps in your documentation and fill-in-the-blanks with new documents that provide explanations for how you and the community implemented pieces of work that are missing initial documentation. Also clarify anything that sounds clunky or jargony so it's clear to the most diverse audience of users possible. Finally, update anything in the documentation that's changed in the course of your project.

### {{ site.assignment }} Create a Maintenance Plan and Add it to GitHub
(15 minutes)

Draft your maintenance plan and share it with your community on GitHub. Your plan should describe:

*   Who is responsible for which parts of the plan.
*   Expected time commitments from each person or for each role.
*   How you and your team will maintain your technology and fix bugs.
*   How you and your team will maintain your data.
*   How you and your team will help others fork and use your project.
*   How and when you and your team will deprecate or sunset and archive your project.
*   How you and your community will stay in touch during the maintenance phase of your project.

Upload it to your repo and invite comments, suggestions, and pull requests that might improve it or cover any blind-spots you had while writing it. Survey contributors to see if any of them would like to volunteer to help maintaining the project in the long-term.

### {{ site.assignment }} File Issues and Set Milestones for Your Check-Ins
(15 minutes)

Finally, add new issues and milestones in GitHub that reflect the steps and scheduling in your maintenance plan. Build on the trust you and your community established in creating the project by stewarding and updating it to ensure its longevity and reliability. Your project is an example of leading and working in the open that can inform and inspire other communities and projects in the future.