# Product Owner Guide

A rough guide for those who are product owners on a dwyl project.

## What is a Product Owner?

**A Product Owner (PO)** is someone who represents the views and needs of the
target audience, stakeholders and the business they represent in agile scrum
methodology. They must understand and communicate the vision of the product to
the rest of the team.

They are the liaison between customers and the development team. This means that
they are responsible for working with stakeholders and user groups to determine
their needs. Then through collaboration with the Scrum Master and developer team
they prioritise and discuss these ideas moulding them into features to be built.

**PO Responsibilities:**
1. Owner and creator of the product backlog* :crown:
2. Adding new features to the backlog. :new:
3. Describing the user-persona(s) in as much detail as possible to make the
"pain" they feel _real_ (_especially useful when the team is remote and don't
often meet with the end-users_) 📝
4. Clearly define, understand and _empathise_ with the end-user. 👩 💡
5. Approving or critiquing development work for release. :white_check_mark:
6. Involving customers or users and getting their feedback to continuously shape
the product development. :+1: :thumbsdown:
7. Maintaining and _updating_ the backlog: adjusting the features and _priority_
as needed after each sprint or iteration. :small_red_triangle: :small_red_triangle_down:
8. Attach a _business_ or _customer_ value to each story/task in the backlog to
ensure that we are building features that are genuinely wanted/needed by users. 💸
9. Have a clear picture of "competitors" and the "market" for similar
products/service to avoid "re-inventing" something that already exists! (_i.e.
  don't try to replace App/Site ABC, you are wasting your time! instead find
  something they aren't doing or are doing poorly and focus on that!_) 🔍
10. Be familiar with _existing_ UX/UI through personal use of other/existing
Apps/services to know what can be done/re-used. ♻️
11. Trust the expertise of your technical team on matters of technical
importance (although feel free to ask them to try to learn more about _why_
  certain things matter when you may not be familiar with what they are) :punch:
12. Note, in order to be able to perform these responsibilities it's important
that POs have been given the authority and means necessary to complete them. :muscle:

* product backlog: a prioritised features list for the product found on github.

See: https://github.com/dwyl/process-handbook/issues/61, linked to #5

## Template for making an issue

**The 3 components you should include when creating an issue are:**

1. A User story
2. Acceptance Criteria
3. A screenshot of a mock-up or a bug on the site (where possible)

Followed by... any other useful/ relevant information for completing the issue.

### User Stories

A user story is a phrase which describes the what, why and who is it for of each
issue. To write one complete the following three starters:

**As...** a team member - **WHO**
**I want to...** see a user story on every issue I read  - **WHAT**
**so that...** I know the context in which the issue is set to help me understand
it better - **WHY**

**Here's another example:**

**As** someone in need of a bin
**I want to** be able to filter on the online shopping site by 'lid type'
**So that** I can find a bin that closes securely to stop mice getting into my
bin 🐭 ❌ 🗑 🧀

### Acceptance Criteria

Acceptance criteria are checkboxes that a developer knows they need to complete
before that issue can be considered 'done'. They are the points against which
the issue will be tested.

### A screenshot or mock up of a new design
A picture which illustrates what the issue should be creating or a screenshot of
an existing page showing where a bug is occurring. Remember to include mock ups
of both mobile and desktop views.

<img src="https://user-images.githubusercontent.com/16775804/34988677-617ac428-fab7-11e7-9f07-3c47a84d2ab5.png" width=150px />

### Real world exemplar issue

The following issue has a clearly defined user story and detailed acceptance
criteria:

![image](https://user-images.githubusercontent.com/16775804/35054346-3732eba8-fba4-11e7-8cce-4f239e45104b.png)

It doesn't have mock-ups/screenshots but note that the second checkbox says the
delete button should follow existing conventions set out in the style guide.

## Responsiveness standards for testing

When you begin a project it is likely you will discuss target audience and
device compatibility. These conversations will cover the important behaviours
of your customers including browser type, device type and any other specific
compatibility requirements e.g. accessibility.

Generally speaking most projects will focus on being mobile, tablet and desktop
friendly and for these measures we use the inbuilt device sizes provided by
browsers to test the application. These devices sizes cover a range of
dimensions and a variety of the most popular iOS and android devices. Testing
using these devices is not only capturing a large part of the user market but
it is also a shared metric and easy way to spot and communicate bugs across a team.

E.g. 'The subheading on the landing page is currently obscured on iPhone 6'
gives the development team a quickly understandable and recognisable way of
finding and fixing a given problem.

### How to test using standard device sizes
To open 'Inspect' right click on your computer with your browser open or if you
are a mac user press control and then click. This menu should appear, then click
on 'Inspect':
<img src="https://user-images.githubusercontent.com/16775804/34882711-54e6a642-f7af-11e7-9044-509708116fea.png" width=150px />

Now your browser has 'Inspect' or 'Dev tools' open you should make sure you are
using the device mode. Look for this symbol in the menu:
![image](https://user-images.githubusercontent.com/16775804/34883357-56336aec-f7b1-11e7-8ed3-6cbf3a0483e5.png)

<img src="https://user-images.githubusercontent.com/16775804/34882755-7633219a-f7af-11e7-92ef-5064cbecf73f.png" width=250px />

If the symbol is orange then you're already in device mode. If it is not, then
click on it so it turns orange. Next, look for this bar and click on the
left-hand dropdown menu to select a device:

<img src="https://user-images.githubusercontent.com/16775804/34882773-827408e8-f7af-11e7-80a7-626d27409c9e.png" width=450px />

<img src="https://user-images.githubusercontent.com/16775804/34882785-890093ac-f7af-11e7-9c65-33bd9399ebca.png" width=130px />

This list is an automatically updated list contained within your browser. It
contains the most popular standard devices sizes for you to test your site against.

Your page will now display according to the dimensions of the device you have
selected:
E.g. iPhone 7:

![image](https://user-images.githubusercontent.com/16775804/34883575-d85ae5ea-f7b1-11e7-8b26-03e6df9c8a12.png)

iPad:
<img src="https://user-images.githubusercontent.com/16775804/34883587-e7b8c46c-f7b1-11e7-8f7a-035b0e29eded.png" width=500px />

So if you come across a bug :bug: remember to include lots of detail to help
your team replicate it. Think:

- What pathway did I take to get to the error? ie. who was I logged in as?
:busts_in_silhouette: what was I trying to do when it happened?
- What device or browser was I using? :iphone::computer: e.g. Internet Explorer
v10 or iPhone 6 view.

Then take a screenshot of the bug and put it all into an issue to be fixed
:wrench: :sparkles:.

## Timing demos and deployments

The PO and the Scrum Master liaise with one another to find a time and day suitable for sprint demos and deployments. We do however recommend the following on all occasions:
- Don't deploy on a Friday, if anything breaks it may not be discovered until after the weekend or may need working on over the weekend.
- As generally we deploy after a sprint demo, for this reason we do not start 10 day sprints on Mondays as this will inevitably end with a demo and deployment on a Friday.
- To avoid bugs disrupting sprint demos the team will demo the work they completed up until a few hours before the demo. If you continue deploying to staging up until the demo you drastically increase the likelihood of a last minute rush or a semi-complete feature causing a bug and disrupting the demo.

For these reasons it is important that the PO and Scrum Master set up demos in advance so all of these factors can be taken into consideration.

## What is Technical Debt?

[Technical debt](https://en.wikipedia.org/wiki/Technical_debt) is the cost to
"re-work" a feature (or entire app) because it was rushed the first time it was built.

Think of Technical Debt like a "loan shark" for your project, if you take
"shortcuts" to implement a feature quickly (e.g: by skipping tests) you will
pay for it later and usually with "interest".

It may feel abstract and hard to understand but it is crucially not ignored.

In other words, whilst in agile methodology we often talk about iterative growth
and only building what is necessary, this should not mean that corners are cut
in the short term that will inevitably end up with greater costs of time and
resources later down the line.

If technical debt does accrue it is worth reducing it systematically. If left
ignored, as other development continues, the debt will grow as the new work
added will also need reworking when the debt is finally addressed. Just like
how financial debt grows when untouched because of interest.

Note: this is related but distinct from retrospective changes that can be made
to a project to make it more performant/relevant/consistent but that could not
have been known/foreseen at the time the code was written.

## Optimal Team Size - Brooks' Law

Sometimes when a deadline is nearing or timing is looking tight then it can
feel tempting to add more people to the team with the aim of getting things done
faster. However it is worth considering Brooks' Law which suggests that
effectiveness/efficiency can decline with too many people. How can this be the
case?

Bringing on new team members has costs as well as benefits:

- Time to learn and get up-to-speed with context/codebase
- Existing (productive) team members time occupied by reviewing new (far less
  productive) team members work at the expense of getting on with their own. i.e.
  output is cut in half not "doubled"!
- Overlap and "stepping on toes" where features are not isolated enough leads to
merge conflicts (where one person's work can "undo" someone else's) which can
take up way more time.

The best time for the whole team to start is at the "ideation" or "Design Sprint"
stage so that no time is wasted on this on-boarding later on.

Further reading: https://en.wikipedia.org/wiki/Brooks%27s_law

## The lifecycle of an issue

At dwyl we use github labels to help indicate the type, duration and status of an
issue. The following image outlines the lifecycle of an issue using labels. In
this example there are 3 actors, the Product Owner (PO), the dev team
(Scrum Master and developers) and in this case the developer who has completed
the issue: 'Cleop'.

<img src="https://user-images.githubusercontent.com/16775804/35041656-65100b90-fb7d-11e7-8139-15916e7325f7.png" width=350px />

To learn more about our contributing process see: https://github.com/dwyl/contributing.

## When to create a new issue when dealing with bugs 🐛  and enhancements :ribbon:

An existing issue is put into `please-test` as the team have finished working on
it and all of the acceptance criteria have been fulfilled. You, the product
owner test the issue and on reflection you decide that you think the designs
would look better with a couple of tweaks - maybe removing the bold on the
title, making the logo a bit bigger and changing the copy by a few words. What
do you do in this situation?

These changes might relate to the changes made in the issue but if they are
fundamentally not what you asked for in the first place or not what was shown on
the mock-up then they belong in a new issue **NOT** as a 'bug' or as a request
at the bottom of the existing issue. Small as they seem, these issues are
enhancements and new scope and they should be dealt with separately.

### Why?
- These kinds of small changes add up, especially if you change your mind a couple
of times or if there are a few across multiple issues.
- The title of the issue may no longer reflect the content inside making it
more complicated for people to follow the chains of conversations.
- The extra changes will impact the developer's initial time estimate
which is damaging for their accuracy when trying to estimate how long issues
will take.
- The extra scope may push something else out of the sprint. Had you prioritised
the changes as a new issue you may not have put this tweak above the other issues
in the sprint.

**Here's an example where a new issue should have been made:**

![image](https://user-images.githubusercontent.com/16775804/35000346-12827d14-fadc-11e7-97da-3921382b2dc2.png)

### So what changes count as bugs :bug: then?
Bugs are places where the acceptance criteria has not been met :negative_squared_cross_mark: :

e.g. you were meant to change the font size across all titles on this page but
you missed out the last title - please can you change it?

I submitted the form but I didn't receive an email notification as specified in
the acceptance criteria. Please can you fix whatever is stopping the email from
being sent?
