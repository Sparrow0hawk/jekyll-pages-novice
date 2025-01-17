---
layout: lesson
root: .  # Is the only page that doesn't follow the pattern /:path/index.html
permalink: index.html  # Is the only page that doesn't follow the pattern /:path/index.html
---

> ## Looking for Beta Testers!
> **We are currently looking for volunteers to test this lesson!**
> If you would like to teach this lesson in a pilot workshop,
> please let the lesson developers know by
> [opening a new issue on the lesson repository](https://github.com/carpentries-incubator/jekyll-pages-novice/issues/new)
> or posting to the [`#jekyll-pages-lesson` Slack channel](https://swcarpentry.slack.com/archives/C0186GK56UC)
> on [The Carpentries Slack](https://swc-slack-invite.herokuapp.com/).
> We would love to help you prepare to teach the lesson and
> receive feedback on how it could be further improved,
> based on your experience in the workshop.
{: .testimonial }

> ## Prerequisites
>
> This lesson guides you through making websites using Jekyll in a web hosting service GitHub Pages.
> If you are comfortable interacting with websites in a web browser, this lesson is for you. Basic understanding
> of HTML and/or Markdown as webpage authoring languages is welcome but not a must.
>
> There may be additional prerequisites for individual lessons in the extras section.
>
{: .prereq }

For those already familiar with the ways that Git
and an online platform like GitHub
can help them track and compare changes to flat text files,
and collaborate with others on projects,
GitHub and GitLab Pages provide a cost-free way to
build and host webpages.
This approach is commonly used to provide documentation
on software projects,
and to create blogs and websites for
individuals and organisations already used to working with
the Git/GitHub toolset for their other projects.
However, for those taking their first steps towards building sites like this,
the process can be confusing and intimidating.
This tutorial aims to address this,
by providing a step-by-step guide to creating a collection of pages
and combining them into a coherent site using a framework called _Jekyll_.

> ## Outdated Screenshots
>
> Throughout this lesson we will make use and show content and screenshots from GitHub.com.
> As an ever evolving platform, GitHub is always adding new features
> and new visual elements to its website.
> **Screenshots** in the lesson may then become out-of-sync, refer or show content that no longer exists.
>
> If during the lesson you find **screenshots** that no longer match what you see in your browser,
> please [open an issue][github-jekyll-issues] describing what you see and how it differs from the lesson content.
> Feel free to add as many screenshots as necessary to clarify the discrepancy.
{: .callout }

## Target Audience

**Anita** is a newly-certified Carpentries instructor.
A librarian for the biology library at her institution,
she learned to work with HTML when she did her masters in library science.
Since grad school, she has been picking up other coding skills and has recently learned R.
The Carpentries instructor who taught her R encouraged her to take Carpentries Instructor Training.
She has never used Git before but wants to help edit the Carpentries teaching material and create new lessons
on topics she thinks would be useful for the students and staff she works with.
After working through this lesson Anita will be comfortable using Github to modify the Carpentries lessons,
playing with her own Jekyll pages repository, and eventually making her own lessons using the Carpentries lesson template.

**Arjun** is a third-year PhD student studying atmospheric chemistry.
He uses Python in his research every day and keeps all his scripts and files under version control with Git.
His supervisor is a new group leader and Arjun was the first PhD student she recruited.
Now that her lab has begun to publish the results of their research,
she has tasked Arjun with setting up a website for the group.
The time and budget the group has for developing and maintaining the site are limited,
and Arjun wants to make sure his labmates can access and edit the pages.
He has seen some other labs use GitHub Pages to host their websites
and thinks this is a good opportunity to put his Git skills to work.
After following this lesson, Arjun will be able to create and maintain the structure of the lab website through GitHub Pages,
and begin teaching his colleagues how to collaborate on the content.

**An** is in the final months of her Masters program in Digital Humanities.
During her six-month lab internship, she started using a couple of tools available on GitHub, and became familiar with the interface.
She has really enjoyed this part of the internship and other technical aspects of her Masters and now wants to find work in digitization of rare books and other written material.
She wants to increase her online profile as she enters the job market, and she knows that a personal website and online CV are a good place to start with this.
An still needs to finish writing her thesis and doesn't have a lot of time to spare for creating a website from scratch, nor a lot of money to pay for hosting, domain names, and so on.
This lesson will teach An how to find and use an existing template to create her personal webpage and online CV,
how to write formatted text and insert images to highlight the skills she has picked up, and how to host those pages online for free.

> ## Learning Objectives
>
> After following this lesson,
> learners will be able to:
>
> - **create** formatted page content with Markdown
> - **configure** their project to build and serve pages on GitHub
> - **build** a coherent site with multiple pages using the Jekyll framework
> - **customise** the layout and style of the pages on their site
>
{: .objectives }

{% include links.md %}
