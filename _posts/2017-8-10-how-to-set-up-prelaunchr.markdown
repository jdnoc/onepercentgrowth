---
layout: post
title: "How To Set Up Prelaunchr In Heroku"
date: 2017-08-10
tags: heroku prelaunchr email
---

This is relatively easy to set up. It's just a matter of:

1. Forking the [Prelaunchr Github Repo](https://github.com/harrystech/prelaunchr)
2. Making a Heroku Account / making a new project
3. Under the 'Deploy' Tab - Link Your Github
4. Link the cloned repo
5. Deploy the master branch
6. In the 'More' Menu (Top Right) - Run Console
7. Type `heroku run rake db:migrate` (Heroku Run is autofilled)
8. Go to your deployed app! Should be https://*project-name*.herokuapp.com

I'm using this for my Blacklet launch to get more emails.
