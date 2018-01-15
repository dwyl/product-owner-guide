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

*product backlog: a prioritised features list for the product found on github.

### Responsiveness standards for testing

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

#### How to test using standard device sizes
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
