---
layout: page
title: "Sharing Your Work in The Open"
module: "4.4"
date: 2016-10-06 14:05:56
time: "60 min"
following: _articles/github-for-collaboration.md
summary: "Learn how to share your code and content for the widest possible use and reuse."
prereq: "Your project’s GitHub repo including any code, content, and data you want to share"
format: "You'll make a LICENSE file explaining how others can use your project’s code and content"
materials: "A computer and access to your project’s online repo"
---

* TOC
{:toc}

### Introduction

By sharing your work widely and with few restrictions, you allow your project to achieve its maximum impact. Your project can have positive, transformative effects far beyond what you’re able to imagine when you empower others to build on your work.

A big part of working open is sharing-- sharing the work of project creation with your community, and also sharing the results of that work with your community members and beyond. When you share your process and making ongoing work openly available on the web, others can build on your work, adapt your process or a part of your product for a novel use. This is called using an open license (traditional ‘licenses’ are restrictive, not permissive). It’s important that you think through how you want to share your work and make that information clear to anyone who encounters your project on GitHub or elsewhere on the web.

The statement of what you and your community permit in terms of sharing-- the guidelines for use and reuse is called a license. Now, while we’re not lawyers, we do strongly believe in openness, and recommend making your work as open, available and remixable as possible. Also remember that if you do not explicitly license your content differently, it generally falls under copyright and technically cannot be remixed without your permission. You may use an open license to share code, or content, or both. There are lots of licenses designed especially for sharing broadly, and organizations like Creative Commons and the Free Software Foundation have created tools and resources to facilitate sharing of content, data and code. If you’re working collaboratively on GitHub or in another common place to store your work, you’ll put the license info in your LICENSE file.

<!--- Placeholder: Sharing your work video --->

### Sharing Your Content

If your community is producing content you’d like to share-- for example learning materials, data colllected in a citizen science project, original images or artwork, a collection of blog posts, or even music files-- or if your project mixes code and other kinds of content (such as original artwork), you’ll want to choose a content license in your LICENSE.md file.

Creative Commons is a nonprofit organization that works to enable the sharing and use of creativity and knowledge through free legal tools. Creative Commons has a variety of open licenses in their [Choose a License](https://creativecommons.org/choose/) section, to help you pick the best way to credit and share the work of your project. Here are some examples of Creative Commons licenses:

*   **CC0 Public Domain** - This label essentially gifts your project into the public domain making it usable by all without restriction.
*   **CC-BY** - This license enables others use your project so long as they attribute what they use and acknowledge that the original work was done “by” you and your team. This license is most commonly used in the Open Access Movement. Here’s an [overview of Open Access](http://legacy.earlham.edu/~peters/fos/overview.htm), and you can learn more about applying its practices from [Science Commons](http://sciencecommons.org/projects/publishing/open-access-data-protocol).
*   **CC-BY-SA** - This license lets others use your project so long as they attribute it correctly and license any derivative work in the same way. They have to “share alike.” This license is commonly used by groups like Wikipedia.

You can mix-and-match the terms and conditions of CC licenses to meet your exact needs and wishes for sharing your project in the open.

![](https://lh4.googleusercontent.com/LV3WBGcXtDDDTiqOeVhp1nwX4nbQRNo0ZY0_fIrHcgvkTVua20PjCgDzBQ4a4aTiOHhYvd64InxQFV-DJpUkEN2-guMFIlOvxzHw33nw9Y-V63Sx8Ia-7vPHM9gG5QM_KJOpwQ1c)

From [Creative Commons](https://creativecommons.org)

Once you pick a license on [Creative Commons](https://creativecommons.org/choose/), you’ll get a snippet of code and text like this:

![](https://lh4.googleusercontent.com/Vss4n88Jw5L-LjUtWZJfDf3RLCjjJc8kWLkLFG6qL8I3HmZ-RAaj9VY6BlS3jYeIoAno_Labvx0caVeEBkFv1s9NauypjCAJDlczRMUNce3Sknf1tL4xDJ6rVeT31fHStnI7XZyK)

From [Creative Commons](https://creativecommons.org)

You can grab the text and link from that snippet and insert your CC license into LICENSE.md using Markdown like this:

<code>Non-software content in this project is licensed under a [Name of the license](link to the license) license.</code>

When you license your “non-software content,” you’re referring to things like your contribution guidelines, code of conduct, and any media or text that might appear on a webpage or in an app.

If you are an academic researcher collecting data, writing articles, books, and papers, or creating visualizations and other research products, you may want to explore making your work Open Access, which means making it available on the web with no restrictions to access and minimal or no restrictions on use.

<!--- Placeholder: Open Access Video --->

### Sharing Your Code

If you and your community are collaborating on code, we recommend using an open license. Open licenses for code help make clear how people can use or contribute to your work, and makes it clear to the community that it's open for remixing. To begin, you’ll need to select an open source software license (OSS). There’s a really easy way to do this, built in to GitHub. When you create a repo, GitHub gives you the option of selecting from a number common OSS licenses, and GitHub automatically generates a LICENSE.md file for you with the terms and conditions of whatever license you picked. This is a handy feature if you and your community want to share the code you create together.

Of course, you can create your own license file or edit your LICENSE.md at any time. This lets you change your license or add a license for content that isn’t code.

Visit [choosealicense.com](http://choosealicense.com/) to learn more about the different kinds of OSS licenses available for your project. The site asks you to identify your primary motivation or need for licensing your project’s code and then suggests a license to you. There are also content licenses in the [“My project isn’t software”](http://choosealicense.com/non-software/) section of [choosealicense.com](http://choosealicense.com).

![](https://lh6.googleusercontent.com/XeH5ZCcaS_MnePa2-wyiXsnJvRtcQ8031yZ_jXEj0H-UMqfhywjD13CZrm-e2kRv480tAYCMafqur0LckEcGym9aq2xaGw9q1csrXR7sbG4aLLUCZjLBkzvLZ6AZkZRo7bOrlE_b)

From [choosealicense.com](http://choosealicense.com/non-software/)

You can cut and paste the license into your pre-existing LICENSE.md file or create a new LICENSE.md file if you didn’t pick a license when you set up your repo

### {{ site.assignment }} Add a License to Your Project

1. Pick an OSS license if your project has code. (10 minutes)
  * Spend some time reading and researching the software licenses on [choosealicense.com](http://choosealicense.com/non-software/). Pick a license that makes the most sense for your project, but remember that the goal of working open is build stuff people can use, adapt, and make their own. Don’t unduly limit your project’s usefulness to your community.
  * Once you’ve picked a license, go to your GitHub repo and look for your LICENSE.md file. Make one if you don’t already have one. Copy and paste your OSS license into the file.
2. Pick a content license for the rest of your work. (10 minutes)
  * Likewise, read around the license descriptions on [Creative Commons](https://creativecommons.org/licenses/) website to get an idea of which content license serves your community best. Once you’ve picked a license, grab its name (like CC-BY 4.0) and [its link](http://creativecommons.org/licenses/by/4.0/). Add the license at the top of your LICENSE.md file like this:
    > Non-software content in this project is licensed under a [CC-BY 4.0](http://creativecommons.org/licenses/by/4.0/) license.
  * If you’re unsure about which licenses to pick for your project, take it to the community. Ask your contributors what they think is appropriate and ask your community, at-large, how they would like to be able to use the project when it is completed and released.