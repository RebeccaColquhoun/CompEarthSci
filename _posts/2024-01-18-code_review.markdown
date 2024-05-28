---
layout: post
title:  "Code review"
date:   2024-01-18 12:00:00 +0000
categories: meetings
---
We sometimes spend time thinking about (and doing) code review. This document contains some guidance for this.
I expect we'll want to update this as we go.

## Tips
Pick a small (maybe 100 lines of code) function or handful of functions to share with your reviewer. Have the reviewer 
"flag up those things that make the code difficult to read, debug, reuse and extend."
A good way to approach this as a reviewer is to ask (open) questions ("why have you done this like that?",
"is there a different way?"). 
[The Oxford Code Review network guidelines for reviewers](https://github.com/OxfordCodeReviewNet/forum/blob/master/guidelines_for_reviewers.md)
is probably a good place to look for more specific ideas. Try to reflect on what you are learning more generally beyond the few lines of code
that is being reviewed.

Annother approach is to think about the larger scale. What is missing from the code or the whole package. The
[review checklist from JOSS](https://joss.readthedocs.io/en/latest/review_checklist.html) could be a good place to start.


## Sources and links
* [Code reviews in academia](https://tlestang.github.io/blog/code-review.html) - blog from Thibault Lestang, February 2021
* [Treat your research code with a code review](https://www.software.ac.uk/blog/treat-your-research-code-code-review) - SSI blog, March 2022.
* [Identifying and overcoming obstacles to adopting code review](https://www.software.ac.uk/blog/identifying-and-overcoming-obstacles-adopting-code-review) - SSI blog (from CW22), August 2022.
* [Guidelines for reviewers](https://github.com/OxfordCodeReviewNet/forum/blob/master/guidelines_for_reviewers.md) - from the Oxford Code Review network
* [Code Review as a Simple Trick to Enhance Reproducibility, Accelerate Learning, and Improve the Quality of Your Team’s Research](https://academic.oup.com/aje/article/190/10/2172/6218064) - Vable et al. (2021) American Journal of Epidemiology
* [Implementing code review in the scientific workflow: Insights from ecology and evolutionary biology](https://onlinelibrary.wiley.com/doi/full/10.1111/jeb.14230) - Ivimey-Cook et al. (2023) Journal of Evolutionary Biology
* [Review checklist from JOSS](https://joss.readthedocs.io/en/latest/review_checklist.html)
* It is very common to feel anxious about giving and receiving code reviews. This [workbook](https://developer-success-lab.gitbook.io) outlines some of the reasons and mitigate for this.
