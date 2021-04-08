---
layout: post
title:  "Software Engineering and Sinatra"
---

## Overview

For my first year in university (2019-2020) there was a module that required me to work in a team of 7, myself included. The goal of the project was to build a product using AGILE that our "clients" wanted. 

The full project can be seen openly on GitHub [here](https://github.com/SamTheDude/COM1001-Bookmark-Site) with instructions about how to use the project in the README. I wouldn't recommend use though, mainly because it is a bit crap.

### Technologies Used

- Ruby
    - Sinatra
    - Capybara
    - Cucumber
    - Rake
- SQL (sqlite3)
- Git
- GitLab
- HTML
- CSS
- Javascript

## Evaluation

This is one of those projects that I hated to no end while doing it, but looking back it did teach me a few things:

*Note: I wrote a lot of stuff, just read the headers if you are bored.*

#### Take Your Time Planning a Database

Before this the most complex database I had worked on was for my A-level project, for other projects I hadn't needed to build something as complicated or had made use of someone elses' code. 

For this project one team member built most of the database but we didn't spend nearly enough time checking the database structure at the start and near the end we made about 4 different very forseeable alterations to the database and then all the underlying code that cost us a lot of time.

#### End to End Testing is Amazing

Prior to this I hadn't used any end to end testing methods and had gotten by using unit testing of models, in fact for my A-level project none of the system was even remotely tested. This was when I realised the power of being able to test if the system still worked without having to run all the tests manually each time you merged a branch.

#### Proper Git Practice is Important

When we began I let the project run wild in terms of git figuring that teaching people in the project to use proper merge requests and alike would be far more effort than it was worth. I did not account for how long people like to go between commits, several times people would push 3-4 commits from the course of several days at the end and then have hell to deal with in terms of merge conflicts. This became such a hellish nightmare and I was fixing the project more than I was actually working on it. Do the proper workflows in all cases or you will get burnt by merge conflicts and failing tests.

### Conclusion

Good project all round, getting experience with using git and Gitlab in a medium-sized team project was a first, I just wish I'd been able to make the product a little better in the end.