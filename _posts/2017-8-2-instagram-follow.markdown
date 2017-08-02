---
layout: post
title:  "Instagram Follow Bookmarklet"
date:   2017-8-2
categories: instagram growth
---

## Instagram Auto-Follow / Auto-Unfollow Bookmarklets

### [Follow (20s)](javascript:function followButton(){var x=document.getElementsByClassName("_4gt3b"),buttons=document.querySelectorAll("._ah57t._84y62._i46jh._rmr7s"),i=buttons.length;buttons[buttons.length-i+1].click(),x[0].scrollTop+=106}var x=document.getElementsByClassName("_4gt3b"),buttons=document.querySelectorAll("._ah57t._84y62._i46jh._rmr7s"),i=buttons.length;buttons[buttons.length-i+1].click(),x[0].scrollTop+=106,setInterval(followButton,2e4);)

### [Unfollow (20s)](javascript:function followButton(){var x=document.getElementsByClassName("_4gt3b"),buttons=document.querySelectorAll("._ah57t._6y2ah._i46jh._rmr7s"),i=buttons.length;buttons[buttons.length-i+1].click(),x[0].scrollTop+=106}var x=document.getElementsByClassName("_4gt3b"),buttons=document.querySelectorAll("._ah57t._6y2ah._i46jh._rmr7s"),i=buttons.length;buttons[buttons.length-i+1].click(),x[0].scrollTop+=106,setInterval(followButton,2e4);)

👆 Drag these links to your bookmarks bar! (Google Chrome Only)

## How To Use

1. Go to [Instagram](https://instagram.com).
2. Go to a page where you want to follow the followers.
3. Click the "<<some number>> Followers" button. You'll see the list of followers pop up.
4. Click the bookmarklet button you want.
5. Profit $$

You'll notice it scrolls a little bit. If you scroll up - you'll see that it followed / unfollowed someone (based on the one you picked).

If it's scrolling, it's working. No worries. Or just scroll up to check. But make sure you scroll back down when you're done checking.

## Tips And Tricks

It clicks every 20s. Which is 30 follows every 10 minutes. Which is 180 follows an hour. Which is4320 follows a day if you let
it run all day. Obviously, you can only follow less than 7500 people, so you'll have to unfollow eventually.

This button isn't very smart. It just looks for 'follow' or 'following' buttons on the page, clicks them,
and scrolls down a little bit after it clicks. 

The reason it scrolls is so new buttons can come up. If no new buttons come up, the script can't do anything.

Now, it should keep scrolling, so even if you hit a patch of people that you already follow/need to unfollow, then 
you should be able to get passed them eventually.

Sometimes you'll notice that it follows the second person and not the first in the list, that's because it takes into account
the follow/following button on the account that you are taking followers from.

