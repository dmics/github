# Constructing Your Digital Identity with GitHub

#### Author: Taylor Arnold, Math & Computer Science, University of Richmond
------

GitHub is a web platform for archiving collections of code and
other materials into what are known as *repositories*. It is 
completely free to use for open source projects developed out
in the public. Paid accounts given access to private repositories
that can contain personal or closed-source materials. You are
currently looking at the repository named **user-template**. In
addition to providing tools for collaborative programming, GitHub
also provides a system for hosting static websites. These are known
collectively as *GitHub pages*. This tutorial will set-up a basic
GitHub pages that can serve as your digital identity. The tutorial
assumes that you already have signed up for a free GitHub account.
If not, go to [https://github.com/](https://github.com/) and create
and validate your username.

The end goal of the tutorial here is to create a website located 
at the following URL:

- https://[USERNAME].github.io/

With your username filled in for *[USERNAME]*. There are two typical
ways that this website can be used:

1. It can redirect to another page, such as a homepage at your
current place of study or employment, or
2. You can host a full-blown website on GitHub.

This tutorial will set-up the first option, by default redirecting to
your GitHub user page. To create a custom website, first follow the
instructions here and then see the tutorial on setting up a 
Jekyll website [here](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/).

## Step 1: Clone repository and edit settings

The first step is to click on the "Fork" button in this repository. It
will make a copy under your username that you can control.

Next, click on the Settings tab (in your fork). Rename the repository
**[USERNAME].github.io** with your exact username filled in.

Then, go back into the Setting page and scroll to the GitHub Pages
section. Select "master Branch" under Source. This will make your repostiory
show up as a website. It can sometimes take a while (upwards of 30 minutes or
more) for this first push to work, so that is why we are starting here.
There should be a link on the settings page once you do this pointing to your
new website.

## Step 2: Edit index.html

While waiting for the GitHub pages to set-up, go to the repository and edit
the file *index.html*. To do this, first click on the file and then click
on the pencil in the upper right-hand corner of the inner window (next to the
trashcan symbol). You will see three link on the page that all point to
the link **https://github.com/USERNAME**. Replace **USERNAME** with your 
GitHub username and then hit to green "Commit changes" button at the bottom
of the page. If you would like to redirect to a different website, you can
fill this site instead. Make sure that all three instances of the website
are the same.

## Step 3: Edit GitHub profile

If you are using your GitHub website as the location to redirect to, you
will want to fill out your user page. Go the [GitHub profile page](https://github.com/settings/profile)
and add a photo and some basic information. Make sure to save your changes.

## Step 4: Test

Finally, we can test that your page works by going to the website

- https://[USERNAME].github.io/

With your username filled in. If it says that no page is found, this may
be due to the GitHub servers not updating your website yet. Be patient as
it should appear with the first hour after your the first time you publish
it. If you get a "404 Page not found" this is likely due to not correctly
changing and saving the *index.html* file. Verify that you completed step
2 correctly. 

## Step 5: Share

You now have a digital identity that you can share with others that is
not tied to your place of study or employment. At any point you can 
redirect this link to your current location and contact information. If
you do not have a personal website to link to but want more than just
the basic information on your GitHub page, follow the Jekyll tutorial
[here](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/)
for setting up a complete website entirely hosted on GitHub. You can
see an example of this on my GitHub pages:

- [http://statsmaths.github.io/](http://statsmaths.github.io/)

Otherwise, share and enjoy!

