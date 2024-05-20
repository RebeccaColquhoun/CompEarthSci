---
layout: post
title:  "Making scientific software public"
date:   2024-05-16 15:00:00 +0100
categories: meetings
---
In this meeting we discussed the reasons for making scientific software public alongside the reasons why we may not want to do this. We then briefly looked at the processes that we can use. The post outlines some of the discussion and links to some useful material, and are based on my notes - *Andrew Walker*.

There is a lot of material and advice available on *how* to make software public, outlining various "best practices" (e.g. do everything in this [top five](https://www.software.ac.uk/blog/top-five-donts-software-development) guide), but one of the challanges is knowing when to stop. Linking the hows and whys may help.

## Why & why not?

We could think of a wide range of reasons why we may be motivated to make our software public:

* We want to allow others to make progress by building on, or using, our work.
* We want to develop collaborations.
* We are publishing a paper and we want the work to be reproducable.
* We are publishing a paper and the publisher / editor / reviewer demands it.
* Our funder or institution demands it.
* We are seeking credit for the work involved in creating the software.
* It will make it easer to publish some future paper or software.
* We want to demonstrate that we can create software.
* Our research group / community considers this standard practice.
* We want to influence the practice of our research group or community.

There was a similar list of reasons why we may hesitate to make software public:

* There is additional work and thus an opportunity cost.
* Others may see our mistakes.
* We don't think our software is good enough / significant enough.
* We may get scooped on future work.
* Our research group / community does not do this as standard.
* Our funders or institution may prevent it.
* There may be a commercial reason not to publish.
* There may be additional work to support / fix the software in future.

## How?
One principle we can apply in approaching the process of releasing software is to apply methods that maximise the chance that we get what we want while minimising the reasons we hesitate to release the software. We can use this approach to choose which of the following things to do or not do. However you proceed, it helps to have your software under some kind of version control (and I assume you are using github below).

* Contibute to an existing project or create your own? If you choose to contribute to an existing project many of the decisions will have been made already, you "just" have to follow the norms of the project. It's a good idea to make a conscious choice.
* Choose and add a license. We should probably always do this as early as possible in the process of writing code. Github has some useful tools to help [add license text](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository) and [choosealicense.com](https://choosealicense.com/) is a useful resource. You may need to discuss this with colaborators.
* Depending on why you want to make the software available, there are different ways to link the software to something that can be cited. A starting point is to make a version control repository public but that doesn't make the software easy to cite. Better choices are to make a 'release' and tie this to a [DOI from Zenodo](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content), to describe the software in a paper that focusses on the science application (and ask people to cite that), or to release a paper dedicated to the software (e.g. in [JOSS](https://joss.theoj.org/) or [Computers & Geosciences](https://www.sciencedirect.com/journal/computers-and-geosciences)).
* Add a [citation file](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-citation-files) to maximise the chance of gaining credit.
* If you are trying to build a collaborations, think about adding a [code of conduct](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-code-of-conduct-to-your-project)
* If you think you will change the code in the future, or you want some assurance around correctness, include tests. Automate the running of tests when the code changes.
* It can help to get somebody else to look at your code - maybe in one of our code review sessions.
* If you want to gain users or collaborators, adding good documentation can help. This could be a simple readme file, or it could be much more extensive. This [blog post](https://www.software.ac.uk/blog/what-are-best-practices-research-software-documentation) has some good ideas and I find these four areas of  [tutorials, how-to guides, technical reference and explanation](https://docs.divio.com/documentation-system/) helpful.

We could spend whole sessions discussing many of these ideas in more detail, and I'm happy to discuss individual cases as needed.
