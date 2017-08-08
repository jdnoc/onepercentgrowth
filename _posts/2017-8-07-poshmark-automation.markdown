---
layout: post
title: "Poshmark Share Automation"
date: 2017-8-07
tags: poshmark javascript
---

This is an older project that I worked on for my wife and her friends. They all sell on posh, and complained about the need to share every individual item in their closet if they wanted to share them all.

Not any more. These bookmarklets allow you to share all of your listings with a push of a button.

Share all of your available items instantly!

### Drag These Links to your Bookmarks Bar in Chrome
## [Share to Followers](javascript: function shareButton() {    buttons[i - 1].click(), i > 0 && setTimeout(function () {        shareToParty()    }, 3000)}function shareToParty() {    var sharebutton = document.querySelector(".pm-followers-share-link.grey");    sharebutton.click(), i > 0 && (setTimeout(function () {        shareButton()    }, 3000), i--, i--)}var buttons = document.querySelectorAll(".icon.share-gray"),    i = buttons.length;setTimeout(function () {    shareButton()}, 3000);) | [Share to Party](javascript: function shareButton() {    buttons[i - 1].click(), i > 0 && setTimeout(function () {        shareToParty()    }, 3000)}function shareToParty() {    var sharebutton = document.querySelector(".pm-party-share-link.grey");    sharebutton.click(), i > 0 && (setTimeout(function () {        shareButton()    }, 3000), i--, i--)}var buttons = document.querySelectorAll(".share"),    i = buttons.length;setTimeout(function () {    shareButton()}, 3000);)

Instructions for use:
* Use Google Chrome
* Drag the above links into the bookmarks toolbar (you might have to make it show)
* Go to your closet on Poshmark (closet is one of the options in the top right corner)
* In the sorting options, set the “Availability” tab to “Available”
* Scroll all the way to the bottom of the page (to load all of the items)
* Click the desired button (Followers or Party, or both! One button at a time.)
* Wait for it…
* Profit! $

The party button won’t work if there isn’t a party going on.

Also, if you get the *Are you a robot?* message, don’t panic. Just follow the instructions and it will go away. If you don’t refresh the page, you can share all of your items again without losing the order in your closet.

Also also, it says in the Poshmark Community Guidelines, **Do not use programs or other forms of automation to participate on Poshmark. This includes, but is not limited to liking, sharing, following, and unfollowing.” At the end, it says “Should we find your account to be in violation of any of the above, we may send you an email or take permanent or temporary action on your account privileges.**

AKA Use at your own risk!

Jordan
