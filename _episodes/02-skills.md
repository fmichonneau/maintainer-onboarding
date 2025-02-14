---
title: "Building Maintainer Skills"
teaching: 10
exercises: 45
questions:
- "What is the role of a Maintainer in interacting with contributors?"
- "What is The Carpentries etiquette for working with GitHub?"
- "What types of issues and PRs am I likely to see and how should I handle them?"
objectives:
- "Apply The Carpentries pedagogical principles to curricular decision making and interactions with contributors."
- "Use the GitHub flow contribution model and Carpentries GitHub etiquette to contribute to Carpentries lessons."
- "Recognize complications involved with different types of PRs and practice dealing with difficult PRs diplomatically."
keypoints:
- ""
---

> ## Preparatory Homework
> Read ["Learning to Say No"](https://opensource.guide/best-practices/#learning-to-say-no). Be prepared to discuss how you can implement these suggestions as a Maintainer.
{: .prereq}

> ## Preparatory Homework
> Read the episode on [Motivation and Demotivation](http://carpentries.github.io/instructor-training/08-motivation/)
> from Instructor Training. Make some notes for yourself about
> how the factors discussed in this episode should influence the
> way we interact with contributors.
{: .prereq}

> ## Preparatory Homework
> Read The Carpentries [Contributor Guidelines](https://github.com/carpentries/maintainer-onboarding/blob/gh-pages/CONTRIBUTING.md). 
> How might these guidelines influence how a contributor contributes to your lesson?
{: .prereq}

> ## Instructor Note: Responding to Minute Cards
> Take a few minutes at the beginning of the session to acknowledge that you have reviewed
> the Minute Card feedback and address a few of the common questions. This will encourage 
> individuals to continue to fill them out!
{: .callout}

> ## Initial Thoughts (5 min)
> What is something new you learned from the readings? If you didn't learn something new, 
> what is an idea that you found compelling, hope to implement, or already use as a Maintainer?
{: .challenge}

## Interacting with Other Contributors

Maintainers represent The Carpentries on some of our most
active online spaces - our GitHub repositories. As a Maintainer,
you will often be the first point of contact for people new to The
Carpentries community.

Igor Steinmacher, a computer scientist who researches
retention of open source contributors, provides [a set of
recommendations](http://wsl.softwarelivre.org/2015/0002/fostering-freelibre-open-source-software-community-formation:-guidelines-for-communities-to-support-newcomers-onboarding-wsl-2015.pdf) based on his research on how to reduce barriers to
new contributors becoming part of your community. While some of these
are more specific to software projects, some are very applicable to
our (or any) community:

* Answer quickly
* Be kind and make newcomers feel part of the team
* Set expectations and needs early
* Point newcomers to easy tasks
* Keep the issue list clean and triaged
* Dismiss or identify outdated information
* Create a live FAQ section

How do you feel the Carpentry community does overall in meeting these recommendations? Can you identify ways in which we could improve?

> ## Discussion (10 min)
> In breakout groups, discuss any of the following questions based on your pre-readings. Please make sure you are taking notes in the Etherpad:
> * How can you balance saying no and being inclusive? What practices can help with this?
> * How might the factors discussed in the Motivation and Demotivation episode of Instructor Training influence the way we interact with contributors?
> * How might the contributing guidelines influence how a contributor contributes to your lesson? How can you use them effectively as a Maintainer?
> * How might you implement the suggestions in “Learning to Say No” as a Maintainer?
> This discussion should take around 10 minutes.
>
> > ## Solution
> > * Teach Most Useful First - we can (and should) politely turn down contributions that take the material out of the scope of the novice learner or that involve unnecessary and distracting technical detail.
> > * Actual Time - everything will probably take longer for learners than it does for you. Limit new additions to the materials and encourage cutting material where needed.
> > * Things You Shouldn't Do in a Workshop - these are also things we shouldn't do in a PR or Issue conversation.
> > * Imposter Syndrome - be encouraging to new contributors, even if they make a formatting mistake.
> > * Accessibility - take seriously any comments a contributor makes about accessibility issues.
> > * Inclusivity - avoid unnecessary use of gendered pronouns and other exclusive language.
> {: .solution}
{: .challenge}

When interacting with contributors, whether new or old, we want to
be sure to embody [The Carpentries values](https://carpentries.org/values/) around communication and teaching
and learning. Part of doing so includes communicating appropriately on Github.

## GitHub Etiquette and Processes

In addition to formal [contributor guidelines](https://github.com/carpentries/maintainer-onboarding/blob/gh-pages/CONTRIBUTING.md), The Carpentries have a set of community norms for working with
GitHub. These include:

* **Including appropriate cross-references:**
    If putting in a PR to address an existing Issue, include a link to the Issue. GitHub will automatically add a note to the Issue linking back to the PR. This is also good practice when communicating in conversation threads on related Issues and PRs.

* **Using the `@` symbol to tag people in a conversation:**
    Most people don't subscribe to all of The Carpentries repositories (there are a lot!) and will only get email alerts if their GitHub handle is tagged. This is a good way to make sure relevant people are included in the conversation.

* **Requesting reviews:**
    You can request a review from a fellow Maintainer or from someone else who has been active on the repository. This is another way of including relevant people in the decision-making process.

* **Not merging your own PRs:**
    Even for small PRs, it's a good idea to have a second pair of eyes to check for typos and formatting issues. In general, always get a second opinion before merging your own PR. This is a good time to request a review.
    
* **Tagging issues with descriptive labels:**
    For community-submitted issues, remember to add appropriate labels, even if you are not going to immediately take action. This shows contributors that issues are being paid attention to and encourages others to take action on issues.

> ## How to Label Issues
> To find a list of issue labels, their corresponding meanings, and when to use each, 
> take a look at this guide on [How to label issues](https://docs.carpentries.org/topic_folders/maintainers/github_labels.html) in The Carpentries handbook. 
> The guide also includes instructions on how to populate a Github repository with these issues.
{: .callout}

Being open to new contributions while keeping the lessons sleek and
teachable is a difficult balancing act. It's ok to say no to a
contribution when it doesn't add anything useful to the materials,
goes beyond the scope of the lesson, or introduces unnecessary
complexity. Even when saying no, however, we want to have positive
interactions with contributors and let them know that their
involvement is valued. GitHub's [OpenSource Guide for Maintainers](https://opensource.guide/best-practices/#learning-to-say-no)
has an excellent discussion on learning to say no.

> ## Lesson Maintenance Demo, pt 1 (5 min)
> We will demonstrate briefly how one might respond to a (sample) issue on a lesson.
> At what points during the demo did we use proper Github etiquette? What could have been improved?
{: .challenge}

> ## Lesson Maintenance Demo, pt 2 (5 min)
> We will demonstrate again how one might respond to a (sample) issue on a lesson.
> At what points during the demo did we use proper Github etiquette? What could have been improved?
{: .challenge}

## Types of Changes

A common question from Maintainers is whether they have the authority to implement certain
types of changes and who should be involved in the decision-making process. Roughly
speaking, we can break down types of changes into three main categories:

- **Typos and minor wording changes**
    These can be implemented immediately after review by a single Maintainer.

- **Introduction of new material to a lesson**
    A decision to implement these changes (or not) should be made by at least two members of the Lesson Team. The first 
    Maintainer to review the change leaves a comment indicating whether it should be approved (we often use the comment "LGTM" 
    (looks good to me) to indicate approval). The second Maintainer to review can either merge (if both have approved the 
    changes) or suggest revisions. Or, if they disagree with the spirit of the change, they should leave a comment explaining 
    why, and allow some time for the contributor, the first approver, or anyone else to respond before closing the PR.

- **Large-scale changes to the structure of the lesson**
    Examples of this would be changing from base R to tidyverse for teaching R, changing from ggplot to matplotlib for plotting
    in Python, or introduction of new tools like a different variant caller for the Data Carpentry Genomics lesson. 
    A decision of this scale
    should involve a broader conversation with the community.

Some lessons have a [Curriculum Advisory Committee](https://docs.carpentries.org/topic_folders/lesson_development/lesson_development_roles.html#curriculum-advisory-committee).
These Committees are responsible for guiding the overall direction
of the curriculum, including any proposed large-scale changes. As of May 2021, the Curriculum Advisory Committees are
on hiatus and are scheduled to be reintroduced in September 2021. While Curriculum Advisors are on hiatus, and for
lessons without a Curriculum Advisory Committee, decisions about large-scale changes to the lessons are made via conversations
in GitHub
repos, on The Carpentries [TopicBox lists](https://carpentries.topicbox.com/), and other communication channels.

> ## Exploring Issues (15-20 min)
> You will be placed in a breakout group with members of your Lesson Team. 
> Open the GitHub repo for your lesson and navigate to the `Issues` tab. 
>
> **First**, select an issue that has been open for less than 6 months with your group and decide which of the above categories it fits into. 
> Add a comment describing your group's suggested action/follow-up on at least one issue. 
> Be sure to tag any involved parties.
>
> **Next**, with your breakout group, select one PR or Issue that has been
> open for > 6 months. Read the comments and discuss what the problem
> is (i.e. why hasn't the PR been merged). Draft a response to the
> PR/Issue in the Etherpad. If you're comfortable doing so, add your
> response to the conversation and tag the other Maintainers for the lesson.
{: .challenge}

> ## Instructor Note: Minute Cards (5 min)
> Have Maintainer Onboarding participants fill out Minute Cards to collect feedback on the session.
{: .challenge}
