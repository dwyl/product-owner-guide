# Product Owner Guide

A rough guide for those who are product owners on a dwyl project.

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

So if you come across a bug :bug: remember to include lots of detail to help your team replicate it. Think: what pathway did I take to get to the error? ie. who was I logged in as? what was I trying to do when it happened? What device or browser was I using? e.g. Internet Explorer v10 or iPhone 6 view. Then take a screenshot of the bug and put it all into an issue to be fixed :wrench: :sparkles:.
