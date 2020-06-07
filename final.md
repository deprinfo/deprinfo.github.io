---
layout: default
---

# [](#finalnotes)Deprinfo Final Notes

## [](#background)Background

It is quite common to see a website asking you to create an account to use their service. A lot of these websites offer an option to sign in using Google or Facebook in order to make the process of account creation more streamlined and easier. This is benefitial for the user as well as it helps the user to remember one less username and password for a website. 

However, most of these services asked for more permissions than they actually require for the purpose of their service. It was noticed that a lot of times the user could turn off certain permissions and the webiste would still allow the user to signup/login as expected without giving away more permissions. 

## [](#goal)Goal

Our goal for this project was to be able to identify websites and the permissions that they asked for in order for the user to sign up and determine the smallest set of required permissions without which signup/login would fail. All this information would then be useful to the user through a plugin that would be able to tell the user the permissions that are not required whenever they tried to login into a previously cataloged website. 

## [](#steps)Steps Taken

In order to collect relevant information and provide user attention to the permissions we had published a plugin that would keep track of the permissions provided to certain websites. We also did a user study using [Amazon Mechanical Turk](https://www.mturk.com/). Using this service, over a period of couple months we collected information from various users sharing voluntarily information regarding the permissions they provided to popular websites and the success and failure rate of login. This was an important step to identify what permissions eventhough not necessary for a account to function properly would stop a registration request to fail. 

## [](#status)Status

This project, however, was closed since providers such as Facebook and Google have implemented a higher privacy standard that stops websites from asking unnecessary permissions making the plugin obsolete. The reason for these elevated privacy standard was due to various recent law changes such as CCPA, GDPR etc. 