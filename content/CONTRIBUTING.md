# Contributing to NEGI-Abisko-2019


Welcome to the `NEGI-Abisko-2019` repository! We're excited you're here and want to contribute.

These guidelines are designed to make it as easy as possible to get involved.
If you have any questions that aren't discussed below, please let us know by opening an [issue][link_issues]!

Before you start you'll need to set up a free [GitHub][link_github] account and sign in.
Here are some [instructions][link_signupinstructions].

Already know what you're looking for in this guide? Jump to the following sections:

* [Joining the conversation](#joining-the-conversation)
* [Contributing through Github](#contributing-through-github)
* [Understanding issues, milestones, and project boards](#understanding-issues-milestones-and-project-boards)
* [Making a change](#making-a-change)
* [Structuring contributions](#style-guide)
* [Recognizing contributors](#recognizing-contributions)

## Joining the conversation

`NEGI-Abisko-2019` repository has been setup for the 3rd course “Climate science at high latitudes: eScience for linking Arctic measurements and modeling” that will be held at Abisko Scientific Research Station from 15th until 24th of October 2019.

We're excited to have you join!
Most of our discussions will take place on open [issues][link_issues].

As a reminder, we expect all contributors to `NEGI-Abisko-2019` to adhere to the [Carpentries Code of Conduct][link_coc] in these conversations.

## Contributing through GitHub

[git][link_git] is a really useful tool for version control.
[GitHub][link_github] sits on top of git and supports collaborative and distributed working.

You'll use [Markdown][markdown] to chat in issues and pull requests on GitHub.
You can think of Markdown as a few little symbols around your text that will allow GitHub
to render the text with formatting.
For example you could write words as bold (`**bold**`), or in italics (`*italics*`),
or as a [link][rick_roll] (`[link](https://https://youtu.be/dQw4w9WgXcQ)`) to another webpage.

GitHub has a helpful page on
[getting started with writing and formatting Markdown on GitHub][writing_formatting_github].


## Understanding issues, milestones and project boards

Every project on GitHub uses [issues][link_issues] slightly differently.

The following outlines how the `jupyter-book` developers think about these tools.

**Issues** are individual pieces of work that need to be completed to move the project forwards.
A general guideline: if you find yourself tempted to write a great big issue that
is difficult to describe as one unit of work, please consider splitting it into two or more issues.

Issues are assigned [labels](#issue-labels) which explain how they relate to the overall project's
goals and immediate next steps.


### Issue labels

The current list of labels are [here][link_labels] and include:

* [![Help Wanted](https://img.shields.io/badge/-help%20wanted-159818.svg)][link_helpwanted] *These issues contain a task that a member of the team has determined we need additional help with.*

    If you feel that you can contribute to one of these issues, we especially encourage you to do so!

    * [![Good First Issue](https://img.shields.io/badge/-good%20first%20issue-blueviolet.svg)][link_helpwanted] *These issues contain a task that a member of the team thinks could be a good entry point to the project.*

        If you're new to the `jupyter-book` project, we think that this is a great place for your first contribution!

* [![Bugs](https://img.shields.io/badge/-bugs-fc2929.svg)][link_bugs] *These issues point to problems in the project.*

    If you find new a bug, please give as much detail as possible in your issue, including steps to recreate the error.
    If you experience the same bug as one already listed, please add any additional information that you have as a comment.

* [![Enhancement](https://img.shields.io/badge/-enhancement-84b6eb.svg)][link_enhancement] *These issues are asking for enhancements to be added to the project.*

    Please try to make sure that your enhancement is distinct from any others that have already been requested or implemented.
    If you find one that's similar but there are subtle differences please reference the other request in your issue.

* [![Question](https://img.shields.io/badge/-question-DE8BE7.svg)][link_question] *These are questions that users and contributors have asked.*

    Please check the issues (especially closed ones) to see if your question has been asked and answered before. 
    If you find one that's similar but there are subtle differences please reference the other request in your issue.

## Making a change

We appreciate contributions from all assistants, teachers and students to `NEGI-Abisko-2019`, but those accepted fastest will follow a workflow similar to the following:

**1. Comment on an existing issue or open a new issue referencing your addition.**

This allows other members of the Abisko core team to confirm that you aren't overlapping with work that's currently underway and that everyone is on the same page with the goal of the work you're going to carry out.

[This blog][link_pushpullblog] is a nice explanation of why putting this work in up front is so useful to everyone involved.

**2. [Fork][link_fork] the [NEGI-Abisko-2019 repository][link_abisko-repo] to your profile.**

This is now your own unique copy of NEGI-Abisko-2019.
Changes here won't effect anyone else's work, so it's a safe space to explore edits to the code!

Make sure to [keep your fork up to date][link_updateupstreamwiki] with the master repository.

**3. Make the changes you've discussed.**

Try to keep the changes focused.
We've found that working on a [new branch][link_branches] makes it easier to keep your changes targeted.

**4. Submit a [pull request][link_pullrequest].**

A member of the development team will review your changes to confirm that they can be merged into the main code base.
When opening the pull request, we ask that you follow some [specific conventions](#pull-requests).
We outline these below.

### Pull Requests

To improve understanding pull requests "at a glance", we encourage the use of several standardized tags.
When opening a pull request, please use at least one of the following prefixes:

* **[DOC]** for new or updated documentation
* **[JNB]** for new or updated jupyter notebook
* **[ENH]** for enhancements
* **[FIX]** for bug fixes
* **[REF]** for refactoring existing code
* **[STY]** for stylistic changes

You can also combine the tags above, for example if you are updating both a test and
the documentation: **[STY, DOC]**.

Pull requests should be submitted early and often!

If your pull request is not yet ready to be merged, please open your pull request as a draft.
More information about doing this is [available in GitHub's documentation][link_drafts].
This tells the development team that your pull request is a "work-in-progress",
and that you plan to continue working on it.

When your pull request is Ready for Review, you can select this option on the PR's page,
and a project maintainer will review your proposed changes.


## Recognizing contributors

We welcome and recognize all contributions from documentation to testing to code development.
You can see a list of current contributors in the [contributors tab][link_contributors].

## Thank you!

Thank you for sharing your codes, documentation, jupyter notebooks, etc.

<br>

*&mdash; Based on contributing guidelines from the [STEMMRoleModels][link_stemmrolemodels] and [Jupyter Book][link_jupyterbook] projects.*

[link_git]: https://git-scm.com
[link_github]: https://github.com/
[link_abisko-repo]: https://github.com/NordicESMHub/NEGI-Abisko-2019
[link_signupinstructions]: https://help.github.com/articles/signing-up-for-a-new-github-account

[writing_formatting_github]: https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github
[markdown]: https://daringfireball.net/projects/markdown
[rick_roll]: https://www.youtube.com/watch?v=dQw4w9WgXcQ
[restructuredtext]: http://docutils.sourceforge.net/rst.html#user-documentation
[sphinx]: http://www.sphinx-doc.org/en/master/index.html
[readthedocs]: https://docs.readthedocs.io/en/latest/index.html

[link_issues]: https://github.com/NordicESMHub/NEGI-Abisko-2019/issues
[link_coc]: https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html

[link_labels]: https://github.com/NordicESMHub/NEGI-Abisko-2019/labels
[link_bugs]: https://github.com/NordicESMHub/NEGI-Abisko-2019/labels/bug
[link_helpwanted]: https://github.com/NordicESMHub/NEGI-Abisko-2019/labels/help%20wanted
[link_enhancement]: https://github.com/NordicESMHub/NEGI-Abisko-2019/labels/enhancement
[link_question]: https://github.com/NordicESMHub/NEGI-Abisko-2019/labels/question

[link_pullrequest]: https://help.github.com/articles/creating-a-pull-request/
[link_fork]: https://help.github.com/articles/fork-a-repo/
[link_pushpullblog]: https://www.igvita.com/2011/12/19/dont-push-your-pull-requests/
[link_updateupstreamwiki]: https://help.github.com/articles/syncing-a-fork/
[link_branches]: https://help.github.com/articles/creating-and-deleting-branches-within-your-repository/

[link_drafts]: https://help.github.com/articles/about-pull-requests/#draft-pull-requests

[link_contributors]: https://github.com/NordicESMHub/NEGI-Abisko-2019/graphs/contributors
[link_stemmrolemodels]: https://github.com/KirstieJane/STEMMRoleModels
[link_jupyterbook]: https://github.com/jupyter/jupyter-book
