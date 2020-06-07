---
layout: default
---

It is quite common nowadays to see a website asking you to create an account to use their service. For example Spotify, Pandora or less famous ones like https://iconsflow.com.  Most of these websites/web services allow you to log in through facebook/google so that it is easy for you and you need not remember yet another password. This is amazing, we always prefer this form of login/signup.

Similar to us, If you also use facebook or google to login, have you ever wondered how much of your information from facebook can be accessible by these services? This information could be really sensitive like: Your friend's list, your groups, your posts, birthday, interested in..so on and so forth.

<b>
This project has been closed. Please visit the [this](./final.md) to read about final notes. 
</b>


# [](#problem)Problem
To get a sense of it, login to your facebook, go to `Settings` -> `Apps and websites'.
Here you can see all the *Active* apps that are using facebook to access your information:

<img src="/assets/images/allapps.png" 
			class='hidden-xs hidden-sm' style='vertical-align: center; ' />
			
You can click on the `View and edit` button to see the exact information, the corresponding web service is accessing, for Instance,

<img src="/assets/images/spotifyperm.jpeg" 
			class='hidden-xs hidden-sm' style='vertical-align: center; ' />

Here, Spotify can access friends list, date of birth, email address, home town.
I don't know why Spotify needs my home town or date of birth or friends list? 

Note that, you can disable these permissions. Actually, my Spotify works fine when I disabled all the permissions. This could be annoying if you have a lot of apps and you don't know which information is needed for the service to work.

# [](#solution)Solution

This could be annoying if you have a lot of apps and you don't know which information is needed for the service to work. To make it easy, we created a small Chrome and Firefox extension. This extension helps you to selectively prevent one or more app to access your private information:

<img src="/assets/images/facebookblock.png" 
			class='hidden-xs hidden-sm' style='vertical-align: center; ' />

You can find all the instructions [here](/usage.md).

We are also conducting a study to understand the extent of this problem. For which, our extension anonymously collects your app names and private information requested by each app *without any of your information*. We even hash your user id to make sure that there is no way to identify you.
For instance, for the above spotify app, our extension will collect the following information:
```
Spotify, fl, dob, ht, ea
```
That's it, it just collects the name of the app and the _name_ of the private information.

# [](#people)People

*   [Francesco Marcantoni](https://seclab.cs.ucsb.edu/academic/people/)
*   [Aravind Machiry](https://machiry.github.io/)
*   [Hojjat Aghakhani](http://hojjat.me/)
