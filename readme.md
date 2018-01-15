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

### What is Technical Debt?

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

### Optimal Team Size - Brooks' Law

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
